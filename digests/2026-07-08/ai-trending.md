# AI 开源趋势日报 2026-07-08

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-08 01:27 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-08）
---

## 今日速览
今日具身智能与机器人开源领域呈现四大核心动向：一是无视觉具身感知工具爆发，基于WiFi信号的空间感知项目RuView单日新增1129星，成为Trending榜最受关注的具身相关项目；二是VLA生态加速向平民化落地，从低成本算力基准、轻量大模型多模态扩展到中文入门教程，覆盖从入门到部署的全链条需求；三是人形机器人开源栈持续完善，从全开源执行器硬件、专用运行时到遥操作框架，软硬件协同的开源路径逐渐清晰；四是机器人开发基础设施不断优化，无ROS的sim2real框架、统一评估工具、Agent安全沙箱等项目进一步降低了具身智能的工程化门槛。

---

## 各维度热门项目
### 🤖 机器人框架/SDK
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,629
   NVIDIA官方推出的机器人学习统一框架，基于Isaac Sim构建，支持从强化学习到VLA的全流程训练与仿真，是目前机器人学习领域最主流的工业级框架。
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,831
   面向AI机器人应用的数据流导向中间件，采用Rust开发，具备低延迟、可组合、分布式的特性，简化了多模态具身系统的搭建流程。
3. [TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox) ⭐0 (+664 today)
   今日Trending热门的轻量安全沙箱，专为AI Agent设计，支持高并发、秒级启动，是具身Agent部署过程中安全隔离、风险管控的核心基础设施。
4. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐120
   无ROS依赖的sim2real开发框架，原生支持VLA模型与RL策略的训练部署，适配Franka、UR5e等主流机械臂，大幅简化了机器人算法的落地流程。
5. [softmata/horus](https://github.com/softmata/horus) ⭐386
   采用Rust开发的高性能机器人运行时系统，定位为“机器人的Android”，针对低延迟运动控制、多模态任务调度做了深度优化，是新兴的人形机器人基础软件方向。
6. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,119
   行业通用的多关节物理仿真引擎，是机器人操作、足式运动等领域训练验证算法的核心工具，目前已支持GPU加速与多平台部署。

---

### 🧠 VLA/基础模型
1. [bradautomates/claude-video](https://github.com/bradautomates/claude-video) ⭐0 (+965 today)
   今日Trending热门的VLA工具链项目，可一键给Claude大模型增加视频理解能力，自动完成视频下载、帧提取、语音转写并喂给大模型，是将通用LLM快速改造为VLA的轻量方案。
2. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐462
   最新开源的通用VLA模型系列，首个版本InternVLA-A1实现了视觉理解、内容生成、机器人操作的能力统一，在多个操作基准上取得了SOTA效果。
3. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,566
   国内最受欢迎的具身智能入门教程，面向仅具备Python基础的开发者，提供从0构建VLA/OpenVLA/SmolVLA/Pi0的全流程实战内容，大幅降低了VLA领域的入门门槛。
4. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐360
   全中文的VLA领域学习与面试手册，聚焦机器人场景特有的技术挑战，覆盖算法原理、工程落地、面试真题等内容，是VLA从业者的实战参考。
5. [muhammadmahadazher/vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget) ⭐0
   面向消费级算力的VLA基准项目，仅需8GB显存的笔记本GPU即可完成ACT、Diffusion Policy、SmolVLA等主流算法的对比测试，为中小开发者提供了低成本的VLA验证方案。
6. [OpenDriveLab/RISE](https://github.com/OpenDriveLab/RISE) ⭐311
   RSS 2026收录的最新研究，通过组合式世界模型实现机器人策略的自进化，无需额外人工标注即可提升策略泛化性，代表了VLA与世界模型结合的前沿方向。

---

### 🦾 操作与抓取
1. [robocasa/robocasa](https://github.com/robocasa/robocasa) ⭐1,523
   大规模机器人日常操作仿真平台，包含数千种贴近真实生活的家庭任务场景，是训练通用操作机器人、验证VLA策略泛化性的核心基准环境。
2. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐166
   CVPR 2025收录的LLM驱动操作仿真生成框架，可自动生成多样化的指令跟随操作任务，解决了机器人操作训练数据不足的痛点。
3. [hetolin/PoseVLA](https://github.com/hetolin/PoseVLA) ⭐33
   RSS 2026收录的通用姿态预训练VLA策略，通过大规模姿态预训练显著提升了unseen场景下的操作泛化性，是VLA面向真实世界落地的重要优化方向。
4. [NVIDIA-ISAAC-ROS/isaac_ros_manipulation](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_manipulation) ⭐107
   NVIDIA官方推出的ROS2机械臂操作工作流包，集成了运动规划、视觉感知、力控等核心能力，是工业级机械臂部署的标准工具链。
5. [sahilrajpurkar03/nlp-pnp-robotic-arm](https://github.com/sahilrajpurkar03/nlp-pnp-robotic-arm) ⭐64
   基于ROS2的自然语言控制拾取放置系统，集成了YOLOv8-OBB检测、MoveIt运动规划与Ollama大模型，是低成本实现语音控制机械臂的完整参考方案。

---

### 🚶 运动与导航
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,700
   完全开源的人形机器人手臂硬件，专为接触富集的物理AI任务设计，可直接适配主流VLA策略，填补了中高端开源人形执行器的空白。
2. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,438
   工业级ROS2导航框架，支持路径规划、避障、多传感器融合等核心能力，是目前移动机器人导航领域最主流的开源方案。
3. [NJU-RLC/quadrupedal-agility](https://github.com/NJU-RLC/quadrupedal-agility) ⭐119
   南京大学开源的四足机器人敏捷运动学习算法官方实现，可实现跳障、快跑等复杂动作，显著提升了足式机器人的运动性能上限。
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐130
   轻量可扩展的人形机器人全身遥操作框架，支持多设备输入与低延迟控制，是采集人形机器人训练数据、验证运动策略的实用工具。
5. [MarcDcls/microban](https://github.com/MarcDcls/microban) ⭐7
   低成本全3D打印的开源人形机器人平台，基于Raspberry Pi Zero 2W驱动，总成本低、易组装，是入门人形机器人研发的高性价比硬件方案。

---

### 📦 具身应用
1. [ruvnet/RuView](https://github.com/ruvnet/RuView) ⭐0 (+1129 today)
   今日Trending热度最高的具身感知项目，无需任何摄像头即可通过商用WiFi信号实现实时空间感知、生命体征监测与人员存在检测，隐私友好、部署成本极低，是具身感知技术的新赛道。
2. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,030
   专为具身与Agent AI设计的强化学习基础设施，提供从数据采集、模型训练到部署上线的全流程工程化支持，加速了RL算法在具身场景的落地。
3. [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3,392
   开源多模态AI助手生态，支持IoT设备控制、跨平台语音交互与MCP协议集成，是具身交互技术面向消费级场景落地的典型参考。
4. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐389
   自进化具身AI操作系统，基于Agent工作流构建，支持机器人能力的自主迭代与场景适配，是具身Agent系统架构的前沿探索。
5. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,037
   目前落地规模最大的具身智能操作系统之一，已支持全球300+款车型的高级驾驶辅助功能，验证了通用具身系统在垂直场景的规模化落地能力。

---

## 趋势信号分析
今日开源数据反映出三大核心趋势：一是**非视觉具身感知**成为新爆发点，RuView项目单日新增千星，说明社区对隐私友好、低功耗、无摄像头的感知方案需求迫切，打破了视觉主导的具身感知技术路径，未来面向家用、养老、办公场景的非视觉感知方案可能成为落地热点。二是**VLA加速平民化落地**，从8GB消费级显卡可跑的基准测试、轻量大模型视频扩展工具到中文入门教程，社区正在推动VLA从学术研究向普通开发者可复现、可部署的方向发展，与近期OpenVLA、SmolVLA等小参数VLA模型的发布形成呼应。三是**人形机器人开源生态加速成熟**，从全开源执行器硬件、专用运行时到遥操作框架的全栈项目密集出现，与近期国内外人形机器人企业密集发布量产计划的行业趋势一致，开源生态正在为人形机器人的规模化落地降低门槛。

---

## 社区关注热点
- 【[ruvnet/RuView](https://github.com/ruvnet/RuView)】：基于WiFi的无视觉空间感知方案，单日新增1129星，无需额外硬件、隐私友好的特性适合家用、养老、办公等场景的具身感知落地，是感知技术的全新赛道。
- 【[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)】：国内首个面向Python基础开发者的具身VLA从0到1实战教程，覆盖OpenVLA、SmolVLA等主流模型，大幅降低了VLA领域的入门门槛，适合新手快速入局。
- 【[enactic/openarm](https://github.com/enactic/openarm)】：完全开源的人形手臂硬件，已获2700星，专为接触富集的物理AI任务设计，适配主流VLA策略，填补了中低端开源人形执行器的空白，适合人形机器人开发者快速原型验证。
- 【[muhammadmahadazher/vla-on-a-budget](https://github.com/muhammadmahadazher/vla-on-a-budget)】：8GB消费级显卡即可运行的VLA基准对比项目，覆盖主流模仿学习算法，解决了中小开发者缺少高端算力验证VLA的痛点，是VLA平民化落地的标志性项目。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*