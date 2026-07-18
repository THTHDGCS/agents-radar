# AI 开源趋势日报 2026-07-18

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-18 01:20 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-18）

---

## 今日速览
今日具身智能与机器人开源领域呈现三大核心动向：一是低门槛VLA学习资源密集涌现，中文教程与入门手册填补了国内开发者的系统化学习空白；二是人形机器人开源软硬件方案持续升温，从机械臂硬件到全身控制基础模型均有高星项目更新；三是具身智能基础设施进一步完善，新兴中间件、运行时、部署工具逐步形成替代传统ROS的技术栈。此外，VLA评测与sim2real落地工具的关注度持续上升，标志着领域正从算法研发向落地验证阶段过渡。

---

## 各维度热门项目

### 🤖 机器人框架/SDK
1. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,846
   Rust开发的面向AI机器人的数据流中间件，主打低延迟、可组合、分布式特性，是目前替代ROS的新兴轻量框架，适合具身应用快速搭建，近期社区活跃度持续上升。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,698
   NVIDIA基于Isaac Sim的统一机器人学习框架，今日多个操作、人形项目均基于其开发，是当前具身智能sim2real训练的核心基础设施。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,247
   通用多关节动力学物理仿真器，是机器人学习、人形控制的标配仿真工具，持续维护更新，生态覆盖全品类机器人场景。
4. [softmata/horus](https://github.com/softmata/horus) ⭐389
   Rust开发的高性能机器人运行时系统，定位“机器人界的Android”，主打低延迟调度，是新兴的具身应用底层基座。
5. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,149
   面向具身与智能体的强化学习基础设施，统一RL训练工作流，大幅降低具身智能模型的训练门槛。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124
   无ROS的VLA/RL智能体sim2real部署框架，原生支持MuJoCo Gymnasium，适配多款主流机械臂与人形，适合VLA模型快速落地。

### 🧠 VLA/基础模型
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,727
   中文入门教程，仅需Python基础即可从零构建具身机器人，涵盖OpenVLA、SmolVLA等主流VLA实现，是国内开发者入门具身智能的首选资源，近期star增长迅速。
2. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐401
   全中文实战导向的VLA学习/面试手册，聚焦机器人领域特有挑战，填补了中文VLA系统化学习资料的空白。
3. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐505
   新一代通用VLA模型InternVLA-A1，统一机器人操作的理解、生成与动作能力，是国内开源的标杆性VLA方案。
4. [knightnemo/Awesome-World-Models](https://github.com/knightnemo/Awesome-World-Models) ⭐3,174
   世界模型领域精选资源列表，涵盖具身AI、视频生成等方向的论文与代码，是研究具身世界模型的一站式资源。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐6
   VLA/物理AI模型的统一评测框架，支持一次定义基准、跨机器人/仿真运行任意策略，是VLA标准化评测的新兴工具。
6. [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)（今日新增⭐+431）
   支持Kimi K3等开源大模型的编码智能体，可作为具身智能的上层规划与代码执行模块，今日登上GitHub总榜前列，社区关注度极高。

### 🦾 操作与抓取
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,733
   完全开源的人形机械臂，面向接触富集的物理AI研究与部署，填补了低成本通用机械臂开源方案的空白，star量增长极快。
2. [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) ⭐38
   双向对齐的具身智能体框架，面向长Horizon操作任务，解决了长序列操作的模态对齐痛点。
3. [RoboTwin-Platform/RMBench](https://github.com/RoboTwin-Platform/RMBench) ⭐170
   基于RoboTwin的记忆依赖型操作基准，填补了长时序操作任务评测的空白。
4. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐258
   机器人操作任务基准平台，支持多场景操作任务的训练与评测。
5. [iit-DLSLab/locomanipulation-teleop-isaaclab](https://github.com/iit-DLSLab/locomanipulation-teleop-isaaclab) ⭐21
   基于IsaacLab的足式机器人+机械臂遥操作环境，支持sim2sim和sim2real pipeline，适合复合操作任务开发。

### 🚶 运动与导航
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,148
   面向机器人的通用操作系统，目前已支持300+车型的辅助驾驶升级，是落地规模最大的开源机器人运动控制系统之一。
2. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐583
   面向人形机器人全身控制的基础模型，是国内开源的标杆性人形运动控制大模型，关注度持续上升。
3. [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐819
   面向足式机器人的IsaacLab直接工作流，大幅简化足式机器人的仿真训练与部署流程。
4. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐258
   UMI-3D SLAM与数据处理pipeline，为具身智能的环境感知提供高精度定位方案。
5. [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐26
   低成本全3D打印开源人形机器人，基于树莓派Zero 2W，是入门人形机器人的高性价比硬件方案。

### 📦 具身应用
1. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐704
   基于智能体工作流的自进化具身智能操作系统，支持具身智能的端到端部署与自主迭代。
2. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,598
   RoboTwin 2.0数字孪生平台，支持机器人的仿真训练与数字孪生验证，是sim2real落地的核心工具。
3. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐132
   轻量可扩展的人形机器人全身遥操作框架，大幅降低人形遥操作的开发门槛。
4. [FastCrest/tether](https://github.com/FastCrest/tether) ⭐73
   开源端边云AI部署CLI，支持Jetson、RTX、Apple Silicon等多硬件的VLA模型优化部署，解决具身模型的边缘落地痛点。

---

## 趋势信号分析
今日开源社区的爆发性关注集中在**低门槛VLA入门资源与人形开源软硬件**两大方向：一方面，全中文VLA手册、零基础具身智能构建教程的star量快速增长，直接对应近期OpenVLA、Pi0等开源VLA模型发布后，国内开发者的入局需求激增；另一方面，全开源人形机械臂、低成本3D打印人形硬件、专用机器人运行时等项目密集登榜，反映具身智能正在从算法研究向全栈落地、硬件自主的方向演进。同时，VLA统一评测框架、无ROS的sim2real部署工具的出现，标志着VLA领域正在进入标准化落地的新阶段，与行业近期对VLA落地能力的高度关注高度契合。（全文287字）

---

## 社区关注热点
- 🎯 入门学习首选：[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)，仅需Python基础即可从零搭建VLA模型与具身机器人，中文教程适配国内开发者路径，大幅降低具身智能入门门槛。
- 🦾 硬件开源标杆：[enactic/openarm](https://github.com/enactic/openarm)，完全开源的接触富集型人形机械臂，填补了低成本通用机械臂开源方案的空白，适合物理AI研究与小批量落地验证。
- 🔧 基础设施新方向：Rust语言开发的机器人运行时[softmata/horus](https://github.com/softmata/horus)，主打高性能低延迟，定位“机器人界的Android”，有望成为替代ROS的新一代底层基座。
- 📊 领域标准化信号：VLA评测框架[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)、无ROS部署框架[RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)等工具涌现，解决了VLA从训练到落地的标准化痛点，将成为后续领域核心基础设施。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*