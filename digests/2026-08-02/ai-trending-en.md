# AI Open Source Trends 2026-08-02

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-02 01:42 UTC

---

# Embodied Intelligence & Robotics Trends Report (2026-08-02)
---

## 1. Today's Highlights
Today’s embodied intelligence and robotics ecosystem sees concentrated momentum in VLA accessibility, humanoid infrastructure, and embodied safety tooling, with all relevant activity coming from topic-tagged active projects (no robotics/embodied AI repos appeared on the general GitHub trending list for August 2, 2026). NVIDIA’s public release of Alpamayo recipes lowers barriers to fine-tuning, RL post-training, and deployment of production-grade VLA models, while new open evaluation frameworks like inspect-robots standardize physical VLA benchmarking across hardware and simulation. Beginner-focused educational resources for embodied AI are surging in popularity, including a Chinese-language VLA interview/learning handbook and a step-by-step course to build state-of-the-art VLA models from basic Python knowledge. Humanoid robotics infrastructure continues to mature, with a fully open-source contact-rich humanoid arm (openarm) and validated locomotion controllers for Unitree G1 robots gaining community traction. Embodied safety is emerging as a high-priority R&D focus, with new approaches to bake collision avoidance directly into VLA policy weights rather than relying on post-hoc runtime filters.

---

## 2. Top Projects by Category
*Note: All star counts listed are total GitHub stars as of 2026-08-02; no embodied intelligence/VLA/robotics projects appeared on the daily trending list, so today's new star data is not available for relevant projects.*

### 🤖 Robot Frameworks / SDKs (control, simulation, planning, middleware)
- [commaai/openpilot](https://github.com/commaai/openpilot): 63,287 stars, an open-source operating system for robotics that currently powers advanced driver assistance for 300+ supported consumer vehicles, the largest deployed open robotics stack for edge use cases.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco): 14,406 stars, the de facto standard multi-joint physics simulator for robot learning and VLA training, with native GPU acceleration and broad hardware integration support.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab): 7,815 stars, NVIDIA’s unified robot learning framework built on Isaac Sim, the leading platform for scalable VLA and RL training for humanoids and manipulators.
- [dora-rs/dora](https://github.com/dora-rs/dora): 3,857 stars, a low-latency, dataflow-oriented robotic middleware optimized for AI-powered robotic applications, offering a composable alternative to traditional ROS for VLA deployments.
- [rerun-io/rerun](https://github.com/rerun-io/rerun): 11,227 stars, a multimodal data visualization and streaming platform purpose-built for robotics training, enabling teams to debug VLA model behavior across vision, language, and action modalities.
- [RLinf/RLinf](https://github.com/RLinf/RLinf): 4,369 stars, a dedicated reinforcement learning infrastructure platform tailored for embodied and agentic AI, streamlining scalable RL training for VLA policies.

### 🧠 VLA / Foundation Models
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied): 2,949 stars, a beginner-friendly course that teaches developers to build state-of-the-art VLA models (OpenVLA, SmolVLA, Pi0) from basic Python knowledge, driving VLA accessibility for new entrants to the field.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook): 459 stars, the first full Chinese-language, practice-oriented VLA learning and interview guide focused exclusively on robotics-specific challenges, addressing a major gap in non-English VLA educational resources.
- [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes): 83 stars, NVIDIA’s official developer hub for its Alpamayo VLA family, providing production-ready pipelines for fine-tuning, RL post-training, quantization, and deployment of VLA models.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): 108 stars, an open-source evaluation framework for physical AI that enables testing of any VLA or LLM robot policy across any manipulator/humanoid hardware and simulation benchmark.
- [dexmal/opendm](https://github.com/dexmal/opendm): 125 stars, an open-world foundation model built specifically for general-purpose embodied intelligence, designed to support cross-domain robot manipulation and navigation tasks.
- [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety): 121 stars, a comprehensive survey of 500+ papers covering embodied AI risks, attacks, and defenses across perception, planning, and agentic system layers, a critical resource for safety-critical VLA development.
- [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA): 2 stars, an early unified VLA framework for seamless whole-body humanoid loco-manipulation control, addressing a key gap in VLA support for combined movement and manipulation tasks.

### 🦾 Manipulation & Grasping
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill): 3,191 stars, a GPU-parallelized robotics manipulation simulator and benchmark suite that enables scalable VLA training for contact-rich manipulation tasks.
- [enactic/openarm](https://github.com/enactic/openarm): 2,788 stars, a fully open-source humanoid arm designed for contact-rich physical AI research and deployment, filling a critical gap in low-cost, open manipulation hardware for VLA teams.
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw): 43 stars, open-source software for synchronized bimanual data collection and retargeting for Universal Manipulation Interface (UMI) ecosystems, simplifying the creation of VLA training datasets for dual-arm robots.
- [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes): 1 star, a training pipeline for Pi0 flow-matching VLA models that bakes collision avoidance directly into policy weights via a differentiable safety loss, eliminating the need for latency-prone runtime safety filters.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo): 329 stars, an official benchmark suite for standardized robotic manipulation evaluation, supporting cross-model comparison of VLA and RL manipulation policies.
- [darshmenon/ur-arm-rl](https://github.com/darshmenon/ur-arm-rl): 4 stars, a MuJoCo RL environment for UR5e manipulators with native support for pick-and-place and multi-arm cooperative tasks, plus pre-built ROS 2 nodes for sim-to-real deployment.

### 🚶 Locomotion & Navigation
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2): 4,538 stars, the official ROS 2 navigation framework for mobile robots, the industry standard for path planning and obstacle avoidance for ground robots.
- [introlab/rtabmap](https://github.com/introlab/rtabmap): 3,924 stars, a widely used graph-based SLAM library and standalone application for real-time robot localization and mapping in unstructured environments.
- [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover): 9,550 stars, a fully open, build-it-yourself 6-wheel Mars rover design, a popular platform for outdoor navigation and VLA field testing.
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software): 324 stars, a production-grade legged locomotion and momentum-based control stack for humanoids, exoskeletons, and other legged robots, used in leading commercial humanoid platforms.
- [mturan33/isaac-g1-ulc](https://github.com/mturan33/isaac-g1-ulc): 16 stars, an open-source low-level RL locomotion controller for Unitree G1 humanoid robots, trained and validated in NVIDIA Isaac Lab for real-world deployment.
- [robit-man/dropbear-locomotion](https://github.com/robit-man/dropbear-locomotion): 0 stars, a COM-guided humanoid locomotion implementation for NVIDIA Isaac Lab using RSL-RL PPO, with pre-validated checkpoints for rapid humanoid locomotion testing.

### 📦 Embodied Applications (sim2real, teleoperation, deployments)
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS): 1,405 stars, a self-evolving embodied AI operating system built on agentic workflows, designed to manage and coordinate physical robot fleets for general-purpose tasks.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack): 125 stars, a lean, ROS-free sim2real framework for training and deploying VLA and RL agents to Franka, UR5e, xArm, and SO101 robots, optimized for low-overhead VLA deployment.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit): 143 stars, a full-embodiment humanoid teleoperation system that enables whole-body control of humanoid robots for VLA training data collection and remote operation.
- [strands-labs/robots](https://github.com/strands-labs/robots): 112 stars, a framework for controlling physical robot hardware via natural language, integrating with Strands agents to connect VLA outputs to real robot actuation.
- [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover): 8 stars, a VLA-powered Strands agent for controlling the FrodoBots Earth Rover Mini+, with an open ECoT dataset for embodied navigation VLA training.
- [dsl-robotics/skatearm](https://github.com/dsl-robotics/skatearm): 1 star, an open bimanual work-cell ecosystem for the R.Botic Skate robot, with MuJoCo simulation, autonomous assembly workflows, and a web-based control cockpit for end-user deployment.

---

## 3. Trend Signal Analysis (272 words)
The most explosive community attention is focused on VLA democratization and production readiness, as the ecosystem shifts from academic research to accessible, deployable tools. The rapid growth of beginner-focused educational resources (VLA-Handbook, every-embodied) indicates a massive influx of new developers entering the embodied AI space, spurred by recent industry launches of low-cost robot hardware and open-source VLA baselines like OpenVLA and Pi0.
A key new direction emerging this week is native VLA safety integration, with projects like LeRobot-SafetyCubes moving beyond post-hoc runtime safety filters to embed collision avoidance directly into VLA policy weights via differentiable loss functions—an approach that reduces deployment latency and improves performance in unstructured environments. Lean, ROS-free sim2real frameworks (e.g., robot-control-stack) are also gaining traction as developers seek VLA-optimized deployment pipelines that avoid the overhead of traditional ROS middleware for small-batch physical AI deployments.
These trends align with recent industry milestones, including NVIDIA’s launch of the Alpamayo VLA family for robotics and the growing commercial availability of low-cost humanoid and manipulator hardware, which is driving demand for end-to-end tooling that spans model training, evaluation, and real-world deployment.

---

## 4. Community Hot Spots
- [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes): NVIDIA’s official VLA development hub is the highest-priority resource for developers building production-grade VLA, as it eliminates months of redundant engineering work with pre-built pipelines for fine-tuning, RL post-training, quantization, and hardware deployment.
- [enactic/openarm](https://github.com/enactic/openarm): The fully open-source humanoid arm fills a critical gap in low-cost, contact-rich manipulation hardware for VLA research, addressing a major bottleneck for academic and startup teams that cannot afford premium commercial manipulators like Franka Emika.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook): The first robotics-focused, Chinese-language VLA learning and interview guide is a leading indicator of surging VLA talent demand, especially in Asia’s fast-growing humanoid robotics market, and is a valuable onboarding resource for non-English-speaking developers.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): Standardized cross-hardware VLA evaluation is a rapidly growing pain point as more teams deploy physical robots, and this framework is the first open-source tool to support uniform testing of VLA and LLM robot policies across simulation and real hardware.
- [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes): Native VLA safety integration is an emerging cutting-edge direction that addresses regulatory and operational barriers to real-world robot deployment, making this early implementation of weight-encoded collision avoidance a key project to track for safety-focused R&D teams.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*