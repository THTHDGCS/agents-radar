# AI 开源趋势日报 2026-08-07

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-08-07 02:02 UTC

---

# 具身智能与机器人开源趋势日报（2026-08-07）
---
## 今日速览
今日GitHub实时Trending榜单以通用AI Agent工程化（编码Agent技能、Agent状态管理）项目为主，暂无具身智能、VLA与机器人领域的相关项目登榜，领域热度集中在7天内活跃的主题仓库中。NVIDIA Alpamayo系列VLA持续迭代，最新34B参数的Alpamayo 2 Super聚焦自动驾驶场景，带动VLA垂直场景落地的关注度。面向开发者的中文VLA/具身智能入门教程仓库活跃度持续上升，软硬件一体化的开源人形机械臂、无ROS的轻量VLA部署框架成为社区新热点。机器人评估工具链不断完善，出现了面向厨房操作等垂直场景的VLA专用基准，进一步降低VLA落地的验证成本。
---
## 各维度热门项目
注：以下项目均来自7天活跃主题仓库，无今日实时新增Star数据。
### 🤖 机器人框架/SDK
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,848：NVIDIA官方推出的统一机器人学习框架，基于Isaac Sim构建，支持VLA训练、RL仿真与sim2real部署，是当前机器人学习领域的首选工业级框架
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,869：Rust编写的低延迟数据流机器人中间件，采用有向图建模应用管线，支持分布式部署与AI能力快速集成，适合构建复杂具身智能系统
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,470：机器人领域标配的多关节接触物理仿真器，GPU加速性能优异，是几乎所有VLA/RL机器人项目的仿真底座
- [softmata/horus](https://github.com/softmata/horus) ⭐407：Rust编写的高性能机器人运行时，定位为“机器人的Android”，针对低延迟运动控制优化，是新兴的机器人操作系统备选方案
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐127：无ROS的轻量sim2real框架，原生适配MuJoCo与主流机械臂，支持VLA模型与RL策略的快速部署，大幅降低落地门槛

### 🧠 VLA/基础模型
- [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐117：NVIDIA最新发布的34B多任务VLA基础模型，专门面向自动驾驶场景优化，支持推理、导航、VQA等能力，是VLA向垂直大场景落地的标杆项目
- [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) ⭐201：通用VLA模型BridgeVLA与BridgeVLA++的官方实现，是当前具身操作领域引用量最高的开源VLA基线之一
- [dexmal/opendm](https://github.com/dexmal/opendm) ⭐142：面向通用具身智能的开放世界基础模型，支持跨场景的多模态感知与决策，是通用具身大模型的新兴探索
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐479：国内首份全中文VLA实战/面试手册，聚焦机器人领域特有的技术挑战，覆盖从入门到进阶的全链路知识点，适合算法工程师快速上手
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,029：面向Python基础开发者的具身智能入门教程，从零手把手构建OpenVLA、SmolVLA等主流模型，是当前国内门槛最低的实战型学习资源

### 🦾 操作与抓取
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,817：完全开源的人形机械臂，针对接触富集的物理AI场景优化，可直接用于研究与落地，填补了中低成本通用开源执行器的市场空白
- [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,205：GPU并行化的机器人操作仿真基准，支持上百种操作任务与多类型机械臂，是VLA操作能力评估的主流基准
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐361：新一代机器人操作基准仓库，覆盖更多真实场景的接触富集任务，为VLA操作能力评估提供更严格的测试集
- [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8：首个面向厨房双手操作的VLA专用基准，基于Inspect Robots框架构建，填补了垂直家庭场景VLA评估的空白
- [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐46：开源双手操作数据采集与重定向工具，支持将遥操作数据快速适配到任意双手机器人，降低操作数据的采集成本

### 🚶 运动与导航
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,351：全球最受欢迎的开源机器人操作系统之一，目前已支持300+款车型的高级辅助驾驶，是VLA技术落地自动驾驶场景的典型参考
- [NJU-RLC/quadrupedal-agility](https://github.com/NJU-RLC/quadrupedal-agility) ⭐122：南京大学发布的四足机器人敏捷行为学习官方实现，可让四足机器人获得多样化的自然运动能力，是足式机器人学习的最新成果
- [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐324：全球顶尖的足式机器人运动控制算法库，支持人形、四足、外骨骼等多种平台的运动控制，是足式运动控制的标杆项目
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐156：全身体人形机器人遥操作系统，支持通过人体动捕快速控制人形机器人的全身运动，降低人形机器人的调试与数据采集门槛
- [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,558：ROS2生态的标准导航框架，支持SLAM、路径规划、避障等全链路能力，是移动机器人导航的首选开源方案

### 📦 具身应用
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,690：ICML 2026收录的RoboTwin 2.0数字孪生官方代码，支持机器人的高精度虚实同步，是sim2real落地的核心支撑技术
- [PhyAgentOS-Dev/PhyAgentOS](https://github.com/PhyAgentOS-Dev/PhyAgentOS) ⭐1,654：自进化具身AI操作系统，基于Agent工作流构建，支持具身智能体的自主迭代与任务执行，是具身OS的新兴探索
- [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,623：斯坦福大学推出的具身AI研究平台，覆盖上千种真实家庭场景任务，是通用具身智能能力验证的核心测试床
- [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐244：给大模型加装闭环物理具身的最小软硬件架构，支持自感知循环，可快速验证大模型的物理交互能力
- [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) ⭐5,061：成熟的开源四足机器宠物框架，支持DIY与二次开发，是具身智能技术面向消费级场景落地的典型案例
---
## 趋势信号分析
当前VLA的垂直场景落地正成为社区核心爆发方向：NVIDIA连续迭代Alpamayo系列自动驾驶VLA，参数从10B升级至34B，新增强化学习增强推理、导航引导、VQA等能力，标志着VLA正从通用机器人操作向自动驾驶等千亿级垂直场景快速渗透，与近期自动驾驶企业大模型化的行业趋势高度契合。其次，无ROS的轻量VLA部署框架首次进入活跃榜单，原生适配MuJoCo、支持多类型主流机械臂的sim2real一站式框架，解决了传统ROS栈冗余、VLA部署门槛高的痛点，贴合当前产业端VLA快速落地的需求。此外，软硬一体化项目热度显著上升，全开源人形机械臂openarm斩获2.8k星，呼应了近期人形机器人产业对低成本通用执行器的迫切需求，开源社区正从纯算法研发向可落地的软硬协同方案转移。
---
## 社区关注热点
- 🎯 【入门首选】[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)：仅需Python基础即可从零构建OpenVLA、SmolVLA等主流模型，实战性强、门槛低，是新手进入具身智能领域的最优学习路径
- 🛠️ 【部署神器】[RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)：无ROS的轻量VLA/RL部署框架，原生适配MuJoCo与Franka、UR5e等主流机械臂，同步仿真与真实执行，大幅降低sim2real的调试成本
- 🦾 【硬件标杆】[enactic/openarm](https://github.com/enactic/openarm)：完全开源的人形机械臂，针对接触富集场景优化，可直接用于物理AI研究与落地，填补了中低成本通用开源执行器的空白
- 📊 【评估工具】[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)：通用VLA/机器人评估框架，支持任意模型在任意机械臂/人形平台上跑通仿真/真实基准，是当前VLA效果验证的首选工具
- 📚 【学习手册】[sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook)：国内首份全中文VLA实战/面试手册，聚焦机器人领域特有的技术挑战，覆盖从入门到进阶的全链路知识点，适合算法工程师定向提升

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*