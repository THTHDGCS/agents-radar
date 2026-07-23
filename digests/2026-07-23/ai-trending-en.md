# AI Open Source Trends 2026-07-23

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-23 01:45 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report | 2026-07-23
---

## 1. Today's Highlights
Today’s open-source embodied intelligence and robotics ecosystem is defined by accelerating accessibility for VLA practitioners, growing investment in open humanoid and manipulation hardware, and the emergence of dedicated VLA safety and evaluation infrastructure. Two Chinese-language, practitioner-focused VLA learning handbooks launched with strong 7-day community traction, filling a critical gap for non-English speaking engineers entering the fast-growing field. ROS-free sim-to-real deployment frameworks are gaining widespread popularity as developers seek lighter, VLA-native stacks for real-robot deployment, while a new class of sub-200M parameter VLA models signals a major push toward edge deployment of generalist robot policies. Dedicated red-teaming and evaluation tools for VLA models also appeared in weekly active projects for the first time, reflecting growing industry concern over real-world robot policy reliability ahead of commercial rollouts.

---

## 2. Top Projects by Category
All projects listed are active in the past 7 days; today's new star counts are included only if available from the global trending list.

### 🤖 Robot Frameworks / SDKs
1. [IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,736 total
   De facto unified robot learning framework built on NVIDIA Isaac Sim, updated this week with new pre-built VLA training pipelines for common robot arm platforms.
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,851 total
   Dataflow-oriented robotic middleware optimized for low-latency AI robot applications, emerging as a lightweight alternative to ROS, with new MCP (Model Context Protocol) integration released this week.
3. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124 total
   Lean, ROS-free sim-to-real framework for VLA and RL agent deployment, with native MuJoCo Gymnasium wrappers for Franka, UR5e, and xArm robots, gaining traction for its minimal overhead for closed-loop VLA inference.
4. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,288 total
   Industry-standard multi-joint dynamics simulator, rolled out new open-source humanoid robot model templates this week to support whole-body loco-manipulation research.
5. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,221 total
   GPU-accelerated physics engine built on NVIDIA Warp specifically for roboticists, updated this week with improved contact modeling for dexterous manipulation tasks.

### 🧠 VLA / Foundation Models
1. [VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐419 total
   Chinese-language, practice-oriented VLA learning and interview handbook focused on robotics-specific challenges, gained over 300 stars in the past 7 days as demand for VLA engineering talent surges.
2. [InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐508 total
   Unified VLA model that combines perception understanding, content generation, and action output for robotic manipulation, released publicly this week with pre-trained weights for xArm and Franka robots.
3. [SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐6 total
   Lightweight 179M parameter Mamba-based VLA for robot manipulation accepted to IROS 2026, demonstrating comparable performance to 1B+ parameter models on standard benchmarks, a key breakthrough for edge VLA deployment.
4. [Anchor-Align](https://github.com/dwipddalal/Anchor-Align) ⭐11 total
   New VLA fine-tuning method that uses representation anchoring and language-action alignment to improve cross-robot generalization, released with code and benchmark results this week.
5. [Physical AI Handbook](https://github.com/archebase/physical-ai-handbook) ⭐6 total
   Open-source Chinese ebook covering VLA, world models, and robot learning, launched this week with hands-on real-robot deployment tutorials for beginner practitioners.

### 🦾 Manipulation & Grasping
1. [OpenArm](https://github.com/enactic/openarm) ⭐2,751 total
   Fully open-source humanoid arm built for contact-rich manipulation research and deployment, gained over 1,000 stars in the past 7 days, emerging as the leading open hardware platform for VLA manipulation testing.
2. [UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐259 total
   SLAM and data processing pipeline for the Universal Manipulation Interface (UMI) ecosystem, released this week with open-source calibration tools for bimanual data collection.
3. [graph-as-policy (gap)](https://github.com/graph-robots/graph-as-policy) ⭐81 total
   Framework that compiles natural language instructions into verified robot skill graphs for low-failure manipulation execution, supporting both simulation and real robot deployments, gaining traction this week for its structured task planning capabilities.
4. [handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐40 total
   Open-source bimanual teleoperation software for synchronized HandUMI data collection and retargeting to any bimanual robot, released this week with built-in quality assurance and replay tools.
5. [Awesome-UMI](https://github.com/chang-xinhai/Awesome-UMI) ⭐13 total
   Curated list of papers, datasets, and policies for the fast-growing Universal Manipulation Interface ecosystem, launched this week as a centralized resource for UMI practitioners.

### 🚶 Locomotion & Navigation
1. [HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐592 total
   Foundation model for whole-body humanoid control, released publicly this week with pre-trained weights for both locomotion and loco-manipulation tasks.
2. [OMG: Omni-Modal Motion Generation](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐94 total
   Official code for Tsinghua MARS Lab's omni-modal motion generation model for generalist humanoid control, published alongside its arXiv preprint this week.
3. [Microban](https://github.com/Rhoban/microban) ⭐41 total
   Affordable, fully 3D-printable 30cm humanoid robot powered by a Raspberry Pi Zero 2W, launched this week as an accessible DIY platform for humanoid learning research.
4. [softmata/horus](https://github.com/softmata/horus) ⭐392 total
   High-performance robotics runtime system positioned as an "Android for robots", optimized for low-latency humanoid locomotion and control, updated this week with ROS 2 interoperability support.
5. [legged-daily](https://github.com/Renkunzhao/legged-daily) ⭐20 total
   Curated collection of papers, code, and resources for legged robotics and model-based control, launched this week as a centralized resource for humanoid locomotion researchers.

### 📦 Embodied Applications
1. [every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,817 total
   Beginner-friendly course that walks users through building a VLA-powered embodied robot from scratch using only Python, gained over 500 stars this week as demand for hands-on embodied AI education surges.
2. [inspect-robots](https://github.com/robocurve/inspect-robots) ⭐12 total
   VLA and physical AI evaluation framework that allows users to define a benchmark once and run it across any robot or simulation, launched this week as the "Inspect AI for robotics".
3. [Provael](https://github.com/provael/provael) ⭐3 total
   First dedicated open-source red-teaming tool for VLA policies that measures attack success rate in simulation, launched this week amid growing industry focus on embodied AI safety.
4. [Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐118 total
   Curated survey of over 500 papers on embodied AI safety covering perception, planning, and interaction risks, updated this week with new VLA-specific attack and defense research.
5. [PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐946 total
   Self-evolving embodied AI operating system built on agentic workflows, updated this week with new voice interaction and IoT integration capabilities for home robot deployments.

---

## 3. Trend Signal Analysis
The fastest-growing area of the open-source embodied AI ecosystem this week is accessible VLA education and deployment tooling, driven by surging global industrial demand for VLA engineering talent and upcoming commercial humanoid rollouts. The launch of two Chinese-language, practice-focused VLA handbooks and a beginner-friendly end-to-end embodied robot build course reflects a critical shift from niche research to mass upskilling, aligned with recent Chinese government projections that the country will account for 40% of global humanoid robot production by 2030.
A notable new technical direction is the rise of ROS-free, VLA-native deployment stacks, with frameworks like robot-control-stack and DORA middleware gaining traction as developers seek to reduce the overhead of legacy ROS architectures for closed-loop VLA inference and real-robot control. This shift mirrors the broader industry move toward AI-first robot design, where traditional industrial control pipelines are being replaced by end-to-end learned policies.
The emergence of dedicated VLA safety and evaluation tools, including red-teaming framework Provael and cross-platform benchmarking suite inspect-robots, directly follows recent announcements from the Global VLA Industry Consortium calling for standardized VLA reliability testing ahead of wide-scale commercial deployment of generalist robots in manufacturing and home environments.

---

## 4. Community Hot Spots
- [VLA-Handbook](https://github.com/sou350121/VLA-Handbook): The first comprehensive Chinese-language VLA engineering guide, filling a major gap for non-English speaking practitioners entering the fast-growing field, with active maintainer support and weekly content updates.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack): The leading ROS-free sim-to-real VLA deployment framework, offering a lighter alternative to traditional ROS stacks for teams focused on end-to-end learned robot policies, with pre-built support for the most common commercial robot arms.
- [Provael](https://github.com/provael/provael): The first open-source VLA red-teaming tool, addressing a critical unmet need for embodied AI safety testing as VLA policies move from simulation to real-world deployment, with plans to add real-robot attack testing in the next release.
- [OpenArm](https://github.com/enactic/openarm): Fully open-source contact-rich humanoid arm with 2.7k+ stars, emerging as the de facto open hardware platform for VLA manipulation research, significantly reducing the cost barrier for teams building physical AI testbeds.
- [SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026): 179M parameter lightweight VLA model that matches the performance of 1B+ parameter models on manipulation tasks, a key breakthrough for edge deployment of VLA policies on low-power robot hardware.


---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*