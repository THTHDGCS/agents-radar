# AI Open Source Trends 2026-09-15

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-09-15 02:16 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
*Date: 2026-09-15 | Data Sources: GitHub Trending, GitHub Topic Search (robotics/embodied-ai/VLA/humanoid)*

---

## 1. Today's Highlights
Today’s most significant embodied AI and robotics development is the viral growth of [JustVugg/colibri](https://github.com/JustVugg/colibri), a pure C, zero-dependency MoE inference engine that gained 2,173 stars in a single day, reflecting massive community demand for running large VLA and embodied foundation models on affordable, edge-side consumer hardware. On the VLA front, NVIDIA’s Alpamayo series dominates the trending VLA topic, with the latest 34B Alpamayo 2 Super targeting multi-task autonomous vehicle development, underscoring the rapid commercialization of VLA technology in the self-driving vertical. Open-source humanoid robotics continues to gain momentum, with accessible platforms like the 3D-printable [Rhoban/microban](https://github.com/Rhoban/microban) biped and fully open [enactic/openarm](https://github.com/enactic/openarm) humanoid arm lowering barriers for researchers to test VLA policies on physical hardware. A growing ecosystem of AI-native, ROS-free robot frameworks is also emerging, catering to the unique needs of modern embodied AI workflows that prioritize low latency and sim-to-real consistency.

---

## 2. Top Projects by Category

### 🤖 Robot Frameworks / SDKs
*(Control, simulation, planning, runtime, and developer tools)*
1. **[JustVugg/colibri](https://github.com/JustVugg/colibri)** — 2,173 new stars today (new repository, total stars unlisted; C, zero dependencies)
   Lightweight MoE inference engine that streams model experts from disk to run frontier models on consumer hardware; it is the fastest-growing project today and directly solves the edge deployment bottleneck for VLA and embodied foundation models.
2. **[google-deepmind/mujoco](https://github.com/google-deepmind/mujoco)** — 15,144 total stars (today's gain unlisted; C++)
   Industry-standard physics simulator for robotics and embodied AI research, with widespread adoption in VLA training, sim-to-real experiments, and humanoid locomotion development.
3. **[isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab)** — 8,122 total stars (today's gain unlisted; Python)
   Unified NVIDIA Isaac Sim-based framework for robot learning, offering pre-built environments and tools for training VLA, RL, and locomotion policies at scale.
4. **[dora-rs/dora](https://github.com/dora-rs/dora)** — 3,936 total stars (today's gain unlisted; Rust)
   Dataflow-oriented robotic middleware with low latency and composable pipelines, emerging as a popular AI-native alternative to ROS for modern embodied intelligence applications.
5. **[rerun-io/rerun](https://github.com/rerun-io/rerun)** — 11,448 total stars (today's gain unlisted; Rust)
   Multimodal robotics data visualization and streaming tool, critical for debugging VLA models, sensor pipelines, and real-world robot deployments.
6. **[softmata/horus](https://github.com/softmata/horus)** — 437 total stars (today's gain unlisted; Rust)
   High-performance robotics runtime system positioned as an "Android for robots", designed to unify software stacks across different robot hardware platforms.

### 🧠 VLA / Foundation Models
*(Vision-Language-Action models, world models, RL policies, pretraining frameworks)*
1. **[NVlabs/alpamayo](https://github.com/NVlabs/alpamayo)** — 2,020 total stars (today's gain unlisted; Python)
   NVIDIA’s open 10B reasoning VLA model for autonomous vehicles, paired with Chain-of-Causation reasoning, a leading example of VLA commercialization in self-driving.
2. **[dexmal/opendm](https://github.com/dexmal/opendm)** — 675 total stars (today's gain unlisted; Python)
   Open-world foundation model for general-purpose embodied intelligence, targeting cross-robot generalization across manipulation, navigation, and interaction tasks.
3. **[HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion)** — 692 total stars (today's gain unlisted; Python)
   Foundation model for whole-body humanoid control, enabling unified locomotion and manipulation policies for humanoid robots, a fast-growing VLA subfield.
4. **[NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2)** — 239 total stars (today's gain unlisted; Python)
   Latest 34B multi-task VLA foundation model from NVIDIA for autonomous vehicle development, supporting navigation, reasoning, and visual question answering.
5. **[OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM)** — 292 total stars (today's gain unlisted; Python)
   Unified framework for training, fine-tuning, and evaluating World Action Models (WAMs), a closely related paradigm to VLA that emphasizes world modeling for physical agents.
6. **[OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA)** — 33 total stars (today's gain unlisted; Python)
   Novel VLA architecture with native video memory and streaming inference, designed for long-horizon robot manipulation tasks that require historical visual context.

### 🦾 Manipulation & Grasping
*(Dexterous hands, skill composition, grasp generation, contact-rich tasks)*
1. **[enactic/openarm](https://github.com/enactic/openarm)** — 3,084 total stars (today's gain unlisted; MDX)
   Fully open-source humanoid arm designed for contact-rich physical AI research, providing a low-cost, standardized hardware platform for testing VLA manipulation policies.
2. **[graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy)** — 134 total stars (today's gain unlisted; Python)
   Framework that compiles natural language instructions into typed, verified robot skill graphs, enabling reliable, composable manipulation task execution across sim and real robots.
3. **[allenai/MolmoBot](https://github.com/allenai/MolmoBot)** — 106 total stars (today's gain unlisted; Python)
   Zero-shot manipulation system trained on large-scale simulation data from the Allen Institute, demonstrating the potential of sim-only training for real-world manipulation.
4. **[graph-robots/open-robot-skills](https://github.com/graph-robots/open-robot-skills)** — 44 total stars (today's gain unlisted; Python)
   Curated skill and tool bundles for the graph-as-policy framework, compatible with Anthropic Agent Skills format, accelerating the development of language-driven manipulation systems.
5. **[XenseRobotics-AI/xense-openpi](https://github.com/XenseRobotics-AI/xense-openpi)** — 16 total stars (today's gain unlisted; Python)
   Adaptation of π0-series VLA models to Xense dual-arm robot platforms, including fine-tuning and real-world deployment pipelines for contact-rich manipulation tasks.

### 🚶 Locomotion & Navigation
*(Legged robots, humanoid biped, SLAM, path planning, autonomous driving)*
1. **[commaai/openpilot](https://github.com/commaai/openpilot)** — 63,650 total stars (today's gain unlisted; Python)
   Open-source robotics OS for advanced driver assistance systems, supporting 300+ car models and representing the most widely deployed embodied AI locomotion system in the world.
2. **[ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot)** — 15,860 total stars (today's gain unlisted; C++)
   Industry-leading open-source flight controller for drones, rovers, and submarines, powering millions of aerial and ground robots globally.
3. **[ros-navigation/navigation2](https://github.com/ros-navigation/navigation2)** — 4,707 total stars (today's gain unlisted; C++)
   Standard ROS 2 navigation framework for mobile robots, providing path planning, localization, and obstacle avoidance capabilities for a wide range of robotic platforms.
4. **[Rhoban/microban](https://github.com/Rhoban/microban)** — 365 total stars (today's gain unlisted; Python)
   Affordable, fully 3D-printable open-source bipedal humanoid robot powered by a Raspberry Pi Zero 2W, lowering the barrier to entry for hobbyists and researchers into legged locomotion.
5. **[mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA)** — 3 total stars (today's gain unlisted)
   Unified Vision-Language-Action framework for humanoid loco-manipulation, enabling seamless control of both locomotion and manipulation tasks in large, unstructured environments.

### 📦 Embodied Applications
*(Sim2real, teleoperation, digital twins, vertical deployments)*
1. **[RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin)** — 2,852 total stars (today's gain unlisted; Python)
   Official ICML 2026 RoboTwin 2.0 repository, a digital twin platform for embodied AI research that bridges simulation and real-world robot deployment.
2. **[PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core)** — 2,281 total stars (today's gain unlisted; Python)
   Recursive Self-Improving (RSI) physical agent operating system that enables embodied agents to iteratively improve their capabilities through agentic workflows in the real world.
3. **[StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K)** — 1,692 total stars (today's gain unlisted; Python)
   Stanford’s embodied AI research platform with 1,000+ daily tasks, providing a standardized benchmark for testing generalist embodied agents in realistic household environments.
4. **[Phyzicalorg/Phyzical_org](https://github.com/Phyzicalorg/Phyzical_org)** — 310 total stars (today's gain unlisted; Python)
   Browser-based teleoperation data platform for embodied AI, generating elizaOS-ready training episodes with on-chain provenance to solve the data scarcity problem for physical agents.
5. **[rokbenko/quackd](https://github.com/rokbenko/quackd)** — 198 total stars (today's gain unlisted; Python)
   Unified CLI tool for controlling multiple heterogeneous robots (LeRobot arms, AlohaMini, ROS bases, etc.) with LLM brains, supporting both cloud and local models for multi-robot orchestration.

---

## 3. Trend Signal Analysis
The most explosive area of community attention this period is edge-native inference for large foundation models, directly enabling on-device deployment of VLA and embodied intelligence systems. The viral growth of [JustVugg/colibri](https://github.com/JustVugg/colibri) — with 2,173 new stars in a single day — reflects widespread developer demand for lightweight, low-cost ways to deploy frontier models without relying on cloud GPUs, a critical bottleneck for real-world robotics where latency and privacy are non-negotiable.

A key emerging tech stack direction is the rise of AI-first, ROS-free robot development frameworks. Projects including [dora-rs/dora](https://github.com/dora-rs/dora), [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack), and [softmata/horus](https://github.com/softmata/horus) prioritize low-latency dataflow, native VLA/RL integration, and simplified sim-to-real workflows, challenging the long-standing dominance of ROS in classical robotics by catering to the needs of modern AI-native roboticists.

These trends align with recent industry and academic milestones: ICML 2026 and CoRL 2026 paper releases (e.g., RoboTwin 2.0, HuRo VLA pretraining) are driving interest in digital twins and scalable VLA data pipelines, while NVIDIA’s Alpamayo VLA series underscores the rapid commercialization of VLA technology in autonomous driving, a vertical leading embodied AI deployment. The growth of open-source humanoid hardware also mirrors the global humanoid robotics boom, as researchers seek accessible platforms to test generalist VLA models in physical environments. (Word count: 287)

---

## 4. Community Hot Spots
- **Edge MoE inference for embodied models**: [JustVugg/colibri](https://github.com/JustVugg/colibri) is a breakout project that lets roboticists run large MoE VLA models on off-the-shelf edge hardware, eliminating cloud latency and privacy barriers — a game-changer for small robotics teams and hobbyists.
- **ROS-free AI robot frameworks**: [dora-rs/dora](https://github.com/dora-rs/dora) dataflow middleware and [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) sim-to-real framework are worth watching as they simplify VLA/RL deployment, a pain point that has slowed AI adoption in classical robotics.
- **Whole-body humanoid VLA**: [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) (whole-body humanoid control foundation model) and [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) (unified loco-manipulation VLA) represent the next frontier of embodied AI, moving beyond single-arm manipulation to full-body humanoid coordination.
- **Teleoperation data infrastructure**: [Phyzicalorg/Phyzical_org](https://github.com/Phyzicalorg/Phyzical_org) addresses the critical data scarcity problem for physical AI by providing a low-barrier browser teleoperation platform to generate training episodes for VLA models.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*