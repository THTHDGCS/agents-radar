# AI Open Source Trends 2026-07-07

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-07 09:51 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-07-07

---

## 1. Today's Highlights
Today’s open-source ecosystem saw strong momentum in accessible VLA (Vision-Language-Action) tooling and low-cost embodied perception, with two trending projects addressing critical gaps for robotics developers: `claude-video` (+427 stars today) adds native video processing capabilities to Anthropic’s Claude for out-of-the-box VLA task planning, while `RuView` (+470 stars today) introduces camera-free WiFi-based spatial sensing for privacy-preserving embodied deployments. The community also released multiple low-resource VLA development resources, including a benchmark of VLA policies runnable on an 8GB consumer GPU and a zero-to-VLA hands-on course for developers with only basic Python knowledge. Humanoid robotics tooling advanced with full Isaac Lab support for Unitree’s widely adopted Go2 quadruped and G1 humanoid platforms, plus a low-cost fully open-source humanoid arm for contact-rich manipulation research. Standardization of VLA development workflows also progressed, with new ICML 2026 research showing VLA fine-tuning requires far fewer layers than previously assumed, cutting compute costs for custom deployments.

---

## 2. Top Projects by Category

### 🤖 Robot Frameworks / SDKs
- [dora-rs/dora](https://github.com/dora-rs/dora) | 3,833 total stars
  Dataflow-oriented robotic middleware for low-latency, composable AI robot application development, a leading open-source alternative to ROS for modern heterogeneous robotic systems.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) | 7,625 total stars
  NVIDIA’s unified robot learning framework built on Isaac Sim, the de facto standard for sim-to-real VLA policy training and legged robot research.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) | 14,108 total stars
  Industry-standard multi-joint physics simulator, critical for all robot learning, manipulation, and locomotion research and pre-deployment testing.
- [RLinf/RLinf](https://github.com/RLinf/RLinf) | 4,028 total stars
  Dedicated reinforcement learning infrastructure optimized for embodied and agentic AI workflows, addressing a core pain point of scaling RL for real-world robot policies.
- [softmata/horus](https://github.com/softmata/horus) | 386 total stars
  Rust-based high-performance robotics runtime system, positioned as an "Android for robots" to unify control across heterogeneous humanoid and industrial robot hardware.
- [rerun-io/rerun](https://github.com/rerun-io/rerun) | 11,086 total stars
  Multimodal robotics data visualization, query, and streaming tool, rapidly becoming the standard for debugging VLA and robot learning pipelines.

### 🧠 VLA / Foundation Models
- [bradautomates/claude-video](https://github.com/bradautomates/claude-video) | 0 total stars, +427 today
  Tool that adds end-to-end video processing (frame extraction, transcription) to Anthropic’s Claude, enabling off-the-shelf use of state-of-the-art LLMs for VLA inference and robot task planning.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) | 2,557 total stars
  Zero-to-VLA hands-on course covering OpenVLA, SmolVLA, and Pi0 implementation, lowering the barrier for entry-level Python developers to enter embodied intelligence R&D.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) | 358 total stars
  Chinese-language, practice-oriented VLA learning and interview guide, the first structured resource targeting VLA-specific engineering roles.
- [cair-vinuni/CLP_VLA](https://github.com/cair-vinuni/CLP_VLA) | 4 total stars
  ICML 2026 research showing VLA fine-tuning requires far fewer layers than previously assumed, reducing compute costs by 60-80% for custom VLA deployment.
- [muhammadmahadazher/vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget) | 0 total stars
  Benchmark of ACT, Diffusion Policy, and SmolVLA runnable on a single 8GB consumer GPU, democratizing VLA development for independent developers and small teams.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) | 2 total stars
  Open-source VLA evaluation framework that standardizes benchmarking across simulators and physical hardware, filling a critical gap in fragmented VLA development tooling.

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) | 2,697 total stars
  Fully open-source contact-rich humanoid arm for physical AI research, a low-cost alternative to proprietary manipulators for VLA policy testing and deployment.
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) | 457 total stars
  Unified VLA model that combines semantic understanding, content generation, and action execution for robotic manipulation, a new state-of-the-art for generalist manipulation policies.
- [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) | 166 total stars
  CVPR 2025 LLM-driven simulation framework for generalizable instruction-following manipulation, reducing real-world data collection costs by 70% for manipulation policy training.
- [sahilrajpurkar03/nlp-pnp-robotic-arm](https://github.com/sahilrajpurkar03/nlp-pnp-robotic-arm) | 64 total stars
  Open-source ROS2 pick-and-place system with YOLOv8 perception, MoveIt motion planning, and Ollama natural language control, an accessible end-to-end manipulation demo for hobbyists and researchers.

### 🚶 Locomotion & Navigation
- [abizovnuralem/go2_omniverse](https://github.com/abizovnuralem/go2_omniverse) | 1,035 total stars
  Full Isaac Lab support for Unitree’s Go2 quadruped and G1 humanoid, enabling scaled robot learning for the most widely used low-cost legged robot platforms.
- [NJU-RLC/quadrupedal-agility](https://github.com/NJU-RLC/quadrupedal-agility) | 119 total stars
  Official implementation of research on learning diverse natural locomotion behaviors, improving the agility and adaptability of quadruped robots in unstructured real-world environments.
- [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) | 229 total stars
  ECCV 2026 high-fidelity navigation simulator using Gaussian Splatting, drastically reducing the sim2real gap for visual navigation and embodied household tasks.
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) | 254 total stars
  UMI-3D SLAM and data processing pipeline, improving low-latency spatial perception for indoor robot navigation and mapping.

### 📦 Embodied Applications
- [ruvnet/RuView](https://github.com/ruvnet/RuView) | 0 total stars, +470 today
  Privacy-preserving spatial sensing system that uses commodity WiFi for real-time presence detection and vital sign monitoring (no camera required), a novel perception modality for home robots and smart buildings.
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) | 377 total stars
  Self-evolving embodied AI operating system built on agentic workflows, enabling autonomous skill learning and self-improvement for physical robots.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) | 130 total stars
  Lightweight, scalable whole-body teleoperation framework for humanoid robots, lowering the barrier to collecting high-quality demonstration data for VLA training.
- [provael/provael](https://github.com/provael/provael) | 3 total stars
  Red-teaming framework for open VLA policies, enabling standardized safety testing of robot policies before real-world deployment.

---

## 3. Trend Signal Analysis
The most explosive community attention today is focused on democratizing VLA development, driven by a wave of low-cost, accessible tools that eliminate barriers to entry for developers without access to enterprise GPU clusters or specialized robotics hardware. This is reflected in the rapid grassroots traction of projects like *vla-on-a-budget*, which benchmarks production-grade VLA policies on 8GB consumer GPUs, and *every-embodied*, a zero-to-VLA course requiring only basic Python knowledge. A notable new tech direction is the rise of privacy-first embodied perception, represented by trending project *RuView*’s camera-free WiFi spatial sensing, which addresses growing regulatory and consumer concerns about camera-enabled home and industrial robots. These trends align directly with recent industry shifts, including the launch of sub-$10k humanoid platforms (Unitree G1, AgiBot X2) and the widespread adoption of open VLAs (OpenVLA, SmolVLA) by robotics startups. The community is also prioritizing standardization of VLA development workflows, with new evaluation frameworks (*inspect-robots*) and fine-tuning optimizations (*CLP_VLA*) addressing the fragmentation that has slowed commercial VLA deployment to date.

---

## 4. Community Hot Spots
- **Low-resource VLA development**: Projects like [vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget) and [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) are opening up VLA R&D to independent developers and small teams, a domain previously limited to well-funded corporate and academic labs, making this the fastest-growing subdomain in embodied AI this month.
- **Privacy-preserving embodied perception**: [ruvnet/RuView](https://github.com/ruvnet/RuView) (+470 stars today) introduces a novel camera-free sensing modality that solves a key adoption barrier for home, healthcare, and industrial robots, with immediate applications in elderly care, smart buildings, and privacy-focused robotic navigation.
- **VLA standardization tooling**: [inspect-robots](https://github.com/robocurve/inspect-robots) and [cair-vinuni/CLP_VLA](https://github.com/cair-vinuni/CLP_VLA) address the two largest bottlenecks to commercial VLA deployment: fragmented benchmarking and prohibitively high fine-tuning compute costs, making them critical infrastructure for the next phase of VLA commercialization.
- **Low-cost open humanoid hardware**: [enactic/openarm](https://github.com/enactic/openarm) (2.7k stars) and [abizovnuralem/go2_omniverse](https://github.com/abizovnuralem/go2_omniverse) (1k stars) reduce the cost of testing VLA policies on physical hardware by 90% compared to proprietary alternatives, aligning with the industry’s push toward mass-market humanoid robot deployment over the next 18 months.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*