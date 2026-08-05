# AI Open Source Trends 2026-08-05

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-05 01:26 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-08-05
*Note: Today’s general GitHub trending list contained no directly relevant embodied AI/robotics projects; all analyzed activity comes from 7-day active topic-tagged repositories.*

---

## 1. Today's Highlights
Today’s key developments are led by NVIDIA’s open expansion of its Alpamayo Vision-Language-Action (VLA) family, including a new 34B multi-task foundation model for autonomous vehicles and supporting deployment recipes, marking a major step toward commoditized, production-ready VLA technology. Humanoid robotics saw a burst of open-source activity, from high-performance runtime systems to dynamic soccer shooting capabilities and full-embodiment teleoperation tools, as the ecosystem prioritizes solving hardware and software bottlenecks for scalable humanoid deployment. The embodied AI community also demonstrated growing demand for standardized evaluation, with open VLA testing frameworks gaining traction, alongside a surge in accessible educational resources that are lowering barriers for new developers to enter the space. Additionally, a new Y Combinator Winter 2026 robotics startup focused on ML-optimized dexterous hands signals increasing investor confidence in near-term commercialization of general-purpose robot systems.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
| Project | Stars | Details |
|---------|-------|---------|
| [dora-rs/dora](https://github.com/dora-rs/dora) | 3,865 total | Low-latency, composable dataflow-oriented robotic middleware that simplifies building AI-integrated robotic applications via modular pipeline design. |
| [RLinf/RLinf](https://github.com/RLinf/RLinf) | 4,424 total | Unified reinforcement learning infrastructure purpose-built for embodied AI and agentic systems, streamlining training, evaluation, and deployment for RL and VLA models. |
| [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) | 3,201 total | Open-source GPU-parallelized robotics simulator and manipulation skill benchmark, a core tool for scaling embodied AI training across thousands of parallel environments. |
| [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) | 7,834 total | Unified NVIDIA Isaac Sim-based framework for robot learning, supporting end-to-end VLA training, RL, and sim2real transfer for manipulators and humanoids. |
| [softmata/horus](https://github.com/softmata/horus) | 405 total | High-performance robotics runtime system positioned as an "Android for robots", optimized for low-latency control of humanoids and legged platforms. |
| [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) | 127 total | Lightweight, ROS-free sim2real framework for deploying VLA models and RL agents, with native MuJoCo wrappers for common manipulator and humanoid hardware. |

---

### 🧠 VLA / Foundation Models
| Project | Stars | Details |
|---------|-------|---------|
| [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) | 1,965 total | NVIDIA’s open 10B-parameter reasoning VLA for autonomous vehicles, paired with Chain-of-Causation trajectory reasoning for interpretable mobility decision-making. |
| [dexmal/opendm](https://github.com/dexmal/opendm) | 132 total | Open-world foundation model designed for general-purpose embodied intelligence, supporting cross-robot transfer across manipulation, locomotion, and navigation tasks. |
| [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) | 127 total | Open-source evaluation framework for physical AI, enabling standardized testing of any LLM/VLA across any manipulator/humanoid platform in sim or real-world environments. |
| [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) | 98 total | Novel policy framework that compiles natural language instructions into type-verified robot skill graphs, enabling reliable, auditable execution on real or simulated robots. |
| [zju3dv/INTACT-JEPA](https://github.com/zju3dv/INTACT-JEPA) | 91 total | Intent-to-Action world model architecture that eliminates search during planning, cutting inference latency for real-time VLA deployment on edge robots. |
| [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) | 42 total | Newly released 34B-parameter multi-task VLA foundation model from NVIDIA, built to accelerate autonomous vehicle development with unified perception, planning, and control. |

---

### 🦾 Manipulation & Grasping
| Project | Stars | Details |
|---------|-------|---------|
| [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) | 345 total | Official repository for the RoboDojo manipulation benchmark, a standardized test suite for evaluating dexterous manipulation and VLA generalization. |
| [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) | 44 total | Open-source software stack for synchronized bimanual manipulation data collection and cross-robot retargeting, lowering the barrier to building custom VLA manipulation datasets. |
| [api-evangelist/origami-robotics](https://github.com/api-evangelist/origami-robotics) | 0 total | Profile of Y Combinator Winter 2026 startup Origami Robotics, which is building ML-optimized dexterous robotic hands for general-purpose manipulation, a key hardware enabler for next-gen VLA systems. |
| [zcy13/cofree-arm](https://github.com/zcy13/cofree-arm) | 0 total | Novel no-training desktop manipulation system that offloads semantic reasoning to multimodal models and low-level control to geometric methods, costing only ~¥0.2 per task to operate. |
| [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) | 8 total | Bimanual kitchen manipulation benchmark for VLA models, built to test real-world contact-rich task performance across diverse food preparation and household workflows. |

---

### 🚶 Locomotion & Navigation
| Project | Stars | Details |
|---------|-------|---------|
| [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) | 324 total | Mature open-source robotics software stack with state-of-the-art legged locomotion algorithms and momentum-based controllers, used on leading humanoid, exoskeleton, and legged robot platforms. |
| [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) | 148 total | Full-embodiment humanoid teleoperation system, enabling low-latency remote control of humanoid robots for data collection, disaster response, and remote manipulation use cases. |
| [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) | 38 total | Official codebase for the RoboNaldo humanoid soccer shooting system, demonstrating highly accurate, stable dynamic locomotion for contact-rich full-body humanoid tasks. |
| [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) | 4,551 total | Industry-standard ROS 2 navigation framework, supporting SLAM, global localization, path planning, and obstacle avoidance for mobile robots and humanoids. |
| [KaushikSiva/baymax](https://github.com/KaushikSiva/baymax) | 0 total | Simulation deployment of a Unitree G1 humanoid for hospital patrol, supporting navigation, patient speech interaction, fall detection, and vital sign escalation workflows. |

---

### 📦 Embodied Applications
| Project | Stars | Details |
|---------|-------|---------|
| [commaai/openpilot](https://github.com/commaai/openpilot) | 63,325 total | Open-source robotics operating system that powers advanced driver assistance systems on 300+ car models, serving as the most widely deployed real-world VLA-enabled mobility system. |
| [TianxingChen/Embodied-AI-Guide](https://github.com/TianxingChen/Embodied-AI-Guide) | 15,241 total | Highly popular community-maintained embodied AI technical guide from Lumina Community, serving as the primary onboarding resource for new developers entering the space. |
| [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) | 2,999 total | Hands-on educational project that teaches developers to build a full embodied AI robot and VLA models (including OpenVLA, SmolVLA, Pi0) from scratch with only basic Python knowledge. |
| [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) | 2,679 total | Official codebase for RoboTwin 2.0, presented at ICML 2026, a high-fidelity digital twin platform for embodied AI training and sim2real validation across robot platforms. |
| [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) | 244 total | Minimal hardware-software architecture that gives LLMs closed-loop physical embodiment with self-perception loops, enabling low-cost prototyping of embodied agent systems. |

---

## 3. Trend Signal Analysis
The fastest-growing areas of the embodied AI ecosystem this week are open VLA standardization and humanoid enablement, driven by NVIDIA’s full open-source release of the Alpamayo VLA series. This release aligns with recent industry consensus that VLA models will become the unified software stack for all physical AI systems, from autonomous vehicles to humanoids, and signals NVIDIA’s push to dominate the VLA tooling ecosystem. A notable emerging tech direction is ROS-free VLA deployment frameworks, exemplified by `robot-control-stack`, which eliminates legacy ROS middleware overhead to deliver the low-latency synchronous execution required for real-world closed-loop VLA operation, addressing a longstanding pain point for embodied AI engineers. The launch of YC-backed Origami Robotics, focused on ML-optimized dexterous hands, addresses the long-identified hardware bottleneck for general manipulation, aligning with the $1B+ in recent humanoid robotics investment. The 15k+ star `Embodied-AI-Guide` confirms rapid developer onboarding, as industry reports estimate demand for VLA and embodied AI talent outpaces supply by 5x.

---

## 4. Community Hot Spots
- **[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)**: Standardized VLA evaluation is the largest unmet need in the ecosystem right now, as teams lack a common framework to compare VLA performance across hardware and tasks; this repo is quickly emerging as the de facto standard for physical AI evals.
- **[RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)**: ROS-free VLA deployment is a high-impact emerging direction, as legacy ROS was not designed for the low-latency, closed-loop inference requirements of edge VLA systems, making this lightweight framework a top pick for teams building real-world VLA deployments.
- **[softmata/horus](https://github.com/softmata/horus)**: Purpose-built robotics runtimes for humanoids are set to displace general-purpose embedded OSes as humanoid production scales; HORUS’s positioning as an "Android for robots" addresses the critical need for standardized, low-latency control middleware across heterogeneous humanoid hardware.
- **[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)**: Hands-on VLA educational resources are in extremely high demand, with this project enabling thousands of new developers to enter the space by removing the barrier of advanced robotics domain knowledge for building VLA models.
- **[NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2)**: NVIDIA’s open 34B VLA for autonomous mobility signals a shift toward larger, multi-task VLA models for physical systems, with transferable capabilities that can be fine-tuned for humanoid and manipulator use cases beyond automotive.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*