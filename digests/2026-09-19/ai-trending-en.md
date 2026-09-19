# AI Open Source Trends 2026-09-19

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-09-19 02:04 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-09-19

---

## 1. Today's Highlights
Today’s embodied AI and robotics ecosystem shows concentrated progress in VLA (Vision-Language-Action) model accessibility, humanoid manipulation tooling, and safety evaluation, even as no core robotics projects broke into the general GitHub top 17 trending list. Open-source VLA development is expanding across the stack, from a new open-world embodied foundation model (`dexmal/opendm`) to memory-optimized VLA architectures for long-horizon tasks and human video-based pretraining pipelines accepted at CoRL 2026. Humanoid robotics hardware and deployment tooling are also democratizing, with a fully open-source humanoid arm platform (`enactic/openarm`) and VLA policy deployment forks for LimX’s TRON2 robot lowering barriers to physical AI research. Safety and evaluation for embodied systems are emerging as high-priority focus areas, with new frameworks for benchmarking VLA models across sim/real robot platforms and red-teaming robot policies to measure attack susceptibility.

---

## 2. Top Projects by Category
> Note: Today's new star counts are only available for repositories on the general GitHub trending list; no core embodied AI/robotics repos appeared on the general trending list today, so only total star counts are listed below.

### 🤖 Robot Frameworks / SDKs
(Control, simulation, planning, middleware, training infrastructure)
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — Total stars: 8,164. A unified robot learning framework with multi-physics and multi-renderer support, serving as a de facto standard for scalable simulation-based robot training for both manipulation and locomotion tasks.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) — Total stars: 15,215. A widely adopted general-purpose multi-joint dynamics simulator with contact modeling, foundational to most modern robotics and embodied AI simulation workflows.
- [dora-rs/dora](https://github.com/dora-rs/dora) — Total stars: 3,966. A dataflow-oriented robotic middleware designed for AI-native robotic applications, offering low-latency, composable, and distributed pipeline support for complex embodied systems.
- [RLinf/RLinf](https://github.com/RLinf/RLinf) — Total stars: 5,288. A dedicated reinforcement learning infrastructure platform built specifically for embodied and agentic AI, streamlining RL training workflows for robot learning teams.
- [newton-physics/newton](https://github.com/newton-physics/newton) — Total stars: 5,650. A GPU-accelerated physics simulation engine built on NVIDIA Warp, optimized for roboticists and simulation researchers working on high-throughput robot learning.
- [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) — Total stars: 295. A unified framework for training, fine-tuning, and evaluating World Action Models (WAMs), filling a gap in standardized tooling for next-generation embodied foundation model development.

### 🧠 VLA / Foundation Models
(Vision-language-action models, world models, VLA resources, evaluation)
- [dexmal/opendm](https://github.com/dexmal/opendm) — Total stars: 1,613. An open-world foundation model for general-purpose embodied intelligence, representing a growing push toward fully open, generalist robot foundation models accessible to the broader community.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) — Total stars: 628. A comprehensive Chinese-language, practice-oriented learning and interview handbook for VLA engineers, addressing the rapidly growing demand for VLA-specific educational resources.
- [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) — Total stars: 244. NVIDIA’s open 34B multi-task foundation model for autonomous vehicle development, extending VLA-like multi-task foundation model paradigms to the autonomous driving robotics domain.
- [zju3dv/INTACT-JEPA](https://github.com/zju3dv/INTACT-JEPA) — Total stars: 195. An isomorphic intent-to-action learning framework for search-free world models, advancing the state of the art in efficient world model-based robot planning.
- [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) — Total stars: 55. A VLA architecture with native video memory using timestamped visual history and streaming inference, enabling long-horizon robot manipulation tasks that require extended context.
- [3587jjh/HuRo](https://github.com/3587jjh/HuRo) — Total stars: 26. A CoRL 2026-accepted project that robotizes human videos for scalable VLA pretraining, offering a new data pipeline to address the critical VLA training data bottleneck.

### 🦾 Manipulation & Grasping
(Dexterous hands, grasp generation, contact-rich tasks, manipulation-specific VLA)
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) — Total stars: 585. The official repository for the RoboDojo manipulation benchmark, providing a standardized testbed for evaluating generalizable robot manipulation capabilities.
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) — Total stars: 556. A VLA model series that unifies understanding, generation, and action for robotic manipulation, showcasing the integration of multi-modal capabilities into task-specific VLA systems.
- [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) — Total stars: 176. A CVPR 2025-accepted project that uses LLM-driven simulation to generate generalizable instruction-following manipulation data, reducing the cost of real-world manipulation data collection.
- [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) — Total stars: 68. Open-source software for synchronized bimanual manipulation data collection and retargeting to any dual-arm robot, supporting calibration, QA, replay, and teleoperation workflows.
- [graph-robots/open-robot-skills](https://github.com/graph-robots/open-robot-skills) — Total stars: 44. Skill and tool bundles for graph-as-policy manipulation systems, compatible with the Anthropic Agent Skills format, bridging general AI agent skill standards with robot manipulation.
- [XenseRobotics-AI/xense-openpi](https://github.com/XenseRobotics-AI/xense-openpi) — Total stars: 16. An adaptation of the π₀/π₀.5 VLA model series for Xense’s dual-arm manipulation platforms, enabling fine-tuning and real-world deployment of state-of-the-art VLA policies on commercial hardware.

### 🚶 Locomotion & Navigation
(Legged robots, humanoid motion, autonomous navigation, drone/rover control)
- [commaai/openpilot](https://github.com/commaai/openpilot) — Total stars: 63,686. An open-source robotics OS for advanced driver assistance systems, supporting 300+ car models and representing one of the most widely deployed open-source mobile robotics platforms in the world.
- [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) — Total stars: 15,888. A mature open-source flight controller suite for planes, copters, rovers, and underwater robots, serving as the backbone of countless DIY and commercial drone/rover projects.
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) — Total stars: 325. A leading open-source robotics software stack with legged locomotion algorithms and momentum-based control, used in world-class humanoid and legged robot systems.
- [RealXiaoze/humanoid-motion-intelligence](https://github.com/RealXiaoze/humanoid-motion-intelligence) — Total stars: 562. A comprehensive knowledge base of humanoid motion intelligence papers, open-source projects, industry updates, and career resources, catering to the fast-growing humanoid robotics workforce.
- [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) — Total stars: 117. The official repository for OMG, an omni-modal motion generation model for generalist humanoid control, advancing whole-body humanoid motion generation capabilities.
- [rokbenko/quackd](https://github.com/rokbenko/quackd) — Total stars: 211. A unified CLI tool for controlling multiple robot platforms (including Microduck, LeRobot, and humanoids) with LLM brains, enabling multi-robot coordination and cross-platform robot development.

### 📦 Embodied Applications
(Sim2real, teleoperation, hardware, deployment, evaluation platforms)
- [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) — Total stars: 1,706. A flagship embodied AI research platform with 1,000 household tasks, serving as a standard benchmark for testing real-world generalist robot capabilities.
- [enactic/openarm](https://github.com/enactic/openarm) — Total stars: 3,462. A fully open-source humanoid arm designed for physical AI research and contact-rich task deployment, lowering the barrier to entry for high-quality manipulation hardware research.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) — Total stars: 536. An open-source physical AI evaluation platform that lets users test any LLM or VLA model on any arm or humanoid robot across simulated and real-world benchmarks.
- [Phyzicalorg/Phyzical_org](https://github.com/Phyzicalorg/Phyzical_org) — Total stars: 292. A browser-based teleoperation data collection platform for embodied AI, providing elizaOS-compatible episodes and onchain data provenance for robot training datasets.
- [FastCrest/tether](https://github.com/FastCrest/tether) — Total stars: 84. An open-source edge-to-cloud AI deployment CLI for robotics, supporting Jetson, RTX, Apple Silicon, and AMD hardware with hybrid edge-cloud inference and parity verification.
- [strands-labs/robots](https://github.com/strands-labs/robots) — Total stars: 161. A platform that lets users control physical robots and hardware via natural language through Strands Agents, bringing no-code robot control to general AI agent ecosystems.

---

## 3. Trend Signal Analysis
The most explosive community attention in embodied AI today is concentrated on VLA ecosystem democratization and humanoid robot enablement. A wave of new projects spans every layer of the VLA stack: from open-source generalist foundation models and memory-augmented VLA architectures to pretraining data pipelines, standardized evaluation tools, and deployment frameworks for commercial robot hardware. This reflects a broader shift from VLA being a niche research area to a maturing engineering discipline with growing developer and industry demand.

Newly emerging tech directions include the integration of general AI agent standards (such as Anthropic’s Agent Skills format) into robot manipulation stacks, creating a bridge between LLM agent tooling and physical robot control. Additionally, human video-to-robot pretraining pipelines (exemplified by the CoRL 2026-accepted HuRo project) are gaining traction as a solution to the critical VLA training data bottleneck, offering a scalable alternative to expensive robot teleoperation data.

These trends align closely with recent industry and research milestones: the upcoming CoRL 2026 conference is driving a surge of open-source robot learning releases, while the 2026 commercialization push for humanoid robots is prompting hardware vendors including LimX Dynamics and Xense Robotics to release open-source VLA deployment tools to build developer ecosystems around their platforms. (287 words)

---

## 4. Community Hot Spots
- **Memory-augmented VLA architectures (e.g., [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA))**: Long-horizon task performance is a major barrier to real-world VLA deployment, and native video memory with streaming inference offers a practical path to extending VLA context windows without excessive compute overhead.
- **Human video-based VLA pretraining (e.g., [3587jjh/HuRo](https://github.com/3587jjh/HuRo))**: The scarcity of high-quality robot interaction data is the biggest bottleneck for scaling VLA models; repurposing massive existing human video datasets could unlock orders of magnitude more training data for generalist robot models.
- **Open-source humanoid manipulation hardware (e.g., [enactic/openarm](https://github.com/enactic/openarm))**: High-cost proprietary robot arms have limited access to manipulation research; fully open hardware designs with contact-rich capability will democratize physical AI experimentation and accelerate iterative development.
- **VLA safety and red-teaming (e.g., [provael/provael](https://github.com/provael/provael), [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots))**: As VLA models move from sim to real-world deployment, standardized evaluation and adversarial testing frameworks are critical to ensuring safe, reliable operation in unstructured environments, making this a fast-growing high-impact area.
- **Cross-platform LLM-powered robot control (e.g., [rokbenko/quackd](https://github.com/rokbenko/quackd))**: Unified interfaces for controlling diverse robot platforms with large language models will lower the barrier to building multi-robot systems and enable transfer of agent skills across different hardware form factors.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*