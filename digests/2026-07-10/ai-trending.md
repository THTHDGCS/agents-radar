# AI 开源趋势日报 2026-07-10

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-10 01:48 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-10）
---

## 今日速览
今日具身智能开源社区的核心热度集中在VLA技术平民化、人形机器人软硬件开源、sim2real工具链轻量化三大方向。多款低门槛VLA项目集中发布，支持消费级GPU甚至无GPU运行，大幅降低了领域入门门槛。全开源人形机械臂、低成本DIY人形机器人项目活跃度显著提升，物理AI的硬件开源生态正在加速完善。面向VLA的评估、安全、高效微调等细分方向的配套工具持续涌现，VLA技术体系正在从模型训练向产业落地全链路成熟。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、中间件）
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,645：NVIDIA官方基于Isaac Sim打造的统一机器人学习框架，是当前工业界和学术界进行机器人仿真训练的核心工具，本周持续更新核心功能。
2. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,059：面向机器人的通用操作系统，目前已适配300+款车型的辅助驾驶升级，是具身智能在自动驾驶场景落地的标杆项目。
3. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,063：专门针对具身智能和Agent AI设计的强化学习基础设施，大幅简化RL策略在机器人场景的训练和部署流程。
4. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,836：数据流导向的轻量机器人中间件，提供低延迟、可组合的分布式数据流转能力，是替代ROS的新一代机器人架构选型。
5. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,142：通用多关节物理仿真器，是当前机器人学习、VLA训练的底层核心工具。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐123：无ROS的轻量化sim2real框架，原生支持VLA模型和RL代理的训练部署，适配Franka、UR5e等主流机械臂，本周新登榜。
7. [robocasa/robocasa](https://github.com/robocasa/robocasa) ⭐1,529：面向通用机器人的大规模日常任务仿真平台，提供海量真实家庭场景的训练数据。

### 🧠 VLA/基础模型（视觉-语言-动作、模仿/强化学习策略）
1. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐371：国内首份全中文、实战导向的VLA领域学习/面试手册，聚焦机器人领域特有挑战，本周星数涨幅显著。
2. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐479：新一代开源VLA模型，统一了机器人操作的理解、生成与动作输出能力，是当前开源VLA的SOTA级项目。
3. [YuZhaoshu/Efficient-VLAs-Survey](https://github.com/YuZhaoshu/Efficient-VLAs-Survey) ⭐168：高效VLA领域的权威综述项目，持续跟进模型压缩、轻量化部署等最新研究进展。
4. [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) ⭐49：RSS 2026录用的最新VLA研究，通过通用姿态预训练实现了强泛化性的视觉-语言-动作策略。
5. [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) ⭐1：极简可解读的VLA实现，仅用冻结CLIP加微型输出头即可在M1/M2 Mac上运行，无GPU门槛，大幅降低入门成本。
6. [muhammadmahadazher/vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget) ⭐0：面向消费级硬件的VLA基准项目，在单张8GB笔记本GPU上对比了ACT、扩散策略、SmolVLA的性能，包含真实负结果，参考价值极高。
7. [cair-vinuni/CLP_VLA](https://github.com/cair-vinuni/CLP_VLA) ⭐4：最新研究证明VLA微调仅需更新极少层即可达到优秀效果，大幅降低VLA微调的算力需求。

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐168：CVPR 2025录用项目，通过LLM驱动仿真生成大量多样化的操作任务数据，大幅提升VLA的指令遵循泛化性。
2. [sahilrajpurkar03/nlp-pnp-robotic-arm](https://github.com/sahilrajpurkar03/nlp-pnp-robotic-arm) ⭐64：基于ROS2 Humble的自然语言控制抓取机械臂系统，集成YOLOv8、MoveIt和Ollama本地大模型，开箱可用。
3. [NVIDIA-ISAAC-ROS/isaac_ros_manipulation](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_manipulation) ⭐108：NVIDIA官方推出的GPU加速机械臂操作工作流包，适配工业级机械臂的实时控制需求。
4. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐48：可验证的机器人策略生成框架，将自然语言指令编译为类型安全的机器人技能图，可直接在仿真或真机上运行。
5. [chang-xinhai/Awesome-Dexterous-Manipulation](https://github.com/chang-xinhai/Awesome-Dexterous-Manipulation) ⭐11：灵巧机器人操作领域的资源汇总，覆盖触觉传感、灵巧手、数据集等核心方向。

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,706：完全开源的人形机械臂，专为物理AI的接触富集环境设计，是当前人形机器人硬件开源的标杆项目，本周星数涨幅显著。
2. [softmata/horus](https://github.com/softmata/horus) ⭐387：高性能机器人运行时系统，定位为机器人领域的Android，大幅提升机器人软件的部署和迭代效率。
3. [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐242：ECCV 2026录用的高保真导航仿真器，基于高斯溅射技术实现动态场景的真实渲染，适配机器人导航任务的训练。
4. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐321：成熟的足式机器人运动控制算法库，支持人形机器人、外骨骼、四足等多类平台的运动控制。
5. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐131：轻量可扩展的人形机器人全身遥操作框架，支持低成本的真人动作捕捉到机器人的映射。
6. [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐8：全3D打印的开源人形机器人，仅用树莓派Zero 2W和19个伺服电机即可实现，总成本极低，适合个人开发者入门实验。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,601：国内热门的具身智能入门项目，仅需Python基础即可从零构建VLA模型和具身机器人，覆盖OpenVLA、SmolVLA等主流模型的实战教学，本周活跃度极高。
2. [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3,394：开源具身AI助手生态，支持MCP协议、多模态交互、IoT设备控制和跨平台语音交互，是具身智能在消费级场景落地的典型项目。
3. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,560：斯坦福推出的具身AI研究基准平台，提供1000+真实场景的日常任务，是衡量通用具身智能能力的核心基准。
4. [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐217：给大模型提供闭环物理具身的最小软硬件架构，集成自感知环路，可快速实现LLM到物理世界的交互。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐3：专门针对VLA和物理AI模型的评估框架，一次定义基准即可在任意机器人或仿真环境上运行，填补了VLA落地的评估工具空白。

---

## 趋势信号分析
今日开源社区的核心爆发方向为**VLA技术的平民化**：多款低门槛VLA项目集中登榜，从支持Mac运行的极简实现、8GB消费级GPU即可运行的基准测试，到中文实战学习手册，覆盖入门、实验、学习全链路，说明VLA正在从学术圈的高算力门槛向普通开发者普及，社区参与度快速提升。新兴技术栈方面，**无ROS的轻量化sim2real框架**首次成为重点方向，摆脱ROS的冗余开销，适配VLA模型的快速迭代部署需求，是机器人开发栈的重要变化。近期特斯拉Optimus、宇树人形机器人的量产预热，直接带动了人形开源硬件、运动控制工具的热度，同时VLA的评估、安全、高效微调等配套工具的涌现，也反映出产业端对VLA落地的需求正在反向推动开源生态的全链路成熟。

---

## 社区关注热点
- 低门槛VLA工具链：代表项目包括[VIRENA](https://github.com/BuceaGeorgia/VIRENA)、[vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget)、[VLA-Handbook](https://github.com/sou350121/VLA-Handbook)，大幅降低了VLA的入门和实验成本，个人开发者和小团队无需高端算力即可快速开展VLA相关研发。
- 无ROS的sim2real框架：代表项目[robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)，摆脱了传统ROS架构的复杂度和性能开销，原生支持VLA和RL策略的训练部署，适配当前机器人学习快速迭代的需求，是极具潜力的下一代机器人开发栈。
- 开源人形硬件生态：代表项目[openarm](https://github.com/enactic/openarm)、[microban](https://github.com/MarcDcls/microban)，全开源的人形机械臂、低成本DIY人形机器人大幅下探了具身智能的实机实验门槛，推动sim2real技术从实验室向大众普及。
- VLA落地配套工具：代表项目包括[inspect-robots](https://github.com/robocurve/inspect-robots)评估框架、[CLP_VLA](https://github.com/cair-vinuni/CLP_VLA)高效微调方法，说明VLA正在从模型研发阶段走向产业落地，配套工具的完善是通用具身智能落地的前置信号。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*