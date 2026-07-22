# AI Open Source Trends 2026-07-22

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-22 01:25 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report | 2026-07-22

---

## 1. Today's Highlights
Today’s embodied intelligence and robotics ecosystem sees growing momentum across accessible VLA development, open humanoid infrastructure, and standardized benchmarking. Lightweight Mamba-based VLA architectures have earned formal validation, with the 179M-parameter SUREFlow model accepted at IROS 2026, offering a path to edge-deployable robotic control. Open-source humanoid hardware and runtime stacks are gaining traction, with the 2.7k-star `openarm` and Rust-based `horus` runtime emerging as low-cost alternatives to proprietary robotic platforms. End-to-end educational resources for embodied AI are surging, as `every-embodied` lowers barriers to entry for developers with only basic Python experience to build custom VLA-powered robots. Finally, specialized VLA evaluation tooling is maturing, with new projects addressing the longstanding gap in standardized performance testing for physical AI models.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs (control, simulation, planning, motion)
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,722 total  
  The de facto unified framework for robot learning built on NVIDIA Isaac Sim, supporting end-to-end training of VLA, RL, and control policies for all major robot form factors.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,850 total  
  Low-latency, dataflow-oriented robotic middleware that simplifies building composable, distributed AI-powered robotic applications, with native support for VLA model deployment.
- [softmata/horus](https://github.com/softmata/horus) ⭐391 total  
  Rust-based high-performance robotics runtime, positioned as the "Android for robots" to unify fragmented software stacks across humanoid, manipulator, and mobile robot platforms.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124 total  
  ROS-free sim-to-real framework for deploying VLA models and RL agents, with native Gymnasium wrappers for common manipulators (Franka, UR5e, xArm) to reduce deployment overhead.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,276 total  
  Industry-standard open-source physics simulator for multi-joint contact dynamics, used universally for robotic simulation, sim2real training, and VLA policy validation.

---

### 🧠 VLA / Foundation Models
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐507 total  
  State-of-the-art VLA series that unifies visual understanding, text generation, and robotic action output for generalist manipulation tasks, from leading Chinese embodied AI lab InternRobotics.
- [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐5 total  
  Newly accepted IROS 2026 work presenting a 179M-parameter Mamba-based VLA for robotic manipulation, outperforming larger transformer-based models while running on edge hardware.
- [Open-X-Humanoid/XR-1](https://github.com/Open-X-Humanoid/XR-1) ⭐186 total  
  Versatile VLA trained on unified vision-motion representations, optimized for both manipulator and humanoid whole-body control tasks.
- [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐590 total  
  Foundation model for whole-body humanoid control, supporting zero-shot generalization across locomotion and manipulation tasks for bipedal robots.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐12 total  
  First dedicated evaluation framework for VLA and physical AI models, allowing users to define a single benchmark and run it across any robot, simulator, or policy architecture.

---

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,749 total  
  Fully open-source humanoid arm designed for contact-rich physical AI research and deployment, with 6 degrees of freedom, force sensing, and sim2real calibration tools.
- [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) ⭐0 total (+291 today)  
  Trending collection of agent skills for CAD, robotics, and hardware design, enabling natural language-driven generation of custom manipulator and end-effector parts.
- [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) ⭐39 total  
  Bidirectionally aligned embodied agent framework for long-horizon manipulation tasks, supporting multi-step household and industrial workflows with error correction.
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐36 total  
  Open-source software stack for synchronized bimanual data collection and retargeting, allowing users to map human teleoperation input to any bimanual robot platform.
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐4 total  
  Bimanual kitchen manipulation benchmark for VLA models, built on Inspect Robots, with 50+ contact-rich household tasks to test long-horizon policy performance.

---

### 🚶 Locomotion & Navigation
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,191 total  
  The largest deployed open-source robotics operating system, powering level 2+ driver assistance for 300+ supported vehicle models as a leading real-world embodied autonomy stack.
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐258 total  
  High-performance UMI-3D SLAM and data processing pipeline, optimized for low-latency embodied perception in manipulation and mobile robot use cases.
- [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx) ⭐259 total  
  JAX-based differentiable Model Predictive Control library for legged and humanoid robot locomotion, supporting real-time trajectory optimization for contact-rich bipedal movement.
- [Rhoban/microban](https://github.com/Rhoban/microban) ⭐38 total  
  Affordable, fully 3D-printable open-source humanoid robot platform, powered by a Raspberry Pi Zero 2W, designed for DIY and academic locomotion research.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,493 total  
  Production-grade ROS 2 navigation framework for mobile robots, supporting path planning, obstacle avoidance, and autonomous navigation across indoor and outdoor environments.

---

### 📦 Embodied Applications & Educational Resources
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,795 total  
  Zero-to-one hands-on tutorial series for developers with only basic Python experience, teaching end-to-end construction of embodied robots and VLA models (OpenVLA, Pi0, SmolVLA).
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐838 total  
  Self-evolving embodied AI operating system built on modular agentic workflows, supporting closed-loop learning from real-world robotic interaction data.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐132 total  
  Lightweight, scalable whole-body teleoperation framework for humanoid robots, supporting low-latency input from VR, motion capture, and handheld controllers.
- [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,587 total  
  Leading embodied AI benchmark platform with 1,000+ photorealistic household tasks, designed to test real-world generalization of VLA and embodied agent policies.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐417 total  
  Chinese-language, practice-oriented VLA learning and interview handbook, tailored for algorithm engineers transitioning from CV/NLP to the robotics/embodied AI field.

---

## 3. Trend Signal Analysis (242 words)
The most explosive community attention this cycle is focused on the democratization of VLA and embodied AI development, breaking down historical barriers that limited work to specialized robotics labs. Unlike 6 months ago, when VLA development required advanced ROS and PhD-level robotics expertise, today’s ecosystem offers end-to-end educational resources (`every-embodied`) and ROS-free deployment stacks (`robot-control-stack`) that enable developers with only basic Python experience to build and deploy custom VLA models. A notable emerging technical direction is Mamba-based lightweight VLA architectures, formalized by the IROS 2026 acceptance of SUREFlow, a 179M-parameter model that outperforms larger transformer-based VLAs on manipulation tasks while running on commodity edge hardware. This aligns with recent industry shifts toward deploying embodied AI on low-cost consumer and industrial robots, rather than limiting use cases to cloud-connected platforms. Additionally, the rapid emergence of specialized VLA benchmarking tools (`inspect-robots`, `kitchenbench`) corresponds to recent industry pushes for standardized physical AI performance metrics, a critical prerequisite for widespread commercial VLA deployment expected in 2027.

---

## 4. Community Hot Spots
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied): As the fastest-growing embodied AI educational resource, it fills a critical gap for non-specialist developers looking to enter the VLA space, making it a high-priority learning asset for engineers transitioning to robotics.
- [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026): The first top-conference Mamba-based VLA, it signals a paradigm shift away from resource-heavy transformer architectures toward edge-deployable embodied models, with major implications for consumer robotics.
- [softmata/horus](https://github.com/softmata/horus): Positioned as a universal runtime for all robot form factors, it addresses the longstanding pain point of fragmented robotics software stacks, with strong early momentum to become an industry standard.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): The first dedicated VLA evaluation framework, it solves a critical bottleneck for VLA commercialization by enabling standardized cross-platform performance testing, making it essential for both researchers and product teams.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*