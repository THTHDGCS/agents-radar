# AI 开源趋势日报 2026-08-19

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-08-19 00:34 UTC

---

# 具身智能与机器人开源趋势日报
**日期：2026年8月19日**

---

## 今日速览
今日GitHub总榜Trending无直接相关的具身智能/机器人项目，领域热度主要集中在细分主题的7天活跃仓库中。VLA领域呈现全链条工程化发展态势，从模型微调、评估工具到安全测试的配套设施陆续涌现。人形机器人开源生态加速完善，运动控制基础模型与全栈硬件平台同步迭代。具身智能入门教育与资源整合类项目获得较高社区关注，反映开发者入局速度加快。Rust编写的高性能机器人基础设施占比持续提升，成为技术栈演进的重要信号。

---

## 各维度热门项目
注：以下项目均来自7天内活跃的GitHub主题搜索，星数为累计总星数，无单独今日新增数据。

### 🤖 机器人框架/SDK
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,914
   基于NVIDIA Isaac Sim构建的统一机器人学习框架，支持仿真到实机的全链路研发，是当前机器人学习领域最主流的仿真开发工具之一。
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,589
   DeepMind开源的通用多关节接触动力学仿真器，是机器人动力学仿真的事实标准，广泛应用于运动控制、操作学习等核心方向。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,884
   Rust编写的数据流导向机器人中间件，提供低延迟、可组合的分布式数据流水线，是新兴的高性能机器人应用开发框架。
4. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,481
   基于NVIDIA Warp的GPU加速物理仿真引擎，针对机器人研究优化，支持大规模并行仿真，可显著提升强化学习训练效率。
5. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,319
   多模态机器人数据可视化与流式处理工具，支持视觉、点云、轨迹等多类型数据的实时查看与标注，是机器人研发的核心调试工具。

### 🧠 VLA/基础模型
1. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐520
   国内首份全中文VLA实战学习/面试手册，聚焦机器人领域特有挑战，覆盖算法、工程、面试全流程，适合开发者快速入门VLA方向。
2. [BridgeVLA/BridgeVLA](https://github.com/BridgeVLA/BridgeVLA) ⭐218
   BridgeVLA与BridgeVLA++的官方实现，是跨场景通用VLA模型的代表性工作，支持多种机器人平台的操作任务迁移。
3. [xiaomi-research/recogdrive](https://github.com/xiaomi-research/recogdrive) ⭐586
   小米研究院ICLR 2026录用工作，提出端到端自动驾驶的强化认知框架，是VLA技术在自动驾驶场景的典型落地探索。
4. [dwipddalal/Anchor-Align](https://github.com/dwipddalal/Anchor-Align) ⭐23
   提出通过表示锚定与语言-动作对齐的通用VLA微调方法，可显著提升VLA模型的跨场景泛化能力，是近期VLA微调方向的重要新进展。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐143
   物理AI开源评估工具，支持在任意机械臂/人形机器人上运行LLM/VLA模型的基准测试，填补了VLA实机统一评估工具的空白。

### 🦾 操作与抓取
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,862
   完全开源的人形机械臂项目，面向接触富集环境的物理AI研究与部署，是当前开源度最高的人形操作硬件平台之一。
2. [vikashplus/robohive](https://github.com/vikashplus/robohive) ⭐630
   统一的机器人操作学习框架，提供丰富的接触富集操作任务基准与预训练策略，广泛应用于灵巧操作研究。
3. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐46
   开源双手同步数据采集与重定向软件，支持任意双臂机器人的示教数据采集，是UMI（通用操作接口）生态的核心工具。
4. [chang-xinhai/Awesome-UMI](https://github.com/chang-xinhai/Awesome-UMI) ⭐14
   UMI生态的精选资源列表，覆盖论文、数据集、策略、分类体系，是跟进通用操作技术进展的一站式索引。
5. [adsade5/so101-visual-tactile-grasp](https://github.com/adsade5/so101-visual-tactile-grasp) ⭐1
   基于ROS2的SO-101机械臂视觉-触觉抓取系统，集成FK/IK、轨迹规划与FlexiTac触觉反馈，是多模态抓取的工程实现参考。

### 🚶 运动与导航
1. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐629
   地平线机器人开源的人形全身控制基础模型，支持多场景下的人形机器人运动生成，是国内人形运动基础模型的代表性工作。
2. [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover) ⭐9,587
   NASA JPL开源的6轮火星车DIY项目，完整覆盖移动机器人机械设计、电子、导航算法，是移动机器人学习的经典参考。
3. [ClemensElflein/OpenMower](https://github.com/ClemensElflein/OpenMower) ⭐6,672
   开源RTK GPS智能割草机器人项目，可改造普通消费级割草机实现自主导航，是移动机器人落地民用场景的典型案例。
4. [Renkunzhao/legged-daily](https://github.com/Renkunzhao/legged-daily) ⭐21
   足式机器人与基于学习的运动控制方向的每日资源更新，包含论文、代码、产业动态，适合足式方向研究者跟进。
5. [ProMineGG/Open-Humanoid-180](https://github.com/ProMineGG/Open-Humanoid-180) ⭐1
   180cm身高的开源人形机器人项目，采用BLDC执行器与分布式CAN控制，集成YOLO+VLM端侧AI，是全栈开源人形硬件的新尝试。

### 📦 具身应用
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,234
   数据鲸开源的具身智能入门教程，主打Python基础即可从零构建VLA/具身机器人，覆盖OpenVLA、SmolVLA等主流模型，是当前最受欢迎的具身入门资源。
2. [Octoday-Hub/Embodied-AI](https://github.com/Octoday-Hub/Embodied-AI) ⭐2,243
   星期八具身智能生态社区的聚合仓库，整合论文、项目、课程、数据集、招聘等资源，连接全球开发者与产业伙伴，是国内具身领域的核心社区之一。
3. [PhyAgentOS-dev/PhyAgentOS](https://github.com/PhyAgentOS-dev/PhyAgentOS) ⭐1,723
   自进化具身AI操作系统，基于Agent工作流构建，支持机器人的自主任务规划、技能学习与迭代，是具身智能系统架构的新探索。
4. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,640
   斯坦福大学开源的具身AI研究平台，包含1000+真实家庭场景任务，是具身智能算法评估的主流基准之一。
5. [knightnemo/Awesome-World-Models](https://github.com/knightnemo/Awesome-World-Models) ⭐3,319
   世界模型方向的精选资源列表，覆盖具身智能、机器人等应用场景，世界模型作为具身智能的核心技术，相关资源关注度持续上升。

---

## 趋势信号分析
当前具身智能领域的核心热度正从单点技术突破向全栈工程化落地转移。VLA方向不再仅聚焦模型架构创新，微调方法（如Anchor-Align）、跨平台评估工具（inspect-robots）、安全红队测试等配套工具快速补齐，与近期行业内VLA模型从实验室走向实机测试的节奏高度契合。人形机器人领域，开源硬件（openarm、Open-Humanoid-180）与运动基础模型（HoloMotion）同步推进，反映产业链上下游正在通过开源降低研发门槛，加速技术迭代。此外，Rust语言在机器人中间件、操作系统等基础设施层的渗透率快速提升，其低延迟、内存安全的特性恰好匹配机器人实时控制的需求，成为值得关注的技术栈方向。（全文约280字）

---

## 社区关注热点
- 【VLA工程化工具链】：从微调（Anchor-Align）、评估（inspect-robots）到安全测试的VLA全栈工具链正在快速完善，建议开发者重点跟进，可大幅降低VLA模型落地的工程成本。
- 【人形开源硬件生态】：enactic/openarm等开源人形机械臂项目Star数逼近3k，结合全栈开源人形机器人项目陆续出现，硬件开源正在成为具身智能落地的重要推动力，适合硬件与算法开发者协同参与。
- 【具身智能入门资源】：datawhalechina/every-embodied、VLA-Handbook等入门教程/手册关注度持续走高，反映行业人才缺口较大，零基础入门资源是当前社区的刚性需求，适合新入局者学习参考。
- 【Rust系机器人基础设施】：dora-rs/dora、robonix、horus等Rust编写的机器人中间件/操作系统密集出现，Rust的性能与安全特性正在获得机器人领域认可，底层开发者可提前布局该技术方向。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*