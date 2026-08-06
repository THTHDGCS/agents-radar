# AI Open Source Trends 2026-08-06

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-06 01:23 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-08-06

---

## 1. Today's Highlights
Today’s embodied AI and robotics ecosystem saw explosive growth in production-grade agent infrastructure, with four agent-focused tools accumulating over 3,400 combined new GitHub stars in a single day. NVIDIA’s full Alpamayo VLA suite emerged as the leading open VLA stack for vertical commercial use cases, with dedicated models, fine-tuning recipes, and scaling plans for autonomous driving. Open-source humanoid and manipulation hardware also gained significant traction, with the fully open OpenArm humanoid arm hitting 2.8k total stars as the community prioritizes low-cost, accessible research platforms. Low-cost VLA inference also broke new ground, with AirLLM demonstrating 70B parameter model runs on a single 4GB GPU, unlocking edge deployment for small robotics teams that previously lacked access to high-end compute.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,867 total: Low-latency, dataflow-oriented robotic middleware designed to streamline building AI-powered robotic applications, with composable, distributed pipeline support ideal for VLA deployment.
- [softmata/horus](https://github.com/softmata/horus) ⭐406 total: Rust-based high-performance robotics runtime system, billed as the "Android for robots", optimized for low-latency control of humanoids and manipulators.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐128 total: Open-source evaluation framework for physical AI, enabling testing of any LLM/VLA on any arm/humanoid across sim/real benchmarks, filling a critical gap in standardized VLA testing.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐127 total: ROS-free sim2real framework for training and deploying VLA and RL agents, with native MuJoCo wrappers for common manipulators like Franka, UR5e, and xArm.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,843 total: Unified industry-standard framework for robot learning built on NVIDIA Isaac Sim, widely used for VLA policy training and sim2real transfer.

---

### 🧠 VLA / Foundation Models
- [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐1,968 total: Open 10B reasoning VLA model for autonomous vehicles, pairing driving trajectories with Chain-of-Causation reasoning to improve interpretability and task performance.
- [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) ⭐194 total: Official implementation of BridgeVLA and BridgeVLA++, state-of-the-art general-purpose VLA models for cross-domain robotic manipulation.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐473 total: Chinese-language, practical learning and interview manual for VLA engineers, focused on robotics-specific VLA challenges rather than general CV/NLP, filling a major educational gap.
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐133 total: Open-world foundation model for general-purpose embodied intelligence, designed for cross-task transfer across different robot platforms and environments.
- [lyogavin/airllm](https://github.com/lyogavin/airllm) ⭐0 total +833 today: Lightweight inference framework that runs 70B parameter models on a single 4GB GPU, enabling state-of-the-art VLA deployment on low-cost edge robot hardware.

---

### 🦾 Manipulation & Grasping
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,204 total: GPU-parallelized robotics manipulation simulator and benchmark suite, widely used for scalable VLA policy training for contact-rich tasks.
- [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐98 total: Framework that compiles natural language instructions into verified robot skill graphs, enabling reliable execution of high-level user commands on sim or real manipulators.
- [Enoch208/Crux](https://github.com/Enoch208/Crux) ⭐0 total: End-to-end framework for failure discovery, repair, and statistical qualification for contact-rich manipulation, running on a single consumer AMD GPU with tamper-evident validation bundles.
- [zcy13/cofree-arm](https://github.com/zcy13/cofree-arm) ⭐0 total: No-fine-tuning desktop manipulation pipeline that uses multimodal models for semantic reasoning and geometric control for numerical planning, with a per-task cost of only ¥0.2.
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8 total: New bimanual kitchen manipulation benchmark for VLA models, built on Inspect Robots as part of the WorldEvals evaluation suite for real-world task testing.

---

### 🚶 Locomotion & Navigation
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,339 total: Open-source robotics operating system powering advanced driver assistance for 300+ supported car models, the largest real-world deployment of embodied locomotion intelligence to date.
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,814 total: Fully open-source humanoid arm optimized for contact-rich physical AI research and deployment, with full ROS 2 and vision integration.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐154 total: Full-embodiment humanoid teleoperation system, enabling high-quality data collection for training locomotion and manipulation policies for humanoid robots.
- [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) ⭐38 total: Official codebase for the RoboNaldo humanoid soccer shooting system, demonstrating accurate, stable dynamic locomotion and force control for complex dynamic tasks.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,556 total: Industry-standard ROS 2 navigation framework for mobile robots, including SLAM, path planning, and obstacle avoidance capabilities.

---

### 📦 Embodied Applications
- [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) ⭐0 total +1,892 today: Team-level shared memory hub for AI agents, converting conversations, docs, and code into four governed, reusable memory assets (Chat Memory, Skill, LLM-Wiki, Code-Graph) for cross-agent use.
- [Uber/ADR](https://github.com/uber/ADR) ⭐0 total +354 today: Production enterprise AI agent security platform with observability, security benchmarking, and threat detection, deployed at scale for Uber's internal agent fleet, addressing critical safety gaps for embodied agents.
- [huangruiteng/loopx](https://github.com/huangruiteng/loopx) ⭐0 total +326 today: Lightweight agent loop state kernel for long-running AI agent teams, agnostic to agent backends, with durable goals, quota-aware auto-wake, and verifiable handoffs ideal for persistent embodied robot teams.
- [cloudflare/computer](https://github.com/cloudflare/computer) ⭐0 total +891 today: Framework that gives AI agents controlled, secure access to computing resources, enabling embodied agents to offload computation and interact with digital systems as part of physical task execution.
- [roboflow/supervision](https://github.com/roboflow/supervision) ⭐0 total +146 today: Reusable, production-grade computer vision toolset for robotic perception, widely integrated into VLA perception pipelines for real-world robot deployments.

---

## 3. Trend Signal Analysis
The most explosive community attention today is focused on production infrastructure for embodied agent teams, a previously underserved segment of the robotics stack. Four agent tools (TencentDB Agent Memory, Uber ADR, LoopX, Cloudflare Computer) accumulated over 3,400 new stars in a single day, signaling a clear field shift from VLA model development to scalable, secure, long-term agent deployment for physical robots. A notable new technical direction is vertical-domain VLA specialization: NVIDIA’s full Alpamayo suite (1, 1.5, 2, developer recipes) is the first open VLA stack purpose-built for autonomous driving, with integrated Chain-of-Causation reasoning and reinforcement learning post-training, aligning with recent industry announcements from AV developers integrating VLA into production stacks. Low-resource VLA inference (AirLLM’s 70B run on 4GB GPUs) also emerged as a critical new enabler, removing the high hardware barrier that previously restricted state-of-the-art VLA use to well-funded labs. This trend aligns with ICML 2026 presentations highlighting sim2real deployment and edge robotics as the next major bottlenecks for embodied intelligence commercialization.

---

## 4. Community Hot Spots
- [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory): Earned 1,892 new stars today as the first production-grade shared memory hub for cross-agent knowledge sharing, solving a core bottleneck for scaling embodied robot fleets with consistent, governed memory assets.
- **NVlabs Alpamayo Suite**: The first open VLA stack purpose-built for autonomous driving, including 10B and 34B model variants and production fine-tuning recipes, signals VLA is moving out of lab manipulation to large-scale commercial verticals.
- [lyogavin/airllm](https://github.com/lyogavin/airllm): Gained 833 new stars today for enabling 70B parameter model inference on a single 4GB GPU, eliminating the high hardware barrier for small teams to deploy state-of-the-art VLAs on edge robot hardware.
- [enactic/openarm](https://github.com/enactic/openarm): Hit 2,814 total stars as a fully open-source humanoid arm optimized for contact-rich tasks, lowering the cost barrier for VLA manipulation research without relying on $10k+ proprietary robotic arms.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*