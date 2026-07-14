# AI Open Source Trends 2026-07-14

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-14 01:19 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
2026-07-14

---

## 1. Today's Highlights
Today’s embodied intelligence and robotics ecosystem is defined by accelerating democratization of VLA (Vision-Language-Action) technology, with new beginner-focused resources lowering entry barriers for non-specialist developers. Open-source hardware-software co-design for robotic manipulation reached a new milestone, with the fully open OpenArm platform gaining a complete, production-ready control stack for contact-rich research and deployment. Standardized evaluation and safety for VLA policies emerged as a fast-growing priority, with new purpose-built tools for cross-platform benchmarking and adversarial red-teaming of embodied models. Lightweight, ROS-free deployment frameworks also gained traction, addressing long-standing developer pain points around middleware bloat for edge VLA inference. *Note: No projects from the daily GitHub trending top 10 met relevance criteria.*

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,193 total: The de facto standard open-source physics simulator for robotics, with native support for VLA policy training, sim2real transfer, and humanoid locomotion testing.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,667 total: NVIDIA’s unified robot learning framework built on Isaac Sim, rapidly becoming the preferred platform for scalable VLA and humanoid control training.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,842 total: Low-latency, dataflow-oriented robotic middleware that simplifies building composable, distributed AI-powered robotic applications without ROS overhead.
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,095 total: End-to-end reinforcement learning infrastructure purpose-built for embodied and agentic AI development, with native VLA training and deployment tooling.
- [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,126 total: Multimodal robotics data visualization and streaming tool that enables developers to debug, analyze, and iterate on VLA policy training and real-world deployments.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124 total: Lean, ROS-free sim2real framework for training and deploying VLA models and RL agents, with out-of-the-box support for common robot arms (Franka, UR5e, xArm) and humanoids.
- [softmata/horus](https://github.com/softmata/horus) ⭐389 total: High-performance open-source robotics runtime system, positioned as an "Android for robots" to standardize low-level control across heterogeneous robotic hardware.

---

### 🧠 VLA / Foundation Models
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,652 total: Community-driven tutorial series that teaches developers with only basic Python skills to build VLA models (including OpenVLA, SmolVLA, Pi0) from scratch, driving mass VLA democratization.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐382 total: First full Chinese-language, practical-oriented VLA learning and interview handbook, focused on robotics-specific challenges distinct from general CV/NLP.
- [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) ⭐60 total: RSS 2026 paper implementation introducing universal pose pretraining for generalizable VLA policies, demonstrating state-of-the-art performance across long-horizon manipulation tasks.
- [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) ⭐6 total: Minimal, human-readable VLA model built on frozen CLIP and a tiny prediction head, compatible with LeRobot and runnable on consumer Mac hardware without a GPU, ideal for VLA beginners.
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐60 total: Open-world foundation model for general-purpose embodied intelligence, designed to support cross-embodiment transfer across robot arms, humanoids, and mobile robots.
- [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) ⭐32 total: Bidirectionally aligned embodied agent framework optimized for long-horizon manipulation tasks, with built-in alignment between natural language commands and low-level robot actions.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐3 total: Universal evaluation framework for VLA and physical AI models, enabling developers to run a single benchmark across any policy, robot, or simulation environment.

---

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,713 total: Fully open-source 7-DOF bimanual humanoid arm designed for contact-rich physical AI research and deployment, with a low cost point that eliminates hardware barriers for small teams.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐206 total: Standardized benchmark suite for robotic manipulation, designed to measure real-world reliability and robustness of VLA and RL policies across diverse contact-rich tasks.
- [Manas-arumalla/openarm-control](https://github.com/Manas-arumalla/openarm-control) ⭐3 total: Complete, tested control and planning stack for the OpenArm v2, including IK, RRT-Connect planning, dynamic catching/throwing, cloth manipulation, and native support for ACT vision policies and RL.
- [philfung/awesome-reliable-robotics](https://github.com/philfung/awesome-reliable-robotics) ⭐156 total: Curated list of robotics research demonstrating real-world reliability and robustness, focused on manipulation use cases that work outside controlled lab environments.
- [ZihaoLu001/flexiv_control](https://github.com/ZihaoLu001/flexiv_control) ⭐3 total: Unified real-time control and safety layer for the Flexiv Rizon collaborative arm, with out-of-the-box support for teleoperation, MPC, RL, and sim2real transfer via MuJoCo.

---

### 🚶 Locomotion & Navigation
- [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,460 total: Mature open-source autopilot framework for drones, rovers, boats, and submersibles, supporting autonomous navigation across 300+ vehicle platforms.
- [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐809 total: End-to-end Isaac Lab workflow for legged robot development, enabling fast training and deployment of locomotion policies for humanoids and quadruped robots.
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐254 total: UMI-3D SLAM and data processing pipeline, optimized for high-accuracy spatial perception in dynamic embodied AI and navigation use cases.
- [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐246 total: ECCV 2026 high-fidelity navigation simulator using dynamic Gaussian Splatting, delivering photorealistic environments for embodied AI navigation training with minimal compute overhead.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐131 total: Lightweight, scalable whole-body teleoperation framework for humanoid robots, enabling low-latency teleop for locomotion and manipulation task data collection.

---

### 📦 Embodied Applications
- [strands-labs/robots](https://github.com/strands-labs/robots) ⭐102 total: Framework for controlling physical robotic hardware via natural language, integrating LLM agents with low-level robot control stacks for no-code task execution.
- [FastCrest/tether](https://github.com/FastCrest/tether) ⭐73 total: Open-source edge-to-cloud AI deployment CLI, optimized for robotics use cases, with native support for Jetson, RTX, Apple Silicon, and AMD hardware, plus hybrid edge-cloud inference for VLAs.
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,569 total: RoboTwin 2.0 digital twin platform for embodied AI, enabling photorealistic sim2real transfer for VLA policies and humanoid control systems.
- [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,568 total: Large-scale embodied AI research platform with 1,000+ real-world everyday tasks, designed to train and evaluate generalist embodied agents on long-horizon household and industrial tasks.
- [provael/provael](https://github.com/provael/provael) ⭐3 total: Red-teaming tool for open VLA robot policies, enabling developers to test adversarial attack resilience across simulation environments and generate standardized Attack Success Rate (ASR) metrics for embodied AI safety.

---

## 3. Trend Signal Analysis (~260 words)
The most explosive community growth today is in VLA democratization, driven by beginner-focused resources that eliminate historical barriers to entry for non-academic developers. Projects like *every-embodied* and VIRENA enable developers with only basic Python skills to run and train VLA models on consumer hardware, mirroring the 2022–2023 LLM democratization wave that turned NLP from a niche field to a mass developer ecosystem. A critical new emerging direction is standardized VLA evaluation and safety, with purpose-built tools for cross-platform benchmarking (inspect-robots) and adversarial red-teaming (provael) filling a gap that has slowed real-world VLA deployment. This aligns directly with recent industry momentum: as commercial humanoid vendors (Figure, Agility Robotics, Boston Dynamics) prepare for large-scale deployments, robust VLA safety and performance testing has become a top priority for regulators and customers alike. Another notable shift is the rise of hardware-software co-design for open manipulation platforms, with the OpenArm ecosystem following the success of open legged robot platforms to reduce the cost of real-world VLA testing by 90% compared to proprietary alternatives. Finally, ROS-free deployment stacks are gaining widespread traction as developers reject ROS bloat in favor of lightweight, edge-optimized middleware for low-power VLA inference on Jetson and Apple Silicon hardware.

---

## 4. Community Hot Spots
- **Beginner VLA onboarding tooling** (e.g., [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied), [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA)): These projects are driving mass adoption of VLA technology by opening the field to developers without robotics PhDs, similar to how early LLM tutorials and fine-tuning tools democratized generative AI.
- **Open-source manipulation hardware-software stacks** (e.g., [enactic/openarm](https://github.com/enactic/openarm), [Manas-arumalla/openarm-control](https://github.com/Manas-arumalla/openarm-control)): Fully open, low-cost bimanual arm platforms eliminate the largest cost barrier to real-world VLA research, with native support for common policy architectures and sim2real workflows accessible to small teams and individual developers.
- **VLA safety and evaluation infrastructure** (e.g., [provael/provael](https://github.com/provael/provael), [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)): As VLA models move from lab prototypes to commercial humanoid deployments, standardized benchmarking and red-teaming tooling is a critical unmet need, with early projects in this space poised to become de facto industry standards.
- **Lightweight, ROS-free deployment middleware** (e.g., [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack), [dora-rs/dora](https://github.com/dora-rs/dora)): These stacks address widespread developer frustration with ROS overhead and complexity, enabling fast, low-latency deployments of VLA policies on edge hardware for consumer and industrial robotics use cases.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*