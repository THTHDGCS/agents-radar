# AI 开源趋势日报 2026-07-15

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-15 01:16 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-15）
> 注：今日GitHub实时Trending榜单无符合筛选条件的具身智能、VLA、机器人领域项目，本次报告所有项目均来自7天内活跃的主题标签搜索结果，star数为仓库总星数。

---

## 今日速览
今日具身智能与机器人开源社区的核心热度集中在VLA落地工具链与人形机器人开源栈两大方向，中文体系化学习资源、低成本可复现的硬件/控制方案获得开发者重点关注。VLA配套生态快速完善，评估框架、安全测试、数据工程类项目批量涌现，标志着VLA正从学术研究逐步走向工程落地。ROS-free的轻量AI原生机器人控制框架成为新兴热点，面向边缘部署的VLA工具链进一步降低了落地门槛。具身强化学习基础设施、数字孪生平台的社区热度持续走高，sim2real的落地路径愈发清晰。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、运动）
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7676
   NVIDIA官方推出的统一机器人学习框架，基于Isaac Sim构建，是目前机器人仿真训练、sim2real迁移的事实标准工具链，支持VLA、RL等多类策略的训练部署。
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3842
   数据流导向的AI原生机器人中间件，用Rust实现低延迟、分布式的流水线编排，可大幅简化具身智能应用的开发流程，适合多模态VLA系统的快速搭建。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14208
   通用多关节物理仿真引擎，是目前具身智能、机器人学习领域应用最广泛的仿真工具，支持高精度的接触动力学模拟，适配人形、机械臂等多类机器人。
4. [softmata/horus](https://github.com/softmata/horus) ⭐389
   号称“机器人界Android”的高性能机器人运行时，用Rust开发，面向物理AI的实时控制需求，是新兴的机器人底层系统方案。
5. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124
   轻量ROS-free的机器人控制框架，原生支持VLA模型和RL代理的训练部署，适配Franka、UR5e等主流机械臂，集成MuJoCo Gymnasium封装，大幅降低VLA的sim2real落地门槛。
6. [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) ⭐2513
   模块化的机器人操作仿真框架与基准平台，支持多机械臂、多任务的仿真训练，是VLA操作策略训练的常用环境。

---

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐384
   国内首份全中文、实战导向的VLA领域学习/面试手册，聚焦机器人领域特有挑战，填补了中文VLA体系化资源的空白，适合算法工程师快速入门。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2665
   面向Python基础开发者的具身智能入门项目，从零讲解并实现OpenVLA、SmolVLA等主流模型，大幅降低了具身智能与VLA的入门门槛。
3. [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐112
   具身AI安全方向的权威综述，收录500+相关论文，覆盖感知、认知、规划、交互全链路风险与攻防方案，是VLA安全研究的核心参考资源。
4. [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) ⭐6
   极简可解读的VLA实现，基于冻结CLIP加轻量头构建，适配ManiSkill任务，集成LeRobot，无GPU的Mac设备即可运行，是VLA入门学习的最佳实践项目。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐3
   首个通用VLA/物理AI模型评估框架，支持“一次定义基准、任意策略在任意机器人/仿真环境运行”，解决了VLA效果难以横向对比的核心痛点。
6. [provael/provael](https://github.com/provael/provael) ⭐3
   专门针对开源VLA机器人策略的红队测试工具，可在仿真中测试策略的鲁棒性并输出攻击成功率，填补了VLA安全测试工具的空白。

---

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2720
   完全开源的双7自由度人形机械臂，专门针对接触富集的物理AI研究与部署设计，配套完整的控制与仿真栈，是目前成本最低的可量产开源操作硬件方案。
2. [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) ⭐60
   RSS 2026顶会成果开源，通过通用姿态预训练大幅提升VLA策略的泛化性，是最新一代操作类VLA的代表方案。
3. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐230
   最新推出的机器人操作基准平台，覆盖多类结构化与非结构化操作任务，支持VLA策略的标准化评测。
4. [RoboTwin-Platform/RMBench](https://github.com/RoboTwin-Platform/RMBench) ⭐167
   基于RoboTwin数字孪生平台构建的记忆依赖型操作基准，专门针对长程操作任务的VLA评测，填补了长程操作基准的空白。
5. [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) ⭐35
   双向对齐的具身Agent框架，专门优化长程操作任务的完成率，支持复杂场景下的多步骤操作规划。
6. [Manas-arumalla/openarm-control](https://github.com/Manas-arumalla/openarm-control) ⭐3
   OpenArm v2的官方控制平台，支持IK、RRT规划、模仿学习、RL、语言指令操作等全栈功能，是开源机械臂操作的核心工具。

---

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐811
   面向足式机器人的直接IsaacLab工作流，大幅简化足式机器人的仿真训练与sim2real迁移流程，是足式机器人开发的核心工具。
2. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐131
   轻量可扩展的人形机器人全身遥操作框架，适合人形机器人的运动数据采集、策略调试，支持多类输入设备接入。
3. [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐20
   完全3D打印的低成本开源人形机器人，仅需树莓派Zero 2W和19个舵机即可搭建，是人形机器人入门教学、DIY实验的最佳方案。
4. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐322
   业界领先的腿式机器人控制算法库，支持人形、双足、外骨骼等多类机器人的动量基控制与运动规划，是足式运动控制的核心参考实现。
5. [ispaik06/convex-mpc-biped](https://github.com/ispaik06/convex-mpc-biped) ⭐12
   基于凸MPC的双足机器人运动控制实现，基于MuJoCo仿真，是双足运动控制入门的最佳实践项目。
6. [Renkunzhao/legged-daily](https://github.com/Renkunzhao/legged-daily) ⭐20
   面向研究人员的足式机器人资源合集，收录代码、论文、工具等，持续更新足式运动控制的最新进展。

---

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4106
   专门面向具身智能与Agent AI的强化学习基础设施，支持大规模RL策略的训练与部署，是目前具身RL领域最热门的开源工具。
2. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2577
   开源机器人数字孪生平台，支持高精度的机器人仿真、数据采集、策略评测，是sim2real落地的核心支撑平台。
3. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐102
   基于Strands Agent的自然语言机器人控制工具，可直接通过自然语言指令控制真实机器人硬件，是VLA落地的前端交互方案。
4. [FastCrest/tether](https://github.com/FastCrest/tether) ⭐73
   开源的边云协同AI部署CLI，支持Jetson、RTX、Apple Silicon等多类硬件，可一键完成VLA模型的优化、验证、部署，解决了VLA边缘落地的核心痛点。
5. [DexForce/EmbodiChain](https://github.com/DexForce/EmbodiChain) ⭐193
   端到端GPU加速的模块化具身智能平台，支持快速搭建多类具身应用，适配不同的机器人硬件与仿真环境。
6. [drussell23/JARVIS](https://github.com/drussell23/JARVIS) ⭐22
   全栈具身AGI操作系统，集成VLA视觉管线、多传感器接入、自进化引擎，是开源全栈具身系统的探索性项目。

---

## 趋势信号分析
当前VLA生态正从模型研发向下游工具链加速转移，评估框架、安全测试、数据工程、入门模板类项目批量涌现，标志着VLA正从学术研究走向工程落地，与近期OpenVLA、SmolVLA等轻量开源模型发布后开发者落地需求激增直接相关。其次，人形机器人开源栈逐步完善，从硬件（OpenArm、Microban）到仿真工作流（TienKung-Lab）、遥操作（Teleopit）的全链条项目增多，对应2026年人形机器人产业化加速的行业趋势，开发者对低成本可复现的开发平台需求迫切。此外，ROS-free的轻量控制框架首次成为热点，针对VLA部署的专用工具链出现，反映具身智能开发正脱离传统机器人技术栈，AI原生的机器人开发范式逐步成型。（全文287字）

---

## 社区关注热点
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook)：国内首份实战导向的中文VLA学习手册，填补了中文体系化VLA资源的空白，适合算法工程师入门、面试与工程落地参考。
- [enactic/openarm](https://github.com/enactic/openarm)：2.7k星的全开源人形机械臂，配套完整的控制仿真栈，是目前接触富集操作研究成本最低的可量产开源硬件方案，适合VLA操作策略的实机验证。
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)：首个通用VLA评估框架，解决了长期以来VLA策略效果难以横向对比的核心痛点，将成为VLA研发的标配工具。
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)：ROS-free的轻量VLA部署框架，原生适配主流机械臂与仿真环境，大幅简化了VLA从训练到实机部署的流程，适合中小团队快速落地VLA应用。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*