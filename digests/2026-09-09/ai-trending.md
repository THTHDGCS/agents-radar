# AI 开源趋势日报 2026-09-09

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-09 01:58 UTC

---

# 具身智能与机器人开源趋势日报
**日期：2026年9月9日**

## 今日速览
今日GitHub总热榜无具身智能、机器人与VLA领域直接相关项目入榜，领域热度集中在主题社区的开源生态更新。世界动作模型（WAM）成为VLA方向新的聚焦点，本周内多个WAM相关的资源合集、训练框架、开源项目密集发布，显示具身基础模型正从单模态VLA向世界模型+动作的融合方向演进。人形机器人开源生态持续扩容，覆盖从低成本3D打印DIY平台、运动控制运行时到全身VLA控制方案的全栈链路。具身AI的垂直落地场景也在拓展，出现了面向化学实验室自动化的数字孪生机器人平台，验证了具身技术在科研场景的落地潜力。

## 各维度热门项目
> 注：今日GitHub Trending总榜无符合筛选条件的具身智能/机器人/VLA项目，以下项目均为7天内活跃的主题社区项目，stars为总存量数据。

### 🤖 机器人框架/SDK（控制、仿真、规划、中间件）
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,080
   基于NVIDIA Isaac Sim的统一机器人学习框架，支持从仿真训练到实机部署的全流程，是当前具身智能仿真训练的主流底座之一，本周持续活跃更新。
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,926
   数据流导向的开源机器人中间件，主打低延迟、可组合、分布式部署，为AI原生机器人应用提供轻量化的架构替代方案，近期社区增长迅速。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,000
   DeepMind开源的多刚体接触动力学仿真器，是机器人学习、操作与运动控制领域的事实标准仿真工具，本周仍保持高频更新。
4. [softmata/horus](https://github.com/softmata/horus) ⭐434
   号称“机器人界Android”的高性能运行时系统，主打极速机器人运动控制，面向人形机器人等复杂硬件场景，本周获得大量开发者关注。
5. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐157
   无ROS依赖的轻量化sim2real框架，原生支持VLA模型与RL策略部署，兼容Franka、UR5e、xArm等主流机械臂，为中小团队提供了更简洁的部署选择。
6. [Hebbian-Robotics/hflow](https://github.com/Hebbian-Robotics/hflow) ⭐253
   专门面向机器人AI训练的数据质量验证SDK，填补了具身数据质量管理的工具空白，帮助团队提升模仿学习/RL的训练效率。

### 🧠 VLA/基础模型（视觉-语言-动作、世界模型、学习策略）
1. [TianxingChen/Embodied-AI-Guide](https://github.com/TianxingChen/Embodied-AI-Guide) ⭐15,873
   Lumina具身智能社区出品的具身智能技术指南，是国内最高星的具身领域资源合集，覆盖算法、硬件、产业全维度，本周持续更新。
2. [OpenMOSS/Awesome-WAM](https://github.com/OpenMOSS/Awesome-WAM) ⭐1,392
   全球首个系统梳理世界动作模型（WAM）的资源列表，覆盖论文、解读、具身AI相关项目，是当前WAM方向最全面的入门索引，本周增长迅猛。
3. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,601
   面向零基础开发者的具身智能实践教程，从Python基础到构建VLA/OpenVLA/SmolVLA/Pi0全链路，是国内最受欢迎的具身入门项目。
4. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐601
   全中文VLA领域实战导向学习/面试手册，聚焦机器人特有挑战而非通用CV/NLP，是国内开发者入门VLA的热门垂直资源。
5. [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) ⭐168
   NVIDIA官方Alpamayo VLA模型的开发者Hub，提供微调、RL后训练、量化、部署的开箱即用配方，标志着大厂正加速VLA的工程化落地。
6. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐178
   世界动作模型（WAM）的统一训练、微调、评估框架，降低了WAM的研发门槛，与Awesome-WAM形成资源+工具的组合，本周同步更新。
7. [starVLA/VLAct](https://github.com/starVLA/VLAct) ⭐115
   提出表征中心的VLA持续预训练方法，跳出传统数据scaling路径，探索VLA性能提升的新方向，近期受到算法研究者关注。

### 🦾 操作与抓取（灵巧手、操作策略、双臂协同）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,936
   完全开源的人形机械臂，专为接触富集环境的物理AI研究与部署设计，是当前高星的开源操作硬件项目，本周持续活跃。
2. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐176
   CVPR 2025录用工作，提出LLM驱动的仿真生成方法，提升通用指令跟随操作的泛化能力，是操作领域大模型融合的代表性工作。
3. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐69
   双臂数据采集与重定向开源软件，支持将演示数据快速适配到任意双臂机器人，降低了操作数据采集的成本。
4. [CyanHaze/Awesome-Dexterous-Hands](https://github.com/CyanHaze/Awesome-Dexterous-Hands) ⭐24
   系统梳理灵巧手与操作领域的论文、数据集、仿真器、硬件平台的资源列表，填补了灵巧手方向垂直资源索引的空白。
5. [RobotControlStack/duobench](https://github.com/RobotControlStack/duobench) ⭐18
   双臂操作的可复现基准，覆盖仿真与真实世界，为双臂协同操作算法提供统一的评估标准，本周刚发布新版本。

### 🚶 运动与导航（人形、足式、SLAM、移动机器人）
1. [RealXiaoze/humanoid-motion-intelligence](https://github.com/RealXiaoze/humanoid-motion-intelligence) ⭐509
   国内开发者维护的人形机器人运动智能知识库，聚合论文、开源项目、产业动态与求职信息，是国内人形运动领域的热门资源站。
2. [Rhoban/microban](https://github.com/Rhoban/microban) ⭐312
   低成本、全3D打印、100%开源的人形机器人，基于树莓派Zero 2W和19个舵机，为DIY爱好者和教学场景提供了可及性极高的人形平台。
3. [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐178
   面向小型机器人的“大脑”系统，通过LLM连接底层运动技能，支持MicroDuck、LeRobot等多类平台，实现自然语言指令到动作的端到端执行。
4. [Open-X-Humanoid/BICMap](https://github.com/Open-X-Humanoid/BICMap) ⭐59
   WebGL驱动的机器人地图可视化SDK，支持SLAM地图、点云、3D模型与导航路径展示，为移动机器人前端交互提供轻量化方案。
5. [Renkunzhao/legged-daily](https://github.com/Renkunzhao/legged-daily) ⭐22
   足式机器人与基于学习的控制方向的研究资源合集，每日更新最新论文与代码，是足式运动研究者的实用信息源。

### 📦 具身应用（sim2real、垂直落地、物理Agent）
1. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,826
   ICML 2026录用的RoboTwin 2.0官方代码，打造具身AI数字孪生平台，支撑操作、导航等多类任务的sim2real研究。
2. [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core) ⭐2,118
   递归自改进的物理Agent操作系统，通过Agent工作流实现自我进化，是具身Agent系统架构的新探索。
3. [RobotecAI/rai](https://github.com/RobotecAI/rai) ⭐583
   厂商无关的物理AI机器人Agent框架，基于ROS2实现复杂动作执行、场景定义、语音交互等功能，可快速部署到不同品牌的机器人上。
4. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐55
   面向化学实验室自动化的机器人数字孪生平台，是具身AI在科研垂直场景的典型落地应用，本周获得产业界关注。
5. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐155
   基于Strands Agents的自然语言机器人控制方案，支持直接通过自然语言指令操控物理硬件，降低了非专业用户使用机器人的门槛。

## 趋势信号分析
本周具身智能开源领域最明确的爆发方向是**世界动作模型（WAM）**：从资源索引、训练框架到开源模型全链路涌现新项目，标志着VLA技术正从单步指令响应的“感知-动作”映射，向融合世界模型的长时序规划、环境推理演进，成为具身基础模型的新核心赛道。
新兴技术栈方面，原本面向通用AI Agent的**MCP（模型上下文协议）**开始渗透机器人领域，已有仿真器、技能框架兼容MCP标准，预示着机器人工具链将与通用Agent生态快速打通。
行业联动上，近期人形机器人产业融资热度持续传导至开源社区，低成本DIY平台、运动控制运行时项目密集更新；NVIDIA Alpamayo VLA官方开发者工具上线，也印证了大厂正加速VLA的工程化落地节奏。（全文约290字）

## 社区关注热点
- **[OpenMOSS WAM系列项目](https://github.com/OpenMOSS/Awesome-WAM)**：全球首个成体系的世界动作模型开源项目组，代表VLA的下一代演进方向，建议算法研究者重点跟踪WAM从预训练到落地的全链路技术路径。
- **[enactic/openarm 开源人形机械臂](https://github.com/enactic/openarm)**：2.9k高星的全开源操作硬件，填补了接触富集场景的低成本开源臂空白，为操作算法研究提供了可及性极高的实机验证平台。
- **[softmata/horus 机器人运行时系统](https://github.com/softmata/horus)**：主打“机器人界的Android”定位，瞄准人形机器人核心 runtime 性能痛点，若生态成型可能重塑机器人软件栈，值得工程团队重点关注。
- **[AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix)**：具身AI在化学实验室自动化场景的标杆落地项目，验证了具身技术的垂直商业化价值，关注产业落地的开发者可跟踪其应用进展。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*