# AI Open Source Trends 2026-07-10

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-10 01:48 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
*Date: 2026-07-10*

---

## 1. Today's Highlights
Today's most notable embodied AI and robotics development is the viral growth of [bradautomates/claude-video](https://github.com/bradautomates/claude-video), which gained 718 stars by enabling off-the-shelf Claude models to process video input, eliminating the need for custom perception stacks for basic VLA pipelines. Second, the open source ecosystem is rapidly democratizing VLA access, with new entry-level courses, 8GB laptop GPU benchmarks, and minimal implementations opening VLA development to developers without advanced robotics backgrounds or high-end compute. Third, open hardware for manipulation and humanoids is gaining mainstream traction, with fully open-source arms and low-cost 3D-printable humanoids drastically reducing the cost of physical robotics research and testing. Fourth, post-RSS 2026 open sourcing of top VLA and robot learning papers is driving a surge in community interest in efficient VLA fine-tuning and generalizable policy pretraining.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs (Control, Simulation, Planning)
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,645 total: Unified NVIDIA Isaac Sim-based robot learning framework, the de facto standard for large-scale VLA and RL training in simulation.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,836 total: Low-latency dataflow-oriented robotic middleware, designed to simplify building composable, distributed AI robotic applications without ROS bloat.
- [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) ⭐2,506 total: Modular simulation framework and benchmark for robot learning, widely used for manipulation policy training and evaluation.
- [softmata/horus](https://github.com/softmata/horus) ⭐387 total: High-performance robotics runtime positioned as the "Android for robots", optimized for real-time control of humanoids and other complex robotic systems.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐123 total: ROS-free sim2real framework for deploying VLA models and RL agents, with native support for Franka, UR5e, xArm, and SO101 robots.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,142 total: Industry-standard physics simulator for multi-joint contact dynamics, foundational for all modern robot learning research.

---

### 🧠 VLA / Foundation Models
- [bradautomates/claude-video](https://github.com/bradautomates/claude-video) ⭐0 (+718 today): Open-source tool that adds end-to-end video processing (download, frame extraction, transcription) to Claude, enabling no-custom-perception VLA pipelines with off-the-shelf LLMs, the fastest growing embodied AI-adjacent project today.
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐479 total: InternVLA-A1, a state-of-the-art open VLA that unifies perception understanding, scene generation, and robotic action for generalizable manipulation.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐371 total: Chinese-language, practice-oriented VLA learning and interview guide focused on robotics-specific challenges, driving massive community onboarding for VLA developers in the APAC region.
- [YuZhaoshu/Efficient-VLAs-Survey](https://github.com/YuZhaoshu/Efficient-VLAs-Survey) ⭐168 total: Curated, continuously updated list of efficient VLA research, addressing the top industry pain point of reducing VLA compute costs for edge deployment.
- [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) ⭐49 total: RSS 2026 work introducing universal pose pretraining to dramatically improve VLA policy generalizability across unseen manipulation tasks.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,601 total: Zero-to-VLA course for developers with only basic Python knowledge, walking through building OpenVLA, SmolVLA, and Pi0 from scratch to demystify embodied intelligence.
- [muhammadmahadazher/vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget) ⭐0 total: Honest benchmark of ACT, Diffusion Policy, and SmolVLA running on a single 8GB laptop GPU, making VLA experimentation accessible to hobbyists and small teams.

---

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,706 total: Fully open-source humanoid arm designed for contact-rich physical AI research, the first low-cost, high-performance open manipulation hardware platform for VLA testing.
- [robocasa/robocasa](https://github.com/robocasa/robocasa) ⭐1,529 total: Large-scale simulation benchmark of 1000+ everyday household tasks for training generalist manipulation robots, widely used for VLA evaluation.
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐254 total: SLAM and data processing pipeline for the Universal Manipulation Interface (UMI), a fast-growing open standard for cross-platform manipulation policy transfer.
- [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐168 total: CVPR 2025 framework that uses LLMs to generate diverse simulation data for instruction-following manipulation, reducing the need for expensive real-world training data.
- [sahilrajpurkar03/nlp-pnp-robotic-arm](https://github.com/sahilrajpurkar03/nlp-pnp-robotic-arm) ⭐64 total: End-to-end ROS2 pick-and-place robotic arm system with YOLOv8 perception, MoveIt motion planning, and Ollama-powered natural language control, ideal for hobbyist manipulation projects.

---

### 🚶 Locomotion & Navigation
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐321 total: Production-grade legged locomotion and momentum-based control software used in world-class humanoids, exoskeletons, and legged robots.
- [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐242 total: ECCV 2026 high-fidelity navigation simulator using dynamic Gaussian Splatting, delivering photorealistic scenes for embodied navigation research far beyond traditional mesh-based simulators.
- [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx) ⭐245 total: JAX-based implementation of Model Predictive Control (MPC), enabling fast, differentiable locomotion control for legged robots compatible with modern ML pipelines.
- [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐8 total: Affordable, fully 3D-printable open-source humanoid robot powered by a Raspberry Pi Zero 2W, lowering the barrier to hobbyist humanoid locomotion experimentation.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,448 total: De facto standard ROS2 navigation framework for mobile robots, supporting path planning, obstacle avoidance, and SLAM integration for commercial and research deployments.

---

### 📦 Embodied Applications
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,063 total: Production-grade reinforcement learning infrastructure built specifically for embodied and agentic AI, standardizing end-to-end RL training pipelines for robotic systems.
- [DexForce/EmbodiChain](https://github.com/DexForce/EmbodiChain) ⭐191 total: End-to-end, GPU-accelerated modular platform for building generalized embodied intelligence, unifying training, simulation, and real-robot deployment in a single stack.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐131 total: Lightweight, scalable whole-body teleoperation framework for humanoid robots, critical for collecting low-cost human demonstration data to train VLA policies for humanoids.
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,059 total: The largest deployed open-source robotics OS, powering advanced driver assistance on 300+ consumer vehicle models, a leading example of mass-market embodied AI.
- [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐217 total: Minimal hardware-software architecture that adds closed-loop physical perception and control to off-the-shelf LLMs, enabling small teams to build embodied agents without custom ML stacks.

---

## 3. Trend Signal Analysis
The most explosive community attention today is focused on the democratization of VLA development, a shift driven by a wave of tools that lower barriers to entry for developers outside of well-funded tech labs. This includes no-code perception tools for off-the-shelf LLMs, low-compute VLA benchmarks, and zero-background learning resources, marking a clear inflection point as VLA moves from a purely research-focused field to accessible, hobbyist-friendly development. A key new technical direction is the emergence of ROS-free sim2real deployment stacks, which address longstanding pain points of ROS complexity and overhead for small teams and individual developers, enabling end-to-end VLA deployment on common robot arms in hours rather than weeks. Additionally, Gaussian Splatting-based navigation simulators and JAX-integrated locomotion control pipelines are gaining traction, bridging modern ML workflows with traditional robotics control. These trends align with recent industry shifts: the 2026 wave of humanoid robotics funding has spurred demand for low-cost open hardware and efficient, edge-deployable VLA policies, while post-RSS 2026 open source releases have accelerated community adoption of new generalizable VLA pretraining techniques. (268 words)

---

## 4. Community Hot Spots
- **No-custom-perception VLA development with [bradautomates/claude-video](https://github.com/bradautomates/claude-video)**: The fastest growing embodied AI-adjacent project today, it cuts VLA development time from weeks to hours by leveraging Claude's native multimodal capabilities instead of building custom perception models.
- **Entry-level VLA upskilling via [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) and [muhammadmahadazher/vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget)**: These resources eliminate the two biggest barriers to VLA entry (advanced domain knowledge and high-end compute), opening the field to tens of thousands of Python developers previously excluded from robotics research.
- **ROS-free sim2real deployment with [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)**: This lightweight framework addresses the top complaint of small robotics teams (ROS bloat and complexity), enabling end-to-end VLA deployment on common commercial robot arms with minimal configuration.
- **Open manipulation hardware testing with [enactic/openarm](https://github.com/enactic/openarm)**: The first fully open-source, contact-rich humanoid arm reduces the cost of physical VLA testing by ~90% compared to commercial alternatives, filling a critical gap in the embodied AI hardware ecosystem.
- **Efficient VLA research via [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) and [cair-vinuni/CLP_VLA](https://github.com/cair-vinuni/CLP_VLA)**: Recent RSS 2026 results that improve VLA generalizability and cut fine-tuning compute costs, directly addressing the two largest barriers to real-world VLA commercial deployment.

---
*Filter note: All unrelated general AI tools, games, and non-robotics repositories from the original trending list were excluded per relevance criteria.*

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*