# AI Open Source Trends 2026-07-30

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-30 01:18 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-07-30

---

## 1. Today's Highlights
Today's general GitHub trending list featured no dedicated embodied intelligence, VLA, or robotics projects, with top spots dominated by general AI agent tools, GIS platforms, and trading resources. However, 7-day active topic-tagged repositories reveal rapid growth in VLA educational infrastructure, open-source humanoid tooling, and VLA evaluation standards. NVIDIA released its official Alpamayo VLA developer hub, providing pre-built recipes for fine-tuning, RL post-training, quantization, and deployment — marking a major vendor push to democratize production-grade VLA development. A wave of new VLA safety and reliability projects launched, including tools to diagnose and fix instruction blindness in VLA policies, and benchmarks for cross-robot VLA evaluation, addressing critical gaps between lab research and real-world deployment. Open-source humanoid manipulation hardware and software gained significant community traction, with fully open humanoid arms and whole-body motion planning controllers lowering barriers to entry for physical AI research.

---

## 2. Top Projects by Category
(Note: Today's new star counts are only available for the daily trending list, which contained no relevant robotics/embodied AI projects; all star values below are total counts for 7-day active repositories.)

### 🤖 Robot Frameworks / SDKs
- [dora-rs/dora](https://github.com/dora-rs/dora): 3,855 total stars. Low-latency, composable dataflow-oriented robotic middleware that simplifies building AI-powered robotic applications, with support for distributed pipeline orchestration.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab): 7,800 total stars. Unified robot learning framework built on NVIDIA Isaac Sim, the de facto standard for high-fidelity simulation and sim2real training for VLA and RL policies.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco): 14,375 total stars. Industry-standard open-source physics simulator for multi-joint contact dynamics, used across all robotics subfields for training and testing.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack): 125 total stars. Lightweight, ROS-free sim2real framework for deploying VLA and RL policies to common robot arms (Franka, UR5e, xArm) with native MuJoCo Gymnasium wrappers.
- [rerun-io/rerun](https://github.com/rerun-io/rerun): 11,210 total stars. Multimodal robotics data visualization and streaming platform, critical for debugging complex VLA and RL training pipelines.
- [DLR-RM/stable-baselines3](https://github.com/DLR-RM/stable-baselines3): 13,629 total stars. Reliable, production-grade PyTorch implementations of core reinforcement learning algorithms widely used for robot control and skill learning.

### 🧠 VLA / Foundation Models
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied): 2,923 total stars. Beginner-friendly open course that teaches developers to build VLA models (OpenVLA, SmolVLA, Pi0) from scratch with only basic Python knowledge, democratizing VLA research.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook): 453 total stars. Chinese-language, practice-oriented VLA learning and interview handbook focused on robotics-specific challenges, tailored for algorithm engineers entering the embodied intelligence space.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): 94 total stars. Open-source cross-platform VLA evaluation suite that supports testing any VLA/LLM on any robot arm or humanoid across simulated and real-world benchmarks.
- [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes): 83 total stars. Official NVIDIA developer hub for the Alpamayo VLA, with production-ready recipes for fine-tuning, RL post-training, quantization, and edge deployment.
- [phi-monster/Galahad](https://github.com/phi-monster/Galahad): 89 total stars. Research project that diagnoses and fixes instruction blindness in VLA policies, providing deconfounded datasets, a measurement battery, and a low-rank data cure for a critical VLA flaw.
- [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety): 120 total stars. Comprehensive survey of embodied AI and VLA safety with 500+ papers, covering risks across perception, cognition, planning, and physical interaction.

### 🦾 Manipulation & Grasping
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill): 3,172 total stars. GPU-parallelized open-source manipulation simulator and benchmark, used for training and evaluating generalizable robot manipulation skills at scale.
- [enactic/openarm](https://github.com/enactic/openarm): 2,781 total stars. Fully open-source humanoid robotic arm designed for contact-rich physical AI research, lowering the hardware barrier for testing manipulation and VLA policies on real hardware.
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw): 42 total stars. Open-source bimanual data collection and retargeting software that enables synchronized teleoperation data capture and transfer to any bimanual robot, solving a key data bottleneck for dexterous manipulation.
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench): 8 total stars. Bimanual kitchen manipulation benchmark for VLA models, built on the Inspect Robots eval platform to test vertical domain manipulation performance.
- [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes): 1 total star. Novel training pipeline that bakes collision avoidance into VLA policy weights via differentiable safety losses, eliminating the need for post-hoc runtime safety filters for manipulation tasks.
- [chang-xinhai/Awesome-UMI](https://github.com/chang-xinhai/Awesome-UMI): 13 total stars. Curated list of resources for the Universal Manipulation Interface (UMI) ecosystem, including papers, datasets, and policies for standardized manipulation research.

### 🚶 Locomotion & Navigation
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2): 4,527 total stars. Industry-standard ROS 2 navigation framework for mobile robots, with production-grade path planning, localization, and obstacle avoidance capabilities.
- [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc): 351 total stars. Whole-body nonlinear model predictive control (MPC) library for real-time humanoid loco-manipulation planning and control, a core low-level component for humanoid deployment.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit): 140 total stars. Full-embodiment humanoid teleoperation system, critical for collecting high-quality loco-manipulation data and remotely controlling humanoid robots.
- [mturan33/isaac-g1-ulc](https://github.com/mturan33/isaac-g1-ulc): 16 total stars. Low-level RL controller for the Unitree G1 humanoid, trained and validated in NVIDIA Isaac Sim for sim2real deployment.
- [Renkunzhao/legged-daily](https://github.com/Renkunzhao/legged-daily): 20 total stars. Curated research collection of code, papers, and resources for legged robotics, covering both model-based and learning-based control methods.
- [zc-xzc/robot_platform](https://github.com/zc-xzc/robot_platform): 2 total stars. Open-source head-tracking active vision platform for humanoid robots, with 3D-printable mounts and simulation models for PICO 4 and D455 cameras.

### 📦 Embodied Applications
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS): 1,268 total stars. Self-evolving embodied AI operating system built on agentic workflows, designed to end-to-end manage physical robot capabilities, safety, and skill evolution.
- [commaai/openpilot](https://github.com/commaai/openpilot): 63,262 total stars. Production-grade robotics operating system currently deployed as an advanced driver assistance system in 300+ car models, the largest-scale real-world embodied AI deployment in the open-source ecosystem.
- [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi): 3,426 total stars. Open-source multimodal embodied assistant ecosystem with MCP integrations, IoT support, and cross-platform voice interaction, deployable to edge and consumer devices.
- [DexForce/EmbodiChain](https://github.com/DexForce/EmbodiChain): 201 total stars. End-to-end GPU-accelerated modular platform for building general embodied intelligence, eliminating the need for fragmented robotics and AI tools.
- [dsl-robotics/skatearm](https://github.com/dsl-robotics/skatearm): 2 total stars. Open bimanual work-cell ecosystem for the R.Botic Skate robot, with sim-first design in MuJoCo, autonomous assembly capabilities, and a web-based control cockpit for industrial use cases.
- [di-omics/plr-lab-robot](https://github.com/di-omics/plr-lab-robot): 1 total star. Simulation-first lab robotics platform for life science tasks, with eye-in-hand vision, dexterous manipulation, and auditable workcell workflows for pharmaceutical and biotech use cases.

---

## 3. Trend Signal Analysis
The embodied AI and robotics ecosystem is seeing explosive community attention in VLA democratization and humanoid enablement, even as the space remains a niche segment relative to general AI agents and consumer tools (evidenced by no robotics projects appearing on the daily GitHub trending list). Growth is driven by a rapid expansion of educational resources and production-grade tooling: courses like *every-embodied* and role-specific handbooks like *VLA-Handbook* have amassed thousands of stars in just 7 days, signaling a massive influx of AI-native developers entering the VLA space, breaking the longstanding barrier of VLA research being restricted to top industrial and academic labs. A key emerging technical direction is the standardization of VLA evaluation and safety: projects like *inspect-robots* are creating vendor-agnostic, cross-robot eval suites, while *LeRobot-SafetyCubes* introduces baked-in safety losses instead of post-hoc runtime filters, addressing a critical gap that has prevented VLA deployment outside controlled lab environments. This shift aligns directly with recent industry announcements of commercial VLA-powered humanoids (e.g., Figure 02, Unitree G1) and industrial manipulation robots, as the ecosystem moves from proof-of-concept research to scalable real-world deployment. Another notable new trend is the rise of ROS-free sim2real pipelines, led by *robot-control-stack*, which reduce deployment complexity for AI-native developers without traditional robotics engineering backgrounds.

---

## 4. Community Hot Spots
- [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes): The first production-grade VLA deployment toolkit from a major AI hardware vendor, with optimized pipelines for fine-tuning, RL post-training, and quantization. This is a critical resource for developers looking to deploy VLA policies on edge robotics hardware, and signals NVIDIA's long-term investment in the VLA ecosystem.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied): With nearly 3k stars, this beginner-friendly course that teaches developers to build VLA models from scratch is the most accessible entry point for general AI engineers transitioning to embodied intelligence, and is already driving rapid growth in the VLA developer community.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): Standardized, cross-platform evaluation is the single biggest bottleneck to VLA progress, and this open-source suite that supports any VLA, any robot, and any sim/real benchmark is rapidly emerging as the de facto community eval standard.
- [enactic/openarm](https://github.com/enactic/openarm): This fully open-source, low-cost humanoid arm for contact-rich manipulation solves the longstanding hardware access barrier for physical AI research, enabling small teams and individual developers to test VLA policies on real hardware without expensive commercial robotic arms.
- [phi-monster/Galahad](https://github.com/phi-monster/Galahad): Instruction blindness is a pervasive, critical flaw in current state-of-the-art VLA policies that causes them to ignore parts of user instructions, and this project provides both diagnostic tools and a proven data-driven fix, making it mandatory reading for anyone training production-ready VLA models.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*