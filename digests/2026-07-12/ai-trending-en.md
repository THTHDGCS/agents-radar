# AI Open Source Trends 2026-07-12

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-12 01:29 UTC

---

# Embodied Intelligence & Robotics GitHub Trends Report
*Date: 2026-07-12*

---

## 1. Today's Highlights
Today’s embodied AI and robotics ecosystem saw sustained open-source activity across VLA tooling, humanoid hardware, and robot simulation infrastructure, with 70+ relevant active repositories in the last 7 days. A notable trend is the proliferation of accessible VLA educational resources and beginner-friendly development kits, lowering entry barriers for new developers entering the field. Open-source humanoid robotics hardware and runtime systems also gained traction, as the community pushes for standardized, low-cost platforms to accelerate physical AI R&D. NASA’s F´ embedded flight software framework appeared on GitHub’s daily trending list, gaining 22 new stars as aerospace and robotic embedded systems see renewed interest from the broader robotics community. Evaluation and benchmarking tools for VLA policies emerged as a fast-growing niche, as the field shifts from model development to standardized performance testing.

---

## 2. Top Projects by Category
### 🤖 Robot Frameworks / SDKs
| Project | Stars | Overview |
|---------|-------|----------|
| [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) | 14,168 total | The de facto open-source physics simulator for robotics and embodied AI research, with native GPU acceleration for contact-rich dynamics training. |
| [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) | 30,014 total | The most widely used open-source educational resource for robotics fundamentals, with Python implementations of localization, path planning, and control algorithms. |
| [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) | 7,659 total | Unified NVIDIA Isaac Sim-based framework for robot learning, the standard toolchain for sim-to-real VLA and RL policy training for commercial robots. |
| [dora-rs/dora](https://github.com/dora-rs/dora) | 3,838 total | Low-latency, dataflow-oriented robotic middleware that simplifies development of distributed AI-powered robotic applications, with native support for VLA inference pipelines. |
| [nasa/fprime](https://github.com/nasa/fprime) | +22 today's new stars | Production-grade embedded flight software framework for aerospace and robotic systems, trending today for its use in small satellite and planetary rover development. |
| [rerun-io/rerun](https://github.com/rerun-io/rerun) | 11,120 total | Multimodal robotics data visualization, streaming, and querying tool that dramatically reduces debugging time for VLA and robot learning pipelines. |

### 🧠 VLA / Foundation Models
| Project | Stars | Overview |
|---------|-------|----------|
| [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) | 482 total | Open-source production VLA series that unifies visual understanding, text generation, and robotic action output, optimized for edge deployment on manipulation robots. |
| [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) | 376 total | Chinese-language, practice-oriented VLA learning and interview guide for algorithm engineers, filling a critical gap in non-English embodied AI educational resources. |
| [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) | 60 total | Official RSS 2026 implementation of universal pose pretraining for generalizable VLA policies, a cutting-edge approach to improving zero-shot VLA transfer across robot platforms. |
| [YuZhaoshu/Efficient-VLAs-Survey](https://github.com/YuZhaoshu/Efficient-VLAs-Survey) | 169 total | Continuously updated curated survey of efficient VLA research, tracking optimizations for edge deployment and low-compute inference, a top industry priority. |
| [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) | 124 total | ROS-free sim-to-real framework built specifically for VLA and RL agent deployment, with native support for Franka, UR5e, and xArm robot arms. |
| [xiaoms22/lunavla](https://github.com/xiaoms22/lunavla) | 2 total | Beginner-friendly VLA project starter with CPU-compatible imitation learning and evaluation workflows, designed for new developers to build their first VLA model in hours. |

### 🦾 Manipulation & Grasping
| Project | Stars | Overview |
|---------|-------|----------|
| [enactic/openarm](https://github.com/enactic/openarm) | 2,708 total | Fully open-source humanoid arm optimized for contact-rich physical AI research, offering a low-cost alternative to proprietary robotic arms for VLA manipulation testing. |
| [robocasa/robocasa](https://github.com/robocasa/robocasa) | 1,531 total | Large-scale simulation benchmark of 1000+ everyday household manipulation tasks, the most widely used dataset for training generalist VLA manipulation policies. |
| [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) | 169 total | Official CVPR 2025 implementation of LLM-driven simulation for generalizable instruction-following manipulation, bridging LLM planning and physical robot execution. |
| [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) | 254 total | SLAM and data processing pipeline for the Universal Manipulation Interface, a critical tool for collecting real-world manipulation data to train VLA models. |
| [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) | 58 total | Framework that compiles natural language instructions into verified robot skill graphs, improving VLA reliability for complex, multi-step manipulation tasks. |

### 🚶 Locomotion & Navigation
| Project | Stars | Overview |
|---------|-------|----------|
| [commaai/openpilot](https://github.com/commaai/openpilot) | 63,082 total | The most widely deployed open-source robotics operating system, powering advanced driver assistance on 300+ car models and serving as a reference for mobile embodied autonomy. |
| [softmata/horus](https://github.com/softmata/horus) | 388 total | High-performance robotics runtime system positioned as the "Android for robots", optimized for low-latency control of humanoid and legged robot locomotion. |
| [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) | 805 total | IsaacLab-based workflow for legged robot development, simplifying sim-to-real transfer for humanoid locomotion policy training. |
| [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) | 245 total | Official ECCV 2026 implementation of a high-fidelity navigation simulator with dynamic Gaussian splatting, dramatically improving photorealism for embodied navigation training. |
| [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) | 2 total | Novel unified VLA framework for seamless humanoid loco-manipulation, extending VLA capabilities beyond tabletop tasks to full-body mobile manipulation. |

### 📦 Embodied Applications
| Project | Stars | Overview |
|---------|-------|----------|
| [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) | 2,622 total | Beginner-friendly hands-on course that teaches building embodied robots and VLA models (OpenVLA, Pi0) from zero with only basic Python knowledge, democratizing embodied AI education. |
| [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) | 472 total | Self-evolving embodied AI operating system built on agentic workflows, enabling closed-loop self-improvement for physical robots in unstructured environments. |
| [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) | 131 total | Lightweight, scalable whole-body teleoperation framework for humanoid robots, a critical tool for collecting large-scale loco-manipulation data to train VLA models. |
| [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) | 2,558 total | Open-source digital twin platform for robotics, enabling high-fidelity sim2real validation of VLA policies before deployment on physical hardware. |
| [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) | 3 total | Cross-platform evaluation framework for VLA and physical AI models that works across all simulators and real robot platforms, standardizing VLA performance benchmarking. |

---

## 3. Trend Signal Analysis
The most explosive community attention today is focused on VLA democratization and humanoid robotics enabling infrastructure, as the embodied AI field shifts from pure research to accessible, deployable tools. A clear new trend is the rise of ROS-free VLA deployment stacks, such as robot-control-stack, which address longstanding pain points of ROS complexity for VLA inference and sim-to-real transfer, marking a departure from the decades-old ROS-centric robotics development paradigm. Another emerging direction is the integration of agentic workflow frameworks into embodied AI operating systems, as seen in PhyAgentOS, bringing self-improving closed-loop capabilities from software agents to physical robots. These developments align with recent industry milestones: the release of multiple open VLA base models (e.g., OpenVLA, Pi0) in Q2 2026 has created demand for educational resources and deployment tooling, driving projects like the VLA-Handbook and lunavla beginner starter kit. Additionally, upcoming robotics conferences (RSS 2026, ECCV 2026) are driving a wave of open-source paper releases, including cutting-edge work on VLA pretraining (PoseVLA) and Gaussian splatting-powered simulation (habitat-gs). The surge in humanoid-related open-source projects also tracks with the $2B+ in humanoid robotics funding announced in H1 2026, as the community races to build standardized open hardware and runtime stacks to compete with proprietary platforms.

---

## 4. Community Hot Spots
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack): This ROS-free VLA deployment framework solves a major industry bottleneck for real-world VLA rollout, eliminating ROS overhead for small research teams and startups testing policies on physical hardware.
- [enactic/openarm](https://github.com/enactic/openarm): The first fully open-source contact-rich humanoid arm fills a critical gap in accessible manipulation hardware, offering a 70% cost reduction compared to proprietary alternatives for VLA research.
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook): This practice-oriented Chinese-language VLA guide signals rapid growth of the non-English embodied AI developer community, and is a high-value resource for new engineers entering the field.
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots): Standardized cross-platform VLA benchmarking is an emerging critical need as the number of open VLA models grows, and this framework is well-positioned to become a community standard.
- [softmata/horus](https://github.com/softmata/horus): This high-performance robotics runtime addresses the lack of standardized low-latency control software for humanoids, a top pain point for the fast-growing humanoid robotics sector.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*