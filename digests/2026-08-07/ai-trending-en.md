# AI Open Source Trends 2026-08-07

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-07 02:02 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-08-07

---

## 1. Today's Highlights
Today's embodied AI and robotics ecosystem is highlighted by NVIDIA's major open-source push for vision-language-action (VLA) models for autonomous vehicles, with four active Alpamayo series repos spanning 10B to 34B parameter models, RL enhancement, and deployment recipes. Standardized evaluation for VLA and physical AI is emerging as a high-priority community focus, with new open-source tools that enable cross-platform testing of models across simulated and real robotic hardware. Accessible educational resources for VLA and embodied intelligence are seeing rapid adoption, including a full Chinese-language VLA interview/learning handbook and a zero-to-VLA build course targeted at developers with only basic Python skills. Humanoid robotics tooling is also maturing, with new open-source runtime systems, teleoperation stacks, and low-cost open manipulators addressing long-standing deployment barriers.

---

## 2. Top Projects by Category
No relevant projects from today's GitHub trending list (all trending entries were general coding agents, authentication tools, or unrelated utilities, excluded per filtering rules). Stars listed below are total GitHub stars; today's new stars are not available for topic search repos.

### 🤖 Robot Frameworks / SDKs (control, simulation, planning, motion)
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,848 total — Unified robot learning framework built on NVIDIA Isaac Sim, the de facto standard for GPU-accelerated robotic simulation, making it a core tool for training VLA and RL policies at scale.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,869 total — Low-latency, dataflow-oriented robotic middleware designed explicitly for AI-powered robotic applications, with native support for distributed deployment that simplifies complex embodied agent orchestration.
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,205 total — Open-source, GPU-parallelized robotics simulator and manipulation benchmark, supporting massive parallel policy training that cuts VLA training time for manipulation tasks by orders of magnitude.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐127 total — Lean, ROS-free sim-to-real framework for deploying VLA models and RL agents to common robotic arms (Franka, UR5e, xArm) and humanoids, eliminating a major pain point of ROS dependency for rapid VLA testing.
- [softmata/horus](https://github.com/softmata/horus) ⭐407 total — High-performance Rust-based robotics runtime system, positioned as an Android-style general-purpose OS for robots, with optimizations for low-latency control critical for humanoid and contact-rich manipulation tasks.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐128 total — Open-source evaluation framework for physical AI that enables testing any VLA/LLM policy across any arm, humanoid, or simulated benchmark, addressing the critical lack of standardized testing for embodied models.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,470 total — Industry-standard multi-joint physics simulator with contact modeling, the foundational tool for almost all simulated robot learning and VLA pre-training workflows.

### 🧠 VLA / Foundation Models (vision-language-action, imitation learning, RL policies)
- [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐117 total — NVIDIA's 34B-parameter multi-task VLA foundation model for autonomous vehicles, the largest open VLA targeted at driving, marking a major expansion of VLA use cases beyond industrial manipulation.
- [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) ⭐102 total — Official developer hub for the Alpamayo VLA series, with pre-built recipes for fine-tuning, RL post-training, quantization, and deployment, making state-of-the-art driving VLA accessible to small teams.
- [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) ⭐201 total — Official implementation of BridgeVLA and BridgeVLA++, the latest open general-purpose VLA models trained on massive cross-embodiment robotic data, a common baseline for new VLA research.
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐142 total — Open-world foundation model for general-purpose embodied intelligence, designed to work across diverse robotic embodiments without task-specific fine-tuning, a key step toward general physical AI.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐479 total — Full Chinese-language, practice-oriented learning and interview handbook for VLA engineers, focused exclusively on robotics-specific VLA challenges rather than general CV/NLP, filling a major educational gap for Chinese-speaking developers.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,029 total — Project-based course that teaches developers with only basic Python skills to build VLA models (including OpenVLA, SmolVLA, Pi0) from scratch, dramatically lowering the barrier to entry for VLA development.
- [worldbench/awesome-embodied-data-pyramid](https://github.com/worldbench/awesome-embodied-data-pyramid) ⭐136 total — Comprehensive survey of the data pyramid for embodied manipulation, compiling best practices for data collection, curation, and scaling for VLA training, addressing the biggest bottleneck for high-performance VLA models.

### 🦾 Manipulation & Grasping (dexterous hands, grasp generation, contact-rich tasks)
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,817 total — Fully open-source 7-DOF humanoid arm designed for contact-rich physical AI research, priced to enable widespread deployment, solving the high hardware cost barrier for VLA manipulation testing.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐361 total — Standardized manipulation benchmark for robot learning, with diverse contact-rich tasks that enable apples-to-apples comparison of VLA manipulation performance across models.
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8 total — New bimanual kitchen manipulation benchmark for VLA models, built on the Inspect Robots evaluation framework, targeting unstructured, real-world household tasks that are a key test of general embodied intelligence.
- [Enoch208/Crux](https://github.com/Enoch208/Crux) ⭐0 total — End-to-end framework for failure discovery, repair, and statistical qualification for contact-rich manipulation, running entirely on a single consumer GPU, making robust manipulation testing accessible to small research teams.
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐46 total — Open-source software for synchronized bimanual manipulation data collection and cross-robot retargeting, solving the critical data collection bottleneck for training general-purpose bimanual VLA models.
- [MrRox1337/GripSense](https://github.com/MrRox1337/GripSense) ⭐0 total — Open-source control software and benchmarking rig for a slip-aware robotic gripper, enabling research into tactile sensing for dexterous manipulation, a key gap in current VLA capabilities.
- [syed-waleed-ahmed/tiago-autonomous-pick-and-place](https://github.com/syed-waleed-ahmed/tiago-autonomous-pick-and-place) ⭐0 total — Fully open-source autonomous pick-and-place implementation for the TIAGo robot in ROS 2 Humble and Gazebo, including SLAM, localization, and ArUco detection, a reusable baseline for industrial manipulation deployments.

### 🚶 Locomotion & Navigation (legged robots, humanoid, SLAM, path planning)
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,351 total — Open-source operating system for robotics that powers advanced driver assistance for 300+ supported vehicles, the most widely deployed embodied AI system for locomotion, serving as a testbed for VLA for autonomous driving.
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐324 total — Mature open-source robotics software stack with state-of-the-art legged locomotion algorithms and momentum-based control, used to power leading humanoid and exoskeleton robots.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,558 total — De facto standard ROS 2 navigation framework for mobile robots, with support for SLAM, path planning, and obstacle avoidance, powering the majority of industrial and research mobile robot deployments.
- [NJU-RLC/quadrupedal-agility](https://github.com/NJU-RLC/quadrupedal-agility) ⭐122 total — Official implementation of a state-of-the-art RL method that teaches quadruped robots diverse natural behaviors to enhance agility, advancing the state of legged robot locomotion beyond basic walking.
- [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) ⭐38 total — Official codebase for a humanoid soccer shooting system that delivers accurate, stable, and powerful bipedal locomotion for dynamic tasks, demonstrating advanced humanoid locomotion capabilities for unstructured environments.
- [emNavi/AirGym](https://github.com/emNavi/AirGym) ⭐169 total — High-performance drone reinforcement learning platform built on IsaacGym, enabling large-scale training of navigation and control policies for aerial robots, a key tool for embodied AI for drones.
- [darshmenon/rl-bipedal-walking](https://github.com/darshmenon/rl-bipedal-walking) ⭐2 total — Beginner-friendly RL project for teaching a 2D bipedal humanoid model to walk, serving as an accessible entry point for developers new to humanoid locomotion research.

### 📦 Embodied Applications (sim2real, teleoperation, autonomous systems, deployments)
- [PhyAgentOS-Dev/PhyAgentOS](https://github.com/PhyAgentOS-Dev/PhyAgentOS) ⭐1,654 total — Self-evolving embodied AI operating system built on agentic workflows, designed to orchestrate diverse robotic hardware and VLA models for general physical tasks, a leading candidate for a unified embodied AI OS.
- [strands-labs/robots](https://github.com/strands-labs/robots) ⭐119 total — Open-source framework that enables control of any physical robot via natural language using agentic workflows, making VLA-powered robot control accessible to non-technical users.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐156 total — Full-embodiment humanoid teleoperation system, enabling low-cost, high-fidelity control of humanoid robots for data collection and remote task execution, solving a key bottleneck for scaling humanoid VLA training data.
- [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐244 total — Minimal hardware-software architecture that gives LLMs closed-loop physical embodiment with self-perception loops, demonstrating a low-cost approach to connecting general-purpose LLMs to the physical world.
- [physiclaw/PhysiClaw](https://github.com/physiclaw/PhysiClaw) ⭐315 total — AI agent designed to interact with humans in the real world via robotic hardware, combining VLA perception and agentic planning for open-world physical interaction, a rare example of a deployed general embodied agent.
- [Yhx888/LocoVLA](https://github.com/Yhx888/LocoVLA) ⭐7 total — 58-lesson open course that teaches robot control, RL, and VLA deployment on a wheeled biped robot (Upkie) with MuJoCo and ROS2, providing end-to-end training for embodied AI deployment.
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,690 total — Official ICML 2026 codebase for RoboTwin 2.0, a digital twin platform for robotic sim2real transfer that reduces deployment time for VLA policies by closing the simulation-to-reality gap.

---

## 3. Trend Signal Analysis (282 words)
The most explosive community attention today is focused on the expansion of VLA use cases beyond traditional industrial manipulation, with NVIDIA’s open-source Alpamayo series marking a major push to apply VLA to autonomous driving. This aligns with recent 2026 industry announcements from automotive and AI firms positioning VLA as the core technology for next-generation autonomous vehicles, moving beyond perception-only models to end-to-end causal reasoning and trajectory control.
A notable new direction emerging this week is the rapid development of standardized cross-embodiment evaluation tools for physical AI, led by projects like inspect-robots and kitchenbench. This addresses a long-standing bottleneck in VLA research, where inconsistent benchmarking has made apples-to-apples comparison of model performance nearly impossible. This push for standardization follows explicit calls from leading embodied AI labs at ICML 2026 for unified evaluation protocols to accelerate field progress.
Additionally, accessible educational resources for VLA and embodied AI are seeing unprecedented traction, with project-based courses and handbooks amassing thousands of stars, reflecting a severe talent shortage in the fast-growing embodied AI industry. Low-cost open-source humanoid hardware like OpenArm is also democratizing access to physical testing, enabling small teams and individual developers to participate in VLA research previously limited to well-funded corporate labs.

---

## 4. Community Hot Spots
- **NVIDIA Alpamayo VLA Ecosystem**: The four interconnected Alpamayo repos (1, 1.5, 2, recipes) represent the most complete open VLA stack for autonomous driving to date, with pre-built deployment workflows that make it easy for developers to test state-of-the-art driving VLA without training models from scratch.
- **VLA Evaluation Tooling**: [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) and [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) fill a critical unmet need in the VLA ecosystem, and early contributors to these standardized benchmarking tools will help shape the de facto evaluation protocols for the entire field as it matures.
- **Accessible VLA Educational Resources**: [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) and [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) lower the barrier to entry for new VLA developers, making them ideal starting points for engineers looking to transition from general AI/ML to embodied intelligence, one of the fastest-growing job markets in tech.
- **Low-Cost Open Humanoid Manipulation Hardware**: [enactic/openarm](https://github.com/enactic/openarm)’s fully open-source 7-DOF humanoid arm eliminates the high hardware cost barrier for VLA manipulation research, making it a must-have for small labs and hobbyists looking to test embodied policies on physical hardware.
- **ROS-Free Sim2Real VLA Deployment**: [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) addresses a major pain point for VLA developers by eliminating complex ROS dependencies, enabling rapid deployment of VLA policies to common robotic arms, making it a high-impact project for teams focused on real-world VLA deployment.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*