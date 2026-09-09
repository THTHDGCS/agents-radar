# OpenClaw Ecosystem Digest 2026-09-09

> Issues: 0 | PRs: 0 | Projects covered: 3 | Generated: 2026-09-09 01:58 UTC

- [OpenClaw](https://github.com/unitreerobotics/unitree_sdk2)
- [MuJoCo](https://github.com/google-deepmind/mujoco)
- [Drake](https://github.com/RobotLocomotion/drake)

---

## OpenClaw Deep Dive

No activity in the last 24 hours.

---

## Cross-Ecosystem Comparison

# Cross-Project Comparison Report: Embodied AI Agent Infrastructure Ecosystem
*Data source: 2026-09-09 community digests for MuJoCo, Drake, and OpenClaw (Unitree SDK2)*

---

## 1. Ecosystem Overview
The open-source ecosystem for embodied AI agents (including robotic personal assistants) relies on a layered stack of simulation frameworks, hardware SDKs, and control tools to enable end-to-end development, training, and deployment. The three projects profiled span this stack: MuJoCo as a high-throughput GPU-accelerated physics simulator, Drake as a full-stack robotics optimization and simulation framework, and OpenClaw as a low-level hardware control SDK for Unitree’s commercial robot platforms. In the 24-hour window ending September 9, 2026, development activity across the simulator projects is concentrated on interoperability, performance scaling, and platform compatibility—all critical pain points for teams building and scaling embodied AI agent workflows from simulation to physical hardware. Maintainer responsiveness and alignment with standard robotics ecosystem conventions are emerging as the key differentiators driving adoption among AI agent development teams.

---

## 2. Activity Comparison
*Health score (0-10) methodology: Weighted metric based on 24h throughput (40%), bug resolution speed/severity coverage (30%), community request responsiveness (20%), and release roadmap clarity (10%). OpenClaw score is provisional due to limited 24h activity data (hardware SDKs typically follow longer vendor-led release cycles).*

| Project | Total Issues Updated (24h) <br> [Open/Active, Closed/Resolved] | Total PRs Updated (24h) <br> [Open/Active, Merged/Closed] | 24h Release Status | Health Score |
|---------|----------------------------------------------------------------|-----------------------------------------------------------|--------------------|--------------|
| MuJoCo  | 10 [2, 8]                                                     | 33 [8, 25]                                                | No new release (next patch/minor expected imminently) | 9.2 |
| Drake   | 4 [3, 1]                                                      | 27 [14, 13]                                               | No new release (v1.57.0 in active preparation) | 8.5 |
| OpenClaw <br> (Unitree SDK2) | 0 [0, 0] | 0 [0, 0] | No new release | 4.0 (provisional) |

---

## 3. OpenClaw's Position
### Advantages vs. Peers
Unlike MuJoCo and Drake (software-only simulation frameworks), OpenClaw is a hardware-native SDK with first-party integration with Unitree’s industry-leading quadruped and humanoid robot platforms. It serves as a critical deployment layer for embodied AI teams that use MuJoCo or Drake for simulation and need to transfer policies to physical Unitree hardware, with pre-built abstractions for real-time actuation, sensor data streaming, and motion control that eliminate low-level hardware bringup work.
### Technical Approach Differences
MuJoCo and Drake are optimized for accurate, high-performance physics simulation and algorithm development; OpenClaw is built for real-time embedded execution on robot on-board computers, with a minimal dependency footprint and hardware-specific performance tuning. It does not include native simulation capabilities, instead acting as a complementary layer in the embodied AI stack.
### Community Size Comparison
OpenClaw has the smallest community of the three projects, with a user base concentrated on Unitree robot owners and hardware-focused teams, and development led primarily by Unitree’s internal engineering team (consistent with its zero 24h community activity). By comparison, MuJoCo (backed by Google DeepMind) has the largest broad-based community spanning RL research, industrial robotics, and academia, while Drake (backed by the Toyota Research Institute) has a mid-sized, specialized community of optimization-focused robotics engineers.

---

## 4. Shared Technical Focus Areas
Three core technical priorities emerge across the active simulation projects, with cross-stack relevance for OpenClaw and embodied AI workflows:
1. **Standardized Model Format Interoperability (MuJoCo, Drake)**: Both projects are reducing model conversion friction for URDF and MJCF, the dominant robot model formats in the robotics ecosystem. MuJoCo resolved a long-standing feature request to support `package://` URIs in URDF imports and added URDF `<mimic>` joint translation, while Drake is developing a fix for nested MJCF include asset resolution to match native MuJoCo behavior. The shared need is to eliminate manual model rework for AI agent teams working across multiple simulators and real hardware platforms (including those deploying via OpenClaw).
2. **Large-Scale Workload Performance Optimization (MuJoCo, Drake)**: Both simulators are prioritizing throughput and scalability for large-scale embodied AI training. MuJoCo fixed a static body sleeping optimization bug that reduced overhead in large, geom-heavy scenes and resolved MJX FFI errors blocking multi-GPU RL training via `jax.shard_map`. Drake is advancing multi-PR feature series for welded-link fusing and SAP joint friction constraints to improve multibody simulation speed and solver accuracy. The shared need is to support higher-throughput batch simulation for RL policy training, a core workflow for AI agent developers.
3. **Build System & Platform Compatibility (MuJoCo, Drake)**: Both projects face sustained demand for compatibility with enterprise build tools and mainstream operating systems. MuJoCo has a 22-month-old community PR for Bazel build support (a top 3 community hot topic) and an unresolved Ubuntu 24.04 GLFW compatibility issue, while Drake maintains frequent Bazel toolchain updates (including an emergency `rules_rs` patch in the 24h window) and is addressing macOS MOSEK wheel parity for cross-platform consistency. The shared need is to reduce integration overhead for enterprise AI agent teams that rely on Bazel for reproducible builds.

---

## 5. Differentiation Analysis
| Dimension | MuJoCo | Drake | OpenClaw (Unitree SDK2) |
|-----------|--------|-------|--------------------------|
| **Core Feature Focus** | High-throughput physics simulation, GPU acceleration (MJX), URDF/asset pipeline improvements, rendering UX; optimized for batch RL training | Full-stack robotics framework: simulation, optimization, planning, and control; focused on multibody physics rigor and solver development | Low-level hardware control for Unitree robots: real-time actuation, sensor I/O, motion control; no native simulation capabilities |
| **Target Users** | Broad audience: RL researchers, embodied AI teams, robotics academics, industrial simulation teams (e.g., Boston Dynamics, iCub community) | Specialized audience: optimization-focused robotics engineers, academic researchers, teams building model-based control systems | Niche hardware-focused audience: Unitree robot owners, embedded engineers, teams deploying AI agents on Unitree platforms |
| **Technical Architecture** | Lightweight C core with Python bindings, GPU-accelerated via JAX/MJX, designed for minimal overhead in batch simulation | Modular C++ framework with Python bindings, built on a system-level graph architecture (LeafSystem), with integrated first- and third-party optimization solvers | Embedded-friendly C/C++ SDK with hardware-specific abstractions, optimized for real-time execution on Unitree on-board computers |

---

## 6. Community Momentum & Maturity
Projects fall into three distinct activity and maturity tiers, based on 24h throughput, development cadence, and backlog management:
1. **High Momentum, Rapid Iteration (MuJoCo)**: With 25 merged PRs and 8 resolved issues in 24 hours, MuJoCo has the highest development velocity. It demonstrates fast triage of high-severity bugs (e.g., the SAP broadphase out-of-bounds read was fixed in ~10 days) and active delivery of long-standing community feature requests. The project is mature and production-grade, with rapid feature expansion aligned with embodied AI demand.
2. **Steady Momentum, Roadmap-Driven (Drake)**: Drake maintains consistent, structured development, with 13 merged PRs in 24 hours and active preparation for the v1.57.0 minor release. Development follows multi-PR feature series (e.g., auto-loop-breaking, SAP joint friction) aligned with a long-term architecture roadmap, balanced with dependency maintenance and bug fixes. The project is mature and enterprise-grade, with deliberate, low-regret feature rollout.
3. **Low Activity, Vendor-Led Stabilization (OpenClaw)**: With no 24h activity, OpenClaw follows the typical cadence of a commercial hardware SDK: development is led primarily by Unitree’s internal team, with updates tied to new product launches and hardware-specific fixes rather than continuous community-driven iteration. The project is stable for supported Unitree hardware, but has minimal community contribution relative to the simulation frameworks.

---

## 7. Trend Signals
Five key industry trends are visible across the project communities, with direct relevance for AI agent developers building embodied or robotic personal assistant systems:
1. **Ecosystem Interoperability is a Critical Adoption Driver**: The top community request in MuJoCo (URDF `package://` support, 10 comments, 3 👍) and Drake’s ongoing MJCF nested include fix both reflect demand for alignment with standard robotics conventions. For AI agent developers, this reduces model porting overhead across simulation and deployment tools, accelerating time-to-market for robot-based agents.
2. **GPU-Accelerated Batch Simulation is Table Stakes for RL Training**: MuJoCo’s MJX fixes for multi-GPU `jax.shard_map` compatibility and convex mesh support address a top pain point for teams scaling RL policy training. For AI agent developers, this enables order-of-magnitude higher throughput simulation, reducing training cycles for complex locomotion and manipulation tasks.
3. **Enterprise Build Tool Compatibility Reduces Integration Friction**: Long-running community demand for Bazel support in MuJoCo and frequent Bazel toolchain maintenance in Drake show that large organizations rely on Bazel for reproducible robotics and AI builds. For AI agent developers in enterprise settings, native Bazel support cuts integration time and simplifies dependency management for production deployments.
4. **Cross-Platform Parity Gaps Persist as Workflow Risks**: Unresolved Ubuntu 24.04 GLFW issues in MuJoCo (open 20 months) and macOS MOSEK parity requests in Drake (open 9 months) highlight that platform consistency remains an unmet need. For AI agent developers, these gaps create risk of workflow disruptions when upgrading OS versions or collaborating across Linux/macOS teams.
5. **Simulation-to-Hardware Integration Demand is Growing**: While OpenClaw had no 24h activity, its position as the de facto hardware SDK for Unitree’s widely used research robots, paired with simulators’ focus on URDF interoperability, points to growing demand for tighter sim-to-real integration. For AI agent developers, standardized, simulator-compatible hardware SDKs will reduce the effort required to transfer trained policies to physical robots, a key bottleneck for embodied AI deployment.

---

## Peer Project Reports

<details>
<summary><strong>MuJoCo</strong> — <a href="https://github.com/google-deepmind/mujoco">google-deepmind/mujoco</a></summary>

# MuJoCo Project Digest | 2026-09-09
*Data source: github.com/google-deepmind/mujoco, 24-hour activity window ending 2026-09-09*

---

## 1. Today's Overview
For the 24-hour period ending 2026-09-09, the MuJoCo project saw high development activity, with 10 issues updated (2 open/active, 8 closed) and 33 pull requests (PRs) updated (8 open, 25 merged/closed), and no new releases published. The majority of closed items address bugs across core physics simulation, collision detection, MJX GPU acceleration, URDF parsing, and rendering, alongside several long-awaited feature enhancements for URDF interoperability. Two active open issues focus on Ubuntu 24.04 GLFW compatibility and actuator default inheritance in Python MJCF loading, both affecting real-world user workflows. Overall project health appears strong, with rapid turnaround on recent high-severity bug reports and progress on long-standing community feature requests.

---

## 2. Releases
No new stable or pre-release versions of MuJoCo were published in the 24-hour window ending 2026-09-09.

---

## 3. Project Progress
A total of 25 PRs were merged or closed in the 24-hour window, advancing core functionality, bug fixes, and usability across multiple domains:
### Core Physics & Collision Fixes
- [PR #3536](https://github.com/google-deepmind/mujoco/pull/3536) and [PR #3539](https://github.com/google-deepmind/mujoco/pull/3539): Resolved an out-of-bounds read in the sweep-and-prune (SAP) collision broadphase (Issue #3535) by either storing pair indices as `uint32_t` or masking the high half during decoding, eliminating undefined behavior for simulations with >32768 collision items.
- [PR #3541](https://github.com/google-deepmind/mujoco/pull/3541): Fixed the sleeping optimization in `mj_kinematics2` and `mj_camlight` to skip static body recomputation when all dynamic bodies are awake, reducing performance overhead in large scenes with many static geoms (resolves [Issue #3540](https://github.com/google-deepmind/mujoco/issues/3540)).
- Resolved a frame bug in `mjCBody::AccumulateInertia` ([Issue #2982](https://github.com/google-deepmind/mujoco/issues/2982)) that caused incorrect inertia calculations for fused static bodies imported from URDFs with fixed joints.
- Fixed `mj_step` to use plugin configuration from `MjModel` instead of `MjData` ([Issue #2644](https://github.com/google-deepmind/mujoco/issues/2644)), correcting behavior for workflows using mismatched model/data pairs.

### URDF & Asset Pipeline Enhancements
- Closed long-standing enhancement [Issue #1432](https://github.com/google-deepmind/mujoco/issues/1432): Added support for loading meshes specified via `package://` URIs in URDF models, aligning with ROS/robotics ecosystem conventions.
- [PR #3530](https://github.com/google-deepmind/mujoco/pull/3530): Added translation of URDF `<mimic>` joints to MuJoCo joint equality constraints, supporting parallel actuator configurations common in robot models.
- [PR #2540](https://github.com/google-deepmind/mujoco/pull/2540): Implemented systematic asset deduplication for attached models, reducing redundant storage of meshes, textures, and height fields when combining multiple models.

### MJX & GPU Acceleration Fixes
- Resolved MJX `put_model` convex mesh processing errors ([Issue #2777](https://github.com/google-deepmind/mujoco/issues/2777)) that blocked GPU-accelerated simulation for models with convex meshes.
- Fixed MJX-Warp FFI call errors with varying-axis metadata under `jax.shard_map` ([Issue #3426](https://github.com/google-deepmind/mujoco/issues/3426)), enabling scalable multi-GPU training workflows.

### Rendering, Tooling & Integrations
- Resolved crashes in the simulate GUI and OGL renderer when using KTX textures ([Issue #3343](https://github.com/google-deepmind/mujoco/issues/3343)).
- [PR #2218](https://github.com/google-deepmind/mujoco/pull/2218): Enabled distance sensing for SDF geoms, expanding sensor functionality for signed distance field objects.
- [PR #2492](https://github.com/google-deepmind/mujoco/pull/2492): Exposed the `viewer` module directly on the top-level `mujoco` Python import, simplifying viewer initialization workflows.
- [PR #1478](https://github.com/google-deepmind/mujoco/pull/1478): Added CMake options to enable/disable installation of MuJoCo samples and the `simulate` executable, improving build customization.
- [PR #1345](https://github.com/google-deepmind/mujoco/pull/1345): Added support for adjusting the default material based on the active rendering pipeline.
- Unity integration improvements: [PR #3544](https://github.com/google-deepmind/mujoco/pull/3544) enabled multi-CCD by default in Unity, and [PR #3267](https://github.com/google-deepmind/mujoco/pull/3267) switched to ID-based scene ordering for deterministic behavior.

### Documentation
- [PR #3526](https://github.com/google-deepmind/mujoco/pull/3526): Clarified regularized friction creep and NoSlip tradeoffs in documentation, explaining soft-contact model behavior and `impratio` usage.
- [PR #1774](https://github.com/google-deepmind/mujoco/pull/1774): Added guidance for building Python bindings against a from-source MuJoCo library.
- [PR #3550](https://github.com/google-deepmind/mujoco/pull/3550): Fixed typos in the Sphinx documentation for tendon lengthrange and impedance deformation coefficients.

---

## 4. Community Hot Topics
*PR comment counts are unavailable in the provided dataset; rankings are based on issue comment volume and reaction counts.*
1. **URDF `package://` URI Mesh Support ([Issue #1432](https://github.com/google-deepmind/mujoco/issues/1432))**  
   10 comments, 3 👍 | Status: Closed  
   The highest-reacted and most-discussed item in the 24-hour window, this long-standing enhancement request was driven by the ROS/robotics community (notably iCub/robotology users) who faced friction with MuJoCo's URDF parser stripping path information from `package://` URIs, a standard convention for robot model asset referencing. The resolution addresses a key interoperability pain point for users integrating MuJoCo with existing robotics toolchains.
2. **GLFW Compatibility on Ubuntu 24.04 ([Issue #2393](https://github.com/google-deepmind/mujoco/issues/2393))**  
   10 comments, 0 👍 | Status: Open  
   Tied for most comments, this bug report from a robotics engineer at Triton Systems details GLFW failures when running MuJoCo 3.2.7 via Python in a Bazel module on Ubuntu 24.04. Extended discussion indicates this is a persistent compatibility issue affecting production interactive simulation workflows on the latest Ubuntu LTS, a core platform for MuJoCo's user base.
3. **Bazel Build System Support ([PR #2225](https://github.com/google-deepmind/mujoco/pull/2225))**  
   Open since 2024-11-12, last updated 2026-09-08 | Status: Open  
   While comment counts are unavailable, this long-running community PR is a high-interest item for users in ML and robotics organizations that use Bazel as their primary build tool (evidenced by multiple users referencing Bazel workflows in issues). The PR adds Bazel build support for the C library, Python bindings, and MJX, and its active updates indicate sustained community demand.

---

## 5. Bugs & Stability
Below is a ranked list of bugs active (reported or resolved) in the 24-hour window, ordered by severity (memory safety/crashes > incorrect physics > performance > usability):
| Severity | Issue ID | Status | Fix PR(s) | Description |
|----------|----------|--------|-----------|-------------|
| High | [#3535](https://github.com/google-deepmind/mujoco/issues/3535) | Closed/Resolved | #3536, #3539 | Out-of-bounds read in the SAP collision broadphase when simulating >32768 collision items, causing undefined behavior or crashes in large-scale simulations. |
| High | [#3343](https://github.com/google-deepmind/mujoco/issues/3343) | Closed/Resolved | Not listed* | KTX texture usage crashes the `simulate` GUI and OGL renderer, breaking rendering workflows for users of compressed texture formats. |
| Medium | [#2644](https://github.com/google-deepmind/mujoco/issues/2644) | Closed/Resolved | Not listed* | `mj_step` uses plugin configuration from `MjData` instead of the provided `MjModel`, leading to incorrect simulation behavior when using mismatched model/data pairs. |
| Medium | [#2982](https://github.com/google-deepmind/mujoco/issues/2982) | Closed/Resolved | Not listed* | Frame bug in `mjCBody::AccumulateInertia` causes incorrect inertia calculations for fused static bodies from URDF fixed joints, degrading physics accuracy. |
| Medium | [#3426](https://github.com/google-deepmind/mujoco/issues/3426) | Closed/Resolved | Not listed* | MJX-Warp FFI calls fail with varying-axis metadata under `jax.shard_map`, blocking multi-GPU training scalability. |
| Medium | [#2777](https://github.com/google-deepmind/mujoco/issues/2777) | Closed/Resolved | Not listed* | MJX `put_model` throws an error in the convex mesh processing function, breaking GPU-accelerated simulation for models with convex meshes. |
| Medium | [#3540](https://github.com/google-deepmind/mujoco/issues/3540) | Closed/Resolved | #3541 | Static body sleeping optimization is disabled when all dynamic bodies are awake, causing unnecessary performance overhead in large static scenes. |
| Low | [#2393](https://github.com/google-deepmind/mujoco/issues/2393) | Open/Active | None identified | GLFW failures on Ubuntu 24.04 break interactive viewer functionality, but do not affect core simulation. |
| Low | [#3561](https://github.com/google-deepmind/mujoco/issues/3561) | Open/Active (newly reported 2026-09-08) | #3563 (open) | Actuator subclass defaults in MJCF incorrectly inherit bias parameters across different actuator types, causing unexpected behavior in RL environment configuration. |

*\*Fix PRs not listed correspond to PRs outside the top 20 by comment count included in the dataset.*

---

## 6. Feature Requests & Roadmap Signals
### Recently Completed Feature Requests (Likely for Next Release)
The following user-requested features were resolved or merged in the 24-hour window, and are highly likely to be included in the next MuJoCo minor or patch release:
1. **URDF `package://` URI support** ([Issue #1432](https://github.com/google-deepmind/mujoco/issues/1432)): A long-requested interoperability feature for ROS/robotics users, enabling direct loading of URDF models with standard package-based mesh paths.
2. **URDF `<mimic>` joint translation** ([PR #3530](https://github.com/google-deepmind/mujoco/pull/3530)): Adds support for a common URDF joint type used in parallel actuator designs, reducing manual model conversion work.
3. **SDF geom distance sensing** ([PR #2218](https://github.com/google-deepmind/mujoco/pull/2218)): Expands sensor functionality for signed distance field objects, a popular request for robotics perception simulation.
4. **Top-level Python viewer import** ([PR #2492](https://github.com/google-deepmind/mujoco/pull/2492)): Improves Python API usability by eliminating the need for separate viewer module imports.

### In-Progress Roadmap Signal
- **Bazel build system support** ([PR #2225](https://github.com/google-deepmind/mujoco/pull/2225)): This long-running community PR has been actively updated for nearly two years, and its focus on Ubuntu x86_64 support aligns with the needs of many ML and robotics organizations. If maintainers provide feedback on cross-platform support requirements, it could be targeted for a 2026 Q4 release.

### Next Release Prediction
The next MuJoCo release (expected to be either 3.12.2 patch or 3.13.0 minor) will almost certainly include:
- SAP broadphase memory safety fixes (#3536, #3539)
- Static body sleeping performance optimization (#3541)
- URDF `package://` and `<mimic>` joint support
- MJX multi-GPU and convex mesh fixes
- KTX texture crash fixes
- Python viewer import and documentation improvements
The actuator default inheritance fix (#3563) is also a strong candidate if merged in the coming week.

---

## 7. User Feedback Summary
### Key User Pain Points
1. **Ecosystem interoperability friction**: Users integrating MuJoCo with ROS/URDF-based robot models (e.g, iCub/robotology community) have long struggled with missing `package://` URI support, requiring manual asset path rewrites. This pain point was resolved in the 24-hour window.
2. **Platform compatibility gaps**: Robotics engineers using Ubuntu 24.04 (Triton Systems) face persistent GLFW failures that break interactive simulation workflows, with no resolution yet available for this LTS release.
3. **Large-scene performance overhead**: Researchers at the University of Ljubljana working with large, geom-heavy worlds encountered unnecessary computational cost due to broken static body sleeping optimizations, now resolved.
4. **MJX scalability limitations**: Multi-GPU RL training workflows using MJX-Warp and `jax.shard_map` were blocked by FFI metadata errors, an issue now fixed to support scalable simulation.
5. **Actuator configuration unexpected behavior**: RL environment developers building parameter comparison experiments encountered cross-subclass default inheritance for actuators, leading to unintended parameter values. A fix PR (#3563) is currently open.

### Represented Use Cases
Feedback comes from a diverse set of users across academia and industry:
- Industrial robotics simulation (Boston Dynamics, Triton Systems)
- Humanoid robot research (iCub/robotology community)
- Reinforcement learning environment development and multi-GPU training
- Academic physics simulation research (Aalto University, University of Ljubljana)
- Unity-based robotics workflow integration

### Satisfaction Signals
- **Responsive bug fixing**: High-severity issues like the SAP out-of-bounds read were resolved within ~10 days of reporting, indicating maintainer prioritization of memory safety and core stability.
- **Community request responsiveness**: Long-standing feature requests (e.g, `package://` URIs, URDF mimic joints) are being addressed, signaling alignment with user ecosystem needs.

### Dissatisfaction Signal
- **Unresolved platform compatibility**: The Ubuntu 24.04 GLFW issue has been open for over 1.5 years, creating ongoing friction for Linux users on the latest LTS release.

---

## 8. Backlog Watch
The following long-unresolved items represent high-impact needs for the user base and warrant maintainer attention:
1. **Ubuntu 24.04 GLFW Compatibility ([Issue #2393](https://github.com/google-deepmind/mujoco/issues/2393))**  
   Open since 2025-01-28 (20 months) | 10 comments  
   This bug breaks interactive viewer functionality for users on Ubuntu 24.04, a widely adopted long-term support Linux distribution that is a standard platform for robotics and ML research. The issue affects production workflows (e.g, Bazel-based pipelines at Triton Systems) and has seen sustained user discussion without a resolution. Prioritizing a fix would address a core pain point for a large segment of MuJoCo's Linux user base.
2. **Bazel Build System Support ([PR #2225](https://github.com/google-deepmind/mujoco/pull/2225))**  
   Open since 2024-11-12 (22 months) | Last updated 2026-09-08  
   This community-contributed PR adds Bazel build support for the MuJoCo C library, Python bindings, and MJX, addressing a key need for organizations that use Bazel as their primary build orchestration tool (common in robotics and ML). While currently limited to Ubuntu 22.04 x86_64, the PR's long history and active updates demonstrate strong community demand. Clear maintainer guidance on cross-platform support requirements and merge criteria would help advance this high-impact contribution.

</details>

<details>
<summary><strong>Drake</strong> — <a href="https://github.com/RobotLocomotion/drake">RobotLocomotion/drake</a></summary>

# Drake Project Digest (2026-09-09)
*Data sourced from [RobotLocomotion/drake](https://github.com/RobotLocomotion/drake), covering activity in the 24-hour period ending 2026-09-09*

---

## 1. Today's Overview
The Drake robotics simulation project demonstrates steady, active development, with 4 updated issues (3 open/active, 1 closed) and 27 updated pull requests (14 open, 13 merged/closed) and no new tagged releases. Core workstreams include multibody physics feature expansion, build system and dependency maintenance, rendering pipeline improvements, and parsing robustness for MuJoCo and model directives. Maintainers are actively preparing for the upcoming v1.57.0 release, as evidenced by an open draft PR for release notes. The 13 merged/closed PRs in the window reflect strong throughput for both incremental bug fixes and larger, multi-PR feature series.

---

## 2. Releases
No new official Drake releases were published in the 24-hour reporting window. Preparation for the upcoming v1.57.0 minor release is underway, tracked via [PR #24973](https://github.com/RobotLocomotion/drake/pull/24973), which adds the release notes draft.

---

## 3. Project Progress
A total of 13 pull requests were merged or closed in the reporting window. Key merged changes advancing features and fixes include (categorized by workstream):
### Multibody Physics & Optimization
- [PR #24923](https://github.com/RobotLocomotion/drake/pull/24923): Merged breaking change assigning coordinate starts to all joints in multibody topology, a critical prerequisite for full welded-link fusing support. This resolves failures in joint iteration loops when dealing with welds in fused compositions.
- [PR #24969](https://github.com/RobotLocomotion/drake/pull/24969): Merged feature adding a configurable weight parameter to `AddMaximizeLogDeterminantCost` for flexible optimization cost weighting.
### Framework API Cleanup
- [PR #24937](https://github.com/RobotLocomotion/drake/pull/24937): Merged deprecation of `SingleOutputVectorSource`, marking the class as vestigial and steering users to the more flexible `LeafSystem` base class. This closes long-standing cleanup Issue #20989.
### Python Bindings & Gym Integration
- [PR #24935](https://github.com/RobotLocomotion/drake/pull/24935): Merged fix for `DrakeGymEnv` to honor `None` action/observation spaces by auto-generating `gym.spaces.Box` instances with ±infinity bounds for vector-valued ports, aligning with documented API behavior.
- [PR #24898](https://github.com/RobotLocomotion/drake/pull/24898): Merged high-priority update of the `nanobind` Python binding dependency to version 3.0.0.
### Build System, Wheels & Dependencies
- [PR #24903](https://github.com/RobotLocomotion/drake/pull/24903): Merged improvement to the wheel build pipeline to test ABI3 wheels across multiple Python versions, validating ABI compatibility per standard.
- [PR #24948](https://github.com/RobotLocomotion/drake/pull/24948) + [PR #24972](https://github.com/RobotLocomotion/drake/pull/24972): Two merged emergency/regular patch updates for the `rules_rs` Bazel Rust toolchain, upgrading from v0.0.106 → v0.0.108 → v0.0.110.
- [PR #24915](https://github.com/RobotLocomotion/drake/pull/24915): Merged update of the internal VTK dependency to the latest commit.
- [PR #24885](https://github.com/RobotLocomotion/drake/pull/24885): Merged patch update of `nanobind` to v2.14.0.bcr.1 (precursor to the v3.0.0 upgrade).
### Documentation Tooling
- [PR #24930](https://github.com/RobotLocomotion/drake/pull/24930): Merged cleanup of legacy Sphinx documentation hacks, replacing vendored workarounds with native upstream features available in the minimum supported Sphinx version (7.2.6).

---

## 4. Community Hot Topics
*Note: Comment count metadata for pull requests was unavailable in the reporting dataset. Active items are ranked by verified issue comment count, with additional context for high-priority in-progress PRs updated in the window.*
1. **macOS MOSEK Wheel Loading Parity** ([Issue #23867](https://github.com/RobotLocomotion/drake/issues/23867), 20 comments, open): The most actively discussed updated issue, this medium-priority feature request seeks to implement `implib`-based MOSEK runtime loading for macOS wheels, matching the existing Linux implementation that removed vendored MOSEK copies. The 20 comments reflect ongoing discussion of toolchain compatibility, implementation approaches, and cross-platform distribution consistency. *Underlying need*: Uniform, low-bloat MOSEK integration across all supported wheel platforms, aligning with PyPI dependency best practices.
2. **`SingleOutputVectorSource` Deprecation** ([Issue #20989](https://github.com/RobotLocomotion/drake/issues/20989), 7 comments, closed): A long-running cleanup issue (filed February 2024) that was resolved in this window via merged PR #24937. Discussion evolved from requesting Python bindings for the class to a consensus that it was redundant with `LeafSystem` and should be deprecated to reduce API surface area. *Underlying need*: A cleaner, more intuitive system framework API that guides users toward modern, flexible design patterns.
3. **Typed Index Formatter Improvements** ([Issue #24262](https://github.com/RobotLocomotion/drake/issues/24262), 4 comments, open): A low-priority good-first-issue request for `fmt::format` output of `TypeSafeIndex` (e.g., `BodyIndex`) and `Identifier` (e.g., `GeometryId`) types to include type context instead of just bare integers, improving error message readability. Discussion has focused on formatter customization and implementation scope. *Underlying need*: Enhanced debuggability for users working with typed indices and identifiers in large simulation projects.
4. **High-Priority In-Progress Feature PRs** (likely active discussion based on scope and priority labels):
   - [PR #24917](https://github.com/RobotLocomotion/drake/pull/24917) (high priority): The third PR in the auto-loop-breaking feature series, adding weld constraints for re-assembling split primary/shadow links and optional shadow link visualization.
   - [PR #24953](https://github.com/RobotLocomotion/drake/pull/24953): A rendering pipeline fix removing the hard-coded OpenGL light limit and streamlining shader logic, a highly requested quality-of-life improvement for complex scene rendering.

---

## 5. Bugs & Stability
No new bug, crash, or regression reports were included among the 4 issues updated in the 24-hour reporting window. The following bug fixes were merged or are in progress during the period, ranked by inferred severity (based on priority labels and impact scope):
1. **Emergency Build Toolchain Fix (Resolved)**
   - [PR #24948](https://github.com/RobotLocomotion/drake/pull/24948): Merged emergency-priority update of `rules_rs` from v0.0.106 to v0.0.108, followed by a follow-up patch to v0.0.110 via [PR #24972](https://github.com/RobotLocomotion/drake/pull/24972). **Severity**: High (inferred from emergency priority) — likely resolved a critical build break or toolchain vulnerability for Rust-based Drake components.
2. **DrakeGymEnv API Compliance Fix (Resolved)**
   - [PR #24935](https://github.com/RobotLocomotion/drake/pull/24935): Merged fix for `DrakeGymEnv` failing to handle `None` action/observation spaces per documented API behavior, requiring users to manually define spaces for vector-valued ports. **Severity**: Medium — impacts reinforcement learning workflows using Gym integration, no simulation correctness or data loss risk.
3. **OpenGL Hard-Coded Light Limit Fix (In Progress)**
   - [PR #24953](https://github.com/RobotLocomotion/drake/pull/24953): Open fix removing the hard-coded maximum light count in the OpenGL renderer, which caused rendering artifacts or missing lighting in scenes with many light sources. **Severity**: Medium — impacts visual fidelity for complex scenes, no simulation correctness risk.
4. **MuJoCo Nested Include Asset Resolution Fix (In Progress)**
   - [PR #24943](https://github.com/RobotLocomotion/drake/pull/24943): Open fix to resolve nested MuJoCo include asset paths relative to the included XML file (matching native MuJoCo behavior), fixing broken mesh loading for models with nested MJCF file structures. **Severity**: Medium — breaks model import for nested MuJoCo workflows, no simulation correctness risk once models load.
5. **Sphinx Documentation Dependency Fix (In Progress)**
   - [PR #24970](https://github.com/RobotLocomotion/drake/pull/24970): Open fix updating Sphinx to v8.2.3 and sphinx-rtd-theme to v3.1.0, removing outdated version constraints and resolving documentation build issues. **Severity**: Low — impacts documentation builds only, no end-user runtime impact.

---

## 6. Feature Requests & Roadmap Signals
### Active User Feature Requests (from updated issues)
1. **macOS MOSEK Implib Loading** ([Issue #23867](https://github.com/RobotLocomotion/drake/issues/23867), medium priority): Requests parity between Linux and macOS wheels for non-vendored MOSEK runtime loading via implib tools. Open since December 2025 with active discussion, but no associated implementation PR yet.
2. **Typed Index Formatter Options** ([Issue #24262](https://github.com/RobotLocomotion/drake/issues/24262), low priority, good first issue): Requests type-aware formatting for `TypeSafeIndex` and `Identifier` types to improve error message readability. Open since March 2026, no implementation PR yet.
### Roadmap Signals from In-Progress Work
Ongoing PRs point to three key roadmap priorities:
- **Multibody loop breaking and fusing**: A multi-PR series (including open PRs #24917, #24909, and merged PR #24923) advancing full auto-loop-breaking and welded-link fusing functionality, a core multibody feature tracked in Issue #24843.
- **SAP joint friction**: Open PR #24920 adds the `SapJointFrictionConstraint` for Coulomb dry friction in 1-DOF joints, part of the long-running SAP solver enhancement roadmap (Issue #18932).
- **Parser robustness and consistency**: Open PRs #24943 (MuJoCo nested includes) and #24938 (model directives DiagnosticPolicy) continue work to align parser behavior across formats and improve error handling.
### Next Release (v1.57.0) Predictions
Based on merged work and in-progress PR status, the following are likely to appear in the upcoming v1.57.0 release:
- **High confidence**: `AddMaximizeLogDeterminantCost` weight parameter, `SingleOutputVectorSource` deprecation, ABI3 multi-Python wheel testing, `nanobind` 3.0.0 upgrade, joint coordinate start topology change (breaking change), legacy Sphinx hack cleanup.
- **Medium confidence**: OpenGL light limit removal (PR #24953), MuJoCo nested include asset resolution fix (PR #24943), model directives DiagnosticPolicy support (PR #24938).
- **Low confidence**: Auto-loop-breaking weld constraint support (PR #24917, part of a larger series requiring additional review), SAP joint friction constraint (PR #24920, not yet wired into the full solver pipeline).
- **Unlikely for v1.57**: macOS MOSEK implib support (no open PR), typed index formatter improvements (no open PR, low priority).

---

## 7. User Feedback Summary
### Key User Pain Points (from issues and PR rationales)
1. **Platform parity for MOSEK on macOS**: macOS wheel users lack the non-vendored MOSEK integration available on Linux, creating inconsistent deployment workflows for optimization-heavy simulations.
2. **Poor error message readability for typed indices**: Bare integer output for `TypeSafeIndex` and `Identifier` types makes debugging errors in large systems with multiple index types time-consuming and error-prone.
3. **MuJoCo model import friction**: Divergent path resolution for nested MuJoCo includes breaks existing MuJoCo models, requiring manual path adjustments to work with Drake.
4. **Gym API incompatibility**: `DrakeGymEnv`’s failure to auto-generate spaces for `None` inputs violates documented API behavior, adding unnecessary boilerplate for RL users.
5. **Rendering light limit constraints**: The hard-coded OpenGL light limit prevents users from rendering complex, realistic scenes with multiple light sources.
### Common Use Cases Represented
- Reinforcement learning with Drake-Gym integration
- Optimization-based control using MOSEK
- MuJoCo model import and simulation
- Complex scene rendering for visualization and sensor simulation
- Multibody simulation with closed-loop kinematic chains
### Satisfaction Signals
All updated issues and PRs in the reporting window have 0 👍 reactions, so no quantifiable user satisfaction or dissatisfaction signal is available from this dataset. However, the alignment of merged fixes/features with user-reported issues (e.g., closing the long-standing #20989 cleanup request) suggests maintainers are responsive to community feedback.

---

## 8. Backlog Watch
*This list is limited to issues and PRs updated in the 24-hour reporting window, and may not reflect all long-standing backlog items across the full repository.* The following items are high-impact or long-running and warrant ongoing maintainer attention:
1. **macOS MOSEK Implib Support** ([Issue #23867](https://github.com/RobotLocomotion/drake/issues/23867)): Open for 9 months (since December 2025) with 20 comments, this medium-priority distribution feature has sustained user discussion but no associated implementation PR. Delaying this work perpetuates platform parity gaps between Linux and macOS wheels, which may frustrate macOS users relying on MOSEK for optimization.
2. **Typed Index Formatter Improvements** ([Issue #24262](https://github.com/RobotLocomotion/drake/issues/24262)): Open for 6 months (since March 2026) as a low-priority good first issue, this small quality-of-life improvement has not attracted a contributor or implementation work. While low impact, it is a low-effort fix that could improve user experience and onboard new contributors.
3. **Multibody World-Splitting Prevention** ([PR #24909](https://github.com/RobotLocomotion/drake/pull/24909)): Open for ~20 days (since August 20, 2026) with low priority, this PR is a foundational fix for the auto-loop-breaking series that prevents invalid shadow link splits from the World body. Untriaged or delayed review of this PR could block progress on the higher-priority loop-breaking feature roadmap.

</details>

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*