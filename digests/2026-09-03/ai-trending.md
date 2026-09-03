# AI 开源趋势日报 2026-09-03

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-03 01:54 UTC

---

# 具身智能与机器人开源趋势日报（2026-09-03）
---

## 今日速览
1. 今日GitHub总Trending榜单暂无具身智能、机器人领域的相关项目，核心热度集中在7天活跃的垂直主题仓库，VLA垂直化落地、人形机器人运动控制、下一代机器人软件栈是三大核心方向。
2. NVIDIA连续开源Alpamayo 1/1.5两款10B参数推理型VLA模型，主打自动驾驶场景的因果链推理，印证大厂正加速推动VLA从通用实验室研究走向垂直领域落地。
3. Rust语言编写的机器人中间件、运行时项目，以及无ROS的轻量sim2real框架密集出现，显示社区正在探索摆脱ROS臃肿架构的下一代机器人软件栈。
4. 中文具身智能学习资源、垂直行业应用（如实验室自动化）仓库增长明显，反映国内开发者参与度快速提升，具身落地正从通用机器人向细分场景渗透。

---

## 各维度热门项目
（注：今日Trending无相关领域项目，以下为7天活跃主题仓库的总星数）

### 🤖 机器人框架/SDK（控制、仿真、规划、运动）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,883  
   业界最广泛使用的多关节接触动力学仿真器，是机器人学习、操作控制研究的基础工具，生态成熟度极高。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,027  
   基于NVIDIA Isaac Sim的统一机器人学习框架，支持VLA、RL等多种训练范式，是当前具身智能仿真训练的主流工具。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,913  
   Rust编写的数据流导向机器人中间件，主打低延迟、可组合、分布式能力，是下一代机器人系统架构的代表性项目。
4. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,578  
   基于NVIDIA Warp的GPU加速物理仿真引擎，专门针对机器人与仿真研究者优化，支持大规模并行仿真训练。
5. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,387  
   多模态机器人数据可视化与流式传输工具，支持视觉、点云、动作等多模态数据的调试与分析，是机器人开发的核心调试工具。
6. [softmata/horus](https://github.com/softmata/horus) ⭐431  
   Rust编写的高性能机器人运行时系统，定位为“机器人的Android”，主打极致低延迟，是新兴的机器人操作系统方向项目。
7. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐155  
   无ROS的轻量sim2real框架，原生支持VLA模型与RL代理的训练部署，覆盖Franka、xArm等多款主流机械臂，降低落地门槛。

### 🧠 VLA/基础模型（视觉-语言-动作、模仿/强化学习策略）
1. [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐2,013  
   NVIDIA开源的10B参数推理型VLA模型，面向自动驾驶场景，配对驾驶轨迹与因果链推理能力，是大厂垂直领域VLA的代表性成果。
2. [NVlabs/alpamayo1.5](https://github.com/NVlabs/alpamayo1.5) ⭐362  
   Alpamayo的升级版本，新增RL增强推理、导航引导、视觉问答能力，进一步提升自动驾驶场景的泛化性。
3. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐582  
   全中文实战导向的VLA学习/面试手册，聚焦机器人领域特有挑战，是国内开发者入门VLA的优质资源。
4. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐459  
   面向通用具身智能的开放世界基础模型，探索跨场景的具身通用能力。
5. [starVLA/VLAct](https://github.com/starVLA/VLAct) ⭐90  
   提出表征中心的VLA持续预训练范式，突破纯数据缩放的瓶颈，为VLA模型的性能提升提供新思路。
6. [dwipddalal/Anchor-Align](https://github.com/dwipddalal/Anchor-Align) ⭐31  
   VLA微调新方法，解决行为克隆导致的VLM预训练表征灾难性遗忘问题，已在物理xArm7机械臂上完成验证，落地性强。
7. [cau-hai-lab/LIBERO-Para](https://github.com/cau-hai-lab/LIBERO-Para) ⭐44  
   EMNLP 2026主会收录的VLA释义鲁棒性基准，填补了VLA语言理解鲁棒性评估的空白。

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,919  
   完全开源的人形机械臂，面向物理AI研究与接触富集场景部署，是当前最受关注的开源人形臂硬件项目。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐466  
   机器人操作领域的官方基准库，用于统一评估操作策略的泛化能力。
3. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐175  
   CVPR 2025收录工作，提出LLM驱动的仿真生成方法，提升通用指令跟随操作的泛化性。
4. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐68  
   开源双臂数据采集与重定向软件，支持适配任意双臂机器人，是操作数据收集的实用工具。
5. [RobotControlStack/duobench](https://github.com/RobotControlStack/duobench) ⭐17  
   双臂操作的可复现基准，同时支持仿真与真实世界评估，填补双臂操作标准化评估的空白。
6. [PINE-Lab-NTU/FACET](https://github.com/PINE-Lab-NTU/FACET) ⭐5  
   刚发布的接触富集精细操作机器人基础模型（arXiv 2609.01596），是精细操作方向的最新进展。

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,554  
   全球最热门的开源机器人操作系统之一，目前已落地于300+车型的辅助驾驶，是自主导航领域的标杆项目。
2. [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) ⭐5,246  
   开源四足机器人宠物框架，兼容波士顿动力风格的四足控制，适合DIY、教育与研究使用。
3. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325  
   经典腿足运动算法库，支持人形机器人、外骨骼、奔跑机器人等多种平台的运动控制。
4. [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx) ⭐273  
   基于JAX的模型预测控制库，为机器人运动控制提供高性能、可微分的实现，JAX在机器人领域的应用是新兴趋势。
5. [purdue-tracelab/PACE-ICRA2026](https://github.com/purdue-tracelab/PACE-ICRA2026) ⭐81  
   ICRA 2026收录工作，提出物理增强的端到端RL方法，实现人形机器人的乒乓球任务，是人形复杂运动控制的新进展。
6. [limxdynamics/humanoid-mujoco-sim](https://github.com/limxdynamics/humanoid-mujoco-sim) ⭐10  
   国产LimX人形机器人的MuJoCo仿真环境，支持sim2real训练与策略评估，是国内人形机器人开源生态的重要组成。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,706  
   面向具身与Agent AI的强化学习基础设施，覆盖从训练到部署的全流程，是具身智能落地的核心基础设施项目。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,492  
   中文社区热门的具身智能入门教程，仅需Python基础即可从0构建VLA/OpenVLA等模型，降低了具身智能的学习门槛。
3. [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core) ⭐2,013  
   递归自我改进的物理Agent操作系统，通过Agent工作流实现能力的自我迭代，是具身智能操作系统的前沿探索。
4. [FastCrest/tether](https://github.com/FastCrest/tether) ⭐83  
   边缘到云的AI部署CLI工具，支持Jetson、RTX、苹果硅等多平台，解决具身模型的边缘部署痛点。
5. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐54  
   机器人辅助化学实验室自动化的数字孪生平台，是具身智能在垂直行业落地的典型案例。
6. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐146  
   基于Strands Agents的自然语言机器人控制方案，支持通过自然语言直接控制物理硬件，降低机器人的使用门槛。

---

## 趋势信号分析
近期具身智能开源社区呈现三大明确趋势：一是VLA进入垂直落地爆发期，以NVIDIA Alpamayo系列为代表的垂直领域VLA模型密集开源，配套的微调方法、鲁棒性基准、细分场景框架同步完善，VLA正从通用演示转向自动驾驶、工业操作等真实场景。二是下一代机器人软件栈雏形显现，Rust凭借内存安全、高性能优势，成为机器人中间件（dora）、运行时（horus）的首选开发语言，无ROS的轻量sim2real框架也获得中小团队青睐，逐步挑战ROS的主流地位。三是国内具身生态加速成熟，中文教程、开源硬件、行业应用项目快速增长，与近期国内人形机器人量产、具身智能创业热潮高度呼应。（全文287字）

---

## 社区关注热点
- **NVIDIA Alpamayo系列VLA模型**：大厂开源的10B级推理型VLA，首次将因果链推理与驾驶轨迹结合，是垂直领域VLA的标杆性成果，对研究VLA的推理能力、落地自动驾驶场景有重要参考价值。
- **dora-rs/dora数据流中间件**：Rust编写的下一代机器人中间件，星数近4k，主打低延迟、分布式、可组合的数据流架构，是探索新型机器人系统架构的核心参考项目。
- **datawhalechina/every-embodied中文教程**：国内最热门的具身智能实战教程，从0搭建VLA模型，星数突破3.4k，极大降低了国内开发者入门具身智能的门槛。
- **无ROS轻量sim2real框架**：以robot-control-stack为代表，摆脱ROS的复杂度与冗余，原生支持VLA/RL训练部署，是中小团队快速落地具身机器人的高性价比选择。
- **enactic/openarm开源人形机械臂**：完全开源的人形臂硬件，面向接触富集场景，星数近3k，为物理AI研究提供了低成本的硬件平台，适合操作方向研究者与DIY爱好者关注。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*