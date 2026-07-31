# AI Open Source Trends 2026-07-31

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-31 01:45 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-07-31

---

## 1. Today's Highlights
Open-source VLA developer tooling and educational resources saw major momentum this week, with NVIDIA releasing official Alpamayo recipes for VLA fine-tuning, RL post-training, and deployment alongside two popular hands-on VLA courses targeting both beginner and advanced practitioners. Humanoid robotics infrastructure is maturing rapidly, with new runtime systems, whole-body VLA implementations, and low-cost open manipulation hardware emerging to reduce barriers to physical AI research and deployment. Standardization of VLA evaluation has emerged as a top community priority, with new open-source tools for cross-platform VLA testing, red-teaming, and transferability benchmarking launching to address longstanding gaps in policy validation. Safety is increasingly being integrated into VLA model design rather than applied as a post-hoc runtime filter, as demonstrated by a novel Pi0 VLA implementation that embeds collision avoidance directly into model weights via differentiable loss functions.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
(Control, simulation, planning, and deployment infrastructure for robotics)
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,805 total: Unified robot learning framework built on NVIDIA Isaac Sim, the de facto standard for large-scale simulated robot training and VLA development, with native support for all major commercial robot platforms.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,390 total: Industry-standard open-source physics simulator for contact-rich robotics, used across 90% of academic and industrial embodied AI research projects for fast, accurate dynamics modeling.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,856 total: Dataflow-oriented robotic middleware optimized for low-latency, composable AI robotic applications, enabling distributed deployment of VLA policies across heterogeneous hardware with minimal overhead.
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,345 total: Purpose-built reinforcement learning infrastructure for embodied and agentic AI, streamlining the end-to-end pipeline from VLA training to sim2real deployment.
- [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,267 total: GPU-accelerated physics simulation engine built on NVIDIA Warp, emerging as a lightweight, robotics-specific alternative to MuJoCo for large-scale parallel VLA training.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐125 total: Lean, ROS-free sim2real framework for VLA and RL agent deployment, with native support for Franka, UR5e, xArm, and Unitree SO101 robots, eliminating ROS latency bottlenecks for real-time control.
- [softmata/horus](https://github.com/softmata/horus) ⭐397 total: High-performance robotics runtime system positioned as an "Android for robots", providing a unified abstraction layer for hardware control, VLA inference, and skill management across diverse robot form factors.

---

### 🧠 VLA / Foundation Models
(Vision-language-action models, embodied foundation models, and training pipelines)
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,935 total: Hands-on zero-to-VLA educational course requiring only basic Python knowledge, walking developers through building OpenVLA, SmolVLA, and Pi0 models from scratch to demystify embodied intelligence for beginners.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐454 total: Chinese-language, practice-oriented VLA learning and interview handbook focused on robotics-specific challenges, filling a major gap in non-English VLA educational resources for algorithm engineers.
- [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) ⭐83 total: Official NVIDIA developer hub for the Alpamayo VLA foundation model, providing pre-built recipes for fine-tuning, RL post-training, quantization, and deployment of production-grade VLA policies.
- [phi-monster/Galahad](https://github.com/phi-monster/Galahad) ⭐102 total: Research project diagnosing instruction blindness in VLA policies, introducing a low-rank data cure and standardized measurement battery to improve the reliability of VLA policy execution on open-world tasks.
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐119 total: Open-world foundation model for general-purpose embodied intelligence, designed to unify perception, planning, and action across diverse robot platforms and task domains.
- [provael/provael](https://github.com/provael/provael) ⭐4 total: First dedicated open-source red-teaming framework for VLA robot policies, enabling automated testing of VLA robustness in simulation and standardized reporting of attack success rates.
- [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐2 total: Novel unified VLA framework for humanoid loco-manipulation, expanding VLA use cases beyond stationary robotic arms to full-body humanoid control in unstructured environments.

---

### 🦾 Manipulation & Grasping
(Dexterous manipulation, UMI, grasp generation, and task benchmarks)
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,180 total: Open-source GPU-parallelized robotics manipulation simulator and benchmark, supporting thousands of parallel environments for fast VLA training on contact-rich manipulation tasks.
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,785 total: Fully open-source humanoid arm designed for physical AI research and contact-rich manipulation tasks, providing a low-cost, customizable alternative to proprietary robotic arm hardware.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐96 total: Open-source evaluation framework for physical AI, enabling standardized testing of any LLM/VLA policy across any robotic arm or humanoid platform in both simulation and real-world settings.
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐42 total: Open-source software for synchronized bimanual UMI (Universal Manipulation Interface) data collection and retargeting, enabling teams to scale high-quality VLA training data across diverse robot platforms.
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8 total: Bimanual kitchen manipulation benchmark for VLA models, built on the Inspect Robots framework to test VLA performance on realistic, long-horizon household tasks.
- [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes) ⭐1 total: Novel implementation of the Pi0 flow-matching VLA that integrates collision avoidance directly into model weights via a differentiable safety loss, eliminating the need for separate runtime safety filters.
- [Archerkattri/actionshift](https://github.com/Archerkattri/actionshift) ⭐1 total: Benchmark testing VLA policy adaptation to hidden robot action interfaces, measuring the ability of pre-trained VLA policies to transfer across robots with different control wiring without retraining.

---

### 🚶 Locomotion & Navigation
(Legged robots, humanoid control, SLAM, and path planning)
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,269 total: The world's largest deployed open-source robotics operating system, currently powering advanced driver assistance systems on 300+ supported car models, serving as a blueprint for scalable embodied autonomy.
- [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,191 total: Definitive open-source textbook and Python code collection for robotics algorithms, covering locomotion, SLAM, path planning, and control for both mobile robots and humanoids.
- [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐351 total: State-of-the-art whole-body nonlinear MPC implementation for real-time humanoid loco-manipulation planning and control, enabling smooth, coordinated full-body movement for humanoid robots.
- [mturan33/isaac-g1-ulc](https://github.com/mturan33/isaac-g1-ulc) ⭐16 total: Open-source low-level RL controller for the Unitree G1 humanoid, providing an accessible baseline for teams developing custom locomotion policies for one of the most widely used commercial humanoid platforms.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,530 total: Standard ROS 2 navigation framework for mobile robots, supporting SLAM, path planning, and obstacle avoidance for ground robots in both indoor and outdoor environments.
- [zc-xzc/robot_platform](https://github.com/zc-xzc/robot_platform) ⭐3 total: Low-cost head-tracking active vision platform for humanoid robots, integrating PICO 4 VR headsets, D415 depth cameras, and 3D-printable mounts to enable affordable humanoid perception research.

---

### 📦 Embodied Applications
(End-to-end systems, teleoperation, sim2real deployments, and agent OS)
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,304 total: Self-evolving embodied AI operating system built on agentic workflows, enabling end-to-end orchestration of perception, planning, and skill learning for physical AI agents.
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,659 total: Official repository for ICML 2026 RoboTwin 2.0, a high-fidelity digital twin platform for robotics that accelerates sim2real transfer of VLA and locomotion policies.
- [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,603 total: Leading embodied AI research platform with 1,000+ standardized household tasks, providing a unified benchmark for testing generalist embodied agent performance.
- [ros-claw/rosclaw](https://github.com/ros-claw/rosclaw) ⭐175 total: Self-evolving runtime infrastructure for physical AI, including sandboxed safety controls, skill evolution mechanisms, and physical memory for embodied agents, designed to ground abstract AI agents into real robot hardware.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐141 total: Full-embodiment humanoid teleoperation system, enabling intuitive remote control of humanoid robots for data collection, disaster response, and remote manipulation tasks.
- [DexForce/EmbodiChain](https://github.com/DexForce/EmbodiChain) ⭐201 total: End-to-end GPU-accelerated modular platform for building generalized embodied intelligence, streamlining the pipeline from VLA training to real-world robot deployment.

---

## 3. Trend Signal Analysis
VLA democratization and humanoid-aligned embodied AI are seeing explosive community growth, driven by coordinated efforts from industry and academia to lower barriers to entry for previously niche technology. The surge of accessible educational resources—from zero-to-VLA build courses to dedicated practitioner handbooks and wheeled biped VLA curricula—indicates VLA is transitioning from exclusive research labs to mainstream developer adoption, mirroring the trajectory of LLMs in 2022–2023. A notable new direction is the shift toward intrinsic VLA safety and robustness, with projects integrating safety constraints directly into training pipelines rather than relying on post-hoc runtime filters, alongside the first dedicated red-teaming frameworks for open VLA policies. These developments align with recent industry milestones, including NVIDIA’s launch of the Alpamayo VLA foundation model and growing commercial investment in humanoid robotics from firms like Figure and Unitree. Additionally, the rise of lean, ROS-free sim2real deployment frameworks signals a broader shift toward VLA-optimized infrastructure that reduces latency overhead for real-time physical control, a critical requirement for real-world VLA deployment.

---

## 4. Community Hot Spots
- [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes): NVIDIA’s official tooling for its state-of-the-art Alpamayo VLA is the most impactful new release for developers building production physical AI systems, providing pre-built pipelines for customizing and deploying VLA policies without starting from scratch.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied): This hands-on zero-to-VLA course fills a critical gap in accessible embodied AI education, walking developers through building production VLA models with only basic Python knowledge, making it a must-use for early-career engineers and researchers entering the field.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): This cross-platform VLA evaluation framework solves a longstanding pain point of fragmented, inconsistent VLA testing workflows, and is positioned to become the community standard for benchmarking VLA policy performance across sim and real hardware.
- [enactic/openarm](https://github.com/enactic/openarm): This fully open-source, contact-rich humanoid arm provides a low-cost alternative to proprietary manipulation hardware, enabling small teams and academic labs to conduct physical VLA research without six-figure hardware investments.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*