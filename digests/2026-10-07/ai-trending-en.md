# AI Open Source Trends 2026-10-07

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-10-07 03:07 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-10-07

---

## 1. Today's Highlights
Today’s top relevant trending repository is [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) with +619 new daily stars, a tool that equips AI agents with CAD generation capabilities, reflecting surging demand for agentic design tools for physical robotics systems. Humanoid robotics software is seeing strong momentum, with a wave of new open-source projects spanning motion imitation, whole-body VLA control, and sim-to-real deployment for low-cost consumer platforms like Unitree G1/R1. VLA (Vision-Language-Action) model tooling is maturing rapidly, with new open-weight 7B–34B parameter action models and unified training frameworks lowering barriers to building generalist embodied agents. Evaluation infrastructure for physical AI is also expanding, with new standardized benchmarks for manipulation and cross-platform VLA testing gaining community traction.

---

## 2. Top Projects by Category

### 🤖 Robot Frameworks / SDKs
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,289 total  
   Unified multi-physics robot learning framework with renderer support, serving as a de facto standard for sim-to-real VLA and RL policy training across humanoid, manipulation, and locomotion tasks.
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,493 total  
   Industry-standard multi-joint contact physics simulator, widely used for prototyping humanoid control, manipulation policies, and VLA model evaluation in controlled simulation environments.
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,993 total  
   Dataflow-oriented robotic middleware designed to streamline AI-powered robot application development, with low-latency composable pipelines that simplify integration of VLA models and perception stacks.
4. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐163 total  
   Lightweight, ROS-free sim-to-real framework for training and deploying VLA models and RL agents, with native MuJoCo Gymnasium wrappers for common robot arms and humanoids, reducing deployment friction for small teams.
5. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,726 total  
   GPU-accelerated physics simulation engine built on NVIDIA Warp, optimized for large-scale parallel robot learning workflows and high-throughput VLA training.
6. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,551 total  
   Multimodal robotics data visualization and streaming platform, enabling teams to debug, iterate on, and train VLA models using synchronized vision, action, and sensor data.

### 🧠 VLA / Foundation Models
1. [black-forest-labs/flux-action](https://github.com/black-forest-labs/flux-action) ⭐138 total  
   Open-weight 7B world action model for robot action prediction, supporting DROID, SO-101 robots, simulators, and games, marking a major new entrant in open-source generalist action models.
2. [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐266 total  
   NVIDIA’s 34B multi-task foundation model for autonomous vehicle development, expanding VLA use cases beyond industrial manipulation to large-scale autonomous driving deployments.
3. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐2,206 total  
   Open-world foundation model for general-purpose embodied intelligence, designed to support cross-embodiment action generation across diverse robot platforms.
4. [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐3 total  
   Unified Vision-Language-Action framework for humanoid loco-manipulation, enabling seamless control of whole-body movement and advanced manipulation tasks in unstructured spaces.
5. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐399 total  
   Unified framework for training, fine-tuning, and evaluating World Action Models, standardizing workflows for VLA model development across different robot embodiments.
6. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐676 total  
   Practice-oriented Chinese-language VLA learning and interview handbook focused on robotics-specific challenges, reflecting rapidly growing developer interest in entering the VLA field.

### 🦾 Manipulation & Grasping
1. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐675 total  
   Unified sim-and-real benchmark for comprehensive evaluation of generalist robot manipulation policies, filling a critical gap in standardized testing for cross-platform manipulation models.
2. [enactic/openarm](https://github.com/enactic/openarm) ⭐3,579 total  
   Fully open-source humanoid arm designed for physical AI research and contact-rich task deployment, providing a low-cost hardware platform for VLA manipulation testing.
3. [XPolicyLab/XPolicyLab](https://github.com/XPolicyLab/XPolicyLab) ⭐395 total  
   Toolkit integrating over 50 advanced manipulation policies, enabling researchers to quickly benchmark and deploy state-of-the-art grasping and contact-rich task solutions.
4. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐75 total  
   Open-source software for synchronized bimanual data collection and retargeting to any bimanual robot, lowering barriers to building high-quality manipulation datasets for VLA training.
5. [RobotControlStack/duobench](https://github.com/RobotControlStack/duobench) ⭐21 total  
   Reproducible bimanual manipulation benchmark for both simulation and real-world testing, supporting standardized evaluation of dual-arm VLA and RL policies.
6. [RunpeiDong/HERO](https://github.com/RunpeiDong/HERO) ⭐10 total  
   CoRL 2026 paper implementation for humanoid end-effector control, enabling visual whole-body open-vocabulary object grasping for humanoid platforms.

### 🚶 Locomotion & Navigation
1. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐16,005 total  
   Open-source autopilot software suite for planes, copters, rovers, and submersibles, supporting a wide range of autonomous navigation and locomotion use cases for mobile robots.
2. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325 total  
   Mature robotics software stack with legged locomotion algorithms and momentum-based control, used for world-class humanoid, exoskeleton, and legged robot platforms.
3. [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐380 total  
   Whole-body nonlinear MPC framework for real-time humanoid loco-manipulation planning and control, enabling coordinated movement and manipulation tasks.
4. [kedianwen/LDRQ](https://github.com/kedianwen/LDRQ) ⭐2 total  
   Sim-to-real asymmetric-PPO walking policy for the Unitree R1 humanoid, deployed on onboard Jetson Orin NX hardware, with English command support via a local LLM.
5. [alertform/g1-motion-imitation](https://github.com/alertform/g1-motion-imitation) ⭐0 total  
   Motion imitation pipeline for the Unitree G1 humanoid, using DeepMimic-style PPO in MuJoCo MJX to achieve 30 seconds of stable walking on a single RTX 4060, demonstrating accessible humanoid locomotion training.
6. [pal-robotics/kangaroo_robot](https://github.com/pal-robotics/kangaroo_robot) ⭐5 total  
   Educational walking robot platform designed to teach locomotion fundamentals, lowering the barrier for students and developers to learn legged robot control.

### 📦 Embodied Applications
1. [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) ⭐18,037 total (+619 today)  
   Text-to-CAD tool that gives AI agents CAD generation superpowers, today’s top trending robotics-adjacent repo, enabling agentic design of robot parts and embodied system components.
2. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,835 total  
   Open-source robotics operating system for advanced driver assistance, deployed on 300+ car models, representing one of the most widely adopted real-world embodied AI systems.
3. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐644 total  
   Open-source evaluation platform for physical AI, supporting testing of any LLM/VLA model on any arm or humanoid robot across sim and real benchmarks, standardizing embodied AI performance measurement.
4. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐176 total  
   Agent-based system for controlling robots and physical hardware with natural language, demonstrating how LLM agent frameworks can be integrated with real-world robot platforms.
5. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐62 total  
   Digital twin platform for robotics-assisted chemistry lab automation, showcasing a high-impact vertical application of embodied AI and robotic manipulation.
6. [arterialist/jev-robot](https://github.com/arterialist/jev-robot) ⭐0 total  
   Integrated Unitree G1 humanoid system with JEV reflexes, Gemini-based planning, and a live browser control room, demonstrating a full-stack embodied agent deployment on consumer humanoid hardware.

---

## 3. Trend Signal Analysis
The most explosive area of community attention is low-cost humanoid robotics software stacks, with a flood of new open-source projects spanning motion imitation, whole-body control, sim-to-real deployment, and VLA integration for accessible platforms like Unitree G1/R1 and K-Scale Zeroth-01. This trend mirrors recent industry pushes to democratize humanoid hardware, as developers prioritize lightweight, ROS-free frameworks that lower barriers for small teams and individual researchers to build and test embodied intelligence on physical hardware.

VLA model commoditization is another key signal: open-weight action models have reached 7B–34B parameter scales (e.g., Black Forest Labs FLUX 3 Action, NVIDIA Alpamayo 2) and expanded beyond industrial manipulation to autonomous driving and generalist embodied agents. Unified training frameworks like EasyWAM are standardizing VLA development workflows, while evaluation platforms like inspect-robots are filling critical gaps in standardized performance testing across embodiments.

A newly emerging direction is agentic robotic design tools, exemplified by today’s top trending relevant repo text-to-cad. This reflects a shift from using AI agents only for robot control to enabling them to design physical robot components, aligning with the broader "physical AI" industry narrative of co-evolving hardware and software for embodied systems.

---

## 4. Community Hot Spots
- **Low-cost humanoid sim-to-real tooling**: Projects like [alertform/g1-motion-imitation](https://github.com/alertform/g1-motion-imitation) and [kedianwen/LDRQ](https://github.com/kedianwen/LDRQ) enable humanoid locomotion training on consumer GPUs and edge hardware, opening the field to developers without access to expensive research robots.
- **Open-weight world action models**: New entries like [black-forest-labs/flux-action](https://github.com/black-forest-labs/flux-action) and [dexmal/opendm](https://github.com/dexmal/opendm) challenge closed-source VLA offerings, giving developers free access to generalist action models that can be fine-tuned for custom robot platforms.
- **Agentic CAD for physical AI**: [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)’s explosive daily growth shows strong demand for tools that let AI agents design physical robot components, a critical building block for self-improving physical agent systems.
- **Standardized VLA evaluation**: Platforms like [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) and [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) address a core pain point in embodied AI research by providing unified benchmarks for comparing VLA models across sim and real hardware.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*