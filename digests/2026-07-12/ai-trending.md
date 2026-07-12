# AI 开源趋势日报 2026-07-12

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-12 01:29 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-12）
---

## 今日速览
1. 今日具身智能开源领域呈现「基础设施打底、VLA落地加速、人形方向升温」的整体态势，机器人仿真、中间件等基础工具持续迭代，VLA相关的学习、开发、部署工具链进一步完善。
2. GitHub全球热榜中，NASA航天级嵌入式机器人框架F´与智能家居具身应用Home Assistant同时登榜，反映出高端航天机器人技术与民用具身落地场景的双向热度。
3. 人形机器人全栈开源生态快速完善，从硬件、运动控制到遥操作、VLA适配的完整链路出现多个优质项目，与近期全球人形机器人产业试点落地的节奏高度匹配。
4. 低门槛化成为VLA方向的重要趋势，不仅出现了CPU可运行的最小VLA实现，还有入门级项目模板与中文学习资源，大幅降低了开发者的进入门槛。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63082
  开源机器人操作系统，目前已支持300+车型的驾驶辅助系统升级，是落地规模最大的开源机器人控制栈之一，长期占据机器人领域星数榜首。
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14168
  通用多关节动力学物理仿真器，是VLA训练、机器人学习的核心基础设施，几乎所有主流具身智能项目均基于其开发。
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7659
  基于NVIDIA Isaac Sim的统一机器人学习框架，是当前人形机器人、通用操作任务训练的首选仿真底座，社区活跃度持续攀升。
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3838
  Rust编写的数据流导向机器人中间件，主打低延迟、可组合、分布式特性，是替代ROS的新兴轻量机器人架构方案。
- [nasa/fprime](https://github.com/nasa/fprime) ⭐0 (+22 today)
  NASA官方开源的飞行软件与嵌入式系统框架，适用于航天机器人、嵌入式边缘机器人的开发，今日登上全球热榜，受到工业界开发者关注。
- [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11120
  专门面向多模态机器人数据的可视化、查询、流处理工具，大幅提升VLA训练、机器人学习的数据调试效率。
- [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5183
  基于NVIDIA Warp的GPU加速物理仿真引擎，专门面向机器人学家优化，是仿真领域的新兴潜力项目。

---

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐376
  国内首份全中文、实战导向的VLA学习/面试手册，聚焦机器人领域特有挑战，是算法工程师入门VLA方向的优质资源。
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐482
  国产VLA系列模型，统一了机器人操作的理解、生成与动作能力，是国内产业界VLA落地的代表性开源项目。
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124
  无ROS的轻量sim2real框架，原生支持VLA模型与RL代理部署，适配Franka、UR5e等主流机械臂，大幅降低VLA落地门槛。
- [YuZhaoshu/Efficient-VLAs-Survey](https://github.com/YuZhaoshu/Efficient-VLAs-Survey) ⭐169
  高效VLA方向的综述合集，持续更新领域最新研究进展，是跟进VLA技术前沿的核心参考资源。
- [OpenDriveLab/RISE](https://github.com/OpenDriveLab/RISE) ⭐317
  RSS 2026最新研究成果，通过组合式世界模型实现机器人策略的自进化，是通用机器人学习的前沿方向。
- [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) ⭐60
  RSS 2026最新研究成果，通过通用姿态预训练提升VLA策略的泛化性，为VLA预训练方向提供了新的技术思路。
- [xiaoms22/lunavla](https://github.com/xiaoms22/lunavla) ⭐2
  入门级VLA项目模板，支持CPU运行、模仿学习与评估，附带完整部署文档，适合零基础开发者快速上手VLA开发。

---

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2708
  完全开源的人形机械臂，专门面向物理AI研究与接触富集任务部署，填补了开源高性价比人形上肢硬件的空白，星数增长迅速。
- [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐169
  CVPR 2025官方实现，通过LLM驱动仿真生成多样化操作任务数据，大幅提升指令跟随操作的泛化性，是操作领域的前沿成果。
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐254
  通用操作接口（UMI）生态的3D SLAM与数据处理管线，是当前通用操作数据采集的核心工具。
- [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐58
  可将自然语言指令编译为可验证的机器人技能图，支持仿真与真实机器人执行，有效提升操作任务的可靠性与可解释性。
- [sahilrajpurkar03/nlp-pnp-robotic-arm](https://github.com/sahilrajpurkar03/nlp-pnp-robotic-arm) ⭐64
  基于ROS2、YOLOv8、Isaac Sim的自然语言控制拾取放置机械臂系统，提供了完整的端到端操作落地方案，适合快速原型验证。

---

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
- [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐805
  基于IsaacLab的足式机器人开发工作流，大幅降低人形/足式机器人的训练与部署门槛，是人形机器人方向的热门开发工具。
- [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐245
  ECCV 2026最新成果，基于动态高斯溅射的高保真导航仿真器，大幅提升导航任务的仿真真实性与训练效果。
- [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx) ⭐246
  基于JAX的高速模型预测控制库，专为足式、人形机器人的运动控制优化，支持实时高性能控制计算。
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐131
  轻量级可扩展的人形机器人全身遥操作框架，是人形机器人数据采集、远程部署的核心工具。
- [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐17
  低成本全3D打印的开源人形机器人，基于树莓派Zero 2W开发，适合人形机器人入门学习与教学实验。

---

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2622
  面向Python基础开发者的具身智能入门教程，覆盖从0构建VLA模型的全流程，是国内最受欢迎的具身智能入门资源。
- [home-assistant/core](https://github.com/home-assistant/core) ⭐0 (+80 today)
  开源智能家居自动化系统，主打本地控制与隐私优先，是具身智能在家庭场景的最大规模落地开源项目，今日登上全球热榜。
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2558
  机器人数字孪生平台2.0官方仓库，支持高精度sim2real映射与验证，是数字孪生+机器人方向的标杆项目。
- [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1561
  斯坦福大学开源的具身AI研究平台，支持1000+日常任务的训练与评估，是通用具身智能能力评估的标准基准。
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐472
  基于Agent工作流的自进化具身AI操作系统，是具身智能系统级架构的前沿探索。

---

## 趋势信号分析
今日开源数据显示，**VLA落地工具链与人形机器人全栈开源**是当前社区热度最高的两大方向：一方面，从入门模板、中文学习资源到端侧推理引擎、sim2real部署框架的完整VLA工具体系正在形成，反映出VLA技术正从学术研究快速走向产业落地，低门槛化的趋势大幅降低了开发者的进入壁垒。另一方面，人形机器人相关的开源硬件、运动控制、遥操作工具数量快速增长，与近期全球人形机器人融资热潮、工业场景试点落地的行业节奏高度匹配。新兴技术栈方面，Rust编写的高性能机器人运行时、无ROS的轻量VLA部署框架、基于高斯溅射的高保真仿真首次成为社区关注热点，预示着具身智能的底层技术栈正在经历新一轮迭代。

---

## 社区关注热点
- 👉 无ROS的VLA部署框架 [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)：原生适配多主流机械臂与VLA/RL模型，规避了ROS的复杂度与冗余性，大幅降低VLA从仿真到真实机器人的落地门槛，适合中小团队快速验证产品方案。
- 👉 中文VLA学习手册 [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook)：国内首份实战导向的VLA全栈学习资源，聚焦机器人领域特有的数据、模型、部署挑战，适合算法工程师快速入门VLA方向，填补了中文VLA学习资源的空白。
- 👉 开源人形机械臂 [enactic/openarm](https://github.com/enactic/openarm)：完全开源的接触富集场景专用机械臂，硬件成本远低于同类商用产品，填补了开源人形上肢硬件的空白，适合物理AI研究与低成本落地场景。
- 👉 高性能机器人运行时 [softmata/horus](https://github.com/softmata/horus)：Rust编写的低延迟机器人runtime，对标手机端的Android系统，是机器人底层系统架构的新兴探索方向，有望解决当前机器人系统性能瓶颈问题。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*