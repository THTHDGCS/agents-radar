# AI Open Source Trends 2026-08-19

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-19 00:34 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report (2026-08-19)

---

## 1. Today's Highlights
No embodied AI, VLA, or robotics projects broke into the general GitHub top 13 trending list on 2026-08-19, with mainstream attention focused on general AI agent tools and video generation workflows. However, topic-tagged active repositories (updated in the last 7 days) reveal accelerating, targeted development across VLA tooling, humanoid control stacks, and embodied AI-specific infrastructure. The VLA ecosystem is expanding beyond core model development to include dedicated finetuning, evaluation, and safety tools, addressing critical gaps for real-world deployment. Humanoid robotics continues to mature as an open-source ecosystem, with new open hardware, whole-body control foundation models, and deployment-ready policy ports lowering barriers for researchers and commercial teams. A growing cohort of embodied AI-native operating systems and runtime systems is also emerging, signaling a shift from legacy robotics middleware to AI-first design paradigms.

---

## 2. Top Projects by Category
*Note: Today's new star counts are only available for the general GitHub trending list, which contained no relevant embodied AI/robotics projects. All star counts below are total repository stars as of the 2026-08-19 snapshot.*

### 🤖 Robot Frameworks / SDKs
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — ⭐7,914 total  
   A unified robot learning framework built on NVIDIA Isaac Sim, it has become a de facto standard for simulation-based VLA and manipulation research, with ongoing updates supporting new humanoid and dexterous hand assets.
2. [dora-rs/dora](https://github.com/dora-rs/dora) — ⭐3,884 total  
   A Rust-based dataflow-oriented robotic middleware designed for low-latency, composable AI robotic applications, it is gaining traction as an alternative to ROS for AI-native robot stacks.
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) — ⭐14,589 total  
   The industry-standard multi-joint physics simulator for robotics, it remains the foundation for most simulation-based robot learning and VLA research, with recent improvements for contact-rich manipulation.
4. [RLinf/RLinf](https://github.com/RLinf/RLinf) — ⭐4,569 total  
   A reinforcement learning infrastructure platform built specifically for embodied and agentic AI, it streamlines RL pipeline development for VLA and locomotion policies.
5. [softmata/horus](https://github.com/softmata/horus) — ⭐416 total  
   A Rust-based high-performance robotics runtime system positioned as an "Android for robots", it targets the need for low-latency, real-time control in AI-powered humanoid and manipulation systems.
6. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) — ⭐30,319 total  
   A comprehensive collection of Python sample codes and textbook materials for robotics algorithms, it remains the most popular learning resource for foundational robot control, planning, and perception.

### 🧠 VLA / Foundation Models
1. [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) — ⭐218 total  
   The official implementation of BridgeVLA and BridgeVLA++, a widely cited general-purpose VLA model, it serves as a baseline for most new VLA research and deployment projects.
2. [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) — ⭐78 total  
   An RSS 2026 work introducing universal pose pretraining for generalizable VLA policies, it addresses a key limitation of current VLA models by improving spatial reasoning for manipulation tasks.
3. [dwipddalal/Anchor-Align](https://github.com/dwipddalal/Anchor-Align) — ⭐23 total  
   A novel VLA finetuning method using representation anchoring and language-action alignment, it enables more efficient generalization of base VLA models to new robot platforms and tasks.
4. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) — ⭐629 total  
   A foundation model for whole-body humanoid control from Horizon Robotics, it represents the growing industry focus on building unified motion models for humanoid robots.
5. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) — ⭐3,234 total  
   A hands-on tutorial series for building VLA models (including OpenVLA, SmolVLA, and Pi0) from scratch with only Python basics, it has become a top learning resource for new VLA developers.
6. [xiaomi-research/recogdrive](https://github.com/xiaomi-research/recogdrive) — ⭐586 total  
   An ICLR 2026 paper implementation of ReCogDrive, a reinforced cognitive framework for end-to-end autonomous driving, it demonstrates the expansion of VLA paradigms to the autonomous driving domain.
7. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) — ⭐520 total  
   A comprehensive Chinese-language, practice-oriented learning and interview handbook for VLA engineers, it reflects the rapidly growing talent demand in the VLA and embodied AI field.

### 🦾 Manipulation & Grasping
1. [enactic/openarm](https://github.com/enactic/openarm) — ⭐2,862 total  
   A fully open-source humanoid arm designed for contact-rich physical AI research and deployment, it has become a popular hardware platform for dexterous manipulation and VLA testing due to its open design and low cost.
2. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) — ⭐46 total  
   Open-source software for the HandUMI bimanual data collection system, it enables synchronized bimanual teleoperation and data retargeting to any dual-arm robot, addressing the critical need for high-quality bimanual manipulation datasets.
3. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) — ⭐24 total  
   A deployment-focused fork of OpenPI for the LimX TRON2 manipulator, it includes pi0.5 policy serving, task fine-tuning, and real-robot client examples, accelerating the deployment of general manipulation policies on commercial hardware.
4. [chang-xinhai/Awesome-Dexterous-Manipulation](https://github.com/chang-xinhai/Awesome-Dexterous-Manipulation) — ⭐14 total  
   A curated list of dexterous manipulation research, including tactile sensing, dexterous hands, datasets, and simulators, it provides a valuable entry point for researchers new to the field.
5. [adsade5/so101-visual-tactile-grasp](https://github.com/adsade5/so101-visual-tactile-grasp) — ⭐1 total  
   A ROS2-based visual-tactile grasping system for the SO-101 robot arm with FlexiTac tactile feedback, it represents the growing focus on multimodal sensing for robust real-world grasping.
6. [codeofwhite/awesome-deformable-manipulation](https://github.com/codeofwhite/awesome-deformable-manipulation) — ⭐1 total  
   A curated resource list for deformable object manipulation in embodied AI, it highlights an emerging niche of manipulation research critical for real-world household and industrial tasks.

### 🚶 Locomotion & Navigation
1. [commaai/openpilot](https://github.com/commaai/openpilot) — ⭐63,447 total  
   An open-source robotics OS that upgrades driver assistance systems on 300+ car models, it is the most widely deployed autonomous navigation system in the open-source community, demonstrating the scaling of embodied AI in the automotive domain.
2. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) — ⭐15,707 total  
   The leading open-source autopilot software for drones, rovers, and submersibles, it remains the foundation for most open-source mobile robot navigation and control projects.
3. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) — ⭐325 total  
   A mature robotics software stack featuring legged locomotion algorithms and momentum-based control for humanoids, exoskeletons, and legged robots, it is a key reference for state-of-the-art bipedal locomotion.
4. [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) — ⭐5,191 total  
   An open-source quadruped robot pet framework for Boston Dynamics-style four-legged robots, it is a popular educational and research platform for legged locomotion and small-scale embodied AI.
5. [limxdynamics/humanoid-description](https://github.com/limxdynamics/humanoid-description) — ⭐13 total  
   Open-source RDF, MuJoCo MJCF, and USD models for LimX humanoid robots (HU_D03, HU_D04) with gripper and dexterous hand variants, it lowers the barrier to simulation-based humanoid locomotion and manipulation research.
6. [zhouyikaiii/DDC](https://github.com/zhouyikaiii/DDC) — ⭐3 total  
   A deployable dynamic-CoM sim2sim benchmark for humanoid single-leg stance that validates on real Unitree G1 robots, it addresses the need for standardized benchmarks to evaluate sim-to-real transfer of humanoid locomotion policies.

### 📦 Embodied Applications
1. [PhyAgentOS-dev/PhyAgentOS](https://github.com/PhyAgentOS-dev/PhyAgentOS) — ⭐1,723 total  
   A self-evolving embodied AI operating system built on agentic workflows, it represents a new paradigm of AI-native robot OS that can autonomously improve its capabilities through interaction with the physical world.
2. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) — ⭐1,640 total  
   A benchmark platform for accelerating embodied AI research with 1,000 household tasks, it remains one of the most comprehensive evaluation environments for embodied VLA and navigation models.
3. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) — ⭐143 total  
   An open-source evaluation framework for physical AI that enables testing any LLM/VLA on any arm/humanoid across real or simulated benchmarks, it fills a critical gap in standardized VLA evaluation for deployment.
4. [provael/provael](https://github.com/provael/provael) — ⭐5 total  
   A red-teaming tool for open VLA robot policies that evaluates attack success rate in simulation, it is one of the first dedicated tools for testing the adversarial robustness of embodied VLA systems.
5. [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) — ⭐6,672 total  
   An open-source project that upgrades cheap off-the-shelf robotic mowers to RTK GPS-based smart lawn mowers, it is a highly successful example of accessible, real-world embodied automation for consumers.
6. [physiclaw/PhysiClaw](https://github.com/physiclaw/PhysiClaw) — ⭐352 total  
   An AI agent designed for real-world physical interaction, it demonstrates the growing interest in building end-to-end embodied agents that can operate in unstructured real environments.
7. [Octoday-Hub/Embodied-AI](https://github.com/Octoday-Hub/Embodied-AI) — ⭐2,243 total  
   A Chinese-language community hub aggregating embodied AI papers, projects, courses, datasets, and job postings, it reflects the rapid growth of the embodied AI developer ecosystem in China and globally.

---

## 3. Trend Signal Analysis
The most explosive community attention in embodied AI right now is centered on VLA deployment tooling and infrastructure, as the field shifts from proving model viability to solving real-world deployment gaps. The proliferation of VLA-specific evaluation frameworks (inspect-robots), red-teaming tools (Provael), and finetuning methods (Anchor-Align, PoseVLA) indicates that the ecosystem is maturing beyond base model development to address robustness, generalization, and safety — critical pain points for commercial VLA deployments on physical robots.

A notable new direction is the emergence of embodied AI-native operating systems and runtime systems (PhyAgentOS, RoboNix, Horus), which depart from legacy ROS-centric middleware designed for industrial robotics. These AI-first systems prioritize agentic workflows, real-time multimodal processing, and self-evolution, signaling a fundamental shift in how robotic software stacks are architected for the VLA era.

These trends align with recent industry momentum: 2026 has seen a wave of humanoid robot commercialization announcements from firms like Figure, Agility Robotics, and LimX Dynamics, driving demand for open-source tools that reduce deployment costs and time-to-market. The upcoming ICLR 2026 and recent RSS 2026 conferences have also contributed to a surge in open-source code drops for novel VLA and robot learning methods, accelerating community iteration. (287 words)

---

## 4. Community Hot Spots
- **VLA Evaluation & Adversarial Safety**: Projects like [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) and [provael/provael](https://github.com/provael/provael) address a long-neglected gap in VLA development: standardized, cross-platform evaluation and adversarial robustness testing. As VLA models move from simulation to physical robots, developers focused on safety and deployment readiness will find this area high-impact and under-served.
- **Embodied AI-Native Operating Systems**: [PhyAgentOS-dev/PhyAgentOS](https://github.com/PhyAgentOS-dev/PhyAgentOS) and [syswonder/robonix](https://github.com/syswonder/robonix) represent a nascent but fast-growing shift away from traditional robotics middleware toward AI-first OS designs optimized for agentic decision-making and real-time physical interaction. This direction is ripe for innovation as humanoid and general-purpose robots require more flexible, AI-native software stacks.
- **Open-Source Humanoid Manipulation Ecosystem**: The combination of [enactic/openarm](https://github.com/enactic/openarm) (open hardware) and [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) (deployment-ready VLA policies) is lowering the barrier to entry for dexterous humanoid manipulation research. With the humanoid industry increasingly prioritizing hand dexterity as a key differentiator, contributions to this ecosystem will have direct commercial and research relevance.
- **Efficient VLA Finetuning for Custom Robots**: [dwipddalal/Anchor-Align](https://github.com/dwipddalal/Anchor-Align) and [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) introduce lightweight methods to adapt general VLA models to new robot platforms and tasks without massive dataset collection. This solves a top pain point for robotics teams looking to leverage pre-trained VLA models on custom hardware, making it a high-demand area for applied research.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*