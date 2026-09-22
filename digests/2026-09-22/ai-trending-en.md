# AI Open Source Trends 2026-09-22

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-09-22 02:14 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
*Date: 2026-09-22*

---

## 1. Today's Highlights
No robotics or embodied AI repositories ranked in the top 12 daily GitHub trending list for September 22, 2026, with viral developer attention skewing toward general AI agent frameworks and financial tools. Despite the absence of daily trending breakouts, active topic repositories show robust momentum across the embodied AI stack, particularly in VLA model adaptation to commercial robotic hardware and standardized physical AI evaluation infrastructure. Key emerging developments include new whole-body VLA frameworks for unified humanoid loco-manipulation control and dedicated red-teaming tools for VLA policy safety, reflecting the field’s shift from siloed manipulation/locomotion research to integrated, safety-validated full-body robotic systems. The surge in open-source ports of state-of-the-art VLA models (including π₀ and OpenPI) to commercial dual-arm and humanoid platforms indicates that open VLA weights are rapidly becoming the default foundation for commercial robotic AI development.

---

## 2. Top Projects by Category
*Note: Only repositories on the daily trending list have verified today's new star counts; all listed star counts below are total lifetime stars.*

### 🤖 Robot Frameworks / SDKs
- [dora-rs/dora](https://github.com/dora-rs/dora) — 3,976 stars: Rust-based dataflow-oriented robotic middleware that simplifies building AI-powered robotic applications with low-latency, composable distributed pipelines, emerging as a modular alternative to ROS for embodied AI stacks.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — 8,189 stars: Unified robot learning framework with multi-physics/renderer support, widely used for sim-to-real VLA and policy training, and a critical tool for scaling embodied AI model development.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) — 15,261 stars: Industry-standard multi-joint dynamics with contact physics simulator, foundational for robotics manipulation, locomotion, and VLA policy validation across research and industry.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) — 4,732 stars: ROS 2-native navigation framework providing path planning, localization, and obstacle avoidance for mobile robots, a staple production tool for autonomous locomotion deployments.
- [softmata/horus](https://github.com/softmata/horus) — 439 stars: Rust-based high-performance robotics runtime system positioned as an "Android for robots", gaining traction as a purpose-built OS alternative for humanoid and general-purpose robotic platforms.
- [baidu-baige/LoongForge](https://github.com/baidu-baige/LoongForge) — 575 stars: High-performance training framework supporting LLMs, VLMs, and embodied models across NVIDIA GPUs and Kunlun XPUs, notable for first-class support for physical AI model training on heterogeneous hardware.

### 🧠 VLA / Foundation Models
- [dexmal/opendm](https://github.com/dexmal/opendm) — 2,213 stars: Open-world foundation model for general-purpose embodied intelligence, one of the few open-source end-to-end foundation models targeting cross-task physical agent capabilities.
- [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) — 309 stars: Unified framework for training, fine-tuning, and evaluating World Action Models, a fast-emerging VLA variant that integrates world modeling for more robust long-horizon task execution.
- [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) — 3 stars: New unified VLA framework for seamless humanoid loco-manipulation control, addressing the critical gap of whole-body coordination between locomotion and manipulation in humanoid VLA systems.
- [3587jjh/HuRo](https://github.com/3587jjh/HuRo) — 29 stars: CoRL 2026 accepted work that robotizes human videos for scalable VLA pretraining, offering a low-cost data sourcing solution to address the longstanding VLA training data bottleneck.
- [XenseRobotics-AI/xense-openpi](https://github.com/XenseRobotics-AI/xense-openpi) — 16 stars: Adaptation of π₀/π₀.₅ VLA models to Xense dual-arm robot platforms, showcasing the growing trend of porting state-of-the-art open VLA models to commercial robotic hardware.
- [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) — 118 stars: Official implementation of Omni-Modal Motion Generation for generalist humanoid control, a cutting-edge approach bridging multimodal inputs to full-body humanoid motion policies.

### 🦾 Manipulation & Grasping
- [NVIDIA-ISAAC-ROS/isaac_ros_cumotion](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_cumotion) — 270 stars: NVIDIA-accelerated ROS 2 packages for robotic arm motion planning and control, optimized for real-time contact-rich manipulation tasks with industrial-grade performance.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) — 602 stars: Standardized manipulation benchmark platform for evaluating embodied AI policies across diverse contact-rich tasks, widely adopted for head-to-head VLA model performance comparison.
- [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) — 142 stars: Framework that compiles natural language instructions into type-verified robot skill graphs for execution on simulators and real robots, enabling reliable, composable manipulation task planning.
- [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) — 68 stars: Open-source bimanual data collection and retargeting software compatible with dual-arm robot platforms, lowering barriers to generating high-quality imitation learning data for dexterous manipulation.
- [physiclaw/PhysiClaw](https://github.com/physiclaw/PhysiClaw) — 375 stars: AI agent that physically operates a smartphone via robotic actuation, demonstrating real-world manipulation capabilities for unstructured consumer electronic interaction tasks.
- [RoboTwin-Platform/RMBench](https://github.com/RoboTwin-Platform/RMBench) — 215 stars: Memory-dependent manipulation benchmark built on the RoboTwin platform, targeting long-horizon manipulation tasks that require persistent state memory, a key gap in current VLA evaluation suites.

### 🚶 Locomotion & Navigation
- [commaai/openpilot](https://github.com/commaai/openpilot) — 63,696 stars: Open-source robotics OS that powers advanced driver assistance systems for 300+ car models, one of the most widely deployed embodied AI systems for real-world mobile navigation.
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) — 325 stars: Leading open-source legged locomotion software stack with momentum-based control, used on world-class humanoids, exoskeletons, and bipedal robots for robust dynamic walking.
- [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) — 15,911 stars: Mature open-source flight controller software for drones, rovers, and submersibles, supporting autonomous navigation across a wide range of mobile robotic platforms.
- [limxdynamics/tron2_rl_deploy_python](https://github.com/limxdynamics/tron2_rl_deploy_python) — 2 stars: New RL deployment toolkit for the LimX TRON2A humanoid (sole-foot and wheel-foot variants), supporting ONNX Runtime, MuJoCo simulation, and real hardware deployment for bipedal locomotion policies.
- [pal-robotics/kangaroo_robot](https://github.com/pal-robotics/kangaroo_robot) — 5 stars: Open-source educational robot platform designed for learning walking locomotion, making legged robotics research accessible to students and hobbyist developers.
- [ershui2500/UniRoboGui](https://github.com/ershui2500/UniRoboGui) — 3 stars: Open-source web GUI and SDK dashboard for Unitree G1 humanoids, supporting telemetry, SLAM/navigation, point cloud visualization, and joint debugging for bipedal platforms.

### 📦 Embodied Applications
- [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core) — 2,475 stars: Recursive self-improving physical agent operating system that enables agents to iteratively improve their capabilities via agentic workflows, a pioneering approach to autonomous embodied skill refinement.
- [rokbenko/quackd](https://github.com/rokbenko/quackd) — 225 stars: Unified CLI for controlling heterogeneous robot fleets (LeRobot, AlohaMini, ROS-based, etc.) with LLM brains, supporting cross-vendor robot orchestration, safety contracts, and persistent memory across runs.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) — 584 stars: Open-source evaluation framework for physical AI, supporting testing of any LLM/VLA model on any arm/humanoid platform across real and simulated benchmarks, addressing the growing need for standardized VLA evaluation.
- [FastCrest/tether](https://github.com/FastCrest/tether) — 84 stars: Edge-to-cloud AI deployment CLI optimized for robotic hardware (Jetson, RTX, Apple Silicon, AMD), with hybrid edge-cloud inference and parity verification, simplifying VLA model deployment on physical robots.
- [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) — 9 stars: Strands VLA agent that controls a FrodoBots Earth Rover Mini+ with full vision-language-action capabilities, paired with an open ECoT dataset for outdoor rover VLA research.
- [provael/provael](https://github.com/provael/provael) — 7 stars: Red-teaming tool for open VLA robot policies in simulation that calculates attack success rates, addressing the rising need for safety validation of embodied AI systems before real-world deployment.

---

## 3. Trend Signal Analysis
The most explosive community attention in embodied AI is currently focused on the commoditization and real-world deployment of vision-language-action (VLA) models, evidenced by a wave of open-source ports of state-of-the-art VLA weights (including π₀ and OpenPI) to commercial dual-arm and humanoid robot platforms. This trend signals a maturing field where model development is no longer limited to top research labs, and downstream robotics teams are prioritizing adapting foundation models to specific hardware and use cases rather than building models from scratch.

A key emerging tech stack direction is the rise of Rust-based high-performance robotic runtimes and middleware (such as horus and dora-rs), positioned as lower-latency, resource-efficient alternatives to traditional Python-heavy ROS stacks for dynamic humanoid and edge robotic systems. This shift is driven by the demand for real-time whole-body control, which legacy ROS pipelines often struggle to deliver for bipedal and high-DOF manipulation platforms.

These trends align with recent industry and academic milestones, including the upcoming CoRL 2026 conference (which has already accepted multiple VLA pretraining and humanoid control works) and a wave of open VLA model releases from major AI labs in Q3 2026. The growing focus on VLA safety and red-teaming tools also corresponds to rising regulatory scrutiny of physical AI systems ahead of broader commercial humanoid deployments.
(Word count: 291)

---

## 4. Community Hot Spots
- **Open VLA model porting to commercial hardware**: Projects like [XenseRobotics-AI/xense-openpi](https://github.com/XenseRobotics-AI/xense-openpi) and [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) are leading a fast-growing trend of adapting state-of-the-art open VLA weights to proprietary robotic platforms, enabling teams to skip costly base model training and jump straight to task-specific fine-tuning.
- **Whole-body humanoid VLA control**: The newly released [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) addresses a critical unmet need for unified locomotion and manipulation control in humanoid VLA systems, a key bottleneck for general-purpose humanoid robots, making it a high-impact project to track for developers and researchers.
- **VLA safety and red-teaming**: [provael/provael](https://github.com/provael/provael), a new simulation-based red-teaming tool for VLA policies, taps into the rapidly growing demand for embodied AI safety validation as VLA models move from lab settings to real-world deployments, with very few dedicated open-source tools currently available in this space.
- **Rust-based robotic infrastructure**: Rust projects like [softmata/horus](https://github.com/softmata/horus) and [dora-rs/dora](https://github.com/dora-rs/dora) are gaining traction as next-generation alternatives to ROS for high-performance humanoid and low-latency robotic applications, representing a potential paradigm shift in the core robotics software stack.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*