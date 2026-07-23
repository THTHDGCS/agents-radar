# AI 开源趋势日报 2026-07-23

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-23 01:45 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-23）
【数据来源】GitHub 2026-07-23 Trending实时热榜、GitHub Search API 7天内活跃的机器人/具身智能/VLA主题项目，已过滤无关通用工具、非技术类项目。

---

## 1. 今日速览
2026年7月23日GitHub具身智能与机器人领域开源生态活跃度持续走高，VLA（视觉-语言-动作）赛道形成从学习资源、模型创新、微调方法到评测体系的全栈开源供给，IROS 2026最新录用的轻量VLA工作SUREFlow首次公开源码。人形机器人方向热度不减，开源项目覆盖硬件本体、运行时系统、全身控制基础模型等全链路环节，低成本可3D打印的人形平台Microban进一步降低了人形研究的硬件门槛。无视觉空间感知技术受到社区广泛关注，基于WiFi信号的空间感知项目RuView登上GitHub总热榜，今日新增741星，为具身机器人的隐私友好型环境感知提供了全新技术路径。面向sim2real部署的轻量机器人框架成为新热点，无ROS依赖的VLA部署框架等项目大幅降低了具身模型的落地工程门槛。

---

## 2. 各维度热门项目
### 🤖 机器人框架/SDK
（覆盖仿真、控制、部署、评测等核心工具）
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,736（无今日公开新增），基于NVIDIA Isaac Sim的统一机器人学习框架，是目前工业界和学术界应用最广泛的具身智能仿真训练基座，近期新增了VLA模型训练的内置支持。
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,851（无今日公开新增），Rust开发的数据流导向机器人中间件，主打低延迟、可组合、分布式特性，是当前非ROS技术栈中最受关注的机器人应用开发框架，适合VLA模型的高性能部署。
3. [robot-control-stack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124（无今日公开新增），无ROS依赖的轻量sim2real框架，原生支持VLA模型与RL策略的训练部署，适配Franka、UR5e等主流机械臂，大幅降低具身模型的落地工程门槛。
4. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,288（无今日公开新增），行业通用的多关节接触物理仿真引擎，是几乎所有机器人学习与VLA研究的标配仿真工具，近期优化了人形机器人全身动力学的计算效率。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐12（无今日公开新增），专门面向VLA与物理AI模型的通用评测框架，支持一次定义基准、跨机器人/仿真环境运行任意策略，填补了VLA标准化评测的工具空白。

### 🧠 VLA/基础模型
（覆盖视觉-语言-动作模型、世界模型、学习资源、评测工具）
1. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐419（无今日公开新增），国内首份全中文、实战导向的VLA领域学习/面试手册，聚焦机器人领域特有的技术挑战，适合算法工程师快速入门具身智能赛道。
2. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐508（无今日公开新增），最新开源的InternVLA-A1模型，统一了机器人操作的理解、生成与动作输出能力，是目前中文语境下表现最优的端到端VLA模型之一。
3. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,817（无今日公开新增），面向Python基础开发者的具身智能入门教程，覆盖从0构建OpenVLA、SmolVLA等主流模型的全流程，是目前社区最受欢迎的具身智能实战学习资源。
4. [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐6（无今日公开新增），IROS 2026最新录用的轻量VLA工作，基于Mamba架构仅179M参数即可实现优秀的机器人操作效果，适合端侧部署的低资源场景。
5. [provael/provael](https://github.com/provael/provael) ⭐3（无今日公开新增），首个面向开源VLA策略的红队测试工具，可自动化评估VLA模型的鲁棒性并输出攻击成功率，填补了VLA安全评测的工具空白。

### 🦾 操作与抓取
（覆盖灵巧操作、UMI生态、抓取策略、操作基准）
1. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐259（无今日公开新增），通用操作接口UMI的3D SLAM与数据处理管线，可大幅提升双臂操作数据采集的精度与效率，是UMI生态的核心工具。
2. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐40（无今日公开新增），开源的双手UMI数据采集与重定向软件，支持同步采集数据并迁移到任意双臂机器人，大幅降低了灵巧操作的数据采集成本。
3. [TransDex](https://github.com/LFGfg/TransDex) ⭐8（无今日公开新增），基于点云重建预训练的3D视触觉融合灵巧操作策略，在接触富集的操作任务上表现优于现有纯视觉方案。
4. [graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐81（无今日公开新增），可将自然语言指令编译为可验证的机器人技能图并执行，支持跨仿真与真实机器人部署，提升了长周期操作任务的可靠性。
5. [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐4（无今日公开新增），面向VLA模型的双臂厨房操作基准，覆盖日常烹饪的典型接触富集任务，是评估通用操作能力的新基准。

### 🚶 运动与导航
（覆盖人形机器人、足式控制、SLAM、路径规划）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,751（无今日公开新增），完全开源的人形机器人臂，专门针对物理AI的接触富集任务设计，是目前最受关注的人形机器人硬件开源项目。
2. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐592（无今日公开新增），最新开源的人形机器人全身控制基础模型，支持统一生成行走、操作等全身运动，是通用人形机器人控制的核心技术突破。
3. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐94（无今日公开新增），清华MARS实验室开源的全模态人形运动生成模型，支持多模态输入生成全身控制指令，是最新的人形控制基础模型工作。
4. [softmata/horus](https://github.com/softmata/horus) ⭐392（无今日公开新增），Rust开发的高性能机器人运行时系统，号称“机器人的Android”，主打低延迟、高并发的运动控制，是人形机器人系统层的新兴技术方案。
5. [Rhoban/microban](https://github.com/Rhoban/microban) ⭐41（无今日公开新增），低成本可3D打印的开源人形机器人，基于树莓派Zero 2W驱动，总成本不到1000元，大幅降低了人形机器人研究的入门门槛。

### 📦 具身应用
（覆盖感知、落地部署、遥操作、自主系统）
1. [ruvnet/RuView](https://github.com/ruvnet/RuView) ⭐0（今日新增+741），今日GitHub总热榜唯一机器人相关项目，可将通用WiFi信号转化为实时空间感知能力，无需摄像头即可实现环境建模、存在检测，为具身机器人提供了隐私友好的新型感知方案，适合家庭、办公等隐私敏感场景的机器人部署。
2. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,193（无今日公开新增），全球最成熟的开源自动驾驶系统，同时也是面向移动机器人的通用机器人操作系统，目前已支持300+款车型，是具身智能在出行领域的标杆落地项目。
3. [DexForce/EmbodiChain](https://github.com/DexForce/EmbodiChain) ⭐198（无今日公开新增），端到端GPU加速的模块化具身智能开发平台，支持快速构建通用具身智能应用，是国内首个开源的全栈具身智能平台。
4. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐946（无今日公开新增），基于代理工作流的自进化具身AI操作系统，支持机器人自主学习新技能，是具身智能系统层的新兴探索。
5. [minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐221（无今日公开新增），面向大语言模型的最小闭环物理具身架构，自带自感知环路，可快速将LLM接入实体机器人，实现简单的具身交互任务。

---

## 3. 趋势信号分析
今日开源数据显示，VLA全栈生态正进入爆发期，从入门教程、模型创新、微调方法到评测、安全工具的全链条供给已成型，尤其是轻量端侧VLA（如179M参数的SUREFlow）和标准化评测工具的密集出现，标志着VLA正从实验室研究走向规模化落地。人形机器人开源生态成熟度快速提升，覆盖低成本硬件、运行时系统、全身控制基础模型的全链路项目持续涌现，与近期人形机器人产业融资热潮、工业场景试点落地的行业趋势高度呼应。新兴技术方面，无视觉的隐私友好型感知技术（如基于WiFi的RuView）首次登上GitHub总热榜，为具身机器人在家庭等隐私敏感场景的落地提供了新路径，有望成为下一代具身感知的重要分支。（全文292字）

---

## 4. 社区关注热点
- **轻量端侧VLA技术**：以SUREFlow为代表的百万参数级VLA模型，能够适配端侧机器人的算力限制，是未来消费级具身机器人的核心技术，开发者可重点关注相关模型的部署优化。
- **无ROS机器人开发栈**：以robot-control-stack、dora为代表的非ROS轻量框架，大幅降低了VLA模型sim2real部署的工程复杂度，适合中小型团队快速落地具身应用。
- **低成本人形机器人平台**：以Microban为代表的千元级开源人形硬件，大幅降低了人形机器人研究的入门门槛，适合个人开发者和小型团队开展人形控制、VLA部署的实验。
- **VLA安全与评测技术**：以inspect-robots、provael为代表的VLA评测与红队工具，填补了VLA可靠性评估的空白，是VLA落地前必须解决的核心问题，相关方向的研究价值持续提升。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*