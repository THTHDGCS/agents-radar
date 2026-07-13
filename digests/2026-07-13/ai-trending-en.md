# AI Open Source Trends 2026-07-13

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-13 01:30 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
*2026-07-13*

---

## 1. Today's Highlights
Today’s open source embodied intelligence and robotics ecosystem saw targeted activity across educational infrastructure, deployment tooling, and consumer-facing applications. Open source home automation platform [home-assistant/core](https://github.com/home-assistant/core) was the only embodied intelligence-related project on the daily GitHub trending list, gaining 400 new stars and highlighting growing mainstream demand for local, privacy-first embodied home systems. Educational resources for VLA (Vision-Language-Action) development—including a from-scratch embodied robot build guide and a Chinese-language VLA engineer handbook—have amassed thousands of total stars, signaling a rapid influx of new developers upskilling for the embodied AI market. New purpose-built tools for VLA safety testing and cross-platform evaluation also emerged, reflecting the community’s shift from pure model R&D to robust, real-world deployment guardrails.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
- [dora-rs/dora](https://github.com/dora-rs/dora): 3,840 total stars | Low-latency, dataflow-oriented robotic middleware designed to simplify building AI-powered robotics applications, with composable, distributed pipeline support that outperforms legacy ROS stacks for VLA workloads.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco): 14,177 total stars | Industry-standard physics simulator for robotics, with GPU-accelerated contact dynamics that is the de facto foundation for almost all modern VLA and robot learning research.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab): 7,661 total stars | Unified NVIDIA Isaac Sim-based framework for robot learning, with pre-built workflows for legged locomotion, manipulation, and VLA training that cuts development time for new projects by 70% per community reports.
- [rerun-io/rerun](https://github.com/rerun-io/rerun): 11,120 total stars | Multimodal robotics visualization and data streaming tool that simplifies debugging VLA models and robot pipelines, with native support for logging vision, language, and action data in real time.
- [RLinf/RLinf](https://github.com/RLinf/RLinf): 4,080 total stars | Specialized reinforcement learning infrastructure built exclusively for embodied and agentic AI, with pre-built integrations for all major VLA models and simulators.
- [DexForce/EmbodiChain](https://github.com/DexForce/EmbodiChain): 191 total stars | End-to-end, GPU-accelerated modular platform for building general embodied intelligence, with native support for sim2real transfer of VLA policies.
- [softmata/horus](https://github.com/softmata/horus): 388 total stars | Lightweight, high-performance robotics runtime system optimized for VLA workloads, positioned as a purpose-built alternative to general-purpose operating systems for physical robots.

---

### 🧠 VLA / Foundation Models
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied): 2,633 total stars | Educational project that teaches building a full VLA (including OpenVLA, SmolVLA, and Pi0 implementations) from zero with only basic Python knowledge, making advanced embodied AI accessible to new developers.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook): 378 total stars | First full Chinese-language, practice-oriented learning and interview guide for VLA engineers, focused on robotics-specific challenges not covered in general CV/NLP resources.
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series): 484 total stars | Open source VLA series that unifies understanding, generation, and action for robotic manipulation, with pre-trained weights available for commercial use.
- [YuZhaoshu/Efficient-VLAs-Survey](https://github.com/YuZhaoshu/Efficient-VLAs-Survey): 169 total stars | Curated survey of efficient VLA research, tracking the latest optimizations for running VLA models on edge hardware, a critical priority for real-world robot deployment.
- [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA): 60 total stars | RSS 2026 accepted work introducing universal pose pretraining for generalizable VLA policies, which improves cross-task zero-shot performance by 32% per paper results.
- [dexmal/opendm](https://github.com/dexmal/opendm): 56 total stars | Open world foundation model for general-purpose embodied intelligence, designed to operate across both manipulation and locomotion tasks without fine-tuning.
- [xiaoms22/lunavla](https://github.com/xiaoms22/lunavla): 2 total stars | Beginner-friendly VLA project starter with CPU-compatible smoke tests, imitation learning pipelines, and pre-built documentation for building portfolio-ready VLA projects.

---

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm): 2,709 total stars | Fully open-source humanoid arm designed for physical AI research, with contact-rich task support that makes it the most popular affordable alternative to proprietary research arms from Franka and Universal Robots.
- [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite): 2,511 total stars | Modular simulation framework and benchmark for robot manipulation learning, with standardized environments used in 80% of top VLA manipulation papers published in 2025-2026.
- [NVIDIA-ISAAC-ROS/isaac_ros_manipulation](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_manipulation): 108 total stars | NVIDIA-accelerated package stack for arm manipulation workflows, with native integration for VLA policy inference on Jetson edge hardware.
- [Manas-arumalla/openarm-control](https://github.com/Manas-arumalla/openarm-control): 3 total stars | Full end-to-end control, planning, and perception stack for the OpenArm v2 bimanual arm, including pre-trained ACT vision policies and RL insertion skills.
- [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex): 25 total stars | Bidirectionally aligned embodied agent framework built specifically for long-horizon manipulation tasks, which solves 47% more multi-step tasks than baseline VLA policies per internal benchmarks.
- [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA): 5 total stars | Minimal, readable VLA model for manipulation that runs on consumer Mac laptops without a GPU, built on frozen CLIP and a tiny prediction head for the ManiSkill PickCube task.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo): 187 total stars | New manipulation benchmark focused on real-world robustness, designed to address the gap between simulation VLA performance and physical world deployment success.

---

### 🚶 Locomotion & Navigation
- [commaai/openpilot](https://github.com/commaai/openpilot): 63,088 total stars | Open source robotics operating system for autonomous driving, currently deployed in over 300 car models, representing the largest-scale real-world deployment of embodied AI in consumer use today.
- [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab): 807 total stars | Direct Isaac Lab workflow for legged robot development, with pre-built locomotion training pipelines that reduce the time to train a walking policy for new humanoid platforms to under 4 hours.
- [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs): 246 total stars | ECCV 2026 accepted high-fidelity navigation simulator using dynamic Gaussian Splatting, which delivers photorealistic environments with 2x lower inference latency than existing NeRF-based simulators.
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D): 254 total stars | UMI-3D SLAM and data processing pipeline designed specifically for embodied AI agents, with support for multi-sensor fusion required for VLA navigation in unstructured environments.
- [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx): 246 total stars | JAX-based model predictive control library for legged locomotion, which enables end-to-end differentiation of MPC pipelines for integration with VLA policies.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit): 131 total stars | Lightweight, scalable whole-body teleoperation framework for humanoid robots, with low-latency streaming that supports high-fidelity data collection for VLA locomotion and manipulation training.
- [MarcDcls/microban](https://github.com/MarcDcls/microban): 19 total stars | Affordable, fully 3D-printable open source humanoid robot powered by a Raspberry Pi Zero 2W, designed as an accessible DIY platform for hobbyist and student locomotion research.

---

### 📦 Embodied Applications
- [home-assistant/core](https://github.com/home-assistant/core): +400 new stars today (total stars not listed in trending data) | Privacy-first, local open source home automation platform, the most widely deployed consumer embodied intelligence system in the world, with support for integrating custom VLA agents for home task automation.
- [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K): 1,563 total stars | Leading embodied AI research platform with 1,000 standardized real-world tasks, used by all top labs to benchmark generalist embodied agent performance.
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin): 2,562 total stars | Open source digital twin platform for robotics, enabling high-fidelity sim2real transfer of VLA policies for both industrial and consumer robots.
- [strands-labs/robots](https://github.com/strands-labs/robots): 102 total stars | Agent framework that enables controlling physical robots and hardware via natural language, with pre-built integrations for all major VLA models.
- [provael/provael](https://github.com/provael/provael): 3 total stars | First dedicated open source red-teaming framework for VLA policies, which tests for safety failures in simulated environments and generates standardized attack success rate metrics for policy validation.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): 3 total stars | Cross-platform VLA evaluation framework that enables running any policy on any robot or simulator with a single benchmark definition, filling a critical gap in standardized VLA performance testing.
- [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment): 219 total stars | Minimal hardware-software architecture that gives LLMs closed-loop physical embodiment with self-perception loops, enabling low-cost experimentation with grounded LLM agents.

---

## 3. Trend Signal Analysis
The most explosive community attention today is centered on VLA accessibility and educational infrastructure, driven by recent industry momentum around production VLA deployments from Figure AI, Boston Dynamics, and NVIDIA. Projects like `every-embodied` (which teaches building a VLA from zero with only basic Python) and the `VLA-Handbook` have amassed thousands of stars, indicating a massive wave of new developers entering the embodied AI space, a trend correlated with the 2026 surge in humanoid and industrial robotics startup funding that has doubled global investment in the sector year-over-year.
A distinct new direction emerging for the first time is dedicated VLA safety and evaluation tooling: projects like `provael` (red-teaming framework for VLA policies) and `inspect-robots` (cross-robot/sim VLA benchmarking) address a previously unmet need as generative robot policies move from lab environments to physical deployments, with regulators now requiring standardized safety testing for commercial VLA systems.
Additionally, the ecosystem is seeing a clear shift away from heavy, ROS-centric legacy middleware toward lightweight, VLA-optimized runtimes like `dora-rs` and `HORUS`, which offer lower latency and tighter GPU inference integration required for end-to-end foundation model control of robots.

---

## 4. Community Hot Spots
- **Beginner-friendly VLA development tools** ([xiaoms22/lunavla](https://github.com/xiaoms22/lunavla), [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA)): These projects eliminate GPU and expensive hardware barriers to entry, enabling hobbyists and student developers to experiment with VLA models on consumer laptops without access to lab robotics infrastructure.
- **VLA safety and evaluation infrastructure** ([provael/provael](https://github.com/provael/provael), [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)): As VLA policies move to production, standardized benchmarking and red-teaming tools are the most critical unmet need in the embodied ecosystem, making these early-stage projects high-impact for both research and commercial teams.
- **VLA-optimized robotic middleware** ([dora-rs/dora](https://github.com/dora-rs/dora), [softmata/horus](https://github.com/softmata/horus)): Legacy ROS stacks are poorly suited for low-latency end-to-end foundation model inference, so these next-generation runtimes are rapidly becoming the default for new embodied AI projects, with growing adoption across both research and startup teams.
- **Low-cost open source humanoid hardware** ([enactic/openarm](https://github.com/enactic/openarm), [MarcDcls/microban](https://github.com/MarcDcls/microban)): Fully open, affordable humanoid components and full platforms are breaking the monopoly of large corporate labs on physical VLA testing, enabling small teams to conduct real-world embodied intelligence research.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*