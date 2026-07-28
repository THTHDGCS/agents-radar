# AI 开源趋势日报 2026-07-28

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-28 01:25 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-28）
---

## 今日速览
今日GitHub具身智能与机器人领域热度集中在VLA落地优化、人形开源软硬件、平民化入门教程三大方向；NVIDIA开源的Alpamayo系列推理VLA持续占据VLA主题星量榜首，轻量Mamba架构VLA、VLA安全与评测类新项目首次进入周度活跃榜；人形机器人领域开源机械臂、全身运动控制方案的社区贡献增速明显，低成本研究门槛持续降低；虚拟具身C端应用、大模型多模态感知工具登上今日总热榜，体现具身智能的应用边界正在从工业端向消费端延伸。

---

## 各维度热门项目
### 🤖 机器人框架/SDK
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14350，通用多关节物理仿真器，是VLA训练、机器人学习的事实标准仿真底座，近期新增了人形控制相关的API优化。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7786，基于NVIDIA Isaac Sim的统一机器人学习框架，支持VLA训练、Sim2Real全链路部署，近期新增了对开源人形G1的原生支持。
3. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5255，基于NVIDIA Warp的GPU加速物理仿真引擎，专门面向机器人学家优化，适合大批次强化学习并行训练。
4. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3854，数据流导向的开源机器人中间件，主打低延迟、可组合、分布式架构，是目前最受关注的非ROS具身应用开发中间件。
5. [RobotecAI/rai](https://github.com/RobotecAI/rai) ⭐556，厂商无关的物理AI机器人Agent框架，原生兼容ROS2，支持复杂任务编排、语音交互，是轻量级具身Agent部署的热门新方案。
6. [softmata/horus](https://github.com/softmata/horus) ⭐393，Rust编写的高实时机器人运行时系统，定位为“机器人领域的Android”，是人形机器人底层控制的新兴技术方案。

### 🧠 VLA/基础模型
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2894，面向Python基础开发者的零基础具身智能实训教程，覆盖OpenVLA、Pi0等主流VLA的从零搭建，是国内社区最火的具身入门项目。
2. [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐1943，NVIDIA开源的10B参数推理型VLA，面向自动驾驶场景，支持因果链推理，是目前参数规模最大的开源可控VLA模型。
3. [bradautomates/claude-video](https://github.com/bradautomates/claude-video) 总星暂无 +434 今日新增，为Claude大模型提供视频下载、帧提取、转录的全链路工具，可直接作为VLA模型的多模态视频输入预处理模块，今日登总热榜体现社区对大模型视觉感知落地的高需求。
4. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐442，全中文VLA领域学习面试手册，聚焦机器人领域特有挑战，是算法工程师入局具身智能的核心参考资料。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐89，通用VLA评测框架，支持任意VLA模型在仿真/真实机械臂、人形机器人上的基准测试，是物理AI评测的新兴标准工具。
6. [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐7，IROS 2026最新提出的轻量Mamba架构VLA，仅179M参数即可完成机器人操控任务，边缘部署潜力大，刚开源即进入操控主题热榜。
7. [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes) ⭐1，基于LeRobot的安全增强VLA训练方案，将碰撞避免损失嵌入模型权重而非运行时过滤，是VLA安全部署方向的最新探索。

### 🦾 操作与抓取
1. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐308，官方机器人操控基准仓库，覆盖多场景接触富集操控任务，是VLA操控能力评测的主流基准。
2. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐42，开源双臂UMI数据采集与重定向工具，支持同步数据采集、校准、遥操作，是通用操控接口UMI生态的核心工具。
3. [chang-xinhai/Awesome-Dexterous-Manipulation](https://github.com/chang-xinhai/Awesome-Dexterous-Manipulation) ⭐11，灵巧操控、触觉感知、仿人手方向的精选资源列表，覆盖论文、数据集、模拟器全链路。
4. [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8，面向VLA的双臂厨房操控基准，基于Inspect Robots构建，专门测试VLA在复杂日常场景的泛化能力。
5. [di-omics/plr-lab-robot](https://github.com/di-omics/plr-lab-robot) ⭐1，仿真优先的实验室机器人操控方案，支持眼在手上视觉、灵巧操控，面向生命科学自动化场景落地。

### 🚶 运动与导航
1. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4517，ROS2官方导航框架，是移动机器人、人形机器人自主导航的事实标准方案。
2. [enactic/openarm](https://github.com/enactic/openarm) ⭐2772，完全开源的人形机械臂，面向物理AI研究与接触富集场景部署，是目前星量最高的开源人形臂项目。
3. [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐351，人形机器人全身非线性模型预测控制方案，支持实时运动规划与操控，是人形运动控制的热门开源实现。
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐139，轻量可扩展的人形全身遥操作框架，支持低成本动捕设备接入，大幅降低人形机器人数据采集门槛。
5. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐95，清华MARS实验室开源的全模态人形运动生成模型，支持通用人形控制，刚发布即进入机器人学习热榜。
6. [THMOS2025/MOS-9-Open-Source-Humanoid-Robot](https://github.com/THMOS2025/MOS-9-Open-Source-Humanoid-Robot) ⭐17，RoboCup儿童组开源人形机器人项目，覆盖硬件、仿真、策略训练全链路，是低成本人形研究的参考方案。

### 📦 具身应用
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63240，开源机器人操作系统，目前已支持300+车型的驾驶辅助升级，是全球落地规模最大的具身智能商用项目。
2. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1160，自进化具身AI操作系统，基于Agent工作流构建，支持多机器人协同任务执行。
3. [moeru-ai/airi](https://github.com/moeru-ai/airi) 总星暂无 +572 今日新增，自托管的虚拟具身AI伴侣系统，支持实时语音交互、Minecraft/Factorio等虚拟世界自主操作，今日登总热榜体现了虚拟具身C端应用的社区关注度快速提升。
4. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐109，基于Strands Agent的自然语言机器人控制系统，支持用户用自然语言直接操控物理硬件。
5. [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8，基于VLA的开源漫游车控制方案，支持视觉-语言-动作全链路自主行驶，附带专用训练数据集。
6. [Yhx888/LocoVLA](https://github.com/Yhx888/LocoVLA) ⭐4，面向轮足机器人的VLA开源实战教程，共58节课，覆盖经典控制、RL、VLA、ROS2部署全流程。

---

## 趋势信号分析
今日数据显示，VLA的可落地化与平民化是社区核心爆发方向：一方面端侧轻量化VLA（如179M参数的Mamba架构SUREFlow）、面向部署的安全增强VLA、标准化评测工具集中出现，呼应了近期行业对VLA从实验室走向真实场景的需求；另一方面面向零基础开发者的具身实训教程星量持续走高，反映了具身智能人才缺口带来的学习刚需。此外，人形开源硬件（如2700+星的openarm）、Rust架构的高实时机器人运行时等新兴技术栈登榜，关联近期人形机器人赛道的融资热与工业落地需求，虚拟具身应用首次进入总热榜也预示C端具身场景正在启动。

---

## 社区关注热点
- 🎯 轻量VLA SUREFlow（IROS 2026）：仅179M参数的Mamba架构VLA，适配边缘部署，是机器人操控端侧落地的最新技术方向，刚开源即进入操控主题热榜。
- 🎯 开源人形臂openarm：总星破2700的完全开源人形机械臂，面向接触富集场景的物理AI研究，大幅降低人形机器人硬件研究门槛。
- 🎯 零基础具身实训项目every-embodied：国内社区最火的具身入门教程，仅需Python基础即可从零搭建OpenVLA/Pi0等主流模型，匹配具身人才培养刚需。
- 🎯 VLA评测框架inspect-robots：支持任意VLA在仿真/真实机器人上的标准化测试，是物理AI落地的核心评测工具，有望成为行业事实标准。
- 🎯 机器人运行时HORUS：Rust编写的高实时机器人底层系统，定位“机器人领域的Android”，是人形机器人控制的新兴底层技术栈。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*