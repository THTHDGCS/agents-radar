# AI 开源趋势日报 2026-08-15

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-08-15 00:34 UTC

---

# 具身智能与机器人开源趋势日报（2026-08-15）

---

## 今日速览
今日GitHub具身智能与机器人领域呈现四大核心动向：一是Trending榜单唯一相关项目`cactus-compute/needle`单日新增662星，14MB超小基础模型适配机器人等边缘设备，端侧轻量化具身模型首次登上热榜；二是人形机器人操作全链路开源加速，LimX Dynamics集中发布TRON2系列操作环境、仿真、模型等工具，覆盖训练到部署全流程；三是VLA基础设施补全提速，跨平台评测、安全红队测试等新工具涌现，填补落地环节空白；四是顶会成果密集开源，ICML 2026 RoboTwin 2.0、ECCV 2026 Habitat-GS等项目，推动仿真与数字孪生技术迭代。

---

## 各维度热门项目

### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,550
   通用多关节动力学物理仿真器，是机器人操作、运动控制研究的核心基础工具，长期占据机器人仿真领域的核心地位。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,899
   基于NVIDIA Isaac Sim的统一机器人学习框架，今日新增多个基于其开发的人形/操作项目，已成为具身智能训练的主流仿真底座。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,872
   数据流驱动的AI机器人中间件，具备低延迟、可组合、分布式特性，适合构建多模态具身智能应用，是替代传统ROS的新兴方案。
4. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,587
   ROS 2官方导航框架，支持路径规划、避障、SLAM对接等全链路导航能力，是移动机器人导航的事实标准工具。
5. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,358
   基于NVIDIA Warp的GPU加速物理仿真引擎，专门面向机器人研究者优化，在并行仿真效率上具备显著优势。
6. [syswonder/robonix](https://github.com/syswonder/robonix) ⭐325
   用Rust开发的具身AI操作系统（EAIOS），针对具身场景的实时性、多模态融合需求定制，是具身系统底座方向的新兴项目。

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. [cactus-compute/needle](https://github.com/cactus-compute/needle) ⭐0（+662 今日新增）
   今日Trending榜单唯一机器人相关项目，仅14MB参数的轻量基础模型，可运行在机器人、可穿戴等边缘设备，打破具身模型依赖高算力的固有认知。
2. [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) ⭐218
   BridgeVLA与BridgeVLA++的官方实现，是当前VLA领域跨场景泛化能力较强的代表性模型，受到算法研究者广泛关注。
3. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐627
   人形全身控制基础模型，支持多模态输入生成全身运动指令，是人形VLA方向的核心落地探索项目。
4. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐107
   清华MARS实验室开源的全模态运动生成框架，面向通才人形控制，是近期人形运动智能领域的顶流研究成果。
5. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐508
   全中文VLA实战学习与面试手册，聚焦机器人领域特有挑战，是国内开发者进入VLA领域的热门学习资源。
6. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐137
   物理AI开源评测框架，支持任意LLM/VLA在机械臂、人形机器人上跨仿真/真机测试，填补VLA统一评测工具的空白。
7. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,536
   面向具身与代理AI的强化学习基础设施，为VLA模型的RL训练提供全链路支持，是具身学习领域的热门底座项目。

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,852
   完全开源的人形手臂项目，面向物理AI研究与接触富集场景设计，是硬件开源领域的高人气项目，降低操作机器人的硬件门槛。
2. [worldbench/awesome-embodied-data-pyramid](https://github.com/worldbench/awesome-embodied-data-pyramid) ⭐148
   具身操作数据金字塔综述，系统梳理操作领域的数据层级与构建方法，直指当前VLA操作模型的核心瓶颈——数据问题。
3. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐23
   LimX TRON2操作机器人的OpenPI部署分支，支持pi0.5策略服务、任务微调与真机客户端，是国产操作机器人落地的代表性工具。
4. [NVlabs/oscar](https://github.com/NVlabs/oscar) ⭐139
   NVIDIA开源的数据驱动操作空间控制框架，可实现自适应、鲁棒的机器人操作，是操作控制领域的前沿研究成果。
5. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐46
   双臂同步数据采集与重定向开源软件，支持跨机器人平台的操作数据迁移，是VLA操作模型数据采集的核心工具。
6. [codeofwhite/awesome-deformable-manipulation](https://github.com/codeofwhite/awesome-deformable-manipulation) ⭐1
   可变形物体操作领域的综述资源，涵盖仿真、任务、sim2real、基准等方向，是操作细分领域的最新知识集合。

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,410
   开源机器人操作系统，当前已落地于300+车型的驾驶辅助场景，是移动机器人运动控制领域规模最大的商业化落地项目。
2. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,688
   开源飞控与无人系统控制框架，支持无人机、无人车、无人船等多类移动机器人，是运动控制领域的标杆性开源项目。
3. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325
   人形与腿式机器人运动控制核心软件，具备动量优化、足式行走等成熟算法，是NASA等人形项目的核心技术底座。
4. [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐275
   ECCV 2026接收的高保真导航仿真器，采用动态高斯泼溅技术，大幅提升导航仿真的真实感与效率。
5. [Open-X-Humanoid/BICMap](https://github.com/Open-X-Humanoid/BICMap) ⭐43
   WebGL-based机器人地图可视化SDK，支持SLAM点云、3D模型、导航路径的展示，是人形机器人导航调试的实用工具。
6. [limxdynamics/humanoid-description](https://github.com/limxdynamics/humanoid-description) ⭐13
   LimX人形机器人的URDF/MJCF/USD模型库，支持ROS、Isaac Sim、MuJoCo等多平台，是国产人形机器人仿真的核心资源。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover) ⭐9,577
   NASA JPL开源的6轮火星车项目，可自行搭建，是航天级移动机器人的开源参考范本，具备极高的工程借鉴价值。
2. [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) ⭐6,668
   开源智能割草机器人项目，基于RTK GPS实现高精度导航，是消费级服务机器人落地的典型代表。
3. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,726
   ICML 2026接收的RoboTwin 2.0官方代码，构建机器人数字孪生系统，为sim2real迁移提供新的技术路径。
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐166
   全身人形遥操作系统，支持人在闭环的数据采集与远程操控，是人形机器人落地的核心配套工具。
5. [FastCrest/tether](https://github.com/FastCrest/tether) ⭐79
   边缘到云的AI部署CLI工具，支持Jetson、RTX、Apple Silicon等多平台，可实现VLA模型的混合推理与快速部署。
6. [physiclaw/PhysiClaw](https://github.com/physiclaw/PhysiClaw) ⭐347
   可在现实世界与用户交互的AI代理项目，探索具身代理在真实场景的落地形态，受到社区广泛关注。
7. [iit-DLSLab/locomanipulation-teleop-isaaclab](https://github.com/iit-DLSLab/locomanipulation-teleop-isaaclab) ⭐22
   基于IsaacLab的移动操作遥操作环境，支持sim2sim与sim2real pipeline，是移动操作研究的实用工具。

---

## 趋势信号分析
今日开源社区的核心趋势集中在**具身智能的轻量化落地与基础设施补全**两大方向。首先，端侧轻量化具身模型首次登上Trending热榜（needle单日新增662星），打破了具身/VLA模型必须依赖高算力GPU的固有认知，呼应了近期人形机器人、边缘机器人对低功耗、本地化推理的迫切需求。其次，人形机器人全栈开源加速，从硬件（openarm）、仿真、训练到部署的工具链持续完善，尤其是国产机器人厂商LimX Dynamics集中开源多个项目，反映产业端正通过开源生态降低研发门槛、加速标准统一。此外，VLA领域的评测、安全等细分工具快速涌现，说明VLA技术已从实验室原型阶段进入商用落地前的基础设施建设期，与近期全球科技企业密集发布人形VLA产品的行业节奏高度匹配。

---

## 社区关注热点
- **边缘端轻量化具身基础模型**（代表项目：[cactus-compute/needle](https://github.com/cactus-compute/needle)）：仅14MB参数即可运行在机器人等边缘设备，无需云端或高性能GPU，为低功耗、高实时性的具身场景提供了新的技术路径，有望成为具身智能落地的关键突破点。
- **人形机器人操作全链路开源工具**（代表项目：[limxdynamics/tron2系列](https://github.com/limxdynamics)、[enactic/openarm](https://github.com/enactic/openarm)）：从硬件设计、仿真模型、训练框架到真机部署的全套开源方案，大幅降低人形操作机器人的研发门槛，呼应国产人形机器人产业化加速的行业趋势。
- **VLA评测与安全工具链**（代表项目：[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)、[provael/provael](https://github.com/provael/provael)）：填补了VLA模型跨硬件平台统一评测、安全红队测试的空白，是VLA技术从实验室走向商用落地的必备基础设施，近期关注度持续上升。
- **具身智能专用操作系统**（代表项目：[syswonder/robonix](https://github.com/syswonder/robonix)、[PhyAgentOS-dev/PhyAgentOS](https://github.com/PhyAgentOS-dev/PhyAgentOS)）：针对具身场景的实时性、多模态融合、Agent调度等特殊需求定制的OS开始涌现，有望替代传统ROS+通用OS的组合，成为具身智能的系统级底座。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*