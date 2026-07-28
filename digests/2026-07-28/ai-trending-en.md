# AI Open Source Trends 2026-07-28

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-28 01:25 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-07-28

---

## 1. Today's Highlights
Today's general GitHub trending list featured no core embodied intelligence, VLA, or robotics projects, with all key community activity coming from topic-tagged projects active in the past 7 days. Democratized access to VLA technology is the biggest community trend this cycle, with a beginner-friendly zero-to-VLA educational course and fully open-source humanoid manipulator each amassing over 2.7k stars, signaling a shift of VLA development from exclusive industrial labs to mainstream developers. NVIDIA's Alpamayo series of domain-specific VLAs for autonomous driving remains the highest-starred dedicated VLA model, with its 1.5 update gaining traction this week for its RL-enhanced causal reasoning capabilities. Ahead of IROS 2026, new research directions including lightweight edge VLA architectures and safety-baked VLA training pipelines are emerging, alongside a wave of new standardization tools for cross-platform VLA evaluation.

---

## 2. Top Projects by Category
All star counts are total GitHub stars unless noted; no core robotics/embodied AI projects appeared on today's real-time trending list.

### 🤖 Robot Frameworks / SDKs
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,240 total | Open-source operating system for robotics, currently deployed as an advanced driver assistance system for 300+ supported consumer vehicles, remains the highest-starred active robotics project on GitHub.
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,854 total | Rust-based dataflow-oriented robotic middleware designed for low-latency, composable AI robotic applications, gaining traction as a lightweight alternative to ROS for edge embodied deployments.
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,350 total | Industry-standard general-purpose physics simulator for multi-joint contact dynamics, the de facto foundation for most open-source robot learning and VLA training pipelines.
4. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,786 total | Unified NVIDIA Isaac Sim-based framework for robot learning, increasingly the preferred simulation stack for scaling VLA pre-training and sim-to-real transfer.
5. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,160 total | Self-evolving embodied AI operating system built on agentic workflows, one of the first dedicated OS projects targeting generalist physical AI deployments.
6. [softmata/horus](https://github.com/softmata/horus) ⭐393 total | High-performance robotics runtime system positioned as the "Android for robots," designed to standardize low-level control across heterogeneous robot hardware platforms.

### 🧠 VLA / Foundation Models
1. [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐1,943 total | NVIDIA's open 10B parameter reasoning VLA model for autonomous vehicles, which pairs driving trajectories with Chain-of-Causation reasoning, the highest-starred dedicated VLA model in active development.
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,894 total | Open educational project that teaches developers with only basic Python knowledge to build VLA models (including OpenVLA, SmolVLA, and Pi0) from scratch, driving massive community onboarding to embodied AI.
3. [NVlabs/alpamayo1.5](https://github.com/NVlabs/alpamayo1.5) ⭐344 total | Updated iteration of NVIDIA's Alpamayo VLA with RL-enhanced reasoning, navigation guidance, and visual question answering capabilities, gaining traction this week for its improved AV reasoning performance.
4. [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐7 total | Newly released IROS 2026 paper implementation: a lightweight Mamba-based VLA with only 179M parameters for robot manipulation, demonstrating strong performance for edge robot deployments.
5. [phi-monster/Galahad](https://github.com/phi-monster/Galahad) ⭐70 total | Research project diagnosing instruction blindness in VLA policies, introducing a low-rank data cure that addresses a key failure mode for generalist embodied agents.
6. [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes) ⭐1 total | Novel VLA training pipeline that bakes collision avoidance into model weights via a differentiable safety loss, eliminating the need for separate runtime safety filters.

### 🦾 Manipulation & Grasping
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,772 total | Fully open-source humanoid arm designed for contact-rich physical AI research and deployment, the highest-starred open manipulator hardware project, driving accessible VLA deployment on physical hardware.
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐308 total | New official manipulation benchmark repository, designed to standardize evaluation of VLA and RL policies for generalist robot manipulation tasks.
3. [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8 total | Bimanual kitchen manipulation benchmark for VLA models built on Inspect Robots, filling a gap in contact-rich, real-world domestic task evaluation for embodied agents.
4. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐42 total | Open-source software for synchronized bimanual manipulation data collection and retargeting to any bimanual robot, lowering barriers to building custom VLA manipulation datasets.
5. [LFGfg/TransDex](https://github.com/LFGfg/TransDex) ⭐8 total | Novel 3D visuo-tactile fusion motor policy for dexterous manipulation, leveraging point cloud reconstruction pre-training to improve performance on contact-rich tasks.
6. [shritankomm/7-DOF-3DP-Open-Arm](https://github.com/shritankomm/7-DOF-3DP-Open-Arm) ⭐1 total | Low-cost ($<800) 3D-printable 7-DOF humanoid robotic arm with ROS2 support, making dexterous manipulation hardware accessible to hobbyists and small research labs.

### 🚶 Locomotion & Navigation
1. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,517 total | Production-grade ROS 2 navigation framework and system, the de facto standard for autonomous path planning and navigation in mobile robots.
2. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐95 total | Official implementation of Omni-Modal Motion Generation for generalist humanoid control, a state-of-the-art approach for cross-modal humanoid locomotion and manipulation planning.
3. [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐351 total | Whole-body nonlinear model predictive control (MPC) pipeline for real-time humanoid loco-manipulation planning and control, widely adopted for high-performance humanoid control.
4. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐322 total | Mature open-source robotics software stack with state-of-the-art legged locomotion algorithms and momentum-based control, used in leading humanoid and exoskeleton platforms.
5. [mturan33/isaac-g1-ulc](https://github.com/mturan33/isaac-g1-ulc) ⭐16 total | Low-level RL controller for the Unitree G1 humanoid robot, demonstrating end-to-end learned locomotion control for commercial humanoid platforms.
6. [Yhx888/LocoVLA](https://github.com/Yhx888/LocoVLA) ⭐4 total | Open 58-lesson course teaching robot control, RL, and VLA for the Upkie wheeled biped robot, filling a gap in educational resources for legged embodied AI.

### 📦 Embodied Applications & Benchmarks
1. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,636 total | Official ICML 2026 repository for RoboTwin 2.0, a digital twin platform for embodied AI that enables high-fidelity sim-to-real transfer for robot learning.
2. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,598 total | Stanford's leading platform for accelerating embodied AI research, with 1,000+ realistic household tasks for evaluating generalist embodied agents.
3. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐89 total | Open-source evaluation framework for physical AI that allows running any LLM/VLA on any arm or humanoid against any real or simulated benchmark, standardizing VLA evaluation across platforms.
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐139 total | Lightweight, scalable whole-body teleoperation framework for humanoid robots, lowering barriers to collecting high-quality human demonstration data for VLA training.
5. [provael/provael](https://github.com/provael/provael) ⭐5 total | First dedicated red-teaming tool for open VLA policies, which calculates Attack Success Rate (ASR) for adversarial inputs in simulation to test VLA safety.
6. [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8 total | Deployed VLA agent that controls a FrodoBots Earth Rover Mini+ via natural language, demonstrating end-to-end VLA deployment on low-cost mobile robotic hardware.

---

## 3. Trend Signal Analysis
The most explosive community attention this cycle is centered on democratized VLA access and open embodied hardware, as evidenced by 2.8k stars for the *every-embodied* zero-to-VLA educational course and 2.7k stars for the fully open-source OpenArm manipulator. This signals a clear shift from VLA development being limited to well-resourced industrial labs to a mainstream, accessible technology for independent developers and small research teams. Two notable new technical directions have emerged this week: first, lightweight Mamba-based VLA architectures (such as the 179M parameter SUREFlow, accepted to IROS 2026) that deliver competitive manipulation performance at a fraction of the parameter count of models like OpenVLA, targeting edge robot deployments. Second, safety-baked VLA training pipelines (like LeRobot-SafetyCubes) that integrate differentiable safety loss directly into model training, eliminating the need for separate runtime collision filters that can degrade policy performance. These trends align with recent industry momentum around VLA standardization, including NVIDIA's open release of the Alpamayo VLA series for autonomous vehicles and upcoming IROS 2026 tracks focused on embodied AI evaluation. The rapid growth of cross-platform VLA evaluation tools also reflects a community push to establish consistent performance metrics for physical AI, a longstanding barrier to commercial deployment.

---

## 4. Community Hot Spots
- **[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) VLA education**: With nearly 3k stars, this project is driving massive new developer onboarding to embodied AI, making it a high-impact entry point for teams looking to build or upskill VLA engineering teams.
- **Lightweight edge VLA architectures (e.g., [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026))**: As commercial robotics deployments prioritize low-power edge compute, small-footprint Mamba-based VLAs will become a critical area of research and product development in the next 12 months.
- **[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) cross-platform VLA evaluation**: Standardized evaluation is the biggest bottleneck to VLA commercialization, making this agnostic benchmark framework a key tool for researchers and vendors testing generalist robot policies.
- **[enactic/openarm](https://github.com/enactic/openarm) open manipulator hardware**: Low-cost, open-source manipulation hardware removes the largest barrier to physical VLA deployment, making this project a core enabler for the long tail of small-batch embodied AI use cases.
- **VLA safety tooling (e.g., [provael/provael](https://github.com/provael/provael), [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes))**: As VLA policies move from lab to real-world deployment, safety testing and guardrails will be a mandatory requirement, making early safety tooling projects high-value to follow.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*