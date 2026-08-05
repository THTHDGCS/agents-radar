# AI 开源趋势日报 2026-08-05

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-08-05 01:26 UTC

---

# 具身智能与机器人开源趋势日报（2026-08-05）
---
## 1. 今日速览
今日具身智能与机器人开源领域呈现多个核心动向：一是大模型轻量化推理工具AirLLM以1711颗日增星成为相关领域增幅最高的项目，为70B级VLA模型的端侧部署提供了低成本方案，引发社区对具身AI边缘算力优化的广泛讨论。二是人形机器人全栈生态持续完善，从底层运行时HORUS、全身遥操作系统Teleopit到足球射门专项算法、医院巡逻场景仿真均有新项目更新，覆盖从底层基础软件到上层垂直应用的全链条需求。三是VLA落地工具链快速成熟，评估框架、学习资源、部署中间件的密集发布进一步降低了VLA的开发与落地门槛，推动通用具身智能从实验室研究走向产业原型验证。此外，面向具身Agent的专门化操作系统赛道涌现多个新项目，显示社区对适配VLA架构的底层基础设施需求持续提升。
---
## 2. 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14442
   通用多关节动力学物理仿真器，是机器人学习、具身智能仿真的核心基础设施，社区生态成熟。
2. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63325
   通用机器人操作系统，目前已支持300+车型的高级驾驶辅助升级，是落地规模最大的开源机器人系统之一。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3865
   Rust开发的数据流导向机器人中间件，主打低延迟、可组合、分布式特性，原生适配AI机器人应用开发。
4. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7834
   基于NVIDIA Isaac Sim的统一机器人学习框架，支持GPU并行仿真，是VLA训练与部署的主流工具链。
5. [softmata/horus](https://github.com/softmata/horus) ⭐405
   Rust开发的高性能机器人运行时，定位为“机器人的Android”，为各类人形、足式机器人提供统一的底层运行环境，今日获得社区重点关注。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐127
   无ROS依赖的sim2real框架，原生支持VLA模型与RL代理部署，兼容Franka、UR5e等主流机械臂，降低真机部署门槛。
---
### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. [lyogavin/airllm](https://github.com/lyogavin/airllm) ⭐总量未标注，今日新增+1711
   大模型轻量化推理工具，支持单4GB GPU运行70B参数模型，是今日Trending榜增幅最高的AI基础设施项目，为端侧VLA部署提供核心支撑。
2. [TianxingChen/Embodied-AI-Guide](https://github.com/TianxingChen/Embodied-AI-Guide) ⭐15241
   Lumina具身智能社区出品的全栈具身智能技术指南，star量破1.5万，是国内最受欢迎的具身入门资源。
3. [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐1965
   NVIDIA开源的10B参数推理型VLA模型，面向自动驾驶场景，支持因果链推理，配套完整的开发工具链。
4. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4424
   面向具身与Agent AI的强化学习基础设施，为VLA模型的训练、评估、部署提供统一的RL底层支撑。
5. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐469
   国内首份全中文、实战导向的VLA领域学习/面试手册，聚焦机器人场景特有的技术挑战，适合算法工程师入门。
6. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐127
   开源物理AI评估工具，支持任意LLM/VLA模型在任意仿真/真机机器人上的基准测试，解决VLA效果评估缺乏统一标准的痛点。
---
### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐345
   机器人操作领域的官方基准仓库，覆盖多类通用操作任务，是VLA操作能力评估的主流数据集。
2. [worldbench/awesome-embodied-data-pyramid](https://github.com/worldbench/awesome-embodied-data-pyramid) ⭐130
   具身操作数据金字塔综述，系统梳理了当前具身操作领域的数据分层、采集方法与发展趋势。
3. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐98
   创新的技能图框架，可将自然语言指令编译为可验证的机器人技能图，直接在仿真或真机上执行。
4. [api-evangelist/origami-robotics](https://github.com/api-evangelist/origami-robotics) ⭐0
   YC 2026孵化的机器人创业公司，主打面向机器学习优化的通用灵巧手，是近期操作硬件领域的新兴项目。
5. [zcy13/cofree-arm](https://github.com/zcy13/cofree-arm) ⭐0
   零训练的桌面机械臂操作方案，采用“多模态管语义+几何管数值”的架构，单次任务成本仅0.2元，探索低成本具身落地路径。
6. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐44
   开源双臂数据采集与重定向软件，支持将人类演示数据适配到任意双臂机器人，降低VLA模仿学习的数据采集门槛。
---
### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐148
   全具身人形机器人遥操作系统，支持全身动作捕捉与实时控制，是人形机器人远程操作的核心工具。
2. [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) ⭐38
   论文《RoboNaldo: Accurate, Stable and Powerful Humanoid Soccer Shooting》的官方代码，实现了人形机器人的高精度足球射门，是人形专项运动能力的代表性成果。
3. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4551
   ROS 2生态的官方导航框架，支持SLAM、路径规划、避障等核心功能，是移动机器人导航的主流开源方案。
4. [NJU-RLC/quadrupedal-agility](https://github.com/NJU-RLC/quadrupedal-agility) ⭐123
   南京大学智能计算与学习实验室的四足机器人敏捷行为学习算法官方实现，提升四足机器人的运动灵活性。
5. [Renkunzhao/legged-daily](https://github.com/Renkunzhao/legged-daily) ⭐21
   面向足式机器人领域的活知识库，每日更新代码、论文与资源，覆盖基于模型与学习的控制方法。
6. [KaushikSiva/baymax](https://github.com/KaushikSiva/baymax) ⭐0
   基于宇树G1人形机器人的医院巡逻仿真系统，支持自主导航、患者语音交互、跌倒检测等功能，是人形垂直场景落地的探索项目。
---
### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2999
   面向Python基础开发者的具身智能入门教程，从0到1讲解VLA/OpenVLA/SmolVLA的构建，是国内最受欢迎的具身实战课程。
2. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1544
   自进化具身AI操作系统，基于Agent工作流构建，支持具身Agent的技能进化、物理记忆与自主决策。
3. [syswonder/robonix](https://github.com/syswonder/robonix) ⭐276
   Rust开发的具身AI操作系统（EAIOS），主打安全、高性能，适配各类机器人硬件平台。
4. [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐244
   大模型物理具身的最小软硬件架构，实现了大模型的闭环物理交互与自感知环，适合开发者快速验证具身Agent原型。
5. [shritankomm/7-DOF-3DP-Open-Arm](https://github.com/shritankomm/7-DOF-3DP-Open-Arm) ⭐1
   开源7自由度3D打印人形机械臂，支持ROS2、视觉与自主控制，总成本低于800美元，大幅降低人形硬件的入门门槛。
6. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐51
   机器人辅助化学实验室自动化的数字孪生平台，探索具身智能在科研自动化场景的落地应用。
---
## 3. 趋势信号分析
今日数据显示，**大模型轻量化推理与VLA落地工具链**正在获得社区爆发性关注，AirLLM的超高日增星数反映了开发者对数十亿参数级VLA模型在边缘机器人设备上部署的强烈需求，解决了当前具身智能落地的核心算力痛点。新兴方向方面，原生适配Agent架构的具身AI操作系统（如PhyAgentOS、RoboNix）首次集中登榜，区别于传统ROS框架的任务导向设计，这类系统原生支持自进化工作流、物理记忆与多模态调度，更适配VLA时代的机器人开发需求。这一趋势与近期人形机器人厂商纷纷布局端侧大模型、通用具身智能加速从实验室走向消费级的行业节奏高度契合，底层基础设施的完善将进一步加速VLA的真机落地进程。
---
## 4. 社区关注热点
- 关注大模型轻量化推理工具[lyogavin/airllm](https://github.com/lyogavin/airllm)：支持单4GB GPU运行70B参数模型，可直接用于端侧VLA部署，大幅降低具身智能的硬件门槛，是今日社区关注度最高的基础设施项目。
- 关注具身AI原生操作系统赛道：今日有PhyAgentOS、RoboNix等多个项目集中亮相，区别于传统ROS框架，这类系统原生支持VLA与Agent工作流，有望成为下一代机器人的底层标准。
- 关注人形机器人全栈开源生态：从底层运行时HORUS、低成本7DOF机械臂到全身遥操作系统Teleopit，今日覆盖全栈的人形开源项目密集发布，适合开发者快速搭建人形机器人原型。
- 关注VLA评估工具[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)：支持任意VLA/LLM模型在任意仿真/真机上的基准测试，解决了当前VLA效果评估缺乏统一工具的核心痛点，是VLA落地的必备工具。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*