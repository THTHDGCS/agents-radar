# AI CLI Tools Community Digest 2026-09-15

> Generated: 2026-09-15 02:16 UTC | Tools covered: 5

- [ROS 2](https://github.com/ros2/ros2)
- [NVIDIA Isaac Lab](https://github.com/isaac-sim/IsaacLab)
- [Genesis](https://github.com/Genesis-Embodied-AI/Genesis)
- [LeRobot](https://github.com/huggingface/lerobot)
- [OpenVLA](https://github.com/openvla/openvla)
- [Claude Code Skills](https://github.com/anthropics/skills)

---

## Cross-Tool Comparison

# Cross-Tool AI Robotics Developer Ecosystem Comparison Report | 2026-09-15
*Data source: 24-hour community digests for ROS 2, NVIDIA Isaac Lab, Genesis, LeRobot, and OpenVLA (2026-09-14 to 2026-09-15)*

---

## 1. Ecosystem Overview
The embodied AI and robotics developer tools ecosystem exhibits divergent maturity trajectories, with activity split between stable core infrastructure maintenance, high-velocity simulation performance tuning, and policy framework standardization. The 24-hour reporting window captures a mix of LTS release validation for widely adopted middleware, pre-major-release hardening for simulation and policy tools, and targeted performance optimizations for next-generation simulation engines. Mature, production-grade tools prioritize stability and incremental infrastructure upgrades, while newer, research-focused tools iterate rapidly on API correctness, speed, and ecosystem integration. The lack of activity in the OpenVLA project reflects a temporary lull or stable maintenance phase relative to faster-moving adjacent tools in the stack.

---

## 2. Activity Comparison
| Tool | Issues Updated (24h, Confirmed Total) | PRs Updated (24h) | Release Status |
|------|----------------------------------------|-------------------|----------------|
| ROS 2 | 0 | 2 (total confirmed) | New LTS patch release: Humble Hawksbill Patch 15 |
| NVIDIA Isaac Lab | 9 | ≥10 (10 high-impact documented) | No new release; 3.0.0 RC1 hardening in progress |
| Genesis | 0 | 6 (total confirmed) | No new release |
| LeRobot | 6 | 27 (total confirmed) | No new release; v0.7.0 roadmap active |
| OpenVLA | 0 | 0 | No new release |

---

## 3. Shared Feature Directions
Three core requirements appear across multiple tool communities, reflecting broader industry priorities:
1. **Core Runtime Performance Optimization** (ROS 2, Isaac Lab, Genesis, LeRobot)
   All active tools prioritize reducing overhead for core workloads to support larger-scale and real-time use cases. Specific needs include: reduced Python binding overhead and smaller binary sizes for ROS 2; faster simulation-rendering sync and physics accuracy for Isaac Lab; GPU rigid solver speedups and sleeping body overhead reduction for large-scale Genesis scenes; and higher training GPU utilization (ACT policy) and inference throughput (SmolVLA) for LeRobot.
2. **Robust API Correctness & Input Validation** (Isaac Lab, LeRobot)
   Both robot learning-focused tools report high-impact silent API failures that corrupt outputs without explicit crashes, driving demand for stricter input validation and contract enforcement. Isaac Lab users face 6 core module bugs (e.g., partial camera intrinsic updates, invalid delay buffer state) that corrupt RL training data/metrics. LeRobot users encounter critical compatibility gaps (e.g., VLABench action bounds rejecting 100% of benchmark actions) that break out-of-the-box workflows.
3. **Ecosystem Integration & Compatibility** (ROS 2, Isaac Lab, Genesis, LeRobot)
   All active tools invest in reducing integration friction for downstream users and dependencies. ROS 2 validates LTS releases across Linux x86_64/aarch64 targets for cross-platform compatibility. Isaac Lab fixes PyPI wheel compliance and Docker image stability, plus works toward PhysX/Newton backend feature parity. Genesis adds CI `workflow_call` triggers to let dependent repositories validate changes against its test suite. LeRobot prioritizes benchmark compatibility (VLABench), offline workflow support, and out-of-tree deployment plugins.

---

## 4. Differentiation Analysis
The tools occupy distinct layers of the robotics/embodied AI stack, with clear differences in focus, user base, and development approach:
- **Feature Focus**: 
  ROS 2 (middleware layer) prioritizes long-term LTS stability and incremental core infrastructure upgrades (e.g., Python binding modernization). Isaac Lab (simulation environment layer) focuses on end-to-end robot learning simulation, 3.0.0 release hardening, and cross-backend consistency. Genesis (simulation engine layer) targets low-level rigid body simulation performance and CI infrastructure scaling. LeRobot (policy framework layer) centers on policy standardization, VLA ecosystem expansion, and end-to-end workflow robustness (rollout, evaluation, migration). OpenVLA (model layer) is inactive in the window, with a historical focus on open VLA model development.
- **Target Users**:
  ROS 2 serves a broad, mature user base of production robotics engineers and academic labs building deployed systems. Isaac Lab targets GPU-focused robot learning researchers and engineers in the NVIDIA ecosystem. Genesis caters to a niche, technical user base of embodied AI researchers needing high-performance simulation. LeRobot serves a large, fast-growing community of robot learning practitioners, researchers, and hobbyists building imitation learning/VLA policies.
- **Technical Approach**:
  ROS 2 follows a conservative, community-governed LTS release cycle with cross-package coordinated infrastructure changes. Isaac Lab uses a rapid, backport-first development model ahead of its 3.0.0 major release, with tight integration to NVIDIA’s hardware/software stack. Genesis operates with a small core team focused on bottom-up simulation engine tuning, with 5 of 6 24h PRs from a single lead contributor. LeRobot uses a community-driven standardization model, consolidating duplicated policy logic into shared primitives and integrating closely with the Hugging Face Hub for model/dataset sharing.

---

## 5. Community Momentum & Maturity
Activity volume, contributor diversity, and release stage indicate clear tiers of maturity and momentum:
- **Mature, Stable (Low Activity, High Adoption)**: ROS 2. Zero reported issues and only 2 PRs (one release, one long-term infrastructure PR) reflect a stable, mature core with few acute user issues. Regular LTS patch releases confirm established production-grade governance.
- **High Velocity, Maturing (High Activity, Pre-Major Release)**: LeRobot and NVIDIA Isaac Lab lead in activity volume. LeRobot has the highest PR count (27) and active community engagement (5 comments on the v0.7.0 roadmap, ongoing discussions on DAgger workflow support), indicating a large, growing contributor base. Isaac Lab has 9 issues and ≥10 high-impact PRs, with high-quality external contributions (6 bugs + 1 fix PR from community contributor peachtree0222) and active release hardening for 3.0.0 RC1.
- **Focused Iteration, Niche User Base (Low Issue Volume, Targeted PRs)**: Genesis. Most 24h PRs (5 of 6) come from a single core contributor, with zero user-reported issues, indicating a small, highly focused development team and either a limited current user base or high stability for existing use cases. Iteration is concentrated exclusively on simulation performance and CI scaling.
- **Low Momentum**: OpenVLA. No 24h activity suggests a temporary development lull or stable maintenance mode with no urgent priorities.

---

## 6. Trend Signals
Community feedback and activity reveal 5 key industry trends with actionable reference value for developers and technical decision-makers:
1. **Performance is a foundational requirement for scaling embodied AI**: Across all active tools, core performance optimization (simulation speed, inference throughput, binding overhead) is a top investment priority. For teams building robot learning or simulation pipelines, investing in GPU kernel tuning, `torch.compile` integration, and binding modernization will be critical to support large-scale training and real-time deployment.
2. **Silent API failures pose underrecognized risks to robot learning workflows**: Both Isaac Lab and LeRobot report high-severity bugs that corrupt training data, metrics, or evaluation results without triggering crashes, leading to wasted compute and invalid experiments. Developers should prioritize input validation, contract testing, and explicit error handling for core pipeline APIs to mitigate this risk.
3. **Ecosystem interoperability drives adoption**: All active tools are investing in compatibility with standard benchmarks, cross-platform/backend environments, and downstream dependencies. For tool developers, building open interfaces and aligning with widely adopted standards (e.g., ROS 2 middleware, VLABench benchmarks, PyPI/Docker deployment) will accelerate user adoption and reduce integration friction.
4. **Shared primitive standardization reduces technical debt**: LeRobot’s ongoing flow matching standardization (consolidating duplicated logic across 4 policies) demonstrates that modular, shared core components lower contribution barriers and reduce maintenance overhead. Ecosystem stakeholders would benefit from collaborating on shared interfaces for common components (e.g., action spaces, observation encoding, flow matching primitives).
5. **LTS stability remains non-negotiable for production robotics**: ROS 2’s steady LTS release cycle and zero active core issues highlight that production robotics users prioritize predictability and reliability over new features. Tools targeting enterprise or deployed use cases should invest in well-tested LTS branches and transparent release governance to build trust with industrial users.

---

## Per-Tool Reports

<details>
<summary><strong>ROS 2</strong> — <a href="https://github.com/ros2/ros2">ros2/ros2</a></summary>

# ROS 2 Core Repository Community Digest | 2026-09-15
Data Source: [ros2/ros2](https://github.com/ros2/ros2) | 24-hour activity window: 2026-09-14 to 2026-09-15

---

## 1. Today's Highlights
The 24-hour update window for the ROS 2 core repository is headlined by the official release of ROS 2 Humble Hawksbill Patch Release 15, finalized after the merged release PR #1874 passed cross-platform CI validation. An open, long-running PR (#1856) proposing a full migration of Python binding infrastructure from pybind11 to nanobind also received an update, marking progress on a core performance improvement for Python-facing ROS 2 libraries. No new issues were filed or updated in the reporting period, indicating stable operation of the core repository.

---

## 2. Releases
- **ROS 2 Humble Hawksbill Patch Release 15 (tag: `release-humble-20260914`)**
  Release Date: 2026-09-14 | Associated Release PR: [ros2/ros2#1874](https://github.com/ros2/ros2/pull/1874)
  Summary: Official binary patch release for the Humble Hawksbill LTS distribution. Users must update their base operating system packages to the latest versions to ensure compatibility with the released binaries. Full installation instructions and runtime dependency details are available in the [official Humble binary package documentation](https://docs.ros.org/en/humble/Installation.html#binary-packages). Release validation was completed via passing CI runs on Linux x86_64 and Linux aarch64 targets.

---

## 3. Hot Issues
No issues were opened or updated in the `ros2/ros2` core repository within the 24-hour reporting window. For full historical issue tracking and community-reported problems, visit the [ros2/ros2 Issues page](https://github.com/ros2/ros2/issues).

---

## 4. Key PR Progress
Only 2 pull requests were updated in the 24-hour reporting window; both are documented below:
1. **[ros2/ros2#1856](https://github.com/ros2/ros2/pull/1856): Migrate from pybind11 to nanobind**
   Status: Open | Author: claraberendsen | Last Updated: 2026-09-14
   Summary: Proposes a core migration of ROS 2’s Python binding stack from pybind11 to nanobind, coordinated with parallel implementation work in rclpy ([ros2/rclpy#1707](https://github.com/ros2/rclpy/pull/1707)). The migration targets reduced Python call overhead, smaller binary sizes, and improved binding maintainability for all Python-dependent ROS 2 core packages. The 2026-09-14 update indicates active ongoing development on this high-impact infrastructure change.
2. **[ros2/ros2#1874](https://github.com/ros2/ros2/pull/1874): Humble release versions 2026-09-14**
   Status: Closed | Author: christophebedard | Last Updated: 2026-09-14
   Summary: Release preparation PR for the September 2026 Humble patch release, closed upon successful completion of release validation and deployment. The PR references a pre-release community announcement on Open Robotics Discourse and links to passing CI builds for Linux x86_64 and Linux aarch64 targets. Its closure marks the official availability of Humble Patch Release 15.

---

## 5. Feature Request Trends
No new feature request issues were filed or updated in the `ros2/ros2` core repository in the 24-hour window. The only active feature-aligned work visible in the period is the pybind11 to nanobind migration (PR #1856), which addresses a longstanding community priority for improved Python binding performance and reduced resource overhead in ROS 2 Python workflows. For full historical feature request tracking, see the [feature request label on ros2/ros2 Issues](https://github.com/ros2/ros2/issues?q=is%3Aissue+label%3A%22feature+request%22).

---

## 6. Developer Pain Points
No new developer pain point issues were submitted or updated in the `ros2/ros2` core repository during the reporting period, indicating no acute, widely reported issues with core ROS 2 functionality in the window. The active nanobind migration PR (#1856) aligns with previously documented community frustrations around pybind11’s relatively high overhead and large binary footprint for Python ROS 2 packages, though no new related feedback was received in the 24-hour period. For historical pain point tracking, refer to the [ros2/ros2 Issues page](https://github.com/ros2/ros2/issues).

</details>

<details>
<summary><strong>NVIDIA Isaac Lab</strong> — <a href="https://github.com/isaac-sim/IsaacLab">isaac-sim/IsaacLab</a></summary>

# NVIDIA Isaac Lab Community Digest | 2026-09-15

## Today's Highlights
No new Isaac Lab official releases were published in the 24-hour window ending 2026-09-15, with active development focused on core API bug fixes, 3.0.0 release hardening, and cross-backend rendering/simulation synchronization. Contributor peachtree0222 filed 6 high-impact core module bug reports (covering MARL environments, event/termination managers, camera APIs, and delay buffers) alongside a matching fix PR for the DirectMARLEnv state space issue. Maintainers pushed a wave of backports to the `release/3.0.0` branch addressing security vulnerabilities, PyPI wheel compliance, and Docker documentation ahead of the 3.0.0 RC1 rollout.

## Hot Issues
There were 9 total issues updated in the 24-hour window, all noteworthy for their impact on core workflows, API correctness, or developer onboarding. Below is a breakdown ordered by user impact:
1. **GUI Stays Frozen While PhysX Simulation Advances ([#7632](https://github.com/isaac-sim/IsaacLab/issues/7632))**: A high-impact bug where the interactive viewport remains completely static during state-based rollouts, even as simulation logs show robot joints and physics advancing normally. This breaks core debugging and rollout validation workflows, as users cannot visually verify robot behavior. **Community reaction**: 1 comment, 0 👍, open since 2026-09-08, with active fix work ongoing in PR #7809.
2. **Errors When Running Isaac Sim from Pre-built Docker Image ([#7732](https://github.com/isaac-sim/IsaacLab/issues/7732))**: Reports widespread errors when running Isaac Sim 6.0.1 inside the official `nvcr.io/nvidia/isaac-lab:3.0.0-beta2` pre-built Docker image, following official deployment documentation. This blocks fast onboarding and cloud/CI deployment for users relying on pre-built images. **Community reaction**: 1 comment, 0 👍, open since 2026-09-10.
3. **Camera Intrinsic Batch Mismatch Silently Updates Only a Prefix ([#7798](https://github.com/isaac-sim/IsaacLab/issues/7798))**: A silent correctness bug where `Camera.set_intrinsic_matrices()` does not validate that the number of input matrices matches the number of selected camera IDs, using `zip()` to stop at the shorter input. This causes partial, undetectable misconfiguration of batch cameras, corrupting vision-based RL training data. **Community reaction**: 0 comments, 0 👍, filed 2026-09-14.
4. **EventManager.apply(reset, env_ids=None) Passes slice(None) to Event Terms ([#7791](https://github.com/isaac-sim/IsaacLab/issues/7791))**: Violates the documented event term API contract, where `env_ids=None` (meaning all environments) is converted to `slice(None)` internally and passed to reset event callbacks. This breaks custom reset handlers and built-in event logic that expects `env_ids` as a tensor or list of indices. **Community reaction**: 0 comments, 0 👍, filed 2026-09-14.
5. **TerminationManager.reset Reports Statistics from Environments Outside env_ids ([#7790](https://github.com/isaac-sim/IsaacLab/issues/7790))**: A metrics correctness bug where `TerminationManager.reset(env_ids)` averages termination statistics across all environments, even when only a subset is being reset. This produces inaccurate episode success/failure rates for RL training, leading to misinformed training tuning decisions. **Community reaction**: 0 comments, 0 👍, filed 2026-09-14.
6. **RigidObjectCollection Deletion Callback Treats an Event as a Path ([#7799](https://github.com/isaac-sim/IsaacLab/issues/7799))**: A lifecycle bug where `RigidObjectCollection._on_prim_deletion()` expects a prim path string as input, but the `AssetBase` registration passes a PhysX event object with the path stored in `event.payload["prim_path"]`. This causes crashes or failed cleanup when rigid objects are dynamically deleted from the scene. **Community reaction**: 0 comments, 0 👍, filed 2026-09-14.
7. **DelayBuffer.set_time_lag Leaves Invalid State After Raising ValueError ([#7793](https://github.com/isaac-sim/IsaacLab/issues/7793))**: A state corruption bug where `DelayBuffer.set_time_lag()` writes invalid lag values to internal state before validating them, so rejected negative or oversize lags remain active even after a `ValueError` is raised. This breaks latency simulation and sim-to-real alignment workflows that rely on accurate delay buffer configuration. **Community reaction**: 0 comments, 0 👍, filed 2026-09-14.
8. **DirectMARLEnv state_space=0 is Exposed as Box(0) Instead of None ([#7792](https://github.com/isaac-sim/IsaacLab/issues/7792))**: An API contract bug where `DirectMARLEnvCfg.state_space = 0` (documented to disable centralized state and set `env.state_space` to `None`) instead creates a zero-width `gym.spaces.Box` space. This breaks downstream MARL frameworks that check for `None` to detect disabled centralized state. A fix is already available in PR #7810. **Community reaction**: 0 comments, 0 👍, filed 2026-09-14.
9. **Why Can't the Base's COM be Randomized in the Example When Using `newton_mjwarp` ([#7786](https://github.com/isaac-sim/IsaacLab/issues/7786))**: A user question highlighting a feature gap in the `newton_mjwarp` backend, where base center-of-mass randomization is disabled (set to `None` in presets) despite being supported on the PhysX backend. This limits domain randomization capabilities for users working with the Newton physics engine. **Community reaction**: 0 comments, 0 👍, filed 2026-09-14.

## Key PR Progress
Below are 10 of the most impactful pull requests updated in the 24-hour window, covering bug fixes, security hardening, release infrastructure, and feature improvements:
1. **PhysX RTX Sync Fix ([#7809](https://github.com/isaac-sim/IsaacLab/pull/7809))**: An alternative approach to longstanding PR #7138, this non-breaking bug fix addresses synchronization gaps between PhysX simulation state and the RTX renderer, the likely root cause of the frozen GUI reported in issue #7632. It restores consistent viewport updates during interactive rollouts.
2. **Fix Implicit Effort Submission in OVPhysX ([#7782](https://github.com/isaac-sim/IsaacLab/pull/7782))**: Resolves a bug where implicit actuators on the default OVPhysX path submitted PD effort estimates as additional joint force while native joint drives remained enabled, causing incorrect torque application. The fix ensures implicit joints receive only feedforward effort, while explicit joints retain their existing behavior.
3. **Resolve Security Findings and Optionalize RL Integrations ([#7805](https://github.com/isaac-sim/IsaacLab/pull/7805))**: Major security hardening PR that ports SonarQube findings from internal development, rejects unsafe legacy pickled actuator checkpoints in favor of TorchScript archives, hardens CI argument handling and MDL import parsing, and pins RL-Games to a verified commit. A backport to `release/3.0.0` is available as PR #7806.
4. **Upgrade Transformers to 5.10.4 ([#7803](https://github.com/isaac-sim/IsaacLab/pull/7803))**: Security upgrade that moves the project off the vulnerable 4.x Transformers release line to the latest non-yanked 5.10.4 patch release. The upgrade is backported to the 3.0.0 release branch as PR #7804 to ensure release builds are patched.
5. **Mirror Newton Frame-View Pose Writes onto Fabric Transforms ([#7691](https://github.com/isaac-sim/IsaacLab/pull/7691))**: Fixes a bug where `Camera.set_world_poses` updated PhysX state but not Newton renderer state, leaving rendered images at the old camera pose while position tensors reported the new pose. The fix aligns Newton rendering behavior with PhysX to ensure consistent cross-backend camera behavior.
6. **Keep Disabled Direct MARL State Spaces as None ([#7810](https://github.com/isaac-sim/IsaacLab/pull/7810))**: Core API bug fix that resolves issue #7792, where `DirectMARLEnvCfg.state_space=0` (documented to disable centralized state and return `None`) instead returned a zero-width `Box` space. The fix preserves the documented API contract while leaving positive/negative state space configurations unchanged.
7. **Exclude Git-Only Integrations from PyPI Wheel Metadata ([#7807](https://github.com/isaac-sim/IsaacLab/pull/7807))**: Release infrastructure fix that removes Git-hosted RL-Games and Robomimic dependencies from PyPI wheel metadata, as these packages are not available on PyPI and would break pip installations of the official Isaac Lab wheel. A 3.0.0 release backport is available as PR #7808.
8. **Update 3.0.0 RC1 Docker References ([#7801](https://github.com/isaac-sim/IsaacLab/pull/7801))**: Documentation and workflow update that aligns Docker docs and OSMO workflow defaults with the new 3.0.0 RC1 pre-built images (`isaac-lab:3.0.0-rc1` and `isaac-lab:3.0.0-rc1-kitless`). A backport to the 3.0.0 release branch is available as PR #7802.
9. **Add Physics-Plus-Render Mode to Render Benchmark ([#7797](https://github.com/isaac-sim/IsaacLab/pull/7797))**: Follow-up to PR #7702 that adds a mode switch to the `Isaac-RenderBenchmark-Franka-Cabinet` task to measure combined physics and rendering performance, plus a dedicated physics timer to help developers isolate bottlenecks between simulation and rendering pipelines.
10. **Move Nightly Lifecycle into cli.py Auto-Bump and Sync uv.lock ([#5867](https://github.com/isaac-sim/IsaacLab/pull/5867))**: Longstanding infrastructure refactor that eliminates split-brain logic between the main branch's nightly changelog trigger and branch-side build logic, consolidating all nightly bump and lockfile sync logic into `cli.py` to reduce maintenance overhead and prevent drift between workflows.

## Feature Request Trends
Based on the 9 issues updated in the 24-hour window, the most prominent feature direction trends are:
1. **Newton Backend Feature Parity**: The only user feature-adjacent question ([#7786](https://github.com/isaac-sim/IsaacLab/issues/7786)) requests support for base center-of-mass randomization on the `newton_mjwarp` backend, reflecting broader demand for full domain randomization capabilities across all physics backends to enable consistent sim-to-real workflows regardless of engine choice. This aligns with ongoing maintainer work on Newton rendering and performance tuning (e.g., PR #6443, #7691).
2. **Stricter Core API Validation**: Multiple bug reports of silent partial failures ([#7798](https://github.com/isaac-sim/IsaacLab/issues/7798), [#7793](https://github.com/isaac-sim/IsaacLab/issues/7793), [#7792](https://github.com/isaac-sim/IsaacLab/issues/7792)) highlight implicit user demand for input validation guardrails across core APIs (cameras, delay buffers, MARL environments) to prevent undetectable training data corruption from misconfigured parameters.
3. **Reliable Simulation-Visualization Sync**: The GUI freeze bug ([#7632](https://github.com/isaac-sim/IsaacLab/issues/7632)) underscores user need for robust, guaranteed sync between underlying simulation state and the interactive viewport, a critical capability for debugging robot behaviors and validating training rollouts in real time.

## Developer Pain Points
Recurring developer frustrations and high-impact issues from the 24-hour window include:
1. **Pre-built Docker Image Instability**: The open issue ([#7732](https://github.com/isaac-sim/IsaacLab/issues/7732)) reporting widespread errors when using the official `isaac-lab:3.0.0-beta2` pre-built Docker image with Isaac Sim 6.0.1 is a major onboarding and deployment pain point, as users relying on Docker for cloud/CI workflows face forced manual image builds and extended setup time.
2. **Silent Core API Failures**: A batch of 6 core module bugs (all filed by contributor peachtree0222 on 2026-09-14) cause silent incorrect behavior rather than explicit crashes: camera intrinsic batch mismatches, invalid DelayBuffer state after validation errors, mismatched DirectMARLEnv state space types, incorrect env_id handling in EventManager and TerminationManager, and broken RigidObjectCollection deletion callbacks. These are high-impact pain points because they corrupt training data or metrics without user awareness, leading to wasted compute and difficult-to-troubleshoot training failures.
3. **Simulation-Viewport Desync**: The GUI freeze bug ([#7632](https://github.com/isaac-sim/IsaacLab/issues/7632)), paired with active PRs addressing PhysX RTX sync ([#7809](https://github.com/isaac-sim/IsaacLab/pull/7809)) and Newton camera pose sync ([#7691](https://github.com/isaac-sim/IsaacLab/pull/7691)), highlights a recurring frustration where rendered visuals do not match actual simulation state, breaking interactive debugging workflows.
4. **Backend Inconsistency**: The user question about missing Newton COM randomization ([#7786](https://github.com/isaac-sim/IsaacLab/issues/7786)) and camera pose gaps on the Newton backend point to pain points from feature and behavior mismatches between the PhysX and Newton physics backends, forcing users to adjust workflows or debug backend-specific issues when switching engines.

</details>

<details>
<summary><strong>Genesis</strong> — <a href="https://github.com/Genesis-Embodied-AI/Genesis">Genesis-Embodied-AI/Genesis</a></summary>

# Genesis Community Digest | 2026-09-15
*Data source: [Genesis-Embodied-AI GitHub Org](https://github.com/Genesis-Embodied-AI), 24-hour window ending 2026-09-15 00:00 UTC*

---

## 1. Today's Highlights
The Genesis Embodied AI project recorded no new releases or community-submitted issues in the 24-hour reporting window, with development activity concentrated on pull requests for rigid simulation performance and CI/CD infrastructure. Four closed PRs from core contributor duburcqa deliver targeted speedups for rigid body simulation, addressing GPU solver efficiency for large contact islands, sleeping body processing overhead, and hibernation costs in fully awake scenes. A new open PR proposes adding `workflow_call` triggers to Genesis’s production CI and benchmark pipelines, enabling dependent repositories to validate changes against Genesis’s full test suite to reduce integration risk.

## 2. Releases
No new stable or pre-release versions were published to Genesis repositories in the 24-hour reporting window.

## 3. Hot Issues
No new or updated GitHub Issues were tracked across Genesis repositories in the reporting window. There are no noteworthy bugs, feature requests, or community discussion threads to report for this period.

## 4. Key PR Progress
Six pull requests were updated in the Genesis ecosystem in the past 24 hours, all in the `genesis-world` repository. All six are listed below (fewer than the standard 10 due to limited activity in the reporting window):

### Open PRs
- **[PR #3371: [MISC] Let dependent repositories run the production CI and benchmark comparison against their changes](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3371)**  
  Author: duburcqa | Created: 2026-09-14 | Updated: 2026-09-14  
  Adds `workflow_call` triggers to `production.yml` and `alarm.yml` CI workflows, allowing Genesis dependency repositories to run Genesis’s full unit test, benchmark, and benchmark comparison suite against their own changes. All inputs are optional to preserve default behavior for existing workflow triggers, reducing integration risk for core dependencies by enabling pre-merge compatibility validation against Genesis’s production test and performance baselines.

### Closed PRs
- **[PR #3370: [FEATURE] Expose the wall time of each phase of a scene step](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3370)**  
  Author: duburcqa | Created: 2026-09-14 | Updated: 2026-09-14  
  Introduces a new `FPSTracker` utility to time individual phases of a scene step process, with support for named phase timing, step-level total timing, and a sliding window average via a new `timings_window` field in `ProfilingOptions`. Exposes per-phase wall times via a `timings` mapping, enabling fine-grained performance profiling of scene step pipelines to identify bottlenecks in simulation, rendering, or logic phases.

- **[PR #3369: [MISC] Speed up rigid simulation where bodies sleep](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3369)**  
  Author: duburcqa | Created: 2026-09-14 | Updated: 2026-09-14  
  Optimizes contact buffer handling for sleeping rigid links by retaining sleeping contacts at the front of the buffer, so per-step processing passes (prune, sort, island edge generation, constraint row building, no-slip handling, backward passes) only traverse the live range of active contacts. Reduces per-step simulation overhead for scenes with large numbers of sleeping rigid bodies, a common pattern in environments with static props or inactive objects.

- **[PR #3368: [MISC] Speed up the GPU rigid solver for large contact islands](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3368)**  
  Author: duburcqa | Created: 2026-09-14 | Updated: 2026-09-14  
  Optimizes GPU rigid solver performance for large contact islands that exceed shared-memory tile caps by using global memory via DOF lists, enabling scattered (non-contiguous) DOF islands to use the same register-tiled processing path as contiguous islands. Removes the scalar fallback path on lane 0 and optimizes Hessian assembly, delivering meaningful speedups for large-scale simulation scenes with complex contact interactions (e.g., multi-robot environments, dense clutter manipulation tasks).

- **[PR #3367: [MISC] Make hibernation free where nothing sleeps](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3367)**  
  Author: duburcqa | Created: 2026-09-14 | Updated: 2026-09-14  
  Eliminates hibernation-related overhead for scenes with no sleeping bodies by moving sleep flag checks from per-link serial kinematic walks (poses, geoms, velocities) to a single per-walk read of the environment’s awake DOF count. Also optimizes actuation path handling for links in environments with sleepers, removing the performance tax of hibernation support for fully dynamic scenes while preserving hibernation benefits for scenes with inactive bodies.

- **[PR #3346: DO NOT MERGE: run production.yml on the ARC runners](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3346)**  
  Author: etiennecoutaud | Created: 2026-09-11 | Updated: 2026-09-14 | *Closed without merge (temporary test)*  
  Throwaway test PR to validate the new ARC runner pool declared in the Genesis infrastructure repo. Only modifies the `runs-on` field for two self-hosted CI jobs to target the `arc-genesis-wo` runner pool, and was closed after successful test execution. Confirms functionality of the new ARC self-hosted runner pool, which will scale CI capacity for Genesis production workflows.

## 5. Feature Request Trends
No new or updated issues were filed in the 24-hour reporting window, so no new feature request trends can be distilled from this period’s data. Trend tracking will resume in future digests as new community submissions are received.

## 6. Developer Pain Points
No new developer pain points, bug reports, or support requests were filed via GitHub Issues in the reporting window. No recurring frustrations or high-frequency requests can be identified from this period’s data.

</details>

<details>
<summary><strong>LeRobot</strong> — <a href="https://github.com/huggingface/lerobot">huggingface/lerobot</a></summary>

# LeRobot Community Digest | 2026-09-15
*Source: github.com/huggingface/lerobot (data updated in 24h window ending 2026-09-15)*

---

## 1. Today's Highlights
No new LeRobot releases were published in the 24-hour window, but the project saw 27 updated pull requests and 6 updated issues focused on policy performance, flow matching standardization, and core workflow bug fixes. Standout updates include a 4.2x inference speedup for SmolVLA via static KV cache and `torch.compile` support, a new shared flow-matching training input layer across policies, and critical fixes for VLABench evaluation and policy migration workflows. Community feedback also highlighted key gaps in DAgger human-in-the-loop recording, ACT multi-GPU utilization, and benchmark compatibility, aligned with the recently updated v0.7.0 community roadmap.

---

## 2. Releases
No new LeRobot releases were published in the 24-hour period ending 2026-09-15.

---

## 3. Hot Issues
All 6 issues updated in the past 24 hours are included below, ranked by impact and community engagement:
1. **#3832 LeRobot Community Roadmap 0.7.0 Release** [Open]  
   The official roadmap for the upcoming v0.7.0 major release, outlining core team priorities and community contribution areas across policies, datasets, simulation, CI, and robot hardware. It serves as the single source of truth for near-term project direction.  
   Community signal: 5 comments, active alignment discussions between maintainers and contributors.  
   [Link](https://github.com/huggingface/lerobot/issues/3832)
2. **#4626 [Bug/Feature Req] DAgger rollout strategy cannot record full task-attempt episodes with HIL corrections** [Open]  
   Reports a critical gap in DAgger workflow support: `record_autonomous=True` only supports unbounded continuous recording or corrections-only recording, with no way to capture full autonomous + human-in-the-loop correction episodes as single bounded units. This breaks standard interactive imitation learning pipelines.  
   Community signal: 2 comments, active discussion on expected behavior and implementation paths.  
   [Link](https://github.com/huggingface/lerobot/issues/4626)
3. **#4406 [Bug] VLABench default eef Box rejects all 3,114,872 unified actions** [Open]  
   High-severity bug where VLABench’s default end-effector action bounds reject 100% of actions from the official unified VLABench dataset, completely breaking out-of-the-box evaluation on the widely used benchmark.  
   Community signal: 1 comment, low engagement so far but blocking for benchmark users.  
   [Link](https://github.com/huggingface/lerobot/issues/4406)
4. **#4624 Proposal: out-of-tree fixed-shape FlowEdge deployment plugin** [Open]  
   Proposes official support for an out-of-tree `lerobot_policy_flowedge` deployment plugin for fixed-shape Diffusion Policy, decoupling inference deployment from core LeRobot’s training, observation encoding, and robot driver stacks to enable lightweight edge deployment.  
   Community signal: 1 comment, early feedback stage.  
   [Link](https://github.com/huggingface/lerobot/issues/4624)
5. **#4612 [Performance] GPU busy about 30% of the time when training ACT on 8x B200 at the default settings** [Open]  
   Reports severe GPU underutilization (only 30% busy) when training the widely used ACT policy on 8x NVIDIA B200 GPUs with default configurations, wasting significant compute resources and slowing training throughput.  
   Community signal: 1 comment, active investigation into data loading and pipeline bottlenecks.  
   [Link](https://github.com/huggingface/lerobot/issues/4612)
6. **#4633 [Performance] SmolVLA in-place DynamicCache crop prevents torch.compile and limits inference to 4.8 Hz** [Open]  
   Identifies that SmolVLA’s use of in-place `DynamicCache` cropping during Euler denoise steps breaks `torch.compile` compatibility and caps inference speed at 4.8 Hz, limiting real-time deployment feasibility for the popular lightweight VLA policy. A corresponding fix PR (#4634) was opened the same day.  
   Community signal: 0 comments, fast triage with a ready implementation.  
   [Link](https://github.com/huggingface/lerobot/issues/4633)

---

## 4. Key PR Progress
10 highest-impact PRs updated in the past 24 hours, selected by scope and user value:
1. **#4634 perf(smolvla): static immutable prefix KV cache and torch.compile support (4.2x speedup)** [Open]  
   Replaces SmolVLA’s mutable in-place `DynamicCache` with a static immutable prefix KV cache during Euler denoise steps, enabling `torch.compile` compatibility and delivering a 4.2x inference speedup (from 4.8 Hz to ~20 Hz). Directly resolves #4633.  
   [Link](https://github.com/huggingface/lerobot/pull/4634)
2. **#4637 fix(vlabench): expand Euler action bounds to [-pi, pi]** [Open]  
   Expands VLABench’s default Euler angle action bounds to [-pi, pi], aligning with the absolute radian targets used in official VLABench training datasets. Addresses the core root cause of the #4406 VLABench action rejection bug.  
   [Link](https://github.com/huggingface/lerobot/pull/4637)
3. **#4221 fix(act): support forward(reduction="none") for sample weighting** [Open]  
   Adds a `reduction: str = "mean"` argument to `ACTPolicy.forward`, fixing a crash that occurred when using sample weighting (via `SampleWeighter`) during ACT training. Unblocks weighted imitation learning workflows for one of LeRobot’s most popular policies.  
   [Link](https://github.com/huggingface/lerobot/pull/4221)
4. **#4631 feat(flow-matching): share training-input construction across policies** [Open]  
   Extracts shared flow-matching training input construction logic into a common utility, eliminating duplicate, policy-specific implementations across pi05, EVO1, GROOT, and WALL-X. Completes the flow-matching standardization effort following prior shared inference and sampling primitives.  
   [Link](https://github.com/huggingface/lerobot/pull/4631)
5. **#3967 feat(policies): add LingBot-VLA 2.0** [Open]  
   Adds LingBot-VLA 2.0 as an official `lingbot_vla_v2` policy, featuring a Qwen3-VL-4B backbone, sparse-MoE Qwen2 action expert, and flow-matching over a 55-D unified action space. Expands LeRobot’s VLA ecosystem with a state-of-the-art open-source policy.  
   [Link](https://github.com/huggingface/lerobot/pull/3967)
6. **#4580 feat(rollout): add chunked_sync inference engine for relative-action** [Open]  
   Implements a new `chunked_sync` inference engine that predicts full action chunks and serves them via a local FIFO, eliminating action drift in relative-action policy rollouts by construction. Resolves a longstanding TODO for reliable relative-action deployment.  
   [Link](https://github.com/huggingface/lerobot/pull/4580)
7. **#4564 perf(datasets): resolve Lance videos row ids lazily per batch** [Open]  
   Modifies the Lance dataset reader to resolve video row IDs lazily per batch instead of scanning the entire `videos` table upfront, reducing initial load time for large remote blob datasets by eliminating thousands of pre-flight requests. Delivers significant speedups for large-scale training workflows.  
   [Link](https://github.com/huggingface/lerobot/pull/4564)
8. **#4078 feat(vla): extract shared action-time expert embedding block (pi0, eo1, smolvla)** [Open]  
   Extracts the duplicated action-time embedding block (noised action projection + sine-cosine timestep embedding + MLP) from pi0, EO1, and SmolVLA into a shared `vla_utils.fuse_action_time_embedding` utility. Reduces code duplication and simplifies future VLA policy development.  
   [Link](https://github.com/huggingface/lerobot/pull/4078)
9. **#4538 fix(eval): persist recording datasets across sequential batches in eval_policy** [Open]  
   Moves recording dataset creation outside the per-batch rollout loop in `eval_policy`, fixing `FileExistsError` crashes when running evaluation with more episodes than the configured batch size. Unblocks multi-batch evaluation and benchmark accumulation workflows.  
   [Link](https://github.com/huggingface/lerobot/pull/4538)
10. **#4635 fix(processor): render local migration model cards offline** [Open]  
    Skips Hub-based model card validation during local policy migration when `HF_HUB_OFFLINE=1`, fixing failures in air-gapped or offline development environments. Improves usability for users working without public Hub access.  
    [Link](https://github.com/huggingface/lerobot/pull/4635)

---

## 5. Feature Request Trends
Three core feature directions emerge from recent issues:
1. **Enhanced Human-in-the-Loop (HIL) Imitation Learning Tooling**: The top user-facing request is for cohesive DAgger workflow support, specifically bounded full-episode recording that combines autonomous rollouts and HIL corrections (#4626), aligned with growing community use of LeRobot for real-world interactive imitation learning.
2. **Flexible, High-Performance Deployment & Training**: Users prioritize deployment flexibility (e.g., out-of-tree FlowEdge plugins, #4624) and speed (`torch.compile` compatibility for VLA policies, #4633), alongside improved training efficiency for popular policies like ACT (#4612) to reduce compute waste on high-end hardware.
3. **Robust Benchmark Compatibility**: There is consistent demand for out-of-the-box support for standard benchmarks like VLABench, with users reporting critical compatibility bugs that block evaluation without manual configuration (#4406).

---

## 6. Developer Pain Points
Recurring frustrations surfaced across issues and PRs:
1. **Fragile Policy Migration Toolchain**: Multiple recent fixes (#4457, #4636, #4632, #4635) address edge cases in policy migration, including tuple-typed config fields breaking migration, legacy unused config fields causing initialization errors, incorrect feature type preservation, and offline mode failures. Developers consistently encounter friction when migrating legacy checkpoints or working in air-gapped environments.
2. **Fragmented Flow Matching Implementations**: The series of flow-matching standardization PRs (#4075, #4077, #4631) indicates that policy-specific, duplicated flow-matching logic has been a persistent contributor pain point, causing maintenance overhead, inconsistent behavior across policies, and a higher barrier to entry for new policy contributions.
3. **End-to-End Workflow Bugs in Rollout & Evaluation**: Common user frustrations include action drift in relative-action rollouts (#4580), device mismatches between rollout configs and policy checkpoints (fixed in closed PR #4586), and multi-batch evaluation crashes (#4538). These bugs break end-to-end deployment and benchmarking workflows for real robot use cases.
4. **Suboptimal Default Compute Utilization**: Default configurations underutilize high-end hardware: ACT training uses only 30% of GPU capacity on 8x B200 setups (#4612), and SmolVLA inference is capped at 4.8 Hz without optimizations (#4633). Wasted compute and slow inference are significant pain points for both training and deployment users.

</details>

<details>
<summary><strong>OpenVLA</strong> — <a href="https://github.com/openvla/openvla">openvla/openvla</a></summary>

No activity in the last 24 hours.

</details>

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*