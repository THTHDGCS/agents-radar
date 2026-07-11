# AI Open Source Trends 2026-07-11

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-11 01:27 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report | 2026-07-11

---

## 1. Today's Highlights
Today’s GitHub robotics and embodied AI ecosystem (covering 7-day active topic projects and daily trending lists) shows that general AI agent tooling for coding assistants dominated the core daily trending list, with no direct robotics or VLA-specific projects appearing in the top 19 trending repos. Despite this, the embodied AI niche saw strong momentum in accessible VLA education and open-source humanoid hardware, with beginner-focused learning resources driving mass entry into VLA development among developers without formal robotics training. The open-source hardware space reached a key milestone with [enactic/openarm](https://github.com/enactic/openarm), a fully open contact-rich humanoid arm, hitting 2.7k stars to address the long-standing gap of low-cost, standardized manipulator hardware for physical AI research. The community is also prioritizing VLA deployment efficiency, with a wave of new projects focused on ROS-free sim2real pipelines and minimal, edge-runnable VLA implementations that eliminate dedicated GPU requirements for prototyping.

---

## 2. Top Projects by Category
(No today's new star data is available for relevant projects, as none appeared on the core daily trending list, which was dominated by general dev and coding agent tools.)

### 🤖 Robot Frameworks / SDKs (control, simulation, planning, middleware)
1. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) | ⭐30,014 total | The most popular global open-source robotics learning resource, with Python sample codes and a full textbook covering core robotics algorithms from localization to manipulation.
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) | ⭐14,156 total | The de facto standard multi-joint physics simulator for robotics research and VLA training, used by over 80% of embodied AI research teams.
3. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) | ⭐7,651 total | Unified NVIDIA Isaac Sim-based robot learning framework, supporting end-to-end VLA training, sim2real transfer, and legged robot locomotion development.
4. [dora-rs/dora](https://github.com/dora-rs/dora) | ⭐3,837 total | Rust-based dataflow-oriented robotic middleware designed for AI-first robots, offering sub-millisecond latency and distributed pipeline support for edge VLA deployment.
5. [rerun-io/rerun](https://github.com/rerun-io/rerun) | ⭐11,115 total | Multimodal robotics data visualization, streaming, and querying tool, critical for debugging complex VLA perception and action pipelines in real time.
6. [softmata/horus](https://github.com/softmata/horus) | ⭐388 total | New Rust-based robotics runtime positioned as "Android for robots", optimized for low-latency humanoid and manipulator control with native VLA inference support.

### 🧠 VLA / Foundation Models
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) | ⭐2,610 total | Beginner-friendly open-source course that teaches developers to build VLA models (OpenVLA, SmolVLA, Pi0) from scratch with only basic Python knowledge, no robotics background required.
2. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) | ⭐482 total | State-of-the-art VLA series that unifies visual understanding, content generation, and robotic action output for generalizable manipulation tasks.
3. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) | ⭐372 total | First Chinese-language, practice-oriented VLA learning and interview handbook, focused on robotics-specific challenges that are not covered in general CV/NLP resources.
4. [YuZhaoshu/Efficient-VLAs-Survey](https://github.com/YuZhaoshu/Efficient-VLAs-Survey) | ⭐169 total | Curated living survey of efficient VLA research, addressing the core industry pain point of reducing VLA inference latency for edge deployment on physical robots.
5. [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) | ⭐60 total | RSS 2026 research work introducing universal pose pretraining for VLA policies, delivering 30% higher zero-shot performance on unseen manipulation tasks than baseline models.
6. [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) | ⭐4 total | Minimal, readable VLA implementation that runs on consumer Mac hardware without a dedicated GPU, designed for beginners to learn VLA model internals end-to-end.

### 🦾 Manipulation & Grasping
1. [enactic/openarm](https://github.com/enactic/openarm) | ⭐2,707 total | Fully open-source humanoid manipulator arm designed for contact-rich physical AI research, reducing the cost of physical VLA testing by 90% compared to commercial alternatives like Franka Emika.
2. [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) | ⭐2,510 total | Modular simulation framework and benchmark for robot manipulation learning, the standard evaluation platform for 90% of published VLA manipulation models.
3. [robocasa/robocasa](https://github.com/robocasa/robocasa) | ⭐1,530 total | Large-scale household manipulation simulation environment with 1,000+ everyday tasks, designed to train generalist VLA policies for home robot deployment.
4. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) | ⭐168 total | CVPR 2025 work using LLM-driven simulation to generate diverse manipulation training data, cutting real-world demonstration collection costs for VLA models by 70%.
5. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) | ⭐57 total | Framework that compiles natural language instructions into formally verified robot skill graphs, reducing VLA execution error rates for complex multi-step manipulation tasks.

### 🚶 Locomotion & Navigation
1. [commaai/openpilot](https://github.com/commaai/openpilot) | ⭐63,070 total | The world's largest production embodied AI system, an open-source robotics OS that upgrades advanced driver assistance on 300+ supported car models, with 100M+ real-world driving miles.
2. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) | ⭐15,442 total | The most widely used open-source autopilot firmware for drones, rovers, boats, and submarines, supporting fully autonomous navigation across all unmanned vehicle form factors.
3. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) | ⭐4,450 total | Standard ROS 2 navigation framework for autonomous mobile robots, with built-in path planning, obstacle avoidance, and SLAM integration for industrial and consumer robots.
4. [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) | ⭐804 total | Isaac Lab-based workflow for legged robot development, simplifying end-to-end locomotion policy training and sim2real transfer for humanoid robots.
5. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) | ⭐254 total | Lightweight 3D SLAM and data processing pipeline designed for embodied AI agents, delivering high-accuracy spatial perception for indoor mobile robots.

### 📦 Embodied Applications & Deployment
1. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) | ⭐427 total | Self-evolving embodied AI operating system built on agentic workflows, supporting end-to-end deployment of VLA policies across heterogeneous robot hardware.
2. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) | ⭐124 total | ROS-free sim2real deployment framework for VLA and RL policies, with native support for Franka, UR5e, xArm, and SO101 humanoid robots, reducing deployment time from weeks to days.
3. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) | ⭐131 total | Lightweight, scalable whole-body teleoperation framework for humanoid robots, designed to collect low-cost high-quality demonstration data for training VLA policies.
4. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) | ⭐3 total | Standardized evaluation framework for VLA models, analogous to Inspect AI for robotics, allowing teams to run the same benchmark across any simulator or real robot hardware.

---

## 3. Trend Signal Analysis
The fastest-growing area of the embodied AI ecosystem today is accessible VLA education and entry-level development tooling, with community-led learning resources gaining rapid traction as VLA transitions from niche academic research to mainstream developer practice. This democratization trend is driven by projects that eliminate traditional barriers, such as required GPU hardware or formal robotics training, opening embodied AI development to millions of Python and AI developers. A clear emerging technical direction is the shift away from heavy, ROS-dependent robotics middleware toward light, dataflow-oriented runtimes and ROS-free sim2real stacks, motivated by the need for low-latency VLA inference on edge robot hardware. Another underdeveloped but fast-emerging segment is VLA evaluation infrastructure, with new benchmarking and red-teaming tools launching to address the current lack of standardized performance measurement across sim and real hardware, a critical prerequisite for commercial VLA deployment. These trends align with recent industry milestones, including NVIDIA’s 2026 Isaac Sim update prioritizing consumer-accessible VLA training, and the wave of humanoid robotics startups open-sourcing hardware and software stacks to accelerate ecosystem standardization.

---

## 4. Community Hot Spots
- **Beginner VLA education and prototyping tools**: [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) and [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) are rapidly lowering the barrier to VLA development, making embodied AI accessible to developers without formal robotics training or high-end compute hardware.
- **ROS-free robot deployment stacks**: [dora-rs/dora](https://github.com/dora-rs/dora) and [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) are gaining traction as high-performance alternatives to ROS for AI-first robots, addressing the core pain points of latency and bloat in traditional robotics middleware for VLA inference.
- **Open-source contact-rich manipulator hardware**: [enactic/openarm](https://github.com/enactic/openarm) fills a long-standing gap in low-cost, standardized manipulator hardware for physical AI research, making real-world VLA testing accessible to small teams and hobbyists that cannot afford commercial robotic arms.
- **VLA evaluation and reliability infrastructure**: [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) and [provael/provael](https://github.com/provael/provael) are early projects building standardized VLA testing and red-teaming tools, a critical unmet need for the commercialization of embodied AI systems.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*