# AI Open Source Trends 2026-08-04

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-04 01:21 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-08-04

---

## 1. Today's Highlights
Today’s embodied AI and robotics ecosystem, represented by 7-day active topic projects (no direct robotics/embodied AI repos appeared in the top 16 daily trending list), is defined by accelerating maturation of VLA (Vision-Language-Action) tooling, growing accessibility of entry-level educational resources, and expanding open-source humanoid development infrastructure. Notably, NVIDIA’s open-source Alpamayo 1 Nano, a 10B parameter reasoning VLA for autonomous vehicles, has emerged as a leading foundation model for embodied navigation, accumulating nearly 2,000 community stars. The ecosystem is also shifting toward standardized validation for physical AI, with new open-source frameworks for VLA evaluation and adversarial red-teaming addressing long-standing gaps in safety and performance benchmarking. Beginner-focused resources, including a zero-to-VLA course that walks developers through building OpenVLA/SmolVLA models from scratch, have amassed thousands of stars, signaling a surge in new developers entering the embodied intelligence space. Humanoid-specific tooling, from joint design simulation to open-source 3D-printable hardware builds, is proliferating, aligned with industry momentum around commercial humanoid deployments.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
(Control, simulation, planning, middleware, and deployment tooling)
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,309 total: An open-source operating system for robotics, currently deployed to upgrade driver assistance systems on over 300 supported consumer vehicles, serving as a leading reference for real-world embodied autonomy stacks.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,428 total: The de facto standard multi-joint physics simulator for robotics research, powering nearly all modern VLA and robot learning simulation workflows with fast, accurate contact dynamics.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,826 total: A unified, NVIDIA Isaac Sim-based framework for robot learning, designed to streamline end-to-end training and deployment of VLA, RL, and classic control policies for a wide range of robot hardware.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,864 total: A Rust-based, dataflow-oriented robotic middleware that delivers low-latency, composable, distributed pipelines for AI-native robotic applications, reducing the overhead of integrating perception, planning, and control stacks.
- [softmata/horus](https://github.com/softmata/horus) ⭐404 total: A high-performance Rust robotics runtime positioned as "Android for robots," providing a standardized abstraction layer to simplify cross-hardware deployment of embodied applications.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐127 total: A lightweight, ROS-free sim-to-real framework purpose-built for VLA and RL agent deployment, with native MuJoCo Gymnasium wrappers for common manipulators (Franka, UR5e, xArm) and the SO101 humanoid.
- [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,240 total: A multimodal robotics data visualization, query, and streaming tool that enables developers to debug and iterate on VLA training pipelines by unifying visual, sensor, and model output data.

---

### 🧠 VLA / Foundation Models
(Vision-language-action models, policy infrastructure, evaluation, and educational resources)
- [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐1,961 total: NVIDIA’s open 10B parameter reasoning VLA model for autonomous vehicles, which pairs driving trajectory outputs with Chain-of-Causation reasoning to improve interpretability and performance for embodied navigation tasks.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,977 total: A beginner-friendly, project-based course that teaches developers to build their own VLA models (including OpenVLA, SmolVLA, and Pi0) from scratch using only basic Python knowledge, democratizing access to embodied AI development.
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,400 total: A modular reinforcement learning infrastructure platform purpose-built for embodied and agentic AI, streamlining the end-to-end pipeline for training, evaluating, and deploying VLA and RL policies.
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐129 total: An open-world foundation model for general-purpose embodied intelligence, designed to generalize across robot hardware and manipulation, navigation, and locomotion tasks.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐123 total: A universal open-source evaluation framework for physical AI, enabling developers to test any LLM or VLA model on any manipulator/humanoid across any real or simulated benchmark, addressing the lack of standardized VLA performance testing.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐466 total: A Chinese-language, practice-oriented learning and interview guide for VLA engineers, focused on robotics-specific challenges distinct from general CV/NLP, including sim2real transfer and contact-rich control.
- [provael/provael](https://github.com/provael/provael) ⭐5 total: A first-of-its-kind open-source red-teaming framework for VLA robot policies, which evaluates adversarial attack success rates on open VLA models in simulation to identify safety vulnerabilities before real-world deployment.

---

### 🦾 Manipulation & Grasping
(Dexterous control, manipulation benchmarks, skill orchestration, and vertical use cases)
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,200 total: A GPU-parallelized robotics manipulation simulator and benchmark suite, enabling large-scale, efficient training and evaluation of VLA policies for contact-rich dexterous manipulation tasks.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐338 total: An official community benchmark for robot manipulation, designed to standardize performance evaluation of VLA and RL policies across a range of common manipulation tasks.
- [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐97 total: A framework that compiles natural language instructions into type-verified robot skill graphs, enabling reliable execution of complex manipulation tasks on both simulators and real robot hardware.
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐9 total: A bimanual kitchen manipulation benchmark for VLA models, built on the Inspect Robots evaluation framework to test real-world domestic task performance.
- [zcy13/cofree-arm](https://github.com/zcy13/cofree-arm) ⭐0 total: A novel no-training desktop manipulation stack that combines multimodal LLMs for semantic reasoning with geometric control for motion planning, eliminating the need for policy fine-tuning and costing just ~$0.2 per task.
- [di-omics/plr-lab-robot](https://github.com/di-omics/plr-lab-robot) ⭐1 total: A simulation-first lab robotics stack for dexterous life science manipulation, integrating PyLabRobot arm control, eye-in-hand vision, and auditable workcell task tracking.

---

### 🚶 Locomotion & Navigation
(Humanoid, legged robots, navigation stacks, and hardware enablement)
- [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,607 total: The leading open-source control stack for autonomous vehicles, supporting planes, copters, rovers, and submersibles, and serving as a foundational navigation framework for mobile robotics.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,547 total: The official ROS 2 navigation framework, providing production-grade path planning, localization, and obstacle avoidance for mobile robots and humanoids.
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐324 total: A state-of-the-art legged locomotion software stack featuring momentum-based control and optimization, used by world-class humanoid, exoskeleton, and legged robot platforms.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐144 total: A full-embodiment humanoid teleoperation system that enables intuitive control of entire humanoid robot bodies for data collection and remote task execution.
- [Justin-Riekehof/zeroth-01-build](https://github.com/Justin-Riekehof/zeroth-01-build) ⭐0 total: A complete build log and software stack for the K-Scale Zeroth-01 open-source 3D-printed humanoid, including Feetech servo control, MuJoCo RL training, and sim2real deployment on a Raspberry Pi 4.
- [YansongW/awesome-humanoid-robot](https://github.com/YansongW/awesome-humanoid-robot) ⭐1 total: A multilingual knowledge graph for humanoid robot mass production, with 2,143 entities and 1,063 relationships mapping the entire humanoid supply chain and technology stack.

---

### 📦 Embodied Applications
(End-to-end deployments, teleoperation, vertical use cases, and prototyping tools)
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,486 total: A self-evolving embodied AI operating system built on agentic workflows, designed to manage skill learning, memory, and task execution for physical robot platforms.
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐44 total: Open-source software for synchronized bimanual data collection and teleoperation, with support for retargeting collected demonstration data to any bimanual robot platform to train VLA policies.
- [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐51 total: A robotics digital twin platform for chemistry lab automation, enabling autonomous operation of lab robots to run experiments with high precision and reproducibility.
- [KaushikSiva/baymax](https://github.com/KaushikSiva/baymax) ⭐0 total: A simulated deployment of a Unitree G1 humanoid for hospital patrol tasks, including navigation, patient speech interaction, fall detection, and vital sign escalation workflows.
- [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐242 total: A minimal, low-cost hardware-software architecture that gives large language models closed-loop physical embodiment with self-perception loops, enabling rapid prototyping of embodied agent systems.
- [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8 total: A VLA-powered autonomous rover agent built on the Strands framework, which controls a FrodoBots Earth Rover Mini+ and includes a public fine-tuning dataset for outdoor embodied navigation.

---

## 3. Trend Signal Analysis
The most explosive community attention in today’s embodied AI ecosystem is centered on VLA tooling and accessibility, as the field shifts from foundational model research to widespread deployment and standardization. The proliferation of evaluation frameworks (`inspect-robots`), red-teaming tools (`provael`), and beginner educational resources (`every-embodied`, `VLA-Handbook`) signals that VLA technology is exiting pure research and entering a maturation phase, with the community prioritizing safety, reproducibility, and onboarding of new developers. A notable new direction is the emergence of ROS-free deployment stacks for VLA, such as `robot-control-stack`, which addresses a long-standing pain point for AI-native developers who lack expertise in traditional robotic middleware. The rapid growth of humanoid-specific tooling—from open hardware builds to joint design simulation and mass production knowledge graphs—directly aligns with recent industry momentum, including Figure AI’s commercial deployment partnerships, Unitree’s low-cost humanoid launches, and increasing manufacturing investment in humanoid actuation supply chains. Additionally, domain-specific embodied applications for lab automation and healthcare are gaining traction, as VLA models demonstrate sufficient reliability to power vertical use cases beyond general research.

---

## 4. Community Hot Spots
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack): This ROS-free VLA deployment framework solves a critical adoption barrier for AI developers unfamiliar with traditional robotic middleware, with native support for the most common manipulator and humanoid hardware. Its lightweight, sim2real-native design positions it as a potential standard for VLA deployment, making it a high-impact area for contributions.
- [provael/provael](https://github.com/provael/provael): As the first open-source VLA red-teaming framework, it addresses a rapidly growing need for embodied AI safety validation as models move to real-world deployment. The project is in its early stages, offering developers the opportunity to shape the emerging field of VLA security testing.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied): With nearly 3,000 stars, this project-based zero-to-VLA course is the fastest-growing educational resource for embodied AI, democratizing access to VLA development for developers with only basic Python skills. It is a key entry point for new developers entering the ecosystem.
- [softmata/horus](https://github.com/softmata/horus): Positioned as a standardized "Android for robots" runtime, Horus addresses the fragmentation of robot hardware platforms by providing a unified abstraction layer for embodied application deployment. Its Rust-based, high-performance design could become a core layer of the embodied AI stack, making it a critical project to monitor.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): This universal VLA evaluation framework is filling a major gap in standardized performance testing for physical AI, with emerging adoption for new benchmarks like `kitchenbench`. Standardized evaluation is a prerequisite for VLA commercialization, making this project a cornerstone of the ecosystem's maturation.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*