# AI Open Source Trends 2026-08-09

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-09 00:50 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-08-09

---

## 1. Today's Highlights
No robotics or embodied AI projects appeared on today’s global GitHub trending list, with all top daily viral repos focused on general coding agents and developer tools; all key activity is concentrated in 7-day active topic-tagged projects, led by NVIDIA’s full open-source Alpamayo VLA family for autonomous vehicles. Open-source humanoid and manipulation infrastructure is maturing rapidly, with high-adoption projects like the 2.8k-star enactic/openarm and limxdynamics’ TRON2 manipulation tooling prioritizing deployable, contact-rich hardware support for physical AI. Educational resources for VLA and embodied AI are seeing explosive community growth, with the 3k-star datawhalechina/every-embodied zero-to-VLA course and 484-star Chinese VLA Handbook emerging as leading hands-on onboarding paths for new developers. Standardized evaluation for VLA and embodied agents is a growing priority, with new benchmarking tools (RoboDojo, kitchenbench, inspect-robots) launching to address the longstanding lack of cross-hardware, cross-task performance measurement for real-world robots.

---

## 2. Top Projects by Category
(Note: No relevant projects appeared on the daily trending list, so all star counts reflect total GitHub stars as of the report date.)

### 🤖 Robot Frameworks / SDKs
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,483: Reinforcement learning infrastructure purpose-built for embodied and agentic AI, offering a unified pipeline for training and scaling RL policies across simulation and real hardware, making it a top pick for teams building production embodied agents.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,869: Dataflow-oriented robotic middleware with low latency, composable, and distributed capabilities, gaining traction as a ROS alternative for lean, AI-native robotic application development.
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,209: Open-source GPU-parallel robotics simulator and manipulation benchmark, supporting large-scale batch training of RL and VLA policies with high physical fidelity.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,489: Industry-standard multi-joint physics simulator with contact modeling, the de facto foundation for most sim-based robot learning and VLA training workflows today.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,861: Unified robot learning framework built on NVIDIA Isaac Sim, optimized for GPU-accelerated simulation and sim-to-real transfer of VLA and locomotion policies.
- [softmata/horus](https://github.com/softmata/horus) ⭐407: High-performance robotics runtime system positioned as an "Android for robots", designed to standardize low-level control across heterogeneous robot hardware platforms.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐128: ROS-free sim-to-real framework for training and deploying VLA and RL agents, with native MuJoCo integration for common manipulator and humanoid platforms, addressing demand for simplified deployment pipelines.

### 🧠 VLA / Foundation Models
- [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐1,978: NVIDIA’s open 10B-parameter reasoning VLA for autonomous vehicles, pairing driving trajectories with Chain-of-Causation reasoning to enable explainable, production-ready AV decision-making.
- [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐144: 34B-parameter multi-task VLA foundation model for autonomous vehicle development, the largest open VLA purpose-built for AV use cases, with support for navigation, perception, and VQA tasks.
- [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) ⭐211: Official implementation of BridgeVLA and BridgeVLA++, state-of-the-art general-purpose manipulation VLAs that achieve strong cross-dataset transfer across 20+ robot platforms.
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐205: Open-world foundation model for general-purpose embodied intelligence, designed to support cross-embodiment control across manipulators, humanoids, and mobile robots.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,050: Hands-on course that teaches developers to build embodied AI robots from zero, with step-by-step implementations of OpenVLA, SmolVLA, and Pi0 policies for users with only basic Python knowledge.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐484: Full Chinese, practice-oriented learning and interview handbook for VLA engineers, focusing on robotics-specific challenges not covered in general CV/NLP guides.
- [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐2: Early-stage unified VLA framework for humanoid loco-manipulation, addressing the emerging need to combine locomotion and manipulation control into a single end-to-end model for full-body humanoid operation.

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,825: Fully open-source humanoid arm designed for physical AI research and contact-rich manipulation deployment, providing a low-cost, standardized hardware platform for VLA testing that fills a gap left by expensive closed commercial manipulators.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐370: Official implementation of the RoboDojo manipulation benchmark, designed to evaluate VLA and RL policies on diverse, contact-rich manipulation tasks across sim and real hardware.
- [worldbench/awesome-embodied-data-pyramid](https://github.com/worldbench/awesome-embodied-data-pyramid) ⭐141: Comprehensive survey and curated list of resources for the embodied manipulation data pyramid, providing a structured overview of datasets, policies, and evaluation protocols for manipulation researchers.
- [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐15: Deployment-focused fork of OpenPI for LimX Dynamics’ TRON2 manipulator, including policy serving, fine-tuning, and real-robot client examples to simplify VLA deployment on commercial hardware.
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8: New bimanual kitchen manipulation benchmark for VLA models, built on the Inspect Robots evaluation framework to enable standardized testing of long-horizon, contact-rich household tasks.
- [Enoch208/Crux](https://github.com/Enoch208/Crux) ⭐0: End-to-end pipeline for failure discovery, repair, and statistical qualification for contact-rich manipulation, running on a single consumer GPU and generating verifiable evidence bundles for policy reliability.
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐46: Open-source software for synchronized bimanual manipulation data collection and retargeting, supporting calibration, teleoperation, and replay across any bimanual robot platform.

### 🚶 Locomotion & Navigation
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,369: Open-source robotics operating system that upgrades driver assistance systems on 300+ supported cars, the most widely deployed embodied AI system for autonomous navigation in consumer use.
- [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) ⭐5,071: Open-source quadruped robot framework for developing Boston Dynamics-style four-legged robots, a popular platform for STEM education and hobbyist locomotion research.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,562: Official ROS 2 navigation framework, the industry standard for path planning and navigation in mobile robots across industrial and research use cases.
- [NJU-RLC/quadrupedal-agility](https://github.com/NJU-RLC/quadrupedal-agility) ⭐122: Official implementation of ICML 2026 work on learning diverse natural behaviors to enhance quadruped robot agility, pushing the boundaries of legged locomotion performance.
- [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) ⭐38: Official codebase for RoboNaldo, a humanoid soccer shooting policy that achieves high accuracy and stability, demonstrating progress in dynamic full-body humanoid locomotion and manipulation.
- [Yhx888/LocoVLA](https://github.com/Yhx888/LocoVLA) ⭐8: 58-lesson open course for learning robot control, RL, and VLA on a wheeled biped robot, combining classical control, state estimation, and VLA deployment for legged robotics.
- [emNavi/AirGym](https://github.com/emNavi/AirGym) ⭐169: High-performance drone deep reinforcement learning platform built on IsaacGym, enabling large-scale training of navigation and control policies for autonomous aerial robots.

### 📦 Embodied Applications
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,702: Official code for ICML 2026’s RoboTwin 2.0 digital twin platform, enabling high-fidelity sim-to-real transfer for robot learning and VLA training across diverse embodiments.
- [PhyAgentOS-Dev/PhyAgentOS](https://github.com/PhyAgentOS-Dev/PhyAgentOS) ⭐1,709: Self-evolving embodied AI operating system built on agentic workflows, designed to support long-running autonomous tasks across physical and simulated robot platforms.
- [Octoday-Hub/Embodied-AI](https://github.com/Octoday-Hub/Embodied-AI) ⭐2,272: Chinese embodied AI ecosystem hub that aggregates papers, projects, courses, datasets, and job listings, connecting global researchers, developers, and industry partners.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐131: Open-source evaluation framework for physical AI, allowing users to run any LLM/VLA on any manipulator or humanoid across sim or real hardware, addressing the lack of standardized VLA testing tools.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐157: Full-embodiment humanoid teleoperation system, enabling low-latency control of humanoid robots for data collection and remote task execution.
- [syswonder/robonix](https://github.com/syswonder/robonix) ⭐314: Open-source Embodied AI Operating System (EAIOS) designed to standardize system-level software for heterogeneous robot hardware, similar to Android for mobile devices.
- [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐52: Digital twin platform for robotics-assisted chemistry lab automation, demonstrating the expansion of embodied AI into vertical industrial use cases beyond consumer and automotive applications.

---

## 3. Trend Signal Analysis
The most explosive community attention today is focused on accessible VLA education and domain-specific VLA development for production use cases. The 3k-star datawhalechina/every-embodied course and 484-star VLA Handbook indicate a massive influx of new developers entering the embodied AI space, driven by growing industry demand for VLA engineers. NVIDIA’s full Alpamayo VLA family, purpose-built for autonomous vehicles rather than general lab manipulation, signals a key shift: VLA technology is moving beyond academic benchmarks to domain-specific production deployments, with optimized model sizes (10B to 34B) and dedicated deployment tooling. A notable emerging tech stack is ROS-free robotic middleware, with projects like dora-rs and robot-control-stack gaining traction as teams prioritize lean, GPU-native workflows to reduce latency and simplify sim-to-real transfer for VLA agents, moving away from the overhead of traditional ROS ecosystems. This activity aligns with recent industry and academic milestones: the recent ICML 2026 conference has driven a wave of new paper code releases (including RoboTwin 2.0 and quadrupedal agility work), while surging investment in humanoid robotics is accelerating the development of open hardware (openarm) and standardized evaluation tools to support widespread VLA testing.

---

## 4. Community Hot Spots
- **NVIDIA Alpamayo VLA Ecosystem**: The full open-source stack of 10B to 34B parameter VLAs for autonomous vehicles, paired with deployment recipes for fine-tuning and quantization, provides the first production-ready, domain-specific VLA foundation for AV developers, filling a gap left by general-purpose VLAs that underperform on driving tasks.
- **datawhalechina/every-embodied**: This 3k-star hands-on course is the most accessible onboarding path for new embodied AI developers, with step-by-step implementations of state-of-the-art VLA models (OpenVLA, Pi0) that require only basic Python knowledge, lowering the barrier to entry for a fast-growing field.
- **enactic/openarm**: The 2.8k-star fully open-source humanoid arm addresses the critical bottleneck of expensive, closed manipulation hardware for physical AI research, enabling low-cost, standardized testing of contact-rich VLA policies for academic and hobbyist teams.
- **ROS-free deployment frameworks (dora-rs, robot-control-stack)**: These lean, GPU-native middleware tools are emerging as a viable alternative to traditional ROS for VLA deployments, reducing latency and simplifying sim-to-real transfer for edge robotics use cases, with growing adoption among teams building production embodied agents.
- **VLA evaluation tooling (robocurve/inspect-robots + kitchenbench)**: This paired evaluation framework and bimanual benchmark solves the longstanding lack of standardized, cross-hardware VLA testing tools, allowing researchers to directly compare model performance across sim and real robots to drive meaningful progress in embodied AI.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*