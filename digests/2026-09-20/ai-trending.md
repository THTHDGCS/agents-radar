# AI 开源趋势日报 2026-09-20

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-20 02:09 UTC

---

# 具身智能与机器人开源趋势日报（2026-09-20）
---

## 今日速览
1. 今日具身领域最亮眼的项目是登上GitHub Trending的[cactus-compute/needle](https://github.com/cactus-compute/needle)，这款2-bit量化后仅8-29MB的端侧自动化基础模型支持机器人、微控制器等多类设备，单日新增234星，反映社区对具身智能端侧落地的高度关注。
2. VLA领域正从模型研发转向基础设施完善，评测框架、数据体系、世界动作模型（WAM）相关项目密集出现，标志着VLA进入落地攻坚阶段。
3. 人形机器人与操作的开源生态加速成熟，从开源硬件、系统 runtime 到全栈学习资源均有新增项目，国内中文资源供给尤其活跃。
4. 数据质量与评测标准化成为当前具身智能的核心痛点，多个针对数据校验、基准测试的项目获得关注，行业正从“做模型”向“做可用的模型”转变。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、运动）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐ 63,685 — 开源机器人操作系统，已支持300+款车型的驾驶辅助升级，是大众级机器人落地的代表性框架，生态成熟度极高。
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐ 15,231 — 通用多关节接触动力学物理仿真器，是机器人学习、具身智能研究的基础工具，几乎所有主流VLA项目都依赖其仿真能力。
3. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐ 8,171 — 支持多物理引擎/渲染器的统一机器人学习框架，是NVIDIA生态下具身智能训练的核心工具，覆盖从仿真到实机部署的全流程。
4. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐ 3,968 — 数据流导向的机器人中间件，专为AI机器人应用设计，提供低延迟、可组合、分布式数据流能力，降低了具身系统的集成难度。
5. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐ 15,895 — 全球最流行的开源多模态机器人控制固件，覆盖无人机、无人车、无人船等场景，生态极其完善。
6. [rerun-io/rerun](https://github.com/rerun-io/rerun) ⭐ 11,478 — 多模态机器人数据可视化、查询与流处理工具，专为机器人训练数据优化，解决了具身研发中多模态数据调试的痛点。
7. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐ 5,657 — 基于NVIDIA Warp的GPU加速物理仿真引擎，专门针对机器人研究者优化，在接触动力学、大规模仿真场景下性能突出。

### 🧠 VLA/基础模型（视觉-语言-动作、模仿学习、强化学习）
1. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐ 2,047 — 面向通用具身智能的开放世界基础模型，是当前VLA向通用具身演进的代表性项目，覆盖多场景机器人任务。
2. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐ 629 — 全中文实战导向VLA学习/面试手册，聚焦机器人领域特有挑战，是开发者入场VLA的优质中文资源。
3. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐ 555 — 物理AI开源评测框架，支持任意LLM/VLA在机械臂/人形机器人上运行真实/仿真基准，解决了当前VLA评测碎片化的核心痛点。
4. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐ 557 — 统一理解、生成与动作能力的机器人操作VLA模型，是国内VLA技术的代表性工作。
5. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐ 301 — 世界动作模型（WAM）的统一训练/微调/评估框架，是VLA之后的新一代具身基础模型方向，融合世界模型规划能力以解决长时序任务。
6. [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) ⭐ 62 — 带原生视频记忆的VLA模型，通过时间戳视觉历史与流推理实现长时序机器人操作，填补了VLA长时记忆能力的空白。
7. [worldbench/awesome-embodied-data-pyramid](https://github.com/worldbench/awesome-embodied-data-pyramid) ⭐ 187 — 具身操作数据金字塔综述，系统梳理不同层级数据对VLA训练的价值，为数据驱动的VLA研发提供清晰路线图。

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐ 3,476 — 完全开源的人形机械臂，专为物理AI研究与接触富集环境部署设计，大幅降低了具身操作研究的硬件门槛。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐ 589 — 机器人操作基准测试官方仓库，提供标准化的操作任务评测体系，是验证操作算法性能的核心基准之一。
3. [Hebbian-Robotics/hflow](https://github.com/Hebbian-Robotics/hflow) ⭐ 273 — 机器人AI训练数据质量验证SDK，帮助团队快速排查数据问题，是VLA/操作模型落地过程中数据质量管控的关键工具。
4. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐ 176 — CVPR 2025收录工作，通过LLM驱动仿真生成可泛化的指令跟随操作数据，解决了操作训练数据不足的痛点。
5. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐ 68 — 开源双臂操作数据采集与重定向工具，支持任意双臂机器人，包含校准、QA、回放、遥操作全流程功能，是双手操作研究的实用工具。
6. [graph-robots/open-robot-skills](https://github.com/graph-robots/open-robot-skills) ⭐ 45 — 基于图策略（GAP）的机器人技能与工具包，兼容Anthropic Agent Skills格式，为操作技能的模块化复用提供了新范式。

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [softmata/horus](https://github.com/softmata/horus) ⭐ 438 — 用Rust开发的高性能机器人运行时系统，号称“机器人的Android”，针对运动控制低延迟需求优化，是人形机器人系统层的新兴方案。
2. [RealXiaoze/humanoid-motion-intelligence](https://github.com/RealXiaoze/humanoid-motion-intelligence) ⭐ 566 — 国内最全的人形机器人运动智能知识库，涵盖论文、开源项目、产业动态与求职信息，是从业者跟踪人形运动领域的核心资源。
3. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐ 325 — 全球顶级的腿式运动控制算法库，包含动量控制、步态规划等核心能力，支持人形、双足、外骨骼等多种机器人平台。
4. [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐ 213 — 统一机器人CLI工具，支持Microduck、AlohaMini、ToddlerBot等多款机器人，兼容多类LLM，内置安全合约与记忆模块，降低了多机器人协同的开发门槛。
5. [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐ 3 — 统一VLA框架实现人形全身运动-操作一体化控制，支持大空间下的复杂任务，是VLA向人形全身控制延伸的前沿探索。
6. [limxdynamics/tron2-robot-description](https://github.com/limxdynamics/tron2-robot-description) ⭐ 10 — LimX TRON2A机器人的官方模型库，包含URDF、MuJoCo、USD等格式，覆盖双臂、双足、轮腿6种变体，为人形机器人仿真与开发提供了标准化底座。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [cactus-compute/needle](https://github.com/cactus-compute/needle) 【今日Trending】 ⭐ 今日新增234（新仓库） — 面向微小设备的自动化基础模型，2-bit量化后仅8-29MB，支持工具调用、结构化提取，可部署在机器人、智能家居、微控制器等边缘端，是今日具身领域最受关注的端侧模型项目。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐ 3,770 — 国内最受欢迎的具身智能入门项目，仅需Python基础即可从零构建VLA/OpenVLA/SmolVLA/Pi0模型，大幅降低了具身智能的学习门槛。
3. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐ 2,881 — ICML 2026收录的数字孪生具身平台，实现高精度仿真到实机的迁移，是sim2real方向的代表性工作。
4. [Phyzicalorg/Phyzical_org](https://github.com/Phyzicalorg/Phyzical_org) ⭐ 292 — 浏览器端具身AI遥操作数据采集平台，兼容elizaOS生态，提供链上数据存证，解决了具身训练数据采集成本高的问题。
5. [strands-labs/robots](https://github.com/strands-labs/robots) ⭐ 162 — 基于Strands Agents的自然语言机器人控制方案，用户可通过自然语言直接操控物理硬件，是VLA落地到消费级机器人的典型应用。
6. [FastCrest/tether](https://github.com/FastCrest/tether) ⭐ 84 — 边云协同的AI部署CLI工具，支持Jetson、RTX、苹果硅等多硬件，提供混合推理与一致性验证，是具身模型端侧部署的实用工具。

---

## 趋势信号分析
今日GitHub具身智能领域的核心趋势是**端侧具身模型与基础设施层的爆发**。登上Trending的needle项目以2-bit超小体量支持机器人、微控制器等边缘设备，单日涨234星，标志着具身智能正从云端大模型向端侧轻量化渗透，适配资源受限的物理硬件，与近期人形机器人量产、端侧AI芯片迭代的行业节奏高度契合。
同时，VLA赛道的关注点已从单纯的模型效果转向评测、数据、工具链的标准化：inspect-robots跨平台评测框架、具身数据金字塔综述等项目涌现，说明VLA正从实验室研究走向落地前的生态搭建。此外，世界动作模型（WAM）相关项目增多，作为VLA的演进方向，其融合世界模型的规划能力，有望破解长时序具身任务的核心难题。（全文约280字）

---

## 社区关注热点
- **端侧具身小模型（[cactus-compute/needle](https://github.com/cactus-compute/needle)）**：2-bit量化后最小仅8MB，支持工具调用与结构化输出，可直接部署在机器人、微控制器等边缘设备，是具身智能从云端走向端侧的代表性项目，今日登上Trending反映社区关注度陡增。
- **VLA统一评测框架（[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)）**：支持任意LLM/VLA在机械臂、人形机器人上运行真实/仿真基准，解决了当前VLA评测标准碎片化、跨模型对比难的核心痛点，是VLA落地的刚需工具。
- **世界动作模型（WAM）框架（[OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM)）**：提供WAM的统一训练、微调、评估全流程工具，是VLA之后具身基础模型的核心演进方向，融合世界模型的规划能力，有望突破长时序操作任务的瓶颈。
- **开源人形操作硬件（[enactic/openarm](https://github.com/enactic/openarm)）**：完全开源的人形机械臂，专为接触富集任务设计，大幅降低了具身操作研究的硬件门槛，与当前人形机器人从“能走”向“能操作”演进的产业趋势高度呼应。
- **中文具身学习资源（[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)、[sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook)）**：从入门实操到进阶面试的全栈中文资源，贴合国内开发者需求，反映出国内具身智能人才需求快速增长，社区入场速度加快。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*