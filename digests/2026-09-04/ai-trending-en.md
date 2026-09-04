# AI Open Source Trends 2026-09-04

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-09-04 01:48 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
*Date: 2026-09-04 | Data Sources: GitHub Trending, GitHub Topic Search (robotics/embodied-AI/VLA)*

---

## 1. Today's Highlights
Today’s overall GitHub trending list is dominated by general-purpose AI coding agent tools and utility libraries, with no core embodied intelligence or robotics projects ranking in the top 19, while active topic-tagged repositories show steady, focused growth across VLA models, humanoid robotics, and simulation infrastructure. NVIDIA’s open-source Alpamayo VLA series for autonomous driving continues to drive community interest, with the 1.5 Nano variant adding RL-enhanced reasoning and VQA capabilities alongside the original 10B parameter reasoning VLA. The humanoid robotics ecosystem is expanding rapidly, with a cluster of new open-source tools from LimX Dynamics covering robot description models, MuJoCo simulation, and ROS 2 / C++ RL deployment pipelines for their HU series humanoids and TRON2 manipulation arms. New releases in manipulation-focused VLA and benchmarks—including PINE Lab’s FACET contact-rich manipulation foundation model and the LIBERO-Para paraphrase robustness benchmark for VLA—signal a shift toward evaluating real-world reliability and fine-grained task performance.

---

## 2. Top Projects by Category
*(Note: Today’s new star counts are unavailable for filtered projects, as none appeared in the overall GitHub top 19 trending list; all star counts are total repository stars.)*

### 🤖 Robot Frameworks / SDKs
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,912 total — Industry-standard multi-joint physics simulator with contact dynamics, serving as the foundational simulation backend for the majority of open-source robot learning and embodied AI projects.
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,036 total — Unified NVIDIA Isaac Sim-based framework for robot learning, with modular environments for manipulation, locomotion, and navigation that have become a de facto standard for sim-to-real research.
3. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,717 total — End-to-end reinforcement learning infrastructure purpose-built for embodied and agentic AI, streamlining training pipeline setup for robotics researchers and teams.
4. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,918 total — Rust-based dataflow-oriented robotic middleware that enables low-latency, composable, and distributed AI robotic application development, gaining traction as a lightweight alternative to ROS.
5. [baidu-baige/LoongForge](https://github.com/baidu-baige/LoongForge) ⭐549 total — High-performance training framework supporting LLMs, VLMs, diffusion models, and embodied models on both NVIDIA GPUs and Kunlun XPUs, addressing the need for cross-hardware embodied model training.
6. [softmata/horus](https://github.com/softmata/horus) ⭐432 total — Rust-based high-speed robotics runtime system positioned as an "Android for robots," providing a unified execution layer for heterogeneous robot hardware and AI models.
7. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐155 total — Lean, ROS-free sim-to-real framework for training and deploying VLA models and RL agents, with native support for popular robot arms including Franka, UR5e, and xArm.

### 🧠 VLA / Foundation Models
1. [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐2,014 total — NVIDIA’s open-source 10B parameter reasoning VLA model for autonomous vehicles, which pairs driving trajectory output with Chain-of-Causation reasoning to improve interpretability and safety.
2. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐467 total — Open-world foundation model for general-purpose embodied intelligence, designed to support cross-embodiment control across different robot platforms and task domains.
3. [NVlabs/alpamayo1.5](https://github.com/NVlabs/alpamayo1.5) ⭐362 total — Updated iteration of NVIDIA’s Alpamayo VLA, featuring RL-enhanced reasoning, navigation guidance, and visual question answering capabilities for autonomous driving use cases.
4. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐201 total — Open-source evaluation framework for physical AI that enables testing any LLM/VLA model on any arm or humanoid robot across both real and simulated benchmarks, addressing a critical gap in VLA validation.
5. [starVLA/VLAct](https://github.com/starVLA/VLAct) ⭐95 total — VLA model focused on representation-centric continued pre-training (instead of pure data scaling) to improve performance, offering a new paradigm for efficient VLA development.
6. [cau-hai-lab/LIBERO-Para](https://github.com/cau-hai-lab/LIBERO-Para) ⭐44 total — EMNLP 2026 accepted diagnostic benchmark and metrics for measuring paraphrase robustness in VLA models, addressing the critical issue of language instruction variability in real-world deployment.
7. [PINE-Lab-NTU/FACET](https://github.com/PINE-Lab-NTU/FACET) ⭐11 total — Newly released (arXiv 2609.01596) robotic foundation model for contact-rich precise manipulation, targeting high-accuracy industrial and service robot tasks.
8. [UARK-AICV/DRAGON_VLA](https://github.com/UARK-AICV/DRAGON_VLA) ⭐14 total — Clutter-resistant VLA model that uses object-centric and geometry grounding to maintain performance in cluttered real-world environments, a common pain point for current VLA systems.

### 🦾 Manipulation & Grasping
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,920 total — Fully open-source humanoid arm designed for physical AI research and deployment in contact-rich environments, providing a low-cost, accessible hardware platform for manipulation research.
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐471 total — Official repository for the RoboDojo manipulation benchmark, a standardized test suite for evaluating generalizable robot manipulation skills.
3. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐175 total — CVPR 2025 accepted work implementing an LLM-driven simulation pipeline for generalizable instruction-following manipulation, reducing the need for expensive real-world training data.
4. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐68 total — Open-source software for synchronized bimanual data collection and retargeting to any dual-arm robot, supporting calibration, quality assurance, and teleoperation replay for high-quality manipulation datasets.
5. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐25 total — Deployment-focused fork of OpenPI for LimX’s TRON2 manipulation arm, including pi0.5 policy serving, task fine-tuning, and real-robot client examples for rapid manipulation deployment.
6. [limxdynamics/TRON2_YG_LAB](https://github.com/limxdynamics/TRON2_YG_LAB) ⭐3 total — Isaac Lab RL training stack for the TRON2A 6-DoF arm and gripper, built for the ATEC challenge with PPO-based policy training for arm-gripper coordination.
7. [PieroJF/Robot-qarm-fruit-sorting](https://github.com/PieroJF/Robot-qarm-fruit-sorting) ⭐4 total — Practical implementation of autonomous fruit sorting using a Quanser QArm 4-DOF arm and Intel RealSense camera, serving as an accessible educational reference for applied manipulation projects.

### 🚶 Locomotion & Navigation
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,565 total — Open-source robotics operating system for driver assistance, currently supporting 300+ car models and serving as one of the most widely deployed open-source autonomous navigation systems.
2. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,437 total — Comprehensive collection of Python sample code and textbook references for robotics algorithms, including locomotion, path planning, SLAM, and navigation, used globally by students and researchers.
3. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,803 total — Mature open-source flight and rover control system supporting planes, copters, rovers, and submersibles, serving as the de facto firmware for DIY and commercial drone/ground robot navigation.
4. [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) ⭐5,251 total — Open-source quadruped robot pet framework for developing Boston Dynamics-style four-legged robots, widely used for STEM education, IoT robotics, and AI-enhanced robotics research.
5. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325 total — Robotics software suite featuring state-of-the-art legged locomotion algorithms and momentum-based control, used to power world-class humanoid, exoskeleton, and running bird robots.
6. [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx) ⭐273 total — JAX-based implementation of Model Predictive Control (MPC) for legged robots and humanoids, enabling fast, differentiable control policy development for locomotion tasks.
7. [Open-X-Humanoid/BICMap](https://github.com/Open-X-Humanoid/BICMap) ⭐45 total — WebGL-based robotics map visualization SDK for SLAM maps, point clouds, 3D models, and robot navigation, providing a browser-based tool for debugging and monitoring navigation systems.

### 📦 Embodied Applications
1. [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover) ⭐9,626 total — Build-it-yourself 6-wheel rover based on NASA’s Mars rover design, providing a fully open-source hardware and software platform for applied embodied robotics research and education.
2. [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) ⭐6,697 total — Open-source project to upgrade cheap off-the-shelf robotic mowers to smart RTK GPS-based lawn mowing robots, demonstrating accessible sim-to-real deployment for consumer robotics.
3. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,808 total — ICML 2026 accepted official repository for RoboTwin 2.0, a digital twin platform that bridges simulation and real-world deployment for embodied AI training and testing.
4. [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core) ⭐2,024 total — Recursive Self-Improving (RSI) physical agent operating system that enables embodied agents to iteratively improve their capabilities through agentic workflows, a novel approach to adaptive physical AI.
5. [robocasa/robocasa](https://github.com/robocasa/robocasa) ⭐1,701 total — Large-scale simulation environment for everyday humanoid robot tasks, providing 1000+ household manipulation and navigation scenarios for training generalist embodied agents.
6. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,678 total — Stanford’s widely used embodied AI research platform with 1000+ realistic household tasks, designed to benchmark and accelerate progress in generalist embodied agent development.
7. [iit-DLSLab/locomanipulation-teleop-isaaclab](https://github.com/iit-DLSLab/locomanipulation-teleop-isaaclab) ⭐25 total — IsaacLab DirectEnv implementation for teleoperation of a Unitree Go2 legged robot paired with an AgileX Piper arm, supporting both sim-to-sim and sim-to-real pipelines for integrated loco-manipulation tasks.
8. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐55 total — Digital twin platform for robotics-assisted chemistry lab automation, representing a fast-growing vertical application of embodied AI for scientific research and lab automation.

---

## 3. Trend Signal Analysis
The embodied AI and robotics open-source ecosystem is currently seeing the most concentrated growth in two areas: humanoid robot developer tooling and VLA model robustness for real-world deployment. A notable cluster of newly active repositories from LimX Dynamics—spanning humanoid URDF/MJCF models, MuJoCo simulation environments, and ROS 2/C++ RL deployment pipelines—reflects a broader trend of humanoid hardware vendors open-sourcing full software stacks to cultivate third-party developer ecosystems, echoing the early smartphone platform wars of the 2010s.

VLA development is clearly shifting from capability demos to production-readiness: newly released projects target longstanding pain points including paraphrase robustness (LIBERO-Para), cluttered environment performance (DRAGON_VLA), and contact-rich manipulation precision (FACET). This shift aligns with recent industry pushback against VLA models that fail in unstructured real-world settings, driving demand for standardized evaluation frameworks like robocurve/inspect-robots.

Additionally, the emergence of purpose-built robotics runtime systems (softmata/horus) and lightweight AI-native middleware (dora-rs) signals a growing gap between legacy robotics infrastructure (e.g., ROS) and the needs of AI-first robotic systems. This trend is reinforced by ICML 2026 and ICRA 2026 paper releases, which prioritize sim-to-real transfer and cross-embodiment VLA architectures as critical research priorities. (Word count: 287)

---

## 4. Community Hot Spots
- **LimX Dynamics Humanoid Open-Source Toolchain**: The full stack of LimX humanoid and TRON2 arm repositories (model descriptions, simulation, RL deployment) is a high-priority focus for developers building on commercial humanoid hardware, as it provides a standardized, production-ready baseline for sim-to-real work.
- **VLA Evaluation & Robustness Tooling**: Projects like [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) and [cau-hai-lab/LIBERO-Para](https://github.com/cau-hai-lab/LIBERO-Para) address a critical unmet need for standardized VLA testing, making them likely to see rapid star growth as more teams shift from model training to real-world validation.
- **AI-Native Robotics Middleware**: [dora-rs/dora](https://github.com/dora-rs/dora) and [softmata/horus](https://github.com/softmata/horus) represent a new generation of robotics infrastructure built specifically for AI-first systems, offering lower latency and simpler integration than ROS for VLA and embodied agent deployments.
- **Contact-Rich Manipulation Foundation Models**: The newly released [PINE-Lab-NTU/FACET](https://github.com/PINE-Lab-NTU/FACET) model targets high-precision, contact-heavy tasks that current VLA models struggle with, positioning it as a key project to watch for industrial robotics and assembly use cases.
- **Digital Twin for Vertical Embodied Applications**: [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) (lab automation) and [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) (general digital twin) highlight the fast-growing adoption of digital twin technology to reduce the sim-to-real gap in vertical robotics use cases.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*