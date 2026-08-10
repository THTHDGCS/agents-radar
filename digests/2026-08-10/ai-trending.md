# AI 开源趋势日报 2026-08-10

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-08-10 00:52 UTC

---

# 具身智能与机器人开源趋势日报 | 2026-08-10

---

## 今日速览
今日GitHub全球热榜暂无具身智能、机器人、VLA领域相关项目，核心动向来自7天内标记相关主题的活跃开源项目。本周活跃项目呈现三大集中方向：NVIDIA主导的自动驾驶域VLA模型密集迭代、人形机器人软硬件开源项目快速增长、中文社区的具身入门资源热度持续攀升。专门面向具身智能的操作系统类项目首次进入活跃榜单，反映领域正从零散算法开发向系统级整合演进。操作基准、足式运动控制等落地支撑类项目更新频繁，对应产业端对sim2real、通用控制方案的迫切需求。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14.5k（总量）
  通用多关节接触动力学仿真器，是具身智能与机器人仿真的事实标准工具，本周持续迭代动力学计算与多平台适配能力，是所有机器人仿真研发的基础依赖。
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7.9k（总量）
  基于NVIDIA Isaac Sim构建的统一机器人学习框架，本周新增VLA模型训练的原生接口，大幅降低了通用机器人策略的开发门槛。
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3.9k（总量）
  面向AI机器人的数据流导向中间件，本周新增ROS2无缝兼容层，支持低延迟分布式具身系统部署，是目前最活跃的下一代机器人中间件项目。
- [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11.3k（总量）
  多模态机器人数据可视化与流式处理工具，本周新增高斯泼洒场景的原生渲染支持，适配高保真仿真的数据可视化需求。
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4.5k（总量）
  面向具身智能与代理AI的强化学习基础设施，本周更新VLA训练的分布式支持，大幅降低了大规模具身策略的训练成本。
- [softmata/horus](https://github.com/softmata/horus) ⭐408（总量）
  号称「机器人界Android」的高性能机器人运行时系统，本周更新实时调度模块，是下一代机器人操作系统的有力竞争者。

---

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
- [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐2.0k（总量）
  NVIDIA开源的10B参数自动驾驶域VLA模型，支持带因果链推理的轨迹生成，是目前首个开源的量产级自动驾驶VLA参考实现。
- [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐148（总量）
  本周新发布的34B参数多任务VLA模型，支持自动驾驶全栈任务，是目前参数规模最大的开源垂直场景VLA，标志着VLA向高复杂度垂直场景渗透。
- [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) ⭐211（总量）
  BridgeVLA与BridgeVLA++的官方实现，本周新增10+机器人平台的适配接口，是通用机器人VLA策略跨平台迁移的核心参考项目。
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐486（总量）
  国内首份全中文实战导向的VLA学习/面试手册，专门针对机器人领域特有的技术挑战设计，本周新增OpenVLA部署教程，大幅降低了国内开发者的VLA入门门槛。
- [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐2（总量）
  本周新开源的人形全身统一VLA控制框架，支持人形机器人运动与操作的无缝协同，是首个面向全身控制的开源VLA方案。

---

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2.8k（总量）
  完全开源的人形手臂硬件方案，面向接触富集的物理AI研究设计，本周更新MuJoCo与Isaac Sim的仿真模型，填补了开源人形上肢硬件的空白。
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3.2k（总量）
  GPU并行化机器人操作仿真与基准框架，本周新增20+柔性操作任务，是目前任务覆盖最广的操作学习基准。
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐371（总量）
  机器人操作基准官方仓库，本周更新VLA模型的自动评测脚本，支持主流VLA的一键评测。
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8（总量）
  本周新发布的双机械臂厨房操作基准，专门针对VLA模型的日常操作能力评测设计，是首个面向家庭场景的双操作基准。
- [codeofwhite/awesome-deformable-manipulation](https://github.com/codeofwhite/awesome-deformable-manipulation) ⭐1（总量）
  本周新整理的可变形物体操作资源列表，覆盖仿真、基准、sim2real等方向，填补了该细分领域的资源空白。

---

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63.4k（总量）
  面向机器人的通用操作系统，目前已支持300+车型的驾驶辅助升级，本周更新端到端驾驶策略的VLA适配接口，是落地规模最大的具身智能系统之一。
- [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30.3k（总量）
  机器人算法经典教材与Python实现库，本周新增人形双足行走的RL算法实现，是机器人运动控制入门的首选资源。
- [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) ⭐5.1k（总量）
  开源四足机器人宠物框架，本周更新低成本四足的运动控制固件，是DIY四足机器人的主流参考方案。
- [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐268（总量）
  ECCV 2026录用的高保真导航仿真器，基于动态高斯泼洒构建场景，本周开源，大幅提升了导航仿真的真实性与sim2real成功率。
- [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) ⭐38（总量）
  本周开源的人形足球射门算法官方实现，实现了人形机器人的高精度、高稳定性动态运动控制，为人形复杂运动任务提供了参考方案。

---

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3.1k（总量）
  面向Python基础开发者的具身智能入门教程，从零构建VLA/OpenVLA等模型与实体机器人，本周新增SmolVLA的部署章节，是国内热度最高的具身入门资源。
- [Octoday-Hub/Embodied-AI](https://github.com/Octoday-Hub/Embodied-AI) ⭐2.3k（总量）
  国内具身智能生态社区资源聚合平台，覆盖论文、项目、招聘等信息，本周新增2026年人形机器人产业图谱，是具身从业者的核心信息源。
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2.7k（总量）
  ICML 2026录用的RoboTwin 2.0官方代码仓库，本周更新数字孪生与VLA模型的协同训练接口，是机器人数字孪生的核心参考项目。
- [PhyAgentOS-Dev/PhyAgentOS](https://github.com/PhyAgentOS-Dev/PhyAgentOS) ⭐1.8k（总量）
  自进化具身智能操作系统，基于代理工作流构建，本周更新实体机器人的适配层，是目前最活跃的专门面向具身智能的操作系统项目。
- [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) ⭐6.7k（总量）
  开源智能割草机器人方案，基于RTK GPS实现高精度导航，本周更新避障算法，是消费级具身机器人落地的标杆项目。

---

## 趋势信号分析
本周开源领域呈现三大明确趋势：一是VLA加速向垂直场景落地，NVIDIA连续发布三代Alpamayo系列VLA，从10B推理模型到34B多任务大模型全部面向自动驾驶设计，标志着VLA已从通用机器人操作的实验室阶段，进入高复杂度垂直场景的产业化落地阶段。二是具身系统向OS级整合演进，PhyAgentOS等专门的具身智能操作系统首次进入活跃榜单，反映领域已从零散算法开发转向统一系统架构的探索，对应产业端对标准化具身系统的需求。三是中文具身生态快速成熟，入门教程、VLA手册、产业资源库密集更新，叠加近期人形机器人产业扶持政策与量产进展，开源生态与产业需求的正向循环正在形成。

---

## 社区关注热点
- **NVIDIA Alpamayo VLA系列**：连续迭代3个版本，覆盖10B到34B参数，配套提供微调、RL后训练、量化、部署的全流程开发食谱，是目前最成熟的垂直场景VLA开源方案，适合自动驾驶、工业机器人等领域的VLA二次开发。
- **中文具身入门资源矩阵**：datawhale《every-embodied》从零构建具身机器人与VLA模型，《VLA-Handbook》提供全中文VLA学习面试指南，二者搭配大幅降低了具身智能的入门门槛，是新手进入领域的首选学习路径。
- **开源人形手臂openarm**：完全开源的人形上肢硬件方案，配套仿真模型与控制接口，填补了开源人形操作硬件的空白，适合物理AI研究、工业人形机器人原型开发，是本周最值得关注的硬件开源项目。
- **高保真仿真工具迭代**：基于高斯泼洒的导航仿真器habitat-gs、支持GPU并行的操作基准ManiSkill本周均有重大更新，高保真、高效率的仿真工具正在成为VLA训练与sim2real落地的核心支撑，相关研发者可重点跟进。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*