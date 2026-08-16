# AI 开源趋势日报 2026-08-16

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-08-16 00:36 UTC

---

# 具身智能与机器人开源趋势日报
**日期：2026-08-16**

---

## 今日速览
1. 今日GitHub Trending中，仅14MB的超小基础模型needle闯入热榜，单日新增547星，可直接部署在机器人、可穿戴等微型设备上，边缘端具身智能轻量化模型成为社区新爆点。
2. VLA赛道进入工程化细化阶段，从核心模型实现、学习资源到边缘部署工具、安全红队测试、人类在环训练流水线等上下游项目密集涌现，赛道分工逐步清晰。
3. 人形机器人开源生态加速构建，企业主导的开源项目覆盖硬件模型、仿真、训练、部署全链路，与近期人形机器人产业化加速的行业趋势高度契合。
4. 具身智能底层架构呈现多元路线竞争，数据流驱动的机器人中间件、具身操作系统、无ROS轻量部署框架等新兴方向均有高潜力项目活跃。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,873  
   Rust实现的数据流导向机器人中间件，提供低延迟、可组合的分布式数据流能力，是适配具身AI多模态传感与控制需求的新一代架构代表。
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,561  
   通用多关节接触动力学物理仿真器，是机器人学习、具身智能研究的核心基础设施，社区长期保持高活跃。
3. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,905  
   基于NVIDIA Isaac Sim的统一机器人学习框架，支持仿真训练、sim2real全流程，是当前具身智能研究的主流仿真工具之一。
4. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,589  
   ROS 2官方导航框架与系统，是移动机器人导航领域的事实标准，持续迭代适配新场景。
5. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,304  
   多模态机器人数据可视化、查询与流式处理工具，专为机器人训练与调试优化，大幅提升多模态数据开发效率。
6. [syswonder/robonix](https://github.com/syswonder/robonix) ⭐328  
   Rust编写的具身AI操作系统（EAIOS），面向具身智能场景定制底层系统能力，是具身系统软件的前沿探索。

---

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. [cactus-compute/needle](https://github.com/cactus-compute/needle) ⭐0 (+547 today)  
   14MB超小体积基础模型，可部署在手机、可穿戴、智能家居及机器人等微型设备上，今日登Trending热榜，边缘端具身模型引发社区爆发性关注。
2. [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) ⭐218  
   BridgeVLA与BridgeVLA++官方实现，是VLA领域的代表性模型项目，支撑跨场景机器人操作任务。
3. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐627  
   人形机器人全身控制基础模型，面向通用人形运动控制场景，是人形具身基础模型的核心探索。
4. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐511  
   全中文实战导向的VLA学习/面试手册，聚焦机器人领域特有挑战，是国内开发者进入VLA领域的热门学习资源。
5. [mll-lab-nu/VAGEN](https://github.com/mll-lab-nu/VAGEN) ⭐493  
   基于世界模型推理的强化学习多轮VLM Agent框架，探索世界模型与具身Agent的结合路径。
6. [FastCrest/tether](https://github.com/FastCrest/tether) ⭐79  
   边缘到云端AI部署CLI工具，支持Jetson、RTX、Apple Silicon等多硬件，为VLA模型的边缘部署提供一站式解决方案。

---

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,854  
   完全开源的人形机械臂项目，面向接触富集环境的物理AI研究与部署，是当前开源人形操作硬件的头部项目。
2. [vikashplus/robohive](https://github.com/vikashplus/robohive) ⭐630  
   统一的机器人操作学习框架，提供丰富的操作任务基准与环境，支撑抓取、灵巧操作等方向的研究。
3. [NVlabs/oscar](https://github.com/NVlabs/oscar) ⭐139  
   NVIDIA实验室推出的数据驱动操作空间控制框架，实现自适应、鲁棒的机器人操作性能。
4. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐24  
   LimX TRON2机器人的操作部署项目，基于OpenPI实现pi0.5策略服务与真机客户端，支持快速落地操作任务。
5. [iit-DLSLab/locomanipulation-teleop-isaaclab](https://github.com/iit-DLSLab/locomanipulation-teleop-isaaclab) ⭐22  
   基于IsaacLab的移动操作遥操作环境，支持Unitree Go2+AgileX Piper的sim2sim与sim2real pipeline。
6. [codeofwhite/awesome-deformable-manipulation](https://github.com/codeofwhite/awesome-deformable-manipulation) ⭐1  
   可变形物体操作领域的精选资源库，涵盖仿真器、任务基准、sim2real等方向，是前沿操作研究的一站式资源。

---

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,422  
   开源机器人操作系统，目前已适配300+车型的高级驾驶辅助，是移动机器人运动与导航领域规模最大的开源项目之一。
2. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,307  
   机器人算法Python示例集与教材，覆盖运动规划、定位、SLAM、控制等核心方向，是机器人领域最受欢迎的学习资源。
3. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,692  
   全球最流行的开源无人系统飞控/运动控制框架，支持无人机、无人车、无人船、潜水器等多类移动机器人平台。
4. [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) ⭐5,165  
   开源四足机器人宠物框架，支持波士顿动力式四足机器人开发，广泛应用于STEM教育、研究与DIY场景。
5. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325  
   成熟的腿式机器人运动控制软件栈，提供动量控制、步态规划等核心算法，支持人形、外骨骼、双足等多类平台。
6. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐107  
   清华大学MARS实验室推出的全模态人形运动生成模型，实现通用人形机器人控制，是近期人形运动智能的前沿成果。

---

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,726  
   ICML 2026 RoboTwin 2.0官方代码仓库，探索数字孪生与具身智能的结合，支撑sim2real与机器人远程操控。
2. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,636  
   斯坦福推出的具身AI研究平台，提供1000+日常操作任务基准，是具身智能算法验证的核心平台之一。
3. [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) ⭐6,671  
   开源智能除草机器人项目，基于RTK GPS实现自主导航割草，是具身技术落地消费级场景的典型代表。
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐167  
   全身人形机器人遥操作系统，支持全沉浸式遥操作，是人形机器人数据采集、远程操控的关键工具。
5. [physiclaw/PhysiClaw](https://github.com/physiclaw/PhysiClaw) ⭐348  
   可在真实物理世界与用户交互的AI Agent项目，探索具身Agent的真实世界落地路径。
6. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐46  
   开源双臂同步数据采集与重定向软件，支持适配任意双臂机器人，为模仿学习提供高质量数据采集工具。

---

## 趋势信号分析
今日社区最显著的爆发性方向是**边缘端轻量化具身基础模型**：仅14MB的needle单日新增547星登上Trending热榜，可直接部署在机器人、可穿戴等低算力设备上，反映出行业对具身模型脱离云端、端侧落地的强烈需求，打破了具身AI依赖高端GPU的固有认知。
VLA赛道进入工程化细化阶段，从核心模型、学习资源到边缘部署工具、安全红队测试、人类在环训练流水线等上下游项目密集涌现，标志VLA正从实验室研究向产业落地过渡。
人形机器人开源生态加速构建，LimX等企业主导的项目覆盖硬件、仿真、训练全链路，与近期人形机器人产业化加速的行业趋势高度契合，产业端通过开源构建生态、降低研发门槛的战略意图明确。（全文约280字）

---

## 社区关注热点
- **端侧轻量化具身基础模型（[cactus-compute/needle](https://github.com/cactus-compute/needle)）**：今日Trending最大黑马，14MB超小体积适配机器人、可穿戴等微型设备，为低算力端具身AI落地提供了新路径，边缘具身计算有望成为下一阶段核心热点。
- **VLA全链路工程化工具链**：从核心模型实现（[BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA)）、边缘部署（[FastCrest/tether](https://github.com/FastCrest/tether)）到安全测试（[provael/provael](https://github.com/provael/provael)）的全链路项目密集出现，VLA进入工程化落地前期，相关工具开发需求将快速增长。
- **企业主导的人形机器人开源生态**：以[enactic/openarm](https://github.com/enactic/openarm)、LimX TRON2系列为代表的开源硬件+配套软件栈（仿真、训练、部署）快速完善，产业界通过开源构建生态的趋势明确，开发者可基于开源项目快速切入人形机器人研发。
- **新一代具身底层架构**：[dora-rs/dora](https://github.com/dora-rs/dora)（数据流中间件）、[syswonder/robonix](https://github.com/syswonder/robonix)（具身操作系统）等项目活跃，传统ROS架构在多模态大模型时代的适配性不足问题凸显，新一代底层架构赛道开始升温。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*