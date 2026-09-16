# AI CLI Tools Community Digest 2026-09-16

> Generated: 2026-09-16 02:09 UTC | Tools covered: 5

- [ROS 2](https://github.com/ros2/ros2)
- [NVIDIA Isaac Lab](https://github.com/isaac-sim/IsaacLab)
- [Genesis](https://github.com/Genesis-Embodied-AI/Genesis)
- [LeRobot](https://github.com/huggingface/lerobot)
- [OpenVLA](https://github.com/openvla/openvla)
- [Claude Code Skills](https://github.com/anthropics/skills)

---

## Cross-Tool Comparison

# Cross-Tool AI Robotics Developer Ecosystem Comparison Report
Date: 2026-09-16 | Source: Community digests for ROS 2, NVIDIA Isaac Lab, Genesis, LeRobot, OpenVLA

---

## 1. Ecosystem Overview
The 2026-09-16 community digests cover five core tools in the embodied AI and robotics developer stack, spanning middleware, physics simulation, robot learning frameworks, and vision-language-action (VLA) model tooling. Across all active projects, development prioritizes stability for high-stakes robotics and reinforcement learning (RL) workloads, alongside expanding interoperability and reducing onboarding friction for new users. Activity is split between foundational physics backend optimizations, end-to-end workflow tooling, and critical silent failure fixes that pose risks to experimental validity and hardware safety. Cross-project alignment on shared pain points (e.g., dependency compatibility, multi-environment reliability) highlights unmet needs in the broader AI robotics toolchain.

---

## 2. Activity Comparison
| Tool | Updated Issues (24h) | Open Updated Issues | Closed Updated Issues | Updated PRs (24h) | New Releases (24h) |
|------|-----------------------|---------------------|-----------------------|--------------------|---------------------|
| ROS 2 | 0 | 0 | 0 | 0 | None |
| NVIDIA Isaac Lab | 10 | 5 | 5 | 10 | None |
| Genesis | 0 | 0 | 0 | 6 | None |
| LeRobot | 7 | 7 | 0 | 10 | None |
| OpenVLA | 1 | 1 | 0 | 1 | None |
*Source: 2026-09-16 official community digests for each repository*

---

## 3. Shared Feature Directions
Three cross-cutting requirements appear across multiple tool communities, reflecting broader ecosystem gaps:
- **Silent failure prevention & dependency guardrails** (OpenVLA, LeRobot, NVIDIA Isaac Lab): All three projects face high-severity silent failures from upstream dependency changes or API contract drift, with no built-in validation to catch issues early. Examples include OpenVLA’s transformers ≥4.50 vision bypass bug, LeRobot’s silent untrained "blind policy" loading from a missing `pretrained_path`, and Isaac Lab’s `DirectMARLEnv` state space API mismatch. Users require runtime correctness checks and stricter dependency version guardrails to avoid wasted compute, invalid experiments, and hardware safety risks.
- **Physics backend & multi-scene simulation reliability** (NVIDIA Isaac Lab, Genesis): Both simulation frameworks prioritize stability and performance for multi-body/multi-environment workloads. Isaac Lab is addressing Newton backend edge cases (stale gravity on hard reset, frame transform mismatches) and resolving long-standing multi-env sensor rendering bugs. Genesis is optimizing rigid kinematics for multi-body scenes, fixing contact simulation edge cases (light object drift, spurious forces), and expanding solver options via Mochi integration.
- **End-to-end sim-to-real & hardware ecosystem integration** (NVIDIA Isaac Lab, LeRobot): Both communities focus on bridging simulation and real-world robot deployment. Isaac Lab users have long demanded official integrated sim-to-real tooling, addressed via a recently closed roadmap update issue. LeRobot is expanding hardware support (Unitree G1-23, B601 safe-home features) and prioritizing official ROS 2 integration to unify fragmented third-party middleware bridges, aligning simulation, training, and hardware control workflows.

---

## 4. Differentiation Analysis
The tools occupy distinct layers of the embodied AI/robotics tech stack, with minimal direct functional overlap:
- **Middleware layer (ROS 2)**: The de facto industry standard for robot communication and component abstraction, serving as a common integration layer for all other tools in the ecosystem. Its core focus is standardized interfaces across hardware and software, rather than simulation or learning functionality. No updates were recorded in the 24-hour window, consistent with its mature, stable release cadence.
- **Simulation layer (NVIDIA Isaac Lab, Genesis)**:
  - Isaac Lab is a full-stack, GPU-optimized robotics simulation platform targeting industrial RL teams and large-scale batch training. It prioritizes end-to-end workflow integration (USD asset pipelines, multi-sensor models, RL environment APIs) built on NVIDIA’s PhysX/Newton backends, optimized for thousands of parallel environments on NVIDIA hardware.
  - Genesis is a lightweight, modular physics engine targeting core robotics researchers and engine developers. It prioritizes raw solver performance, contact simulation accuracy, and pluggable solver architecture rather than pre-built RL or sensor abstractions, with a focus on iterative improvement of foundational physics capabilities.
- **Learning & deployment layer (LeRobot, OpenVLA)**:
  - LeRobot is an end-to-end robot learning framework targeting applied robotics teams and imitation learning researchers. It spans dataset curation, policy training, and real hardware deployment, with deep integration into the Hugging Face ecosystem and a focus on expanding hardware embodiment support and standardized workflow tooling.
  - OpenVLA is a specialized VLA model toolkit targeting VLA researchers and teams deploying vision-language-action policies. It has a narrow focus on core model correctness and inference performance, with minimal overhead beyond the VLA pipeline, and relies on upstream frameworks for end-to-end workflow support.

---

## 5. Community Momentum & Maturity
Activity volume and composition reflect varying stages of project maturity and community size:
- **Highest activity, mature governance**: NVIDIA Isaac Lab leads 24h activity with 20 total updated issues/PRs, demonstrating balanced, mature maintenance. It resolved 5 long-standing user pain points (some open 1–2 years, e.g., TiledCamera rendering bugs) while triaging 5 new critical issues, with PRs spanning core runtime, documentation standardization, CI supply-chain hardening, and formal deprecation policy alignment. This indicates a large, established user base and a mature maintainer team balancing feature work, technical debt, and process improvement.
- **Fast-growing, community-driven**: LeRobot follows closely with 17 total updated issues/PRs, reflecting rapid growth and broad community engagement. All 7 updated issues are new/open, covering use cases from middleware integration to hardware safety, and PRs add hardware support, performance optimizations, and community-contributed tooling (FiftyOne visualization, RDA dataset auditor). The presence of cross-cutting RFCs (e.g., ROS 2 integration strategy) signals expanding adoption and maturing ecosystem governance.
- **Niche, fast-iterating core tech**: Genesis has a smaller, more technical user base with no user-reported issues in the 24h window, but 6 focused PRs (4 from core maintainers, 1 community solver contribution) targeting core physics performance and stability. It is iterating rapidly on foundational engine capabilities, with a user base concentrated in advanced robotics research rather than applied teams.
- **Specialized, responsive maintenance**: OpenVLA has the narrowest scope and smallest 24h activity volume (1 critical issue + 1 fix PR), but demonstrates highly responsive maintenance for high-severity correctness bugs (fix submitted within 9 days of reporting). Its community is specialized around VLA research and deployment, with lower overall issue volume due to its limited functional scope.
- **Mature baseline middleware**: ROS 2 recorded no 24h activity, which is typical for its large, multi-subproject structure and stable release cycle, rather than a sign of low momentum.

---

## 6. Trend Signals
Four key industry trends emerge from the 24h community data, with actionable implications for technical decision-makers and developers:
1. **Silent correctness failures are a top cross-stack risk**
   - Evidence: Critical silent bugs (plausible but invalid outputs, no error warnings) were identified across the stack: OpenVLA’s transformers ≥4.50 vision bypass, LeRobot’s untrained policy loading, and Isaac Lab’s API contract drift. These bugs are far more costly than explicit crashes, as they can waste weeks of compute, invalidate research, or cause hardware damage.
   - Takeaway: Implement runtime sanity checks for core inference/simulation paths, enforce both upper and lower version pins for critical dependencies, and add functional regression tests (not just error-free execution) to CI pipelines.
2. **Sim-to-real unification is the biggest unmet ecosystem need**
   - Evidence: LeRobot’s top community request is official ROS 2 integration to replace 6 fragmented third-party bridges; Isaac Lab users have long demanded natively integrated sim-to-real tooling; cross-simulator sim-to-sim transfer gaps are a growing pain point for humanoid control research.
   - Takeaway: Build modular pipelines with standard interfaces (ROS 2 for middleware, USD for assets, Hugging Face for datasets/models) to avoid vendor lock-in and reduce integration overhead as the ecosystem consolidates.
3. **Physics backend diversification drives demand for agnostic workflows**
   - Evidence: Isaac Lab is actively maturing its Newton backend alongside legacy PhysX; Genesis is optimizing its core solver and adding third-party Mochi support. Users are increasingly using cross-physics validation to improve policy robustness for real-world deployment.
   - Takeaway: Abstract physics backend dependencies in robot learning and control code where possible, to enable workload-specific solver selection and sim-to-sim validation pipelines.
4. **Dataset quality tooling is a growing bottleneck for robot learning**
   - Evidence: LeRobot’s first community-contributed dataset auditing tool (RDA) and demand for more flexible DAgger recording workflows highlight that data curation and quality assurance are emerging as key pain points as imitation learning and VLA adoption scales.
   - Takeaway: Invest in automated dataset quality checks and standardized recording pipelines early in robot learning projects, to reduce manual curation overhead and improve policy reproducibility and sim-to-real transfer.

---

## Per-Tool Reports

<details>
<summary><strong>ROS 2</strong> — <a href="https://github.com/ros2/ros2">ros2/ros2</a></summary>

No activity in the last 24 hours.

</details>

<details>
<summary><strong>NVIDIA Isaac Lab</strong> — <a href="https://github.com/isaac-sim/IsaacLab">isaac-sim/IsaacLab</a></summary>

# NVIDIA Isaac Lab Community Digest | 2026-09-16

---

## 1. Today's Highlights
Over the 24-hour window ending 2026-09-16, the Isaac Lab community saw no new official releases, with activity concentrated on Newton physics backend stability fixes, documentation standardization, and CI supply-chain hardening. Five new open issues were filed focused on Newton runtime edge cases, cross-simulator hierarchical control transfer, and onboarding friction, while 20 pull requests advanced across core runtime, docs, and infrastructure tracks. Notable recently resolved issues include long-standing multi-environment TiledCamera rendering bugs and a frequently asked pose query question that has been closed with clarified guidance.

---

## 2. Hot Issues
*10 noteworthy issues updated in the last 24 hours, ranked by community impact and relevance:*

1. **[Issue #7732](https://github.com/isaac-sim/IsaacLab/issues/7732) | OPEN | Errors when running Isaac Sim from pre-built Docker image**
   - Why it matters: Pre-built Docker images are the recommended zero-setup deployment path for cloud, CI, and new user onboarding. This bug breaks core Isaac Sim functionality when following official documentation for the 3.0.0-beta2 image, blocking onboarding and production CI workflows.
   - Community reaction: Reported 6 days prior by a user following official docs, with 2 follow-up comments and no resolution as of the digest date.

2. **[Issue #7750](https://github.com/isaac-sim/IsaacLab/issues/7750) | OPEN | Hierarchical Isaac Lab→MuJoCo sim-to-sim transfer failure for AMP + BeyondMimic G1 controllers**
   - Why it matters: Cross-physics sim-to-sim validation is critical for robust humanoid control pipelines, and hierarchical control (high-level AMP actors + low-level trackers) is a leading architecture for legged robots. This failure highlights unaddressed gaps in cross-engine behavior parity.
   - Community reaction: Filed 6 days prior by a humanoid robotics researcher, with 1 comment and active investigation.

3. **[Issue #7792](https://github.com/isaac-sim/IsaacLab/issues/7792) | OPEN | DirectMARLEnv state_space=0 exposed as Box(0) instead of None**
   - Why it matters: The MARL environment API is a core interface for multi-agent RL research. This bug breaks the documented contract, causing user code that checks for `None` state spaces (to disable centralized training) to fail silently or crash.
   - Community reaction: Filed 1 day prior, with 1 triage comment, indicating fast initial response.

4. **[Issue #7833](https://github.com/isaac-sim/IsaacLab/issues/7833) | OPEN | Newton asset data retains stale gravity binding after hard reset**
   - Why it matters: Hard environment resets are a standard part of RL training loops, and stale gravity values will cause non-deterministic simulation behavior and invalid training results for users of the new Newton physics backend.
   - Community reaction: Filed the same day as the digest, with 0 comments, representing a newly identified critical Newton bug.

5. **[Issue #7816](https://github.com/isaac-sim/IsaacLab/issues/7816) | OPEN | Unstated ROS dependency causing startup failures**
   - Why it matters: Unclear mandatory dependencies create onboarding friction for users working on non-ROS workflows, indicating a regression in dependency management or documentation for recent builds.
   - Community reaction: Filed the same day as the digest, with 0 comments, highlighting an unaddressed UX gap for non-ROS developers.

6. **[Issue #713](https://github.com/isaac-sim/IsaacLab/issues/713) | CLOSED | Real-robot code roadmap update**
   - Why it matters: With 6 upvotes, this is the highest-engagement issue in the 24-hour update window, reflecting strong community demand for official sim-to-real deployment tooling integrated with Isaac Lab.
   - Community reaction: Long-standing (filed July 2024) question that received a final update and closure, indicating roadmap clarity has been provided to users.

7. **[Issue #1127](https://github.com/isaac-sim/IsaacLab/issues/1127) | CLOSED | TiledCamera flips orientation when num_envs > 1**
   - Why it matters: Multi-environment batch training is the standard for RL, and wrist camera pose inconsistencies break visual policy training and perception benchmarking workflows. This long-standing bug had been open since October 2024.
   - Community reaction: Closed after ~2 years of being open, with 2 comments, resolving a frequent pain point for visual RL developers.

8. **[Issue #4431](https://github.com/isaac-sim/IsaacLab/issues/4431) | CLOSED | TiledCamera brightness inconsistency with ArticulationCfg and num_envs > 1**
   - Why it matters: Related to the multi-env camera flip bug, this brightness inconsistency breaks visual RL training by introducing unmodeled variance across environment instances, invalidating batch training results.
   - Community reaction: Closed after 8 months of being open, with 2 comments, addressing a critical issue for multi-env visual perception workflows.

9. **[Issue #4257](https://github.com/isaac-sim/IsaacLab/issues/4257) | CLOSED | Contact reporting broken after saving RigidObject USD and reloading**
   - Why it matters: USD asset pipelines are core to Isaac Lab's asset workflow, and broken contact sensors on reloaded assets break RL reward functions, collision detection, and perception pipelines that rely on contact data.
   - Community reaction: Closed after 9 months of being open, with 3 comments, resolving a key pain point for users building custom asset libraries.

10. **[Issue #783](https://github.com/isaac-sim/IsaacLab/issues/783) | CLOSED | How to get local/world object pose in Isaac Lab**
    - Why it matters: This is one of the most frequent beginner questions (13 comments, open since August 2024) about a core simulation primitive. Its closure indicates that documentation or API clarity has been improved to reduce support burden.
    - Community reaction: Closed with resolved guidance, 1 upvote, serving as a canonical reference for new users learning the pose query API.

---

## 3. Key PR Progress
*10 high-impact pull requests updated in the last 24 hours, covering features, fixes, and infrastructure:*

1. **[PR #7691](https://github.com/isaac-sim/IsaacLab/pull/7691) | OPEN | Mirror Newton frame-view pose writes onto Fabric transforms**
   - Fixes a critical bug where `Camera.set_world_poses` updated camera pose data but not rendered output on the Newton backend, by mirroring frame view pose writes to Fabric transforms consumed by the RTX renderer. Unblocks visual RL and perception workflows on the Newton backend.

2. **[PR #6083](https://github.com/isaac-sim/IsaacLab/pull/6083) | CLOSED | Add GRU and GRU-residual network actuator models**
   - Adds two recurrent GRU-based actuator network models to `isaaclab.actuators` alongside existing MLP and LSTM options: `ActuatorNetGRU` (predicts total joint effort from position error and velocity, derived from `IdealPDActuator`) and a residual GRU variant. Expands options for modeling complex actuator dynamics and sim-to-real transfer.

3. **[PR #6673](https://github.com/isaac-sim/IsaacLab/pull/6673) | OPEN | Add volume and surface deformable schema fragment families**
   - Adds deformable-body schema fragment families to the composable fragment framework, supporting both volume and surface deformables. Deformable writers auto-create full simulation mesh setups on matched prims, reducing the need for manual USD authoring for soft-body workflows.

4. **[PR #7839](https://github.com/isaac-sim/IsaacLab/pull/7839) | OPEN | Deprecate legacy physics schema cfgs and writers**
   - Marks all legacy physics schema config classes and writers as deprecated, with per-symbol migration guidance to the new composable fragment API. No functionality is removed in this PR, per project deprecation policy. Gives users clear advance notice of upcoming breaking changes.

5. **[PR #7838](https://github.com/isaac-sim/IsaacLab/pull/7838) | OPEN | Migrate all in-repo call sites to physics schema fragments**
   - Migrates every internal Isaac Lab call site from legacy physics schema configs to the new composable fragment API, and adds a parity test verifying both APIs produce identical USD output. Validates functional parity and clears the path for eventual legacy code removal.

6. **[PR #7499](https://github.com/isaac-sim/IsaacLab/pull/7499) | OPEN | Export initialized deployment environment USD**
   - Adds functionality to export a fully initialized single environment (with pre-configured physical properties and scene resources) to USD, with an option to export environment 0 before training randomization is applied. Streamlines the training-to-deployment pipeline for production use cases.

7. **[PR #7819](https://github.com/isaac-sim/IsaacLab/pull/7819) | OPEN | Consolidate asset and Docker guides, repair tutorial examples**
   - Consolidates overlapping robot/articulation documentation into a single worked guide, reorganizes Docker/cloud/cluster docs into discoverable workflow pages, and fixes broken tutorial examples (ROS mesh resolution, OSC target corrections, etc.). Reduces onboarding friction for new users.

8. **[PR #7835](https://github.com/isaac-sim/IsaacLab/pull/7835) | OPEN | Harden CI dependencies, update Starlette, align aiohttp**
   - Implements supply-chain security hardening for CI pipelines, including hash-locked wheel-only requirements for contract test tools, restricted Git LFS downloads, and patched web dependencies (Starlette, aiohttp) to address vulnerabilities. Reduces the project's supply-chain attack surface.

9. **[PR #7829](https://github.com/isaac-sim/IsaacLab/pull/7829) | OPEN | Restore Franka core tasks on shared Menagerie asset**
   - Fixes performance and policy regressions in core Franka manipulation tasks introduced by the switch to the shared Menagerie asset and teleoperation compatibility changes, including restoring reward term behavior and reducing PhysX startup overhead. Restores benchmark validity for widely used Franka workflows.

10. **[PR #7840](https://github.com/isaac-sim/IsaacLab/pull/7840) | OPEN | Standardize removal release across all deprecation notices**
    - Aligns all deprecation notices across the repository to specify a single consistent removal release (currently 4.0), fixing inconsistencies where related symbols cited different removal versions (4.0 vs. 5.0). Eliminates user confusion about breaking change timelines.

---

## 4. Feature Request Trends
Distilled from issues updated in the 24-hour window, four key community demand directions emerge:
1. **Newton Backend Performance & Feature Parity**: Users are pushing for optimizations to the newer Newton physics backend (e.g., GPU-resident MPM particle updates during RTX rendering, [Issue #7828](https://github.com/isaac-sim/IsaacLab/issues/7828)) and closing feature gaps with PhysX for deformables, rendering integration, and runtime stability.
2. **Sim-to-Real & Cross-Simulator Interoperability**: There is strong community demand for official real-robot deployment tooling integrated with Isaac Lab ([Issue #713](https://github.com/isaac-sim/IsaacLab/issues/713), 6 upvotes), as well as reliable sim-to-sim transfer pipelines between Isaac Lab (PhysX/Newton) and other engines like MuJoCo, particularly for hierarchical humanoid control stacks ([Issue #7750](https://github.com/isaac-sim/IsaacLab/issues/7750)).
3. **Workflow Standardization & Developer UX**: Users want more consistent project structures across the core repo and generated template projects ([Issue #2915](https://github.com/isaac-sim/IsaacLab/issues/2915)), clearer documentation for core API behavior (e.g., actuator units, [Issue #663](https://github.com/isaac-sim/IsaacLab/issues/663)), and streamlined deployment workflows like one-click environment export.
4. **Documentation & Deprecation Transparency**: There is consistent demand for clearer, more consistent documentation — from beginner-friendly guides for common tasks like pose queries ([Issue #783](https://github.com/isaac-sim/IsaacLab/issues/783)) to standardized deprecation timelines — so users can plan migrations without unexpected breaking changes.

---

## 5. Developer Pain Points
Recurring and high-impact frustrations identified from recent issues:
1. **Multi-Environment Sensor Reliability**: Multiple long-standing resolved bugs ([Issue #1127](https://github.com/isaac-sim/IsaacLab/issues/1127), [Issue #4431](https://github.com/isaac-sim/IsaacLab/issues/4431)) highlight that multi-environment (`num_envs > 1`) setups have historically suffered from sensor rendering inconsistencies (pose flips, brightness variance) that break batch RL training and perception benchmarks, indicating ongoing fragility in multi-env sensor pipelines.
2. **Newton Backend Edge Case Instability**: A cluster of newly filed open issues ([Issue #7833](https://github.com/isaac-sim/IsaacLab/issues/7833), [Issue #7830](https://github.com/isaac-sim/IsaacLab/issues/7830), [Issue #7783](https://github.com/isaac-sim/IsaacLab/issues/7783), [Issue #7827](https://github.com/isaac-sim/IsaacLab/issues/7827)) point to immature stability in the Newton physics backend, with bugs in hard reset behavior, contact buffer sorting, frame transform handling, and VBD color balancing that cause non-deterministic or incorrect simulation results.
3. **Pre-Built Docker Image Reliability**: The official pre-built Docker image (a core onboarding and CI path) has unresolved runtime errors when following official documentation ([Issue #7732](https://github.com/isaac-sim/IsaacLab/issues/7732)), creating significant friction for new users and teams relying on containerized deployments.
4. **Unclear Dependencies & Onboarding Friction**: New users frequently encounter unexpected setup issues, including unstated ROS dependencies that cause startup failures ([Issue #7816](https://github.com/isaac-sim/IsaacLab/issues/7816)) and missing example resources that break first-run tutorials ([Issue #446](https://github.com/isaac-sim/IsaacLab/issues/446)), indicating gaps in dependency documentation and release validation.
5. **API Contract Drift**: Several bugs involve API behavior diverging from documented contracts, such as `DirectMARLEnv` returning a `Box(0)` state space instead of `None` ([Issue #7792](https://github.com/isaac-sim/IsaacLab/issues/7792)) and the develop branch silently dropping Python return codes ([Issue #5237](https://github.com/isaac-sim/IsaacLab/issues/5237)), which break user code that relies on specified interface guarantees.

</details>

<details>
<summary><strong>Genesis</strong> — <a href="https://github.com/Genesis-Embodied-AI/Genesis">Genesis-Embodied-AI/Genesis</a></summary>

# Genesis Embodied AI Community Digest
Date: 2026-09-16  
Source: github.com/Genesis-Embodied-AI/Genesis (genesis-world sub-repository)

---

## 1. Today's Highlights
No new releases or community issues were recorded for the Genesis embodied AI framework in the 24-hour window ending 2026-09-16, with all development activity concentrated on 6 pull requests in the genesis-world codebase. Core contributor duburcqa led a trio of physics engine updates targeting rigid kinematics performance for multi-body scenes and two critical stability bugs affecting light objects in contact simulations. Two PRs were closed, including a CI workflow enhancement enabling upstream dependent repositories to run Genesis production test suites, while a community contributor proposed integration of the new Mochi solver.

---

## 2. Hot Issues
No new or recently updated issues were tracked in the Genesis or genesis-world repositories in the 24-hour reporting window. No noteworthy issue discussions, community feedback, or prioritized user bug reports are available for this period.

---

## 3. Key PR Progress
A total of 6 pull requests were updated in the genesis-world repository in the 24-hour window. All high-priority PRs are listed below (full set of updated PRs, as total count falls below the 10-item threshold):

1. **PR #3376 | [OPEN] [MISC] Rigid Kinematics Speedup for Multi-Body Scenes**  
   Author: duburcqa  
   Details: Refactors the rigid kinematic sweep (link poses, geoms, centers of mass, Cartesian velocities/accelerations) to run one thread per kinematic tree (instead of per entity), gated on the tree root's sleep flag, with per-root CoM tracking. Delivers measurable performance improvements for environments with multiple bodies or robots per scene.  
   Link: [https://github.com/Genesis-Embodied-AI/genesis-world/pull/3376](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3376)

2. **PR #3373 | [OPEN] [BUG FIX] Drift Fix for Light Resting Objects Under Elliptic Friction**  
   Author: duburcqa  
   Details: Modifies the constraint solver's Newton line search to select candidate steps at transitions between sticking and saturated states of `signorini` friction blocks, or at normal row on/off switches, instead of bracket endpoints. Eliminates slow positional drift of light resting objects when elliptic friction is enabled.  
   Link: [https://github.com/Genesis-Embodied-AI/genesis-world/pull/3373](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3373)

3. **PR #3375 | [OPEN] [BUG FIX] Spurious Force Fix for Light Objects in Incomplete Contact Solves**  
   Author: duburcqa  
   Details: Updates the implicit damping pass for `Euler` and `implicitfast` integrators to apply damped acceleration as a direct correction to the constraint solver's output acceleration (`a' = a - (M + hD)^-1 (hD a)`) rather than re-solving from smooth and constraint forces. Resolves issues where light objects are impulsively "kicked" away when the contact solver terminates before full convergence.  
   Link: [https://github.com/Genesis-Embodied-AI/genesis-world/pull/3375](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3375)

4. **PR #3372 | [OPEN] [FEATURE] Mochi Solver Integration**  
   Author: Kashu7100  
   Details: Proposes addition of the Mochi solver to the genesis-world physics stack. The PR follows Genesis contribution guidelines, with full implementation details, benchmarks, and use case documentation pending further updates.  
   Link: [https://github.com/Genesis-Embodied-AI/genesis-world/pull/3372](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3372)

5. **PR #3371 | [CLOSED] [MISC] Dependent Repository Production CI Access**  
   Author: duburcqa  
   Details: Adds `on: workflow_call` triggers to `production.yml` and `alarm.yml` CI workflows, enabling upstream repositories that Genesis depends on to run Genesis unit tests, benchmarks, and benchmark comparisons against their own changes. Called workflows inherit the caller's event context, runner configuration, and secrets.  
   Link: [https://github.com/Genesis-Embodied-AI/genesis-world/pull/3371](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3371)

6. **PR #3374 | [CLOSED] Yiling/260903 QIPC Merge**  
   Author: YilingQiao  
   Details: Closed merge PR for the QIPC feature branch, submitted in compliance with Genesis pull request contribution guidelines. No public functional summary was provided in the PR description.  
   Link: [https://github.com/Genesis-Embodied-AI/genesis-world/pull/3374](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3374)

---

## 4. Feature Request Trends
No new feature request issues were filed or updated in the 24-hour reporting window, so no issue-based feature trend data is available for this period. The only in-progress community feature PR — Mochi solver integration ([PR #3372](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3372)) — suggests early community interest in expanding Genesis' physics solver ecosystem with alternative solver options.

---

## 5. Developer Pain Points
No new user-reported issues were tracked in the 24-hour window, so no community-derived developer pain point trends can be distilled from issue data for this period. The batch of physics-focused PRs from core maintainer duburcqa targets three prioritized limitations of the current physics stack (identified via internal testing or prior community feedback):
1. High rigid kinematics overhead in multi-robot/multi-body scenes ([PR #3376](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3376))
2. Positional drift of light resting objects under elliptic friction ([PR #3373](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3373))
3. Spurious impulsive forces on light objects during non-converged contact solves ([PR #3375](https://github.com/Genesis-Embodied-AI/genesis-world/pull/3375))

---

*Note: The Releases section is omitted per digest guidelines, as no new versions were published in the 24-hour window.*

</details>

<details>
<summary><strong>LeRobot</strong> — <a href="https://github.com/huggingface/lerobot">huggingface/lerobot</a></summary>

# LeRobot Community Digest | 2026-09-16
Source: [github.com/huggingface/lerobot](https://github.com/huggingface/lerobot)

---

## 1. Today's Highlights
Over the last 24 hours, the LeRobot community advanced hardware embodiment support, policy performance, and ecosystem tooling, with active discussion around a long-running ROS 2 integration strategy RFC. New PRs add Unitree G1-23 humanoid support and a FiftyOne dataset visualization backend, while critical bug fixes address silent pretrained config loading failures and real-time control action glitches. Community contributors also shared an open-source automated dataset quality auditing tool for LeRobot-format datasets.

---

## 2. Releases
No new LeRobot releases were published in the 24-hour window ending 2026-09-16.

---

## 3. Hot Issues
All 7 issues updated in the last 24 hours are featured below, ranked by community engagement and impact:
1. **Issue #4368: RFC: ROS 2 integration strategy (ecosystem survey and proposed direction)**  
   [Link](https://github.com/huggingface/lerobot/issues/4368)  
   *Why it matters*: ROS 2 is the de facto standard for robot middleware; 6 incompatible community projects currently implement partial LeRobot-ROS 2 bridges, creating fragmentation and redundant work for users. This RFC proposes a unified official integration path spanning datasets, simulation, hardware, and training workflows.  
   *Community reaction*: 15 comments, 7 upvotes, cross-cutting interest across 16 topic labels (documentation, hardware, simulation, etc.).

2. **Issue #4626: [Bug/Feature Req/Fix?] DAgger rollout strategy cannot record full task-attempt episodes with HIL corrections**  
   [Link](https://github.com/huggingface/lerobot/issues/4626)  
   *Why it matters*: DAgger is a core imitation learning algorithm for human-in-the-loop (HIL) dataset collection. The current implementation only supports unbounded continuous recording or corrections-only datasets, making it impossible to capture full autonomous + correction task attempts as bounded episodes, which degrades dataset quality and reproducibility.  
   *Community reaction*: 3 comments, filed 3 days ago, active triage from maintainers.

3. **Issue #4609: B601: preserve the MIT target when entering safe-home**  
   [Link](https://github.com/huggingface/lerobot/issues/4609)  
   *Why it matters*: The native `rebot_b601_follower` directly cuts motor torque on `disconnect()`, risking arm damage or workspace hazards when stopping teleop/recording via Ctrl+C. A configurable safe-home trajectory would add critical hardware safety for B601 users.  
   *Community reaction*: 2 comments, high priority for hardware-focused contributors.

4. **Issue #4633: [Performance] SmolVLA in-place DynamicCache crop prevents torch.compile and limits inference to 4.8 Hz**  
   [Link](https://github.com/huggingface/lerobot/issues/4633)  
   *Why it matters*: SmolVLA is a popular lightweight vision-language-action (VLA) model for edge deployment. Its DynamicCache implementation breaks `torch.compile`, capping inference at 4.8 Hz — far below the 10–30 Hz required for real-world robot control.  
   *Community reaction*: 1 comment, active investigation from policy maintainers.

5. **Issue #4650: [RDA Audit] Data Quality Report for lerobot/svla_so101_pickplace**  
   [Link](https://github.com/huggingface/lerobot/issues/4650)  
   *Why it matters*: Dataset quality directly correlates to policy performance. A community contributor shared the open-source *Robot Data Audit (RDA)* tool, which automates quality checks for LeRobot-format datasets, along with a full audit of the `lerobot/svla_so101_pickplace` dataset (50 episodes, 11,939 frames).  
   *Community reaction*: 0 comments, newly filed, first external dataset auditing tool contribution.

6. **Issue #4649: migrate_policy_normalization emits empty config.json and does not copy model weights**  
   [Link](https://github.com/huggingface/lerobot/issues/4649)  
   *Why it matters*: The `migrate_policy_normalization` utility (v0.6.1) produces unloadable output directories with empty `config.json` files and missing weights, blocking users from upgrading existing policies to newer normalization formats.  
   *Community reaction*: 0 comments, newly filed critical tooling bug.

7. **Issue #4647: PreTrainedConfig.from_pretrained() leaves pretrained_path=None → silently builds untrained processor pipeline (blind policy)**  
   [Link](https://github.com/huggingface/lerobot/issues/4647)  
   *Why it matters*: A silent failure in `PreTrainedConfig.from_pretrained()` leaves `pretrained_path` unset, causing the pipeline to load an untrained "blind" policy instead of the requested pretrained weights. This is dangerous for hardware deployment and extremely difficult to debug.  
   *Community reaction*: 0 comments, newly filed high-severity bug.

---

## 4. Key PR Progress
10 high-impact PRs updated in the last 24 hours, selected by functional impact:
1. **PR #4651: feat(unitree-g1): add G1-23 embodiment support**  
   [Link](https://github.com/huggingface/lerobot/pull/4651)  
   Adds foundational support for the 23-DoF Unitree G1 variant while preserving existing G1-29 joint layout behavior, expanding LeRobot's humanoid hardware compatibility.

2. **PR #4607: perf(act): training on 8x B200, 28.0 ms to 13.0 ms per step**  
   [Link](https://github.com/huggingface/lerobot/pull/4607)  
   Delivers a 54% speedup for ACT policy training on 8x B200 GPUs via kernel launch optimization, reducing DDP buffer broadcast overhead and redundant loss computation in eager mode.

3. **PR #4613: feat(viz): add FiftyOne backend to lerobot-dataset-viz**  
   [Link](https://github.com/huggingface/lerobot/pull/4613)  
   Adds a `--display-mode fiftyone` option to the dataset visualization CLI, which reads LeRobot v3 dataset layouts directly without pre-decoding frames, enabling millisecond-scale dataset import.

4. **PR #4648: fix(configs): backfill pretrained_path in PreTrainedConfig.from_pretrained**  
   [Link](https://github.com/huggingface/lerobot/pull/4648)  
   Fixes Issue #4647 by writing the source pretrained path back to parsed configs, eliminating the silent "blind policy" failure mode for programmatic loading paths (notebooks, serving code).

5. **PR #3967: feat(policies): add LingBot-VLA 2.0**  
   [Link](https://github.com/huggingface/lerobot/pull/3967)  
   Adds native support for LingBot-VLA 2.0, an open-source VLA with a Qwen3-VL-4B backbone, sparse-MoE Qwen2 action expert, and flow-matching over a 55-D unified action space.

6. **PR #4057: feat(rollout): add-relative-action support to the synchronous inference engine**  
   [Link](https://github.com/huggingface/lerobot/pull/4057)  
   Adds relative-action support to `SyncInferenceEngine`, fixing intra-chunk drift for relative action policies by aligning pre/post-processing pipelines with prediction-time state anchors.

7. **PR #3984: Unitree G1 gripper control + multi-camera streaming**  
   [Link](https://github.com/huggingface/lerobot/pull/3984)  
   Adds ZMQ-based gripper control and synchronized head + wrist camera streaming for the Unitree G1, enabling end-to-end teleoperation and data collection for the HIW-500 dataset.

8. **PR #4645: feat(g1): select the sim's end effector and camera options through a config**  
   [Link](https://github.com/huggingface/lerobot/pull/4645)  
   Lets users configure G1 simulation end effectors (`dex1` parallel grippers, `dex3` articulated hands, or `dummy` bare wrists) and matching camera setups via config, aligning simulation with hardware variants.

9. **PR #4454: fix(rtc): chunk-splice jump and mean-action seam**  
   [Link](https://github.com/huggingface/lerobot/pull/4454)  
   Fixes two critical real-time control (RTC) bugs: chunk-splice jumps from discarded queued actions and mean-action seams at chunk boundaries, improving smoothness of RTC policy deployment.

10. **PR #4646: refactor: store language recipes only in policy configs**  
    [Link](https://github.com/huggingface/lerobot/pull/4646)  
    Removes standalone language recipe YAML files and centralizes recipe definitions in serialized policy configs, reducing configuration fragmentation and simplifying fine-tuning workflows for VLA policies.

---

## 5. Feature Request Trends
Distilled from issues updated in the last 24 hours:
- **Ecosystem standardization**: ROS 2 integration is the top cross-cutting request, with the community seeking an official unified strategy to replace 6 current incompatible third-party implementations.
- **Flexible data collection**: Demand for bounded full-task episode recording in DAgger workflows, combining autonomous rollouts and HIL corrections into single labeled episodes to improve imitation learning dataset quality.
- **Hardware safety**: Requests for configurable safe-home trajectories for robot arms (e.g, B601) to prevent damage during abrupt stops (Ctrl+C, process crashes).
- **Real-time inference performance**: Demand for `torch.compile` compatibility and speed optimizations for lightweight VLAs like SmolVLA to reach production-grade control frame rates.
- **Automated dataset tooling**: Community interest in open-source quality auditing tools for LeRobot-format datasets to reduce manual curation overhead and catch labeling/frame errors early.

---

## 6. Developer Pain Points
Recurring frustrations and high-friction issues reported by contributors:
- **Silent configuration failures**: Two critical bugs (#4647, #4649) cause config loading and migration workflows to produce broken outputs (empty configs, missing pretrained paths) without explicit errors, leading to hard-to-debug failures or dangerous untrained policies on hardware.
- **Fragmented middleware support**: No official ROS 2 integration forces developers to patch together 6 incompatible community projects, each covering only a subset of required functionality and lacking cross-compatibility.
- **Inflexible recording pipelines**: DAgger recording only supports unbounded continuous or corrections-only modes, forcing users to build custom post-processing scripts to construct full-task episode datasets.
- **Inference bottlenecks for edge use cases**: SmolVLA's DynamicCache implementation breaks `torch.compile`, capping inference at 4.8 Hz and making it unsuitable for most real-world robot control deployments.
- **Hardware safety gaps**: The B601 follower lacks a safe homing routine on disconnect, creating risk of arm damage or workspace injury during unexpected teleop or recording stops.

</details>

<details>
<summary><strong>OpenVLA</strong> — <a href="https://github.com/openvla/openvla">openvla/openvla</a></summary>

# OpenVLA Community Digest | 2026-09-16
Data source: [github.com/openvla/openvla](https://github.com/openvla/openvla)

---

## 1. Today's Highlights
The OpenVLA community is addressing a high-severity silent failure bug in OpenVLA-7B that occurs on transformers ≥4.50, where the model’s vision tower is bypassed during inference to produce plausible but fully input-independent action outputs with no error warnings. A targeted fix for the bug has been submitted via PR #348, which resolves a DynamicCache handling mismatch between newer transformers versions and OpenVLA’s generation pipeline. No new official releases were published in the 24-hour window.

---

## 2. Releases
No new official releases were published to the openvla/openvla repository in the 24-hour period ending 2026-09-16.

---

## 3. Hot Issues
(1 issue updated in the last 24 hours; no additional issues met the 24-hour activity threshold for inclusion)
- **#346: OpenVLA-7B silently ignores the image on transformers ≥4.50 — constant action for every input** | [Link](https://github.com/openvla/openvla/issues/346)
  - Why it matters: This is a critical correctness bug that breaks core inference functionality for all OpenVLA-7B variants (including fine-tuned checkpoints like `openvla/openvla-7b-finetuned-libero-spatial`) when used with transformers ≥4.50. The failure is silent: no error messages are raised, and the model returns semantically plausible action outputs completely unmoored from input visual data, making it extremely easy for developers to run invalid experiments, waste compute, or deploy broken models without detection. The issue is reproducible with standard `predict_action` workflows, greedy decoding, and PyTorch 2.10.0.
  - Community reaction: Filed by jashshah999 on 2026-09-07, the issue has 2 comments and 0 upvotes as of the digest window, but has received rapid triage with a dedicated fix PR submitted within 9 days, indicating maintainer prioritization of silent correctness failures.

---

## 4. Key PR Progress
(1 pull request updated in the last 24 hours; no additional PRs met the 24-hour activity threshold for inclusion)
- **#348: Fix silent vision bypass under transformers ≥4.50 empty DynamicCache** | [Link](https://github.com/openvla/openvla/pull/348)
  - Description: This PR resolves issue #346 by fixing a logic flaw in `prepare_inputs_for_generation` that caused the vision tower to be skipped on transformers ≥4.50. The root cause is that newer transformers versions pass an empty (but truthy) `DynamicCache` object on the first generation step instead of `None`; the previous check `past_key_values is not None` incorrectly triggered prompt slicing to a single token, bypassing all visual input processing. The fix adjusts cache validation logic to properly detect empty cache state, ensuring vision embeddings are included in the first forward pass.
  - Status: Open, filed 2026-09-16 by contributor dundysm, no comments or review feedback recorded as of the digest window.

---

## 5. Feature Request Trends
No new feature request issues were filed or updated in the 24-hour window ending 2026-09-16. Based on the available 24-hour activity dataset, no emerging feature request directions can be identified at this time.

---

## 6. Developer Pain Points
Based on 24-hour community activity, two key pain points are evident:
1. **Silent cross-dependency compatibility failures**: The #346 bug underscores a major risk for OpenVLA developers: breaking changes in upstream ML dependencies (specifically transformers’ DynamicCache behavior in v4.50+) can cause silent correctness issues with no explicit errors. Because the model produces plausible-looking outputs, developers may not detect the bug for extended periods, leading to wasted compute, invalid experimental results, and potential deployment failures.
2. **Insufficient dependency guardrails for core workflows**: The absence of upper-bound version pins for critical dependencies like transformers, combined with a lack of runtime validation checks for core inference paths (e.g., confirming vision tower activation), means users on recent, untested dependency stacks will hit this bug without warning, with no built-in safety net to catch functional regressions.

</details>

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*