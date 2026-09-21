# AI 开源趋势日报 2026-09-21

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-21 02:10 UTC

---

# 具身智能与机器人开源趋势日报
**日期**：2026-09-21  
**数据来源**：GitHub Trending 实时热榜、GitHub 主题搜索（7天活跃项目）

---

## 今日速览
1. 今日GitHub热榜中，数字具身基础设施项目[trycua/cua](https://github.com/trycua/cua)单日新增1018星，反映AI操作计算机（Computer-Use）赛道正获得社区爆发性关注，成为具身智能的新兴分支。
2. VLA（视觉-语言-动作）领域全栈生态快速完善，从通用基础模型、统一训练框架到中文学习资源均有热门项目，数据端出现通过人类视频生成预训练数据的新方案，大幅降低研发门槛。
3. 人形机器人开源工具链加速落地，从底层运行时系统、运动控制算法到VLA模型适配、实机场景应用全链路均有新项目更新，国产硬件与全球开源生态的融合速度加快。
4. 机器人操作领域的泛化性与可靠性成为核心痛点，技能图编译、LLM驱动仿真生成等方案涌现，触觉数据采集、双臂UMI等工具进一步降低实机数据获取门槛。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,241  
   通用多关节接触动力学物理仿真器，是机器人学习、具身AI研究的核心底层工具，拥有行业最完善的生态与社区支持。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,177  
   基于Isaac Sim的统一机器人学习框架，支持多物理引擎、多渲染器，是当前具身智能仿真训练的主流工具链。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,970  
   数据流导向的机器人中间件，具备低延迟、可组合、分布式特性，专为AI机器人应用设计，适配多类硬件与模型。
4. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,663  
   基于NVIDIA Warp的GPU加速物理仿真引擎，专为机器人研究者优化，支持大规模并行仿真，显著提升训练效率。
5. [softmata/horus](https://github.com/softmata/horus) ⭐439  
   号称“机器人的Android”的高性能运行时系统，面向机器人场景深度优化，近期人形机器人赛道热度带动其关注度快速上升。
6. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,729  
   ROS 2官方导航框架，覆盖定位、路径规划、避障全链路，是移动机器人的标配导航方案。
7. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,480  
   多模态机器人数据可视化、查询与流处理工具，解决机器人研发中多源数据调试的核心痛点。

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐2,055  
   开放世界通用具身智能基础模型，面向多场景通用具身任务，代表VLA从单任务向通用具身智能进化的核心方向。
2. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐5,309  
   专为具身与Agent AI设计的强化学习基础设施，支撑大规模RL训练，是VLA模型迭代的核心底座。
3. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,789  
   面向零基础开发者的中文具身智能教程，从0搭建VLA/OpenVLA/Pi0等主流模型，社区活跃度极高。
4. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐304  
   世界动作模型（WAM）统一训练、微调、评估框架，大幅降低VLA类模型的研发门槛，推动工程化落地。
5. [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) ⭐66  
   带原生视频记忆的VLA模型，通过时间戳视觉历史与流推理支持长时序机器人操作，解决长horizon任务痛点。
6. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐634  
   全中文VLA领域实战学习/面试手册，聚焦机器人特有挑战，填补中文VLA系统化学习资源的空白。
7. [3587jjh/HuRo](https://github.com/3587jjh/HuRo) ⭐27（CoRL 2026）  
   通过将人类视频自动转换为机器人训练数据，解决VLA预训练数据稀缺的核心问题，有望大幅降低VLA研发成本。

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐597  
   主流机器人操作基准平台，为操作算法提供统一评测环境，支撑操作策略的泛化性验证。
2. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐176（CVPR 2025）  
   通过LLM驱动仿真生成，提升指令跟随操作的泛化能力，为操作任务数据增强提供新路径。
3. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐141  
   将自然语言指令编译为类型安全的机器人技能图，可直接在仿真/实机执行，显著提升操作任务的可靠性。
4. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐68  
   开源双手UMI数据采集与重定向软件，支持任意双臂机器人，解决双臂操作数据采集的痛点。
5. [XenseRobotics-AI/lerobot-xense](https://github.com/XenseRobotics-AI/lerobot-xense) ⭐20  
   LeRobot v5.1分支，支持多品牌机械臂与触觉夹爪，集成VR/SpaceMouse等遥操作方式，降低实机数据采集门槛。
6. [XenseRobotics-AI/xense-openpi](https://github.com/XenseRobotics-AI/xense-openpi) ⭐16  
   π0系列VLA适配Xense双臂平台，支持微调与实机部署，推动开源VLA向工业级硬件落地。

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,694  
   最受欢迎的开源机器人操作系统之一，已落地300+车型的驾驶辅助，是移动机器人导航落地的标杆项目。
2. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325  
   业界领先的足式运动算法与动量控制器，支持人形机器人、外骨骼等多类平台，是足式控制的核心参考实现。
3. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐117  
   清华MARS实验室工作，多模态运动生成模型，实现通用人形机器人控制，代表运动智能的前沿方向。
4. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐26  
   LimX TRON2双臂人形机器人的OpenPI部署分支，带实机客户端示例，推动开源VLA与人形硬件的深度结合。
5. [Renkunzhao/legged-daily](https://github.com/Renkunzhao/legged-daily) ⭐23  
   足式机器人与基于学习的控制研究资源合集，实时跟踪领域前沿进展，是足式方向开发者的优质信息源。
6. [ershui2500/UniRoboGui](https://github.com/ershui2500/UniRoboGui) ⭐3  
   宇树G1人形机器人的Web GUI与SDK仪表盘，支持遥测、控制、SLAM、点云调试等功能，为人形机器人调试提供便捷工具。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [trycua/cua](https://github.com/trycua/cua) ⭐0（今日+1018，Trending热榜）  
   今日最大黑马，面向Computer-Use 2.0的全栈开源基础设施，覆盖跨OS驱动、集群管理、训练/评估基准，为数字具身Agent提供完整工具链，单日新增超千星，社区关注度爆发。
2. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐570  
   物理AI开源评估框架，支持任意LLM/VLA在任意机械臂/人形机器人上跑仿真/实机基准，解决VLA落地评测碎片化的痛点。
3. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,708  
   斯坦福大学具身AI研究平台，提供1000+真实家庭任务，是具身智能sim2real验证的主流基准。
4. [physiclaw/PhysiClaw](https://github.com/physiclaw/PhysiClaw) ⭐374  
   可物理操作手机的AI Agent，完全模拟人类操作方式，是具身智能向消费电子场景落地的创新探索。
5. [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐219  
   统一机器人CLI工具，支持多类机器人硬件与LLM后端，内置安全合约与记忆机制，降低多机器人协同部署门槛。
6. [Orboh/DimOS_base_G1-TOYOTA-BODY-RESEARCH](https://github.com/Orboh/DimOS_base_G1-TOYOTA-BODY-RESEARCH) ⭐1  
   基于宇树G1的秋葵收获实装项目，集成YOLO检测、逆运动学、UMI扩散策略，是人形机器人农业场景落地的前沿实践。

---

## 趋势信号分析
今日社区热度核心集中在**数字具身（Computer-Use）**与**VLA全栈生态完善**两大方向。其中trycua/cua登热榜并单日破千星，标志着“操作数字世界的具身Agent”首次成为GitHub具身赛道的爆点方向，本质是VLA技术从物理机器人向数字场景的延伸，与近期Anthropic、OpenAI密集推出computer-use产品的行业节奏高度契合。
此外，VLA领域正从单点模型研发向工程化落地过渡：训练端出现EasyWAM等统一框架、SimpleMemVLA等长时序方案，数据端出现HuRo等人类视频转训练数据的低成本路径，评测端出现inspect-robots等跨平台工具，全链路工具链的成熟意味着VLA距离规模化落地更近一步。人形机器人方面，国产硬件的开源适配项目增多，反映国内产业正加速与全球开源VLA生态融合。（全文约290字）

---

## 社区关注热点
- 🔥 **[trycua/cua](https://github.com/trycua/cua)**：今日热榜最大黑马，单日新增1018星，是首个面向Computer-Use 2.0的全栈开源基础设施，覆盖驱动、集群、基准全链路，值得所有关注具身Agent落地的开发者重点跟踪。
- 🧠 **[dexmal/opendm](https://github.com/dexmal/opendm)**：2k+星的开放世界通用具身基础模型，代表VLA从单任务向通用具身智能进化的核心方向，是当前基础模型向具身延伸的代表性项目。
- 🦾 **[3587jjh/HuRo](https://github.com/3587jjh/HuRo)**：CoRL 2026接收工作，通过人类视频机器人化生成VLA预训练数据，直击VLA训练数据稀缺的核心痛点，有望大幅降低VLA研发成本。
- 🤖 **[softmata/horus](https://github.com/softmata/horus)**：主打“机器人的Android”的高性能运行时系统，随着人形机器人赛道升温，专用运行时作为底层软件底座的价值正在凸显，有望成为机器人领域的生态级项目。
- 📚 **[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)**：3.7k+星的中文具身智能入门教程，从0搭建VLA模型，内容覆盖从基础到实战全流程，是开发者快速进入具身智能领域的优质资源。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*