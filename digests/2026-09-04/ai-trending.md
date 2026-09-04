# AI 开源趋势日报 2026-09-04

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-04 01:48 UTC

---

# 具身智能与机器人开源趋势日报
**日期**：2026-09-04  
**数据来源**：GitHub Trending 实时榜、GitHub 主题搜索（7天活跃项目）

---

## 今日速览
1. 今日GitHub Trending榜单暂无直接聚焦具身智能、机器人与VLA的专属项目，社区短期热度仍向通用AI Agent技能类工具倾斜，但主题搜索下的具身智能生态仍保持高活跃度，覆盖从底层基础设施到落地应用的全链条。
2. VLA领域技术迭代加速，不仅有NVIDIA推出的面向自动驾驶的Alpamayo系列推理型VLA模型，也涌现出面向精确操作、鲁棒性评测等细分方向的前沿研究与工具链，配套的训练、评估基础设施逐步完善。
3. 人形与操作机器人的开源生态快速扩容，从openarm开源人形机械臂、足式运动控制算法到sim2real部署工具的全链路项目持续更新，厂商主导的开源项目成为推动技术落地的重要力量。
4. 具身智能的落地场景持续外延，除了自动驾驶、服务机器人等成熟场景，实验室自动化、数字孪生、农业分拣等新兴场景的开源项目不断出现，显示出具身技术向垂直行业渗透的趋势。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、中间件）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,912  
   通用多关节动力学接触物理仿真器，是机器人学习、具身智能研究的核心仿真基础设施，生态覆盖人形、操作、足式等几乎所有机器人方向。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,036  
   基于NVIDIA Isaac Sim的统一机器人学习框架，支持从仿真训练到部署的全流程，是当前VLA、强化学习研究最常用的仿真平台之一。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,918  
   数据流导向的机器人中间件，低延迟、可组合、分布式，专为AI机器人应用设计，适配多模态感知与VLA部署。
4. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,393  
   多模态机器人数据可视化、查询与流式工具，解决具身智能训练中多传感器数据对齐、可视化的痛点。
5. [softmata/horus](https://github.com/softmata/horus) ⭐432  
   号称“机器人界的Android”的高性能机器人运行时系统，定位通用机器人操作系统，是新兴的机器人底层基础设施项目。
6. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,717  
   面向具身与Agent AI的强化学习基础设施，为VLA、机器人策略训练提供工程化支撑。

### 🧠 VLA/基础模型（视觉-语言-动作、模仿/强化学习、世界模型）
1. [NVlabs/alpamayo1.5](https://github.com/NVlabs/alpamayo1.5) ⭐362  
   NVIDIA最新开源的10B参数推理型VLA模型，面向自动驾驶场景，新增RL增强推理、导航引导与VQA能力，是大模型厂商入局具身VLA的标志性项目。
2. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐467  
   面向通用具身智能的开放世界基础模型，定位跨场景、跨机器人的通用具身基座，是近期VLA领域的新兴项目。
3. [starVLA/VLAct](https://github.com/starVLA/VLAct) ⭐95  
   提出以表征为中心的VLA持续预训练方法，突破数据缩放瓶颈，为VLA模型的性能提升提供了新的技术路径。
4. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐201  
   开源物理AI评估工具，支持任意LLM/VLA在任意机械臂/人形机器人的仿真/真实基准上测试，填补了VLA统一评估的空白。
5. [baidu-baige/LoongForge](https://github.com/baidu-baige/LoongForge) ⭐549  
   高性能训练框架，支持LLM、VLM、扩散模型与具身模型的训练，适配NVIDIA GPU与昆仑芯XPU，是国内少有的具身模型训练基础设施。
6. [cau-hai-lab/LIBERO-Para](https://github.com/cau-hai-lab/LIBERO-Para) ⭐44  
   EMNLP 2026论文实现，针对VLA模型的 paraphrase 鲁棒性提出诊断基准与评测指标，推动VLA的自然语言理解泛化能力提升。

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,920  
   完全开源的人形机械臂，面向接触丰富环境下的物理AI研究与部署，是操作领域核心的高端硬件开源项目。
2. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐175  
   CVPR 2025论文实现，提出LLM驱动的仿真生成方法，提升指令跟随操作的泛化性，是操作任务与大模型结合的前沿方向。
3. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐471  
   机器人操作官方基准库，为操作算法的横向对比提供统一评测平台。
4. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐68  
   开源双臂同步数据采集与重靶向软件，支持任意双臂机器人的演示数据收集，解决操作任务数据稀缺的痛点。
5. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐25  
   OpenPI的部署导向fork，适配LimX TRON2操作臂，提供pi0.5策略部署、任务微调与实机客户端示例，推动VLA操作模型的落地。
6. [PINE-Lab-NTU/FACET](https://github.com/PINE-Lab-NTU/FACET) ⭐11  
   针对接触丰富型精确操作的机器人基础模型，解决VLA在精细操作任务中的泛化性问题，是操作类VLA的前沿探索。

### 🚶 运动与导航（足式、人形、SLAM、运动控制）
1. [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) ⭐5,251  
   开源四足机器人宠物框架，类波士顿动力四足设计，面向STEM教育、DIY与研究，是足式机器人领域最成熟的开源硬件项目之一。
2. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325  
   专注足式运动算法与动量优化控制的机器人软件，支撑多个人形、双足机器人研发，是运动控制领域的标杆开源项目。
3. [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx) ⭐273  
   基于JAX的模型预测控制实现，适配人形、足式机器人的高速运动规划，是运动控制算法的前沿工具。
4. [Open-X-Humanoid/BICMap](https://github.com/Open-X-Humanoid/BICMap) ⭐45  
   基于WebGL的机器人地图可视化SDK，支持SLAM地图、点云、3D模型与导航可视化，为人形机器人导航开发提供前端工具。
5. [purdue-tracelab/PACE-ICRA2026](https://github.com/purdue-tracelab/PACE-ICRA2026) ⭐81  
   ICRA 2026论文，提出物理增强的端到端强化学习方法，实现人形机器人的多任务乒乓球操作，是人形运动+操作交叉的前沿研究。
6. [limxdynamics/humanoid-mujoco-sim](https://github.com/limxdynamics/humanoid-mujoco-sim) ⭐10  
   LimX人形机器人的MuJoCo仿真环境，支持sim-to-real训练与策略评估，是人形机器人运动学习的基础工具。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,565  
   机器人操作系统，当前已适配300+车型的ADAS升级，是具身智能在自动驾驶场景规模最大的落地开源项目。
2. [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) ⭐6,697  
   开源智能割草机器人方案，基于RTK GPS将传统廉价割草机升级为自主导航机型，是服务机器人落地的典型开源项目。
3. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,808  
   ICML 2026论文的数字孪生项目，支撑机器人的仿真训练与虚实映射，是sim2real的核心基础设施之一。
4. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐55  
   面向化学实验室自动化的机器人数字孪生，是具身技术在生命科学、科研自动化场景的落地探索。
5. [iit-DLSLab/locomanipulation-teleop-isaaclab](https://github.com/iit-DLSLab/locomanipulation-teleop-isaaclab) ⭐25  
   基于IsaacLab的足式+机械臂遥操作环境，支持sim-to-sim与sim-to-real管线，是遥操作技术的前沿落地工具。
6. [limxdynamics/humanoid-rl-deploy-ros2](https://github.com/limxdynamics/humanoid-rl-deploy-ros2) ⭐13  
   基于ROS 2 Humble的人形机器人RL策略部署方案，支持ONNX推理与运动控制，推动人形机器人的sim2real落地。

---

## 趋势信号分析
当前具身智能开源社区的核心热度正向**VLA垂直化落地与机器人底层基础设施**两个方向集中：一方面，VLA技术从通用演示模型向自动驾驶、精密操作等垂直场景深化，NVIDIA等头部厂商的入场带动了推理型VLA、场景专用VLA的探索热度，配套的统一评估工具、训练框架等生态快速补全，与近期行业内“基础模型向具身物理世界落地”的趋势高度契合。
另一方面，机器人底层系统涌现新的技术路径，以dora-rs数据流中间件、Horus机器人运行时为代表的“机器人OS”类项目，试图突破传统ROS架构在AI机器人场景下的性能瓶颈，呼应了当前人形机器人、通用机器人对低延迟、多模态融合算力调度的迫切需求。（全文约280字）

---

## 社区关注热点
- **NVIDIA Alpamayo系列VLA模型**：作为头部算力厂商推出的开源推理型VLA，首次将因果链推理与机器人动作生成结合，代表了大模型厂商入局具身智能的技术路线，值得开发者跟进VLA的“推理+动作”新范式。
- **softmata/horus 机器人运行时**：定位“机器人界的Android”的新型底层操作系统，跳出传统ROS的节点通信范式，面向AI机器人优化 runtime，可能成为下一代具身智能机器人的核心基础设施。
- **enactic/openarm 开源人形机械臂**：完全开源的接触丰富型人形机械臂硬件，填补了开源操作硬件的高端空白，降低了物理AI、精密操作研究的硬件门槛，适合操作方向的研究者与开发者关注。
- **robocurve/inspect-robots VLA评估工具**：支持跨模型、跨机器人、跨仿真/实机的统一评估框架，解决了当前VLA领域缺乏标准评测体系的痛点，是VLA从实验室走向落地的必备工具。
- **LimX Dynamics 人形全链路开源项目**：厂商连续开源人形机器人的模型、仿真、部署全链路工具，代表了人形机器人行业从闭源走向开放的趋势，有效降低研发门槛，是人形方向开发者的重点关注对象。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*