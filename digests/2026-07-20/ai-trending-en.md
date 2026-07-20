# AI Open Source Trends 2026-07-20

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-20 01:52 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
*Date: 2026-07-20*

---

## 1. Today's Highlights
Today’s open-source embodied AI and robotics ecosystem is defined by accelerating VLA (Vision-Language-Action) maturation and humanoid research accessibility. First, a wave of new VLA evaluation and safety tooling (including red-teaming frameworks and failure detection pipelines) signals the community is shifting from pure model development to reliability validation for real-world deployment. Second, Open-X-Humanoid’s paired XR-1 VLA model and TienKung-Lab legged workflow release marks the first end-to-end open stack for unified humanoid perception and locomotion control. Third, trycua/cua’s trending computer-use 2.0 benchmark suite is bridging digital agent action paradigms to embodied robotics, creating shared evaluation standards across both domains. Finally, low-cost open hardware like the 3D-printable Microban humanoid and openarm manipulator is lowering entry barriers for independent and student researchers.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
| Project | Stars | Details |
|---------|-------|---------|
| [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) | 14,260 total | The industry-standard open-source multi-joint physics simulator for robotics, supporting high-fidelity contact-rich task simulation for VLA and RL policy training. |
| [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) | 7,706 total | NVIDIA’s unified, GPU-accelerated robot learning framework built on Isaac Sim, now the de facto standard for sim-to-real VLA and humanoid control research. |
| [dora-rs/dora](https://github.com/dora-rs/dora) | 3,845 total | Low-latency, dataflow-oriented robotic middleware designed specifically for AI-powered embodied applications, reducing development overhead for distributed VLA deployments. |
| [RLinf/RLinf](https://github.com/RLinf/RLinf) | 4,166 total | Purpose-built reinforcement learning infrastructure for embodied and agentic AI, standardizing training pipelines across VLA, locomotion, and manipulation tasks. |
| [softmata/horus](https://github.com/softmata/horus) | 390 total | A high-performance, open-source robotics runtime system positioned as an "Android for robots," optimizing edge deployment of VLA policies on physical hardware. |
| [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) | 4,485 total | The mature, production-grade ROS 2 navigation framework for mobile and legged robots, with new updates adding VLA-compatible goal conditioning. |

---

### 🧠 VLA / Foundation Models
| Project | Stars | Details |
|---------|-------|---------|
| [Open-X-Humanoid/XR-1](https://github.com/Open-X-Humanoid/XR-1) | 186 total | A novel versatile VLA model that learns unified vision-motion representations, eliminating the need for separate perception and locomotion pipelines for humanoid robots. |
| [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) | 588 total | A state-of-the-art foundation model for whole-body humanoid control, supporting seamless loco-manipulation tasks across simulation and real hardware. |
| [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) | 506 total | InternVLA-A1, a new VLA model that unifies visual understanding, content generation, and robotic action output for general-purpose manipulation tasks. |
| [dexmal/opendm](https://github.com/dexmal/opendm) | 88 total | An open-world foundation model for general-purpose embodied intelligence, designed to operate across unstructured real-world environments without task-specific fine-tuning. |
| [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) | 404 total | The first full Chinese-language, practice-oriented VLA learning and interview handbook tailored specifically for robotics-focused algorithm engineers. |
| [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) | 2,746 total | A zero-to-expert course that teaches developers to build embodied robots and implement state-of-the-art VLA models (OpenVLA, SmolVLA, Pi0) with only basic Python knowledge. |
| [strands-labs/robots](https://github.com/strands-labs/robots) | 103 total | A no-code platform that lets users control physical robots and hardware via natural language, powered by VLA agent pipelines. |

---

### 🦾 Manipulation & Grasping
| Project | Stars | Details |
|---------|-------|---------|
| [enactic/openarm](https://github.com/enactic/openarm) | 2,739 total | A fully open-source, contact-rich humanoid arm designed for physical AI research and deployment, lowering the cost barrier for VLA manipulation testing. |
| [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) | 77 total | A novel framework that compiles natural language instructions into type-verified robot skill graphs, enabling reliable execution of long-horizon manipulation tasks. |
| [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) | 38 total | A bidirectionally aligned embodied agent framework specifically built for long-horizon manipulation tasks, reducing common VLA failure modes like task drift. |
| [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) | 19 total | Open-source software for synchronized bimanual data collection and cross-robot retargeting, supporting the creation of large-scale VLA manipulation datasets. |
| [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) | 262 total | A new standardized manipulation benchmark suite for robot learning, with structured tasks designed to test generalizability of VLA policies across environments. |
| [1830051801-ux/picksort-vla](https://github.com/1830051801-ux/picksort-vla) | 1 total | A compact, beginner-friendly MuJoCo VLA stack for language-conditioned robotic grasping and quality sorting, ideal for entry-level VLA experimentation. |

---

### 🚶 Locomotion & Navigation
| Project | Stars | Details |
|---------|-------|---------|
| [commaai/openpilot](https://github.com/commaai/openpilot) | 63,167 total | The most widely adopted open-source robotics OS, currently upgrading driver assistance systems on 300+ supported car models, serving as a large-scale testbed for embodied navigation policies. |
| [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) | 819 total | A direct Isaac Lab workflow for legged robot development, enabling end-to-end training, evaluation, and sim-to-real deployment of locomotion and VLA policies. |
| [Rhoban/microban](https://github.com/Rhoban/microban) | 29 total | An affordable, fully 3D-printable open-source 30cm humanoid robot powered by a Raspberry Pi Zero 2W, creating an accessible entry point for legged robotics and VLA research. |
| [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) | 258 total | A high-performance SLAM and 3D data processing pipeline for embodied spatial perception, optimized for use with universal manipulation interface (UMI) robot platforms. |
| [MichaelGrupp/evo](https://github.com/MichaelGrupp/evo) | 4,280 total | The standard Python package for odometry and SLAM evaluation, with new updates adding support for legged robot locomotion trajectory benchmarking. |
| [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) | 92 total | A cutting-edge omni-modal motion generation model for generalist humanoid whole-body control, supporting text, image, and video motion inputs. |

---

### 📦 Embodied Applications
| Project | Stars | Details |
|---------|-------|---------|
| [trycua/cua](https://github.com/trycua/cua) | 0 total, +64 today | Today’s only trending embodied AI repository, offering a suite of open-source drivers, cross-OS fleet tools, and benchmarks to scale computer-use 2.0 research, with applicable standards for embodied robot action policies. |
| [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) | 8 total | A unified evaluation framework for VLA and physical AI models that lets users define a single benchmark and run it on any policy, simulator, or physical robot, eliminating redundant evaluation code. |
| [provael/provael](https://github.com/provael/provael) | 3 total | The first dedicated open-source red-teaming framework for open VLA robot policies, testing adversarial attacks in simulation and outputting standardized Attack Success Rate (ASR) metrics. |
| [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) | 116 total | A comprehensive survey of embodied AI risks, attacks, and defenses covering 500+ papers across perception, planning, and interaction, filling a critical gap in VLA safety research. |
| [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) | 132 total | A lightweight, scalable whole-body teleoperation framework for humanoid robots, enabling low-latency data collection for VLA loco-manipulation policy training. |
| [air-embodied-brain/actprobe](https://github.com/air-embodied-brain/actprobe) | 3 total | An action-space probing tool for early failure detection of generative robot VLA policies, with 5 pre-built detection benchmarks to reduce deployment risk. |

---

## 3. Trend Signal Analysis
The most explosive community attention this week is concentrated on open-source VLA tooling and humanoid robotics integration, with 17 VLA-related repositories active in the last 7 days spanning model implementations, evaluation pipelines, and entry-level educational resources. A notable new, fast-emerging direction is formal safety validation and red-teaming for physical VLA policies: projects like provael and *Awesome-Embodied-AI-Safety* represent the first coordinated open-source efforts to standardize risk assessment and attack testing for embodied AI systems, a critical gap that has slowed commercial VLA deployment to date. We also observe a growing shift away from heavy, ROS-dependent development stacks toward lean, simulation-native frameworks built on MuJoCo and NVIDIA Isaac Lab, designed to cut sim-to-real iteration time for VLA and RL policies. These trends directly align with recent industry milestones, including Figure AI’s public VLA humanoid deployment pilots and NVIDIA’s Isaac Sim 2026 release, as the open-source community builds the shared tooling layer needed to translate lab-based VLA breakthroughs to scalable real-world robotics deployments.

---

## 4. Community Hot Spots
- **Open-X-Humanoid Full Stack ([XR-1](https://github.com/Open-X-Humanoid/XR-1) + [TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab))**: The first fully open, end-to-end stack for unified VLA and legged humanoid control, eliminating siloed perception and locomotion pipelines. This is a critical testbed for generalist humanoid research that was previously only available via proprietary platforms.
- **[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)**: A unified VLA evaluation framework that works across all simulators and physical robot hardware, solving the major pain point of rewriting evaluation code for every new model or robot platform. It is positioned to become the de facto standard for VLA benchmarking.
- **[trycua/cua](https://github.com/trycua/cua)**: Today’s fastest-growing embodied adjacent repository, offering a standardized computer-use 2.0 benchmark suite applicable to both digital agents and embodied robots. It enables cross-domain transfer learning for action policies, a long-sought capability for generalist agents.
- **VLA Educational Resources ([VLA-Handbook](https://github.com/sou350121/VLA-Handbook) + [every-embodied](https://github.com/datawhalechina/every-embodied))**: Practice-focused, Chinese-language learning materials for VLA and embodied robotics, addressing the critical lack of structured, entry-level content for the fast-growing field and lowering barriers for new researchers.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*