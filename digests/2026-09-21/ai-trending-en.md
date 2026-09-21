# AI Open Source Trends 2026-09-21

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-09-21 02:10 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-09-21

---

## 1. Today's Highlights
Today’s embodied AI and robotics ecosystem sees surging interest in cross-environment agent infrastructure, with [trycua/cua](https://github.com/trycua/cua) leading the trending list at +1,018 daily stars for its open-source computer-use 2.0 drivers, cross-OS fleet management, and training/evaluation benchmarks. The VLA (Vision-Language-Action) space continues to mature rapidly, with new open-source releases tackling core bottlenecks: [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) adds native video memory for long-horizon manipulation, while [3587jjh/HuRo](https://github.com/3587jjh/HuRo) (accepted to CoRL 2026) enables scalable VLA pretraining by converting human videos to robot training data. Humanoid robotics development is accelerating, with a wave of new open-source hardware models, locomotion control stacks, and whole-body VLA solutions targeting both research and commercial deployment. Evaluation and data quality tools for physical AI are also emerging as high-priority community needs, as teams work to close the sim-to-real gap for real-world robot deployments.

---

## 2. Top Projects by Category
(Star data: total stars for 7-day active topic projects; total + daily new stars for today's trending projects)

### 🤖 Robot Frameworks / SDKs
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,241: The de facto standard multi-joint physics simulator for robotics research, widely used for VLA training, manipulation testing, and humanoid locomotion simulation.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,177: Unified multi-physics robot learning framework with support for NVIDIA Isaac Sim, MuJoCo, and PyBullet, critical for scalable VLA and locomotion policy training.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,970: Dataflow-oriented robotic middleware designed for low-latency, composable AI robotics applications, gaining traction as a ROS alternative for AI-native robot stacks.
- [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,906: Open-source flight/rover/submarine control stack supporting hundreds of vehicle platforms, a foundational tool for mobile robot navigation and locomotion research.
- [softmata/horus](https://github.com/softmata/horus) ⭐439: A high-performance robotics runtime system positioned as "Android for robots", with recent updates optimized for humanoid and industrial robot deployments.
- [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,480: Multimodal robotics data visualization, streaming, and querying tool, increasingly used for debugging VLA models and real-world robot telemetry.
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,729: The official ROS 2 navigation framework, the industry standard for mobile robot path planning, SLAM integration, and autonomous navigation deployment.

### 🧠 VLA / Foundation Models
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐2,055: An open-world general-purpose embodied intelligence foundation model, one of the highest-starred new VLA projects in the 7-day active list.
- [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) ⭐66: A VLA model with native video memory using timestamped visual history and streaming inference, addressing the critical gap of long-horizon robot manipulation.
- [3587jjh/HuRo](https://github.com/3587jjh/HuRo) ⭐27: CoRL 2026 accepted work that robotizes human videos for scalable VLA pretraining, offering a low-cost path to expanding VLA training datasets.
- [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐3: A unified VLA framework for seamless humanoid loco-manipulation, representing the emerging trend of whole-body control via vision-language models.
- [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐246: NVIDIA's open 34B multi-task foundation model for autonomous vehicle development, expanding VLA technology to the autonomous driving domain.
- [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐304: A unified framework for training, fine-tuning, and evaluating World Action Models (WAMs), lowering the barrier to building custom VLA variants.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐570: Open-source evaluation framework for physical AI that supports testing any LLM/VLA on any arm/humanoid across sim/real benchmarks, addressing a key VLA adoption bottleneck.

### 🦾 Manipulation & Grasping
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐597: A widely used manipulation benchmark platform, critical for standardized evaluation of dexterous robotic grasping and contact-rich task performance.
- [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐176: CVPR 2025 work that uses LLMs to drive simulation for generalizable instruction-following manipulation, bridging natural language and physical robot skills.
- [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐141: A framework that compiles natural language instructions into verified robot skill graphs, enabling reliable execution of complex manipulation tasks on sim/real robots.
- [XenseRobotics-AI/lerobot-xense](https://github.com/XenseRobotics-AI/lerobot-xense) ⭐20: A LeRobot v5.1 fork adding support for Flexiv Rizon4, Elite CS66, and tactile grippers, expanding accessible bimanual manipulation research tools.
- [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐68: Open-source HandUMI software for synchronized bimanual data collection and cross-robot retargeting, solving a key data bottleneck for dual-arm manipulation.
- [RoboTwin-Platform/RMBench](https://github.com/RoboTwin-Platform/RMBench) ⭐215: A memory-dependent manipulation benchmark built on the RoboTwin platform, testing long-horizon manipulation skills that require state memory.

### 🚶 Locomotion & Navigation
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325: Industry-leading legged locomotion and humanoid control software with momentum-based optimization, used in top humanoid robot platforms.
- [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐117: Omni-Modal Motion Generation framework for generalist humanoid control, enabling cross-modal (text, video, audio) motion generation for bipedal robots.
- [limxdynamics/tron2-robot-description](https://github.com/limxdynamics/tron2-robot-description) ⭐11: Open-source URDF, MuJoCo XML, and USD models for the LimX TRON2A humanoid series (6 variants, ROS 1/2 ready), lowering the barrier to humanoid simulation research.
- [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,663: GPU-accelerated physics simulation engine built on NVIDIA Warp, optimized for roboticists working on contact-rich locomotion and manipulation tasks.
- [pal-robotics/kangaroo_robot](https://github.com/pal-robotics/kangaroo_robot) ⭐5: An open-source bipedal robot platform designed specifically for learning walking locomotion, targeted at academic and hobbyist researchers.
- [AlessioPagliai/primo](https://github.com/AlessioPagliai/primo) ⭐3: A fully open-source 3D-printed humanoid robot with 30 RobStride actuators and Jetson Thor compute, representing the growing DIY humanoid developer movement.

### 📦 Embodied Applications
- [trycua/cua](https://github.com/trycua/cua) ⭐1,018 total (+1,018 today, new repository): Open-source infrastructure for scaling computer-use 2.0 agents, with cross-OS drivers, fleet management, and training benchmarks, leading today's trending embodied AI projects.
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,694: The most starred open-source robotics OS, currently deployed as an advanced driver assistance system on 300+ car models, a leading real-world embodied AI deployment.
- [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐219: A unified CLI for controlling multiple robot platforms (LeRobot, AlohaMini, Unitree, etc.) with LLM brains, supporting cross-robot collaboration and safety contracts.
- [physiclaw/PhysiClaw](https://github.com/physiclaw/PhysiClaw) ⭐374: An AI agent that physically operates smartphones using a robotic gripper, mimicking human interaction with mobile devices for real-world testing.
- [strands-labs/robots](https://github.com/strands-labs/robots) ⭐162: Natural language control framework for physical robots via Strands Agents, enabling non-technical users to command robot hardware with plain text.
- [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8: A VLA-powered Earth rover agent that sees, thinks, and drives a FrodoBots platform, with a public real-world dataset on Hugging Face.
- [Orboh/DimOS_base_G1-TOYOTA-BODY-RESEARCH](https://github.com/Orboh/DimOS_base_G1-TOYOTA-BODY-RESEARCH) ⭐1: A practical deployment of Unitree G1 humanoid for agricultural okra harvesting, combining YOLO detection, inverse kinematics, and UMI diffusion policies.

---

## 3. Trend Signal Analysis
The most explosive community attention this period is focused on **embodied agent infrastructure** spanning both digital computer-use and physical robot deployments. Breakout trending project [trycua/cua](https://github.com/trycua/cua) gained over 1,000 stars in a single day, reflecting surging developer demand for standardized drivers, fleet orchestration, and benchmarking tools for agents that interact with real or digital environments.

A clear new direction gaining traction is **memory-augmented VLA and low-cost pretraining data pipelines**. Projects like OpenBMB/SimpleMemVLA (native video memory for long-horizon manipulation) and 3587jjh/HuRo (human video robotization for scalable VLA pretraining, accepted to CoRL 2026) directly address two critical VLA bottlenecks: limited task duration and prohibitively expensive real-robot training data. Another emerging stack is **unified whole-body VLA for humanoid loco-manipulation**, which combines locomotion and manipulation control under a single vision-language model.

These trends align with recent industry shifts: leading humanoid OEMs (LimX, Unitree) are open-sourcing hardware models and software stacks to grow developer ecosystems, while the broader AI community is expanding VLA use cases beyond industrial manipulation to autonomous driving, mobile robotics, and digital computer-use agents. Evaluation tools for physical AI are also proliferating as the community prioritizes closing the sim-to-real gap for commercial deployments. (Word count: 282)

---

## 4. Community Hot Spots
- **Memory-augmented VLA architectures (e.g., [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA))**: Long-horizon task performance is the biggest barrier to VLA real-world adoption, and native visual memory designs are emerging as a high-potential solution to extend task duration from seconds to minutes.
- **Open-source humanoid full stacks (e.g., [limxdynamics/tron2-robot-description](https://github.com/limxdynamics/tron2-robot-description), [AlessioPagliai/primo](https://github.com/AlessioPagliai/primo))**: As humanoid robotics enters early commercialization, the growing set of open hardware models, control stacks, and VLA integration tools is lowering the barrier for small teams and independent researchers to build and test humanoid systems.
- **Physical AI evaluation frameworks (e.g., [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots))**: Standardized, cross-platform evaluation of VLA and robot policies is a critical unmet need, and projects supporting sim/real, multi-hardware testing are likely to see rapid community adoption as the field matures.
- **VLA pretraining data tools (e.g., [3587jjh/HuRo](https://github.com/3587jjh/HuRo), [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw))**: Scarcity of high-quality robot training data is the top bottleneck for VLA scaling, and tools that repurpose human video data or simplify bimanual data collection are poised to accelerate VLA model performance gains.
- **Digital-physical embodied agent convergence (e.g., [trycua/cua](https://github.com/trycua/cua))**: Computer-use (digital embodied) agents share core challenges with robotics (action space standardization, benchmarking, fleet management), and cross-pollination between the two communities is driving rapid innovation in shared infrastructure.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*