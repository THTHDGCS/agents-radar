# AI Open Source Trends 2026-08-01

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-08-01 01:46 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report | 2026-08-01

---

## 1. Today's Highlights
No general GitHub trending repositories met the relevance criteria for embodied intelligence, VLA, or robotics, with all key activity concentrated in active topic-tagged projects. The ecosystem sees growing momentum around VLA accessibility and safety, with NVIDIA releasing official developer recipes for its Alpamayo VLA foundation model alongside new open source tools for evaluating and red-teaming VLA policies across simulated and physical hardware. Humanoid robotics remains a core growth area, with new open source control stacks, teleoperation systems, and competitive benchmarking arenas targeting affordable platforms like the Unitree G1. Educational resources for VLA have also surged, including a full Chinese-language VLA engineer handbook and a hands-on course to build production VLA models for developers with only basic Python experience.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,857 total: Dataflow-Oriented Robotic Architecture middleware for low-latency, composable AI robotic application development, offering a modular, high-performance alternative to traditional ROS stacks for VLA deployment.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,813 total: Unified NVIDIA Isaac Sim-based framework for robot learning, with native support for VLA fine-tuning, RL training, and sim2real transfer for manipulators and humanoids.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,400 total: Industry-standard multi-joint dynamics physics simulator, the de facto tool for VLA training, humanoid locomotion testing, and contact-rich manipulation research.
- [softmata/horus](https://github.com/softmata/horus) ⭐402 total: New high-performance robotics runtime system positioned as an "Android for robots", optimized for low-latency VLA inference and edge physical hardware control.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐125 total: Lightweight, ROS-free sim2real framework for deploying VLA models and RL agents to common robot arms (Franka, UR5e, xArm) and humanoids (SO101).
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,363 total: Reinforcement learning infrastructure purpose-built for embodied and agentic AI, streamlining large-scale VLA training and cross-benchmark evaluation workflows.

### 🧠 VLA / Foundation Models
- [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) ⭐83 total: Official NVIDIA developer hub for the Alpamayo VLA foundation model, with ready-to-use recipes for fine-tuning, RL post-training, quantization, and edge deployment.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐459 total: Full Chinese-language, practice-oriented learning and interview handbook for VLA engineers, focused on robotics-specific challenges distinct from general CV/NLP.
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐123 total: New open-world general-purpose embodied intelligence foundation model, targeting cross-platform deployment across manipulators, humanoids, and mobile robots.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐104 total: Open source evaluation framework for physical AI, supporting testing of any LLM/VLA on any robot arm or humanoid across simulated and real-world benchmarks.
- [provael/provael](https://github.com/provael/provael) ⭐4 total: First dedicated open source red-teaming tool for VLA robot policies, generating adversarial scenarios and measuring attack success rates in simulation.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,945 total: Hands-on course for building production VLA models (OpenVLA, SmolVLA, Pi0) from scratch, targeted at developers with only basic Python knowledge.
- [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐121 total: Comprehensive survey of embodied AI safety risks, attacks, and defenses, curating over 500 papers across perception, planning, and agent system layers.

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,788 total: Fully open-source humanoid arm designed for contact-rich physical AI research and deployment, with open hardware designs and native MuJoCo/ROS integrations.
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,185 total: GPU-parallelized robotics manipulation simulator and benchmark suite, supporting large-scale VLA training for dexterous and contact-rich tasks.
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐43 total: Open-source software for synchronized bimanual teleoperation data collection and retargeting to any bimanual robot platform, a critical tool for VLA imitation learning.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐324 total: New standardized manipulation benchmark for evaluating VLA and RL policies across 100+ contact-rich task variants.
- [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes) ⭐1 total: Novel implementation of a Pi0 flow-matching VLA with collision avoidance baked into model weights via differentiable safety loss, eliminating the need for runtime safety filters.
- [chang-xinhai/Awesome-UMI](https://github.com/chang-xinhai/Awesome-UMI) ⭐13 total: Curated list of papers, datasets, and policies for the Universal Manipulation Interface (UMI) ecosystem, a leading framework for low-cost imitation learning for manipulation.

### 🚶 Locomotion & Navigation
- [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐352 total: Whole-body nonlinear model predictive control stack for real-time humanoid loco-manipulation planning and control, supporting combined walking and on-the-move manipulation.
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,280 total: Open-source robotics operating system currently deployed as an advanced driver assistance system for 300+ car models, the largest-scale production embodied AI system for mobile platforms.
- [mturan33/isaac-g1-ulc](https://github.com/mturan33/isaac-g1-ulc) ⭐16 total: Low-level RL controller for the Unitree G1 humanoid, trained in Isaac Sim for stable bipedal locomotion and zero-shot sim2real transfer.
- [KaushikSiva/robot-gym](https://github.com/KaushikSiva/robot-gym) ⭐0 total: New competitive embodied AI arena for the Unitree G1 humanoid, supporting AI vs AI, human vs AI, and multiplayer policy evaluation in MuJoCo.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,533 total: Industry-standard ROS 2 navigation framework for mobile robots, with newly added native integrations for VLA-based high-level path planning.

### 📦 Embodied Applications
- [strands-labs/robots](https://github.com/strands-labs/robots) ⭐112 total: Framework for controlling any physical robot hardware via natural language using Strands LLM/VLA agents, with out-of-the-box support for common manipulator and mobile robot platforms.
- [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8 total: End-to-end VLA agent for the FrodoBots Earth Rover Mini+, including a custom outdoor navigation ECoT dataset hosted on Hugging Face for mobile robot VLA training.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐143 total: Full-embodiment humanoid teleoperation system, enabling low-latency remote control of bipedal robots for large-scale VLA demonstration data collection.
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,353 total: Self-evolving embodied AI operating system built on agentic workflows, supporting continuous skill learning and deployment across heterogeneous robot hardware.
- [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover) ⭐9,548 total: Open-source, build-it-yourself 6-wheel Mars rover design, a popular low-cost platform for testing outdoor VLA and autonomous navigation policies.

---

## 3. Trend Signal Analysis
The most explosive community attention in today's embodied AI ecosystem is centered on VLA democratization and safety, catalyzed by NVIDIA's recent launch of its open Alpamayo VLA foundation model. Official developer recipes for Alpamayo fine-tuning, RL post-training, quantization, and edge deployment have drawn immediate researcher and practitioner interest, alongside a wave of complementary open source tools for cross-platform VLA evaluation and dedicated red-teaming of VLA robot policies. A notable new technical direction appearing this cycle is the integration of safety constraints directly into VLA weights via differentiable loss functions, as demonstrated by the LeRobot-SafetyCubes project, which eliminates the performance tradeoffs of traditional post-hoc runtime safety filters. Humanoid robotics remains tightly coupled to VLA advancement, with a surge in humanoid-specific VLA frameworks, low-level RL locomotion controllers, and competitive benchmarking arenas targeting affordable mass-market platforms like the Unitree G1. This aligns with recent industry announcements of near-term commercial humanoid deployments, as the open source community builds out the full stack from low-level control to high-level VLA reasoning to reduce deployment barriers for small teams.

---

## 4. Community Hot Spots
- **[NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes)**: As the first official developer toolkit for NVIDIA's state-of-the-art open VLA model, this repo cuts months of development work for teams looking to fine-tune and deploy Alpamayo on custom robot hardware.
- **VLA safety and evaluation tooling**: [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) and [provael/provael](https://github.com/provael/provael) address the fast-growing bottleneck of VLA robustness testing, making them essential for validating policies before physical hardware rollout.
- **Low-barrier VLA education**: [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) and [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) provide an accessible, hands-on path to VLA development for developers with no advanced robotics or ML background, filling a critical gap in Chinese-language embodied AI resources.
- **Affordable humanoid VLA stacks**: The convergence of whole-body VLA frameworks (WholebodyVLA), low-level RL controllers (isaac-g1-ulc), and competitive benchmarks (robot-gym) for the Unitree G1 creates a unique opportunity for small teams to build and test general-purpose humanoid agents with minimal upfront cost.
- **ROS-free VLA infrastructure**: [softmata/horus](https://github.com/softmata/horus) and [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) represent an emerging shift away from heavyweight traditional robotics middleware toward lighter, VLA-optimized runtimes for edge deployment.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*