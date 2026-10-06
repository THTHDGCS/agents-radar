# AI 开源趋势日报 2026-10-06

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-10-06 03:40 UTC

---

# 具身智能与机器人开源趋势日报
**日期**：2026-10-06  
**数据来源**：GitHub Trending 实时榜、GitHub 主题搜索（7天活跃项目）

---

## 今日速览
今日 GitHub 具身智能与机器人领域中，AI 辅助机器人设计工具 `text-to-cad` 登上总 Trending 榜，单日新增 437 星，反映 Agent 能力向硬件研发流程渗透的新趋势。学术侧有多篇顶会论文集中开源，包括 CoRL 2026 Oral 的人形足球射门项目 `RoboNaldo`、NeurIPS 2026 的 VLA 预训练工作 `VLAct`，覆盖人形运动控制与 VLA 训练前沿。世界动作模型（WAM）方向涌现从基础模型到训练框架的全栈开源项目，成为 VLA 落地的核心抓手。此外，操作基准、双臂数据工具、开源人形臂等项目持续迭代，支撑具身智能从算法到硬件的全链路发展。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,285
   统一机器人学习框架，支持多物理引擎与渲染器，是当前具身智能仿真训练的主流基础设施，社区生态完善。
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,993
   数据流式机器人中间件，低延迟、可组合、分布式设计，适配 AI 原生机器人应用开发，Rust 实现性能优异。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,474
   通用多关节接触动力学仿真器，是人形机器人、操作任务仿真的事实标准，支持从研究到落地的全流程。
4. [omnilink-tech/omnisim](https://github.com/omnilink-tech/omnisim) ⭐186
   面向编码 Agent 的开源机器人仿真器，支持 HTTP/JSON+MCP 控制、Newton 物理、ROS2 与可复现基准，是 Agent+仿真的新兴工具。
5. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐11,549
   多模态机器人数据可视化与流式工具，支持视觉、IMU、关节数据等多模态同步展示，大幅提升机器人调试效率。
6. [Hebbian-Robotics/hflow](https://github.com/Hebbian-Robotics/hflow) ⭐286
   机器人训练数据质量验证 SDK，帮助团队快速筛查 AI 模型训练数据的缺陷，解决具身数据质量痛点。

---

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐2,205
   面向通用具身智能的开放世界基础模型，是当前开源 VLA/世界模型方向的高潜力项目，覆盖多场景具身任务。
2. [black-forest-labs/flux-action](https://github.com/black-forest-labs/flux-action) ⭐133
   Black Forest Labs 开源的 7B 权重世界动作模型，支持机器人（DROID、SO-101）、仿真与游戏的动作预测，是 VLA 领域的新基础模型选项。
3. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐643
   开源物理 AI 评估框架，支持任意 LLM/VLA 在任意机械臂/人形机器人上的仿真/真实基准测试，解决 VLA 落地的统一评估难题。
4. [starVLA/VLAct](https://github.com/starVLA/VLAct) ⭐139
   NeurIPS 2026 收录工作，提出以表示为中心的 VLA 持续预训练方法，突破数据 scaling 的瓶颈，是 VLA 训练的前沿进展。
5. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐675
   全中文实战导向的 VLA 学习/面试手册，聚焦机器人领域特有挑战，适合国内开发者快速入门 VLA 方向。
6. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,924
   面向 Python 基础开发者的具身智能入门教程，从 0 搭建 VLA/OpenVLA/SmolVLA/Pi0，实操性强，社区热度高。
7. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐396
   世界动作模型统一训练、微调与评估框架，降低 WAM 模型的开发门槛，适配多种具身任务场景。

---

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐3,574
   完全开源的人形机械臂，面向接触富集环境的物理 AI 研究与部署，是人形操作方向的核心开源硬件平台。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐672
   统一的 sim-real 机器人操作基准，用于全面评估通用机器人操作策略，是操作领域的新基准工具。
3. [XPolicyLab/XPolicyLab](https://github.com/XPolicyLab/XPolicyLab) ⭐395
   集成 50+ 先进操作策略的工具库，获 IROS 2026 ScaleInfra Workshop 最佳工具论文，方便研究者快速对比不同操作算法。
4. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐75
   开源双臂同步数据采集与重靶向软件，支持校准、QA、回放与遥操作，适配任意双臂机器人，降低双臂操作数据采集门槛。
5. [XenseRobotics-AI/lerobot-xense](https://github.com/XenseRobotics-AI/lerobot-xense) ⭐20
   LeRobot v5.1 分叉版本，新增 Flexiv Rizon4、Elite CS66、ARX5 等多型号机械臂与触觉夹爪支持，覆盖单臂/双臂操作场景。
6. [RunpeiDong/HERO](https://github.com/RunpeiDong/HERO) ⭐9
   CoRL 2026 收录工作，提出人形末端执行器控制方法，实现视觉全身开放词汇物体抓取，是人形操作的前沿进展。

---

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,825
   开源机器人操作系统，已适配 300+ 车型的高级驾驶辅助，是移动机器人/自动驾驶领域落地最成熟的开源项目之一。
2. [RealXiaoze/humanoid-motion-intelligence](https://github.com/RealXiaoze/humanoid-motion-intelligence) ⭐617
   人形机器人运动智能知识库，汇总论文、开源项目、产业动态与求职信息，是国内人形机器人开发者的重要参考资源。
3. [OpenDriveLab/RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo) ⭐55
   CoRL 2026 Oral 论文，实现精准、稳定、强力的人形足球射门，代表人形机器人动态运动控制的最新学术水平。
4. [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐380
   人形全身非线性 MPC 控制器，用于实时人形运动-操作规划与控制，支持复杂场景下的全身协同任务。
5. [lok-i/vibe](https://github.com/lok-i/vibe) ⭐47
   人形全身跟踪后训练工具，面向感知控制任务，提升人形机器人对自身状态与环境的感知精度。
6. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐325
   成熟的腿式运动算法库，包含动量控制器与优化框架，支撑多款世界级人形、足式机器人的运动控制。

---

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) ⭐17,496 (+437 today)
   今日 Trending 唯一机器人相关项目，为 AI Agent 赋予 CAD 设计能力，可用于机器人零部件快速设计，是 AI 辅助机器人研发的新兴工具。
2. [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core) ⭐2,718
   递归自改进的物理 Agent 操作系统，通过 Agent 工作流实现自我迭代，是具身智能系统架构的新探索。
3. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐175
   基于 Strands Agents 的自然语言机器人控制方案，支持用户用自然语言直接控制物理硬件，降低机器人使用门槛。
4. [AccelerationConsortium/Matterix](https://github.com/AccelerationConsortium/Matterix) ⭐62
   面向化学实验室自动化的机器人数字孪生平台，是具身智能在科学场景落地的典型应用。
5. [Justin-Riekehof/zeroth-01-build](https://github.com/Justin-Riekehof/zeroth-01-build) ⭐3
   K-Scale Zeroth-01 3D 打印开源人形的构建日志与软件栈，包含 MuJoCo/ksim RL 训练与树莓派 sim2real 部署，是低成本人形机器人落地的参考项目。
6. [pradeepsuryad/Xr_quest2_Unitree](https://github.com/pradeepsuryad/Xr_quest2_Unitree) ⭐1
   用 Meta Quest 2 头显遥操作 MuJoCo 中 Unitree G1 人形的工具链，是 VR+人形遥操作的轻量实现方案。

---

## 趋势信号分析
当前具身智能领域呈现三大爆发方向：一是人形机器人的「运动+操作」融合技术，CoRL 2026 多篇相关论文（RoboNaldo、HERO）集中放出，学术研究正从单一点突破转向全身协同能力，匹配行业内人形机器人从演示到实用的落地节奏；二是世界动作模型（WAM）栈快速完善，从 flux-action、opendm 等基础模型，到 EasyWAM、Alpamayo Recipes 等训练工具形成完整链路，标志着 VLA 从通用视觉语言向具身动作预测的深度下沉；三是 AI 辅助机器人设计成为新兴交叉方向，text-to-cad 登 Trending 总榜说明 Agent 能力正在渗透到机器人研发的上游环节，有望大幅降低硬件开发的门槛与周期。整体来看，开源社区正围绕「模型-硬件-工具」全链条加速具身智能的落地验证。

---

## 社区关注热点
- 🎯 [text-to-cad](https://github.com/earthtojake/text-to-cad)：今日唯一登上 GitHub 总 Trending 的机器人相关项目，单日新增 437 星，AI Agent+CAD 的组合为机器人硬件设计提供了新效率工具，适合开发者关注如何用 AI 加速机器人零部件、结构迭代。
- 🎯 [black-forest-labs/flux-action](https://github.com/black-forest-labs/flux-action)：Black Forest Labs 新开源的 7B 权重世界动作模型，是继 FLUX 图像模型后在具身动作领域的延伸，支持多种机器人与仿真场景，是 VLA 开发者值得跟进的新基础模型选项。
- 🎯 [RoboNaldo](https://github.com/OpenDriveLab/RoboNaldo)：CoRL 2026 Oral 论文项目，实现了高精度、高稳定性的人形足球射门，代表人形机器人动态运动控制的顶尖学术水平，对人形运动控制研发有重要参考价值。
- 🎯 [inspect-robots](https://github.com/robocurve/inspect-robots)：开源物理 AI 统一评估工具，解决了当前 VLA 模型跨硬件、跨场景评估难的痛点，支持从机械臂到人形、从仿真到真实的全维度测试，是 VLA 落地的必备工具。
- 🎯 [openarm](https://github.com/enactic/openarm)：完全开源的人形机械臂，面向接触富集场景的物理 AI 研究，填补了开源人形操作硬件的空白，适合团队快速搭建人形操作实验平台。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*