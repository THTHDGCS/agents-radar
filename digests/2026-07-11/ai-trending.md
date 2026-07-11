# AI 开源趋势日报 2026-07-11

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-11 01:27 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-11）

---

## 今日速览
1. 今日具身智能领域最大亮点为Agent技能生态爆发，3款标准化技能框架今日新增stars均破千，可复用、跨平台的技能正在成为具身智能落地的核心基建；
2. 数字具身应用迎来破圈，专为AI agent打造的Office操作套件OfficeCLI今日新增1224星，验证了办公、桌面等非物理场景的具身操作需求；
3. VLA全链路基础设施持续完善，从本地记忆模块、技能标准到入门教程均出现成熟开源项目，开发者参与门槛进一步降低；
4. 人形机器人工具链迭代加速，开源机械臂、专用运行时、仿真框架等项目活跃度持续提升，物理AI落地的底层支撑逐步完备。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、中间件）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,156
   通用多关节接触物理仿真引擎，是机器人学习、VLA训练的核心底层仿真工具，长期占据机器人仿真赛道的核心地位。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,651
   基于NVIDIA Isaac Sim构建的统一机器人学习框架，支持人形、机械臂等多类型机器人的仿真训练，是当前sim2real的主流工具。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,837
   数据流导向的机器人中间件，提供低延迟、可组合、分布式的数据流转能力，大幅简化AI机器人应用的开发与部署。
4. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,183
   基于NVIDIA Warp构建的GPU加速物理仿真引擎，专门面向机器人学家与仿真研究者，针对接触富集场景做了专项优化。
5. [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) ⭐2,510
   模块化机器人学习仿真框架与基准，提供标准化的操纵任务环境，是VLA策略评估的主流基准平台。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124
   无ROS依赖的轻量化sim2real框架，原生支持VLA模型与RL agent部署到Franka、UR5e等主流机械臂，降低落地门槛。

### 🧠 VLA/基础模型（视觉-语言-动作、智能体基建、世界模型）
1. [mattpocock/skills](https://github.com/mattpocock/skills) ⭐今日+1,712
   面向Claude的生产级工程技能集合，直接复用成熟开发者的工作流配置，是当前数字具身agent最热门的技能插件。
2. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) ⭐今日+1,116
   生产级AI编码agent技能库，符合Agent Skills开放标准，支持多agent平台调用，是VLA技能编排层的核心基建。
3. [obra/superpowers](https://github.com/obra/superpowers) ⭐今日+1,013
   端到端的agent技能框架与软件开发方法论，支持智能体自主完成复杂软件工程任务，为具身智能的任务规划提供了可落地范式。
4. [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) ⭐今日+123
   完全本地化的AI agent四层长期记忆架构，零外部API依赖，解决了具身智能长任务执行的核心记忆痛点。
5. [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) ⭐今日+117
   基于MCP协议的Agent技能库，兼容Claude Code、Gemini CLI、Cursor等多平台，推动VLA技能接口走向标准化。
6. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐372
   全中文实战导向的VLA学习/面试手册，聚焦机器人领域特有挑战，覆盖算法、部署全流程，是国内开发者入门VLA的首选资源。
7. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,074
   面向具身智能与Agent AI的强化学习基础设施，提供标准化的VLA训练、评估pipeline，大幅降低基础模型的研发门槛。

### 🦾 操作与抓取（灵巧操纵、抓取生成、VLA操纵策略）
1. [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) ⭐今日+1,224
   全球首个专为AI agent打造的Office操作套件，开源免费、单二进制部署、无需Office安装，支持agent自主读写编辑Word/Excel/PPT，是数字具身操作领域的爆火项目。
2. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐482
   统一理解、生成、动作能力的机器人操纵VLA模型，在接触富集任务上表现优异，是国内开源VLA的代表性成果。
3. [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) ⭐60
   RSS 2026最新成果，通过通用姿态预训练提升VLA操纵策略的泛化性，在跨场景、跨物体任务上实现显著效果提升。
4. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐168
   CVPR 2025成果，LLM驱动的操纵仿真生成框架，自动生成多样化的训练场景，大幅提升VLA的指令遵循泛化能力。
5. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐57
   将自然语言指令编译为类型验证的机器人技能图，支持直接部署到仿真或真实机器人，解决了VLA任务执行的可靠性问题。

### 🚶 运动与导航（足式/人形机器人、SLAM、路径规划）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,070
   全球落地最广的开源机器人操作系统，当前支持300+车型的高级驾驶辅助，是移动机器人导航领域的标杆项目。
2. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,707
   完全开源的人形机械臂，面向物理AI研究与接触富集场景部署，大幅降低了人形机器人操纵硬件的研发门槛。
3. [softmata/horus](https://github.com/softmata/horus) ⭐388
   Rust编写的低延迟机器人运行时，定位为“机器人的Android系统”，专门针对人形机器人的高实时性控制需求做了优化。
4. [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐804
   面向足式机器人的IsaacLab工作流，简化人形机器人运动策略的仿真训练与部署，是足式机器人学习的核心工具。
5. [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐244
   ECCV 2026最新成果，基于动态高斯溅射的高保真导航仿真器，大幅提升了仿真环境与真实场景的域对齐效果。

### 📦 具身应用（sim2real、遥操作、落地部署）
1. [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) ⭐今日+328
   基于MCP协议的Claude桌面控制服务，赋予大模型终端操作、文件系统搜索、差异编辑能力，是数字具身落地桌面场景的核心工具。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,610
   面向零基础开发者的具身实践教程，仅需Python基础即可从零构建具身机器人，覆盖OpenVLA、Pi0等主流VLA模型的实现与部署。
3. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐101
   轻量化VLA部署框架，支持通过自然语言直接控制物理机器人与硬件，降低了VLA落地真实场景的门槛。
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐131
   轻量可扩展的人形机器人全身遥操作框架，支持低成本采集人形机器人的运动数据，降低了模仿学习的数据源门槛。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐3
   VLA/物理AI模型的通用评估框架，一次定义基准即可在任意机器人或仿真环境运行，解决了VLA评估碎片化的痛点。

---

## 趋势信号分析
今日开源社区最显著的趋势是**Agent技能生态与数字具身赛道的爆发性增长**，4款相关项目今日新增stars破千，是近期具身智能领域少有的破圈热度。新兴技术栈方面，Anthropic推出的MCP（模型上下文协议）首次成为批量登榜的技术标准，基于MCP的技能框架、桌面控制工具正在成为具身智能的通用接口层，有望统一数字与物理场景的具身能力调用标准。
行业联动上，本次热度直接受益于上周Anthropic正式发布Claude 3.5 Sonnet的桌面控制能力与MCP生态推广，同时近期OpenVLA、Pi0等开源VLA模型的普及，也带动了开发者对标准化技能、部署工具、入门资源的需求上涨，人形机器人产业链的融资热则进一步推高了运行时、硬件开源项目的关注度。

---

## 社区关注热点
- 【MCP技能生态】基于Model Context Protocol的标准化技能库，理由：今日3款相关项目新增破千，跨平台、可复用的技能正在替代定制化开发，成为具身智能落地的核心抓手，兼容MCP的技能将成为未来VLA的核心能力模块。
- 【数字具身落地】面向办公、桌面场景的AI agent操作工具，理由：OfficeCLI、DesktopCommanderMCP等项目验证了数字场景的具身需求，无需硬件投入即可快速落地，商业化路径更清晰，是中小团队切入具身智能赛道的首选方向。
- 【VLA入门平权】全中文VLA学习资源、零基础实践项目，理由：VLA技术已从科研走向普惠，入门级资源快速补充，普通开发者无需高端GPU或机器人硬件即可参与VLA开发，社区参与度将快速提升。
- 【人形机器人专用runtime】低延迟机器人操作系统项目，理由：人形机器人对实时性、可靠性的要求远高于传统软件，HORUS等专用runtime的出现填补了行业空白，有望成为下一代物理AI的基础软件层。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*