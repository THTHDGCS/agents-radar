# AI Open Source Trends 2026-07-15

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-15 01:16 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-07-15

---

## 1. Today's Highlights
None of the 15 global GitHub daily trending repositories focus on embodied intelligence, VLA, or robotics, with top spots dominated by general LLM agent tools, media editors, and productivity utilities. However, 7-day active topic repositories reveal surging community investment in democratizing VLA development, with multiple beginner-friendly educational resources and low-cost hardware platforms launching to lower entry barriers. Open-source humanoid manipulator project OpenArm reached 2.7k total stars, indicating strong demand for accessible physical hardware to test VLA policies, while new dedicated VLA evaluation and safety tooling emerged as a fast-growing subcategory. The ecosystem is also seeing a shift away from traditional ROS stacks toward lighter, VLA-native runtime and deployment frameworks optimized for edge hardware.

---

## 2. Top Projects by Category
*Note: No relevant embodied AI/robotics projects appeared on the daily GitHub trending list, so all star counts below reflect total repository stars as of 2026-07-15.*

### 🤖 Robot Frameworks / SDKs
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,676 — Unified robot learning framework built on NVIDIA Isaac Sim, the de facto standard for sim-to-real VLA and humanoid control research, with active weekly updates supporting new robot platforms.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,842 — Dataflow-oriented robotic middleware designed for low-latency, composable AI robotic applications, gaining traction as a lightweight alternative to ROS for VLA deployments.
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,106 — Reinforcement learning infrastructure purpose-built for embodied and agentic AI, streamlining RL policy training for VLA and locomotion tasks.
- [softmata/horus](https://github.com/softmata/horus) ⭐389 — Rust-based high-performance robotics runtime, positioned as an "Android for robots" to standardize low-level control across humanoid and manipulator hardware.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124 — ROS-free sim-to-real framework for training and deploying VLA models and RL agents, with native support for common manipulator and humanoid platforms like Franka and SO101.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,208 — Industry-standard GPU-accelerated physics simulator, used for nearly all open-source VLA and humanoid locomotion research and prototyping.

### 🧠 VLA / Foundation Models
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐384 — Chinese-language, practice-oriented learning and interview handbook for VLA engineers, focused on robotics-specific challenges distinct from general CV/NLP, filling a major gap in non-English VLA educational resources.
- [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐112 — Comprehensive survey of embodied AI safety covering risks, attacks, and defenses across perception, planning, and agentic systems, with 500+ curated papers, a key resource for VLA safety research.
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐61 — Open-world foundation model for general-purpose embodied intelligence, one of the few fully open VLA foundation models targeting cross-platform robot control.
- [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) ⭐6 — Minimal, readable VLA model that runs on consumer Mac hardware with no GPU, integrated with LeRobot and ManiSkill, lowering testing barriers for new VLA developers.
- [xiaoms22/lunavla](https://github.com/xiaoms22/lunavla) ⭐2 — Beginner-friendly VLA project starter with ACT imitation learning, evaluation pipelines, and resume-ready documentation, designed for entry-level VLA engineers.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐3 — Evaluation framework for VLA and physical AI models, enabling one-time benchmark definition to run policies across any robot or simulation, analogous to Inspect AI for robotics.
- [provael/provael](https://github.com/provael/provael) ⭐3 — First open-source red-teaming framework for VLA robot policies, measuring attack success rate in simulation to test physical safety of deployed VLA agents.

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,720 — Fully open-source humanoid arm designed for contact-rich physical AI research, the highest-starred open manipulator platform released in 2026, with a full accompanying control stack.
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐254 — UMI-3D SLAM and data processing pipeline for manipulation tasks, supporting the Universal Manipulation Interface ecosystem for cross-platform robot skill transfer.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐230 — New standard manipulation benchmark for VLA and robot learning, with standardized task definitions across simulation and real hardware.
- [RoboTwin-Platform/RMBench](https://github.com/RoboTwin-Platform/RMBench) ⭐167 — Memory-dependent manipulation benchmark built on the RoboTwin digital twin platform, testing long-horizon manipulation skills critical for real-world deployments.
- [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) ⭐35 — Bidirectionally aligned embodied agent framework for long-horizon manipulation, combining VLA and symbolic planning for complex assembly and household tasks.
- [Manas-arumalla/openarm-control](https://github.com/Manas-arumalla/openarm-control) ⭐3 — Full control, planning, and learning platform for the OpenArm v2 bimanual manipulator, with support for ACT vision policies, RL insertion, and language-commanded skills.

### 🚶 Locomotion & Navigation
- [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐811 — Direct Isaac Lab workflow for legged robot development, streamlining sim-to-real locomotion policy training for humanoids and quadrupeds.
- [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐91 — Official implementation of the 2026 Omni-Modal Motion Generation model for generalist humanoid control, enabling cross-modal command of full-body humanoid locomotion and manipulation.
- [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐20 — Affordable, fully 3D-printable open-source humanoid robot powered by a Raspberry Pi Zero 2W, designed as an accessible DIY platform for hobbyists and entry-level robotics researchers.
- [ispaik06/convex-mpc-biped](https://github.com/ispaik06/convex-mpc-biped) ⭐12 — Open implementation of convex model predictive control for biped humanoid locomotion in MuJoCo, a reference for stable low-level humanoid walking control.
- [Open-X-Humanoid/BICMap](https://github.com/Open-X-Humanoid/BICMap) ⭐35 — WebGL-based SDK for visualizing SLAM maps, point clouds, and robot navigation data, enabling browser-based monitoring of mobile robot and humanoid localization.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,461 — Mature ROS 2 navigation framework, the standard for path planning and obstacle avoidance in mobile robots and autonomous systems.

### 📦 Embodied Applications
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,665 — Zero-to-embodied-AI course for developers with only basic Python knowledge, walking learners through building VLA models including OpenVLA and SmolVLA from scratch, one of the fastest-growing embodied educational resources of 2026.
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,577 — Official RoboTwin 2.0 digital twin platform for robotics, enabling high-fidelity sim-to-real transfer for VLA and humanoid control via photorealistic simulation and hardware alignment.
- [strands-labs/robots](https://github.com/strands-labs/robots) ⭐102 — Framework for controlling physical robots and hardware via natural language using LLM agents, enabling no-code command of manipulators and mobile robots for non-technical users.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐131 — Lightweight, scalable whole-body teleoperation framework for humanoid robots, supporting low-latency teleop for kinesthetic teaching and VLA demonstration data collection.
- [FastCrest/tether](https://github.com/FastCrest/tether) ⭐73 — Open-source edge-to-cloud AI deployment CLI for robotics, optimizing and deploying VLA models across Jetson, RTX, Apple Silicon, and AMD hardware with hybrid edge-cloud inference support.
- [DexForce/EmbodiChain](https://github.com/DexForce/EmbodiChain) ⭐193 — End-to-end, GPU-accelerated modular platform for building generalized embodied intelligence, integrating perception, planning, and control modules for rapid embodied agent development.

---

## 3. Trend Signal Analysis
The most explosive community attention in embodied AI this week is focused on democratizing VLA development, driven by the 2026 release of small, runnable open VLA models like OpenVLA and SmolVLA that no longer require datacenter-scale compute. Educational resources such as every-embodied, the VLA Handbook, and LunaVLA are targeted at developers with only basic Python experience, expanding the VLA developer pool far beyond traditional robotics PhD researchers. A notable new direction appearing for the first time is dedicated VLA safety and evaluation infrastructure: projects like inspect-robots and Provael are the first open-source tools purpose-built for standardized VLA benchmarking across sim and real hardware, as well as red-teaming to test physical safety of deployed policies. This aligns directly with recent industry announcements of commercial humanoid deployments in manufacturing and logistics, where regulatory safety requirements and consistent performance metrics are critical for real-world rollout. Additionally, lightweight, ROS-free sim2real and runtime frameworks (Robot Control Stack, HORUS) are gaining traction as developers seek to avoid the overhead of traditional robotics middleware for edge-deployed VLA agents on low-power hardware like Jetson and Raspberry Pi.

---

## 4. Community Hot Spots
- **Beginner VLA onboarding ecosystems**: Projects like [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied), [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook), and [xiaoms22/lunavla](https://github.com/xiaoms22/lunavla) are filling a critical gap for non-specialist developers, making VLA development accessible to general ML engineers, and will drive a wave of new VLA applications and fine-tuned models in the next 6–12 months.
- **VLA safety and evaluation infrastructure**: [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) and [provael/provael](https://github.com/provael/provael) are the first open-source tools dedicated to standardized VLA benchmarking and red-teaming, addressing a major pain point that has slowed commercial VLA deployment, and are likely to become de facto testing tools as VLA adoption grows.
- **Open humanoid manipulator hardware**: [enactic/openarm](https://github.com/enactic/openarm) (2.7k stars) is the highest-starred open humanoid arm platform released in 2026, with a full accompanying control and learning stack that reduces the cost of physical VLA testing by an order of magnitude relative to commercial manipulators.
- **Lightweight VLA-native deployment stacks**: [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) and [softmata/horus](https://github.com/softmata/horus) are ROS-free runtime and sim2real frameworks optimized for edge VLA inference, addressing the high latency and overhead of traditional ROS stacks for low-power embedded robot hardware.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*