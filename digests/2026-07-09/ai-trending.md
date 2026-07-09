# AI 开源趋势日报 2026-07-09

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-09 01:49 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-09）

---

## 今日速览
今日具身智能领域爆发性关注集中在**AI代理的端侧基础设施与工具链**，OfficeCLI、CubeSandbox等项目单日涨星超500，核心需求是降低具身代理从纯对话向实体/数字交互落地的门槛。VLA方向的平民化趋势明显，出现了面向8GB消费级显卡的基准、全中文VLA学习手册等资源，覆盖从入门到前沿研究的全链条需求。人形机器人开源生态持续完善，从全开源机械臂、轻量遥操作框架到低成本入门级硬件均有活跃更新，sim2real工具链逐步成熟。非视觉感知方案获得社区关注，RuView利用WiFi信号实现空间感知，为具身机器人提供了低成本、隐私友好的感知新路径。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、中间件、基础设施）
1. [TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox) ⭐0 (+564 today)：面向AI代理的瞬时、并发、轻量安全沙箱，实现代理执行环境的隔离与权限管控，是具身代理安全落地的核心基础设施，今日涨星突出。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7632：基于NVIDIA Isaac Sim的统一机器人学习框架，是当前VLA模型训练与sim2real验证的主流仿真底座，7天内持续活跃更新。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3833：数据流导向的AI机器人中间件，提供低延迟、可组合的分布式数据流转能力，大幅简化具身智能应用的开发流程，近期社区活跃度快速上升。
4. [alibaba/zvec](https://github.com/alibaba/zvec) ⭐0 (+395 today)：轻量级高速进程内向量数据库，可作为具身代理的本地长期记忆底座，无需外部服务依赖，适合边缘端具身设备部署，今日涨星显著。
5. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14135：全球应用最广的多关节接触物理仿真器，是机器人学习、VLA训练的核心基础设施，本周新增多项GPU加速优化。
6. [softmata/horus](https://github.com/softmata/horus) ⭐386：面向机器人的高性能运行时系统，定位为机器人领域的Android，统一机器人硬件抽象层，降低跨硬件部署难度。

---

### 🧠 VLA/基础模型（视觉-语言-动作、模仿学习、世界模型）
1. [bradautomates/claude-video](https://github.com/bradautomates/claude-video) ⭐0 (+951 today)：为Claude大模型添加视频理解能力，自动完成视频下载、帧提取、转录与多模态输入，是扩展VLA模型时序感知能力的实用工具，今日涨星超900。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2585：面向入门者的免费具身智能教程，仅需Python基础即可从0搭建VLA/OpenVLA/SmolVLA模型，是国内社区最受欢迎的具身入门资源。
3. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐365：全中文实战导向的VLA领域学习/面试手册，聚焦机器人场景的特有挑战，覆盖算法、部署、面试题，适合国内算法工程师入门。
4. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐473：商汤最新开源的InternVLA-A1模型，统一机器人操纵的理解、生成与动作能力，是当前国产VLA的代表工作。
5. [YuZhaoshu/Efficient-VLAs-Survey](https://github.com/YuZhaoshu/Efficient-VLAs-Survey) ⭐168：高效VLA研究综述项目，持续更新前沿论文与代码，聚焦低资源VLA的优化方向，为研究者提供一站式导航。
6. [muhammadmahadazher/vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget) ⭐0：首个面向8GB消费级笔记本显卡的VLA基准对比项目，覆盖ACT、扩散策略、SmolVLA的公平对比，大幅降低VLA研究的硬件门槛。

---

### 🦾 操作与抓取（灵巧手、操纵任务、抓取规划）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2704：完全开源的人形机械臂，专为接触富集的物理AI研究设计，是当前开源度最高、面向落地的人形臂方案，7天内获得大量开发者关注。
2. [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) ⭐2503：机器人操纵领域的模块化仿真框架与基准，支持多种机械臂与任务场景，是VLA操纵能力验证的主流平台。
3. [robocasa/robocasa](https://github.com/robocasa/robocasa) ⭐1527：大规模家庭日常任务仿真数据集，包含上千种真实场景的操纵任务，为通用机器人操纵模型训练提供高质量数据。
4. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐167：CVPR2025收录的LLM驱动操纵仿真生成方法，可自动生成多样化的指令跟随操纵任务，提升VLA的泛化能力。
5. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐33：将自然语言指令编译为类型安全的机器人技能图，支持在仿真与真实机器人上执行，降低操纵任务的规划门槛。
6. [sahilrajpurkar03/nlp-pnp-robotic-arm](https://github.com/sahilrajpurkar03/nlp-pnp-robotic-arm) ⭐64：基于ROS2、YOLOv8、Ollama的自然语言控制机械臂抓取系统，支持Franka、UR5臂，入门友好，适合个人开发者快速搭建演示系统。

---

### 🚶 运动与导航（人形、足式、SLAM、感知）
1. [ruvnet/RuView](https://github.com/ruvnet/RuView) ⭐0 (+799 today)：无需摄像头，仅利用普通WiFi信号即可实现实时空间感知、生命体征检测与存在识别，为具身机器人提供低成本、隐私友好的感知方案，今日涨星近800。
2. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15437：全球最大的开源无人系统运动控制固件，支持无人机、无人车、无人船等多种平台，是移动机器人导航控制的主流底层方案。
3. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐254：UMI-3D SLAM与数据处理管线，为具身机器人的三维环境感知与建图提供开箱即用的工具链。
4. [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐238：ECCV2026收录的高保真导航模拟器，采用动态高斯溅射技术，大幅提升导航仿真的真实度，缩小sim2real差距。
5. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐320：人形、足式机器人的运动控制算法库，核心为动量优化控制器，是波士顿动力之外最成熟的开源足式控制方案之一。
6. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐131：轻量可扩展的人形机器人全身遥操作框架，支持低成本采集人形运动演示数据，为VLA的模仿学习提供数据支撑。

---

### 📦 具身应用（代理工具、落地部署、自主系统）
1. [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) ⭐0 (+1717 today)：首个专为AI代理打造的开源Office自动化工具，支持Word/Excel/PPT的读写、编辑与自动化，无需安装Office，单二进制部署，今日涨星居具身相关项目首位，是数字具身办公场景的标杆项目。
2. [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) ⭐0 (+318 today)：面向AI代理的全本地长期记忆方案，采用四层渐进式管线，零外部API依赖，适合边缘端具身设备的隐私化记忆部署，今日获得大量关注。
3. [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3393：开源跨平台AI助手生态，支持MCP集成、多模态工作流、IoT控制与语音交互，是当前国内落地性最强的消费级具身助理方案。
4. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐408：自进化具身AI操作系统，基于代理工作流实现物理世界的自主任务执行，是面向具身通用智能的早期探索项目。
5. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐99：通过自然语言即可控制实体机器人硬件的代理系统，屏蔽不同机器人的底层接口差异，降低具身应用的部署门槛。
6. [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐218：最小化LLM物理具身架构，实现带自感知闭环的端到端物理交互，适合研究者快速验证具身智能的核心假设。

---

## 趋势信号分析
今日社区爆发性关注集中在**具身代理的端侧基础设施**，安全沙箱、本地记忆、场景化操作工具等项目单日涨星均超300，核心驱动是近期大模型代理从纯对话向实体/数字世界交互落地的需求爆发，与OpenAI MCP生态、Claude 3.5 Sonnet的工具调用能力升级直接相关。新兴方向方面，非视觉的WiFi空间感知首次登上热榜，为具身机器人的低成本、隐私友好感知提供了替代路径；VLA方向的平民化趋势明显，出现了面向8GB消费级显卡的基准项目，降低了中小开发者的参与门槛。此外，国产VLA模型、全中文入门资源的活跃度持续上升，反映国内具身智能生态正在快速成熟。

---

## 社区关注热点
- 🎯 优先关注**AI代理的端侧基础设施**：CubeSandbox、TencentDB-Agent-Memory等项目均主打全本地、零外部依赖，契合具身设备的隐私与低延迟需求，是未来落地的核心方向。
- 🎯 重点跟进**低资源VLA的相关工作**：从面向8GB显卡的基准到高效微调方法，VLA正在脱离高算力门槛，中小开发者可快速参与，相关开源生态将迎来爆发。
- 🎯 留意**非视觉感知的具身方案**：RuView的WiFi感知方案无需摄像头，成本低、隐私性强，有望在家庭服务机器人、工业巡检场景获得广泛应用。
- 🎯 国内开发者可关注**本土具身生态**：全中文VLA手册、入门教程、国产VLA模型的持续更新，为国内从业者提供了更友好的学习与落地路径。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*