# AI 开源趋势日报 2026-07-19

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-19 01:26 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-19）

---

## 今日速览
今日具身智能与机器人开源领域最大热点为新发布的3D场景重建基础模型lingbot-map，单日新增831星登顶技术热榜，具身感知基础模型成为社区新宠。VLA生态进一步完善，从入门教程、小型化模型到评估测试工具全链路均有新项目推出，技术落地门槛持续降低。人形机器人开源生态覆盖硬件、控制、仿真全栈，低成本开源方案加速技术普惠。同时，具身智能的中间件、仿真底座等基础设施持续迭代，为上层应用研发提供核心支撑。

---

## 各维度热门项目

### 🤖 机器人框架/SDK
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,843：Rust编写的数据流导向机器人中间件，支持低延迟、可组合的分布式机器人应用构建，是当前最受关注的新一代机器人操作系统候选方案。
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,700：基于NVIDIA Isaac Sim的统一机器人学习框架，是当前VLA和人形机器人策略训练的主流仿真底座，生态完善且更新频繁。
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,254：业界通用的多关节接触物理仿真引擎，是机器人Sim2Real研发的核心基础设施，近期持续优化GPU加速能力。
- [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,160：面向机器人的通用操作系统，当前已落地于300+车型的驾驶辅助系统，是具身智能落地大规模场景的标杆项目。
- [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124：无ROS依赖的轻量Sim2Real框架，原生支持VLA和RL策略的训练与部署，适配主流机械臂与人形机器人，大幅降低落地部署门槛。
- [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐738：基于代理工作流的自进化具身AI操作系统，支持多模态感知与决策的模块化组合，是具身智能系统级方案的前沿探索。

### 🧠 VLA/基础模型
- [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map) ⭐0（今日+831）：全新发布的前馈式3D基础模型，可从流式传感器数据中实时重建3D场景，是具身智能动态环境感知的核心技术，单日星量暴涨为今日最大热点。
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,737：国内热门的具身智能入门教程，仅需Python基础即可从零搭建VLA/OpenVLA等模型，是新手入局的首选学习资源。
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐403：国内首份全中文VLA实战与面试手册，聚焦机器人领域特有的技术挑战，填补了中文VLA专业资源的空白。
- [Open-X-Humanoid/XR-1](https://github.com/Open-X-Humanoid/XR-1) ⭐186：面向通用具身智能的VLA模型，通过学习统一的视觉-运动表示实现多场景的机器人控制，是VLA技术的前沿探索。
- [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) ⭐7：极简可解释的小型VLA模型，冻结CLIP+轻量头部即可在无GPU的Mac设备上运行，大幅降低了VLA的研发与测试门槛。
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐7：专为VLA和物理AI模型设计的评估框架，支持一次定义基准、跨机器人/仿真运行策略，是VLA性能验证的核心工具。

### 🦾 操作与抓取
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,738：全开源的人形机械臂，专为接触富集场景的物理AI研究设计，是目前少有的可直接用于落地实验的开源人形臂方案。
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐506：上海AI实验室推出的操作类VLA模型，统一了机器人操作的理解、生成与动作能力，是国内操作VLA的代表性工作。
- [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐260：通用机器人操作基准数据集与评估平台，可标准化验证VLA模型的操作能力，是操作方向研发的必备工具。
- [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐76：可将自然语言指令编译为类型安全的机器人技能图的框架，解决了VLA长程操作的可靠性问题，是提升操作任务成功率的前沿方案。
- [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) ⭐38：双向对齐的长程操作具身代理框架，支持复杂场景下的连续操作任务，适配主流操作机器人。

### 🚶 运动与导航
- [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐819：面向足式机器人的直接IsaacLab工作流，大幅简化足式机器人的策略训练与部署流程，是足式机器人研发的热门工具。
- [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐585：面向人形机器人全身控制的基础模型，可实现复杂场景下的全身运动规划，是人形运动控制的前沿研究成果。
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐258：UMI-3D SLAM与数据处理管线，支持具身场景下的高精度实时建图，是动态场景感知的核心工具。
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐132：轻量可扩展的人形全身遥操作框架，支持低成本的人形机器人数据采集与控制，适合小规模团队使用。
- [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐28：低成本全3D打印的开源人形机器人，基于树莓派Zero 2W，是个人开发者入门人形机器人的高性价比平台。

### 📦 具身应用
- [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3,413：开源AI助手生态，支持MCP集成、多模态工作流、IoT控制与跨平台语音交互，是具身智能落地消费级场景的代表性项目。
- [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,599：官方开源的机器人数字孪生平台2.0，支持高保真的Sim2Real验证，是机器人落地前测试的核心工具。
- [strands-labs/robots](https://github.com/strands-labs/robots) ⭐102：通过自然语言控制机器人与物理硬件的代理框架，无需专业机器人知识即可完成任务指令下发，降低了机器人的使用门槛。
- [FastCrest/tether](https://github.com/FastCrest/tether) ⭐73：面向AI模型的边云部署CLI工具，支持VLA等模型在Jetson、RTX、苹果硅等硬件上的一键部署，是具身模型落地的核心工具链组件。

---

## 趋势信号分析
今日开源生态呈现三大核心趋势：一是具身感知基础模型获得爆发性关注，新发布的lingbot-map单日新增831星，3D流式场景重建作为VLA和人形机器人的核心感知底座，正在成为社区研发的新热点，对应近期产业界对具身智能动态环境感知能力的迫切需求。二是VLA技术平民化进程加速，从入门教程、新手项目模板到可在消费级硬件运行的小型VLA密集出现，大幅降低了开发者入局门槛。三是VLA的可靠性验证工具开始涌现，评估框架、红队测试等周边生态逐步完善，标志着VLA正从实验室原型走向落地前的可靠性验证阶段，与人形机器人产业试点加速的行业节奏高度契合。

---

## 社区关注热点
- 重点关注 [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map)：单日新增831星的黑马项目，前馈式3D流重建基础模型可大幅提升具身机器人的动态场景感知效率，有望成为下一代具身感知的核心组件。
- 优先学习 [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)、[VLA-Handbook](https://github.com/sou350121/VLA-Handbook)：国内稀缺的体系化具身智能/VLA中文学习资源，仅需Python基础即可从零搭建VLA模型，适合新手快速入局。
- 跟踪开源人形硬件生态：[enactic/openarm](https://github.com/enactic/openarm)、[MarcDcls/microban](https://github.com/MarcDcls/microban)等低成本全开源人形硬件项目，可大幅降低人形机器人的研发门槛，是个人开发者和小型团队入局的绝佳切入点。
- 布局VLA落地工具链：[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)、[provael/provael](https://github.com/provael/provael)等VLA评估、红队测试工具，是VLA落地前的核心刚需，未来将成为具身智能研发的必备基础设施。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*