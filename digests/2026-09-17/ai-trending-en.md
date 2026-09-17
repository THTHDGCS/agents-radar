# AI Open Source Trends 2026-09-17

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-09-17 02:13 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-09-17

---

## 1. Today's Highlights
Computer vision toolchain `roboflow/supervision` leads today’s trending embodied AI-related repos with +260 new stars, reflecting growing demand for standardized perception building blocks for physical AI systems. The VLA (Vision-Language-Action) ecosystem is expanding rapidly across the full stack, with new projects covering long-horizon memory, scalable pretraining data, and unified evaluation frameworks, signaling maturation beyond early architecture research. Open-source humanoid manipulation hardware and VLA deployment tools for commercial manipulators are seeing surging adoption, as the field shifts from simulation benchmarks to real-world hardware integration. Meanwhile, whole-body humanoid control foundation models and cognitive autonomous driving frameworks are emerging as key research frontiers, aligned with recent industry and conference milestones.

---

## 2. Top Projects by Category

### 🤖 Robot Frameworks / SDKs
*(control, simulation, planning, middleware, visualization)*
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,667  
   Open-source operating system for robotics that powers advanced driver assistance across 300+ car models, serving as a leading reference for end-to-end mobile robot autonomy stacks.
2. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,528  
   Comprehensive Python sample code library and textbook for core robotics algorithms, including localization, mapping, path planning, and control — a staple educational and prototyping resource.
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,177  
   Industry-standard multi-joint dynamics simulator with contact modeling, widely used for robot learning, manipulation, and locomotion research due to its speed and accuracy.
4. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,460  
   Multimodal data visualization and streaming platform built for robotics and embodied AI, enabling developers to debug, analyze, and iterate on robot perception and control pipelines.
5. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,145  
   Unified framework for robot learning with multi-physics and multi-renderer support, providing modular environments for training VLA, RL, and control policies at scale.
6. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐5,264  
   Reinforcement learning infrastructure purpose-built for embodied and agentic AI, streamlining the end-to-end workflow from data collection to policy training and evaluation.
7. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐4,036  
   Rust-based dataflow-oriented robotic architecture middleware that delivers low-latency, composable, and distributed pipelines for AI-powered robotic applications.
8. [roboflow/supervision](https://github.com/roboflow/supervision) ⭐N/A (+260 today)  
   Trending today: reusable, production-grade computer vision tools for detection, segmentation, and tracking, widely adopted as a perception building block for embodied AI and robotics systems.

---

### 🧠 VLA / Foundation Models
*(vision-language-action models, world models, imitation/RL policies, tooling)*
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,723  
   Hands-on tutorial project guiding developers to build embodied intelligent robots from scratch, including step-by-step implementations of VLA models like OpenVLA, SmolVLA, and Pi0.
2. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐1,146  
   Open-world foundation model for general-purpose embodied intelligence, designed to support diverse manipulation, navigation, and interaction tasks across unstructured environments.
3. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐624  
   Practice-oriented Chinese-language handbook for VLA algorithm engineers, covering robotics-specific challenges, interview preparation, and real-world deployment considerations.
4. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐514  
   Open-source evaluation platform for physical AI, enabling standardized testing of any LLM/VLA model across any arm/humanoid robot in both simulated and real-world benchmarks.
5. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐284  
   Unified framework for training, fine-tuning, and evaluating World Action Models (WAMs), a class of foundation models that bridge visual understanding to physical action execution.
6. [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐241  
   NVIDIA’s open 34B multi-task foundation model for autonomous vehicle development, leveraging large-scale multimodal data to accelerate end-to-end self-driving research.
7. [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) ⭐37  
   Rising VLA model with native video memory, using timestamped visual history and streaming inference to enable long-horizon robot manipulation tasks that require persistent context.

---

### 🦾 Manipulation & Grasping
*(dexterous hands, contact-rich tasks, manipulation VLA, teleoperation)*
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐3,400  
   Fully open-source humanoid arm designed for physical AI research and deployment in contact-rich environments, filling a critical gap in accessible, hackable manipulation hardware.
2. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐554  
   InternVLA-A1, a unified VLA model that integrates visual understanding, generation, and action execution for generalizable robotic manipulation tasks.
3. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐551  
   Official repository for the RoboDojo benchmark, a standardized test suite for evaluating manipulation policy robustness and generalization across diverse tasks.
4. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐176  
   CVPR 2025 work: LLM-driven simulation framework for generating diverse instruction-following manipulation data, improving the generalization of VLA policies.
5. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐137  
   Framework that compiles natural language instructions into type-verified robot skill graphs, which can be executed on both simulators and real-world manipulation platforms.
6. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐25  
   Deployment-focused fork of OpenPI optimized for the LimX TRON2 manipulator, including policy serving, task fine-tuning, and real-robot client examples.
7. [XenseRobotics-AI/xense-openpi](https://github.com/XenseRobotics-AI/xense-openpi) ⭐16  
   Adaptation of π₀/π₀.5 VLA models to Xense Robotics’ dual-arm manipulation platforms, with support for fine-tuning and real-world deployment on BiARX5 and BiFlexiv rigs.

---

### 🚶 Locomotion & Navigation
*(legged robots, humanoid control, autonomous driving, navigation stacks)*
1. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,876  
   Industry-leading open-source autopilot system supporting planes, copters, rovers, and submersibles — a foundational platform for mobile robot navigation and control.
2. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,712  
   Standard ROS 2 navigation framework providing reliable path planning, localization, and obstacle avoidance for mobile robots across indoor and outdoor environments.
3. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐705  
   Foundation model for whole-body humanoid control, enabling coordinated locomotion and manipulation capabilities for general-purpose humanoid robots.
4. [xiaomi-research/recogdrive](https://github.com/xiaomi-research/recogdrive) ⭐607  
   ICLR 2026 work: ReCogDrive, a reinforced cognitive framework for end-to-end autonomous driving that combines perception, reasoning, and planning in a unified system.
5. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325  
   State-of-the-art legged locomotion and humanoid control software, featuring momentum-based optimization and algorithms used in world-class humanoid and exoskeleton systems.
6. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐117  
   Omni-modal motion generation foundation model for generalist humanoid control, supporting diverse motion tasks from text, vision, and audio inputs.

---

### 📦 Embodied Applications
*(sim2real, teleoperation, real-world deployments, physical AI assistants)*
1. [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3,472  
   Open-source multimodal AI assistant ecosystem with MCP integrations, IoT support, and cross-platform voice interaction, enabling embodied smart home and physical interaction use cases.
2. [Phyzicalorg/Phyzical_org](https://github.com/Phyzicalorg/Phyzical_org) ⭐311  
   Browser-based teleoperation data collection platform for embodied AI, generating elizaOS-ready training episodes with on-chain provenance to fuel robot learning pipelines.
3. [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐203  
   Unified CLI tool for LLM-powered control of diverse robot platforms (humanoids, arms, rovers), supporting multiple model providers, safety contracts, and multi-robot flocks.
4. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐158  
   Platform that enables natural language control of physical robots via Strands Agents, bridging VLA and LLM agent ecosystems to real-world hardware.
5. [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8  
   VLA-powered Earth rover deployment using a FrodoBots platform, with a public ECoT dataset of real-world vision-language-action interactions for research.
6. [omrfrkkus/Adam-Humanoid-Robot-Showcase](https://github.com/omrfrkkus/Adam-Humanoid-Robot-Showcase) ⭐4  
   Open-source 3D-printed humanoid robot showcase integrating Gemini, Llama, and computer vision for ultra-low-latency physical interaction.

---

## 3. Trend Signal Analysis
The most explosive community attention is focused on full-stack VLA tooling and real-world robotic manipulation deployment, marking a critical inflection point for the field. The proliferation of platform-specific adaptations of leading VLA models (OpenPI, Pi0) for commercial manipulators (LimX TRON2, Xense dual-arm rigs) demonstrates a clear shift from simulation-only research to actionable sim-to-real pipelines, driven by the growing availability of affordable robot hardware.

A notable new tech stack direction is the integration of mainstream LLM agent ecosystem standards — including the Anthropic Skills format and Model Context Protocol (MCP) — into robotic control systems. Projects such as graph-robots/open-robot-skills, rokbenko/quackd, and py-xiaozhi are repurposing agent-native tooling for physical AI, creating composable, interoperable robot stacks that break from traditional siloed robotics middleware. This lowers barriers for developers with LLM agent experience to enter the embodied AI space.

These trends align with recent industry and academic milestones: the 2026 ICML and IROS conferences featured record VLA and humanoid research tracks, while commercial humanoid and manipulator launches have created urgent demand for open-source deployment infrastructure. The strong daily growth of roboflow/supervision further underscores the need for standardized perception building blocks to accelerate physical AI development at scale. (Word count: 289)

---

## 4. Community Hot Spots
- **Long-horizon VLA with native visual memory**: [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) addresses a key limitation of current VLA models by adding timestamped visual history and streaming inference, enabling multi-step manipulation tasks that require persistent context. This direction is critical for real-world deployment where robots must operate across extended, unscripted scenarios.
- **Open-source humanoid manipulation hardware**: [enactic/openarm](https://github.com/enactic/openarm) (3.4k stars) is a rapidly growing open-source humanoid arm designed for contact-rich tasks, filling a gap in accessible, hackable hardware for physical AI research. Its adoption signals strong demand for low-cost, customizable manipulators to complement the maturing VLA software ecosystem.
- **LLM agent standards for robotics**: The adoption of Anthropic Skills and MCP in robotic projects (e.g., [graph-robots/open-robot-skills](https://github.com/graph-robots/open-robot-skills), [rokbenko/quackd](https://github.com/rokbenko/quackd)) is an emerging cross-disciplinary direction that reuses the broader LLM agent toolchain for physical systems. This could dramatically expand the pool of developers capable of building robot agents.
- **Unified VLA evaluation infrastructure**: [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) provides a common framework to test any VLA model across any robot platform (simulated or real), addressing the long-standing pain point of fragmented, inconsistent benchmarks. Standardized evaluation will be critical to measuring meaningful progress and comparing VLA models fairly.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*