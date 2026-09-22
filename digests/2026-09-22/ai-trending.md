# AI 开源趋势日报 2026-09-22

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-22 02:14 UTC

---

# 具身智能与机器人开源趋势日报（2026-09-22）
---

## 今日速览
1. 今日GitHub热榜中，数字具身（计算机使用）项目[trycua/cua](https://github.com/trycua/cua)单日新增609星，成为唯一登榜的具身领域项目，反映VLA在数字操作场景的落地正在快速获得社区关注。
2. 具身智能基础设施层持续迭代，从数据流中间件、物理仿真到VLA训练框架的全栈工具生态不断完善，哈佛CS249r具身AI教材、dora-rs中间件等高星项目保持高活跃度。
3. 人形机器人VLA落地加速，LimX、Xense等厂商密集开源OpenPI系列VLA模型的硬件适配与部署工具，开源社区的sim2real落地链路进一步打通。
4. 具身AI安全与评测方向开始显现早期热度，出现了专门针对VLA策略的红队测试工具，社区对具身系统可靠性与安全性的重视程度逐步提升。

---

## 各维度热门项目
### 🤖 机器人框架/SDK
1. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,976  
   Rust 编写的数据流导向机器人中间件，主打低延迟、可组合与分布式特性，是AI原生机器人应用的核心基础设施，近期社区生态快速扩张。
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,261  
   DeepMind开源的通用多关节动力学物理仿真器，是机器人学习、具身AI研究的事实标准工具，长期保持高活跃度。
3. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,189  
   基于NVIDIA Isaac Sim的统一机器人学习框架，支持多物理引擎与渲染器，是当前具身智能模型训练的核心底座之一。
4. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,483  
   专为机器人AI打造的多模态数据可视化、查询与流式工具，支持训练、调试全流程，是近年增长最快的机器人开发工具之一。
5. [softmata/horus](https://github.com/softmata/horus) ⭐439  
   主打高性能的机器人运行时系统，定位“机器人的安卓”，为具身智能应用提供底层 runtime 支撑，是机器人OS方向的新兴代表项目。
6. [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐225  
   统一机器人控制CLI，支持LeRobot、AlohaMini等多型机器人与多款LLM/VLA后端，兼容仿真与真实硬件，大幅降低多机器人协同开发门槛。

### 🧠 VLA/基础模型
1. [harvard-edge/cs249r_book](https://github.com/harvard-edge/cs249r_book) ⭐28,404  
   哈佛CS249r课程配套教材，涵盖ML系统、Agentic AI、物理AI（具身）四大卷，是具身智能领域最权威的系统化学习资源之一。
2. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐2,213  
   开源通用具身智能基础模型，面向开放世界的通用具身任务，是当前少数开源的全栈具身基础模型项目。
3. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,807  
   面向中文开发者的具身智能入门教程，从零构建VLA/OpenVLA/SmolVLA等模型，实战导向，是中文社区最热门的具身学习资源。
4. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐5,336  
   专为具身与Agentic AI打造的强化学习基础设施，为具身模型的训练、部署提供全链路RL支撑。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐584  
   开源物理AI评测框架，支持任意LLM/VLA在机械臂、人形机器人上的仿真/真实基准测试，填补了VLA统一评测的空白。
6. [provael/provael](https://github.com/provael/provael) ⭐7  
   新兴的VLA策略红队测试工具，可在仿真中测试开源VLA模型的安全性并输出攻击成功率，是具身AI安全方向的早期代表。

### 🦾 操作与抓取
1. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐602  
   机器人操作领域的基准测试平台，覆盖多类接触富集操作任务，为操作模型的评估提供标准化环境。
2. [NVIDIA-ISAAC-ROS/isaac_ros_cumotion](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_cumotion) ⭐270  
   NVIDIA加速的机械臂运动规划与控制ROS包，是Isaac ROS生态中操作方向的核心组件，支持工业级臂的实时控制。
3. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐142  
   将自然语言指令编译为类型安全的机器人技能图并执行的框架，支持仿真与真实硬件，是VLA落地中技能编排的新兴可靠方案。
4. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐68  
   开源双臂同步数据采集与重定向软件，支持校准、回放、遥操作，为双臂操作VLA模型的训练提供低成本数据工具。
5. [worldbench/awesome-embodied-data-pyramid](https://github.com/worldbench/awesome-embodied-data-pyramid) ⭐188  
   具身操作数据金字塔综述，系统梳理了从仿真到真实世界的操作数据层级，为VLA数据工程提供体系化参考。

### 🚶 运动与导航
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,696  
   全球规模最大的开源机器人操作系统之一，已落地300+车型的辅助驾驶升级，是移动机器人/自动驾驶领域的标杆项目。
2. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,732  
   ROS 2官方导航框架，是移动机器人导航领域的事实标准，支持路径规划、避障、SLAM对接等全链路功能。
3. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325  
   顶尖的足式/人形机器人运动控制软件，基于动量控制与优化算法，支撑多款世界级人形/足式机器人的运动控制。
4. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐118  
   清华MARS实验室出品的通用人形控制多模态运动生成模型（CoRL 2026），实现了人形机器人的全模态运动生成。
5. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,911  
   全球最流行的开源无人系统自驾框架，支持无人机、无人车、无人船等多型移动机器人的运动控制与导航。

### 📦 具身应用
1. [trycua/cua](https://github.com/trycua/cua) ⭐0 (+609 today)  
   今日热榜唯一具身相关项目，主打计算机使用2.0的开源驱动、跨OS设备集群与训练/评测/数据生成基准，是数字具身领域的新兴热门项目。
2. [physiclaw/PhysiClaw](https://github.com/physiclaw/PhysiClaw) ⭐375  
   可物理操作手机的AI具身Agent，模拟人类使用手机的方式完成任务，是物理具身在消费电子场景的典型应用。
3. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐26  
   LimX TRON2人形机器人的OpenPI策略部署方案，支持pi0.5模型服务、任务微调与真实机器人客户端，是人形VLA落地的最新厂商适配。
4. [XenseRobotics-AI/xense-openpi](https://github.com/XenseRobotics-AI/xense-openpi) ⭐16  
   Xense机器人平台的OpenPI VLA模型适配项目，支持在双臂机器人上微调与部署pi0系列模型，加速VLA的工业落地。
5. [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐9  
   基于Strands Agent的VLA漫游车项目，实现了视觉-语言-动作全链路控制的小型地面机器人，是VLA在移动机器人场景的轻量化落地案例。

---

## 趋势信号分析
今日具身领域最核心的爆发信号是**数字具身（计算机使用）**方向的快速升温，trycua/cua单日新增609星登上热榜，与近期OpenAI推出computer-use beta、行业普遍将数字操作视为VLA首个规模化落地场景的趋势高度契合，开源社区正快速补齐数字具身的驱动、基准与数据生成工具链。
其次，人形机器人VLA的硬件适配成为新兴热点，LimX、Xense等厂商集中开源OpenPI系列模型的部署方案，反映VLA正从实验室Demo走向真实硬件落地，开源生态中“模型-硬件”双向适配的节奏明显加快。
此外，具身AI安全方向出现早期项目，针对VLA策略的红队测试工具首次进入主题榜单，意味着社区在追求性能的同时，开始重视具身系统的可靠性与安全性，与全球AI监管趋严的行业背景形成呼应。（全文约290字）

---

## 社区关注热点
- **数字具身工具链（trycua/cua）**：作为今日唯一登榜的具身项目，cua填补了开源computer-use基础设施的空白，开发者可基于其快速搭建数字VLA的训练与评测环境，建议关注数字具身与物理具身的技术复用性。
- **人形VLA的硬件适配方案**：LimX、Xense等厂商接连开源OpenPI模型的硬件适配，意味着通用VLA模型的落地门槛正在快速降低，中小团队可基于开源方案快速实现VLA在自有硬件上的部署验证。
- **机器人技能编排框架（graph-as-policy）**：将自然语言编译为类型安全技能图的方案，为VLA落地提供了更可控的中间层，解决了端到端VLA可解释性差、可靠性不足的痛点，是具身智能落地的重要技术路径。
- **具身AI评测与安全工具**：从inspect-robots的统一评测到provael的红队测试，具身系统的评测与安全工具正在快速补位，随着具身应用走向真实场景，这类工具将成为开发者的必备基础设施。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*