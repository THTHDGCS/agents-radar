# OpenClaw Ecosystem Digest 2026-10-07

> Issues: 0 | PRs: 0 | Projects covered: 3 | Generated: 2026-10-07 03:07 UTC

- [OpenClaw](https://github.com/unitreerobotics/unitree_sdk2)
- [MuJoCo](https://github.com/google-deepmind/mujoco)
- [Drake](https://github.com/RobotLocomotion/drake)

---

## OpenClaw Deep Dive

No activity in the last 24 hours.

---

## Cross-Ecosystem Comparison

# Cross-Project Comparison Report: Embodied AI Agent Infrastructure
*Reporting Window: 24 hours ending 2026-10-07 | Tracked Projects: OpenClaw (Unitree SDK2), MuJoCo, Drake*

## 1. Ecosystem Overview
The open-source embodied AI agent and physical personal assistant ecosystem relies on a layered stack of physics simulation, robot control, and optimization tools to enable sim-to-real training, deployment, and validation of AI-powered robotic systems. The three tracked projects cover complementary tiers of this stack: OpenClaw (Unitree SDK2) provides low-level hardware control interfaces for Unitree legged robots, MuJoCo is a de facto standard physics engine for robotics and reinforcement learning (RL) training, and Drake offers a full-stack toolkit for model-based robotics design and optimization. Over the 24-hour reporting window, activity across the ecosystem was moderate, focused on bug resolution, cross-platform expansion, and long-standing backlog reduction rather than high-impact new feature launches. No new stable releases were published across any tracked project, with most maintainer teams operating in a pre-release or maintenance cadence.

## 2. Activity Comparison
Metrics are sourced directly from 24-hour repository activity data. The 24h Health Score (1–10, higher = healthier maintenance cadence) is calculated based on critical bug resolution rate, PR merge throughput, backlog progress, and absence of unaddressed high-severity issues.

| Project | Updated Issues (Total / Open / Closed) | Updated PRs (Total / Merged+Closed / Open) | Release Status | 24h Health Score |
|---------|----------------------------------------|--------------------------------------------|----------------|------------------|
| OpenClaw (Unitree SDK2) | 0 / 0 / 0 | 0 / 0 / 0 | No 24h public activity; no new releases tracked | N/A (insufficient activity data) |
| MuJoCo | 5 / 3 / 2 | 14 / 13 / 1 | No new releases in window | 8.5/10 |
| Drake | 5 / 4 / 1 | 13 / 5 / 8 | No new releases; v1.58.0 minor release in preparation (draft release notes open) | 8/10 |

*Score rationale: MuJoCo resolved 1 critical runtime segfault and 1 8-month-old backlog issue, merged 13 cross-functional PRs, and has only 1 pending high-severity issue. Drake resolved 1 medium-high solver correctness bug, merged new feature and toolchain updates, and has active long-term feature development in progress.*

## 3. OpenClaw's Position
OpenClaw is the codename for Unitree Robotics’ official `unitree_sdk2`, a hardware-specific low-level control SDK occupying a distinct, deployment-focused layer of the embodied AI stack relative to general-purpose simulation tools MuJoCo and Drake.
- **Advantages vs. peers**: Purpose-built for Unitree legged robot hardware, it provides native low-latency access to motor control, real-time sensor streams, and robot state management capabilities that simulation-only tools cannot offer. It serves as a core reference implementation for sim-to-real deployment pipelines targeting Unitree platforms, eliminating the need for teams to build custom hardware abstraction layers for legged robots.
- **Technical approach differences**: Unlike MuJoCo and Drake, which prioritize hardware-agnostic abstracted modeling for design, training, and validation, OpenClaw is tightly coupled to Unitree’s hardware architecture. It minimizes abstraction layers to prioritize real-time execution reliability and control latency, with no built-in simulation or mathematical optimization functionality.
- **Community size comparison**: OpenClaw has a smaller, vertically specialized community concentrated among Unitree robot owners, legged robotics researchers, and hardware deployment engineers. In contrast, MuJoCo and Drake serve broader cross-sector user bases spanning aerospace, industrial robotics, RL research, and game development, as evidenced by the higher volume of issues, PRs, and diverse user segments reported in their 24h activity logs. The lack of 24h public activity for OpenClaw likely reflects a feature-complete, stable SDK with updates tied to new hardware launches rather than frequent software iterations.

## 4. Shared Technical Focus Areas
Three core requirements emerge across the general-purpose simulation/optimization projects, with indirect relevance to OpenClaw’s hardware deployment use case:
1. **Cross-Platform Compatibility & CI Reliability**
   - *Projects*: MuJoCo, Drake
   - *Specific needs*: Both teams are expanding platform coverage and build toolchain compatibility to reduce deployment friction across user environments. MuJoCo merged PRs adding Linux ARM64 and Windows Clang to its build matrix, fixing Windows ccache compatibility, upgrading CI workflows to Node.js 24, and resolving GCC 15 compatibility warnings. Drake merged Xcode 27 Apple Clang compatibility fixes, is evaluating an x86_64-v2 minimum microarchitecture target for improved performance, and is working toward full Xcode 27 CI support. Both prioritize CI speed via dependency caching to accelerate development cycles.
2. **Modular Robot Model Parsing Robustness**
   - *Projects*: MuJoCo, Drake
   - *Specific needs*: Both projects address pain points with parsing complex, modular robot models built with standard description formats, as users increasingly adopt reusable component libraries to reduce design overhead. MuJoCo resolved an 8-month-old bug causing keyframe validation failures for MJCF models using `<replicate>` tags (for procedurally generated modular robot trees). Drake has advanced a 3.5-year-old feature request for closed kinematic chain parsing from SDF/URDF, enabling declarative definition of complex topologies (e.g., legged robots, underactuated grippers) without manual programmatic constraint setup.
3. **Simulation Interoperability & Sim-to-Real Consistency**
   - *Projects*: MuJoCo, Drake
   - *Specific needs*: Both projects prioritize improvements to sim-to-real workflow reliability and cross-tool interoperability, a core requirement for production embodied AI agents. MuJoCo is addressing a high-severity issue where closed-loop behavior diverges between CPU MuJoCo (deployment reference) and GPU-accelerated `mujoco_warp` (RL training engine), despite identical per-step forces. Drake is developing compatibility for MuJoCo mesh `refpos`/`refquat` attributes to fix vertex placement mismatches when importing MuJoCo models, enabling seamless asset sharing across tools.

## 5. Differentiation Analysis
The three projects differ sharply in feature focus, target users, and technical architecture, reflecting their distinct roles in the embodied AI stack:

| Dimension | OpenClaw (Unitree SDK2) | MuJoCo | Drake |
|-----------|--------------------------|--------|-------|
| **Feature Focus** | Low-level hardware control and sensor abstraction for Unitree legged robots; no simulation/optimization capabilities | High-performance, accurate physics simulation; GPU-accelerated RL training support; ecosystem plugins (Unity, Python/Wasm) | Full-stack robotics toolkit: physics simulation + mathematical optimization (QP, nonlinear programming) + kinematics/dynamics + model parsing |
| **Target Users** | Unitree robot operators, legged robotics deployment engineers, hardware-focused AI teams | RL researchers, aerospace engineers (NASA), industrial robotics teams, Unity simulation developers, robot learning framework maintainers | Model-based robotics researchers, trajectory optimization teams, formal verification engineers, complex manipulation system developers |
| **Technical Architecture** | Hardware-coupled, lightweight, optimized for real-time execution on ARM edge platforms; minimal abstraction to reduce latency | Physics-first C/C++ core with CPU/GPU runtime support; modular language bindings (Python, Wasm) and plugins; optimized for simulation throughput | Modular, optimization-centric C++ architecture with a solver abstraction layer supporting multiple backends; designed for extensibility and end-to-end robotics pipeline integration |

## 6. Community Momentum & Maturity
Projects fall into three distinct activity and maturity tiers based on 24h activity data and backlog management patterns:
1. **High Activity, Mature & Steadily Iterating: MuJoCo**
   MuJoCo has the highest 24h PR throughput (13 merged/closed) of the tracked projects, with active maintenance across core runtime, build infrastructure, ecosystem tooling, and dependencies. Maintainers demonstrate rapid turnaround for high-severity issues (4-day resolution of a critical CCD segfault) and consistent backlog clearance (resolving an 8-month-old keyframe validation bug). As a de facto standard for robotics simulation, it balances critical bug fixes, long-term platform expansion, and ecosystem investment with a well-established maintenance cadence.
2. **Moderate-High Activity, Mature with Long-Term Feature Investment: Drake**
   Drake has moderate PR throughput (5 merged/closed, 8 open under review) with work spanning new feature integration (DAQP dense QP solver), bug fixes, toolchain compatibility, and long-requested backlog features (closed kinematic chain parsing). Its structured release cadence (draft v1.58.0 notes open) and praise from external maintainers for engineering quality reflect high maturity. Iteration speed is slightly slower than MuJoCo due to its full-stack scope, but progress on 3+ year-old community requests demonstrates sustained investment in high-impact features.
3. **Low Visible Activity, Likely Feature-Stable: OpenClaw**
   No public 24h activity indicates either a focus on internal hardware-coupled updates not reflected in the public repository, or a feature-complete state for current Unitree hardware generations. As a core reference SDK for commercially available legged robots, OpenClaw’s stability is its key value proposition: deployment teams prioritize predictable, low-breaking-change SDKs over frequent feature additions, aligning with its low public update cadence.

## 7. Trend Signals
Four key industry trends emerge from community feedback and project activity, with clear value for AI agent developers building embodied or physical personal assistant systems:
1. **Sim-to-Real Consistency is a Production-Critical Requirement**
   - *Evidence*: MuJoCo’s top emerging high-impact issue is cross-engine behavioral divergence between training (GPU) and deployment (CPU) runtimes, which directly undermines RL policy transfer. NASA’s use of MuJoCo for aerospace sim-to-real testing and Drake’s work to reduce cross-tool simulation mismatches further highlight this priority.
   - *Value for developers*: Teams building physical AI agents must prioritize simulation tools with validated cross-runtime consistency to avoid costly sim-to-real gap debugging. Selecting actively maintained engines with a track record of simulation correctness reduces deployment risk and improves policy transfer success rates.
2. **Edge-Optimized Cross-Platform Support is a Fast-Growing Priority**
   - *Evidence*: MuJoCo’s Linux ARM64 build expansion and aarch64 packaging fixes respond to demand from teams deploying robot learning frameworks on ARM edge hardware. Drake’s x86_64-v2 target evaluation and Xcode 27 support reflect focus on optimizing for modern edge and developer hardware.
   - *Value for developers*: As embodied AI agents move from cloud training to on-robot edge deployment, natively supported ARM/edge tooling reduces porting overhead and improves on-device performance. Tools with active cross-platform roadmaps avoid deployment bottlenecks and vendor lock-in.
3. **Modular Declarative Modeling Reduces Custom Hardware Development Overhead**
   - *Evidence*: MuJoCo’s `<replicate>` tag fix addresses pain points for teams building reusable robot component libraries, while Drake’s 3.5-year-long community demand for closed kinematic chain parsing reflects widespread frustration with manual constraint setup for modular robot designs.
   - *Value for developers*: Teams building custom robot hardware for specialized AI agent use cases (e.g., assistive robotics, industrial manipulation) can drastically reduce modeling time by using tools that support modular, declarative robot description formats, freeing resources to focus on agent intelligence rather than low-level model setup.
4. **Interoperable Toolchains Enable Best-of-Breed Embodied AI Pipelines**
   - *Evidence*: Drake’s MuJoCo asset compatibility work enables seamless workflow integration across simulation and optimization tools, while MuJoCo’s Unity plugin feature gap highlights demand for integration with game engine-based interactive simulation workflows.
   - *Value for developers*: No single tool covers the entire embodied AI development pipeline (training, optimization, verification, deployment). Tools with open interoperability standards and compatible asset formats reduce integration work and allow teams to select the best tool for each stage of development.

---

## Peer Project Reports

<details>
<summary><strong>MuJoCo</strong> — <a href="https://github.com/google-deepmind/mujoco">google-deepmind/mujoco</a></summary>

# MuJoCo Project Digest (2026-10-07)
Data sourced from [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco), covering activity in the 24-hour window ending 2026-10-07.

---

## 1. Today's Overview
For the 24-hour window ending 2026-10-07, the MuJoCo project saw moderate core maintenance and ecosystem activity, with 5 updated issues (3 open, 2 closed) and 14 updated pull requests (1 open, 13 merged/closed) and no new releases. The majority of merged PRs focus on build infrastructure improvements, cross-platform support expansion, and routine dependency updates, alongside two core runtime bug fixes for keyframe validation and native CCD segfaults. Newly opened issues span high-priority use cases including cross-engine simulation consistency for RL training, aarch64 packaging gaps, and Unity plugin feature parity with core MuJoCo functionality. Overall project health is strong, with maintainers actively addressing both long-standing backlog items and high-severity runtime bugs while investing in CI/CD reliability and platform coverage.

---

## 2. Releases
No new MuJoCo versions were published in the 24-hour window ending 2026-10-07. No recent release entries are included in the tracked dataset.

---

## 3. Project Progress
Thirteen pull requests were merged or closed in the reporting window, spanning core bug fixes, build infrastructure, ecosystem tooling, and dependency maintenance:

### Core Runtime Bug Fixes
- [PR #3074: Keyframe validation fixes](https://github.com/google-deepmind/mujoco/pull/3074): Resolves keyframe validation errors for MJCF models using `<replicate>` tags by rebuilding the model tree prior to joint offset calculation and hardening validation logic for dynamically generated joints. Closes Issue #3071.
- Resolved: [Issue #3646: Native CCD (EPA) horizon buffer overflow segfault](https://github.com/google-deepmind/mujoco/issues/3646): Fixed deterministic crashes during inverse kinematics loops with cylinder-mesh geometry pairs using the native CCD backend.

### Build & CI Infrastructure Improvements
- [PR #3639: Add Linux ARM64 and Windows Clang to build matrix](https://github.com/google-deepmind/mujoco/pull/3639): Expands official build testing to cover Linux ARM64 and Windows Clang configurations, laying groundwork for broader platform support for Python wheels and native binaries.
- [PR #3660: Disable LTO on windows-clang and fix Python bindings ccache on Windows](https://github.com/google-deepmind/mujoco/pull/3660): Reduces Windows Clang build times by disabling uncached LTO (saving ~9 minutes per build) and fixes ccache compatibility for Python bindings on Windows by normalizing path formats.
- [PR #3661: Use external deps cache in Python bindings build and mjx job](https://github.com/google-deepmind/mujoco/pull/3661): Extends Eigen dependency caching to Python binding and MJX build jobs, eliminating redundant upstream downloads and speeding up CI pipelines.
- [PR #3658: Update GitHub Actions workflows to Node.js 24 actions](https://github.com/google-deepmind/mujoco/pull/3658): Upgrades all CI workflow actions to Node.js 24-compatible versions, resolving Node.js 20 deprecation warnings and ensuring long-term CI stability.
- [PR #3205: Fix GCC 15 compatibility warnings](https://github.com/google-deepmind/mujoco/pull/3205): Fixes two GCC 15 `-Werror` warnings (discarded qualifiers in `engine_print.c`, alloc-size overflow in `engine_plugin.cc`) to support compilation with newer GCC toolchains.

### Ecosystem & Tooling
- [PR #3268: [Unity plugin] Surface a clear error when mesh asset is missing](https://github.com/google-deepmind/mujoco/pull/3268): Adds explicit error messaging for missing or misnamed mesh assets in the Unity plugin, replacing silent null reference failures and improving debugging UX for Unity users. Related to Issue #1354.

### Routine Dependency Updates
- Wasm/JavaScript:
  - [PR #3649: Bump brace-expansion from 2.1.1 to 2.1.7 in /wasm](https://github.com/google-deepmind/mujoco/pull/3649)
  - [PR #3657: Bump source-map-js from 1.2.1 to 1.2.2 in /wasm](https://github.com/google-deepmind/mujoco/pull/3657)
  - [PR #3467: Bump postcss from 8.5.15 to 8.5.29 in /wasm](https://github.com/google-deepmind/mujoco/pull/3467)
- Python:
  - [PR #3538: Bump pip from 26.1.2 to 26.2 in /mjx](https://github.com/google-deepmind/mujoco/pull/3538)
  - [PR #3537: Bump pip from 26.1 to 26.2 in /python](https://github.com/google-deepmind/mujoco/pull/3537)
  - [PR #3416: Bump pillow from 12.2.0 to 12.3.0 in /python](https://github.com/google-deepmind/mujoco/pull/3416)

---

## 4. Community Hot Topics
Ranked by comment count (the primary available activity metric for this dataset), with analysis of underlying user needs:
1. **Top Active Issue: [Issue #3071: Keyframe validation error when using replicate tags](https://github.com/google-deepmind/mujoco/issues/3071)** (4 comments, closed 2026-10-06)
   This 8-month-old issue was submitted by a NASA robotics engineer using MuJoCo via `ros2_control` for aerospace sim-to-real testing. The comment thread focused on edge cases in MJCF keyframe parsing when `<replicate>` tags generate dynamic joint trees, reflecting a core need for robust validation of modular, procedurally generated robot models — a common pattern in industrial and aerospace robotics where reusable component libraries reduce development overhead. The fix was merged via PR #3074.
2. **Emerging High-Impact Topic: [Issue #3663: Same policy, same seeds: 99.6% on mujoco_warp vs 87.4% on mujoco — per-step forces bit-identical, closed-loop behavior diverges](https://github.com/google-deepmind/mujoco/issues/3663)** (0 comments, opened 2026-10-07)
   Newly filed by a sim-to-real manipulation researcher, this issue identifies a critical behavioral divergence between CPU MuJoCo (deployment reference engine) and GPU-accelerated `mujoco_warp` (large-scale RL training engine), despite identical per-step force calculations. While not yet discussed, this addresses a top pain point for the global RL research community, which relies on consistent simulation dynamics to ensure trained policies transfer reliably between training clusters and deployment hardware.
3. **Packaging Priority Topic: [Issue #3659: Missing aarch64 wheel for python 3.11 in mujoco version 3.15](https://github.com/google-deepmind/mujoco/issues/3659)** (0 comments, opened 2026-10-06)
   Filed by a research engineer at Neuracore (maintainers of the NeuracoreAI robot learning framework), this issue highlights a packaging gap blocking ARM64 deployments of MuJoCo 3.15. With the recent addition of Linux ARM64 to the official build matrix (PR #3639), this topic is likely to see rapid resolution and community engagement from other ARM64 users.

---

## 5. Bugs & Stability
Bugs updated in the 24-hour window, ranked by severity, with fix status noted:

### Critical (Crashes / Data Corruption)
- [Issue #3646: Native CCD (EPA): horizon buffer overflow (nedges > 24) in addEdge causes SIGSEGV in projectOriginPlane](https://github.com/google-deepmind/mujoco/issues/3646) **(CLOSED, resolved 2026-10-06)**
  Details: A deterministic segfault triggered during `mj_forward` calls in inverse kinematics loops, occurring with a two-geom model (cylinder + public mesh) using the native CCD (EPA) backend. Reported by a user simulating a SO-101 robot arm manipulation cell. No linked fix PR is listed in the dataset, but the issue closure confirms resolution.

### High (Functional Breakdown / Simulation Validity / Deployment Blockers)
- [Issue #3663: Same policy, same seeds: 99.6% on mujoco_warp vs 87.4% on mujoco — per-step forces bit-identical, closed-loop behavior diverges](https://github.com/google-deepmind/mujoco/issues/3663) **(OPEN, reported 2026-10-07)**
  Details: A critical behavioral divergence between CPU MuJoCo (reference deployment engine) and GPU-accelerated `mujoco_warp` (RL training engine), where identical policies and random seeds produce drastically different task success rates (99.6% vs 87.4%) despite bit-identical per-step force outputs. No fix PR exists yet; this issue threatens the validity of sim-to-real RL workflows that use `mujoco_warp` for large-scale training.
- [Issue #3659: Missing aarch64 wheel for python 3.11 in mujoco version 3.15](https://github.com/google-deepmind/mujoco/issues/3659) **(OPEN)**
  Details: The MuJoCo 3.15 release lacks Python 3.11 wheels for the aarch64 platform, blocking deployment for robot learning teams (e.g., Neuracore) targeting ARM64 edge or robot hardware. No fix PR is listed, but the recent merge of PR #3639 (adding Linux ARM64 to the build matrix) suggests this will likely be resolved in an upcoming patch release.
- [Issue #3071: Keyframe validation error when using replicate tags](https://github.com/google-deepmind/mujoco/issues/3071) **(CLOSED, resolved 2026-10-06)**
  Details: Keyframe validation failed for MJCF models using `<replicate>` tags, due to outdated joint tree state during offset calculation. Fixed via [PR #3074: Keyframe validation fixes](https://github.com/google-deepmind/mujoco/pull/3074).

---

## 6. Feature Requests & Roadmap Signals
Below is the active user feature request from the reporting window, plus roadmap inferences based on recent merged work:

### Top User Feature Request
- [Issue #3662: Why doesn't unity plugin support Mujoco baked components?](https://github.com/google-deepmind/mujoco/issues/3662) **(OPEN, enhancement)**
  Request: Native support for pre-baked (serialized) MuJoCo components in the official Unity plugin, eliminating runtime MJCF-to-Unity asset conversion overhead. The user notes that core MuJoCo already supports binary serialization/deserialization of assets, but the Unity plugin does not expose this functionality, forcing users to modify upstream packages to implement the feature.

### Roadmap Predictions (Data-Backed by Recent Activity)
1. **Near-term (next patch release, 3.15.1): aarch64 Python 3.11 wheel support** – The merge of PR #3639 (Linux ARM64 build matrix) directly addresses the infrastructure gap behind Issue #3659, making this packaging fix highly likely in the next patch.
2. **Short-term (1-2 minor releases): Unity plugin UX and feature expansion** – The recent merge of PR #3268 (Unity mesh error messaging) signals active maintainer investment in the Unity plugin, and baked component support (Issue #3662) is a low-to-moderate lift feature that leverages existing core MuJoCo serialization functionality.
3. **Ongoing: Build performance and cross-platform support** – Multiple merged PRs (#3660, #3661, #3658, #3205) focus on CI speed, compiler compatibility, and new platform targets, indicating sustained investment in making MuJoCo buildable and deployable across a wider range of environments.

---

## 7. User Feedback Summary
All feedback is sourced directly from issue submitters in the reporting window, representing diverse MuJoCo user segments:

### Represented Use Cases
1. **Aerospace robotics (NASA):** Uses MuJoCo via `ros2_control` for sim-to-real testing and capability development of robotic systems.
2. **Sim-to-real RL research:** Uses CPU MuJoCo as a deployment reference and `mujoco_warp` for large-scale GPU-accelerated manipulation policy training.
3. **Industrial robotics:** Uses MuJoCo Python bindings for inverse kinematics and manipulation cell simulation for the SO-101 robot arm.
4. **Robot learning framework development (Neuracore):** Distributes MuJoCo as a core dependency of their open-source robot learning library, targeting aarch64 hardware.
5. **Unity simulation development:** Uses the official MuJoCo Unity plugin for interactive simulation workflows.

### Key Pain Points
1. **Cross-engine simulation inconsistency:** Divergence between core MuJoCo and `mujoco_warp` closed-loop behavior undermines RL training validity, even when low-level physics calculations match.
2. **Platform packaging gaps:** Missing aarch64 Python 3.11 wheels for 3.15 block downstream ARM64 deployments.
3. **MJCF validation edge cases:** Modular model features like `<replicate>` tags break keyframe validation, creating friction for teams building reusable robot component libraries.
4. **Unity plugin feature parity gap:** Lack of access to core MuJoCo serialization features forces users to fork or modify upstream packages, adding maintenance burden.

### Satisfaction Signals
No explicit user dissatisfaction with maintainer responsiveness or overall project direction is present in the dataset. The continued use of MuJoCo for high-stakes use cases (NASA aerospace testing, industrial robot simulation, production RL training) indicates strong baseline trust in the engine. The resolution of the long-standing keyframe validation bug and the rapid 4-day turnaround on the critical CCD segfault further suggest maintainer responsiveness meets user expectations for high-severity issues.

---

## 8. Backlog Watch
> Note: This digest only includes issues and PRs updated in the 24-hour window ending 2026-10-07, so long-unanswered backlog items with no recent activity are not represented.

### Pending Triage (Open, Updated in Last 24h)
1. [Issue #3663: mujoco_warp vs MuJoCo closed-loop behavioral divergence](https://github.com/google-deepmind/mujoco/issues/3663) (opened 2026-10-07): High-severity simulation consistency issue critical for RL research workflows, awaiting initial maintainer triage and root cause analysis.
2. [Issue #3659: Missing aarch64 Python 3.11 wheel for MuJoCo 3.15](https://github.com/google-deepmind/mujoco/issues/3659) (opened 2026-10-06): Packaging blocker for ARM64 deployments, likely resolvable using the recently expanded Linux ARM64 build matrix.
3. [Issue #3662: Unity plugin baked component support](https://github.com/google-deepmind/mujoco/issues/3662) (opened 2026-10-06): Enhancement request for Unity ecosystem improvement, pending maintainer prioritization.
4. [PR #3656: Bump fsspec from 2024.10.0 to 2026.6.0 in /python](https://github.com/google-deepmind/mujoco/pull/3656) (opened 2026-10-06): Routine Python dependency update from dependabot, awaiting review and merge.

### Recently Cleared Long-Running Backlog Items (Open >3 Months, Closed in Reporting Window)
- [Issue #3071 / PR #3074: Keyframe validation error with replicate tags](https://github.com/google-deepmind/mujoco/issues/3071): Open for ~8 months (Feb 2026 – Oct 2026), resolving a long-standing MJCF validation edge case for modular robot models.
- [PR #3205: Fix GCC 15 compatibility warnings](https://github.com/google-deepmind/mujoco/pull/3205): Open for ~6 months (Mar 2026 – Oct 2026), fixing compiler compatibility for newer GCC toolchains.
- [PR #3268: Unity plugin missing mesh error messaging](https://github.com/google-deepmind/mujoco/pull/3268): Open for ~5 months (May 2026 – Oct 2026), improving debugging UX for Unity plugin users.

</details>

<details>
<summary><strong>Drake</strong> — <a href="https://github.com/RobotLocomotion/drake">RobotLocomotion/drake</a></summary>

# Drake Project Digest (2026-10-07)
*Data source: GitHub repository [RobotLocomotion/drake](https://github.com/RobotLocomotion/drake), covering activity in the 24-hour window ending 2026-10-07*

## 1. Today's Overview
For the 24-hour reporting window, the Drake robotics toolkit saw moderate development activity, with 5 updated issues (4 open/active, 1 closed), 13 updated pull requests (8 open, 5 merged/closed), and no new formal releases. Work spans core focus areas including multibody parsing capabilities, mathematical solver reliability and expansion, build system/CI compatibility updates, and routine dependency maintenance, with a draft v1.58.0 release notes PR indicating an upcoming formal release. A long-requested closed kinematic chain parsing feature has advanced to a draft implementation, while a recently reported NLopt solver correctness bug has been fully resolved. Overall, the project demonstrates a steady maintenance cadence paired with iterative advancement of high-impact user-facing features.

## 2. Releases
No new releases were published during the 24-hour reporting window. A draft PR for v1.58.0 release notes ([#25059](https://github.com/RobotLocomotion/drake/pull/25059)) is open, indicating a forthcoming minor release in the near term.

## 3. Project Progress
Five pull requests were merged or closed in the reporting window, advancing bug fixes, new features, infrastructure compatibility, and dependency maintenance:
### New Features
- **DAQP dense active-set QP solver integration** ([PR #25035](https://github.com/RobotLocomotion/drake/pull/25035)): Contributed by the DAQP upstream maintainer, this PR adds a new dense active-set quadratic programming solver to Drake's solver portfolio, expanding options for convex optimization workloads.
### Bug Fixes
- **NLopt NaN solution success status fix** ([PR #25053](https://github.com/RobotLocomotion/drake/pull/25053)): Resolves Issue [#24995](https://github.com/RobotLocomotion/drake/issues/24995) by ensuring NLopt returns a failure status when it produces NaN solutions, instead of incorrectly reporting `kSolutionFound`.
- **Partial revert of ruff linter fixes** ([PR #25061](https://github.com/RobotLocomotion/drake/pull/25061)): Reverts unintended changes to legacy test syntax from a prior "ruff up" linter update, preserving intentional test examples written with legacy code patterns.
### Infrastructure & Compatibility
- **Xcode 27 Apple Clang compatibility fix** ([PR #25014](https://github.com/RobotLocomotion/drake/pull/25014)): Addresses LLVM/Apple Clang compatibility issues from Xcode 27 by using dedicated mathematical comparators instead of template specializations, advancing progress on Xcode 27 CI support (Issue [#25001](https://github.com/RobotLocomotion/drake/issues/25001)).
### Dependency Updates
- **Ipopt internal dependency upgrade to v3.14.20** ([PR #25048](https://github.com/RobotLocomotion/drake/pull/25048)): Part of the October 2026 externals upgrade effort (Issue [#25028](https://github.com/RobotLocomotion/drake/issues/25028)), updating the interior-point optimizer to its latest patch release.

## 4. Community Hot Topics
All tracked items have 0 user 👍 reactions, and PR comment data is unavailable in the provided dataset. Rankings are based on issue comment counts, with associated active PRs noted:
1. **Closed kinematic chain parsing from SDF/URDF** (Issue [#18803](https://github.com/RobotLocomotion/drake/issues/18803), 25 comments)
   - This 3.5-year-old feature request is the most actively discussed item in the window. It reflects a persistent user need for declarative definition of closed-chain robot systems (common in legged robots like Cassie, and underactuated grippers) via standard robot description formats, eliminating the need for manual programmatic constraint setup. The recent opening of draft PR [#25060](https://github.com/RobotLocomotion/drake/pull/25060) (adding SDF support for unassembled closed-topology mechanisms) signals active progress, making this a top community priority.
2. **Xcode 27 CI and build support** (Issue [#25001](https://github.com/RobotLocomotion/drake/issues/25001), 5 comments)
   - This recent request tracks compatibility with the newly released Xcode 27 toolchain, driven by macOS-based Drake users and developers who need supported, CI-validated builds for the latest Apple development environment. The merged PR [#25014](https://github.com/RobotLocomotion/drake/pull/25014) addressing Apple Clang compatibility shows steady progress on this infrastructure goal.

## 5. Bugs & Stability
No new bugs were reported in the 24-hour window. One pre-existing medium-high severity bug was resolved:
| Severity | Bug Description | Status | Fix |
|----------|-----------------|--------|-----|
| Medium-High | **NLopt Augmented Lagrangian Solver Returns NaN Solution with Status `kSolutionFound`** ([Issue #24995](https://github.com/RobotLocomotion/drake/issues/24995)): NLopt failed to handle NaN values internally, returning a success status and invalid NaN solutions, which could cause incorrect downstream results and wasted compute time. | Resolved | Fixed via merged PR [#25053](https://github.com/RobotLocomotion/drake/pull/25053), which enforces a failure status when NaN solutions are detected. |

Two additional bug-fix PRs are open and under review, addressing memory safety and error visibility issues (see Section 8: Backlog Watch).

## 6. Feature Requests & Roadmap Signals
### Likely to appear in upcoming v1.58.0 release
These features have merged PRs and are tracked in the draft v1.58.0 release notes:
- DAQP dense active-set QP solver integration ([PR #25035](https://github.com/RobotLocomotion/drake/pull/25035))
- NLopt NaN solution correctness fix ([PR #25053](https://github.com/RobotLocomotion/drake/pull/25053))
- Ipopt 3.14.20 dependency upgrade ([PR #25048](https://github.com/RobotLocomotion/drake/pull/25048))
- Xcode 27 Apple Clang compatibility fixes ([PR #25014](https://github.com/RobotLocomotion/drake/pull/25014))

### In-progress features targeted for near-term releases (1-2 future versions)
- **Closed kinematic chain parsing for SDFormat** (Issue [#18803](https://github.com/RobotLocomotion/drake/issues/18803), Draft PR [#25060](https://github.com/RobotLocomotion/drake/pull/25060)): A draft implementation for SDF support of unassembled closed-topology mechanisms is now open. While marked WIP and not merge-ready, active development on this long-requested feature suggests it may land in the next 1-2 releases once finalized, with potential URDF support to follow.
- **MuJoCo mesh asset `refpos`/`refquat` compatibility** (PR [#24985](https://github.com/RobotLocomotion/drake/pull/24985)): This PR adds parsing for MuJoCo's mesh reference pose attributes to fix vertex placement mismatches, improving parity with MuJoCo asset workflows. It is open and under review, with a high chance of landing in the next release if review completes promptly.
- **x86_64-v2 minimum microarchitecture target** (PR [#25051](https://github.com/RobotLocomotion/drake/pull/25051)): This build system change raises the minimum required x86_64 microarchitecture to v2 for improved performance on modern CPUs. It is under review, with inclusion in the next release dependent on validation of compatibility with legacy supported systems.
- **Full Xcode 27 CI support** (Issue [#25001](https://github.com/RobotLocomotion/drake/issues/25001)): Initial code compatibility fixes are merged, but remaining tasks (macOS Tahoe Xcode 27 base image creation, CI deployment) are incomplete. Full support is expected in the next 1-2 releases.

## 7. User Feedback Summary
### Pain Points
1. **Closed-chain definition friction**: Users commenting on Issue [#18803](https://github.com/RobotLocomotion/drake/issues/18803) over 3+ years report that programmatic definition of closed kinematic chain constraints is error-prone and cumbersome, especially for common robot designs like Cassie and underactuated grippers. They request native support in standard robot description formats to streamline modeling workflows.
2. **Silent solver failures**: The NLopt bug ([#24995](https://github.com/RobotLocomotion/drake/issues/24995)) created a critical pain point where users could unknowingly receive invalid NaN solutions marked as successful, leading to wasted computational resources and potential errors in downstream robotics workflows such as trajectory optimization.
3. **Cross-platform toolchain lag**: macOS developers using the latest Xcode 27 release face unsupported build environments (tracked in Issue [#25001](https://github.com/RobotLocomotion/drake/issues/25001)), creating friction for users on cutting-edge Apple development tools.
4. **MuJoCo asset parity gaps**: Users importing MuJoCo models into Drake encounter mismatched mesh positioning due to missing support for `refpos` and `refquat` attributes (PR [#24985](https://github.com/RobotLocomotion/drake/pull/24985), fixing Issue [#22488](https://github.com/RobotLocomotion/drake/issues/22488)), requiring manual adjustments to align assets.

### Positive Feedback
- External contributor darnstrom, maintainer of the DAQP solver, praised Drake in PR [#25035](https://github.com/RobotLocomotion/drake/pull/25035) as "carefully engineered, documented and tested" and a "high bar for open-source robotics software," reflecting strong community satisfaction with the project's quality, scope, and maintenance standards.

## 8. Backlog Watch
The following long-standing or high-impact backlog items (from the 24-hour updated set) warrant maintainer attention to reduce user friction and backlog size:
1. **Solver error visibility: Name quadratic cost on PSD decomposition failure** ([PR #24932](https://github.com/RobotLocomotion/drake/pull/24932))
   - Open since 2026-08-31 (~5 weeks), this PR addresses long-standing Issue [#20892](https://github.com/RobotLocomotion/drake/issues/20892) by adding clear error messaging that identifies the specific `QuadraticCost` causing PSD decomposition failures, rather than throwing generic errors. This quality-of-life improvement for solver users has been in the backlog for over a month and would benefit from prioritized review.
2. **MuJoCo compatibility and pydrake memory fixes** (PRs [#24985](https://github.com/RobotLocomotion/drake/pull/24985), [#24986](https://github.com/RobotLocomotion/drake/pull/24986))
   - Both PRs have been open since 2026-09-10 (~4 weeks):
     - PR #24985 fixes MuJoCo mesh vertex placement mismatches, addressing a user-reported compatibility gap.
     - PR #24986 fixes a memory lifecycle bug in pydrake's nested Iris options for inline `MathematicalProgram`s, preventing dangling references and potential crashes.
   - Both address concrete user pain points and are candidates for prioritized review.
3. **Long-standing feature: Closed kinematic chain parsing** ([Issue #18803](https://github.com/RobotLocomotion/drake/issues/18803))
   - Open since February 2023 (3.5+ years) with 25 user comments, this is one of the longest-running high-demand feature requests in the updated set. While a draft PR ([#25060](https://github.com/RobotLocomotion/drake/pull/25060)) has recently been opened, sustained maintainer attention will be needed to move the implementation from draft to production-ready, given the complexity of parsing extensions and cross-format (SDF/URDF) considerations.

</details>

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*