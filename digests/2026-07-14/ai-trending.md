# AI 开源趋势日报 2026-07-14

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-14 01:19 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-14）

---

## 今日速览
今日GitHub通用Trending榜单无核心具身智能/机器人领域项目上榜，社区热度集中于主题标签下的开源工具链与普惠化资源。VLA方向的全中文学习资源、极简入门demo、工程化工具链同步涌现，标志着VLA正式从学术研究进入大规模开发者上手的阶段。全开源人形机械臂、低成本3D打印人形机器人等硬件项目快速迭代，配合无ROS轻量化部署框架，大幅降低了具身智能的研发门槛。机器人runtime、中间件等底层基础软件出现创新项目，对应近期人形机器人产业化加速的行业趋势，产业链关注度正从上层算法向下层基础软件渗透。

---

## 各维度热门项目

### 🤖 机器人框架/SDK（控制、仿真、规划、中间件）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,104  
   全球最知名的开源机器人操作系统，目前已落地支持300+车型的辅助驾驶，是具身智能落地消费级场景的标杆项目。
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,193  
   通用多体物理仿真器，是当前机器人学习、VLA训练的事实标准仿真工具，生态覆盖几乎所有主流具身智能项目。
3. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,667  
   基于NVIDIA Isaac Sim的统一机器人学习框架，是目前工业界和学术界人形机器人、操作任务研发的首选仿真训练平台。
4. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,842  
   数据流导向的开源机器人中间件，主打低延迟、可组合、分布式特性，适合AI原生机器人应用的快速开发。
5. [softmata/horus](https://github.com/softmata/horus) ⭐389  
   面向机器人的高性能runtime系统，定位“机器人的Android”，是底层机器人操作系统方向的新兴高潜力项目。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124  
   无ROS的轻量化sim2real部署框架，原生支持VLA模型与RL代理的训练部署，适配多款主流机械臂，大幅降低落地门槛。

---

### 🧠 VLA/基础模型（视觉-语言-动作、策略学习）
1. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐382  
   国内首份全中文、实战导向的VLA学习面试手册，聚焦机器人领域特有挑战，是算法工程师进入VLA领域的首选入门资料。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,652  
   零门槛具身智能教学项目，仅需Python基础即可从0构建OpenVLA/SmolVLA等主流VLA模型，是普惠化具身智能教育的标杆。
3. [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) ⭐60  
   RSS2026顶会论文开源项目，通过通用姿态预训练实现可泛化的VLA策略，代表了当前VLA算法研究的前沿方向。
4. [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) ⭐6  
   极简可解读的VLA实现，仅用冻结CLIP加微型头即可完成ManiSkill任务，支持LeRobot，无GPU的Mac也可运行，是VLA入门学习的最佳极简demo。
5. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐60  
   面向通用具身智能的开源基础模型，探索开放世界下的具身能力泛化，是具身基础模型方向的新兴项目。
6. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐3  
   VLA与物理AI模型的通用评估框架，可实现一次定义基准、跨机器人/仿真运行所有策略，填补了VLA工程化中统一评估的空白。

---

### 🦾 操作与抓取（灵巧手、接触富集任务、硬件平台）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,713  
   全开源人形机械臂平台，专为接触富集的物理AI研究与落地设计，是目前全球热度最高的开源操作硬件项目。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐206  
   机器人操作方向的官方基准仓库，提供标准化的操作任务评测集，用于验证操作算法的泛化性与鲁棒性。
3. [philfung/awesome-reliable-robotics](https://github.com/philfung/awesome-reliable-robotics) ⭐156  
   持续更新的真实世界鲁棒机器人操作论文合集，聚焦操作技术的落地可靠性，是从事落地研发的必备资源。
4. [Manas-arumalla/openarm-control](https://github.com/Manas-arumalla/openarm-control) ⭐3  
   OpenArm v2双臂机械臂的全栈控制平台，支持IK规划、ACT视觉策略、RL插入等核心操作能力，是openarm生态的核心配套工具。
5. [flexiv_control](https://github.com/ZihaoLu001/flexiv_control) ⭐3  
   Flexiv Rizon力控机械臂的统一实时控制与安全层，支持遥操作、MPC、RL与sim2real，是工业机械臂操作落地的实用工具。

---

### 🚶 运动与导航（足式/人形机器人、SLAM、路径规划）
1. [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐809  
   基于IsaacLab的足式机器人开发工作流，大幅简化人形足式机器人的仿真训练与sim2real流程，是足式研发的热门工具。
2. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,459  
   ROS2生态的标准导航框架，支持路径规划、避障、定位等全链路导航能力，是移动机器人落地的成熟方案。
3. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐254  
   UMI-3D SLAM与数据处理管线，提供高精度的三维环境建图能力，支持具身机器人的真实世界导航与定位。
4. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐322  
   专业的足式运动控制算法库，支持人形机器人、外骨骼、四足等多种平台的运动控制，是运动控制方向的标杆开源项目。
5. [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐19  
   低成本全3D打印开源人形机器人，基于树莓派Zero 2W，总硬件成本极低，是个人开发者入门人形机器人研发的首选DIY平台。
6. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐131  
   轻量可扩展的人形机器人全身遥操作框架，支持低成本的全身动作捕捉与机器人控制，是人形机器人数据收集与调试的实用工具。

---

### 📦 具身应用（sim2real、部署、落地场景）
1. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,095  
   面向具身与Agent AI的强化学习基础设施，提供标准化的RL训练与部署 pipeline，是具身智能算法落地的核心支撑工具。
2. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,569  
   开源机器人数字孪生平台，支持高保真仿真与真实机器人的双向同步，是sim2real落地的核心载体。
3. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,568  
   斯坦福大学推出的具身AI研究平台，提供1000+真实世界日常任务基准，加速具身智能算法的泛化性验证与落地。
4. [FastCrest/tether](https://github.com/FastCrest/tether) ⭐73  
   开源边缘到云端的AI部署CLI，支持Jetson、RTX、Apple Silicon等多平台的VLA模型优化与部署，解决了具身模型跨硬件部署的痛点。
5. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐102  
   基于大语言Agent的自然语言硬件控制工具，可直接通过自然语言指令控制各类机器人与物理硬件，是VLA落地消费级场景的低代码方案。

---

## 趋势信号分析
今日社区热度呈现两大核心趋势：一是VLA工程化落地节奏明显加快，从入门手册、极简demo到评估框架、跨硬件部署工具的全链路工具链同步补全，说明VLA已经走出实验室，进入开发者大规模验证、场景落地的阶段，相关工具缺口正在被快速填补；二是具身智能普惠化趋势明确，全开源人形机械臂、低成本DIY人形机器人、零门槛中文教程的出现，让个人开发者与小团队无需高额硬件投入即可参与具身智能研发，大幅扩大了社区基数。此外，面向机器人的专用runtime、中间件等底层软件创新涌现，对应近期人形机器人产业化的行业需求，产业链正从算法创新向底层基础软件生态延伸。

---

## 社区关注热点
- 【[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)】：国内最友好的零门槛具身智能中文教程，仅需Python基础即可从0实现主流VLA模型，适合所有想要进入具身领域的开发者，社区热度持续攀升。
- 【[enactic/openarm](https://github.com/enactic/openarm)】：2.7k星的全球热度最高开源人形机械臂，专为接触富集的物理AI场景设计，解决了操作方向研发的硬件成本痛点，是操作与VLA落地的首选硬件平台。
- 【VLA全链路工具链方向】：今日涌现的VLA评估、部署、红队测试等工具项目，标志着VLA进入工程化落地阶段，提前布局相关工具链研发的开发者将获得行业先发优势。
- 【[softmata/horus](https://github.com/softmata/horus)】：定位“机器人的Android”的专用runtime，是机器人底层操作系统方向的颠覆性创新项目，可能重构未来机器人软件的开发范式，值得长期关注。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*