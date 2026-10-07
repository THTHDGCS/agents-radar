# AI 开源趋势日报 2026-10-07

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-10-07 03:07 UTC

---

# 具身智能与机器人开源趋势日报（2026-10-07）

---

## 今日速览
1. 今日GitHub全站Trending中，唯一入选的机器人领域项目是面向AI Agent的CAD生成工具[earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)，单日新增619星，反映出具身智能与物理设计工具融合的需求正在快速爆发。
2. 人形机器人开源生态持续向细分化发展，从底层执行器选型、运动控制、动作模仿到全身VLA控制的全链路项目密集更新，宇树系列消费级人形平台成为第三方开发者的核心载体。
3. VLA领域工具链逐步完善，世界动作模型（WAM）作为新兴技术方向首次出现系统性开源框架，标志着具身基础模型正从“指令跟随”向“世界建模+动作预测”的阶段升级。
4. 机器人操作与评估的标准化进程加快，sim2real框架、双臂操作基准等项目的社区关注度持续上升，进一步降低了具身智能算法的落地门槛。

---

## 各维度热门项目

### 🤖 机器人框架/SDK（控制、仿真、规划、运动）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,493
   机器人领域应用最广的通用物理仿真器，是几乎所有具身智能、机器人学习项目的底层依赖，长期占据机器人基础设施核心地位。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,289
   NVIDIA官方的机器人学习统一框架，支持多物理引擎/渲染器，是当前sim2real、VLA训练的主流仿真平台，社区活跃度极高。
3. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐16,005
   全球最流行的开源无人机/无人车/水下机器人飞控系统，支持多类型移动机器人的运动控制与导航，是移动机器人领域的事实标准。
4. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,993
   Rust开发的数据流导向机器人中间件，低延迟、可组合、分布式特性，为AI原生机器人应用提供了ROS之外的轻量替代方案。
5. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,551
   多模态机器人数据可视化与流式处理工具，支持视觉、点云、动作等多种数据的实时查看与标注，是具身智能开发的必备调试工具。
6. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,726
   基于NVIDIA Warp的GPU加速物理仿真引擎，专门面向机器人与仿真研究者，在并行仿真效率上相比传统引擎有显著优势。
7. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐163
   无ROS依赖的轻量sim2real框架，原生支持Franka、UR5e等多型号机械臂与VLA/RL策略部署，大幅降低机器人学习的落地门槛。
8. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,636
   机器人算法经典Python教科书，覆盖路径规划、SLAM、控制等全栈知识点，是机器人领域入门与参考的核心开源资源。

### 🧠 VLA/基础模型（视觉-语言-动作、强化学习、世界模型）
1. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐5,446
   面向具身智能与Agent AI的强化学习基础设施，为RL模型的训练、部署提供了统一的底层框架，是具身学习领域的核心基础设施项目。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,930
   面向Python基础开发者的具身智能入门教程，从0逐步构建VLA/OpenVLA/SmolVLA/Pi0，是国内最受欢迎的具身智能实战资源。
3. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐2,206
   面向通用具身智能的开放世界基础模型，是当前开源界少有的端到端具身大模型项目，代表了具身基础模型的发展方向。
4. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐644
   开源物理AI评估工具，支持任意LLM/VLA在任意机械臂/人形机器人的仿真/实机基准上运行，解决了VLA评估标准不统一的痛点。
5. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐676
   全中文VLA领域实战/面试手册，聚焦机器人特有挑战，是国内算法工程师进入具身智能领域的核心参考资料。
6. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐399
   世界动作模型（WAM）的统一训练、微调、评估框架，填补了WAM开发工具链的空白，标志着动作模型进入工程化落地阶段。
7. [black-forest-labs/flux-action](https://github.com/black-forest-labs/flux-action) ⭐138
   黑森林实验室开源的7B参数世界动作模型，支持机器人（DROID、SO-101）、仿真器、游戏多场景动作预测，是近期VLA领域的重磅开源项目。
8. [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐266
   NVIDIA开源的34B参数多任务基础模型，面向自动驾驶场景，是VLA技术在自动驾驶领域落地的代表性项目。

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐3,579
   全开源人形机械臂平台，面向物理AI研究与接触富集场景部署，填补了开源人形上肢硬件的空白，是操作类VLA与运动控制研究的核心硬件载体。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐675
   统一仿真与实机的通用机器人操作策略评估基准，覆盖多类接触富集任务，是操作类VLA与RL模型的标准化测试平台。
3. [XPolicyLab/XPolicyLab](https://github.com/XPolicyLab/XPolicyLab) ⭐395
   收录50+高级机器人操作策略的工具库，获IROS 2026 ScaleInfra Workshop最佳工具论文，为操作算法开发提供了开箱即用的基线集合。
4. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐75
   开源双臂同步数据采集与重定向软件，支持校准、质量检测、回放、遥操作全流程，是双臂操作数据采集与模仿学习的关键工具。
5. [RunpeiDong/HERO](https://github.com/RunpeiDong/HERO) ⭐10
   CoRL 2026最新研究成果，实现人形机器人末端的视觉全身开放词汇抓取控制，是人形操作领域的前沿技术探索。
6. [graph-robots/open-robot-skills](https://github.com/graph-robots/open-robot-skills) ⭐49
   基于图策略的机器人操作技能库，兼容Anthropic Agent Skills格式，为具身Agent的操作能力复用提供了标准化方案。
7. [RobotControlStack/duobench](https://github.com/RobotControlStack/duobench) ⭐21
   可复现的双臂操作基准，同时支持仿真与实机测试，填补了双臂操作标准化评估的空白。

### 🚶 运动与导航（足式机器人、人形机器人、路径规划）
1. [RealXiaoze/humanoid-motion-intelligence](https://github.com/RealXiaoze/humanoid-motion-intelligence) ⭐617
   人形机器人运动智能知识库，收录论文、开源项目、产业动态与求职信息，是国内开发者了解人形机器人运动领域的核心导航资源。
2. [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐380
   人形机器人全身非线性模型预测控制（MPC）框架，支持实时 loco-manipulation 规划与控制，是人形运动控制的主流技术方案。
3. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325
   全球知名的腿式机器人运动控制软件栈，支持人形、双足、外骨骼等多类机器人的运动规划与控制，是人形运动控制的经典开源项目。
4. [alertform/g1-motion-imitation](https://github.com/alertform/g1-motion-imitation) ⭐0
   宇树G1人形机器人动作模仿项目，实现从人体动捕到PPO训练的全流程，单张RTX 4060即可运行4096并行仿真环境，大幅降低人形运动训练门槛。
5. [kedianwen/LDRQ](https://github.com/kedianwen/LDRQ) ⭐2
   宇树R1人形机器人非对称PPO步行策略项目，实现从Isaac Lab到Jetson Orin NX的全链路sim2real部署，支持本地LLM指令控制。
6. [DeRuiChen258/Unitree_Low-Level_Balance](https://github.com/DeRuiChen258/Unitree_Low-Level_Balance) ⭐1
   宇树G1人形机器人小脑平衡与多动作自适应系统，支持弯腰拾取、避障等复杂任务，是人形底层运动控制的前沿开源实践。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) ⭐18,037 (+619 today)
   今日Trending热门项目，为AI Agent赋予原生CAD生成能力，打通了具身智能从“设计”到“制造”的上游环节，反映出Agent与物理工具融合的爆发性需求。
2. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,835
   全球最受欢迎的开源自动驾驶/机器人操作系统，支持300+车型的辅助驾驶升级，是VLA技术在移动机器人领域落地的最大规模开源项目。
3. [Adam-CAD/CADAM](https://github.com/Adam-CAD/CADAM) ⭐5,213
   开源text-to-CAD Web应用，与text-to-cad项目形成工具矩阵，为机器人硬件设计、具身Agent物理建模提供了低代码方案。
4. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐62
   面向化学实验室自动化的机器人数字孪生平台，是具身智能在科学自动化场景落地的代表性项目。
5. [pradeepsuryad/Xr_quest2_Unitree](https://github.com/pradeepsuryad/Xr_quest2_Unitree) ⭐1
   基于Meta Quest 2 VR头显的宇树G1人形机器人遥操作方案，为人形机器人的远程控制与数据采集提供了低成本消费级方案。
6. [FastCrest/tether](https://github.com/FastCrest/tether) ⭐85
   边缘-云协同的AI模型部署CLI工具，支持Jetson、RTX、苹果硅等多硬件平台，为具身模型的端侧部署提供了一键化解决方案。

---

## 趋势信号分析
今日社区最突出的爆发方向是**具身Agent与物理设计工具的融合**：text-to-CAD类项目同时登上全站Trending与机器人主题榜，单日新增超600星，反映出社区对“AI直接参与硬件设计、物理世界建模”的需求快速增长，与近期具身智能从纯软件向物理落地、硬件迭代加速的行业趋势高度契合。
其次，人形机器人开源生态进入细分化爆发阶段，覆盖执行器选型、运动控制、动作模仿、全身VLA的全链路项目密集出现，其中宇树系列平台的第三方项目占比超60%，印证了消费级人形平台正在成为开发者生态的核心载体。
此外，世界动作模型（WAM）作为VLA的延伸方向首次出现系统性开源工具链，代表具身基础模型正从“指令响应”向“主动世界建模”升级，与2026年以来基础模型厂商加码物理AI的动向一致。

---

## 社区关注热点
- 🔥 [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)：单日新增619星的全站Trending项目，首次实现AI Agent原生的CAD生成能力，打通了具身智能从设计到制造的上游环节，是硬件AI方向的核心工具，值得所有关注具身落地的开发者跟进。
- 🤖 [black-forest-labs/flux-action](https://github.com/black-forest-labs/flux-action)：黑森林实验室最新开源的7B参数世界动作模型，支持机器人、仿真、游戏多场景动作预测，是当前开源界覆盖场景最广的动作基础模型之一，代表了VLA技术的新方向。
- 🦾 [enactic/openarm](https://github.com/enactic/openarm)：3.5k+星的全开源人形机械臂平台，面向接触富集任务的物理AI研究，填补了开源人形上肢硬件的空白，是操作类VLA与运动控制研究的重要载体。
- 🛠️ [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)：无ROS依赖的轻量sim2real框架，原生支持多型号机械臂与VLA/RL策略部署，解决了当前机器人学习框架依赖ROS、部署复杂的痛点，适合快速原型验证。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*