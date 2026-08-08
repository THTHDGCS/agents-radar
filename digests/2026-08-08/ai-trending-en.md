# AI Open Source Trends 2026-08-08

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-08 00:46 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-08-08

---

## 1. Today's Highlights
Today’s GitHub embodied intelligence and robotics ecosystem is led by NVIDIA’s open VLA roadmap for autonomous driving, with four interconnected Alpamayo model and developer tool repositories active in the past 7 days. Commercial humanoid vendor LimX Dynamics has released a full open-source stack of simulation, modeling, and VLA deployment tools for its humanoid and robotic arm product lines, marking a rare shift from closed proprietary hardware tooling to open ecosystem development. End-to-end VLA deployment accessibility is emerging as a key community priority, with new ROS-free frameworks gaining rapid traction among researchers frustrated by legacy robotics middleware overhead. General agent skill frameworks, which dominated the broader GitHub trending list today, are also explicitly crossing over to embodied use cases, with new tooling for CAD automation and physical agent workflows.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
- [commaai/openpilot](https://github.com/commaai/openpilot) | ⭐63,358 total | Robotics operating system that upgrades driver assistance systems for 300+ supported consumer vehicles, the highest-starred active robotics framework this week.
- [dora-rs/dora](https://github.com/dora-rs/dora) | ⭐3,870 total | Dataflow-Oriented Robotic Architecture middleware for low-latency, composable AI robotic applications, growing in popularity for simplifying distributed robot pipeline development.
- [softmata/horus](https://github.com/softmata/horus) | ⭐407 total | High-performance robotics runtime positioned as the "Android for robots", optimized for low-latency physical AI deployments on heterogeneous hardware.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) | ⭐127 total | ROS-free sim-to-real framework for VLA and RL agent deployment, with native wrappers for common robot arms and humanoids, solving a longstanding pain point of ROS configuration overhead for VLA researchers.
- [newton-physics/newton](https://github.com/newton-physics/newton) | ⭐5,302 total | GPU-accelerated physics engine built on NVIDIA Warp, purpose-built for robotic simulation and high-fidelity sim-to-real transfer.
- [rerun-io/rerun](https://github.com/rerun-io/rerun) | ⭐11,260 total | Multimodal robotics data visualization and streaming tool, widely adopted for debugging VLA and robot learning workflows.

### 🧠 VLA / Foundation Models
- [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) | ⭐1,975 total | Open 10B reasoning VLA for autonomous vehicles with Chain-of-Causation trajectory reasoning, NVIDIA’s flagship open VLA model with massive developer interest.
- [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) | ⭐136 total | 34B multi-task VLA foundation model for autonomous vehicle development, released this week as the largest openly available VLA for driving use cases.
- [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) | ⭐206 total | Official implementation of BridgeVLA and BridgeVLA++, state-of-the-art generalist robot VLA models widely used for sim-to-real manipulation transfer.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) | ⭐129 total | Open-source evaluation framework for physical AI, enabling standardized testing of any VLA/LLM on any robot hardware or simulation benchmark.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) | ⭐3,041 total | Zero-to-VLA course requiring only basic Python, walking developers through building OpenVLA, SmolVLA, and Pi0 models from scratch, driving accessibility for embodied AI newcomers.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) | ⭐482 total | Chinese-language, practice-focused VLA learning and interview guide, filling a gap for non-English speaking developers entering the field.

### 🦾 Manipulation & Grasping
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) | ⭐3,208 total | GPU-parallelized robotics manipulation simulator and benchmark, the de facto standard for VLA manipulation training.
- [enactic/openarm](https://github.com/enactic/openarm) | ⭐2,820 total | Fully open-source humanoid arm for physical AI research in contact-rich environments, a low-cost open hardware option for independent manipulation research teams.
- [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) | ⭐13,048 total | Library of agent skills for CAD, CAE, and CAM workflows, demonstrating how general agent skill frameworks are expanding to physical engineering and manufacturing use cases.
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) | ⭐46 total | Open-source software for synchronized bimanual data collection and cross-robot retargeting, solving a critical data bottleneck for bimanual VLA training.
- [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) | ⭐14 total | Deployment-focused Pi0 VLA policy fork for LimX TRON2 manipulation arms, including fine-tuning and real-robot client examples.
- [Enoch208/Crux](https://github.com/Enoch208/Crux) | ⭐0 total | End-to-end failure discovery and repair tool for contact-rich manipulation, running on a single consumer GPU with verifiable results, a novel approach to improving manipulation reliability.

### 🚶 Locomotion & Navigation
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) | ⭐4,562 total | ROS 2 navigation framework for mobile robots, the industry standard for autonomous path planning and obstacle avoidance.
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) | ⭐324 total | Open legged locomotion and momentum-based control software used by leading humanoid and exoskeleton projects worldwide.
- [NJU-RLC/quadrupedal-agility](https://github.com/NJU-RLC/quadrupedal-agility) | ⭐122 total | Official implementation of state-of-the-art quadruped agility training, enabling diverse natural behaviors for four-legged robots.
- [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) | ⭐38 total | Official code for the RoboNaldo humanoid soccer shooting system, demonstrating state-of-the-art dynamic bipedal locomotion for high-force, contact-rich tasks.
- [limxdynamics/humanoid-mujoco-sim](https://github.com/limxdynamics/humanoid-mujoco-sim) | ⭐9 total | MuJoCo simulation environment for LimX humanoid robots, optimized for sim-to-real locomotion policy training and evaluation.

### 📦 Embodied Applications
- [666ghj/MiroFish](https://github.com/666ghj/MiroFish) | ⭐0 total (+141 today) | Simple, universal swarm intelligence engine for general prediction and multi-robot coordination, the only embodied-adjacent project on today’s general GitHub trending list with triple-digit daily star growth.
- [PhyAgentOS-Dev/PhyAgentOS](https://github.com/PhyAgentOS-Dev/PhyAgentOS) | ⭐1,673 total | Self-evolving embodied AI operating system built on agentic workflows, bridging general autonomous agent frameworks to physical robot control.
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) | ⭐2,698 total | Official code for the ICML 2026 RoboTwin 2.0 digital twin platform for embodied AI training and sim-to-real transfer.
- [robocasa/robocasa](https://github.com/robocasa/robocasa) | ⭐1,630 total | Large-scale household task simulation environment for generalist robots, with 1000+ everyday tasks for VLA evaluation.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) | ⭐157 total | Full-embodiment humanoid teleoperation system, enabling low-cost remote control of humanoid robots for data collection and remote task execution.

---

## 3. Trend Signal Analysis
The most explosive community attention this period is concentrated on vertically specialized Vision-Language-Action (VLA) models, marking a clear shift from generalist lab manipulation VLA to production-ready, domain-specific use cases. NVIDIA’s open-source Alpamayo VLA series for autonomous driving—spanning 10B to 34B parameter models with Chain-of-Causation reasoning and RL-enhanced navigation—has rapidly become a reference for VLA deployment outside of academic robotics labs, aligned with recent industry pushes to integrate foundation models into consumer and commercial autonomous vehicle stacks.
A notable new direction is commercial humanoid hardware vendors releasing full open-source development stacks: LimX Dynamics published six interconnected repositories covering humanoid URDF models, MuJoCo simulation environments, VLA policy fine-tuning tools, and real-robot deployment clients, a break from the historical pattern of closed proprietary hardware tooling. This shift mirrors the early mobile OS ecosystem, where vendors opened platforms to cultivate third-party developer ecosystems and reduce barriers to adoption.
Finally, the broader agent skill framework trend (visible in today’s general GitHub trending list of coding agent tools) is explicitly crossing over to embodied use cases, with new tooling for CAD agent skills, embodied agent operating systems, and swarm intelligence engines for multi-robot coordination.

---

## 4. Community Hot Spots
- **NVIDIA Alpamayo VLA Ecosystem**: The full stack of Alpamayo models, fine-tuning recipes, and 34B foundation model is the most active new VLA initiative, with direct applicability to both autonomous driving and general embodied reasoning, making it a high-priority area for developers working on production VLA deployment.
- **LimX Dynamics Humanoid Toolchain**: The first full open development stack from a commercial humanoid vendor eliminates custom integration work for researchers, enabling direct testing of VLA policies on production-grade humanoid and robotic arm hardware.
- **ROS-Free VLA Deployment Frameworks**: Projects like `robot-control-stack` address a longstanding pain point for VLA researchers, eliminating the overhead of ROS configuration for sim-to-real transfer, and are likely to become standard for small teams and individual developers building VLA applications.
- **Low-Barrier Embodied AI Education**: The `every-embodied` zero-to-VLA course and `VLA-Handbook` are driving rapid entry of new developers into embodied AI, filling a critical gap for accessible, practical learning resources that do not require advanced robotics or ML background.
- **Embodied Agent Operating Systems**: Projects like PhyAgentOS are bridging the gap between general autonomous agent frameworks (e.g., AutoGPT) and physical robot control, a fast-growing intersection that will enable more self-improving embodied systems in the near term.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*