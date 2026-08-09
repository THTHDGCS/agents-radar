# AI 开源趋势日报 2026-08-09

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-08-09 00:50 UTC

---

# 具身智能与机器人开源趋势日报（2026-08-09）

---

## 今日速览
今日GitHub具身智能与机器人领域的核心动向集中在三方面：一是自进化Agent与模块化技能系统登上全球Trending总榜，单日新增star均破数百，其架构思路为具身Agent的长期自主任务执行提供了参考；二是VLA技术向垂直场景快速渗透，NVIDIA连续开源3代面向自动驾驶的Alpamayo系列VLA，同时人形机器人全栈开源工具链快速扩容；三是中文具身开发者生态持续升温，入门教程、学习手册、资源聚合项目均获得稳定的社区关注度。此外，操作基准、评估工具等细分方向涌现多个新项目，填补了VLA落地的工具缺口。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、中间件）
1. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3869（7天活跃）：数据流导向的机器人中间件，低延迟分布式架构，是当前最受关注的机器人应用开发基础设施，适用于VLA、自主机器人等各类场景的快速搭建。
2. [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3209（7天活跃）：GPU并行化的机器人操作仿真与基准框架，支持大规模VLA/RL策略训练，是具身操作研究的标配仿真工具。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14489（7天活跃）：通用多关节接触物理仿真引擎，是目前机器人学习领域应用最广的开源仿真工具，近期持续优化VLA训练的并行支持。
4. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7861（7天活跃）：基于NVIDIA Isaac Sim的统一机器人学习框架，支持从仿真到实机的全链路开发，是工业级具身应用的首选开发平台。
5. [softmata/horus](https://github.com/softmata/horus) ⭐407（7天活跃）：号称“机器人的Android”的高性能运行时系统，主打低延迟、高并发，解决了当前机器人系统碎片化、部署难的痛点，为新人形机器人产品提供了统一的底层系统选项。
6. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4483（7天活跃）：面向具身与Agent AI的强化学习基础设施，支持大规模RL策略的训练与部署，是VLA算法研发的核心工具。
7. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐128（7天活跃）：无ROS依赖的VLA/RL策略部署框架，原生支持多类机械臂与人形机器人，大幅降低了VLA实机部署的门槛。

---

### 🧠 VLA/基础模型（视觉-语言-动作、Agent能力、策略）
1. [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) ⭐0（今日+2483）：自进化RLM Agent，支持编码工作流与长期自主任务，其自迭代架构为具身Agent的持续学习能力设计提供了重要参考，是今日Trending总榜热度最高的AI Agent项目。
2. [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐1978（7天活跃）：NVIDIA开源的10B参数推理型VLA，面向自动驾驶场景，支持驾驶轨迹与因果链推理的联合输出，是目前规模最大的开源垂直场景VLA。
3. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) ⭐0（今日+779）：生产级AI Agent技能库，今日登上Trending总榜，其模块化、可复用的技能设计思路，可直接迁移至具身VLA的任务拆解与技能组合场景。
4. [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐144（7天活跃）：NVIDIA最新开源的34B参数多任务VLA，支持自动驾驶场景的推理、导航、VQA等多类任务，标志着VLA正在向大参数、多能力方向进化。
5. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐484（7天活跃）：全中文VLA学习与面试手册，聚焦机器人领域的特有挑战，是国内开发者进入VLA领域的核心学习资源。
6. [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) ⭐211（7天活跃）：BridgeVLA与BridgeVLA++的官方实现，是通用具身VLA的主流基线模型，支持多类机器人操作任务的零样本泛化。
7. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐131（7天活跃）：开源物理AI评估工具，支持任意LLM/VLA在任意机器人平台上的基准测试，解决了VLA效果难以横向对比的痛点。

---

### 🦾 操作与抓取（灵巧手、操作基准、接触富集任务）
1. [worldbench/awesome-embodied-data-pyramid](https://github.com/worldbench/awesome-embodied-data-pyramid) ⭐141（7天活跃）：具身操作数据金字塔综述，系统梳理了从原始数据到策略的全链路数据体系，是操作领域研究的必备参考。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐370（7天活跃）：官方机器人操作基准仓库，覆盖多类接触富集操作任务，是VLA操作能力评估的主流基准。
3. [enactic/openarm](https://github.com/enactic/openarm) ⭐2825（7天活跃）：全开源人形手臂，专门针对接触-rich的物理AI场景设计，为VLA的真实世界操作落地提供了低成本的硬件平台。
4. [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8（7天活跃）：面向VLA模型的双手厨房操作基准，基于Inspect Robots搭建，填补了通用操作基准在日常家庭场景的空白。
5. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐15（7天活跃）：LimX TRON2操作机器人的OpenPI部署分支，包含pi0.5策略服务、实机客户端示例，是VLA操作落地的参考实现。
6. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐46（7天活跃）：开源双手操作数据采集与重定向工具，支持将人类操作数据同步到任意双手机器人，是VLA模仿学习数据采集的核心工具。
7. [MrRox1337/GripSense](https://github.com/MrRox1337/GripSense) ⭐0（7天活跃）：滑觉感知机器人抓取控制软件与基准平台，解决了VLA在抓取易碎、易滑物体时的感知痛点。

---

### 🚶 运动与导航（足式、人形、移动机器人、路径规划）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63369（7天活跃）：开源机器人操作系统，目前已支持300+车型的驾驶辅助升级，是VLA在自动驾驶场景落地的最大规模开源项目。
2. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15647（7天活跃）：开源无人机、无人车、无人船固件，是移动机器人导航控制的主流基础设施。
3. [NJU-RLC/quadrupedal-agility](https://github.com/NJU-RLC/quadrupedal-agility) ⭐122（7天活跃）：四足机器人敏捷运动论文官方实现，支持学习多样自然行为，提升四足运动能力，是足式机器人学习的热门项目。
4. [limxdynamics/humanoid-mujoco-sim](https://github.com/limxdynamics/humanoid-mujoco-sim) ⭐9（7天活跃）：LimX人形机器人的MuJoCo仿真环境，支持sim-to-real训练与策略评估，是人形机器人运动学习的参考仿真平台。
5. [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) ⭐38（7天活跃）：人形机器人足球射门项目官方代码，实现了精准、稳定的人形全身运动控制，是人形机器人动态运动能力的典型展示。
6. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4562（7天活跃）：ROS2导航框架，是移动机器人路径规划、自主导航的标配工具，近期新增了VLA导航指令的支持。
7. [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) ⭐6656（7天活跃）：开源智能割草机器人方案，基于RTK GPS实现高精度导航，是服务机器人导航落地的典型参考。

---

### 📦 具身应用（sim2real、遥操作、落地场景、教育资源）
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3050（7天活跃）：面向Python基础开发者的具身智能入门教程，从零构建VLA模型与机器人，是国内新手进入该领域的首选学习资源。
2. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2702（7天活跃）：ICML 2026接收的RoboTwin 2.0官方代码，是机器人数字孪生领域的最新研究成果，支持sim-to-real的高精度迁移。
3. [PhyAgentOS-Dev/PhyAgentOS](https://github.com/PhyAgentOS-Dev/PhyAgentOS) ⭐1709（7天活跃）：基于Agent工作流的自进化具身AI操作系统，支持机器人的长期自主任务执行，是具身系统层面的前沿探索。
4. [Octoday-Hub/Embodied-AI](https://github.com/Octoday-Hub/Embodied-AI) ⭐2272（7天活跃）：国内首个具身智能生态资源社区，聚合论文、项目、课程、招聘等信息，是连接开发者与产业的核心枢纽。
5. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐157（7天活跃）：全身人形机器人遥操作系统，支持人类动作的实时重定向，是人形机器人数据采集与远程操控的核心工具。
6. [robocasa/robocasa](https://github.com/robocasa/robocasa) ⭐1633（7天活跃）：大规模日常任务仿真环境，覆盖上千种家庭操作任务，是通用具身机器人落地家庭场景的核心测试平台。
7. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐52（7天活跃）：面向化学实验室自动化的机器人数字孪生平台，是具身智能在工业垂直场景落地的典型探索。

---

## 趋势信号分析
今日数据显示，VLA技术的垂直场景落地正进入爆发期：NVIDIA连续开源3代Alpamayo系列自动驾驶VLA，参数从10B升级至34B，覆盖推理、导航、VQA等多类能力，标志着VLA已经从通用机械臂操作向自动驾驶、人形机器人等大场景快速渗透。同时，人形机器人全栈开源生态快速成熟，从硬件、仿真、运行时到上层全身控制VLA的工具链持续完善，与近期特斯拉Optimus、Figure 01等人形产品的商业化进展形成呼应，产业落地需求倒逼开源基础设施迭代。此外，具身智能的评估体系逐步成型，各类操作基准、跨平台评估工具密集发布，解决了长期以来VLA效果难以横向对比的痛点。中文开发者生态持续升温，入门教程、学习手册类项目获得稳定关注，国内开发者进入该领域的需求旺盛。

---

## 社区关注热点
- 🎯 **NVIDIA Alpamayo系列VLA**：连续开源3代模型+配套开发食谱，是目前最大规模的开源垂直场景VLA，可直接用于自动驾驶、人形导航等场景的二次开发，代表了VLA商业化落地的主流方向。
- 🎯 **datawhalechina/every-embodied**：仅需Python基础即可入门的全栈具身开发教程，覆盖从VLA模型训练到实机部署的全流程，是新手进入具身智能领域的最低门槛学习资源。
- 🎯 **softmata/horus**：号称“机器人的Android”的高性能运行时系统，解决了当前机器人系统碎片化、部署成本高的痛点，为人形机器人的规模化落地提供了统一底层系统选项，值得长期跟踪。
- 🎯 **robocurve/inspect-robots**：通用VLA/机器人评估工具，支持任意模型、任意机器人、任意基准的统一测试，是VLA研发阶段的必备工具，将推动具身智能评估标准的统一。
- 🎯 **enactic/openarm**：全开源人形手臂，专门针对接触-rich的物理场景设计，大幅降低了VLA实机操作测试的硬件成本，是具身智能真实世界落地的核心硬件平台。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*