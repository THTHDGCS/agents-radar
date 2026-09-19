# AI 开源趋势日报 2026-09-19

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-19 02:04 UTC

---

# 具身智能与机器人开源趋势日报（2026-09-19）
---

## 今日速览
1. 今日GitHub总热榜被编码Agent、开发工具类项目占据，暂无具身智能/机器人相关项目进入总榜，但主题赛道内VLA、人形机器人方向活跃度较高，涌现出多个前沿研究与产业落地成果。
2. VLA领域正从基础模型研发向落地支撑体系延伸，记忆增强、预训练数据工程、评测与安全类项目集中出现，瞄准长程能力、数据不足、标准缺失等核心痛点。
3. 人形机器人与VLA的融合成为新热点，逐际动力、Xense Robotics等产业厂商纷纷开源模型适配工具，推动VLA从单臂操作向人形全身控制拓展。
4. 世界动作模型（WAM）作为VLA的上游核心技术，首次出现统一训练框架EasyWAM，预示着VLA技术栈正从单任务模型向通用世界模型演进。

---

## 各维度热门项目
### 🤖 机器人框架/SDK
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,215  
   通用多关节接触动力学仿真引擎，机器人仿真领域的标杆工具，广泛应用于操作、人形、足式机器人研发，是具身智能算法验证的核心基础设施。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,164  
   英伟达Isaac Sim官方机器人学习统一框架，支持多物理/多渲染器，覆盖从仿真训练到真实部署的全链路，是当前机器人学习生态最完善的框架之一。
3. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐5,288  
   面向具身与Agent AI的强化学习基础设施，解决大规模RL训练的工程痛点，支撑大模型驱动的具身智能研发。
4. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,966  
   数据流导向的AI原生机器人中间件，低延迟、可组合、分布式，Rust实现，适配大模型时代的机器人应用开发需求。
5. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,878  
   ICML 2026收录的机器人数字孪生平台RoboTwin 2.0官方代码，支持高保真仿真与sim2real迁移，是具身智能仿真领域的最新成果。
6. [softmata/horus](https://github.com/softmata/horus) ⭐437  
   主打“机器人界的Android”的高性能运行时系统，Rust实现，针对人形机器人实时控制优化，是机器人底层系统赛道的新兴项目。
7. [OpenMOSS/EasyWAM](https://github.com/OpenMOSS/EasyWAM) ⭐295  
   全球首个统一的世界动作模型（WAM）训练、微调、评估框架，打通世界模型到机器人动作的落地链路，是VLA上游技术的重要突破。

### 🧠 VLA/基础模型
1. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐1,613  
   开放世界通用具身智能基础模型，瞄准通用具身智能的核心目标，是VLA领域大模型方向的代表项目。
2. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐628  
   全中文VLA实战导向学习/面试手册，聚焦机器人领域特有挑战，是国内开发者进入VLA领域的优质资源，社区热度持续上升。
3. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐536  
   开源物理AI评测框架，支持任意LLM/VLA在任意机械臂/人形机器人上的仿真/真实基准评测，解决VLA落地的评测标准化痛点。
4. [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐244  
   英伟达推出的34B参数多任务基础模型，专为自动驾驶研发设计，是VLA技术在自主移动场景的典型落地成果。
5. [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐142  
   具身AI安全综述项目，收录500+论文，覆盖感知、认知、规划、交互等全链路安全问题，是具身安全领域的最全资源库。
6. [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) ⭐55  
   首次实现原生视频记忆的VLA模型，通过带时间戳的视觉历史和流式推理解决长时序操作任务的上下文缺失问题，是VLA长程能力的关键突破。
7. [3587jjh/HuRo](https://github.com/3587jjh/HuRo) ⭐26  
   CoRL 2026收录工作，通过将人类视频机器人化实现可扩展的VLA预训练，解决VLA预训练数据不足的核心痛点。
8. [provael/provael](https://github.com/provael/provael) ⭐7  
   首个针对VLA机器人策略的红队评测工具，输出攻击成功率（ASR）指标，填补了VLA安全评测的空白。

### 🦾 操作与抓取
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐3,462  
   完全开源的人形手臂，专为物理AI研究与接触富集场景设计，支持高精度力控，填补了高端操作硬件开源的空白，大幅降低操作VLA的硬件门槛。
2. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐585  
   机器人操作基准测试平台，覆盖多类操作任务，为操作算法提供标准化评测环境，社区认可度高。
3. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐556  
   统一理解、生成、动作的机器人操作VLA模型，实现单模型支撑多类操作任务，是操作领域的前沿模型代表。
4. [InternRobotics/GenManip](https://github.com/InternRobotics/GenManip) ⭐176  
   CVPR 2025收录工作，LLM驱动的通用指令跟随操作仿真框架，通过大模型生成仿真场景解决操作数据泛化难题。
5. [murobotics-ai/handumi-sw](https://github.com/murobotics-ai/handumi-sw) ⭐68  
   开源双臂数据采集与重定向软件，支持同步采集、校准、回放，适配任意双臂机器人，是操作数据工程的核心工具。
6. [XenseRobotics-AI/xense-openpi](https://github.com/XenseRobotics-AI/xense-openpi) ⭐16  
   OpenPI VLA模型的Xense商业机械臂适配版本，支持双臂操作与触觉反馈，推动VLA模型在工业场景的落地。

### 🚶 运动与导航
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,686  
   开源自动驾驶操作系统，支持300+车型，是移动机器人自主导航领域最成熟的开源项目，具备大规模真实道路落地经验。
2. [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) ⭐15,888  
   全球最流行的开源无人系统固件，支持固定翼、多旋翼、无人车、无人船等多类平台，覆盖空中、地面、水面全场景移动机器人控制。
3. [RealXiaoze/humanoid-motion-intelligence](https://github.com/RealXiaoze/humanoid-motion-intelligence) ⭐562  
   人形机器人运动智能论文、开源项目、产业与求职知识库，是国内人形运动领域最全的资源聚合站。
4. [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐211  
   统一多机器人控制CLI，支持人形、足式、机械臂等多类硬件，兼容主流LLM与本地模型，降低多机器人协同的开发门槛。
5. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐117  
   清华MARS实验室推出的全模态人形运动生成模型，支持通用人形机器人控制，是当前人形运动智能的前沿研究成果。
6. [limxdynamics/tron2_openpi](https://github.com/limxdynamics/tron2_openpi) ⭐25  
   逐际动力TRON2机器人的OpenPI部署版本，支持pi0.5策略服务与任务微调，推动VLA模型在人形机器人上的落地。

### 📦 具身应用
1. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,537  
   机器人算法Python实现合集与经典教材，覆盖定位、规划、控制等全栈技术，是具身智能开发者入门的首选资源。
2. [harvard-edge/cs249r_book](https://github.com/harvard-edge/cs249r_book) ⭐28,322  
   哈佛CS249r课程配套教材，覆盖机器学习系统、Agent AI、物理AI四大卷，是具身智能系统方向的权威学习资料。
3. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐3,756  
   Datawhale出品的中文具身智能入门教程，仅需Python基础即可从0构建VLA/OpenVLA等模型，大幅降低国内开发者的入门门槛。
4. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,706  
   斯坦福推出的具身AI研究平台，覆盖1000+日常家庭任务，是具身智能算法泛化性验证的核心基准。
5. [FastCrest/tether](https://github.com/FastCrest/tether) ⭐84  
   边缘到云的AI部署CLI，支持Jetson、RTX、苹果硅等多硬件，带混合边云推理验证，解决VLA模型端侧部署的工程痛点。
6. [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8  
   基于VLA的真实漫游车控制项目，实现视觉-语言-动作全链路自主控制，是VLA在移动机器人场景的典型落地Demo。

---

## 趋势信号分析
当前具身智能开源社区的核心爆发点集中在**VLA落地支撑体系与人形机器人融合**两大方向。一方面，VLA领域已度过早期基础模型扎堆的阶段，近期新增的SimpleMemVLA（记忆增强）、HuRo（预训练数据工程）、inspect-robots（通用评测）、provael（安全评测）等项目，全链条覆盖VLA落地的核心痛点，说明社区开始从“做模型”转向“用模型”，技术成熟度持续提升。另一方面，人形机器人与VLA的结合明显加速，WholebodyVLA、tron2_openpi等项目先后开源，产业侧厂商主动参与生态建设，与近期人形机器人量产落地、通用人形研发加速的行业趋势高度契合。此外，首个WAM统一训练框架EasyWAM的出现，标志着VLA上游技术底座开始走向标准化。

---

## 社区关注热点
- **SimpleMemVLA（带原生记忆的VLA）**：首次实现基于时间戳视觉历史的流式推理VLA，解决长时序操作任务的上下文缺失问题，是VLA从短程抓取走向长程复杂任务的关键技术突破，值得算法研究者重点跟踪。
- **OpenArm开源人形手臂**：3.4k星的高热度开源硬件，专为接触富集场景设计，填补了高端力控手臂开源的空白，大幅降低操作VLA的硬件研发门槛，适合操作方向团队快速验证算法。
- **inspect-robots通用VLA评测框架**：支持任意VLA/LLM在任意机械臂、人形机器人上的仿真/真实评测，解决当前VLA评测标准不统一、跨平台对比难的痛点，将显著加速VLA模型的迭代效率。
- **EasyWAM世界动作模型统一框架**：全球首个WAM全链路训练框架，打通世界模型到机器人动作的落地路径，代表了VLA技术向通用化演进的新方向，是基础模型研究者的重点关注对象。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*