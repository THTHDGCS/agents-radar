# AI 开源趋势日报 2026-09-08

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-08 01:52 UTC

---

# 具身智能与机器人开源趋势日报
**日期**：2026-09-08  
**数据来源**：GitHub Trending 实时榜、GitHub 主题搜索（机器人/具身智能/VLA相关主题，7天活跃）

---

## 今日速览
1. 今日GitHub通用Trending榜单未出现具身智能、机器人及VLA相关项目，社区热度集中在7天内活跃的主题项目中，覆盖机器人框架、VLA、操作、运动、具身应用五大方向，共60+有效项目。
2. VLA领域正从“数据缩放”向“表示优化”“场景适配”演进，本周新增多个面向抗杂波、接触丰富操作的专用VLA模型，以及世界动作模型（WAM）的统一训练框架，WAM正成为新的热点赛道。
3. 人形机器人开源生态加速完善，从低成本DIY硬件、运动控制算法到全身VLA方案形成完整链路，JAX、无ROS架构等AI原生技术栈正在向机器人底层工具链快速渗透。
4. 落地导向的工具链关注度显著上升，包括VLA评估框架、sim2real部署工具、数字孪生平台等，成为连接算法与实体机器人的核心缺口。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,463  
   机器人算法的Python示例库与教材，覆盖路径规划、SLAM、运动控制等核心模块，是机器人入门与算法验证的经典工具。
2. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,822  
   全球最活跃的开源飞控/自动驾驶框架，支持无人机、无人车、无人船等多类移动机器人，是移动机器人运动控制的事实标准。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,977  
   DeepMind开源的通用多关节动力学物理仿真器，是机器人学习、VLA训练的核心仿真基础设施。
4. [DLR-RM/stable-baselines3](https://github.com/DLR-RM/stable-baselines3) ⭐13,776  
   基于PyTorch的强化学习算法库，提供可靠的RL实现，是机器人强化学习研究的标配工具。
5. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,407  
   多模态机器人数据可视化工具，支持实时流与训练数据可视化，大幅提升机器人系统调试效率。
6. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,598  
   基于NVIDIA Warp的GPU加速物理仿真引擎，专为机器人研究者优化，支持大规模并行仿真任务。
7. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,924  
   数据流导向的AI机器人中间件，低延迟、可组合、分布式架构，是ROS之外的新兴轻量化AI原生机器人开发框架。

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. [OpenMOSS/Awesome-WAM](https://github.com/OpenMOSS/Awesome-WAM) ⭐1,386  
   世界动作模型（WAM）精选论文与资源列表，WAM是VLA向长时序、可预测演进的核心方向，是领域入门的全景式参考。
2. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐596  
   全中文VLA实战学习/面试手册，聚焦机器人领域特有挑战，适合国内开发者系统入门。
3. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐474  
   面向通用具身智能的开放世界基础模型，支持多模态感知与动作生成，是新一代具身基础模型的代表。
4. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐364  
   开源物理AI评估框架，支持任意LLM/VLA在机械臂/人形机器人上的仿真与真实基准测试，解决VLA评估碎片化问题。
5. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐159  
   世界动作模型（WAM）的统一训练、微调、评估框架，大幅降低WAM研发门槛，是近期增长最快的工具类项目。
6. [starVLA/VLAct](https://github.com/starVLA/VLAct) ⭐110  
   提出表示中心的VLA持续预训练方法，突破数据缩放瓶颈，为VLA性能提升提供新的技术路径。
7. [UARK-AICV/DRAGON_VLA](https://github.com/UARK-AICV/DRAGON_VLA) ⭐14  
   抗杂波的对象中心几何接地VLA模型，解决真实场景中背景干扰问题，提升VLA在复杂环境下的落地可靠性。

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [RoboTwin-Platform/RMBench](https://github.com/RoboTwin-Platform/RMBench) ⭐207  
   基于RoboTwin的记忆依赖操作基准，聚焦长时序操作任务中的记忆与推理能力，填补了操作类基准的细分空白。
2. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐176  
   CVPR 2025入选工作，通过LLM驱动仿真生成通用指令跟随操作数据，为解决操作数据稀缺问题提供新方案。
3. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐130  
   将自然语言指令编译为可验证的机器人技能图，支持仿真与真实机器人部署，提升操作任务的可靠性与可解释性。
4. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐69  
   双臂同步数据采集与动作重靶向软件，适配多类双臂机器人平台，是VLA操作技能训练的核心数据工具。
5. [RobotControlStack/duobench](https://github.com/RobotControlStack/duobench) ⭐18  
   双臂操作可复现基准，覆盖仿真与真实世界，为双臂VLA模型的性能对比提供统一标准。
6. [PINE-Lab-NTU/FACET](https://github.com/PINE-Lab-NTU/FACET) ⭐12  
   最新发布的接触丰富精确操作机器人基础模型（arXiv 2609.01596），面向高精度装配等工业场景，是操作基础模型的前沿进展。

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,932  
   完全开源的人形机械臂，面向接触丰富环境的物理AI研究与部署，是当前最热门的开源人形硬件项目之一。
2. [softmata/horus](https://github.com/softmata/horus) ⭐433  
   号称“机器人界Android”的高性能运行时系统，面向AI原生机器人设计，低延迟高并发，是新兴的机器人操作系统候选。
3. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325  
   IHMC开源的腿式机器人算法库，包含成熟的动量控制与运动规划算法，是人形/双足机器人运动控制的经典参考。
4. [Rhoban/microban](https://github.com/Rhoban/microban) ⭐293  
   100%开源3D打印的低成本人形机器人，基于树莓派Zero 2W与19个舵机，大幅降低人形机器人开发门槛。
5. [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx) ⭐273  
   基于JAX的模型预测控制（MPC）库，适配人形/腿式机器人的高速运动控制，代表JAX技术栈向机器人底层渗透的趋势。
6. [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐3  
   统一VLA框架实现人形机器人全身操作-运动控制，是VLA从单臂操作向人形全身能力拓展的前沿探索。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,597  
   开源驾驶辅助系统，支持300+车型，是全球规模最大的具身智能落地应用之一，验证了AI机器人在消费级场景的可行性。
2. [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover) ⭐9,632  
   NASA JPL开源的六轮火星车DIY项目，面向科研与教育，是行星探测类具身机器人的参考实现。
3. [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) ⭐6,698  
   开源RTK GPS智能割草机器人，将消费级机器人改装为高精度自主平台，是户外具身应用的典型代表。
4. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,576  
   国内热门的具身智能入门教程，从Python基础到VLA模型构建全链路覆盖，大幅降低国内开发者的入门门槛。
5. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,818  
   ICML 2026入选的RoboTwin 2.0官方实现，机器人数字孪生平台，是sim2real落地的核心工具。
6. [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐171  
   低门槛具身Agent部署工具，用LLM为小型机器人规划动作，支持多类硬件平台与大模型，适合快速原型验证。

---

## 趋势信号分析
从本周活跃项目来看，**VLA工程化与世界动作模型（WAM）** 是社区爆发性关注的核心方向：7天内VLA相关活跃项目近20个，覆盖模型、训练框架、评估工具全链路，其中WAM相关项目增速最快，反映社区正从“单步视觉-动作映射”向“长时序世界建模+动作生成”的下一代具身基础模型演进。
新兴技术栈方面，**无ROS轻量化机器人架构、JAX生态的运动控制/RL工具、支持MCP协议的AI原生仿真器** 首次集中出现，代表软件AI Agent的技术栈正在向具身领域渗透，机器人系统正从“专用硬件驱动”向“AI原生”重构。
这一趋势与近期人形机器人量产推进、大厂加码具身基础模型的行业节奏高度吻合：随着Optimus、宇树等产品落地，行业对统一VLA训练/评估标准、低成本sim2real工具的需求快速释放，开源社区正在补全落地最后一公里的基础设施缺口。

---

## 社区关注热点
- 🌟 **世界动作模型（WAM）方向**：代表项目 [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM)、[OpenMOSS/Awesome-WAM](https://github.com/OpenMOSS/Awesome-WAM)。WAM被视为VLA的下一代演进方向，统一训练框架的出现将大幅降低研发门槛，建议开发者提前布局相关技术。
- 🌟 **无ROS的AI原生机器人框架**：代表项目 [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)、[dora-rs/dora](https://github.com/dora-rs/dora)。传统ROS生态复杂度高、适配AI效率低，面向VLA/RL优化的轻量化框架正在成为机器人AI化的核心基础设施。
- 🌟 **接触丰富操作的基础模型**：代表项目 [PINE-Lab-NTU/FACET](https://github.com/PINE-Lab-NTU/FACET)。当前VLA多面向非接触或简单操作任务，接触丰富的精确操作是人形机器人落地工业、家庭场景的核心瓶颈，相关研究具备高技术价值。
- 🌟 **低成本开源人形机器人平台**：代表项目 [Rhoban/microban](https://github.com/Rhoban/microban)、[enactic/openarm](https://github.com/enactic/openarm)。千元级DIY人形硬件将大幅降低开发者的入门门槛，推动具身AI从实验室向普惠化发展。
- 🌟 **VLA统一评估体系**：代表项目 [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)。当前VLA模型缺乏统一的物理世界评估标准，评估工具将成为行业事实标准的核心载体，具备高生态价值。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*