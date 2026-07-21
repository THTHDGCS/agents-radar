# AI 开源趋势日报 2026-07-21

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-21 01:26 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-21）

---

## 今日速览
今日具身智能开源社区的核心热度集中在VLA落地工具链、人形机器人全栈开源、仿真基础设施三大方向，其中零基础具身实战项目、中文VLA学习资源获得国内开发者广泛关注。低参数轻量型VLA模型首次出现在IROS 2026顶会开源序列，Mamba架构在机器人动作序列建模中的应用开始落地验证。全栈开源人形硬件、机器人专用runtime系统的热度持续上升，社区对具身智能从算法到硬件的可复现性需求显著提升。VLA模型的评估、微调方法论相关项目快速增长，标志着VLA从原型开发进入性能优化的规模化落地阶段。

---

## 各维度热门项目
### 🤖 机器人框架/SDK
1. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,848
   基于Rust实现的数据流向开源机器人中间件，提供低延迟、可组合的分布式数据流能力，将机器人应用抽象为有向图pipeline，是当前替代ROS的轻量方案中社区活跃度最高的项目之一。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,715
   基于NVIDIA Isaac Sim的统一机器人学习框架，原生支持强化学习、模仿学习、VLA训练，近期新增足式机器人工作流适配，是人形机器人仿真训练的首选工具。
3. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,182
   面向具身智能与代理AI的强化学习基础设施，封装了从数据采集、训练到部署的全流程，大幅降低具身RL算法的落地门槛。
4. [softmata/horus](https://github.com/softmata/horus) ⭐391
   号称“机器人界Android”的高性能runtime系统，基于Rust开发，针对机器人低延迟、高并发的控制需求设计，是新兴机器人操作系统方向的代表性项目。
5. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,267
   行业通用的多关节物理仿真器，近期新增GPU加速的接触求解优化，是VLA、机器人学习项目的标准仿真底座。

### 🧠 VLA/基础模型
1. [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map) ⭐0（今日新增+565，今日Trending）
   前馈式3D场景重建基础模型，支持从流式传感器数据实时重建环境，是具身智能感知模块的核心技术，为今日Trending榜单中唯一的具身相关高增长项目。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,770
   面向Python基础开发者的零基础具身智能实战项目，覆盖从VLA/OpenVLA/SmolVLA复现到实体机器人搭建的全流程，是国内入门具身领域的首选实战资源。
3. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐410
   国内首份全中文VLA领域实战/面试手册，聚焦机器人领域特有的感知、规划、动作对齐挑战，填补了中文VLA系统化学习资源的空白。
4. [Open-X-Humanoid/XR-1](https://github.com/Open-X-Humanoid/XR-1) ⭐186
   开源通用VLA模型，通过学习统一的视觉-运动表征实现多任务机器人控制，是当前人形机器人VLA方向的代表性开源实现。
5. [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐5
   IROS 2026收录的轻量型VLA模型，基于Mamba架构仅179M参数即可实现机器人操作任务，标志着小参数VLA的落地可行性得到顶会验证。
6. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐10
   通用VLA/物理AI模型评估框架，支持一次定义基准即可在任意机器人、仿真环境中运行不同策略，解决了当前VLA评估碎片化的痛点。

### 🦾 操作与抓取
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,742
   全开源人形机械臂，针对接触富集的物理AI研究与部署设计，提供从硬件设计到控制算法的全栈方案，是当前开源操作硬件中热度最高的项目。
2. [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) ⭐38
   双向对齐的具身代理框架，专门面向长horizon机器人操作任务，解决了传统VLA在长流程任务中容易累计误差失效的问题。
3. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐79
   可验证的机器人技能图编译框架，将自然语言指令转换为类型安全的操作流程，可直接在仿真或真实机器人上执行，大幅提升VLA落地的可靠性。
4. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐28
   开源双手操作数据采集与重定向工具，支持将人类演示数据同步重定向到任意双臂机器人，大幅降低灵巧操作的训练数据采集成本。

### 🚶 运动与导航
1. [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐819
   面向足式机器人的直接IsaacLab工作流，简化了足式机器人从仿真训练到真实部署的流程，是人形机器人运动控制的核心开发工具。
2. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐588
   全身人形控制基础模型，支持统一生成人形机器人的行走、操作等全身运动，是当前人形机器人通用运动控制的代表性成果。
3. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐132
   轻量可扩展的人形全身遥操作框架，支持低成本动捕设备实现人形机器人的全身体感控制，降低了人形机器人演示数据的采集门槛。
4. [MichaelGrupp/evo](https://github.com/MichaelGrupp/evo) ⭐4,282
   行业通用的SLAM与里程计评估工具，支持多种SLAM算法的精度评估与可视化，是机器人导航模块开发的必备工具。

### 📦 具身应用
1. [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3,415
   开源具身AI助手生态，原生支持MCP协议、多模态交互、IoT设备控制，可直接对接家用机器人、智能硬件，是国内落地性最强的具身应用项目之一。
2. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124
   无ROS依赖的sim2real部署框架，原生支持VLA与RL模型的端到端部署，适配Franka、UR5e、xArm等主流工业机械臂，解决了VLA落地的ROS依赖痛点。
3. [iit-DLSLab/locomanipulation-teleop-isaaclab](https://github.com/iit-DLSLab/locomanipulation-teleop-isaaclab) ⭐21
   Unitree Go2四足机器人+AgileX Piper机械臂的遥操作仿真环境，支持sim2sim与sim2real pipeline，是移动操作机器人开发的快速原型工具。
4. [Rhoban/microban](https://github.com/Rhoban/microban) ⭐29
   全3D打印的低成本开源人形机器人，仅需树莓派Zero 2W即可驱动，是具身智能入门、DIY实验的高性价比硬件平台。

---

## 趋势信号分析
今日数据显示，VLA落地工具链与全栈开源人形机器人是具身领域最核心的增长方向：一方面，从VLA中文学习手册、微调方法到标准化评估框架的全链路项目密集出现，标志着VLA技术已走出实验室原型，进入规模化落地的性能优化与标准化阶段；另一方面，全开源人形硬件、机器人专用runtime系统的热度持续上升，反映社区对具身智能“算法-硬件-部署”全链路可复现性的需求爆发。新兴技术方面，基于Mamba架构的179M参数轻量VLA首次进入IROS 2026顶会开源序列，小参数VLA的落地可行性得到官方验证，未来将大幅降低VLA在边缘机器人上的部署门槛。这一趋势与近期OpenVLA、Pi0等通用VLA模型开源，以及特斯拉Optimus、Figure 01等人形机器人的商业化进展直接相关，产业端的落地节奏正在反向推动开源社区的工具链完善。（全文约290字）

---

## 社区关注热点
- 零基础具身智能实战项目 [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)：覆盖OpenVLA、SmolVLA等主流模型的复现与实体机器人部署，无需高深的机器人或AI基础即可上手，填补了中文具身入门实战资源的空白。
- 中文VLA学习面试手册 [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook)：聚焦机器人领域特有的VLA技术挑战，覆盖算法原理、实战开发、面试考点全场景，是转入VLA方向开发者的首选学习资源。
- 轻量VLA模型 [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026)：IROS 2026收录的Mamba架构小参数VLA，仅179M参数即可完成机器人操作任务，适合在边缘机器人、低算力设备上部署VLA能力。
- 机器人专用runtime [softmata/horus](https://github.com/softmata/horus)：针对机器人低延迟控制需求设计的高性能runtime，是替代ROS的新兴轻量方案，代表了下一代机器人操作系统的发展方向。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*