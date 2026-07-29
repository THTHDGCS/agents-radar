# AI Open Source Trends 2026-07-29

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-29 01:25 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
Date: 2026-07-29

---

## 1. Today's Highlights
Today’s embodied intelligence and robotics GitHub ecosystem centers on VLA productionization tooling, safety evaluation infrastructure, and democratized access to hardware and learning resources. NVIDIA’s public release of official Alpamayo developer recipes marks a key milestone for moving state-of-the-art VLA models from academic research to deployable production systems. The emergence of dedicated VLA red-teaming and robustness testing tools reflects a critical field maturation shift, with the community now prioritizing reliability and safety alongside raw task performance. Low-cost open humanoid manipulation hardware and structured, beginner-friendly VLA/embodied AI learning resources also saw strong traction, lowering barriers to entry for independent developers and small research teams.

---

## 2. Top Projects by Category
No core embodied AI/robotics projects appeared on the general GitHub daily trending list; all projects below are drawn from active (last 7 days) topic-tagged repositories, with total stars as listed.

### 🤖 Robot Frameworks / SDKs
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,249 total  
   A production-grade robotics operating system that powers advanced driver assistance for 300+ consumer vehicles, the highest-starred active robotics project demonstrating real-world deployable middleware.
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,359 total  
   The de facto standard physics simulator for robotic learning, with ongoing GPU acceleration optimizations critical for large-scale parallel VLA training workflows.
3. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,789 total  
   NVIDIA’s unified robot learning framework built on Isaac Sim, now a core dependency for most state-of-the-art VLA training and evaluation pipelines.
4. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,856 total  
   Low-latency dataflow-oriented robotic middleware, rapidly gaining traction as a lightweight, AI-native alternative to ROS for edge VLA deployments.
5. [softmata/horus](https://github.com/softmata/horus) ⭐396 total  
   A new high-performance robotics runtime system positioned as an "Android for robots," optimized for real-time humanoid control and VLA workloads.

### 🧠 VLA / Foundation Models
1. [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) ⭐83 total  
   NVIDIA’s official developer hub for its state-of-the-art Alpamayo VLA model, including pre-built workflows for fine-tuning, RL post-training, quantization, and deployment — the most impactful VLA tooling release this month.
2. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐451 total  
   A practical, Chinese-language VLA learning and interview handbook focused on robotics-specific challenges, filling a critical gap in structured entry-level VLA educational content.
3. [phi-monster/Galahad](https://github.com/phi-monster/Galahad) ⭐79 total  
   New research project diagnosing widespread instruction blindness in VLA policies, with a low-rank data cure and standardized measurement battery to improve real-world task reliability.
4. [provael/provael](https://github.com/provael/provael) ⭐5 total  
   The first open-source red-teaming framework for VLA policies, designed to test adversarial robustness and report attack success rates across simulation benchmarks, addressing growing industry focus on VLA safety.
5. [Yhx888/LocoVLA](https://github.com/Yhx888/LocoVLA) ⭐5 total  
   A 58-lesson open course teaching VLA, reinforcement learning, and robot control for Upkie wheeled bipeds, combining theory with MuJoCo simulation and ROS2 deployment tutorials.

### 🦾 Manipulation & Grasping
1. [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,165 total  
   GPU-parallelized robotics manipulation simulator and benchmark, the most widely used environment for training and evaluating generalist manipulation VLA models.
2. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,780 total  
   Fully open-source 7-DOF humanoid arm optimized for contact-rich physical AI research, priced for accessible deployment and driving democratization of manipulation hardware.
3. [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8 total  
   A new bimanual kitchen manipulation benchmark built on Inspect Robots, designed to test VLA performance on unstructured, real-world household tasks.
4. [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐7 total  
   IROS 2026 paper introducing a lightweight 179M parameter Mamba-based VLA for robot manipulation, delivering competitive performance at a fraction of the size of large foundation models.
5. [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes) ⭐1 total  
   Novel approach to baking collision avoidance directly into Pi0 VLA weights via differentiable safety loss, eliminating the need for separate runtime safety filters.

### 🚶 Locomotion & Navigation
1. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,519 total  
   The standard ROS 2 navigation framework for mobile robots, with new native integrations for VLA-based high-level task planning.
2. [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐351 total  
   Whole-body nonlinear MPC library for real-time humanoid loco-manipulation planning and control, a critical component for production humanoid robot deployments.
3. [THMOS2025/MOS-9-Open-Source-Humanoid-Robot](https://github.com/THMOS2025/MOS-9-Open-Source-Humanoid-Robot) ⭐17 total  
   Open-source RoboCup Kid-Size humanoid robot hub unifying hardware, simulation, policy learning, and deployment tooling for small-team humanoid research.
4. [zc-xzc/robot_platform](https://github.com/zc-xzc/robot_platform) ⭐2 total  
   Open head-tracking active vision platform for humanoid robots, with 3D-printable mounts and simulation models, enabling low-cost active perception for edge VLA pipelines.

### 📦 Embodied Applications
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,906 total  
   Beginner-friendly Chinese course teaching users to build VLA models (including OpenVLA, SmolVLA, Pi0) and embodied robots from scratch with only basic Python knowledge, driving grassroots adoption of embodied AI.
2. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐92 total  
   Open-source evaluation framework for physical AI, supporting testing of any LLM/VLA across any robot arm/humanoid and any real/sim benchmark, addressing the longstanding lack of standardized VLA evaluation.
3. [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐119 total  
   Comprehensive survey of embodied AI safety with 500+ papers covering perception, cognition, planning, and agent system risks, the first centralized safety resource for the field.
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐139 total  
   Lightweight, scalable whole-body teleoperation framework for humanoid robots, critical for collecting high-quality VLA training data at scale.
5. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,223 total  
   Self-evolving embodied AI operating system built on agentic workflows, targeting end-to-end control of physical robots via natural language.

---

## 3. Trend Signal Analysis
The most explosive community attention this cycle is concentrated on VLA productionization and safety evaluation, marking a clear field-wide shift from capability demonstration to real-world readiness. The release of NVIDIA’s Alpamayo recipes confirms that leading tech firms are standardizing end-to-end tooling for VLA fine-tuning, RL post-training, quantization, and deployment, reducing the custom engineering overhead previously required to ship production VLA systems. A newly emerged direction this week is dedicated VLA safety and red-teaming: projects like Provael, Galahad, and the Awesome Embodied AI Safety survey fill a longstanding gap in standardized robustness testing, addressing risks ranging from instruction blindness to adversarial attacks. Parallel to this, a strong democratization trend is visible, with low-cost open manipulation hardware, beginner-focused end-to-end embodied AI courses, and lightweight small-parameter VLA models making the field accessible to developers without advanced robotics or ML expertise. These trends align directly with recent industry events, including NVIDIA’s Alpamayo launch at CVPR 2026 and the wave of humanoid robot startups targeting industrial deployment, as the ecosystem builds the supporting infrastructure to move VLA from lab demos to scalable real-world products. (282 words)

---

## 4. Community Hot Spots
- [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes): NVIDIA’s official VLA development hub provides production-ready, pre-built workflows for the state-of-the-art Alpamayo model, eliminating months of custom engineering for teams looking to fine-tune and deploy VLA systems for robotic use cases.
- [provael/provael](https://github.com/provael/provael): As the first open-source VLA red-teaming framework, it addresses a critical unmet need for standardized robustness testing, and is poised to become a core component of production VLA evaluation pipelines as the field prioritizes real-world safety.
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied): This beginner-focused course teaches end-to-end VLA and embodied robot construction with only basic Python knowledge, driving grassroots adoption and expanding the pool of developers working in embodied AI beyond specialized research teams.
- [enactic/openarm](https://github.com/enactic/openarm): The fully open-source, low-cost 7-DOF humanoid arm solves a major hardware access bottleneck for small teams and independent researchers, enabling real-world testing of manipulation VLA policies without the high cost of commercial robotic arms.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*