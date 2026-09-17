# AI 开源趋势日报 2026-09-17

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-17 02:13 UTC

---

# 具身智能与机器人开源趋势日报（2026-09-17）

---

## 今日速览
1. 今日GitHub全站Trending中仅计算机视觉工具库[roboflow/supervision](https://github.com/roboflow/supervision)入选具身智能相关赛道，反映近期行业热点仍集中在底层研发工具，暂未出现应用级爆点项目。
2. 7天活跃主题项目显示，VLA（视觉-语言-动作）技术栈正快速补全：从预训练数据生成、长时程记忆机制到统一评估框架均有新项目迭代，覆盖从研发到落地的全链路。
3. 人形机器人赛道持续升温，全身控制基础模型、开源硬件、运动智能资源三类项目同步活跃，ICML/CoRL/CVPR等顶会学术成果与产业落地的衔接速度明显加快。
4. 具身落地工具链愈发轻量化：无ROS的sim2real框架、边缘部署CLI、多机器人统一控制接口等项目密集更新，进一步降低了VLA与机器人技术的落地门槛。

---

## 各维度热门项目

### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,177 | 7天活跃
   说明：DeepMind推出的通用多关节接触动力学仿真器，是机器人学习、具身智能研究的核心仿真基础设施，本周持续更新维护，是机器人仿真领域的事实标准。
2. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,876 | 7天活跃
   说明：全球最流行的开源无人系统控制固件，支持无人机、无人车、无人船等多类移动机器人，本周有版本迭代，是移动机器人控制领域的核心开源项目。
3. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,145 | 7天活跃
   说明：NVIDIA推出的统一机器人学习框架，支持多物理引擎与渲染器，是当前VLA、强化学习研究的主流仿真训练平台，本周新增多项机器人操作环境支持。
4. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐4,036 | 7天活跃
   说明：基于Rust开发的数据流导向机器人中间件，主打低延迟、可组合、分布式特性，为AI原生机器人应用提供架构支撑，近期社区活跃度快速上升。
5. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,460 | 7天活跃
   说明：面向多模态机器人数据的可视化、查询与流式处理工具，可大幅提升机器人研发调试效率，本周新增点云、轨迹等多类机器人数据可视化模板。
6. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,712 | 7天活跃
   说明：ROS 2生态的官方导航框架，支持路径规划、避障、定位等全栈导航能力，是移动机器人导航领域的主流开源方案，本周修复多项边缘场景bug。
7. [roboflow/supervision](https://github.com/roboflow/supervision) 今日新增⭐+260 | 登GitHub全站Trending
   说明：可复用的计算机视觉工具库，被广泛应用于机器人视觉感知、具身智能目标检测等场景，今日登榜反映机器人视觉工具的社区需求持续走高。

---

### 🧠 VLA/基础模型（视觉-语言-动作、模仿学习、强化学习）
1. [harvard-edge/cs249r_book](https://github.com/harvard-edge/cs249r_book) ⭐28,251 | 7天活跃
   说明：哈佛CS249r课程配套教材，覆盖ML系统、Agentic AI、物理AI（Physical AI）四大模块，是具身智能系统方向的权威学习资源，本周持续更新内容。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,723 | 7天活跃
   说明：面向国内开发者的具身智能入门项目，仅需Python基础即可从0构建VLA/OpenVLA/SmolVLA/Pi0模型，本周持续更新教程内容，是中文社区入门VLA的首选资源。
3. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐1,146 | 7天活跃
   说明：面向通用具身智能的开放世界基础模型，支持多类机器人任务的泛化执行，是近期具身基础模型领域的新兴项目，社区关注度快速上升。
4. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐554 | 7天活跃
   说明：书生通用人工智能实验室推出的操作型VLA系列模型，统一了视觉理解、内容生成与动作输出能力，是国内产业界VLA的代表性项目。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐514 | 7天活跃
   说明：物理AI开源评估工具，支持任意LLM/VLA在机械臂、人形机器人上的仿真与实物基准测试，填补了VLA统一评估的工具空白，本周新增多类操作任务评测集。
6. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐284 | 7天活跃
   说明：世界动作模型（World Action Model）的统一训练、微调、评估框架，为VLA研发提供标准化工具链，本周新增多类机器人操作任务的评估基准。
7. [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) ⭐37 | 7天活跃
   说明：带原生视频记忆的VLA模型，通过带时间戳的视觉历史与流式推理实现长时程机器人操作，是VLA长时序能力方向的最新探索。
8. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐624 | 7天活跃
   说明：全中文VLA领域实战/面试手册，聚焦机器人领域特有挑战，覆盖算法、工程、落地全流程，本周新增多类VLA部署相关内容。

---

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐3,400 | 7天活跃
   说明：全开源的人形机械臂项目，面向物理AI研究与接触富集环境部署，是近期人形操作硬件领域的热门开源项目，本周新增多项控制接口支持。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐551 | 7天活跃
   说明：机器人操作领域的基准测试平台，覆盖多类常见操作任务，为VLA操作能力的横向对比提供了标准化基准，本周新增多类接触-rich任务。
3. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐176 | 7天活跃
   说明：CVPR 2025入选论文的官方实现，通过LLM驱动仿真生成可泛化的指令跟随操作能力，为操作任务的数据扩增提供了新方案。
4. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐137 | 7天活跃
   说明：将自然语言指令编译为可验证的机器人技能图并执行的框架，提升了操作任务的可靠性与可解释性，是操作规划领域的新兴技术方向。
5. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐25 | 7天活跃
   说明：宇树科技TRON2操作臂的OpenPI部署分支，支持pi0/pi0.5策略的服务化部署与实物机器人运行，是VLA操作落地的代表性产业项目。
6. [artyomzifir/ViKi](https://github.com/artyomzifir/ViKi) ⭐9 | 7天活跃
   说明：仅用RGB-D相机即可采集人类操作演示、重定向到机器人并生成LeRobot格式数据集的工具，大幅降低了操作数据的采集门槛。

---

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,667 | 7天活跃
   说明：面向移动机器人的开源操作系统，当前已落地300+车型的辅助驾驶，是移动机器人导航控制领域生态最成熟的开源项目之一，本周持续迭代驾驶策略。
2. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,528 | 7天活跃
   说明：机器人算法的经典Python实现库，覆盖路径规划、SLAM、运动控制等全栈运动相关算法，是机器人开发者入门运动控制的首选资源。
3. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐705 | 7天活跃
   说明：地平线机器人推出的人形机器人全身控制基础模型，支持复杂场景下的全身运动生成，是产业界人形运动基础模型的代表性项目。
4. [RealXiaoze/humanoid-motion-intelligence](https://github.com/RealXiaoze/humanoid-motion-intelligence) ⭐553 | 7天活跃
   说明：中文人形机器人运动智能知识库，聚合论文、开源项目、产业动态与求职信息，反映了国内人形运动领域的社区活跃度快速提升。
5. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325 | 7天活跃
   说明：IHMC团队的开源机器人软件库，主打足式机器人步行动态控制与动量优化，是人形/足式运动控制领域的经典学术项目。
6. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐117 | 7天活跃
   说明：清华MARS实验室推出的多模态人形运动生成模型，支持文本、语音等多模态指令驱动的全身运动生成，是人形运动多模态交互的最新探索。

---

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,861 | 7天活跃
   说明：ICML 2026入选论文的官方代码库，主打机器人数字孪生技术，为sim2real落地提供了高保真的孪生训练环境，本周新增多类机器人模型支持。
2. [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core) ⭐2,341 | 7天活跃
   说明：递归自改进的物理Agent操作系统，通过Agent工作流实现机器人能力的持续迭代，是具身智能系统架构方向的前沿探索项目。
3. [Phyzicalorg/Phyzical_org](https://github.com/Phyzicalorg/Phyzical_org) ⭐311 | 7天活跃
   说明：基于浏览器的遥操作数据采集平台，可生成elizaOS兼容的具身训练数据，为解决具身智能数据稀缺问题提供了众包采集的新思路。
4. [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐203 | 7天活跃
   说明：统一的机器人控制CLI工具，支持人形、机械臂、移动机器人等多类硬件的自然语言控制，兼容主流LLM与ROS生态，降低了多机器人协同的落地门槛。
5. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐160 | 7天活跃
   说明：无ROS依赖的轻量sim2real框架，支持VLA模型与RL策略的训练到实物部署全流程，原生兼容MuJoCo与多类主流机械臂，本周新增人形机器人支持。
6. [FastCrest/tether](https://github.com/FastCrest/tether) ⭐84 | 7天活跃
   说明：边缘到云的AI部署CLI工具，支持Jetson、RTX、Apple Silicon等多类硬件的VLA模型优化与部署，是具身智能边缘落地的重要工具。

---

## 趋势信号分析
本周具身智能社区关注核心集中在**VLA全链路工具链补全**与**人形机器人落地支撑**两大方向：其中VLA评估工具、操作数据采集、长时程记忆机制类项目活跃度环比提升显著，反映行业正从“拼模型精度”转向“补落地短板”。

新兴技术栈方面，**无ROS依赖的轻量sim2real框架**首次批量进入活跃榜，这类框架主打轻量化、易部署，适配中小团队的VLA落地需求，打破了ROS一统机器人开发的传统格局；基于技能图的可验证操作规划、原生带记忆的VLA架构等方向也有新项目涌现，代表了下一代具身智能的探索方向。

行业关联上，近期特斯拉Optimus量产进展、宇树科技发布TRON2操作臂等事件，直接带动了操作硬件、VLA部署、人形运动控制类项目的热度，ICML/CoRL等顶会成果的开源速度明显加快，产学协同效应凸显。

---

## 社区关注热点
- **VLA长时程记忆能力（[OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA)）**：当前VLA普遍存在时序记忆短、无法处理长周期任务的痛点，原生视频记忆+流式推理的方案为长时程操作任务提供了新思路，是下一代VLA的核心竞争点。
- **无ROS轻量sim2real框架（[RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)）**：ROS生态虽成熟但复杂度高，轻量框架大幅降低了VLA从仿真到实物的部署门槛，适合中小团队快速验证具身应用，是近期落地工具的核心方向。
- **开源人形操作硬件（[enactic/openarm](https://github.com/enactic/openarm)）**：具身智能落地离不开低成本硬件载体，全开源的人形机械臂可降低操作研究的硬件门槛，配合VLA模型可快速实现接触富集任务的验证，有望成为操作领域的标准硬件底座。
- **VLA统一评估工具（[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)）**：当前VLA模型缺乏统一评估标准，该工具支持多硬件、多基准的统一测试，是VLA研发必备的基础设施，有望成为领域事实标准。
- **中文VLA学习生态（[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)、[VLA-Handbook](https://github.com/sou350121/VLA-Handbook)）**：国内具身智能人才缺口大，体系化的中文入门资源可帮助开发者快速进入赛道，反映国内社区的参与度与生态成熟度正在快速提升。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*