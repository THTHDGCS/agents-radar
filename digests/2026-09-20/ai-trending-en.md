# AI Open Source Trends 2026-09-20

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-09-20 02:09 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report (2026-09-20)
---
## 1. Today's Highlights
Today’s embodied AI and robotics trending is led by [cactus-compute/needle](https://github.com/cactus-compute/needle), a tiny 2-bit automation foundation model optimized for edge deployment on robots, wearables, and microcontrollers, which gained 234 stars in a single day amid surging demand for on-device embodied intelligence. The VLA ecosystem continues to expand rapidly, with new releases spanning long-horizon memory augmentation, human video-based pretraining pipelines, and standardized evaluation frameworks for physical AI. Open hardware and software for humanoid manipulation and locomotion is also gaining traction, with projects lowering barriers to building and deploying real-world physical AI systems. Additionally, unified cross-platform robot control tools are simplifying deployment of LLM/VLA-powered heterogeneous robot fleets, signaling a maturing path from research to production.
---
## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
*(Control, simulation, planning, middleware, and tooling for robotics development)*
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,231 total  
  The de facto open-source physics simulator for contact-rich robot dynamics, foundational for VLA training, sim-to-real transfer, and humanoid locomotion research.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,171 total  
  Unified multi-physics robot learning framework with modular task design, critical for scaling VLA and reinforcement learning training in high-fidelity simulation.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,968 total  
  Low-latency dataflow-oriented robotic middleware for building composable AI-powered robot applications, gaining traction as a flexible alternative to ROS for embodied agent stacks.
- [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,478 total  
  Multimodal robotics data visualization and streaming tool, essential for debugging VLA pipelines, teleoperation workflows, and real-world robot deployment.
- [softmata/horus](https://github.com/softmata/horus) ⭐438 total  
  High-performance robotics runtime system positioned as an "Android for robots," standardizing software stacks across heterogeneous humanoid and industrial robot hardware.
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐5,295 total  
  Purpose-built reinforcement learning infrastructure for embodied and agentic AI, addressing scaling bottlenecks for large-batch robot RL and VLA training.
- [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,708 total  
  Leading embodied AI benchmark platform with 1,000+ household manipulation tasks, a standard testbed for evaluating general-purpose VLA and robot learning models.
### 🧠 VLA / Foundation Models
*(Vision-language-action models, world models, and embodied AI foundation models)*
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐2,047 total  
  Open-world foundation model for general-purpose embodied intelligence, a leading open VLA-aligned base model for physical AI and robot manipulation.
- [cactus-compute/needle](https://github.com/cactus-compute/needle) ⭐234 total (+234 today, newly launched)  
  Today’s top trending embodied AI project: a 2-bit, 8–29 MB automation foundation model with tool use and embedding capabilities, optimized for edge deployment on robots, microcontrollers, and wearables.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐555 total  
  Open-source evaluation framework for physical AI, supporting any LLM/VLA on any arm or humanoid robot across sim and real benchmarks—critical for standardized VLA performance measurement.
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐557 total  
  State-of-the-art VLA series that unifies visual understanding, generation, and action for robotic manipulation, with strong performance on real-world dexterous tasks.
- [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) ⭐62 total  
  VLA architecture with native video memory and streaming inference, solving key limitations of current VLA models for long-horizon robot manipulation tasks.
- [3587jjh/HuRo](https://github.com/3587jjh/HuRo) ⭐27 total (CoRL 2026)  
  Newly released work that robotizes human videos for scalable VLA pretraining, addressing the field’s critical data scaling bottleneck by repurposing massive existing human video datasets.
- [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐244 total  
  NVIDIA’s 34B multi-task foundation model for autonomous vehicle development, expanding VLA technology to large-scale embodied driving use cases.
### 🦾 Manipulation & Grasping
*(Dexterous hands, manipulation policies, teleoperation, and contact-rich task tooling)*
- [enactic/openarm](https://github.com/enactic/openarm) ⭐3,476 total  
  Fully open-source humanoid arm designed for contact-rich physical AI research, filling a critical gap in affordable, modifiable open hardware for VLA manipulation experiments.
- [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐68 total  
  Open-source bimanual data collection and retargeting software (HandUMI), enabling scalable VR teleoperation data generation for dexterous dual-arm manipulation training.
- [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐176 total (CVPR 2025)  
  LLM-driven simulation pipeline for generating generalizable instruction-following manipulation data, reducing the cost of building diverse VLA training datasets.
- [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐25 total  
  Deployment-focused fork of OpenPI for LimX TRON2 bimanual robots, bridging state-of-the-art VLA manipulation policies to real-world humanoid hardware.
- [XenseRobotics-AI/lerobot-xense](https://github.com/XenseRobotics-AI/lerobot-xense) ⭐20 total  
  LeRobot v5.1 fork supporting multiple industrial arms and tactile grippers with VR/SpaceMouse teleoperation, lowering barriers to building high-quality manipulation datasets.
- [graph-robots/open-robot-skills](https://github.com/graph-robots/open-robot-skills) ⭐45 total  
  Robot skill bundles compatible with Anthropic Agent Skills format for graph-as-policy manipulation frameworks, standardizing skill packaging across AI agent and robotics ecosystems.
### 🚶 Locomotion & Navigation
*(Legged robots, humanoid locomotion, autonomous navigation, and SLAM)*
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,685 total  
  The most widely deployed open-source robotics OS for passenger vehicles, delivering advanced driver assistance and autonomous navigation capabilities for 300+ car models.
- [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,895 total  
  De facto standard open-source autopilot software for drones, rovers, and underwater robots, supporting full autonomous navigation and control for mobile robotic systems.
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325 total  
  Leading open-source legged locomotion and momentum-based control stack, used in state-of-the-art humanoid, exoskeleton, and bipedal robot systems.
- [limxdynamics/tron2-robot-description](https://github.com/limxdynamics/tron2-robot-description) ⭐10 total  
  Open URDF/MuJoCo/USD models for the LimX TRON2A humanoid platform (dual-arm, bipedal, wheeled-leg variants), accelerating cross-platform humanoid locomotion research.
- [pal-robotics/kangaroo_robot](https://github.com/pal-robotics/kangaroo_robot) ⭐5 total  
  Open educational platform for learning walking locomotion control, designed to lower entry barriers for legged robotics research and development.
- [ershui2500/UniRoboGui](https://github.com/ershui2500/UniRoboGui) ⭐3 total  
  Open-source web GUI for Unitree G1 humanoids, supporting real-time telemetry, SLAM navigation, and joint debugging for humanoid deployment and testing.
### 📦 Embodied Applications
*(Real-world deployments, teleoperation, multi-robot systems, and vertical use cases)*
- [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐213 total  
  Unified CLI for controlling heterogeneous robot fleets with LLM/VLA brains, supporting Microduck, LeRobot, AlohaMini, and ROS-based platforms out of the box.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,770 total  
  Hands-on tutorial project that teaches developers to build an embodied robot from scratch and implement VLA models (OpenVLA, SmolVLA, Pi0), democratizing access to embodied AI development.
- [strands-labs/robots](https://github.com/strands-labs/robots) ⭐162 total  
  Low-code platform for controlling physical robots with natural language via Strands Agents, enabling rapid deployment of VLA-powered robot fleets for industrial and research use cases.
- [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8 total  
  VLA-powered edge rover agent (FrodoBots Earth Rover Mini+) with visual reasoning and autonomous navigation, a practical reference for building low-cost field embodied agents.
- [omrfrkkus/Adam-Humanoid-Robot-Showcase](https://github.com/omrfrkkus/Adam-Humanoid-Robot-Showcase) ⭐4 total  
  DIY 3D-printed humanoid robot showcase integrating Gemini, Llama, and computer vision for low-latency physical interaction, a reference design for hobbyist and small-scale embodied AI projects.
- [Orboh/DimOS_base_G1-TOYOTA-BODY-RESEARCH](https://github.com/Orboh/DimOS_base_G1-TOYOTA-BODY-RESEARCH) ⭐1 total  
  Vertical use case of a Unitree G1 humanoid performing agricultural okra harvesting using VLA and UMI diffusion policies, demonstrating real-world humanoid utility in unstructured environments.
---
## 3. Trend Signal Analysis
Edge-optimized embodied foundation models are seeing explosive community attention, led by the viral launch of [cactus-compute/needle](https://github.com/cactus-compute/needle)—a 2-bit, sub-30MB automation model for robots, wearables, and microcontrollers that gained 234 stars in a single day. This surge aligns with growing industry demand to deploy VLA and control policies on resource-constrained physical devices without cloud dependency, a key pain point highlighted by recent humanoid and industrial robotics launches emphasizing on-device latency, reliability, and data privacy.
A critical emerging direction is scalable VLA pretraining data generation beyond expensive robot teleoperation: the CoRL 2026 work [3587jjh/HuRo](https://github.com/3587jjh/HuRo) introduces a pipeline to robotize human videos for VLA training, addressing the field’s most pressing scaling bottleneck by unlocking massive existing human video datasets. Additionally, the growing ecosystem of LLM agent-compatible robot skill packages signals a new tech stack convergence between general AI agent tooling and robotics, standardizing how manipulation skills are discovered and deployed across heterogeneous hardware.
These trends follow recent NVIDIA Isaac 2026 and Figure AI updates that have catalyzed open-source investment in edge VLA, data infrastructure, and cross-hardware compatibility, as the global developer community races to replicate and extend closed commercial embodied AI systems.
---
## 4. Community Hot Spots
- 🔹 **[cactus-compute/needle](https://github.com/cactus-compute/needle)**: The day’s top trending embodied AI project, with a unique tiny 2-bit model design that enables VLA-like tool use and perception on microcontrollers and edge robots. It fills a major gap in the open-source ecosystem for on-device embodied intelligence, a fast-growing niche with few production-ready options.
- 🔹 **[3587jjh/HuRo](https://github.com/3587jjh/HuRo)**: A newly released CoRL 2026 work that converts human videos to robot-compatible training trajectories. It is likely to spark a wave of new VLA pretraining pipelines leveraging billions of hours of existing human video data, drastically reducing the cost of training general-purpose manipulation models.
- 🔹 **[enactic/openarm](https://github.com/enactic/openarm)**: A fully open-source humanoid arm with 3.4k+ stars, filling a critical gap in affordable, modifiable open hardware for contact-rich manipulation research. It is positioned to become the de facto open hardware reference for VLA manipulation experiments, similar to how Aloha popularized bimanual teleoperation.
- 🔹 **[rokbenko/quackd](https://github.com/rokbenko/quackd)**: A unified CLI for controlling heterogeneous robots with LLM/VLA brains, supporting nearly all popular open-source robot platforms. It addresses the growing pain point of fragmented robot control stacks, making it easier for developers to build cross-platform embodied agent applications without rewriting hardware-specific code.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*