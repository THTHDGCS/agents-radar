# AI Open Source Trends 2026-08-03

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-03 01:45 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-08-03
Data Sources: GitHub Daily Trending, GitHub Topic Search API (robotics/embodied-AI/VLA tags, 7-day activity)

---

## 1. Today's Highlights
Notably, none of GitHub’s top 15 daily trending repositories are directly related to embodied intelligence or robotics, reflecting that broad developer attention remains concentrated on general LLM tooling, agent infrastructure, and coding assistants this week, with specialized robotics activity occurring in niche topic-tagged projects. The most significant development in the embodied AI space is the active release of official developer resources for NVIDIA’s newly launched Alpamayo VLA model, including recipes for fine-tuning, RL post-training, quantization, and edge deployment. Open-source humanoid software stacks are also seeing growing community investment, with new projects targeting standardized runtime systems, pre-trained locomotion policies, and vertical use case development for commercial humanoid robots. Finally, VLA robustness and safety have emerged as urgent priorities, with the first dedicated open-source red-teaming frameworks and empirical performance studies launching this week to address gaps in real-world VLA reliability.

---

## 2. Top Projects by Category
*Note: Daily star delta is only tracked for the daily trending list, which contained no relevant robotics/embodied AI projects; only total star counts are listed below.*

### 🤖 Robot Frameworks / SDKs (Control, Simulation, Planning)
1. **[commaai/openpilot](https://github.com/commaai/openpilot)** | Total: 63,297 ⭐  
   An open-source robotics operating system that adds advanced driver assistance to 300+ consumer vehicles, one of the most widely deployed production robotics stacks globally.
2. **[google-deepmind/mujoco](https://github.com/google-deepmind/mujoco)** | Total: 14,417 ⭐  
   The de facto standard multi-joint physics simulator for robotics research, powering the vast majority of VLA and robot learning training pipelines.
3. **[isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab)** | Total: 7,819 ⭐  
   NVIDIA’s unified robot learning framework built on Isaac Sim, rapidly becoming the go-to platform for sim-to-real VLA and humanoid locomotion training.
4. **[dora-rs/dora](https://github.com/dora-rs/dora)** | Total: 3,858 ⭐  
   Low-latency, dataflow-oriented robotic middleware optimized for AI-powered robots, designed to simplify composable VLA deployment across distributed hardware.
5. **[RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)** | Total: 126 ⭐  
   A lightweight, ROS-free sim-to-real framework for deploying VLA models and RL agents, with native support for common manipulators including Franka, UR5e, and xArm.

### 🧠 VLA / Foundation Models (Vision-Language-Action, Policies, Infrastructure)
1. **[NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes)** | Total: 83 ⭐  
   Official developer hub for NVIDIA’s July 2026-launched Alpamayo VLA, with pre-built workflows for fine-tuning, RL post-training, quantization, and edge deployment.
2. **[dexmal/opendm](https://github.com/dexmal/opendm)** | Total: 127 ⭐  
   An open-source general-purpose embodied foundation model targeting open-world robotic tasks, a community-led alternative to closed commercial VLAs.
3. **[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)** | Total: 119 ⭐  
   Open-source evaluation framework for physical AI, enabling cross-benchmark testing of any VLA model on simulated or real robot hardware.
4. **[mohanchillara1/gr00trobustnessresearch](https://github.com/mohanchillara1/gr00trobustnessresearch)** | Total: 1 ⭐  
   Empirical robustness study of GR00T N1.7 VLA models finding that common visual perturbations (dimming, rotation) can reduce task success rates by 100%, highlighting critical reliability gaps for real-world deployment.
5. **[provael/provael](https://github.com/provael/provael)** | Total: 5 ⭐  
   The first open-source red-teaming framework for VLA policies, measuring attack success rates in simulation to improve embodied AI safety and reliability.

### 🦾 Manipulation & Grasping (Dexterous Skills, Benchmarks, Hardware)
1. **[mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill)** | Total: 3,196 ⭐  
   GPU-parallelized robotics manipulation simulator and benchmark, supporting large-scale VLA policy training for contact-rich, generalizable manipulation tasks.
2. **[RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo)** | Total: 332 ⭐  
   Official repository for the RoboDojo manipulation benchmark, a new standard for evaluating cross-task generalizability of robotic manipulation policies.
3. **[robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw)** | Total: 44 ⭐  
   Open-source software for synchronized bimanual manipulation data collection and cross-robot retargeting, addressing a key VLA training data bottleneck for two-armed robots.
4. **[zcy13/cofree-arm](https://github.com/zcy13/cofree-arm)** | Total: 0 ⭐  
   A novel no-training desktop robotic arm system that combines multimodal models for semantic reasoning and geometric methods for motion planning, reducing per-task cost to ~$0.20.

### 🚶 Locomotion & Navigation (Humanoid, Legged Robotics, SLAM)
1. **[softmata/horus](https://github.com/softmata/horus)** | Total: 403 ⭐  
   A high-performance runtime system for humanoid robots, positioned as the "Android for robots" to standardize the fragmented humanoid software ecosystem.
2. **[ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software)** | Total: 324 ⭐  
   Production-grade legged locomotion software used in world-class humanoids and exoskeletons, with momentum-based control and built-in optimization.
3. **[robit-man/dropbear-locomotion](https://github.com/robit-man/dropbear-locomotion)** | Total: 0 ⭐  
   Open-source Dropbear humanoid locomotion implementation in NVIDIA Isaac Lab using RSL-RL PPO, with validated pre-trained checkpoints available for community use.
4. **[introlab/rtabmap](https://github.com/introlab/rtabmap)** | Total: 3,925 ⭐  
   Widely used real-time SLAM library for autonomous robots, supporting visual and LiDAR-based mapping for navigation and humanoid localization.

### 📦 Embodied Applications (Sim2Real, Teleoperation, Vertical Use Cases)
1. **[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)** | Total: 2,955 ⭐  
   Beginner-friendly open course teaching users to build a VLA-powered embodied robot from scratch with only basic Python knowledge, democratizing access to VLA development.
2. **[PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS)** | Total: 1,463 ⭐  
   A self-evolving embodied AI operating system built on agentic workflows, designed to unify software for cross-platform physical AI agents.
3. **[BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit)** | Total: 143 ⭐  
   Full-embodiment humanoid teleoperation system, enabling low-cost remote control of humanoid robots for data collection and task execution.
4. **[x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety)** | Total: 121 ⭐  
   Comprehensive survey of embodied AI safety risks, attacks, and defenses with 500+ papers, reflecting rising industry and regulatory focus on safe real-world robotic deployment.

---

## 3. Trend Signal Analysis
The specialized embodied AI and robotics community’s attention this week is overwhelmingly focused on VLA deployment tooling and humanoid software standardization, directly driven by two recent industry catalysts: NVIDIA’s late July 2026 launch of its flagship Alpamayo VLA model, and accelerating pilot deployments of commercial humanoid robots in manufacturing and healthcare. The release of official Alpamayo development recipes has spurred a wave of complementary community projects, including cross-hardware evaluation frameworks and robustness testing tools, as developers race to adapt state-of-the-art VLAs to real-world robotic use cases. A notable new direction emerging this week is dedicated red-teaming and safety evaluation infrastructure for VLA policies, a response to growing regulatory and industry concern over unregulated embodied AI deployment in shared spaces. Additionally, there is a clear shift toward ROS-free robot control stacks optimized for VLA deployment, as developers seek to reduce latency and eliminate unnecessary middleware abstractions for AI-native robotic systems. These trends align with key takeaways from the 2026 Embodied AI Summit, which prioritized VLA commercialization and standardized humanoid software stacks as core industry goals for 2027. (272 words)

---

## 4. Community Hot Spots
- **[NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes)**: As the official developer resource for NVIDIA’s industry-leading Alpamayo VLA model, this repository will see rapid iteration and community contributions as teams implement custom fine-tuning, quantization, and deployment workflows for a wide range of robotic hardware.
- **[softmata/horus](https://github.com/softmata/horus)**: Positioned as a universal runtime system for humanoid robots, this project addresses a critical gap in the highly fragmented humanoid software ecosystem and is well-positioned to become a core building block for commercial humanoid development.
- **[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)**: Standardized, cross-platform VLA evaluation is a major missing piece of the embodied AI stack, and this open-source framework, which supports testing any VLA on any sim or real robot, is poised to become the de facto benchmarking tool for VLA model comparison.
- **[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)**: This beginner-friendly, hands-on course lowers the barrier to entry for VLA development by teaching users to build a working embodied robot from scratch with only basic Python knowledge, making it a top resource for new engineers entering the fast-growing embodied AI job market.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*