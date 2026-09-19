# OpenClaw Ecosystem Digest 2026-09-19

> Issues: 0 | PRs: 0 | Projects covered: 3 | Generated: 2026-09-19 02:04 UTC

- [OpenClaw](https://github.com/unitreerobotics/unitree_sdk2)
- [MuJoCo](https://github.com/google-deepmind/mujoco)
- [Drake](https://github.com/RobotLocomotion/drake)

---

## OpenClaw Deep Dive

No activity in the last 24 hours.

---

## Cross-Ecosystem Comparison

# Cross-Project Ecosystem Comparison Report | 2026-09-19
*Focus: Embodied AI Agent Infrastructure (Simulation & Robot Control)*

---

## 1. Ecosystem Overview
The open-source personal AI assistant and embodied agent ecosystem relies on physics simulation, robot control SDKs, and controls libraries as foundational infrastructure for training, validation, and real-world deployment of physically interactive agent workflows. Over the 24-hour reporting window ending 2026-09-19, core projects in this stack exhibited mixed activity levels, with mature simulation platforms delivering high-impact bug fixes and feature iterations, while lower-level robot SDKs saw quieter development cycles. Community feedback across the ecosystem prioritizes reducing sim-to-real transfer gaps, improving efficiency for large-scale batch agent training, and expanding cross-platform support for both simulation and physical robot deployments. These tools directly enable personal AI assistant use cases from home service robots to industrial collaborative agents by providing the reliable simulation and control layers required for safe, performant agent operation.

---

## 2. Activity Comparison
Metrics are sourced from 24-hour GitHub activity in the reporting window. The 24h Health Score is a 1–10 composite of activity volume, bug resolution velocity, community engagement, and backlog progress captured in the window; it does not reflect long-term project stability.

| Metric | OpenClaw (unitree_sdk2) | MuJoCo (google-deepmind) | Drake (RobotLocomotion) |
|--------|--------------------------|---------------------------|--------------------------|
| Total Updated Issues | 0 | 8 | 2 |
| ├─ Open/Active Issues | 0 | 2 | 2 |
| └─ Closed Issues | 0 | 6 | 0 |
| Total Updated PRs | 0 | 11 | 1 |
| ├─ Open PRs | 0 | 2 | 1 |
| └─ Merged/Closed PRs | 0 | 9 | 0 |
| Release Status | No new releases | No new releases | No new releases |
| 24h Health Score¹ | 2.0 | 8.5 | 5.5 |

¹ Scoring rationale: OpenClaw has no measurable 24h activity; MuJoCo delivers high-impact, high-volume changes with fast bug resolution and active community engagement; Drake has low-volume but strategic, maintainer-led activity with no merged changes in the window.

---

## 3. OpenClaw's Position
OpenClaw (Unitree SDK2) occupies a unique niche in the embodied AI stack as a hardware-facing robot control SDK, distinct from the general-purpose simulation and controls libraries represented by MuJoCo and Drake.
- **Advantages vs. peers**: As a first-party SDK for Unitree’s widely adopted quadruped and humanoid robots, it delivers native, low-latency access to hardware interfaces (actuators, sensors, communication buses) with no middleware abstraction, enabling direct deployment of simulation-trained policies to physical robots. Its narrow focus eliminates compatibility overhead of general-purpose control stacks for Unitree-based workflows.
- **Technical approach differences**: Unlike MuJoCo (GPU-accelerated general-purpose physics engine with batch simulation support) and Drake (optimization-first controls and simulation framework), OpenClaw has no built-in simulation capabilities and is purpose-built for real-time, on-robot control with minimal computational footprint.
- **Community size comparison**: OpenClaw has the smallest, most niche community of the three, limited to teams building on Unitree hardware (evidenced by zero 24h activity). In contrast, MuJoCo has the largest and most diverse user base (with 11 upvotes and 4 comments on a single closed issue in the reporting window), while Drake has a smaller, highly specialized community of controls and optimization researchers (with targeted stakeholder discussions on platform lifecycle planning).

---

## 4. Shared Technical Focus Areas
Three cross-cutting requirements emerge across the simulation-focused projects, with implicit relevance to OpenClaw’s hardware deployment use case:
1. **Large-scale simulation performance optimization** (MuJoCo, Drake)
   - MuJoCo users report severe bottlenecks from single-element model editing APIs that recompute full model signatures per addition (Issue #3397), driving demand for batch operations to support procedural environment generation for reinforcement learning (RL) and large-scale scene workflows.
   - Drake users face a confirmed performance regression in `SceneGraph::RemoveRole` (v1.52, Issue #25004) that causes superlinear slowdowns for dynamic geometry workflows (e.g., adaptive collision modeling, dynamic object loading), impacting teams building large, interactive simulation scenes.
2. **Cross-platform support predictability and compatibility** (MuJoCo, Drake)
   - MuJoCo resolved a critical iOS Safari compatibility bug for MuJoCo Live (PR #3529) that blocked all iPhone users from accessing web-based simulation tools, prioritizing broad end-user access across desktop and mobile platforms.
   - Drake is formalizing macOS Sequoia end-of-support planning (Issue #24941) to align with its 2-most-recent-version support policy, with active cross-stakeholder discussion to ensure downstream teams have sufficient advance notice for OS and dependency upgrades.
3. **Tooling correctness for high-stakes workflows** (MuJoCo, Drake)
   - MuJoCo merged fixes for multiple core engine correctness bugs (equality constraint signature hashing, discrete actuator derivative limit indexing, MJX nested vmap touch sensor errors) that could produce invalid simulation results for system identification, control optimization, and batch RL use cases.
   - Drake is implementing validation for sums-of-squares (SOS) Region of Attraction (RoA) certificates (PR #25003) to address a long-standing gap where numerically unsound results could mislead safety-critical controls design work.

OpenClaw, as a hardware control SDK, has no visible 24h activity aligned with these focus areas, but it is a downstream beneficiary of improved sim-to-real fidelity and simulation tooling reliability, as these reduce barriers to deploying trained agents to physical Unitree robots.

---

## 5. Differentiation Analysis
The three projects occupy distinct layers of the embodied AI stack, with clear differentiation across core dimensions:

| Dimension | OpenClaw | MuJoCo | Drake |
|-----------|----------|--------|-------|
| **Core Feature Focus** | Low-level real-time hardware control for Unitree robots (actuator command, sensor data access, communication bus management); no native simulation capabilities. | General-purpose physics simulation, GPU-accelerated batch simulation (MJX), cross-platform visualization (desktop + web), and model import/export tooling; prioritizes workflow flexibility and broad use case support. | Optimization-first robotics simulation and controls framework, with deep mathematical programming, system identification, and formal verification tooling; prioritizes numerical correctness for high-stakes controls design. |
| **Target Users** | Niche community of Unitree hardware users (research labs, industrial robotics teams, hobbyists). | Diverse global user base spanning RL researchers, robotics engineers, educators, and industry teams building embodied AI and manipulation workflows. | Specialized community of controls researchers, optimization experts, and industry teams building safety-critical or high-precision robotic systems. |
| **Technical Architecture** | Lightweight, hardware-native SDK with minimal dependencies, purpose-built for on-robot real-time deployment; tightly coupled to Unitree’s proprietary communication protocols. | Modular C-based core engine with cross-language bindings, a JAX-native MJX backend for GPU batch processing, and decoupled viewer/tooling modules; optimized for both single-scene simulation and large-scale batch RL. | C++/Python framework built on a systems-level abstraction model, with tight integration to mathematical programming solvers; tightly integrated architecture designed for end-to-end optimization-driven controls design. |

---

## 6. Community Momentum & Maturity
The projects fall into three distinct activity and maturity tiers, based on 24h development velocity and backlog management signals:
1. **High Momentum, Mature General-Purpose Platform: MuJoCo**  
   MuJoCo exhibits the highest activity level, with 9 merged PRs across all core components, 6 resolved issues, and active community discussion on open enhancement requests. Its 3-day resolution time for a high-severity actuator derivative bug demonstrates strong maintainer responsiveness, while closure of 20-month-old community-prioritized requests (Python viewer texture injection) shows consistent progress on backlog debt. The project is in a mature, rapid iteration phase, balancing stability with frequent user-facing improvements.
2. **Low Activity, Deliberate Mature Framework: Drake**  
   Drake has low day-to-day activity, with no merged PRs or closed issues in the 24h window, and all updated items focused on long-term planning (macOS deprecation) or core maintainer-led feature work (RoA validation). This aligns with its mature, maintainer-led development model, where changes are rigorously vetted and targeted at high-impact, mathematically complex functionality rather than frequent incremental updates. Multi-year backlog items (e.g., the 5+ year-old RoA validation gap) reflect its priority on correctness over release velocity.
3. **No Measurable Activity, Stable Hardware SDK: OpenClaw**  
   OpenClaw recorded zero 24h activity, consistent with its role as a hardware-specific SDK with development cycles tied to Unitree product launches rather than continuous community iteration. Its lack of visible day-to-day activity likely reflects feature stability for its supported hardware, rather than stagnation, as low-level robot control SDKs require less frequent incremental updates once core functionality is validated.

---

## 7. Trend Signals
Four key industry trends emerge from community feedback across the ecosystem, with direct value for AI agent developers building embodied or physical-interaction capabilities:
1. **Sim-to-real fidelity is a non-negotiable priority for production embodied AI**  
   *Evidence*: MuJoCo’s most actively discussed physics enhancement request (Issue #3528) seeks torque-dependent gearhead friction models for DC motors, with 7 technical comments from users working on motor control and sim-to-real transfer.  
   *Value for AI agent developers*: Higher-fidelity actuator simulation reduces the gap between training and real-world performance, cutting deployment time and failure risk for personal service robots, industrial collaborative agents, and other physically interactive AI assistants.
2. **Large-scale dynamic simulation performance is a bottleneck for agent training scaling**  
   *Evidence*: MuJoCo users report severe performance bottlenecks from single-element model editing APIs for large procedural environments (Issue #3397), while Drake users face a superlinear slowdown in dynamic geometry removal for large scenes (Issue #25004).  
   *Value for AI agent developers*: Efficient dynamic scene modification is critical for scaling RL and procedural training pipelines to thousands of parallel environments, reducing training costs and iteration time for complex agent behaviors.
3. **Cross-platform simulation accessibility expands the embodied AI developer pool**  
   *Evidence*: MuJoCo resolved a critical iOS compatibility bug that blocked all iPhone users from accessing its MuJoCo Live web viewer (PR #3529), expanding access to mobile and education-focused users.  
   *Value for AI agent developers*: Broader, low-barrier access to simulation tools lowers entry barriers for new developers building personal AI assistant hardware/software workflows, accelerating ecosystem innovation and talent development.
4. **Validation tooling is critical for safety-critical personal AI agent deployments**  
   *Evidence*: Drake is implementing validation for SOS-based RoA certificates (PR #25003) to address a long-standing gap where numerically unsound controls results could mislead high-stakes design work.  
   *Value for AI agent developers*: Robust validation tooling is essential for ensuring safe, reliable operation of personal AI assistants in home or public environments (e.g., assistive robots, delivery agents), reducing liability risk and supporting regulatory compliance for physical agent deployments.

---

## Peer Project Reports

<details>
<summary><strong>MuJoCo</strong> — <a href="https://github.com/google-deepmind/mujoco">google-deepmind/mujoco</a></summary>

# MuJoCo Project Digest | 2026-09-19
*Data covers 24-hour activity ending 2026-09-18, sourced from github.com/google-deepmind/mujoco*

## 1. Today's Overview
The MuJoCo project saw moderate, high-impact activity over the trailing 24 hours, with 8 updated issues (2 open/active enhancements, 6 closed: 3 enhancements, 3 bugs) and 11 updated pull requests (2 open feature PRs, 9 merged/closed PRs). No new official releases were published. Merged work spans core engine correctness, MJX JAX backend stability, cross-platform web viewer support, rendering reliability, and import/export tooling fixes. Two open enhancement issues remain in active discussion, addressing model editing performance and actuator physics fidelity, reflecting ongoing user demand for both workflow efficiency and higher simulation accuracy. The project made meaningful progress on backlog debt, resolving multiple long-standing community requests and bug reports.

## 2. Releases
No new MuJoCo official releases were published in the 24-hour period ending 2026-09-19.

## 3. Project Progress
Nine pull requests were merged/closed in the window, delivering fixes and improvements across all major MuJoCo components:

### Core Engine & API
- **PR #3549: Fix mjSpec signature ignoring the first equality constraint**  
  https://github.com/google-deepmind/mujoco/pull/3549  
  Resolved a hash calculation bug where `mjCModel::Signature()` started its equality constraint loop at index 1, causing specs with 1 equality constraint to match the hash of specs with none. This prevented required model recompilation when adding the first equality constraint to a compiled spec.
- **PR #3566: Keep finite-difference residual evaluations within bounds**  
  https://github.com/google-deepmind/mujoco/pull/3566  
  Fixed `jacobian_fd` to avoid crossing variable bounds on narrow intervals (e.g., [0, 1e-10]), which previously caused `least_squares` optimization failures by evaluating residuals outside valid ranges.
- **PR #3606: Index ctrllimited/ctrlrange by control slot in actuator derivatives**  
  https://github.com/google-deepmind/mujoco/pull/3606  
  Fixed discrete actuator derivative control limit indexing (resolves Issue #3598), where the effective-metric derivative checked limits using actuator ordinal instead of control block address, breaking order invariance for variable-width actuator inputs.
- **PR #3570: Fix documented default of ccd_iterations (35, not 50)**  
  https://github.com/google-deepmind/mujoco/pull/3570  
  Corrected XML reference documentation to match the actual engine default of 35 (updated in v3.4.0), aligning docs with source code and XSD schema definitions.

### MJX JAX Backend
- **PR #3574: Fix touch sensors under nested vmap**  
  https://github.com/google-deepmind/mujoco/pull/3574  
  Resolved nested `jax.vmap` batch dimension ordering errors in touch sensor evaluation (resolves Issue #3209). Replaced matrix multiplication in the contact-to-site coordinate transform with element-wise operations to avoid JAX matmul batching rules reordering batch dimensions and causing invalid `dot_general` shapes.

### Viewers & Web Platform
- **PR #3529: Make MuJoCo Live work on iPhones**  
  https://github.com/google-deepmind/mujoco/pull/3529  
  Fixed iOS Safari compatibility for MuJoCo Live (resolves Issue #3442) by reducing initial WebAssembly shared memory allocation to fit iOS WebKit limits, while retaining scalable memory for desktop platforms.
- **PR #3543: Fix Filament crash when hiding geom groups**  
  https://github.com/google-deepmind/mujoco/pull/3543  
  Fixed a repeatable MuJoCo Studio crash with the Filament renderer, where toggling geom group visibility caused an uncaught `utils::PreconditionPanic` due to missing renderable preparation for hidden groups.

### Import/Export & Tooling
- **PR #2469: Fix URDF scaled mesh re-use**  
  https://github.com/google-deepmind/mujoco/pull/2469  
  Fixed URDF import bug where reusing meshes with different scaling factors incorrectly selected the first imported mesh instead of the appropriately scaled cached version, leading to wrong mesh dimensions in imported models.
- **PR #3107: Include external assets in `to_zip` output**  
  https://github.com/google-deepmind/mujoco/pull/3107  
  Fixed `to_zip` export functionality to include external assets (resolves Issue #3104), ensuring exported model archives are fully self-contained.

## 4. Community Hot Topics
Ranked by community engagement (comment count + upvotes; PR comment data unavailable):

1. **Issue #2362: API function on Python Viewer to inject textures independently from mjModel** (closed, 11 upvotes, 4 comments)  
   https://github.com/google-deepmind/mujoco/issues/2362  
   The most reacted-to issue in the update window, with 11 upvotes indicating broad community demand. Underlying need: Users building custom visualization workflows (for sensor data overlays, annotations, and debugging) require flexible texture management that does not require modifying the core simulation model, enabling dynamic, use-case-specific visual layers without altering simulation state. The issue was closed after 20 months in the backlog, signaling resolution of a long-standing user request.

2. **Issue #3397: Batch adding of bodies/geoms/etc.** (open, 8 comments, 0 upvotes)  
   https://github.com/google-deepmind/mujoco/issues/3397  
   The most actively discussed open issue, focused on model editing performance. Underlying need: Users building large procedural environments or performing batch scene modifications face severe performance bottlenecks from single-element add APIs, which recompute the full model signature on every addition. The request proposes batch operations to reduce overhead for large-scale model editing workflows.

3. **Issue #3528: Torque-proportional loss in dcmotor** (open, 7 comments, 0 upvotes)  
   https://github.com/google-deepmind/mujoco/issues/3528  
   A high-engagement physics enhancement request. Underlying need: Robotics engineers and researchers simulating geared DC motors find existing friction models (Coulomb, LuGre) insufficient, as they do not account for torque-dependent gearhead losses — a critical gap for accurate sim-to-real transfer in motor control and manipulation applications. The discussion includes technical details of proposed implementation approaches.

## 5. Bugs & Stability
Bugs reported or resolved in the 24-hour window, ranked by severity (Critical > High > Medium > Low):

### Critical
- **Filament renderer crash when toggling geom group visibility**  
  Fix merged via PR #3543: https://github.com/google-deepmind/mujoco/pull/3543  
  Details: MuJoCo Studio’s Filament renderer terminated with an uncaught exception when hiding geom groups, as hidden renderables were removed from the scene and not prepared for subsequent frames. The fix ensures proper renderable state management to prevent the crash.

### High
1. **Discrete actuator derivative incorrect control limit indexing**  
   Reported in Issue #3598: https://github.com/google-deepmind/mujoco/issues/3598 (closed)  
   Fix merged via PR #3606: https://github.com/google-deepmind/mujoco/pull/3606  
   Details: The discrete integrator’s effective-metric derivative read target control from the actuator’s control block address but checked control limits using actuator ordinal, leading to incorrect limit validation for variable-width actuator inputs. This breaks derivative order invariance, critical for system identification and control optimization workflows. Fixed 3 days after the issue was reported.

2. **mjSpec signature ignores first equality constraint**  
   Fix merged via PR #3549: https://github.com/google-deepmind/mujoco/pull/3549  
   Details: A core API bug where model signature hashing failed to include the first equality constraint, leading to silent mismatches between spec and compiled model state, and skipped required recompilations. This could cause incorrect simulation behavior for users dynamically adding equality constraints.

3. **MuJoCo Live non-functional on iOS Safari**  
   Reported in Issue #3442: https://github.com/google-deepmind/mujoco/issues/3442 (closed)  
   Fix merged via PR #3529: https://github.com/google-deepmind/mujoco/pull/3529  
   Details: The MuJoCo Live web viewer failed to initialize on iPhones due to an initial WebAssembly shared memory request (1 GiB) that exceeds iOS WebKit’s memory limits. The fix adjusts initial memory allocation to fit iOS constraints, restoring access for all mobile iOS users.

4. **MJX touch sensor evaluation fails under nested `jax.vmap`**  
   Tracked in Issue #3209: https://github.com/google-deepmind/mujoco/issues/3209 (closed, labeled enhancement but addresses functional correctness)  
   Fix merged via PR #3574: https://github.com/google-deepmind/mujoco/pull/3574  
   Details: JAX’s matmul batching rule reordered nested batch dimensions in the touch sensor’s coordinate transform, causing invalid `dot_general` shapes and XLA verification errors for users running batch MJX simulations with nested vectorization.

### Medium
1. **URDF scaled mesh re-use selects incorrect cached mesh**  
   Fix merged via PR #2469: https://github.com/google-deepmind/mujoco/pull/2469  
   Details: URDF import incorrectly selected the first imported mesh when reusing a mesh with a different scaling factor, leading to wrong geom dimensions in imported robot models. A workaround (duplicating mesh files for each scale) was required prior to the fix.

2. **Finite-difference residual evaluations cross variable bounds**  
   Fix merged via PR #3566: https://github.com/google-deepmind/mujoco/pull/3566  
   Details: `jacobian_fd`’s inward step size could cross the opposite bound on narrow variable intervals, causing `least_squares` optimization failures for users working with tightly constrained parameters.

3. **EGL and Mesa rendering produce identical performance (user-reported, closed)**  
   Reported in Issue #2090: https://github.com/google-deepmind/mujoco/issues/2090 (closed)  
   Details: A user reported no performance difference between EGL GPU rendering and Mesa software rendering on an Ubuntu server with an NVIDIA GPU for a simple scene. The issue was closed; resolution details are not specified in available data (likely a user configuration issue or expected behavior for low-complexity scenes).

### Low
- **Incorrect documented default for `ccd_iterations`**  
  Fix merged via PR #3570: https://github.com/google-deepmind/mujoco/pull/3570  
  Details: XML reference documentation listed the default `ccd_iterations` value as 50, while the actual engine default (updated in v3.4.0) is 35. The fix aligns documentation with source code and schema definitions.

## 6. Feature Requests & Roadmap Signals
### Active User-Requested Features (Open Issues)
1. **Batch model editing API (Issue #3397)**  
   https://github.com/google-deepmind/mujoco/issues/3397  
   Requests batch addition of bodies, geoms, and other model elements to avoid per-element signature recomputation overhead. The request has 8 comments with active technical discussion, indicating strong engagement from users building procedural environments and large-scale scenes.

2. **Torque-proportional dcmotor loss (Issue #3528)**  
   https://github.com/google-deepmind/mujoco/issues/3528  
   Requests torque-dependent gearhead friction loss models for DC motor actuators, to better match real-world actuator behavior and improve sim-to-real transfer. The 7-comment discussion includes exploration of implementation approaches, signaling maintainer interest in the feature.

### In-Progress Feature PRs (Open)
1. **Adhesion actuation time constant (PR #3162)**  
   https://github.com/google-deepmind/mujoco/pull/3162  
   Implements a `timeconst` parameter for adhesion actuation to enable smoother control of "sticky force" signals, addressing long-standing Issue #2145. The PR was recently updated after 6.5 months in development, suggesting it is nearing review completion.

2. **Unity Plugin terrain creation context menu (PR #1504)**  
   https://github.com/google-deepmind/mujoco/pull/1504  
   Adds a QoL context menu to create and align Unity terrain with MuJoCo hfield geoms, plus improved MJCF terrain height configuration. The PR was recently updated after 2.5 years in the backlog, indicating renewed contributor effort.

### Roadmap Predictions
- **High likelihood of next release inclusion**: The adhesion time constant feature (PR #3162) is a strong candidate, as it is a focused, well-scoped physics enhancement with active recent updates and a clear, validated use case.
- **Medium-term roadmap item**: Batch model editing (Issue #3397) addresses a significant performance pain point with strong community engagement, but no implementation PR has been submitted, so it is unlikely to ship in the immediate next release but is a priority for future versions.
- **Longer-term roadmap item**: Torque-proportional dcmotor loss (Issue #3528) requires core actuator model changes and ongoing technical discussion, so it is targeted for a future release focused on actuator fidelity, not the upcoming minor version.

## 7. User Feedback Summary
### Key User Pain Points
- **Model editing performance bottlenecks**: Users building large procedural environments report severe slowdowns from single-element model editing APIs that recompute signatures on every addition (Issue #3397).
- **Actuator fidelity gaps**: Robotics engineers note that existing friction models fail to capture torque-dependent gearhead losses, reducing sim-to-real transfer accuracy for motor control (Issue #3528).
- **Python viewer texture inflexibility**: For 20 months, users building custom visualization tools (sensor overlays, annotations) lacked a way to inject textures without modifying the core `mjModel`, complicating dynamic visualization workflows (Issue #2362, 11 upvotes).
- **System identification workflow gaps**: Researchers in system identification and adaptive control have requested better support for linear inverse dynamics parametrization since 2024 to streamline model identification pipelines (Issue #1631).
- **Cross-platform web access gaps**: iOS users were fully blocked from using MuJoCo Live due to WebAssembly memory limits, limiting access to interactive documentation and demos (Issue #3442).

### Key User Use Cases
- Procedural environment generation for robotics simulation and reinforcement learning.
- High-fidelity actuator simulation for motor control design and sim-to-real transfer.
- Custom visualization overlays for sensor data, debugging, and annotation.
- System identification and adaptive control research.
- Batch vectorized simulation on the MJX JAX backend.
- URDF import of complex robot models with reused scaled meshes.

### Satisfaction Signals
- Fast resolution of the discrete actuator derivative bug (3 days from report to fix) demonstrates strong responsiveness for core engine issues.
- Closure of long-standing high-demand requests (Issue #2362, Issue #1631) signals progress on community-prioritized features, likely improving user satisfaction.

### Dissatisfaction Signals
- Multi-year waits for high-upvoted feature requests (e.g., 20 months for Python viewer texture injection, 2.3 years for linear inverse dynamics parametrization) suggest frustration with slow progression of community-prioritized enhancements.
- The iOS MuJoCo Live outage, which affected an entire mobile user segment, likely caused dissatisfaction among users accessing resources on iPhones.

## 8. Backlog Watch
Long-running open items requiring maintainer attention to reduce backlog debt and address community needs:

1. **PR #1504: [Unity-plugin] Context menu for creating Unity terrain components**  
   https://github.com/google-deepmind/mujoco/pull/1504  
   - Opened: 2024-03-13 (2.5+ years in backlog)
   - Status: Open, updated 2026-09-18
   - Importance: Delivers high-value QoL functionality for Unity plugin users, enabling one-click terrain creation and alignment with hfield geoms, plus improved MJCF terrain configuration. The recent update indicates the contributor has refreshed the PR for review, and prolonged delay risks alienating Unity integration users.

2. **PR #3162: full adhesion timeconst feature update**  
   https://github.com/google-deepmind/mujoco/pull/3162  
   - Opened: 2026-03-10 (6.5 months in backlog)
   - Status: Open, updated 2026-09-18
   - Importance: Implements a widely requested adhesion actuation time constant, a key feature for soft robotics and manipulation simulation. The PR is functionally complete and recently updated, so prioritizing review will deliver a high-impact enhancement to the community.

</details>

<details>
<summary><strong>Drake</strong> — <a href="https://github.com/RobotLocomotion/drake">RobotLocomotion/drake</a></summary>

# Drake (RobotLocomotion/drake) Project Digest | 2026-09-19

---

## 1. Today's Overview
For the 24-hour period ending 2026-09-19, the Drake robotics simulation and controls library exhibited low overall development activity, with no new releases, merged pull requests, or closed issues recorded. A total of 2 open issues were updated, spanning platform support lifecycle planning and a newly reported performance regression in core geometry functionality, alongside 1 newly opened feature pull request in the systems module. All tracked activity items remain in active/open status, with no resolution milestones reached in the reporting window. The narrow scope of updated items suggests focused, targeted workstreams rather than broad community contribution surges, consistent with the project’s mature, maintainer-led development model.

## 2. Releases
No new Drake releases were published in the 24-hour reporting window. No release notes, breaking changes, or migration guidance are applicable for this period.

## 3. Project Progress
No pull requests were merged or closed in the 24-hour period ending 2026-09-19. As a result, no new features, bug fixes, or maintenance changes were formally incorporated into the Drake codebase during this window. The single updated PR remains in open review status.

## 4. Community Hot Topics
Items are ranked by measurable engagement (comment volume, as all tracked items have 0 👍 reactions):
1. **#24941 macOS Sequoia (15) support end of life** [Open, component: distribution / continuous integration, type: feature request]  
   Link: https://github.com/RobotLocomotion/drake/issues/24941  
   Engagement: 6 comments, 0 👍 reactions  
   Analysis: This is the most actively discussed item in the reporting window, centered on Drake’s published stable support policy, which commits to supporting the two most recent macOS and Ubuntu LTS versions. The discussion focuses on aligning Sequoia deprecation timing with the upcoming release of macOS Golden Gate (27), with underlying needs including predictable, policy-aligned deprecation timelines that allow downstream robotics teams to plan OS and dependency upgrades without unexpected operational disruption. The active comment thread indicates cross-stakeholder alignment on the policy goal, with remaining discussion likely focused on logistical details like advance notice windows and CI pipeline updates.

The remaining updated items (Issue #25004, PR #25003) were first opened or significantly updated on 2026-09-18 and have not yet accumulated community engagement, consistent with their very recent status.

## 5. Bugs & Stability
One new bug report was tracked in the 24h window, ranked by estimated severity based on functional impact and regression status:
1. **#25004 Poor performance of SceneGraph::RemoveRole starting in v1.52** [Open, type: bug]  
   Link: https://github.com/RobotLocomotion/drake/issues/25004  
   Severity: Medium-High  
   Details: This is a confirmed performance regression introduced in Drake v1.52, where `SceneGraph::RemoveRole(..., Role::kProximity)` exhibits superlinear runtime scaling, compared to linear/acceptable performance in v1.51. The reporter provided a reproducible example script demonstrating the degradation. SceneGraph is a core foundational component of Drake’s simulation, collision detection, and geometry processing pipeline, so this regression impacts users working with large simulation scenes or workflows requiring frequent dynamic role removal (e.g., adaptive collision modeling, dynamic object loading/unloading, perception integration pipelines).  
   Fix status: No associated fix pull request has been linked or submitted as of the reporting window, and the issue has not yet received maintainer triage.

## 6. Feature Requests & Roadmap Signals
Tracked feature requests and in-progress feature work with clear roadmap relevance:
1. **Formalized macOS Sequoia (15) end-of-support** (Issue #24941, type: feature request)  
   Link: https://github.com/RobotLocomotion/drake/issues/24941  
   Details: This request formalizes the planned deprecation and end of support for macOS Sequoia (15) to align with Drake’s 2-most-recent-version platform support policy, ahead of the public release of macOS Golden Gate (27).  
   Roadmap likelihood: Very High. This change is policy-driven rather than discretionary, and active discussion indicates planning is already underway. It will almost certainly be implemented in the first minor release cycle following the public launch of macOS Golden Gate, with advance deprecation notices posted to Drake’s stable documentation and pre-release notes.

2. **Region of Attraction (RoA) SOS certificate validation** (PR #25003, systems module)  
   Link: https://github.com/RobotLocomotion/drake/pull/25003  
   Details: This in-progress feature resolves long-standing issue #12876 by adding validation for sums-of-squares (SOS)-based RoA certificates, addressing a known gap where poorly conditioned problems could produce numerically invalid, misleading RoA results without user warning. The implementation includes two core improvements: strengthened RoA code to detect bad numerics, and associated validation tooling.  
   Roadmap likelihood: High. The PR is authored by core project lead Russ Tedrake, targets a long-open user-facing quality gap, and is already in active review. It is likely to land in the next 1-2 minor release cycles, barring unforeseen review feedback or implementation revisions.

## 7. User Feedback Summary
User and contributor feedback captured in the 24h window reflects two core pain points and use cases:
1. **Performance regression pain point**: A user reported unanticipated superlinear slowdown in `SceneGraph::RemoveRole` after upgrading from Drake v1.51 to v1.52. The implicit use case is workflows requiring frequent dynamic modification of collision geometry roles (e.g., large-scale simulation with dynamic object management, adaptive perception pipelines) where the regression would render previously feasible workflows impractically slow. The user invested time in building a reproducible test case, indicating the issue is materially impactful to their work. No explicit satisfaction or dissatisfaction language is included in the report.
2. **Platform support predictability need**: A contributor raised the planned macOS Sequoia deprecation to align with published support policy, reflecting a broader downstream need for clear, advance communication of platform lifecycle changes. This feedback is tied to use cases where teams build production or research robotics stacks on Drake and require multi-week to multi-month planning horizons for OS and dependency upgrades to avoid project delays or operational disruption.

## 8. Backlog Watch
Based on items referenced in the 24h updated activity set, the following long-standing backlog items and triage priorities warrant note:
1. **Issue #12876: Unvalidated numerically unsound RoA SOS results**  
   Link: https://github.com/RobotLocomotion/drake/issues/12876  
   Context: This long-open issue (evidenced by its significantly lower issue number relative to the current ~25k issue count, indicating multiple years in the backlog) tracks a critical quality gap in Drake’s systems analysis tooling, where RoA calculations using SOS programming can produce invalid, misleading results without user-facing validation or warnings. The issue represents a risk for users relying on RoA analysis for safety-critical or high-stakes controls design work.  
   Status update: Newly opened PR #25003 (led by core maintainer Russ Tedrake) proposes a full resolution, indicating the issue is finally receiving active maintainer attention after an extended period in the backlog.

2. **New regression bug #25004 (SceneGraph::RemoveRole performance)**  
   Link: https://github.com/RobotLocomotion/drake/issues/25004  
   Context: While not yet long-unanswered (opened 2026-09-18, 0 comments), this medium-high severity performance regression in a core component requires prompt maintainer triage and backlog prioritization. Without a fix, it may impact a growing number of users upgrading to Drake v1.52 or later versions, particularly those working with complex simulation scenes.

</details>

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*