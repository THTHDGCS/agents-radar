# AI 开源趋势日报 2026-08-01

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-08-01 01:46 UTC

---

# 具身智能与机器人开源趋势日报（2026-08-01）
---

## 今日速览
2026年8月1日GitHub全站Trending无直接相关的具身智能/机器人项目，领域核心热点集中在垂直主题的7天活跃项目中，核心方向为VLA落地工具链、人形机器人全栈开源、具身安全三大类，社区资源从入门教程向工业级部署框架快速倾斜。NVIDIA官方开放Alpamayo VLA的微调、RL后训练、量化、部署全流程配方，成为今日最受关注的官方资源，大幅降低大模型落地物理硬件的门槛。人形机器人领域从单体运动控制向全身VLA统一控制、多智能体竞技基准延伸，同时涌现出无ROS的轻量化sim2real部署框架，适配中小团队的快速落地需求。具身AI安全首次成为集中上榜的细分方向，覆盖策略评估、红队测试、安全损失嵌入等全链路工具，响应行业对物理AI风险管控的迫切需求。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、运动）
1. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,857
   Rust编写的数据流导向机器人中间件，支持低延迟、可组合、分布式数据流，是当前社区热度最高的下一代AI原生机器人架构方案。
2. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,280
   全球星量最高的开源机器人操作系统之一，已支持300+量产车型的辅助驾驶升级，是具身智能在乘用车场景落地的标杆项目。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,400
   通用多关节接触物理仿真器，是机器人学习、VLA训练的核心基础工具，近期持续更新面向人形机器人的接触仿真优化。
4. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,813
   基于NVIDIA Isaac Sim构建的统一机器人学习框架，原生支持VLA训练、RL部署与sim2real迁移，是当前工业级机器人学习的首选框架。
5. [softmata/horus](https://github.com/softmata/horus) ⭐402
   号称“机器人界Android”的高性能机器人运行时系统，采用Rust编写，面向人形机器人的低延迟实时控制需求，是新兴的机器人OS候选方案。

### 🧠 VLA/基础模型（视觉-语言-动作、模仿/强化学习策略）
1. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐459
   国内首份全中文、实战导向的VLA领域学习/面试手册，聚焦机器人领域特有的技术挑战，填补了国内VLA系统化学习资源的空白。
2. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐123
   面向通用具身智能的开放世界基础模型，是少数开源的通用VLA基础模型方案，支持多场景机器人任务迁移。
3. [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) ⭐83
   NVIDIA官方发布的Alpamayo VLA开发者资源库，提供微调、RL后训练、量化、部署的全流程现成配方，是当前VLA落地的核心官方参考。
4. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,945
   面向Python基础开发者的零基础具身智能入门项目，支持从0搭建VLA/OpenVLA/SmolVLA/Pi0等主流模型，是入门具身智能的首选实践资源。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐104
   开源物理AI评估工具，支持任意LLM/VLA在任意机械臂/人形机器人的仿真/真实基准测试，解决了VLA效果统一评估的行业痛点。
6. [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐121
   具身AI安全领域最全的综述资源，收录500+相关论文，覆盖感知、认知、规划、系统全链路风险与防御方案。

### 🦾 操作与抓取（灵巧手、抓取、接触富集任务）
1. [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,185
   GPU并行化的机器人操作仿真框架与基准平台，支持上万路并行的VLA/RL策略训练，是当前具身操作领域应用最广的基准之一。
2. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,788
   完全开源的人形机械臂项目，面向接触富集环境的物理AI研究与部署，填补了高性价比开源人形上肢硬件的空白。
3. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐324
   新一代机器人操作基准平台，针对复杂接触任务的策略评估设计，是操作领域新兴的基准方案。
4. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐43
   开源双手通用操作接口（UMI）数据采集软件，支持同步采集与数据重定向到任意双臂机器人，降低了VLA操作数据的采集门槛。
5. [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes) ⭐1
   探索将碰撞安全损失直接嵌入PI0 VLA训练权重而非依赖runtime过滤，为操作安全提供了端到端的新思路。

### 🚶 运动与导航（足式、人形、SLAM、路径规划）
1. [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐2
   采用统一VLA框架实现人形机器人全身运动与操作的无缝控制，支持大空间复杂任务，是VLA从单臂操作向全身人形延伸的代表性项目。
2. [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐352
   面向人形机器人实时全身运动规划与控制的非线性MPC方案，是人形运动控制领域的核心开源技术参考。
3. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐143
   全身人形机器人遥操作系统，支持低延迟的全姿态采集与重定向，是人形数据采集、远程部署的核心工具。
4. [KaushikSiva/robot-gym](https://github.com/KaushikSiva/robot-gym) ⭐0
   面向Unitree G1人形机器人的具身AI竞技竞技场，支持AI vs AI、人机对战等模式，是人形机器人能力评估的新兴场景。
5. [introlab/rtabmap](https://github.com/introlab/rtabmap) ⭐3,921
   成熟的开源SLAM库与standalone应用，支持多传感器融合的实时定位与地图构建，是移动机器人导航的核心工具。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,363
   面向具身智能与Agent AI的强化学习基础设施，支持大规模RL训练与部署，是具身智能工程化落地的核心底层设施。
2. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,353
   基于Agent工作流的自进化具身AI操作系统，支持机器人技能的自动迭代与runtime管理，是OS级具身系统的代表性方案。
3. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐112
   支持通过自然语言直接控制各类机器人与物理硬件的Agent框架，降低了非专业用户操作机器人的门槛。
4. [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8
   VLA驱动的开源漫游车项目，搭载完整的视觉-语言-动作管线并公开了对应的ECoT数据集，是小型移动具身机器人的落地参考案例。
5. [dsl-robotics/skatearm](https://github.com/dsl-robotics/skatearm) ⭐1
   面向工业装配场景的开源双臂工作单元，采用仿真优先的开发模式，支持自主装配、摄像头QC与ROS2桥接，是具身智能工业落地的探索项目。

---

## 趋势信号分析
今日数据显示，VLA落地工具链与具身AI安全正在获得社区爆发性关注：前者涌现出NVIDIA官方全流程部署配方、跨平台统一评估框架、零基础实践教程等全链路资源，覆盖从入门到工业落地的全层级需求；后者首次集中出现安全综述、策略红队测试、端到端安全损失训练等细分项目，填补了领域长期的工具空白。
新兴技术栈方面，无ROS的轻量化sim2real部署框架、全身人形VLA统一控制、VLA内嵌安全训练范式首次集中登榜，反映社区核心需求已从“演示VLA能力”向“低成本落地VLA”转型。
该趋势与近期行业事件高度相关：上月NVIDIA正式开源Alpamayo VLA模型、全球人形机器人量产进程加速、多国启动物理AI安全监管调研，直接推动了社区对落地工具与风险管控方案的需求。（全文287字）

---

## 社区关注热点
- 🎯 **[NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes)**：NVIDIA官方发布的Alpamayo VLA全流程开发资源，是当前工业级VLA落地的最权威参考，适合所有面向机器人部署的VLA开发者跟进。
- 📚 **[sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook)**：国内首份实战导向的中文VLA学习手册，填补了国内系统化VLA学习资源的空白，适合想要入门或转岗VLA领域的算法工程师。
- 🦾 **[enactic/openarm](https://github.com/enactic/openarm)**：完全开源的人形机械臂硬件项目，大幅降低了人形上肢的研发门槛，适合面向人形机器人操作方向的研究团队与创业团队参考。
- 🔒 **具身AI安全方向**：今日集中上线了从综述到红队测试、端到端安全训练的全链路项目，是具身智能领域的新兴蓝海方向，提前布局可抢占行业标准制定的先机。
- ⚡ **无ROS轻量化机器人框架**：以`robot-control-stack`、`horus`为代表的新一代轻量框架，适配AI原生机器人的开发需求，适合中小团队快速落地具身应用。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*