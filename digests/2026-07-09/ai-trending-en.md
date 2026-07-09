# AI Open Source Trends 2026-07-09

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-09 01:49 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report | 2026-07-09
---
## 1. Today's Highlights
Today’s embodied AI and robotics ecosystem saw explosive traction across perception infrastructure, accessible VLA tooling, and humanoid deployment stacks. ruvnet/RuView, a WiFi-based spatial intelligence system that eliminates camera dependency for presence detection and vital sign monitoring, gained 799 new stars, highlighting fast-growing demand for privacy-first embodied perception. Low-barrier VLA development emerged as a top community priority: bradautomates/claude-video (951 new stars) adds out-of-the-box video processing capabilities to Claude, while muhammadmahadazher/vla-on-a-budget democratizes VLA benchmarking for developers with only 8GB laptop GPUs. Humanoid robotics infrastructure also reached key maturity milestones, with the fully open-source OpenArm humanoid manipulator crossing 2.7k total stars and purpose-built runtime systems like HORUS gaining traction for production deployments.
---
## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,135 total — The de facto standard open-source physics simulator for robotics, used for everything from VLA pre-training to humanoid locomotion testing, with native support for all major robot learning frameworks.
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,833 total — A Rust-based, low-latency dataflow middleware for AI robotics that simplifies building composable, distributed embodied applications, emerging as a popular ROS alternative for VLA deployments.
3. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,632 total — NVIDIA’s unified robot learning framework built on Isaac Sim, the most widely used platform for scalable VLA pre-training and sim2real transfer today.
4. [TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox) ⭐0 total (+564 today) — A lightweight, secure Rust sandbox for AI agents, designed to mitigate risk when deploying untrusted embodied agent policies to physical hardware.
5. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐122 total — A ROS-free sim2real framework for VLA and RL agent deployment, with native support for Franka, UR5e, and xArm manipulators, eliminating common ROS overhead for small teams.
6. [softmata/horus](https://github.com/softmata/horus) ⭐386 total — A high-performance Rust robotics runtime system, positioned as an "Android for robots" to standardize low-level hardware control across heterogeneous humanoid and manipulator platforms.
### 🧠 VLA / Foundation Models
1. [bradautomates/claude-video](https://github.com/bradautomates/claude-video) ⭐0 total (+951 today) — A lightweight Python tool that adds end-to-end video processing (download, frame extraction, transcription) to Claude, drastically lowering the barrier to building video-fed VLA systems.
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,585 total — A hands-on, Python-first course that teaches developers to build VLA models (including OpenVLA, SmolVLA, and Pi0) from scratch, addressing the critical gap in accessible VLA educational resources.
3. [muhammadmahadazher/vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget) ⭐0 total — A benchmark comparing ACT, Diffusion Policy, and SmolVLA on a single 8GB laptop GPU, providing transparent, negative-inclusive results for developers without access to high-end compute.
4. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐473 total — InternVLA-A1, a state-of-the-art VLA that unifies visual understanding, content generation, and robotic action, setting a new bar for generalizable manipulation performance.
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐2 total — An open-source VLA evaluation framework that lets users define a single benchmark and run it across any policy, robot, or simulation environment, standardizing VLA performance testing.
6. [cair-vinuni/CLP_VLA](https://github.com/cair-vinuni/CLP_VLA) ⭐4 total — Code for the recent paper showing that VLA fine-tuning requires far fewer layers than previously thought, enabling efficient, low-compute VLA adaptation for edge deployments.
### 🦾 Manipulation & Grasping
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,704 total — A fully open-source humanoid manipulator designed for contact-rich physical AI research, the most popular open hardware arm for VLA testing as of today.
2. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐167 total — Official CVPR 2025 implementation of GenManip, an LLM-driven simulation framework that generates diverse manipulation task datasets to improve VLA generalization.
3. [sahilrajpurkar03/nlp-pnp-robotic-arm](https://github.com/sahilrajpurkar03/nlp-pnp-robotic-arm) ⭐64 total — A ROS2-based pick-and-place system that integrates YOLOv8, MoveIt, and Ollama for natural language control of Franka Panda and UR5 arms, a ready-to-use end-to-end manipulation stack.
4. [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) ⭐44 total — RSS 2026 paper implementation of PoseVLA, a universal pose-pretrained VLA that achieves state-of-the-art generalization across unseen manipulation tasks.
5. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐33 total — A framework that compiles natural language instructions into verified robot skill graphs, reducing execution errors for long-horizon manipulation tasks.
### 🚶 Locomotion & Navigation
1. [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐238 total — ECCV 2026 implementation of Habitat-GS, a high-fidelity navigation simulator using dynamic Gaussian splatting, drastically improving sim2real transfer for indoor navigation policies.
2. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐254 total — An open-source SLAM and data processing pipeline for the Universal Manipulation Interface, a critical tool for mapping and navigation in unstructured real-world environments.
3. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐131 total — A lightweight, scalable whole-body teleoperation framework for humanoid robots, reducing the cost and complexity of collecting human demonstration data for locomotion and manipulation.
4. [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐8 total — An affordable, fully 3D-printable open-source humanoid robot powered by a Raspberry Pi Zero 2W, designed as an accessible educational platform for legged locomotion research.
5. [zengury/roboonto](https://github.com/zengury/roboonto) ⭐7 total — IEEE 1872-aligned machine-readable robot ontologies for LLM agents, enabling agents to query robot capabilities and validate actions before execution on Unitree G1 and AgiBot X2 humanoids.
### 📦 Embodied Applications
1. [ruvnet/RuView](https://github.com/ruvnet/RuView) ⭐0 total (+799 today) — A Rust-based system that turns commodity WiFi signals into real-time spatial intelligence, presence detection, and vital sign monitoring without any camera input, a breakthrough for privacy-first embodied sensing.
2. [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐218 total — A minimal hardware-software stack that gives LLMs closed-loop physical embodiment with self-perception loops, enabling low-cost testing of embodied agent policies on real hardware.
3. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐408 total — A self-evolving embodied AI operating system built on agentic workflows, designed to enable continuous learning for physical robots in unstructured environments.
4. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐99 total — A framework that lets users control physical robots and hardware via natural language through Strands Agents, a low-code solution for deploying embodied agents to real hardware.
5. [zengury/manastone-diag](https://github.com/zengury/manastone-diag) ⭐8 total — An LLM-powered offline fault diagnosis assistant for the AgiBot X2 Ultra humanoid, combining rule-based logic and causal inference to resolve hardware issues from log files.
---
## 3. Trend Signal Analysis
The most explosive community attention today is focused on democratizing VLA development for low-resource teams and individual developers. Projects ranging from the zero-to-VLA *every-embodied* course to the 8GB GPU *vla-on-a-budget* benchmark signal a clear shift from lab-only VLA research to accessible, edge-first tooling, driven by widespread demand to deploy VLA policies on low-cost robotic hardware.
A newly emerging technical direction is privacy-first embodied perception, as demonstrated by ruvnet/RuView’s 799 daily stars. WiFi-based spatial sensing eliminates camera dependency, addressing growing regulatory and consumer pushback against perpetual visual surveillance in smart home, healthcare, and industrial robotics use cases.
These trends align closely with recent industry milestones: the announcement of mass-produced sub-$10k humanoids from Unitree and AgiBot has accelerated demand for both low-cost VLA deployment stacks and production-grade infrastructure for robot maintenance and safety. Standardized VLA evaluation frameworks, robot ontologies for action validation, and secure agent sandboxes are all rapidly maturing to support the coming wave of commercial embodied AI deployments.
---
## 4. Community Hot Spots
- **Low-compute VLA development**: Prioritize experimenting with [muhammadmahadazher/vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget) and [cair-vinuni/CLP_VLA](https://github.com/cair-vinuni/CLP_VLA), as layer-efficient fine-tuning and edge VLA deployment will be the highest-growth subfield over the next 6 months, driven by mass market robot hardware launches.
- **Privacy-first embodied sensing**: Explore [ruvnet/RuView](https://github.com/ruvnet/RuView) for non-visual perception use cases, as camera-free spatial intelligence is rapidly becoming a requirement for compliance with global privacy regulations for consumer and healthcare robotics.
- **Humanoid infrastructure standardization**: Contribute to [softmata/horus](https://github.com/softmata/horus) and [zengury/roboonto](https://github.com/zengury/roboonto), as standardized runtime systems and robot capability ontologies will be core to interoperability across the fragmented humanoid hardware ecosystem.
- **VLA evaluation and safety**: Test [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) and [provael/provael](https://github.com/provael/provael), as standardized benchmarking and red-teaming tools will be mandatory for any commercial VLA deployment going forward, with regulatory bodies already drafting safety requirements for embodied AI.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*