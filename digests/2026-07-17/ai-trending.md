# AI 开源趋势日报 2026-07-17

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-17 01:29 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-17）
---
## 今日速览
1. 今日GitHub实时热榜以通用AI Agent、编码工具为主，具身智能与机器人领域的核心热度集中在7天活跃的主题仓库中，整体呈现「基础工具链快速补全、落地导向增强」的特征。
2. 人形机器人全栈开源生态加速成型，从上层控制基础模型、中间件运行时到DIY硬件的全链路项目均有更新，大幅降低了人形研发的准入门槛。
3. VLA（视觉-语言-动作）领域出现明显的普惠化趋势，面向新手的入门教程、极简实现、中文学习资源集中涌现，同时评估、安全测试、部署等落地配套工具首次批量登榜。
4. 具身智能的研发重心正在从模型原型向落地验证转移，sim2real部署框架、跨硬件适配工具、场景化基准的关注度持续提升。
---
## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. [commaai/openpilot](https://github.com/commaai/openpilot) | ⭐ 63,141 | 面向机器人的通用操作系统，当前已支持300+款车型的辅助驾驶升级，是落地规模最大的开源机器人OS项目。
2. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) | ⭐ 30,059 | 机器人算法的经典Python示例集与教材，覆盖导航、控制、感知等全领域，是机器人开发者的入门必看资源。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) | ⭐ 14,236 | 通用多关节动力学物理仿真器，是机器人学习、人形控制领域的事实标准仿真工具。
4. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) | ⭐ 7,691 | 基于NVIDIA Isaac Sim的统一机器人学习框架，已成为人形、足式机器人仿真训练的首选工具链。
5. [dora-rs/dora](https://github.com/dora-rs/dora) | ⭐ 3,845 | 数据流导向的机器人中间件，低延迟、可组合的特性专门适配AI机器人的开发需求，逐步成为ROS之外的新兴选择。
6. [softmata/horus](https://github.com/softmata/horus) | ⭐ 389 | Rust编写的高性能机器人运行时，定位为「机器人的Android」，针对人形实时控制场景优化，是基础软件方向的潜力项目。

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) | ⭐ 2,711 | 面向Python基础开发者的具身智能入门教程，从0到1实现VLA/OpenVLA/SmolVLA等模型，是国内普惠化具身教育的标杆项目。
2. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) | ⭐ 579 | 面向人形全身控制的基础模型，实现了统一的人形运动与操控策略生成，是基础模型落地人形控制的代表性成果。
3. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) | ⭐ 395 | 国内首份全中文、实战导向的VLA学习/面试手册，聚焦机器人领域特有挑战，填补了中文VLA系统化学习资源的空白。
4. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) | ⭐ 498 | 面向机器人操控的VLA系列，统一了理解、生成、动作三大能力，适配工业与家用机器人的操控场景。
5. [Open-X-Humanoid/XR-1](https://github.com/Open-X-Humanoid/XR-1) | ⭐ 186 | 通过学习统一视觉-运动表示实现的通用VLA模型，支持人形、机械臂等多类机器人的跨场景任务。
6. [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) | ⭐ 7 | 极简可运行的VLA实现，仅依赖冻结CLIP与小型输出头，支持Mac无GPU运行，大幅降低了VLA的上手门槛。
7. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) | ⭐ 6 | 对标Inspect AI的VLA专用评估框架，支持一次定义基准、跨机器人/仿真运行，解决了当前VLA评估标准不统一的痛点。

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) | ⭐ 2,729 | 全开源人形机械臂，专门针对接触富集环境的物理AI研究与落地设计，是当前少数可直接适配VLA模型的开源硬件方案。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) | ⭐ 249 | 机器人操控通用基准，覆盖家用、工业等多场景操控任务，支持VLA模型的统一评测。
3. [RoboTwin-Platform/RMBench](https://github.com/RoboTwin-Platform/RMBench) | ⭐ 168 | 基于数字孪生的记忆依赖操控基准，针对长程、复杂操控任务设计，填补了现有VLA基准的场景空白。
4. [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) | ⭐ 62 | RSS 2026收录的VLA工作，通过通用姿态预训练实现了强泛化性的操控策略，在跨机器人、跨场景任务上表现优异。
5. [chang-xinhai/Awesome-Dexterous-Manipulation](https://github.com/chang-xinhai/Awesome-Dexterous-Manipulation) | ⭐ 11 | 灵巧操控方向的精选资源列表，覆盖触觉传感、灵巧手、数据集等全链条内容，适合研究者快速梳理领域进展。

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) | ⭐ 4,475 | ROS2生态的官方导航框架，支持路径规划、避障、定位等全链路导航能力，是移动机器人导航的事实标准。
2. [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) | ⭐ 816 | 面向足式机器人的直接IsaacLab工作流，简化了足式机器人从仿真到实机的开发流程，是足式研发的热门工具。
3. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) | ⭐ 132 | 轻量可扩展的人形全身遥操作框架，支持低成本动捕设备接入，大幅降低了人形遥操作数据采集的门槛。
4. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) | ⭐ 257 | UMI-3D SLAM与数据处理管线，支持动态环境下的高精度机器人定位与建图，适配具身智能的复杂导航需求。
5. [MarcDcls/microban](https://github.com/MarcDcls/microban) | ⭐ 23 | 低成本全3D打印的开源DIY人形机器人，基于树莓派Zero 2W开发，适合个人爱好者与教学场景使用。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) | ⭐ 2,592 | 开源机器人数字孪生平台，支持高保真仿真、实机同步与操控验证，是具身智能sim2real落地的核心基础设施。
2. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) | ⭐ 664 | 自进化具身AI操作系统，基于Agent工作流实现机器人的自主任务规划与执行，面向家用与服务机器人场景。
3. [FastCrest/tether](https://github.com/FastCrest/tether) | ⭐ 73 | 开源边缘到云端的AI部署CLI，支持Jetson、RTX、Apple Silicon等主流硬件，适配VLA模型的边缘部署需求。
4. [EmbodiChain/EmbodiChain](https://github.com/DexForce/EmbodiChain) | ⭐ 193 | 端到端GPU加速的模块化具身智能构建平台，支持快速搭建从感知到执行的全链路机器人系统。
5. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) | ⭐ 92 | 清华大学MARS实验室开源的全模态人形运动生成模型，支持文本、视觉等多模态输入生成人形全身运动。
---
## 趋势信号分析
今日社区热度呈现两大核心趋势：一是人形机器人全栈开源生态加速成型，从上层控制基础模型（HoloMotion）、中间件运行时（Horus）到DIY硬件（Microban）的全链路项目同步迭代，尤其Open-X-Humanoid等组织推出的成套工具链，打破了此前人形研发依赖闭源硬件、工具碎片化的瓶颈，与近期国内人形机器人量产试点、产业资本入场的行业节奏高度契合。二是VLA领域从「模型研发」向「落地配套」转移，面向新手的入门资源、极简实现批量出现，同时评估框架、安全红队、部署工具等此前的薄弱环节快速补全，反映社区正在为VLA在工业、服务机器人上的规模化落地做基础设施准备，整体从Demo验证走向产业落地的信号明确。
---
## 社区关注热点
- 🎯 全开源人形机械臂 [enactic/openarm](https://github.com/enactic/openarm)：2.7k星的高人气开源硬件，专门针对接触富集的物理AI场景设计，可直接适配现有VLA模型，适合研究者与创业团队快速原型验证，填补了开源人形机械臂的市场空白。
- 🎯 中文VLA学习手册 [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook)：国内首份实战导向的VLA全中文学习/面试手册，聚焦机器人领域的特有挑战，适合算法工程师快速入门，解决了中文VLA学习资源零散的痛点。
- 🎯 高性能机器人运行时 [softmata/horus](https://github.com/softmata/horus)：Rust编写的低延迟机器人运行时，定位为「机器人的Android」，针对人形实时控制场景优化，是机器人基础软件方向的新兴潜力项目，有望替代传统臃肿的机器人中间件。
- 🎯 VLA通用评估框架 [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)：对标Inspect AI的机器人专用评估工具，支持一次定义基准、跨机器人/仿真运行，解决了当前VLA评估标准不统一、评测效率低的核心痛点。
- 🎯 极简VLA实现 [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA)：仅需Mac即可运行的无GPU VLA实现，代码极简易读，适合新手快速理解VLA的核心逻辑，大幅降低了VLA领域的准入门槛。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*