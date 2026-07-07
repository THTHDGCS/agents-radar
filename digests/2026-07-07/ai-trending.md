# AI 开源趋势日报 2026-07-07

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-07 09:51 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-07）

---

## 1. 今日速览
今日具身智能与机器人领域开源生态呈现三大核心动向：一是非视觉具身感知工具与VLA预处理工具登上GitHub热榜，具身感知的多元化路径与VLA工具链的完善获得开发者广泛关注；二是VLA效率优化成为顶会研究热点，ICML2026多项成果证实VLA下游适配的计算成本可大幅降低，为VLA的规模化落地扫清技术障碍；三是人形机器人、消费级具身应用的工具链持续完善，从硬件开源、仿真适配到落地运维均有新增开源项目，同时面向普通开发者的低门槛VLA学习、测试资源快速增加，进一步降低了具身智能的入场门槛。

---

## 2. 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,625（总量）：NVIDIA官方基于Isaac Sim推出的统一机器人学习框架，是目前VLA训练、sim2real验证的核心工具链，近期新增Unitree系列机器人支持，生态快速扩张。
- [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,833（总量）：Rust编写的数据流导向机器人中间件，主打低延迟、可组合、分布式特性，适合构建端到端AI机器人应用，是具身系统架构的新兴候选方案。
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,108（总量）：通用多关节物理仿真器，是机器人学习、具身智能研究的基础工具，近期持续优化GPU加速能力，适配大批次VLA训练需求。
- [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,086（总量）：Rust编写的多模态机器人数据可视化、查询、流处理工具，解决VLA训练、部署过程中的多模态数据对齐调试痛点，近期获得大量机器人开发者采用。
- [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,028（总量）：专为具身和代理AI设计的强化学习基础设施，简化VLA训练、RL策略部署流程，大幅降低具身智能开发门槛。
- [softmata/horus](https://github.com/softmata/horus) ⭐386（总量）：Rust编写的高性能机器人运行时系统，定位为机器人领域的“Android”，主打低延迟、高实时性，为人形、工业机器人提供统一运行底座。

---

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
- [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,557（总量）：面向Python基础开发者的零门槛具身智能教程，覆盖VLA/OpenVLA/SmolVLA/Pi0等主流模型的从0构建，是入门VLA领域的最热门学习资源。
- [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐457（总量）：国内最新开源的通用VLA模型，统一了机器人操作的理解、生成、动作能力，覆盖多类接触富集操作任务。
- [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐358（总量）：首份全中文、实战导向的VLA学习/面试手册，聚焦机器人领域特有挑战，填补了中文VLA专业资料的空白。
- [bradautomates/claude-video](https://github.com/bradautomates/claude-video) ⭐0（+427 今日新增）：为Claude增加长视频处理能力的工具，可作为VLA模型的长时序视觉输入预处理组件，解决现有VLA多帧输入处理复杂的痛点，今日热度上涨迅速。
- [cair-vinuni/CLP_VLA](https://github.com/cair-vinuni/CLP_VLA) ⭐4（总量，ICML2026）：ICML2026最新研究成果，证明VLA微调仅需调整极少层即可达到最优效果，大幅降低VLA下游适配的计算成本。
- [muhammadmahadazher/vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget) ⭐0（总量，7天活跃）：面向消费级硬件的VLA基准测试项目，仅需8GB笔记本显卡即可完成ACT、扩散策略、SmolVLA的对比测试，大幅降低VLA研究的硬件门槛。

---

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
- [enactic/openarm](https://github.com/enactic/openarm) ⭐2,697（总量）：完全开源的人形手臂硬件，面向接触富集的物理AI研究与部署，填补了高性能开源人形操作硬件的空白，是近期操作领域最受关注的硬件项目。
- [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐166（总量，CVPR2025）：CVPR2025收录的LLM驱动的通用操作仿真框架，可生成多样化的指令遵循操作任务，提升VLA操作策略的泛化能力。
- [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) ⭐26（总量，RSS2026）：RSS2026最新研究，提出通用位姿预训练方法，大幅提升VLA操作策略的泛化性，是操作VLA预训练的新方向。
- [sahilrajpurkar03/nlp-pnp-robotic-arm](https://github.com/sahilrajpurkar03/nlp-pnp-robotic-arm) ⭐64（总量）：基于ROS2、YOLOv8、Ollama的自然语言控制拾取放置机械臂系统，可实现零代码自然语言操作指令执行，适合入门级操作应用开发。
- [CyanHaze/Awesome-Dexterous-Hands](https://github.com/CyanHaze/Awesome-Dexterous-Hands) ⭐4（总量）：最新整理的灵巧机器人手与操作领域的论文、数据集、硬件资源列表，覆盖当前主流灵巧操作研究方向。

---

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
- [abizovnuralem/go2_omniverse](https://github.com/abizovnuralem/go2_omniverse) ⭐1,035（总量）：为Unitree Go2四足、G1人形机器人提供Isaac Lab支持的项目，打通了消费级足式机器人与主流机器人学习框架的适配，是足式机器人学习的核心工具。
- [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) ⭐229（总量，ECCV2026）：ECCV2026收录的高保真导航模拟器，采用3D高斯溅射实现动态场景渲染，解决了传统导航模拟器真实感不足的问题，适合具身导航策略训练。
- [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐254（总量）：港大Mars实验室开源的UMI-3D SLAM与数据处理管线，为具身机器人提供高精度3D环境感知能力，是近期SLAM方向面向具身场景的重要成果。
- [ruvnet/RuView](https://github.com/ruvnet/RuView) ⭐0（+470 今日新增）：基于WiFi信号的无视觉空间感知、生命体征检测工具，可作为具身机器人的低成本环境感知模块，无需摄像头即可实现存在检测、动作识别，今日热度上涨迅速。
- [NJU-RLC/quadrupedal-agility](https://github.com/NJU-RLC/quadrupedal-agility) ⭐119（总量）：南京大学开源的四足机器人多样化自然行为学习代码，提升四足机器人的运动敏捷性，是足式机器人学习的最新成果。

---

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
- [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3,390（总量）：开源多模态AI助手生态，支持MCP集成、IoT控制、跨平台语音交互，是面向消费级的具身AI助手落地项目，用户基数增长迅速。
- [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐130（总量）：轻量级可扩展的人形机器人全身遥操作框架，降低人形机器人遥操作的开发门槛，适合具身数据采集、远程部署场景。
- [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐2（总量）：开源VLA/物理AI模型评估框架，支持一次定义基准、跨机器人跨仿真运行，解决VLA落地评估标准不统一的痛点。
- [zengury/manastone-diag](https://github.com/zengury/manastone-diag) ⭐6（总量）：面向AgiBot X2 Ultra人形机器人的离线故障诊断助手，结合规则与LLM代理实现故障自动排查，是人形机器人落地运维的首个开源工具。
- [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) ⭐4,901（总量）：开源四足机器宠物框架，适合STEM教育、DIY具身机器人场景，是消费级具身硬件落地的代表项目。

---

## 3. 趋势信号分析
今日开源数据显示，低门槛VLA开发工具与非视觉具身感知方向正在获得社区爆发性关注：前者受益于OpenVLA、Pi0等开源VLA模型的普及，开发者对低成本验证、学习VLA的需求暴涨，出现了8GB显卡可运行的VLA基准、零入门门槛的中文VLA教程等项目；后者则因视觉感知的隐私、环境限制痛点，WiFi等无传感器感知路径首次登上热榜，成为具身感知的新兴探索方向。技术栈方面，Rust正在成为机器人基础设施的首选语言，今日热榜的感知、中间件、运行时项目均采用Rust开发，其低延迟、高可靠性特性适配机器人的实时性需求。行业层面，ICML2026、RSS2026等顶会的最新研究集中开源，叠加人形机器人量产进程加速的行业背景，共同推高了VLA优化、人形工具链等方向的热度。

---

## 4. 社区关注热点
- **低门槛VLA开发资源**：代表项目为[every-embodied](https://github.com/datawhalechina/every-embodied)教程、[vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget)基准，无需高端GPU即可完成VLA的学习与验证，适合中小开发者快速入场VLA领域。
- **Rust生态的机器人基础设施**：代表项目为[dora-rs/dora](https://github.com/dora-rs/dora)中间件、[softmata/horus](https://github.com/softmata/horus)运行时，Rust的低延迟、高安全性特性正在重构机器人基础软件栈，是未来具身系统的核心技术方向。
- **非视觉具身感知技术**：代表项目为[ruvnet/RuView](https://github.com/ruvnet/RuView)，基于WiFi的无摄像头感知方案解决了视觉感知的隐私、光照限制问题，可广泛应用于家庭服务机器人、工业检测等场景。
- **人形机器人全栈工具链**：从[enactic/openarm](https://github.com/enactic/openarm)开源硬件到[manastone-diag](https://github.com/zengury/manastone-diag)运维工具，人形机器人的开源生态正在快速完善，提前布局相关工具可获得先发优势。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*