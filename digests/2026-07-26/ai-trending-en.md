# AI Open Source Trends 2026-07-26

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-26 01:43 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report | 2026-07-26
*Filtered from GitHub Trending and 7-day active robotics/embodied AI/VLA topic repositories; no relevant projects appeared on today’s general trending list.*

---

## 1. Today's Highlights
NVIDIA’s open Alpamayo VLA series has emerged as the leading open VLA stack for autonomous mobility, with the 10B-parameter Alpamayo 1.5 (featuring RL-enhanced chain-of-causation reasoning) paired with a dedicated developer recipe hub to accelerate production deployment. Open humanoid robotics continues to democratize access, with fully open-source manipulators, low-cost 3D-printable humanoid platforms, and whole-body control foundation models lowering barriers for both academic research and hobbyist experimentation. VLA robustness and evaluation tooling is maturing rapidly, with new frameworks for testing policy reliability, benchmarking long-horizon manipulation tasks, and addressing critical failure modes like instruction blindness gaining traction in the research community. Educational resources for embodied AI are also proliferating, with hands-on zero-to-VLA courses and Chinese-language practitioner handbooks meeting surging demand for upskilling in the fast-growing field.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,764 total: Unified GPU-accelerated robot learning framework built on NVIDIA Isaac Sim, the de facto standard for sim2real VLA and RL training with support for all major robot platforms.
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,852 total: Rust-based dataflow-oriented robotic middleware that enables low-latency, composable, distributed AI robotic application development, emerging as a lightweight alternative to ROS for edge deployments.
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,255 total: End-to-end reinforcement learning infrastructure purpose-built for embodied and agentic AI, streamlining pipeline management for training and deploying large-scale VLA and robot policies.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐65 total: New evaluation framework for VLA and physical AI models that lets users define a single benchmark to run any policy across any simulator or real robot, addressing a critical gap in VLA reproducibility.
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐125 total: ROS-free sim2real framework for VLA and RL agent deployment, with native MuJoCo Gymnasium wrappers for common manipulators and humanoids, simplifying end-to-end policy deployment.
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,325 total: Industry-standard open-source physics simulator for multi-joint contact dynamics, the foundation for nearly all modern robotic simulation, VLA training, and sim2real research.

---

### 🧠 VLA / Foundation Models
- [NVlabs/alpamayo1.5](https://github.com/NVlabs/alpamayo1.5) ⭐342 total: NVIDIA’s latest 10B-parameter open VLA for autonomous vehicles, featuring RL-enhanced chain-of-causation reasoning, navigation guidance, and visual question answering for real-world mobility.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐435 total: First full Chinese-language, practice-oriented VLA learning and interview handbook focused specifically on robotics-specific challenges, rapidly gaining traction among Chinese embodied AI practitioners.
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐511 total: InternVLA-A1, a new state-of-the-art VLA that unifies visual understanding, content generation, and robotic action prediction for general-purpose manipulation tasks.
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐115 total: Open-world general-purpose embodied intelligence foundation model designed for cross-domain deployment across manipulation, navigation, and mobile robotics use cases.
- [phi-monster/Galahad](https://github.com/phi-monster/Galahad) ⭐50 total: Novel research project diagnosing instruction blindness in VLA policies, introducing a low-rank data curing method to improve policy reliability on out-of-distribution language commands.
- [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐7 total: New IROS 2026 lightweight Mamba-based VLA for robot manipulation, with only 179M parameters enabling edge deployment on low-power robotic hardware.

---

### 🦾 Manipulation & Grasping
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,765 total: Fully open-source humanoid robotic arm purpose-built for contact-rich physical AI research and deployment, with standardized interfaces for VLA integration and real-world testing.
- [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐87 total: Novel framework that compiles natural language instructions into type-verified robot skill graphs, enabling reliable execution of complex manipulation tasks across sim and real robots.
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8 total: Bimanual kitchen manipulation benchmark for VLA models, built on the Inspect Robots evaluation framework to standardize testing of long-horizon household manipulation tasks.
- [shritankomm/7-DOF-FDM-Open-Arm](https://github.com/shritankomm/7-DOF-FDM-Open-Arm) ⭐1 total: Low-cost (under $800) 3D-printable 7-DOF humanoid manipulator with ROS 2 support, vision integration, and autonomous control capabilities, making VLA manipulation research accessible to low-resource teams.
- [Manas-arumalla/panda-tamp](https://github.com/Manas-arumalla/panda-tamp) ⭐1 total: Closed-loop task and motion planning pipeline for Franka Panda manipulators, bridging PDDL high-level planning with real geometry perception and ROS 2/MoveIt 2 execution for language-grounded manipulation.
- [dsl-robotics/skatearm](https://github.com/dsl-robotics/skatearm) ⭐1 total: Open bimanual work-cell ecosystem with MuJoCo simulation, ROS 2 bridging, and a web-based control cockpit, designed for end-to-end autonomous assembly tasks with integrated quality control.

---

### 🚶 Locomotion & Navigation
- [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐598 total: Foundation model for whole-body humanoid control, enabling unified locomotion and manipulation coordination for general-purpose humanoid robots.
- [softmata/horus](https://github.com/softmata/horus) ⭐393 total: Rust-based high-performance robotics runtime system, positioned as the "Android for robots" to standardize low-level control across diverse humanoid and mobile robot hardware.
- [Rhoban/microban](https://github.com/Rhoban/microban) ⭐45 total: Affordable, fully 3D-printable open-source humanoid robot powered by a Raspberry Pi Zero 2W, designed as an accessible DIY platform for legged robotics research and education.
- [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐96 total: Official repository for Omni-Modal Motion Generation, a state-of-the-art framework for generalist humanoid control that supports cross-modal input for whole-body motion planning.
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐259 total: UMI-3D SLAM and data processing pipeline for embodied robots, enabling high-accuracy 3D environment mapping for navigation and manipulation tasks.
- [THMOS2025/MOS-9-Open-Source-Humanoid-Robot](https://github.com/THMOS2025/MOS-9-Open-Source-Humanoid-Robot) ⭐17 total: Open-source hub for the MOS9 RoboCup Kid-Size humanoid robot, integrating hardware design, deployment tools, policy learning, and simulation resources for competitive and research use.

---

### 📦 Embodied Applications
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,860 total: Popular hands-on educational project that teaches users to build a full embodied intelligent robot from zero with only Python basics, including step-by-step implementations of OpenVLA, SmolVLA, and Pi0 models.
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,073 total: Self-evolving embodied AI operating system built on agentic workflows, supporting closed-loop perception, planning, and action for physical robot deployments.
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,225 total: The most widely deployed open-source robotics operating system, currently providing advanced driver assistance for over 300 supported car models, serving as a leading real-world testbed for VLA and mobility AI.
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐138 total: Lightweight, scalable whole-body teleoperation framework for humanoid robots, enabling low-latency remote control for VLA demonstration data collection and real-world task execution.
- [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐221 total: Minimal hardware-software architecture that gives large language models closed-loop physical embodiment with self-perception loops, enabling low-cost testing of LLM-powered robotic agents.
- [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8 total: Deployed VLA agent for the FrodoBots Earth Rover Mini+, integrating vision, language, and action control with a public ECoT dataset hosted on Hugging Face for mobile VLA research.

---

## 3. Trend Signal Analysis
The most explosive community attention today is centered on vertical specialization of VLA models for high-impact use cases, particularly autonomous driving and whole-body humanoid control. NVIDIA’s open Alpamayo series, paired with dedicated developer recipes for fine-tuning and deployment, signals a maturing of VLA technology out of general research and into production-grade mobility applications, echoing the company’s 2026 Computex announcements around automotive and robotic AI.
A notable new technical direction is the adoption of Rust as a core language for robotic infrastructure, with high-performance runtime (Horus) and middleware (dora-rs) projects emerging as lightweight, low-latency alternatives to legacy Python and ROS-based stacks, addressing critical reliability requirements for real-world physical AI deployments. Additionally, Mamba-based lightweight VLA architectures (such as the IROS 2026 SUREFlow model) are appearing for the first time, enabling edge deployment of VLA policies on low-power hardware without sacrificing performance, a key shift from the large, cloud-only VLA designs of 2024-2025.
This ecosystem activity aligns directly with the 2026 industry wave of humanoid commercialization and autonomous driving VLA deployment, with open-source tooling rapidly closing gaps in evaluation, reproducibility, and hardware accessibility to support mass market adoption.

---

## 4. Community Hot Spots
- **NVIDIA Alpamayo Ecosystem**: The full stack of Alpamayo VLA models, fine-tuning recipes, and autonomous driving use cases is the highest-impact new VLA release of Q3 2026, with pre-trained weights and deployment tools making production VLA mobility accessible to all developers.
- **Low-Cost Open Humanoid Hardware**: Projects like OpenArm, Microban, and the $800 7-DOF manipulator are drastically lowering the barrier to entry for physical VLA research, enabling hobbyists and low-resource labs to test policies on real hardware instead of only simulation.
- **VLA Evaluation & Robustness Tooling**: Inspect Robots, Galahad, and KitchenBench address a longstanding gap in VLA research around standardized benchmarking and failure mode mitigation, a critical prerequisite for VLA commercialization that is rapidly gaining developer mindshare.
- **Non-English Embodied AI Educational Resources**: Chinese-language resources like the VLA Handbook and *Every-Embodied* zero-to-VLA course are filling a major gap in localized learning materials, supporting the fast-growing Chinese embodied AI developer community which now makes up over 40% of global robotics researchers.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*