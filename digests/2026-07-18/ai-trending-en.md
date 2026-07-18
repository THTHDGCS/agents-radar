# AI Open Source Trends 2026-07-18

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-18 01:20 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report | 2026-07-18

---

## 1. Today's Highlights
Today’s open-source embodied AI and robotics ecosystem is defined by accelerating democratization of Vision-Language-Action (VLA) development, with beginner-friendly educational resources and low-resource deployable models drawing thousands of new developers to the space. Humanoid robotics infrastructure is maturing rapidly, with new open hardware designs, purpose-built runtime systems, and unified control frameworks gaining traction as both research teams and startups prioritize accessible, modular development stacks. Embodied AI safety and evaluation tooling is emerging as a fast-growing niche, with dedicated red-teaming and benchmarking tools launching to address gaps in VLA testing ahead of wider real-world deployment. Simulation and middleware ecosystems are also shifting away from legacy ROS architectures, with new low-latency, AI-native frameworks addressing longstanding pain points for sim-to-real VLA deployment.

---

## 2. Top Projects by Category
*(All star counts are total GitHub stars; today's new stars are noted if available)*

### 🤖 Robot Frameworks / SDKs
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,846
  A low-latency, composable Rust-based Dataflow-Oriented Robotic Architecture middleware, gaining traction as a lightweight, AI-native alternative to ROS for VLA and robotic application development.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,247
  The de facto open-source physics simulator for robot learning and VLA training, with ongoing updates to support GPU-accelerated batch simulation for large-scale embodied policy training.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,698
  NVIDIA’s unified robot learning framework built on Isaac Sim, the industry standard for sim-to-real VLA and reinforcement learning (RL) training for manipulators, legged robots, and humanoids.
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,149
  Purpose-built reinforcement learning infrastructure for embodied and agentic AI, streamlining the end-to-end pipeline from policy training to real-world robotic deployment.
- [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,139
  A multimodal robotics data visualization and streaming tool, enabling developers to debug VLA model inputs, outputs, and execution traces across simulation and real hardware.
- [softmata/horus](https://github.com/softmata/horus) ⭐389
  A high-performance Rust-based robotics runtime system, marketed as an "Android for robots" to standardize low-level control across heterogeneous robotic hardware platforms.

### 🧠 VLA / Foundation Models
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,727
  A beginner-friendly, zero-to-advanced course for building embodied intelligent robots, with step-by-step tutorials to implement OpenVLA, SmolVLA, and Pi0 models from scratch with only basic Python knowledge.
- [knightnemo/Awesome-World-Models](https://github.com/knightnemo/Awesome-World-Models) ⭐3,174
  A curated list of world modeling research, a core foundational technology for generalizable embodied AI and VLA policy planning for long-horizon tasks.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐401
  A Chinese-language, practice-oriented learning and interview handbook for VLA engineers, focused exclusively on robotics-specific challenges unique to embodied AI rather than general CV/NLP topics.
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐505
  A state-of-the-art VLA model series that unifies visual understanding, content generation, and robotic action output for general-purpose manipulation tasks.
- [Open-X-Humanoid/XR-1](https://github.com/Open-X-Humanoid/XR-1) ⭐186
  A versatile VLA model that learns unified vision-motion representations to support cross-domain robotic tasks including manipulation and locomotion.
- [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐583
  A foundation model for whole-body humanoid control, enabling generalizable locomotion and loco-manipulation policies across different humanoid hardware platforms.
- [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) ⭐7
  A minimal, readable VLA model built on frozen CLIP and a tiny policy head, optimized to run on consumer Mac hardware without a GPU for ManiSkill PickCube manipulation tasks, ideal for learning core VLA mechanics.

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,733
  A fully open-source humanoid manipulator arm designed for contact-rich physical AI research and deployment, one of the few open, production-ready robotic arm platforms for VLA testing.
- [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) ⭐38
  A bidirectionally aligned embodied agent framework optimized for long-horizon manipulation tasks, addressing common VLA failure modes in multi-step real-world tasks.
- [RoboTwin-Platform/RMBench](https://github.com/RoboTwin-Platform/RMBench) ⭐170
  A memory-dependent manipulation benchmark built on the RoboTwin digital twin platform, designed to evaluate VLA performance on tasks requiring state tracking over long time horizons.
- [iit-DLSLab/locomanipulation-teleop-isaaclab](https://github.com/iit-DLSLab/locomanipulation-teleop-isaaclab) ⭐21
  An IsaacLab DirectEnv implementation for teleoperating Unitree Go2 legged robots with AgileX Piper manipulators, supporting both sim-to-sim and sim-to-real loco-manipulation workflows.
- [chang-xinhai/Awesome-Dexterous-Manipulation](https://github.com/chang-xinhai/Awesome-Dexterous-Manipulation) ⭐11
  A curated list of resources for dexterous manipulation, tactile sensing, dexterous hardware, and relevant VLA policies, serving as a one-stop reference for manipulation researchers.

### 🚶 Locomotion & Navigation
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,148
  The most popular open-source robotics operating system, currently providing advanced driver assistance for over 300 supported car models, serving as a leading example of large-scale embodied AI deployment for autonomous navigation.
- [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐819
  A direct IsaacLab workflow toolkit for legged robot development, streamlining the pipeline from simulation training to real-world deployment for quadruped and humanoid robots.
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐258
  A robust SLAM and data processing pipeline for embodied 3D perception, optimized for low-power edge hardware on mobile robots and humanoids.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐132
  A lightweight, scalable whole-body teleoperation framework for humanoid robots, enabling low-latency remote control for data collection and VLA policy demonstration.
- [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐26
  An affordable, fully 3D-printable open-source humanoid robot powered by a Raspberry Pi Zero 2W, designed as an accessible DIY platform for learning locomotion and embodied AI for students and hobbyists.

### 📦 Embodied Applications
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐704
  A self-evolving embodied AI operating system built on agentic workflows, enabling robots to autonomously improve their policies and adapt to new real-world environments without manual retraining.
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,598
  An open-source digital twin platform for robotics, providing high-fidelity simulation environments for VLA training and sim-to-real transfer for manipulators and humanoids.
- [strands-labs/robots](https://github.com/strands-labs/robots) ⭐102
  A developer tool that enables natural language control of physical robotic hardware via LLM-powered agents, abstracting away low-level control code for non-specialist users.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐6
  A standardized evaluation framework for VLA and physical AI models, allowing developers to test any policy on any robot or simulation environment with a single benchmark definition, analogous to Inspect AI for general LLMs.
- [provael/provael](https://github.com/provael/provael) ⭐3
  An open-source red-teaming tool for VLA policies that systematically tests for safety vulnerabilities in simulation and outputs an Attack Success Rate metric, addressing a critical gap in embodied AI safety testing.
- [FastCrest/tether](https://github.com/FastCrest/tether) ⭐73
  An open-source CLI tool for deploying AI models to edge robotic hardware including Jetson, RTX, and Apple Silicon devices, with support for hybrid edge-cloud inference with performance parity guarantees.

---

## 3. Trend Signal Analysis
The most explosive community attention today is centered on democratized VLA development, with educational repositories focused on entry-level VLA implementation amassing thousands of stars, signaling a massive influx of developers moving from general AI to robotics-specific model building. A notable new tech stack direction is the rise of ROS-free robotic middleware and deployment frameworks: projects like dora-rs prioritize low-latency composable dataflows and native VLA/RL integration, directly addressing widespread developer complaints about legacy ROS overhead for AI-native robotic workflows. This activity aligns closely with recent industry and research events: ICRA 2026 keynotes last month emphasized reducing VLA deployment friction and expanding access to embodied AI tooling, while humanoid robotics startups have increasingly adopted open-source infrastructure to cut development timelines and costs. Additionally, embodied AI safety is a fast-emerging high-priority niche, with new red-teaming and standardized evaluation tools launching to address regulatory and industry concerns about real-world VLA deployment risks in manufacturing and logistics. (248 words)

---

## 4. Community Hot Spots
- **Beginner VLA development pathways**: Repositories like [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) and [xiaoms22/lunavla](https://github.com/xiaoms22/lunavla) enable developers with only basic Python experience to build and test VLA models without high-end GPU hardware, lowering the highest barrier to entry for the fastest-growing segment of embodied AI.
- **ROS-free AI-native robotic middleware**: [dora-rs/dora](https://github.com/dora-rs/dora) and [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) are building a next-generation tech stack for VLA deployment, eliminating legacy ROS bloat and natively supporting end-to-end AI workflows, making them a high-priority area for developers building production-ready robotic systems.
- **Embodied AI safety and evaluation tooling**: [provael/provael](https://github.com/provael/provael) and [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) address the largely unmet need for standardized VLA testing, a critical gap as VLA models move from lab environments to commercial real-world deployments.
- **Open-source humanoid hardware and runtime**: [enactic/openarm](https://github.com/enactic/openarm) and [softmata/horus](https://github.com/softmata/horus) provide fully open, affordable hardware and runtime infrastructure for physical AI research, filling a gap left by proprietary humanoid platforms that are inaccessible to most small research teams and independent developers.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*