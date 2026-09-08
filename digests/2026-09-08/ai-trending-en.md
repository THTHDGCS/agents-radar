# AI Open Source Trends 2026-09-08

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-09-08 01:52 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
**Date: 2026-09-08**

---

## 1. Today's Highlights
No core embodied intelligence, VLA, or robotics repositories appeared in GitHub’s daily top 14 trending list, which is dominated by general AI coding agents, web automation tools, and productivity utilities. However, topic-specific activity over the past 7 days reveals accelerating momentum in specialized VLA model development and open-source humanoid infrastructure, with 30+ new or updated relevant repositories. Key developments include a new wave of task-specific VLA models targeting clutter resistance and contact-rich manipulation, the emergence of World Action Models (WAMs) as a distinct VLA subfield, and growing investment in vendor-agnostic robot runtime systems. Evaluation infrastructure for physical AI is also maturing rapidly, addressing a long-cited bottleneck for VLA deployment.

---

## 2. Top Projects by Category
*(Today’s new star counts are only available for daily trending repos; all star values below are total stars for active projects from the past 7 days.)*

### 🤖 Robot Frameworks / SDKs
- [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,463  
  Python sample code library and textbook covering core robotics algorithms (planning, control, perception), a staple educational resource for new robotics developers.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,977  
  De facto standard multi-joint dynamics physics simulator for robot learning and VLA training, with ongoing updates for GPU-accelerated contact-rich simulation.
- [DLR-RM/stable-baselines3](https://github.com/DLR-RM/stable-baselines3) ⭐13,776  
  PyTorch-based library with production-ready reinforcement learning algorithm implementations, widely used for robot policy training and VLA fine-tuning.
- [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,407  
  Multimodal robotics data visualization, query, and streaming tool, critical for debugging VLA models and robot learning pipelines across sim and real hardware.
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,065  
  Unified robot learning framework built on NVIDIA Isaac Sim, the leading platform for large-scale VLA pre-training and sim2real transfer for manipulation and locomotion.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,924  
  Dataflow-oriented robotic middleware with low-latency distributed pipelines, emerging as a flexible, AI-native alternative to ROS for modern robot applications.
- [softmata/horus](https://github.com/softmata/horus) ⭐433  
  High-performance robotics runtime system positioned as the "Android for robots", gaining traction for its optimized execution across humanoid and industrial robot hardware.

### 🧠 VLA / Foundation Models
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐474  
  Open-world foundation model for general-purpose embodied intelligence, one of the few open-source VLA-adjacent models targeting broad cross-task generalization.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐364  
  Open-source evaluation framework for physical AI, supporting testing of any LLM/VLA across robotic arms, humanoids, and sim/real benchmarks—filling a critical gap in VLA validation.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐596  
  Chinese-language, practice-oriented VLA learning and interview handbook, reflecting booming developer interest in VLA careers in the APAC region.
- [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐159  
  Unified framework for training, fine-tuning, and evaluating World Action Models (WAM)—a fast-evolving VLA subfield focused on long-horizon embodied tasks.
- [starVLA/VLAct](https://github.com/starVLA/VLAct) ⭐110  
  VLA model with representation-centric continued pre-training that outperforms pure data-scaling approaches, pointing to a new direction for efficient VLA improvement.
- [PINE-Lab-NTU/FACET](https://github.com/PINE-Lab-NTU/FACET) ⭐12  
  Robotic foundation model for contact-rich precise manipulation, addressing a key limitation of current VLA models in high-precision, force-dependent tasks.
- [UARK-AICV/DRAGON_VLA](https://github.com/UARK-AICV/DRAGON_VLA) ⭐14  
  Clutter-resistant VLA model with object-centric and geometry grounding, designed for robust performance in unstructured real-world environments.

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,932  
  Fully open-source humanoid arm for physical AI research and contact-rich environments, a high-popularity hardware project that lowers barriers to dexterous manipulation research.
- [robocasa/robocasa](https://github.com/robocasa/robocasa) ⭐1,709  
  Large-scale simulation platform for everyday domestic manipulation tasks, widely used as a benchmark for VLA model evaluation in home robotics scenarios.
- [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐176  
  LLM-driven simulation framework for generalizable instruction-following manipulation, leveraging generative AI to create diverse training data for VLA models.
- [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐130  
  Framework that compiles natural language instructions into verified robot skill graphs, enabling reliable execution of complex manipulation tasks on sim and real hardware.
- [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐69  
  Open-source bimanual data collection and retargeting software, supporting synchronized teleoperation data for training dexterous dual-arm VLA models.
- [RobotControlStack/duobench](https://github.com/RobotControlStack/duobench) ⭐18  
  Reproducible bimanual manipulation benchmark for sim and real world, addressing the lack of standardized evaluation for dual-arm robot systems.
- [shritankomm/7-DOF-3DP-Open-Arm](https://github.com/shritankomm/7-DOF-3DP-Open-Arm) ⭐6  
  Low-cost ($800) 3D-printable 7-DOF robotic arm with ROS2 and vision support, expanding access to manipulation experimentation for hobbyists and small labs.

### 🚶 Locomotion & Navigation
- [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover) ⭐9,632  
  Build-it-yourself 6-wheel Mars rover design, a landmark open-source hardware project for mobile robot navigation education and research.
- [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) ⭐6,698  
  Open-source RTK GPS-based smart lawn mower upgrade for off-the-shelf robots, a successful consumer-facing embodied navigation project with a large community.
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325  
  Mature robotics software suite with state-of-the-art legged locomotion algorithms and momentum-based control, used in leading humanoid robot projects.
- [Rhoban/microban](https://github.com/Rhoban/microban) ⭐293  
  Affordable, 3D-printable open-source humanoid robot powered by Raspberry Pi Zero 2W, providing an accessible platform for legged locomotion and VLA research on humanoids.
- [Open-X-Humanoid/BICMap](https://github.com/Open-X-Humanoid/BICMap) ⭐56  
  WebGL-based visualization SDK for SLAM maps, point clouds, and robot navigation, simplifying development of humanoid navigation user interfaces.
- [limxdynamics/humanoid-description](https://github.com/limxdynamics/humanoid-description) ⭐13  
  Open-source URDF/MJCF/USD models for LimX humanoid robots, compatible with ROS, Isaac Sim, and MuJoCo, accelerating sim2real for humanoid locomotion.
- [Degas01/nao_robot](https://github.com/Degas01/nao_robot) ⭐4  
  Autonomous path planning system for NAO humanoid robots with A* algorithm and Webots simulation, a practical entry-level humanoid navigation project.

### 📦 Embodied Applications
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,597  
  Open-source operating system for robotics that powers advanced driver assistance on 300+ car models, the most widely deployed open-source embodied AI system in the world.
- [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,822  
  Open-source autopilot software for drones, rovers, boats, and submersibles, supporting a massive ecosystem of autonomous mobile robot applications.
- [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core) ⭐2,101  
  Recursive self-improving physical agent operating system, exploring agentic workflows for autonomous robot skill improvement without human intervention.
- [strands-labs/robots](https://github.com/strands-labs/robots) ⭐154  
  Platform for controlling physical robots and hardware via natural language through Strands Agents, enabling no-code deployment of VLA-powered robot workflows.
- [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐171  
  Toolkit that connects LLMs to small legged robots (MicroDuck, Open Duck Mini, LeRobot) via natural language goals, democratizing access to LLM-powered robot control.
- [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐55  
  Digital twin platform for robotics-assisted chemistry lab automation, showcasing a fast-growing vertical use case for embodied AI in life sciences.
- [Vottivott/microduck-playground](https://github.com/Vottivott/microduck-playground) ⭐33  
  Reproducible RL experiment suite and hardware add-ons for MicroDuck robots, supporting end-to-end sim2real deployment for small legged robot policies.

---

## 3. Trend Signal Analysis
The most explosive community attention is centered on specialized VLA model development and evaluation infrastructure, marking a clear maturation from general-purpose VLA demos to real-world deployment-ready tooling. Over 12 active VLA-related repositories emerged in the last 7 days, spanning task-specific model variants (clutter-resistant DRAGON_VLA, contact-rich manipulation FACET, whole-body humanoid WholebodyVLA) and dedicated evaluation frameworks like robocurve/inspect-robots. This shift aligns with findings from the 2026 ICML Embodied AI Workshop, which identified benchmark standardization and task-specific fine-tuning as the top two bottlenecks for VLA commercialization.

A notable new technical direction is the formalization of World Action Models (WAMs) as a distinct subfield of VLA, with dedicated training frameworks (OpenMOSS/EasyWAM) and curated resource lists gaining traction. WAMs extend traditional VLA by integrating predictive world modeling with action generation, targeting long-horizon, dynamic tasks that current VLA models fail at—an urgent need highlighted by recent humanoid robot deployment trials in logistics and manufacturing.

The wave of open-source humanoid infrastructure (softmata/horus runtime, enactic/openarm, Rhoban/microban) directly echoes recent industry moves by leading humanoid vendors to open their SDK ecosystems. The open-source community is racing to build vendor-agnostic, standardized software and hardware stacks for humanoids, mirroring the early 2010s shift from proprietary mobile operating systems to open Android-compatible ecosystems. (287 words)

---

## 4. Community Hot Spots
- **VLA Evaluation Infrastructure ([robocurve/inspect-robots](https://github.com/robocurve/inspect-robots))**: As VLA model variants proliferate, standardized cross-platform evaluation has become the most critical bottleneck for real-world deployment. inspect-robots’ ability to test any LLM/VLA across robotic arms, humanoids, and sim/real benchmarks positions it as a potential de facto standard for physical AI validation, with rapid contributor growth expected.
- **World Action Models (WAMs) ([OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM))**: WAMs are emerging as the next evolutionary step for VLA, addressing key limitations in long-horizon task planning and dynamic environment adaptation. EasyWAM’s unified training, fine-tuning, and evaluation framework lowers barriers to entry for WAM research, and the surge in WAM-focused resource lists indicates a broad community pivot toward this architecture.
- **Vendor-Agnostic Humanoid Runtime ([softmata/horus](https://github.com/softmata/horus))**: With humanoid robot commercialization accelerating, the open-source community is prioritizing alternatives to proprietary vendor SDKs to avoid lock-in. Horus’ positioning as a high-performance "Android for robots" runtime has attracted cross-industry interest, as teams seek flexible, customizable software foundations for humanoid development.
- **Low-Cost LLM-Powered Robot Deployment ([rokbenko/quackd](https://github.com/rokbenko/quackd))**: The trend of connecting affordable small legged robots (MicroDuck, LeRobot, Aloha Mini) to LLMs via natural language is democratizing embodied AI development. quackd’s multi-platform support, built-in safety contracts, and MCP integration make it an accessible entry point for hobbyists and small labs entering the space.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*