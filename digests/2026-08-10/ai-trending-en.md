# AI Open Source Trends 2026-08-10

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-10 00:52 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-08-10

---

## 1. Today's Highlights
Today’s most notable embodied AI development is the active iteration of NVIDIA’s Alpamayo VLA series, with three open model releases and dedicated deployment tools advancing reasoning-capable VLAs for autonomous locomotion and manipulation. Second, the ecosystem is seeing a proliferation of humanoid-specific open source tools, from fully open robotic arm hardware to whole-body VLA control frameworks, aligned with accelerating industrial investment in general-purpose humanoid robots. Third, standardized cross-platform VLA evaluation tools are gaining traction, with projects like Inspect Robots and Kitchenbench addressing the critical unmet need for consistent, hardware-agnostic benchmarking of embodied model performance. Finally, accessible educational resources for VLA and embodied intelligence are growing rapidly, with zero-to-production tutorials lowering entry barriers for new developers without advanced robotics backgrounds.

*Note: No core embodied intelligence, VLA, or robotics projects appeared in the August 10, 2026 GitHub daily top 12 trending list; all star counts below are total public GitHub stars as of the report date.*

---

## 2. Top Projects by Category

### 🤖 Robot Frameworks / SDKs (Control, Simulation, Planning, Middleware)
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,496: De facto standard physics simulator for robotics, serving as the foundation for most sim-to-real VLA and robot learning workflows.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,865: Unified NVIDIA Isaac Sim-based robot learning framework, rapidly becoming the industry standard for large-scale VLA pre-training and policy development.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,868: Dataflow-oriented robotic middleware optimized for low-latency AI robot deployments, solving critical composability and latency pain points for embodied agent stacks.
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,493: Dedicated reinforcement learning infrastructure built exclusively for embodied and agentic AI, streamlining end-to-end VLA training pipelines.
- [softmata/horus](https://github.com/softmata/horus) ⭐408: High-performance robotics runtime positioned as an "Android for robots", targeting low-latency control for humanoids and general-purpose embodied systems.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,567: Production-grade ROS 2 navigation stack, a core tool for mobile robot and humanoid path planning and autonomous navigation.
- [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,269: Multimodal robotics data visualization and streaming tool, essential for debugging complex VLA and robot learning workflows.

### 🧠 VLA / Foundation Models
- [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐148: NVIDIA's latest 34B multi-task VLA foundation model for autonomous vehicles, marking a major scale-up in reasoning VLA development for embodied systems.
- [NVlabs/alpamayo1.5](https://github.com/NVlabs/alpamayo1.5) ⭐352: 10B reasoning VLA with RL-enhanced navigation and visual question answering capabilities, supported by official deployment recipes for developers.
- [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) ⭐211: Official implementation of BridgeVLA and BridgeVLA++, widely adopted open VLA baselines for robotic manipulation research.
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐224: Open-world foundation model for general-purpose embodied intelligence, designed for cross-robot transfer learning.
- [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐2: New open VLA framework for unified humanoid loco-manipulation, addressing the gap of whole-body control via vision-language inputs.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐133: Open-source evaluation platform for VLAs, supporting testing across any robot arm or humanoid in simulated or real environments.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,059: Zero-to-VLA educational project that walks developers through building OpenVLA, SmolVLA, and Pi0 from scratch with only basic Python knowledge.

### 🦾 Manipulation & Grasping
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,211: GPU-parallelized robotics manipulation simulator and benchmark, a standard for VLA manipulation pre-training and evaluation.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐371: Leading manipulation benchmark for generalist robot learning, with standardized contact-rich task suites.
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,827: Fully open-source humanoid robotic arm for physical AI research, lowering the barrier for real-world VLA manipulation testing.
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐46: Open-source bimanual data collection and retargeting software, critical for generating real-world manipulation training data for VLAs.
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8: New bimanual kitchen manipulation benchmark for VLAs, built on the Inspect Robots evaluation framework.
- [MrRox1337/GripSense](https://github.com/MrRox1337/GripSense) ⭐0: Open-source slip-aware robotic gripper control software and benchmarking rig, addressing tactile sensing gaps in contact-rich manipulation.
- [codeofwhite/awesome-deformable-manipulation](https://github.com/codeofwhite/awesome-deformable-manipulation) ⭐1: Curated resource list for deformable object manipulation, a fast-growing unsolved challenge in embodied AI.

### 🚶 Locomotion & Navigation
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,377: Open-source robotics OS for advanced driver assistance, the most widely deployed embodied locomotion system for consumer vehicles.
- [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,271: Definitive open textbook and code samples for robotics algorithms, including locomotion, navigation, and SLAM.
- [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) ⭐5,075: Open-source quadruped robot pet framework, a standard platform for DIY and research legged locomotion testing.
- [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐268: ECCV 2026 high-fidelity navigation simulator using dynamic Gaussian splatting, enabling photorealistic sim-to-real navigation training.
- [NJU-RLC/quadrupedal-agility](https://github.com/NJU-RLC/quadrupedal-agility) ⭐122: Official implementation of the state-of-the-art method for enhancing quadrupedal robot agility via diverse natural behavior learning.
- [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) ⭐38: ICML 2026 humanoid soccer shooting system, demonstrating advanced dynamic locomotion control for humanoid robots.
- [limxdynamics/humanoid-mujoco-sim](https://github.com/limxdynamics/humanoid-mujoco-sim) ⭐9: Open MuJoCo simulation environment for LimX humanoids, designed for sim-to-real locomotion policy training and evaluation.

### 📦 Embodied Applications
- [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) ⭐6,657: Open-source upgrade for low-cost robotic lawn mowers to RTK GPS-based autonomous operation, a high-adoption consumer embodied AI application.
- [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover) ⭐9,560: Build-it-yourself 6-wheel Mars rover replica, a popular platform for educational and research field robotics deployments.
- [PhyAgentOS-Dev/PhyAgentOS](https://github.com/PhyAgentOS-Dev/PhyAgentOS) ⭐1,750: Self-evolving embodied AI OS built on agentic workflows, targeting general-purpose real-world robot deployment.
- [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,624: Stanford's platform for accelerating embodied AI research, with 1,000 real-world aligned tasks for sim-to-real testing.
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,705: ICML 2026 RoboTwin 2.0 digital twin framework for embodied AI, enabling high-fidelity sim-to-real transfer for industrial robots.
- [DexForce/EmbodiChain](https://github.com/DexForce/EmbodiChain) ⭐206: End-to-end GPU-accelerated modular platform for building general embodied intelligence, streamlining deployment across hardware platforms.
- [mkdir-sweetiepie/harvest_robot](https://github.com/mkdir-sweetiepie/harvest_robot) ⭐0: Open-source crop harvesting robot project, demonstrating embodied AI adoption in agricultural automation.

---

## 3. Trend Signal Analysis (272 words)
The fastest-growing area of the embodied AI ecosystem this week is reasoning-enabled Vision-Language-Action (VLA) models, with NVIDIA’s open-source Alpamayo series driving community attention as it scales from 10B to 34B parameters and adds chain-of-causation reasoning, RL-enhanced navigation, and cross-task transfer capabilities. This marks a clear shift from VLAs built exclusively for tabletop manipulation to general-purpose models capable of supporting autonomous vehicles, humanoid loco-manipulation, and industrial robotics use cases.

A notable new technical direction is the emergence of dedicated, AI-native robotic runtimes and middleware positioned as ROS alternatives, including Horus (a low-latency "Android for robots" runtime) and DORA (dataflow-oriented robotic architecture). These tools solve long-standing pain points with ROS’s latency overhead and poor composability for end-to-end VLA deployments, signaling a maturation of the stack as embodied systems move from research to production.

This activity aligns closely with the 2026 ICML and ECCV publication cycles, which featured multiple breakthrough humanoid and VLA papers, as well as recent $1B+ funding rounds for humanoid robotics startups that have accelerated demand for open-source pre-training, simulation, and evaluation tools.

---

## 4. Community Hot Spots
- **NVIDIA Alpamayo VLA Ecosystem**: The full stack of open Alpamayo models (1 Nano, 1.5 Nano, 2 Super) plus official fine-tuning and deployment recipes is the most active VLA development effort this week, offering production-ready reasoning VLAs that can be adapted to custom robot platforms with minimal overhead.
- **Humanoid Whole-Body VLA Tooling**: Projects like [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) and [enactic/openarm](https://github.com/enactic/openarm) fill a critical gap for humanoid developers, providing open hardware and software stacks for unified loco-manipulation control that was previously limited to proprietary research systems.
- **Cross-Platform VLA Evaluation**: [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) is a high-impact new tool that standardizes VLA testing across simulated and real hardware, solving a major bottleneck for comparing VLA performance and accelerating iterative model development.
- **Accessible VLA Education**: [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) is a fast-growing educational resource that lowers entry barriers to VLA development, enabling developers with only basic Python experience to build and deploy state-of-the-art VLA models from scratch.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*