# AI 开源趋势日报 2026-07-20

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-20 01:52 UTC

---

# 具身智能与机器人开源趋势日报
**日期：2026-07-20**

---

## 今日速览
今日具身智能与机器人开源社区核心热度集中在VLA落地工具链、人形机器人基础能力两大方向，中文VLA系统化学习资源与低成本开源人形硬件获得开发者持续关注。NVIDIA Isaac生态的衍生训练与部署项目持续增多，无ROS的轻量化sim2real方案成为社区新的创新热点，适配AI开发者的落地需求。跨平台通用VLA评测框架首次出现，大幅降低了VLA模型的迭代与验证成本。数字具身（计算机使用）基准平台登上今日GitHub热榜，预示具身智能的落地场景正在从物理机器人向通用数字代理拓展。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、运动）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14260  
   通用多关节接触物理仿真引擎，是机器人动力学仿真的事实标准，支撑绝大多数VLA与RL策略的仿真训练。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7706  
   基于NVIDIA Isaac Sim的统一机器人学习框架，原生支持人形、机械臂等多形态机器人的仿真训练与sim2real迁移，是当前VLA开发的核心基础设施。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3845  
   数据流导向的开源机器人中间件，低延迟、可组合的分布式架构适配AI原生机器人的开发需求，大幅简化多模态具身系统的搭建。
4. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4485  
   ROS 2生态的官方导航框架，支持路径规划、避障、定位等全链路移动机器人导航能力，是工业级移动机器人的核心组件。
5. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5214  
   基于NVIDIA Warp的GPU加速物理仿真引擎，专门面向机器人研究者优化，适合大规模并行的机器人学习任务。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124  
   无ROS的轻量化sim2real部署框架，原生支持VLA模型与RL策略的端到端部署，适配Franka、xArm、SO101等主流机器人硬件，降低AI开发者的落地门槛。

---

### 🧠 VLA/基础模型（视觉-语言-动作、模仿学习、强化学习策略）
1. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐404  
   国内首份全中文、实战导向的VLA学习与面试手册，聚焦机器人领域特有挑战，覆盖从入门到落地的全流程知识，填补了中文VLA系统化资料的空白。
2. [Open-X-Humanoid/XR-1](https://github.com/Open-X-Humanoid/XR-1) ⭐186  
   面向人形机器人的通用VLA模型，通过学习统一的视觉-运动表征实现多任务跨场景的机器人控制，是人形VLA领域的重要进展。
3. [trycua/cua](https://github.com/trycua/cua) ⭐0 (+64 今日新增)  
   今日Trending上榜的计算机使用2.0开源平台，提供跨OS驱动、集群管理与训练评测基准，支撑数字具身代理的规模化开发与验证。
4. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2746  
   面向Python基础开发者的具身智能入门教程，从零讲解OpenVLA、SmolVLA等主流模型的构建与部署，是社区热度最高的具身入门资源之一。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐8  
   通用VLA/物理AI模型评测框架，支持一次定义基准、跨多类机器人与仿真环境运行，大幅降低VLA模型的验证成本。
6. [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐116  
   覆盖500+论文的具身AI安全综述，涵盖感知、认知、规划、Agent系统等全链路安全风险与攻防方案，是VLA安全领域的核心参考资料。

---

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2739  
   完全开源的人形机械臂，面向接触富集任务的物理AI研究与部署，提供标准化的硬件接口与仿真模型，是VLA物理落地的核心低成本硬件载体。
2. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐506  
   统一理解、生成、动作能力的机器人操作VLA模型，支持复杂场景下的多步操作任务，是国内开源VLA操作模型的代表性工作。
3. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐262  
   官方机器人操作基准平台，覆盖多类接触富集操作任务，支撑操作策略的统一训练与评测。
4. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐77  
   将自然语言指令编译为可验证的机器人技能图的框架，解决VLA模型在长时序操作任务中的可靠性问题。
5. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐19  
   开源双手操作数据采集与重靶向软件，支持多传感器同步采集与跨机器人的动作重定向，降低操作数据的采集成本。
6. [RoboTwin-Platform/RMBench](https://github.com/RoboTwin-Platform/RMBench) ⭐172  
   基于数字孪生的记忆依赖操作基准，面向长时序复杂操作任务的评测，填补了操作任务中记忆能力评测的空白。

---

### 🚶 运动与导航（足式、人形、SLAM、路径规划）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63167  
   目前落地规模最大的开源具身智能系统，作为机器人操作系统支持300+车型的高级辅助驾驶升级，验证了具身智能在移动场景的落地可行性。
2. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐588  
   全身人形控制基础模型，支持人形机器人的多模态运动生成与控制，是人形运动控制领域的重要基础模型工作。
3. [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐819  
   面向足式机器人的IsaacLab直接工作流，简化足式机器人的仿真环境搭建与策略训练，降低足式机器人的开发门槛。
4. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15509  
   最广泛应用的开源移动机器人控制固件，支持无人机、无人车、无人船等多类移动机器人的运动控制，是工业级移动机器人的核心底层软件。
5. [MichaelGrupp/evo](https://github.com/MichaelGrupp/evo) ⭐4280  
   SLAM与里程计评估的Python工具包，支持多类SLAM算法的精度评估，是移动机器人感知开发的事实标准工具。
6. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐92  
   清华MARS实验室开源的多模态人形运动生成模型，支持通用人形机器人的跨场景运动控制，是人形运动生成的前沿工作。

---

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐103  
   支持自然语言控制机器人硬件的Agent框架，封装了VLA模型与硬件驱动的适配层，开发者可通过简单的自然语言指令控制物理机器人。
2. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐132  
   轻量可扩展的人形机器人全身遥操作框架，支持多类输入设备与跨硬件平台的动作重定向，是人形机器人数据采集与远程控制的核心工具。
3. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐770  
   自进化具身AI操作系统，基于Agent工作流架构，支持VLA模型的动态迭代与物理硬件的适配，面向具身智能的规模化落地。
4. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2601  
   开源机器人数字孪生平台2.0，支持高保真物理仿真与sim2real迁移，降低机器人策略的物理落地风险。
5. [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3414  
   开源具身AI助手生态，支持多模态交互、IoT设备控制与MCP协议集成，是面向家庭场景的具身助手的代表性开源项目。

---

## 趋势信号分析
今日社区数据显示，VLA落地工具链与人形机器人基础技术正获得爆发性关注，尤其是面向中小开发者的轻量化部署方案、中文入门资源的增速显著。新兴技术栈方面，无ROS的sim2real部署框架成为重点创新方向，相比传统ROS生态更适配VLA模型的端到端训练与部署需求，降低了非机器人背景AI开发者的落地门槛。
结合近期OpenVLA、SmolVLA等小参数开源VLA模型的普及，社区正从“VLA算法创新”向“VLA落地工具链完善”过渡，而低成本开源人形硬件的涌现，也为VLA的物理落地提供了更广泛的测试载体。此外，数字具身基准平台登榜，与近期大模型厂商集中发布计算机使用能力的行业动向形成呼应，反映出具身智能的边界正在从物理机器人向通用智能代理拓展。

---

## 社区关注热点
- 👉 [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook)：国内首份实战导向的中文VLA学习手册，覆盖从入门到面试的全流程知识，填补了中文VLA系统化资料的空白，适合算法工程师快速入局具身智能领域。
- 👉 [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)：无ROS的轻量化VLA/RL部署框架，适配主流机械臂与人形硬件，大幅降低AI开发者从模型到物理机器人的落地门槛，是近期sim2real领域的核心创新方向。
- 👉 [enactic/openarm](https://github.com/enactic/openarm)：完全开源的低成本人形机械臂，面向接触富集任务的研究与部署，为VLA模型的物理验证提供了标准化的硬件载体，适合小团队与个人研究者使用。
- 👉 [trycua/cua](https://github.com/trycua/cua)：今日登上GitHub热榜的数字具身基准平台，支撑计算机使用代理的规模化训练与评测，预示具身智能的落地场景正在向数字世界拓展，值得提前布局。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*