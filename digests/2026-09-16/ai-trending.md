# AI 开源趋势日报 2026-09-16

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-16 02:09 UTC

---

# 具身智能与机器人开源趋势日报
**日期**：2026年9月16日  
**数据来源**：GitHub Trending 实时榜、GitHub 主题搜索（7天活跃项目）

---

## 1. 今日速览
今日GitHub通用Trending榜无具身智能、机器人领域直接相关项目，反映当前领域仍以垂直技术社区深耕为主，尚未进入通用开发者的广泛视野。VLA（视觉-语言-动作）全栈开源生态加速完善，从记忆增强型模型、预训练数据生成工具到统一评估框架的各环节均有新项目更新，是当前最活跃的细分方向。人形机器人开源生态持续扩容，从低成本DIY硬件、全身运动基础模型到多机器人统一控制工具的项目均获得社区关注，落地门槛持续降低。具身智能底层技术栈呈现轻量化、高性能化趋势，Rust编写的机器人运行时、无ROS的sim2real框架等新兴方向迭代加速，逐步挑战传统ROS生态的地位。

---

## 2. 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63664：开源机器人操作系统，已落地300+车型的高级驾驶辅助，是移动机器人领域商业化程度最高的开源项目之一。
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15160：经典多关节接触物理仿真器，是机器人学习、仿真领域的事实标准，生态覆盖绝大多数具身研究项目。
3. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11454：多模态机器人数据可视化与流处理工具，覆盖机器人训练、调试全流程，近期在开发者群体中渗透率快速提升。
4. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8137：NVIDIA Isaac Sim生态下的统一机器人学习框架，支持多物理/渲染引擎，是VLA与sim2real研究的核心工具。
5. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐5239：面向具身智能与Agent AI的强化学习基础设施，为具身算法训练提供统一的底层支撑。
6. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4710：ROS 2官方导航框架，覆盖定位、路径规划、避障全链路，是移动机器人开发的标配工具。
7. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3941：数据流驱动的机器人中间件，主打低延迟、可组合与分布式部署，是AI时代机器人架构的热门探索方向。
8. [softmata/horus](https://github.com/softmata/horus) ⭐437：Rust编写的高性能机器人运行时系统，对标手机端的Android，主打极低延迟，是机器人底层系统的新兴方向。

---

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐772：开放世界通用具身智能基础模型，是少有的开源全栈具身基础模型项目，覆盖多场景具身任务。
2. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐619：全中文VLA实战导向学习与面试手册，聚焦机器人领域特有挑战，是国内开发者入门VLA的热门资源。
3. [xiaomi-research/recogdrive](https://github.com/xiaomi-research/recogdrive) ⭐607：ICLR 2026录用项目，提出强化认知的端到端自动驾驶框架，是VLA技术在自主驾驶场景的典型落地。
4. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐553：统一视觉理解、内容生成与动作输出的机器人操作VLA，来自国内团队，覆盖操作任务全链路。
5. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐284：世界动作模型（WAM）统一训练/微调/评估框架，是VLA之外具身基础模型的新兴范式。
6. [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) ⭐35：带原生视频记忆的VLA模型，支持长时序机器人操作与流式推理，解决了传统VLA上下文窗口受限的核心痛点。
7. [3587jjh/HuRo](https://github.com/3587jjh/HuRo) ⭐23：CoRL 2026录用项目，通过将人类视频“机器人化”实现VLA大规模预训练，为解决VLA训练数据不足问题提供了新思路。

---

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐3345：全开源人形手臂，面向物理AI研究与接触富集环境，是当前开源硬件中完成度最高的人形手臂项目之一。
2. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐176：CVPR 2025录用项目，提出LLM驱动的仿真生成方法，大幅提升机器人操作任务的泛化性。
3. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐135：将自然语言指令编译为可验证的机器人技能图，相比端到端VLA可靠性更高，适合工业级操作场景。
4. [allenai/MolmoBot](https://github.com/allenai/MolmoBot) ⭐106：基于大规模仿真数据训练的零样本操作模型，验证了大规模仿真对操作泛化能力的提升价值。
5. [XenseRobotics-AI/lerobot-xense](https://github.com/XenseRobotics-AI/lerobot-xense) ⭐19：LeRobot v5.1的商业级分支，支持Flexiv、Elite等多种主流机械臂与触觉夹爪，覆盖VR、SpaceMouse等多类遥操作方式。
6. [XenseRobotics-AI/xense-taccap-lerobot](https://github.com/XenseRobotics-AI/xense-taccap-lerobot) ⭐14：视觉触觉融合的抓取数据采集工具，支持Pico4遥操作，填补了开源触觉操作数据采集工具的空白。

---

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐695：全身人形机器人控制基础模型，是人形机器人运动智能领域的前沿探索。
2. [Rhoban/microban](https://github.com/Rhoban/microban) ⭐391：低成本全3D打印开源人形机器人，基于树莓派Zero 2W，是DIY人形机器人与入门研究的热门平台。
3. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325：成熟的腿式运动控制算法库，支持人形机器人、外骨骼、足式机器人等多种平台。
4. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐117：清华MARS实验室推出的全模态运动生成框架，用于通用人形机器人控制。
5. [Open-X-Humanoid/BICMap](https://github.com/Open-X-Humanoid/BICMap) ⭐77：基于WebGL的机器人地图可视化SDK，支持SLAM点云、3D模型与导航数据展示，是前端与机器人交叉的实用工具。
6. [Renkunzhao/legged-daily](https://github.com/Renkunzhao/legged-daily) ⭐22：腿式机器人研究资源合集，覆盖基于模型与学习的控制方法，适合研究者跟踪前沿进展。

---

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3709：面向Python基础开发者的具身机器人从零构建教程，覆盖VLA、OpenVLA、Pi0等主流模型，是国内入门具身智能的顶流资源。
2. [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core) ⭐2317：递归自改进物理Agent操作系统，通过Agentic工作流实现具身Agent的自我迭代，是具身智能系统级架构的新探索。
3. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐491：物理AI通用评估框架，支持任意VLA/LLM模型在任意机械臂、人形机器人上的实机/仿真基准测试，解决了具身模型评估难、标准不统一的痛点。
4. [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐201：统一机器人控制CLI工具，支持多种硬件平台与LLM后端，内置MCP、记忆与多机器人集群管理功能。
5. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐160：无ROS的轻量sim2real框架，支持VLA与RL Agent的训练部署，兼容多种主流机械臂，适合快速落地验证算法。
6. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐56：机器人辅助化学实验室自动化数字孪生平台，是具身智能在垂直行业落地的典型案例。

---

## 3. 趋势信号分析
今日数据显示，**VLA（视觉-语言-动作）全栈生态**是当前具身智能领域最具爆发性的方向：从记忆增强型VLA模型、视频转运动学的数据生成工具，到跨硬件通用评估框架，覆盖数据、训练、部署、评估的全链路项目均有更新，反映VLA正从实验室原型快速走向工程化落地。
技术栈层面，**Rust编写的机器人底层系统、无ROS轻量sim2real框架**成为新兴方向：dora、horus等Rust项目主打低延迟与高性能，robot-control-stack等无ROS框架降低了VLA部署的复杂度，体现出开发者对传统ROS生态“重、慢”的替代需求。
行业关联上，近期全球人形机器人厂商新品密集发布、大厂VLA模型持续迭代，直接带动了开源社区对人形硬件、VLA工具链的投入，领域正从“单点技术突破”转向“全生态成熟”阶段。

---

## 4. 社区关注热点
- **记忆增强VLA技术**：代表项目[OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA)，通过原生视频记忆与流式推理解决了传统VLA长时序操作的痛点，是VLA从简单抓取任务走向复杂长流程工业/家用任务的关键技术方向。
- **无ROS轻量具身框架**：代表项目[RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)，主打轻量化、sim2real一体化，适配多种主流机械臂与VLA模型，大幅降低了中小团队与个人开发者的算法验证门槛。
- **低成本开源人形硬件**：代表项目[Rhoban/microban](https://github.com/Rhoban/microban)，仅需树莓派Zero 2W与3D打印即可搭建完整人形机器人，成本低、可扩展性强，适合个人开发者与高校入门研究。
- **VLA通用评估工具**：代表项目[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)，支持任意VLA模型在任意硬件平台上的实机/仿真基准测试，解决了当前具身模型评估标准不统一、测试成本高的行业痛点。
- **机器人高性能运行时**：代表项目[softmata/horus](https://github.com/softmata/horus)，Rust编写的低延迟机器人运行时系统，对标手机端的Android生态，是下一代具身机器人底层系统的核心探索方向。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*