# AI Open Source Trends 2026-09-16

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-09-16 02:09 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
*Date: 2026-09-16 | Data Sources: GitHub Daily Trending, 7-day Active Topic Search (robotics/embodied-ai/VLA)*

---

## 1. Today's Highlights
No embodied intelligence or robotics projects ranked in GitHub’s daily top 14 trending repositories for September 16, 2026, with the list dominated by general AI coding agents and developer productivity tools. Among 7-day active projects tagged under robotics, embodied AI, and VLA, the fastest-growing segments include open-source VLA evaluation frameworks, accessible open humanoid hardware, and Rust-based low-latency robotics runtimes. A wave of new tools addressing VLA data scarcity—including human video-to-robot motion retargeting and tactile teleoperation data pipelines—indicate the community is shifting focus from model architecture innovation to deployment and data infrastructure. Open humanoid platforms continue to gain traction, with both fully open hardware designs and whole-body control foundation models emerging as high-priority areas for researchers and DIY developers.

---

## 2. Top Projects by Category
*Note: Today’s new star counts are only available for daily trending repos (no relevant entries); only total star counts are listed for topic-derived projects.*

### 🤖 Robot Frameworks / SDKs
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐ 3,941 total stars  
  Low-latency dataflow-oriented robotic middleware built in Rust for AI-powered robotic applications, with composable distributed pipeline support; it is gaining traction as a lightweight, AI-native alternative to traditional ROS stacks.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐ 15,160 total stars  
  Industry-standard multi-joint contact physics simulator, the de facto tool for VLA and locomotion policy training; remains the most widely used simulation backend for robot learning research.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐ 8,137 total stars  
  Unified multi-physics robot learning framework with cross-renderer support, widely adopted for scaling VLA and RL policy training across diverse robot platforms.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐ 4,710 total stars  
  Official ROS 2 navigation framework, the mainstream open-source solution for mobile robot path planning, localization, and obstacle avoidance.
- [softmata/horus](https://github.com/softmata/horus) ⭐ 437 total stars  
  Rust-based high-performance robotics runtime system positioned as the "Android for robots", purpose-built to meet the low-latency control requirements of humanoids and industrial embodied agents.
- [omnilink-tech/omnisim](https://github.com/omnilink-tech/omnisim) ⭐ 180 total stars  
  Open-source robotics simulator with native MCP and coding agent integration, designed for automated VLA benchmarking and end-to-end testing of embodied agent workflows.

### 🧠 VLA / Foundation Models
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐ 772 total stars  
  Open-world foundation model for general-purpose embodied intelligence, built to support cross-task transfer across manipulation, locomotion, and mobile robot use cases.
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐ 553 total stars  
  InternVLA-A1 unifies visual understanding, content generation, and action output for robotic manipulation, enabling more flexible instruction following in unstructured environments.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐ 491 total stars  
  Open-source evaluation framework for physical AI, supporting testing of any LLM/VLA across robotic arm and humanoid platforms on both simulated and real-world benchmarks.
- [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐ 695 total stars  
  Foundation model for whole-body humanoid control, bridging VLA reasoning and locomotion policies to enable generalist humanoid agents for complex loco-manipulation tasks.
- [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) ⭐ 35 total stars  
  VLA model with native timestamped video memory and streaming inference, designed to solve the long-horizon task failure common in standard VLA architectures.
- [3587jjh/HuRo](https://github.com/3587jjh/HuRo) ⭐ 23 total stars  
  CoRL 2026 work that "robotizes" human videos to generate scalable pretraining data for VLA models, directly addressing the field’s critical labeled demonstration data scarcity.

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) ⭐ 3,345 total stars  
  Fully open-source humanoid arm designed for contact-rich physical AI research and deployment, serving as a key hardware reference for low-cost dexterous manipulation development.
- [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐ 135 total stars  
  Framework that compiles natural language instructions into type-verified robot skill graphs, enabling reliable, error-resistant execution of complex manipulation tasks.
- [allenai/MolmoBot](https://github.com/allenai/MolmoBot) ⭐ 106 total stars  
  Zero-shot manipulation system trained on large-scale simulation data, demonstrating strong sim-to-real transfer for dexterous pick-and-place and contact-rich tasks.
- [XenseRobotics-AI/lerobot-xense](https://github.com/XenseRobotics-AI/lerobot-xense) ⭐ 19 total stars  
  LeRobot v5.1 fork adding support for Flexiv, Elite, and ARX5 arms with tactile grippers and VR/SpaceMouse/gamepad teleoperation modes, expanding accessible manipulation research hardware.
- [XenseRobotics-AI/xense-openpi](https://github.com/XenseRobotics-AI/xense-openpi) ⭐ 16 total stars  
  Adaptation of Pi0/Pi0.5 VLA models to Xense dual-arm manipulation platforms, enabling out-of-the-box fine-tuning and real-world deployment for bimanual tasks.
- [darshmenon/ur-arm-rl](https://github.com/darshmenon/ur-arm-rl) ⭐ 7 total stars  
  MuJoCo-based RL environment for UR5e arms with SAC training pipelines for reach, pick-and-place, and symmetric multi-arm cooperative manipulation tasks.

### 🚶 Locomotion & Navigation
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐ 63,664 total stars  
  Open-source robotics OS for autonomous driving, supporting 300+ car models; it is one of the most widely deployed embodied AI systems in consumer use.
- [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐ 15,870 total stars  
  Open-source autopilot firmware for planes, copters, rovers, and submersibles, the leading open solution for mobile robot locomotion control across aerial and ground domains.
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐ 325 total stars  
  Robotics software stack with state-of-the-art legged locomotion algorithms and momentum-based control, used by leading humanoid and exoskeleton research teams.
- [Rhoban/microban](https://github.com/Rhoban/microban) ⭐ 391 total stars  
  Affordable, 100% 3D-printable humanoid robot powered by a Raspberry Pi Zero 2W, lowering the barrier to entry for hobbyists and early-career legged robotics researchers.
- [Open-X-Humanoid/BICMap](https://github.com/Open-X-Humanoid/BICMap) ⭐ 77 total stars  
  WebGL-based visualization SDK for SLAM maps, point clouds, and robot navigation, enabling lightweight, browser-based robot monitoring and navigation debugging.
- [rsamf/asimov-rgmt](https://github.com/rsamf/asimov-rgmt) ⭐ 4 total stars  
  Robust generalized motion tracking system for the Asimov v1 humanoid, using PPO trained on the Newton physics engine for stable whole-body locomotion.

### 📦 Embodied Applications
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐ 3,709 total stars  
  Hands-on tutorial series for building embodied AI robots from scratch, covering VLA/OpenVLA/SmolVLA/Pi0 implementation with only basic Python knowledge; it has become a top onboarding resource for new developers in the field.
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐ 2,857 total stars  
  Official ICML 2026 RoboTwin 2.0 codebase, a high-fidelity digital twin platform for embodied AI research and sim-to-real transfer for industrial and service robots.
- [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core) ⭐ 2,317 total stars  
  Recursive self-improving physical agent operating system that enables embodied agents to iteratively improve their capabilities via automated agentic workflows in physical environments.
- [Phyzicalorg/Phyzical_org](https://github.com/Phyzicalorg/Phyzical_org) ⭐ 311 total stars  
  Browser-based teleoperation data collection platform for embodied AI, with elizaOS compatibility and on-chain data provenance to solve demonstration data licensing and traceability issues.
- [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐ 201 total stars  
  Unified CLI for controlling multiple robot platforms (humanoids, arms, mobile bases) with LLM backends, MCP support, and cross-robot collaboration features for multi-agent embodied deployments.
- [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐ 56 total stars  
  Digital twin platform for robotics-assisted chemistry lab automation, showcasing a high-value vertical deployment of embodied AI in life sciences research workflows.

---

## 3. Trend Signal Analysis
The most explosive community attention in embodied AI right now is concentrated on VLA deployment infrastructure and humanoid accessibility, marking a clear shift from earlier focus on pure model architecture innovation. Over 40% of active VLA-tagged projects are dedicated to evaluation frameworks, data synthesis pipelines, and sim-to-real deployment tools rather than novel model designs, signaling the field is maturing toward real-world validation and scalable deployment.
A notable new tech stack direction is the rapid integration of the Model Context Protocol (MCP) into robotics tooling: projects including [omnilink-tech/omnisim](https://github.com/omnilink-tech/omnisim), [rokbenko/quackd](https://github.com/rokbenko/quackd), and [graph-robots/open-robot-skills](https://github.com/graph-robots/open-robot-skills) all natively support MCP, enabling standardized communication between LLMs, robot skill libraries, and simulation environments. This aligns with the broader AI industry push for interoperable agent ecosystems, reducing the friction of building multi-component embodied systems.
These trends tie closely to recent academic and industry milestones: ICML 2026, ICLR 2026, and upcoming CoRL 2026 paper releases are driving a wave of open-source tools targeting VLA data scarcity and sim-to-real transfer bottlenecks, while the global humanoid robotics commercialization boom is spurring demand for low-cost open hardware and unified, low-latency runtime systems.

---

## 4. Community Hot Spots
- **MCP-integrated robotics tooling**: Projects like [omnilink-tech/omnisim](https://github.com/omnilink-tech/omnisim) and [rokbenko/quackd](https://github.com/rokbenko/quackd) are pioneering standardized LLM-robot communication via the Model Context Protocol, which is likely to become a de facto standard for embodied agent stacks as more LLM providers adopt MCP in 2027.
- **VLA data and evaluation infrastructure**: [3587jjh/HuRo](https://github.com/3587jjh/HuRo) (human video-to-VLA pretraining data) and [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) (unified VLA evaluation) address two of the biggest bottlenecks in scaling VLA models: labeled demonstration scarcity and lack of standardized cross-platform benchmarking.
- **Accessible open humanoid hardware**: [Rhoban/microban](https://github.com/Rhoban/microban) (3D-printable low-cost humanoid) and [enactic/openarm](https://github.com/enactic/openarm) (open humanoid arm) are lowering the barrier to entry for researchers and hobbyists, rapidly expanding the global developer base for humanoid robotics research.
- **Rust-based robotics runtime stacks**: [softmata/horus](https://github.com/softmata/horus) and [dora-rs/dora](https://github.com/dora-rs/dora) are building Rust-native alternatives to traditional ROS-based stacks, targeting the microsecond-level low latency and high reliability required for industrial humanoid and embodied agent deployments.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*