# AI 开源趋势日报 2026-07-25

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-25 01:29 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-25）
---
## 今日速览
今日具身智能与机器人领域呈现三大核心动向：一是具身代理基础设施爆发，三款工具（统一AI网关、代理专用浏览器、无视觉空间感知）进入GitHub全品类Trending，单日最高新增星近2000，社区对落地工具的需求远超算法原型；二是VLA技术双线演进，大厂大模型向自动驾驶等全场景拓展，同时轻量Mamba架构VLA入选顶会，端侧部署成为新方向；三是开源人形与操作硬件栈加速普及，覆盖从百元级DIY平台到工业级机械臂的全层级需求，VLA场景化评测工具补全了研发链路的关键缺口。
---
## 各维度热门项目
### 🤖 机器人框架/SDK
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7759
   NVIDIA官方基于Isaac Sim的机器人学习统一框架，是当前工业界和学术界进行VLA训练、sim2real验证的主流仿真基础设施。
2. [dora-rs/dora](https://github.com/dora-rs/dora) [Rust] ⭐3853
   数据流导向的开源机器人中间件，主打低延迟、可组合、分布式架构，为AI原生机器人应用简化开发流程，是Rust技术栈在机器人领域的代表性项目。
3. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124
   无ROS依赖的轻量sim2real框架，原生支持VLA模型与RL代理部署，已适配Franka、UR5e、SO101等主流机械臂与人形机器人，大幅降低VLA落地门槛。
4. [softmata/horus](https://github.com/softmata/horus) [Rust] ⭐392
   主打极致性能的机器人运行时系统，定位为机器人领域的“Android”，为异构机器人硬件提供统一 runtime 层，是近期机器人基础设施领域的新兴项目。
5. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14315
   全球应用最广的通用多关节物理仿真器，是机器人操作、足式控制、VLA训练的核心工具，生态成熟度最高。

### 🧠 VLA/基础模型
1. [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐1933
   NVIDIA开源的10B参数推理型VLA，面向自动驾驶场景，支持驾驶轨迹输出与因果链推理，是VLA向非工业机器人场景拓展的代表性项目。
2. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐510
   国内团队开源的机器人操作VLA，统一了感知理解、内容生成与动作输出能力，覆盖多类接触富集操作任务，是国产VLA的标杆项目。
3. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐430
   首份全中文VLA领域实战学习/面试手册，聚焦机器人领域特有的技术挑战，填补了国内VLA入门资源的空白。
4. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2851
   面向入门开发者的具身智能教程，仅需Python基础即可从零实现OpenVLA、SmolVLA等主流模型，社区普及度极高。
5. [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐7
   IROS 2026录用的轻量VLA，采用Mamba架构仅179M参数即可完成机器人操作任务，代表VLA端侧部署、轻量化的技术方向。
6. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐36
   专门面向VLA与物理AI模型的统一评测框架，支持一次定义基准即可跨仿真、跨机器人运行所有策略，补全了VLA研发的关键工具链。

### 🦾 操作与抓取
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2762
   完全开源的人形机械臂，专为接触富集的物理AI研究与落地设计，是当前开源操作硬件领域星标最高的项目之一。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐298
   通用机器人操作基准的官方仓库，为VLA操作能力评估提供统一的任务集与评测指标。
3. [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8
   面向VLA模型的双手厨房操作基准，覆盖复杂长流程操作任务，是VLA场景化评测的新兴方向。
4. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐84
   可将自然语言指令编译为可验证机器人技能图的框架，支持仿真与真机部署，探索了VLA输出的可解释性与安全性路径。

### 🚶 运动与导航
1. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐598
   地平线开源的人形机器人全身控制基础模型，支持多类运动与操作任务的统一生成，是国内人形基础模型的代表性成果。
2. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐259
   港大开源的UMI-3D SLAM与数据处理管线，为具身智能的三维环境感知提供轻量化解决方案。
3. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐138
   轻量可扩展的人形机器人全身遥操作框架，支持低成本数据采集与策略验证，是人形机器人数据闭环的核心工具。
4. [Rhoban/microban](https://github.com/Rhoban/microban) ⭐44
   百元级3D打印开源人形机器人，基于树莓派Zero 2W，大幅降低人形机器人研究与DIY的入门门槛。
5. [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx) ⭐263
   JAX实现的高性能模型预测控制库，专为足式与人形机器人的运动控制优化，支持端侧快速部署。

### 📦 具身应用
1. [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) [TypeScript] ⭐0 (+1841 today)
   今日Trending爆火的开源AI网关，统一接入290+大模型提供商、500+模型，支持配额感知自动降级、15-95% token压缩，是具身代理、VLA后端的核心基础设施，单日新增星近2000，社区需求极强。
2. [ruvnet/RuView](https://github.com/ruvnet/RuView) [Rust] ⭐0 (+1022 today)
   无视觉空间感知方案，通过普通WiFi信号即可实现实时空间感知、生命体征检测、存在识别，无需摄像头，是隐私友好的具身感知技术，今日涨星超千。
3. [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) [JavaScript] ⭐0 (+880 today)
   专为AI代理设计的最快自动化浏览器，支持安全共享登录状态、不干扰用户使用，零成本零配置，是web具身代理的核心运行载体，今日涨星显著。
4. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63207
   全球落地最成熟的开源机器人操作系统之一，已支持300+款量产车的高级驾驶辅助，是具身智能在民用场景落地的标杆项目。
5. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1045
   自进化具身AI操作系统，基于代理工作流架构，支持物理世界任务的自主规划与执行，是具身OS方向的前沿探索项目。
---
## 趋势信号分析
今日具身智能领域最核心的爆发方向为**具身代理基础设施**，三款相关工具进入GitHub全品类Trending前20，单日最高新增星达1841，反映社区重心正从VLA算法原型研发转向落地工具链搭建，集中解决具身代理的多模型接入、运行载体、低成本感知等核心痛点。
技术栈层面，Rust正成为机器人核心基础设施的首选：今日上榜的机器人runtime、中间件、无视觉感知项目均采用Rust开发，主打低延迟高可靠，适配物理AI的实时性要求。此外Mamba架构轻量VLA入选IROS 2026，VLA端侧部署成为新兴方向。
行业关联上，近期两大事件直接驱动热度：一是人形机器人量产进度加速，推动开源操作硬件、全身控制模型活跃；二是Claude 3.7、OpenAI o3的代理能力爆发，直接带动AI网关、代理专用浏览器等工具需求暴涨。
---
## 社区关注热点
- **OmniRoute 统一AI网关**：单日涨星近2000，解决了具身代理多模型切换、成本优化的核心痛点，是所有VLA、代理项目的刚需后端，建议开发者优先纳入技术栈。
- **VLA评测工具链**：inspect-robots、KitchenBench等评测项目密集涌现，标志着VLA发展从“造模型”进入“测能力”阶段，标准化评测将成为下一阶段的竞争核心。
- **Rust原生机器人基础设施**：从runtime到中间件再到感知方案全栈采用Rust，反映机器人行业对实时性、可靠性的要求正在提升，Rust将成为机器人开发的主流语言之一。
- **低成本人形机器人平台**：Microban等百元级开源人形项目的出现，大幅降低了人形机器人研究、数据采集的门槛，适合个人开发者与小型团队入场。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*