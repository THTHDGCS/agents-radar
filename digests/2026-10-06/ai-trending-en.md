# AI Open Source Trends 2026-10-06

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-10-06 03:40 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
*Date: 2026-10-06*

---

## 1. Today's Highlights
Today’s most notable trending robotics project is [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad), which gained 437 new stars by enabling AI agents to generate CAD models, filling a critical gap between software agents and physical world design for embodied intelligence workflows. The community is seeing a surge in top-tier conference-backed VLA and humanoid robotics projects, including CoRL 2026 Oral work [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) (humanoid soccer shooting) and NeurIPS 2026 paper [starVLA/VLAct](https://github.com/starVLA/VLAct) (representation-centric VLA pre-training), signaling rapid academic progress translating to open-source tooling. Industry-led open action model ecosystems are expanding, with NVIDIA’s [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) (Alpamayo fine-tuning/deployment tooling) and Black Forest Labs’ [black-forest-labs/flux-action](https://github.com/black-forest-labs/flux-action) (open-weight 7B world action model) making generalized robot action models more accessible to developers. Evaluation infrastructure for physical AI is emerging as a high-priority area, with projects like [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) (cross-hardware VLA/robot evals) and [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) (sim-real manipulation benchmarks) addressing a key bottleneck for VLA model deployment.

---

## 2. Top Projects by Category

### 🤖 Robot Frameworks / SDKs
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab): ⭐8,285 total | Unified robot learning framework with multi-physics and multi-renderer support, serving as a de facto standard for scalable robot simulation and policy training across academia and industry.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco): ⭐15,474 total | Industry-standard multi-joint dynamics simulator with contact modeling, widely used for humanoid, manipulation, and legged robot research, with ongoing updates for GPU-accelerated MJX workflows.
- [dora-rs/dora](https://github.com/dora-rs/dora): ⭐3,993 total | Dataflow-oriented robotic middleware built in Rust, designed for low-latency, composable AI robotic applications, gaining traction as a modern alternative to ROS for AI-native robot stacks.
- [RLinf/RLinf](https://github.com/RLinf/RLinf): ⭐5,441 total | Reinforcement learning infrastructure purpose-built for embodied and agentic AI, streamlining pipeline setup for training VLA and locomotion policies at scale.
- [omnilink-tech/omnisim](https://github.com/omnilink-tech/omnisim): ⭐186 total | Open-source robotics simulator tailored for coding agents, with HTTP/JSON + MCP control, Newton physics, and ROS 2 support, addressing the growing need for agent-accessible simulation environments.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2): ⭐4,765 total | Mature ROS 2 navigation framework with SLAM, path planning, and obstacle avoidance capabilities, the standard open-source stack for mobile robot navigation deployments.

### 🧠 VLA / Foundation Models
- [dexmal/opendm](https://github.com/dexmal/opendm): ⭐2,205 total | Open-world foundation model for general-purpose embodied intelligence, one of the highest-starred open VLA-adjacent models targeting cross-task embodied reasoning.
- [black-forest-labs/flux-action](https://github.com/black-forest-labs/flux-action): ⭐133 total | Open-weight 7B world action model from Black Forest Labs, supporting action prediction for robots (DROID, SO-101), simulators, and games, marking a new entrant in open action foundation models.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): ⭐643 total | Open-source evaluation framework for physical AI, enabling testing of any LLM/VLA model on any arm or humanoid robot across sim and real benchmarks, filling a critical gap in VLA model validation.
- [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM): ⭐396 total | Unified framework for training, fine-tuning, and evaluating World Action Models, lowering the barrier for developers to build and iterate on custom action models for robotics.
- [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes): ⭐196 total | NVIDIA’s official developer hub for the Alpamayo action model, providing pre-built recipes for fine-tuning, RL post-training, quantization, and deployment, signaling NVIDIA’s push into open VLA tooling.
- [starVLA/VLAct](https://github.com/starVLA/VLAct): ⭐139 total | NeurIPS 2026 accepted work on representation-centric continued pre-training for VLA models, challenging the dominant data-scaling paradigm and offering a new path to improve VLA performance.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook): ⭐675 total | All-Chinese, practice-oriented learning and interview handbook for VLA engineers, reflecting the rapidly growing talent demand and community interest in VLA in the Chinese tech ecosystem.

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm): ⭐3,574 total | Fully open-source humanoid arm designed for physical AI research and contact-rich environment deployment, a leading open hardware option for dexterous manipulation research.
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo): ⭐672 total | Unified simulation-and-real benchmark for comprehensive evaluation of generalist robot manipulation policies, enabling standardized comparison of VLA and imitation learning models across common robot platforms.
- [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw): ⭐75 total | Open-source HandUMI software for synchronized bimanual data collection and retargeting to any bimanual robot, addressing the shortage of accessible bimanual manipulation data tools.
- [XPolicyLab/XPolicyLab](https://github.com/XPolicyLab/XPolicyLab): ⭐395 total | Library integrating over 50 advanced manipulation policies, winner of the IROS 2026 ScaleInfra Workshop Best Tool Paper, providing a one-stop resource for manipulation policy development.
- [XenseRobotics-AI/lerobot-xense](https://github.com/XenseRobotics-AI/lerobot-xense): ⭐20 total | LeRobot v5.1 fork adding support for Flexiv Rizon4, Elite CS66, ARX5, and tactile grippers (single and bimanual), expanding the open-source robot learning ecosystem to more commercial hardware.

### 🚶 Locomotion & Navigation
- [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc): ⭐380 total | Whole-body nonlinear MPC framework for real-time humanoid loco-manipulation planning and control, a high-performance open-source option for humanoid whole-body motion control.
- [RealXiaoze/humanoid-motion-intelligence](https://github.com/RealXiaoze/humanoid-motion-intelligence): ⭐617 total | Curated knowledge base of humanoid motion intelligence papers, open-source projects, industry updates, and career resources, reflecting the booming humanoid locomotion field.
- [lok-i/vibe](https://github.com/lok-i/vibe): ⭐47 total | Post-training humanoid whole-body trackers for perceptive control tasks, offering a new approach to improving humanoid motion tracking performance without full retraining.
- [DeRuiChen258/Unitree_Low-Level_Balance](https://github.com/DeRuiChen258/Unitree_Low-Level_Balance): ⭐1 total | Open-source low-level balance and multi-action adaptive system for the Unitree G1 humanoid, including teacher policy reuse and skill primitive composition for contact-rich tasks like heavy object lifting.
- [pal-robotics/kangaroo_robot](https://github.com/pal-robotics/kangaroo_robot): ⭐5 total | Open-source educational robot designed for learning walking locomotion, lowering the barrier for beginners to get started with legged robot control.

### 📦 Embodied Applications
- [commaai/openpilot](https://github.com/commaai/openpilot): ⭐63,825 total | The most starred open-source robotics project, an operating system for robotics that currently upgrades driver assistance on 300+ supported cars, a widely deployed example of embodied AI at scale.
- [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad): ⭐17,496 total | +437 today | Trending project that grants AI agents CAD generation capabilities, bridging the gap between software agents and physical design workflows critical for embodied intelligence and robotic manufacturing.
- [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core): ⭐2,718 total | Recursive self-improving physical agent operating system that enables agents to self-optimize via agentic workflows, exploring a new paradigm for autonomous physical agent development.
- [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo): ⭐55 total | CoRL 2026 Oral accepted work implementing accurate, stable, and powerful humanoid soccer shooting, demonstrating advanced humanoid loco-manipulation capabilities in a dynamic, contact-rich task.
- [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix): ⭐62 total | Digital twin platform for robotics-assisted chemistry lab automation, showcasing embodied AI’s expanding use case in scientific research and lab automation verticals.
- [Justin-Riekehof/zeroth-01-build](https://github.com/Justin-Riekehof/zeroth-01-build): ⭐3 total | Open-source build log and software for the K-Scale Zeroth-01 3D-printed humanoid, with MuJoCo/ksim RL training and sim-to-real deployment on Raspberry Pi 4, advancing accessible DIY humanoid robotics.

---

## 3. Trend Signal Analysis
The fastest-growing area in today’s embodied AI ecosystem is open VLA (Vision-Language-Action) and world action model tooling, paired with standardized evaluation infrastructure for physical AI. Driven by both industry and academic contributions, this trend signals a shift from early VLA model prototyping to accessible, deployable stacks: projects like NVIDIA’s Alpamayo recipes and Black Forest Labs’ FLUX 3 Action lower barriers to fine-tuning and deploying action models, while evaluation frameworks like inspect-robots and RoboDojo address a longstanding bottleneck of standardized cross-hardware VLA testing.
A notable new direction is the integration of traditional engineering tools (CAD, simulation) with agent-native interfaces. The viral 437-star daily growth of text-to-cad demonstrates strong demand for embodied agents that can interact with physical design workflows, while omnisim’s MCP/HTTP API for simulation enables coding agents to directly control and test robots in virtual environments.
These releases align with upcoming top-tier robotics conferences (CoRL 2026, NeurIPS 2026), where humanoid loco-manipulation and VLA efficiency are core themes. They also mirror broader industry momentum around humanoid robotics commercialization, as open hardware (openarm) and low-cost sim2real humanoid builds (Zeroth-01) expand access to physical AI research beyond large corporate labs.

---

## 4. Community Hot Spots
- **[earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)**: The only trending robotics repo today (437 new stars) fills a unique gap between AI agents and physical design. Developers focused on embodied agents for manufacturing, robotics prototyping, or hardware design should track this project as it evolves to support more complex CAD workflows and agent integrations.
- **[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)**: As VLA models proliferate, standardized evaluation is becoming a critical pain point. This cross-hardware, cross-benchmark eval framework is well-positioned to become a community standard for testing physical AI models, making it a high-impact project for VLA researchers and robot developers.
- **Humanoid manipulation open tooling** (represented by [enactic/openarm](https://github.com/enactic/openarm) and [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw)): The combination of open-source humanoid arm hardware and bimanual data collection software lowers the barrier to entry for dexterous humanoid manipulation research, a field historically limited by high hardware and data collection costs.
- **[black-forest-labs/flux-action](https://github.com/black-forest-labs/flux-action)**: Black Forest Labs’ entry into the world action model space brings a new open-weight 7B model to robotics, competing with existing VLA offerings. Its support for both robot and game action prediction suggests potential cross-domain transfer, making it a key project to watch for general-purpose action model development.
- **Agent-native simulation** (represented by [omnilink-tech/omnisim](https://github.com/omnilink-tech/omnisim)): Simulation with MCP/HTTP APIs for coding agents is an emerging category that enables general AI agent developers to build and test robot workflows without specialized robotics expertise, potentially democratizing robot application development.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*