# AI 开源趋势日报 2026-08-03

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-08-03 01:45 UTC

---

# 具身智能与机器人开源趋势日报（2026-08-03）
---

## 今日速览
今日GitHub Trending无具身智能、机器人或VLA相关的垂直项目登榜，核心活跃项目集中在7天内更新的主题仓库，整体社区热度向基础工具链和落地实践倾斜。NVIDIA机器人生态相关项目持续保持高活跃度，Isaac Lab统一学习框架、Alpamayo VLA开发工具包、基于Warp的Newton物理引擎均获得大量开发者关注，头部厂商的开源生态正在形成行业技术标准。中文开发者的具身智能学习资源供给加速，从零基础VLA实践教程、中文面试手册到产业知识地图的项目密集更新，大幅降低了国内开发者的入门门槛。人形机器人领域的开源项目转向落地导向，运动控制、遥操作、服务场景原型类工具密集推出，与近期国内人形机器人产业政策落地、量产计划发布的行业节奏高度匹配。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、中间件）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,297（总）：面向机器人的开源操作系统，当前已支持300+款车型的ADAS升级，是全球star量最高的机器人开源项目，生态成熟度极高。
2. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,601（总）：覆盖无人机、无人车、无人船、水下机器人的通用运动控制固件，是移动机器人控制领域的事实标准开源项目。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,417（总）：通用多关节接触物理仿真器，是机器人学习、具身智能研发的核心基础工具，几乎所有主流VLA项目均基于其做仿真验证。
4. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,819（总）：NVIDIA推出的基于Isaac Sim的统一机器人学习框架，近期密集更新人形、操作任务的RL训练支持，是sim2real研发的首选框架之一。
5. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,858（总）：面向AI机器人的数据流驱动中间件，主打低延迟、可组合、分布式部署，为VLA驱动的机器人应用提供了轻量化的ROS替代方案。
6. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,275（总）：基于NVIDIA Warp的GPU加速物理仿真引擎，专门针对机器人研发优化，比传统仿真器速度提升数倍，适合大规模VLA预训练的数据生成。

### 🧠 VLA/基础模型（视觉-语言-动作、机器人学习策略）
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,955（总）：面向Python基础开发者的零基础具身智能实践教程，覆盖从0构建VLA/OpenVLA/SmolVLA/Pi0的全流程，是国内入门VLA的最热门实践资源。
2. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,463（总）：基于Agent工作流的自进化具身AI操作系统，支持技能自动进化、物理记忆、安全沙箱等特性，是首个面向实体机器人的Agent OS开源实现。
3. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐461（总）：全中文实战导向的VLA领域学习/面试手册，聚焦机器人领域的特有挑战，填补了国内VLA领域系统化学习资料的空白。
4. [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) ⭐83（总）：NVIDIA最新VLA模型Alpamayo的官方开发工具包，包含微调、RL后训练、量化、部署的开箱即用脚本，是落地Alpamayo的核心资源。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐119（总）：开源物理AI/VLA评测框架，支持任意LLM/VLA在任意机械臂/人形机器人上的跨基准评测，解决了VLA效果评估不统一的痛点。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐126（总）：无ROS依赖的轻量sim2real框架，原生支持VLA模型和RL Agent的训练与部署，适配Franka、UR5e、xArm等主流机械臂，降低了VLA落地的工程门槛。

### 🦾 操作与抓取（灵巧手、操作任务、技能规划）
1. [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,196（总）：GPU并行的机器人操作仿真与基准框架，支持大规模操作任务的训练与评测，是VLA操作能力评估的主流基准之一。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐332（总）：新兴的机器人操作基准，覆盖多场景、多难度的接触富集操作任务，填补了现有基准的场景覆盖空白。
3. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐44（总）：开源双手操作数据采集与重定向工具，支持将遥操作数据重定向到任意双臂机器人，解决了灵巧操作数据采集成本高的痛点。
4. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐97（总）：将自然语言指令编译为可验证的机器人技能图的框架，支持在仿真和真实机器人上执行操作任务，实现了VLA输出的可解释性与安全性校验。
5. [zcy13/cofree-arm](https://github.com/zcy13/cofree-arm) ⭐0（总）：无需训练策略的桌面机械臂操作方案，采用“多模态大模型管语义+几何方法管数值”的架构，单次任务成本仅0.2元，是轻量级桌面机器人落地的新思路。

### 🚶 运动与导航（足式、人形、SLAM、路径规划）
1. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐324（总）：人形、足式机器人的核心运动控制算法库，包含动量基控制器、足式 locomotion 算法，由波士顿动力Atlas核心团队开源，技术可靠性极高。
2. [introlab/rtabmap](https://github.com/introlab/rtabmap) ⭐3,925（总）：成熟的RGB-D/LiDAR SLAM库，支持多传感器融合的实时定位与建图，是移动机器人、人形机器人导航的核心感知工具。
3. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,543（总）：ROS2生态的官方导航框架，支持路径规划、避障、多机器人协同，是移动机器人导航的事实标准。
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐143（总）：全身人形机器人遥操作系统，支持动捕、VR等多种输入方式，解决了人形机器人数据采集、远程操作的工程痛点。
5. [robit-man/dropbear-locomotion](https://github.com/robit-man/dropbear-locomotion) ⭐0（总）：基于Isaac Lab和RSL-RL PPO的Dropbear人形机器人 locomotion 实现，提供预训练checkpoint和仿真环境，是人形运动控制入门的绝佳参考。

### 📦 具身应用（教程、产业、落地原型）
1. [TianxingChen/Embodied-AI-Guide](https://github.com/TianxingChen/Embodied-AI-Guide) ⭐15,195（总）：Lumina具身智能社区出品的具身智能技术指南，是国内star量最高的具身智能入门资源，覆盖技术栈、产业、论文等全维度内容。
2. [Octoday-Hub/Embodied-AI](https://github.com/Octoday-Hub/Embodied-AI) ⭐2,219（总）：国内首个具身智能知识索引与产业地图，梳理了从核心技术到落地场景的全产业链，适合从业者把握行业格局。
3. [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover) ⭐9,552（总）：NASA JPL开源的可自制6轮火星漫游车，提供完整的硬件BOM、3D打印模型、软件源码，是移动机器人硬件落地的标杆项目。
4. [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐240（总）：最小化具身智能软硬件架构，为大模型提供带自感知闭环的物理实体，适合个人开发者快速搭建首个具身智能原型。
5. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐51（总）：面向化学实验室自动化的机器人数字孪生平台，实现了机器人操作与实验室场景的虚实同步，是具身智能在工业场景落地的典型案例。

---

## 趋势信号分析
今日社区热度集中在具身智能基础工具链与入门资源两大方向，其中NVIDIA生态的机器人开源项目正在形成开发者集聚效应，Isaac Lab、Alpamayo VLA工具包、Newton仿真引擎的活跃度均领先同类项目，头部厂商的技术栈正快速成为行业事实标准。其次，中文开发者的具身智能供给侧爆发，覆盖从入门到就业全链路的学习资源密集更新，反映了国内具身智能人才缺口下的学习需求暴涨。另外，人形机器人的落地导向项目显著增多，研发重心逐步从算法验证向场景落地转移，与近期国内人形机器人产业政策落地、头部厂商发布量产计划的行业节奏高度吻合。（全文278字）

---

## 社区关注热点
- 重点关注 [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)：国内首个面向Python基础开发者的VLA全流程实战教程，无需高端硬件即可完成从0到1的VLA构建，社区更新频率高、反馈活跃，是切入VLA领域的最佳入门资源。
- 重点关注 [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes)：NVIDIA最新开源VLA模型Alpamayo的官方开发工具包，提供微调、RL后训练、量化、部署的开箱即用脚本，Alpamayo是当前性能顶尖的开源VLA模型，该项目将大幅降低VLA落地的工程门槛。
- 重点关注人形机器人开源工具链：今日集中更新了足式运动控制、全身遥操作、服务场景仿真等多个核心项目，反映社区正在为人形机器人的量产落地做工具链准备，提前布局相关技术栈将获得先发优势。
- 重点关注 [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS)：首个面向实体机器人的具身Agent OS开源项目，将大模型Agent的工作流范式引入物理机器人领域，支持技能自进化、物理记忆、安全沙箱等特性，代表了具身智能系统架构的新方向。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*