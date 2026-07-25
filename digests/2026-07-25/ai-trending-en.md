# AI Open Source Trends 2026-07-25

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-25 01:29 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report | 2026-07-25
---

## 1. Today's Highlights
Today’s embodied AI and robotics ecosystem saw explosive traction across open VLA models, accessible humanoid hardware, and novel perception tools. NVIDIA’s open-source Alpamayo VLA series for autonomous driving dominates active VLA development, with a full stack of base models, RL-enhanced updates, and developer fine-tuning recipes available to the community. A new lightweight Mamba-based VLA, SUREFlow (179M parameters), was released ahead of IROS 2026, demonstrating growing interest in small, edge-deployable VLA architectures for real-world robotics. Open-source physical hardware also gained significant attention, with the fully open humanoid arm OpenArm and 3D-printable Microban humanoid lowering barriers to physical AI research for independent developers. WiFi-based spatial sensing tool RuView went viral with 1,022 new stars today, offering a privacy-preserving, camera-free alternative for embodied perception and presence detection.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab): ⭐7,759 total | Unified robot learning framework built on NVIDIA Isaac Sim, the de facto standard for high-fidelity simulation and sim-to-real transfer for VLA and RL policy training.
- [dora-rs/dora](https://github.com/dora-rs/dora): ⭐3,853 total | Rust-based dataflow-oriented robotic middleware designed for low-latency, composable AI robotic applications, emerging as a lightweight alternative to ROS for edge embodied systems.
- [RLinf/RLinf](https://github.com/RLinf/RLinf): ⭐4,243 total | End-to-end reinforcement learning infrastructure purpose-built for embodied and agentic AI, streamlining policy training, evaluation, and deployment workflows.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco): ⭐14,315 total | Industry-standard open-source physics simulator for contact-rich robotic tasks, powering nearly all modern manipulation and locomotion policy training pipelines.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): ⭐36 total | New evaluation framework for VLA and physical AI models, enabling users to define a single benchmark and run it across any robot or simulation environment, addressing a critical gap in standardized VLA testing.
- [softmata/horus](https://github.com/softmata/horus): ⭐392 total | Rust-based high-performance robotics runtime system, positioned as a purpose-built "Android for robots" to unify low-level control across heterogeneous robotic hardware.

---

### 🧠 VLA / Foundation Models
- [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo): ⭐1,933 total | NVIDIA’s open 10B parameter reasoning VLA for autonomous vehicles, which pairs driving trajectories with Chain-of-Causation reasoning to enable interpretable embodied decision-making.
- [NVlabs/alpamayo1.5](https://github.com/NVlabs/alpamayo1.5): ⭐341 total | Updated iteration of Alpamayo with RL-enhanced reasoning, navigation guidance, and visual question answering capabilities, expanding the model’s utility for complex real-world autonomous systems.
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series): ⭐510 total | InternVLA-A1, a unified foundation model that integrates visual understanding, content generation, and action prediction for general-purpose robotic manipulation.
- [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026): ⭐7 total | New lightweight Mamba-based VLA with only 179M parameters for robot manipulation, accepted to IROS 2026, demonstrating a shift toward small, efficient VLA architectures for edge deployment.
- [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion): ⭐598 total | Foundation model for whole-body humanoid control, unifying locomotion and manipulation policy learning for generalist humanoid robots.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook): ⭐430 total | All-Chinese, practice-oriented learning and interview handbook for VLA engineers, focused on robotics-specific challenges absent from general CV/NLP resources, filling a critical educational gap for new practitioners.

---

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm): ⭐2,762 total | Fully open-source humanoid robotic arm designed for contact-rich physical AI research and deployment, with standardized interfaces for VLA policy integration.
- [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy): ⭐84 total | Framework that compiles natural language instructions into verified, typed robot skill graphs, executable on both simulators and real manipulators, enabling reliable, verifiable language-driven manipulation.
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench): ⭐8 total | New bimanual kitchen manipulation benchmark purpose-built for VLA model evaluation, part of the WorldEvals initiative to standardize real-world embodied task testing.
- [Shahwar0997/detect-plan-grasp](https://github.com/Shahwar0997/detect-plan-grasp): ⭐3 total | End-to-end open-source pipeline for language-driven robotic manipulation, combining INT8 YOLO perception, local LLMs, and from-scratch 6-DOF inverse kinematics in the MuJoCo simulator, accessible to beginners.
- [LFGfg/TransDex](https://github.com/LFGfg/TransDex): ⭐8 total | Novel 3D visuo-tactile fusion motor policy for dexterous manipulation, leveraging point cloud reconstruction pre-training to improve grasp reliability in contact-rich tasks.

---

### 🚶 Locomotion & Navigation
- [commaai/openpilot](https://github.com/commaai/openpilot): ⭐63,207 total | Open-source robotics operating system currently deployed as an advanced driver assistance system for 300+ supported consumer vehicles, the most widely adopted embodied navigation system in consumer use.
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D): ⭐259 total | Open-source UMI-3D SLAM and data processing pipeline, enabling high-accuracy 3D scene perception for embodied navigation and manipulation tasks.
- [Rhoban/microban](https://github.com/Rhoban/microban): ⭐44 total | Affordable, fully 3D-printable open-source humanoid robot powered by a Raspberry Pi Zero 2W, lowering barriers to legged locomotion research and hobbyist experimentation.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2): ⭐4,504 total | Industry-standard ROS 2 navigation framework, powering autonomous path planning and obstacle avoidance for most mobile and legged robotic systems.
- [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG): ⭐96 total | Omni-Modal Motion Generation foundation model for generalist humanoid control, enabling whole-body locomotion and manipulation action generation from multi-modal inputs.

---

### 📦 Embodied Applications & Tools
- [ruvnet/RuView](https://github.com/ruvnet/RuView): ⭐0 total / +1022 today | Viral open-source tool that converts commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection without any camera input, offering a privacy-preserving perception alternative for embodied systems.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied): ⭐2,851 total | Beginner-friendly Chinese educational course that teaches users to build a full embodied intelligent robot from scratch with only basic Python knowledge, including step-by-step implementations of VLA models like OpenVLA and SmolVLA.
- [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K): ⭐1,596 total | Leading embodied AI research platform with 1,000+ realistic household tasks, widely used for benchmarking generalist embodied agent performance across perception, planning, and action.
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS): ⭐1,045 total | Self-evolving embodied AI operating system built on agentic workflows, designed to manage heterogeneous robotic hardware and continuously improve task performance via runtime learning.
- [philfung/awesome-reliable-robotics](https://github.com/philfung/awesome-reliable-robotics): ⭐159 total | Curated, continuously updated list of robotics research demonstrating real-world reliability and robustness, addressing a key gap between lab simulation and deployed embodied systems.

---

## 3. Trend Signal Analysis
The most explosive community attention today is concentrated on small, edge-deployable VLA architectures and accessible open physical robotics hardware, marking a clear shift from the 2024-2025 focus on large, generalist VLA foundation models to deployable, cost-effective embodied systems. The release of SUREFlow, a 179M Mamba-based VLA for manipulation, signals growing demand for lightweight models that can run on edge robot hardware without cloud connectivity, aligning with recent ICRA 2026 industry panels emphasizing real-world VLA deployment over lab-only performance.

NVIDIA’s full-stack Alpamayo VLA release for autonomous driving demonstrates a new industry direction for domain-specialized VLAs, moving beyond generic manipulation models to use cases with clear commercial paths. This aligns with NVIDIA’s GTC 2026 announcement of $10B in investment for physical AI infrastructure. A third critical trend is the rapid growth of standardized VLA evaluation tools and open educational resources, indicating the VLA field is maturing from ad-hoc model development to a structured ecosystem with shared benchmarks and a rapidly expanding developer base.

---

## 4. Community Hot Spots
- [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026): This lightweight Mamba-based VLA represents the next generation of edge-deployable embodied models, and its open-source release ahead of IROS 2026 makes it a prime target for developers building low-power manipulators and mobile robots.
- [softmata/horus](https://github.com/softmata/horus): Positioned as a unified runtime for all robots, this Rust-based robotics OS addresses a critical unmet need for standardized low-level control across heterogeneous hardware, filling a gap between ROS and proprietary robot firmware.
- [ruvnet/RuView](https://github.com/ruvnet/RuView): Camera-free WiFi-based spatial perception solves a key privacy pain point for embodied systems deployed in homes and public spaces, with clear commercial applications for security, elder care, and residential robots.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): Standardized VLA evaluation is the biggest bottleneck to field deployment right now, and this framework’s ability to run cross-robot, cross-sim benchmarks makes it a high-impact tool for both researchers and commercial robotics teams.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied): This beginner-friendly, hands-on embodied AI course is rapidly expanding the global VLA developer base, making it an essential resource for teams looking to upskill engineers new to physical AI.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*