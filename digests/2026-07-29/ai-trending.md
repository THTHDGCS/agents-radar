# AI 开源趋势日报 2026-07-29

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-29 01:25 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-29）
## 今日速览
今日具身智能与机器人开源领域呈现VLA工程化加速、消费级具身应用破圈的核心特征。VLA全链路工具密集上新，覆盖感知输入、微调部署、安全评测全流程，大厂与社区同步推进落地标准。低成本开源机器人硬件持续下探，7自由度机械臂、人形操作臂的开源方案大幅降低实体具身的开发门槛。中文具身智能入门资源集中释放，填补了国内VLA与机器人学习的实战教程空白。虚拟具身应用首次登上热榜前列，消费级具身场景的关注度快速提升。

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、中间件）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,249 面向机器人的通用操作系统，目前已支持300+车型的辅助驾驶升级，是移动机器人领域落地最成熟的开源OS项目。
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,359 通用多关节接触物理仿真器，是VLA与机器人学习领域最主流的仿真底座，长期保持社区高活跃度。
3. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,789 基于NVIDIA Isaac Sim构建的统一机器人学习框架，支持VLA训练、仿真到部署全流程，是当前工业级具身学习的首选框架之一。
4. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,856 数据流驱动的机器人中间件，主打低延迟、可组合、分布式特性，大幅简化AI机器人应用的开发流程，近期社区增速明显。
5. [softmata/horus](https://github.com/softmata/horus) ⭐396 号称“机器人界的Android”的高性能机器人运行时系统，主打低延迟调度，为人形与工业机器人提供统一 runtime 底座。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐125 无ROS依赖的VLA/RL机器人部署框架，原生支持MuJoCo与主流机械臂、人形机器人，解决了ROS栈在具身部署中的冗余问题。

### 🧠 VLA/基础模型（视觉-语言-动作、具身基础模型、学习策略）
1. [bradautomates/claude-video](https://github.com/bradautomates/claude-video) ⭐0 (+988 today) 今日热榜新增Star第一的项目，为大模型提供端到端视频解析能力，支持帧提取、语音转录，是VLA多模态感知的轻量化工具，解决了大模型无法直接处理长视频的痛点。
2. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐451 国内首份全中文、实战导向的VLA学习/面试手册，聚焦机器人领域特有挑战，填补了中文VLA入门资源的空白，近期获得国内开发者大量关注。
3. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐92 开源物理AI评测工具，支持任意LLM/VLA在任意机械臂、人形机器人的仿真/真实环境基准测试，统一了VLA落地前的评测标准。
4. [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) ⭐83 NVIDIA官方推出的Alpamayo VLA开发者工具包，提供微调、RL后训练、量化、部署的开箱即用方案，代表了大厂VLA工程化的最新方向。
5. [phi-monster/Galahad](https://github.com/phi-monster/Galahad) ⭐79 针对VLA指令失明问题的完整解决方案，包含论文、模型、去混淆数据集与测试套件，解决了VLA落地中常见的指令理解失效问题。
6. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,906 面向零基础开发者的具身智能教程，从Python基础到从零构建VLA/OpenVLA，大幅降低了具身智能的入门门槛，国内社区热度极高。

### 🦾 操作与抓取（灵巧手、操作基准、硬件方案）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,780 完全开源的人形机械臂，面向物理AI研究与接触富集任务部署，提供开源硬件+软件全套方案，大幅降低了灵巧操作的硬件门槛。
2. [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,165 GPU并行化机器人操作仿真基准，支持灵巧操作、抓取等任务的大规模VLA/RL训练，是目前操作领域最常用的基准平台之一。
3. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐42 开源双臂数据采集工具，支持同步采集、动作重定向到任意双臂机器人，解决了VLA操作训练的数据采集痛点。
4. [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8 面向VLA的双臂厨房操作基准，基于Inspect Robots构建，是首个面向家用场景的复杂操作VLA评测基准。
5. [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐7 IROS 2026最新录用的轻量VLA模型，基于Mamba架构仅179M参数即可实现机器人操作任务，适合边缘部署。
6. [shritankomm/7-DOF-3DP-Open-Arm](https://github.com/shritankomm/7-DOF-3DP-Open-Arm) ⭐1 成本低于800美元的开源7自由度3D打印机械臂，支持ROS2与视觉控制，为个人开发者提供了极低门槛的操作硬件方案。

### 🚶 运动与导航（足式、人形、移动机器人、路径规划）
1. [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover) ⭐9,545 NASA JPL开源的6轮火星车复刻项目，包含完整的硬件设计与软件栈，是移动机器人导航与运动控制的经典参考项目。
2. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,519 ROS2官方导航框架，支持路径规划、避障、定位全流程，是移动机器人领域应用最广泛的导航方案。
3. [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐351 面向人形机器人全身的非线性MPC控制器，支持实时运动-操作规划，是人形机器人运动控制的最新成熟开源方案。
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐139 轻量级可扩展的人形机器人全身遥操作框架，解决了人形机器人数据采集与远程控制的痛点。
5. [Yhx888/LocoVLA](https://github.com/Yhx888/LocoVLA) ⭐5 面向Upkie轮足机器人的开源VLA课程，包含58节课，覆盖经典控制、RL、VLA、ROS2部署全流程，填补了轮足VLA教学资源的空白。
6. [THMOS2025/MOS-9-Open-Source-Humanoid-Robot](https://github.com/THMOS2025/MOS-9-Open-Source-Humanoid-Robot) ⭐17 RoboCup KidSize开源人形机器人项目，包含硬件、部署、仿真、策略学习全套方案，是人形机器人入门的完整参考。

### 📦 具身应用（sim2real、遥操作、自主系统、消费级应用）
1. [moeru-ai/airi](https://github.com/moeru-ai/airi) ⭐0 (+797 today) 今日热榜新增Star第二的项目，自托管的虚拟具身伴侣，支持实时语音交互、Minecraft/Factorio游戏环境操作，目标达到Neuro-sama的水平，是虚拟具身应用破圈的代表性项目。
2. [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3,424 开源AI助手生态，支持MCP协议、多模态工作流、IoT控制、跨平台语音交互，是消费级具身应用的成熟开源方案。
3. [huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech) ⭐0 (+227 today) HuggingFace推出的开源本地语音agent构建工具，支持端侧部署，为具身机器人的语音交互提供了开箱即用的方案。
4. [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) ⭐0 (+46 today) 微软推出的AI Agent治理工具包，覆盖10/10 OWASP Agentic Top10风险，支持策略执行、零信任身份、沙箱执行，为具身自主agent的安全落地提供了标准方案。
5. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,223 自进化具身AI操作系统，基于agent工作流构建，支持具身agent的自主迭代与环境交互，是具身OS方向的前沿探索项目。
6. [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8 基于Strands Agent的VLA控制漫游车，支持视觉-语言-动作全链路，包含公开数据集，是VLA在移动机器人落地的最小实践案例。

## 趋势信号分析
今日开源社区核心热度集中在VLA工程化落地与具身应用破圈两大方向。其一，VLA全链路生态工具出现爆发式增长，从视频感知输入、模型微调、安全测试到统一评测的工具密集登榜，其中NVIDIA官方Alpamayo VLA开发套件、面向VLA的红队测试工具Provael均为首次公开，标志VLA已从学术研究进入工业落地的工程化阶段。其二，虚拟具身应用首次跻身GitHub热榜前列，支持实时交互、虚拟环境操作的Airi项目单日新增近800星，反映具身智能的落地场景正从工业机器人向消费级虚拟/实体助手延伸。此外，微软推出的Agent治理工具覆盖OWASP Agentic全量风险点，与近期全球AI监管收紧、具身机器人安全标准制定的行业动向高度契合。

## 社区关注热点
- 🔥 VLA全链路工具链成型：今日新增的视频输入工具、微调套件、评测框架、安全测试工具覆盖了VLA落地的所有核心环节，开发者可基于现有工具快速搭建生产级VLA应用，无需从零构建基础设施。
- 📚 中文具身入门资源集中释放：包括VLA中文手册、零基础具身构建教程、轮足VLA公开课在内的中文资源密集上线，大幅降低了国内开发者进入具身智能领域的门槛，适合新手系统学习。
- 🦾 低成本开源操作硬件下探：从成本800美元的7自由度3D打印臂到完全开源的人形臂OpenArm，开源硬件的成本下探使得个人开发者与小型团队也能开展灵巧操作与VLA的实体测试，无需依赖昂贵的工业机械臂。
- 🛡️ 具身Agent安全成为新焦点：微软的Agent治理工具、具身安全综述、VLA红队测试工具同步出现，反映具身智能的安全问题已从学术讨论进入落地前的标准制定阶段，相关技术栈将成为未来半年的热点方向。
- 🎮 虚拟具身消费场景破圈：Airi等虚拟具身伴侣项目的高热度显示，具身智能的消费级场景正在打开，虚拟环境下的交互、操作能力将成为继工业机器人之后的另一个具身落地蓝海。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*