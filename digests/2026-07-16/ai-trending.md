# AI 开源趋势日报 2026-07-16

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-16 01:26 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-16）
---

## 今日速览
今日具身智能与机器人开源领域整体呈现「平民化落地导向」，VLA相关的入门工具、学习资源集中涌现，大幅降低了算法工程师的入局门槛。人形机器人赛道的开源项目覆盖硬件、控制、仿真全链路，从DIY级人形平台到工业级机械臂方案均有更新。具身智能基础设施层持续迭代，数据流中间件、GPU加速仿真、VLA评估框架等工具不断补全生态。值得注意的是，今日GitHub全站Trending无核心具身智能项目进入Top10，领域仍处于技术积累阶段，大众关注度有待提升。

---

## 各维度热门项目
### 🤖 机器人框架/SDK
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,683（无今日新增）：NVIDIA官方推出的基于Isaac Sim的统一机器人学习框架，是目前VLA与机器人学习研究的主流仿真底座，生态持续完善中。
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,843（无今日新增）：Rust编写的低延迟数据流导向机器人中间件，支持分布式部署，是ROS之外新兴的机器人应用开发架构，近期关注度持续上升。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,219（无今日新增）：通用多刚体物理仿真引擎，是机器人接触仿真、强化学习训练的核心工具，最新版本已支持多GPU并行仿真。
4. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,194（无今日新增）：基于NVIDIA Warp构建的开源GPU加速物理引擎，专为机器人仿真优化，是MuJoCo之外的新兴仿真方案。
5. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,133（无今日新增）：多模态机器人数据可视化、查询与流传输工具，解决了机器人训练过程中多源数据（视觉、关节、动作）的统一可视化痛点。
6. [softmata/horus](https://github.com/softmata/horus) ⭐389（无今日新增）：主打低延迟的机器人运行时系统，定位为“机器人领域的Android”，致力于统一不同机器人硬件的底层控制接口。

### 🧠 VLA/基础模型
1. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐390（无今日新增）：国内首份全中文、实战导向的VLA领域学习/面试手册，聚焦机器人领域特有挑战，填补了中文VLA入门资源的空白，受到国内开发者高度关注。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,690（无今日新增）：面向Python基础开发者的零基础具身智能入门项目，从零搭建OpenVLA、SmolVLA等主流模型，降低了VLA的实践门槛。
3. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,124（无今日新增）：专为具身与Agent AI设计的强化学习基础设施，支持VLA策略的训练、部署与评估，是具身智能训练层的核心工具。
4. [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐113（无今日新增）：具身AI安全领域的综述资源，收录500+相关论文，覆盖感知、规划、Agent系统等全链路安全方向，是VLA安全研究的一站式资源。
5. [BuceaGeorgia/VIRENA](https://github.com/BuceaGeorgia/VIRENA) ⭐6（无今日新增）：极简可解读的VLA实现，基于冻结CLIP加小型头，支持ManiSkill任务，可在Mac设备无GPU运行，是VLA入门学习的绝佳Demo。
6. [xiaoms22/lunavla](https://github.com/xiaoms22/lunavla) ⭐2（无今日新增）：面向初学者的VLA项目脚手架，包含CPU可运行的ACT模仿学习示例、评估脚本与简历可用的文档，是学生入门VLA实践的快速启动工具。
7. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐5（无今日新增）：VLA与物理AI模型的通用评估框架，支持一次定义基准、在任意机器人/仿真环境运行任意策略，填补了VLA统一评估的工具空白。
8. [provael/provael](https://github.com/provael/provael) ⭐3（无今日新增）：开源VLA机器人策略红队测试工具，支持在仿真环境中测试VLA策略的安全性，输出攻击成功率，是VLA安全研究的核心工具。

### 🦾 操作与抓取
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,725（无今日新增）：全开源人形机械臂，专为物理AI研究与接触富集任务设计，是目前最受关注的开源操作硬件平台之一。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐236（无今日新增）：机器人操作任务基准平台，覆盖多场景抓取、装配任务，支持VLA策略的标准化评测。
3. [RoboTwin-Platform/RMBench](https://github.com/RoboTwin-Platform/RMBench) ⭐167（无今日新增）：基于RoboTwin数字孪生的记忆依赖操作基准，针对需要长序列记忆的复杂操作任务设计。
4. [ASIG-X/manusGlove](https://github.com/ASIG-X/manusGlove) ⭐22（无今日新增）：Manus灵巧手数据手套的Linux ROS2驱动，支持高精度遥操作抓取数据采集与控制。
5. [iit-DLSLab/locomanipulation-teleop-isaaclab](https://github.com/iit-DLSLab/locomanipulation-teleop-isaaclab) ⭐20（无今日新增）：面向Unitree Go2+AgileX Piper移动操作平台的IsaacLab遥操作环境，支持sim-to-sim与sim-to-real pipeline。

### 🚶 运动与导航
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,127（无今日新增）：开源机器人操作系统，目前已落地支持300+车型的驾驶辅助系统，是具身智能在自动驾驶场景的标杆落地项目。
2. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,477（无今日新增）：全球最流行的开源飞控系统，支持多旋翼、固定翼、无人车、水下机器人等多平台运动控制。
3. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐255（无今日新增）：港大Mars实验室推出的UMI-3D SLAM与数据处理管线，支持移动机器人的高精度三维环境感知与定位。
4. [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) ⭐813（无今日新增）：专为足式机器人设计的IsaacLab直接工作流，简化了人形、四足机器人的运动控制训练与部署流程。
5. [ispaik06/convex-mpc-biped](https://github.com/ispaik06/convex-mpc-biped) ⭐12（无今日新增）：基于MuJoCo实现的双足人形凸MPC运动控制算法，支持接触wrench优化，是双足locomotion入门的绝佳参考实现。

### 📦 具身应用
1. [moeru-ai/airi](https://github.com/moeru-ai/airi) ⭐0（今日+110）：今日Trending上榜的虚拟具身项目，支持自托管的赛博生命交互，可实现实时语音聊天、在Minecraft/Factorio等虚拟环境中自主行动，是虚拟具身落地的新尝试。
2. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,587（无今日新增）：开源机器人数字孪生平台RoboTwin 2.0官方仓库，支持高保真物理仿真与sim2real迁移，是具身智能落地的核心工具。
3. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐102（无今日新增）：基于Strands Agent的自然语言机器人控制方案，支持用户通过自然语言指令直接控制实体机器人与硬件。
4. [ros-claw/rosclaw](https://github.com/ros-claw/rosclaw) ⭐163（无今日新增）：物理AI与具身Agent的自演进运行时基础设施，支持将AI Agent接地到实体机器人，自带安全沙箱、技能演化等核心能力。
5. [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐21（无今日新增）：可全3D打印的低成本开源人形机器人，基于树莓派Zero 2W，是DIY爱好者与教学场景的高性价比具身硬件平台。

---

## 趋势信号分析
今日开源社区的核心爆发点集中在VLA领域的「门槛下探」：中文全栈学习手册、零基础入门项目、消费级硬件可运行的轻量VLA Demo集中涌现，打破了此前VLA研究仅面向顶级实验室的高门槛，中小开发者与学生群体的入局成本大幅降低。同时VLA生态工具链快速补全，从数据合成、策略训练到统一评估、红队测试的全流程工具均有新项目更新，说明VLA正从学术研究走向工程化落地。此外，人形机器人开源项目覆盖从DIY硬件到工业级控制的全链路，与近期全球人形机器人融资热潮、产业端落地加速的趋势形成呼应。虚拟具身项目首次进入全站Trending，也意味着具身智能的落地场景正在从实体机器人向虚拟交互场景延伸。

---

## 社区关注热点
- 🎯 **VLA入门与学习资源**：以《VLA-Handbook》、every-embodied为代表的中文入门资源集中发布，是国内开发者快速入局VLA领域的绝佳路径，建议想要转岗VLA算法工程师的开发者优先关注。
- 🛠️ **机器人开发新架构**：dora-rs、Horus等新兴机器人中间件/运行时正在挑战ROS的传统地位，低延迟、数据流导向、原生支持AI部署的特性更适配VLA时代的机器人开发需求，值得技术架构师重点调研。
- 🦾 **开源操作硬件平台**：OpenArm全开源机械臂的关注度持续上升，其面向接触富集任务的设计适配VLA策略的真实世界部署需求，是实验室与创业团队降低硬件成本的优质选择。
- 🧪 **VLA评估与安全工具**：inspect-robots、Provael等VLA评估与红队测试工具的出现，填补了VLA落地的验证环节空白，是VLA产品化过程中必不可少的核心工具。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*