# AI 开源趋势日报 2026-09-15

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-09-15 02:16 UTC

---

# 具身智能与机器人开源趋势日报（2026-09-15）

---

## 今日速览
今日GitHub具身智能与机器人领域热度攀升，非视觉感知、群体智能两个方向登上总Trending榜，其中WiFi空间感知项目RuView、通用群体智能引擎MiroFish分别获得383、560的当日新增stars，社区关注度爆发。VLA技术路径持续多元，NVIDIA推出34B多任务VLA模型Alpamayo 2，长时序记忆VLA、人类视频预训练VLA、人形全身VLA等细分方向均有新项目涌现，基础模型与具身场景的结合不断深化。人形机器人生态进一步完善，从低成本DIY硬件、全身运动基础模型到统一管控工具覆盖全栈，无ROS的轻量sim2real框架开始出现，降低开发者落地门槛。具身数据与评测基础设施受到更多关注，遥操作数据平台、统一评测工具等项目持续活跃，成为支撑VLA模型从实验室走向落地的关键支撑。

---

## 各维度热门项目

### 🤖 机器人框架/SDK（控制、仿真、规划、中间件）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐15,144  
   通用多关节接触动力学物理仿真器，是机器人仿真与具身智能研究的事实标准工具，广泛应用于运动控制、操作等场景。
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐8,122  
   基于NVIDIA Isaac Sim的统一机器人学习框架，支持VLA、RL等多种训练范式，是当前工业界主流的仿真训练平台。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,936  
   Rust编写的数据流导向机器人中间件，低延迟、可组合、分布式的特性适配AI机器人的多模态处理需求，是下一代机器人中间件的代表项目。
4. [newton-physics/newton](https://github.com/newton-physics/newton) ⭐5,635  
   基于NVIDIA Warp的GPU加速物理仿真引擎，专为机器人研究者优化，仿真效率较传统引擎显著提升。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐479  
   物理AI开源评测工具，支持任意LLM/VLA在机械臂、人形机器人的仿真/真实基准上运行，填补了VLA统一评测的空白。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐160  
   轻量无ROS的sim2real框架，原生支持VLA/RL模型的训练与部署，适配多种主流机械臂，大幅降低AI机器人落地门槛。
7. [baidu-baige/LoongForge](https://github.com/baidu-baige/LoongForge) ⭐564  
   高性能训练框架，支持LLM/VLM/扩散/具身模型训练，适配NVIDIA GPU和昆仑芯XPU，是国产具身模型训练工具的代表。

### 🧠 VLA/基础模型（视觉-语言-动作、世界模型、运动基础模型）
1. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐675  
   开放世界通用具身智能基础模型，瞄准通用具身AI的核心目标，是该方向少有的开源项目。
2. [NVlabs/alpamayo2](https://github.com/NVlabs/alpamayo2) ⭐239  
   NVIDIA推出的34B多任务VLA基础模型，面向自动驾驶场景，支持推理、导航、VQA等多任务，是大厂最新的VLA技术成果。
3. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐692  
   全身人形控制基础模型，实现人形机器人全身运动的统一建模，是人形机器人运动智能的重要突破。
4. [zju3dv/INTACT-JEPA](https://github.com/zju3dv/INTACT-JEPA) ⭐191  
   浙大提出的同构意图到动作学习框架，基于JEPA构建无搜索世界模型，为具身智能的世界模型研究提供了新路径。
5. [OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA) ⭐33  
   带原生视频记忆的VLA模型，通过带时间戳的视觉历史和流式推理解决长时程机器人操作问题，是VLA技术的重要迭代方向。
6. [3587jjh/HuRo](https://github.com/3587jjh/HuRo) ⭐23  
   CoRL 2026录用工作，通过将人类视频“机器人化”生成训练数据，有效缓解VLA预训练数据稀缺的痛点。

### 🦾 操作与抓取（灵巧手、技能图、双臂操作）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐3,084  
   全开源人形机械臂，专为物理AI研究和接触富集环境设计，是当前最热门的开源人形操作硬件项目。
2. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐134  
   提出“图即策略”范式，将自然语言指令编译为可验证的机器人技能图，可在仿真/真实机器人上直接执行。
3. [allenai/MolmoBot](https://github.com/allenai/MolmoBot) ⭐106  
   AI2推出的MolmoBot系统，基于大规模仿真训练实现零样本机器人操作，是操作领域的最新进展。
4. [XenseRobotics-AI/xense-openpi](https://github.com/XenseRobotics-AI/xense-openpi) ⭐16  
   将π₀系列VLA模型适配到Xense双臂机器人平台，支持微调和真实世界部署，是VLA落地双臂操作的典型案例。
5. [XenseRobotics-AI/xense-taccap-lerobot](https://github.com/XenseRobotics-AI/xense-taccap-lerobot) ⭐14  
   基于LeRobot的视触觉数据采集工具，支持Pico4遥操作和XTac-UMI夹爪，填补了低成本触觉数据采集工具的空白。

### 🚶 运动与导航（足式、人形、SLAM、运动控制）
1. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐117  
   清华MARS实验室推出的全模态运动生成模型，用于通才人形机器人全身控制，是人形运动智能的前沿研究成果。
2. [Rhoban/microban](https://github.com/Rhoban/microban) ⭐365  
   低成本、全3D打印的开源人形机器人平台，基于树莓派Zero 2W和19个Dynamixel舵机，是DIY人形机器人与运动控制研究的入门首选。
3. [Open-X-Humanoid/BICMap](https://github.com/Open-X-Humanoid/BICMap) ⭐75  
   WebGL驱动的机器人地图可视化SDK，支持SLAM地图、点云、3D模型渲染与导航交互，大幅提升机器人导航调试效率。
4. [rsamf/asimov-rgmt](https://github.com/rsamf/asimov-rgmt) ⭐4  
   Asimov v1人形机器人的鲁棒通用运动跟踪方案，基于PPO算法和Newton物理引擎实现，是人形运动控制的最新研究进展。
5. [Renkunzhao/legged-daily](https://github.com/Renkunzhao/legged-daily) ⭐22  
   足式机器人与基于模型/学习的控制方向的论文、代码、资源合集，是足式机器人研究者的一站式资源库。

### 📦 具身应用（sim2real、遥操作、落地场景）
1. [666ghj/MiroFish](https://github.com/666ghj/MiroFish) ⭐0 (+560 today)  
   今日热榜项目，简洁通用的群体智能引擎，可支撑群体机器人协同决策、多智能体系统等场景，当日新增stars超500，社区关注度爆发。
2. [ruvnet/RuView](https://github.com/ruvnet/RuView) ⭐0 (+383 today)  
   今日热榜项目，基于商用WiFi信号实现实时空间智能、生命体征监测与存在检测，无需摄像头，为具身机器人提供低功耗、高隐私的环境感知方案。
3. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,650  
   开源机器人操作系统，已支持300+车型的辅助驾驶升级，是具身智能在自动驾驶领域规模最大的落地项目。
4. [PhyAgentOS/PhyAgentOS-core](https://github.com/PhyAgentOS/PhyAgentOS-core) ⭐2,281  
   递归自提升的物理Agent操作系统，通过Agent工作流实现自我迭代，是物理智能体操作系统的前沿探索。
5. [Phyzicalorg/Phyzical_org](https://github.com/Phyzicalorg/Phyzical_org) ⭐310  
   浏览器端遥操作数据采集平台，为具身AI提供训练数据，支持轨迹格式转换和链上存证，是具身数据基础设施的新方向。
6. [rokbenko/quackd](https://github.com/rokbenko/quackd) ⭐198  
   统一CLI工具，可控制双足机器人、机械臂、移动底盘等多型硬件，支持多LLM后端、MCP协议与安全合约，降低多机器人管控的复杂度。

---

## 趋势信号分析
今日具身智能开源社区的爆发性关注点集中在**边缘侧非视觉感知**和**群体智能引擎**两个方向，二者均登上GitHub总Trending榜，当日新增stars均超350，反映出社区对具身智能的探索正在从“模型优先”向“感知-协同-落地”全栈延伸，低功耗、高隐私的无摄像头感知方案，以及支撑多机器人协同的群体智能技术成为新的热门赛道。
新兴技术栈方面，**无ROS的轻量sim2real框架**开始进入主流视野，RobotControlStack等项目提出原生适配VLA/RL训练部署的轻量方案，摆脱ROS的复杂度，更适配AI机器人的快速迭代需求，有望成为中小团队落地VLA的首选技术路径。
本次榜单中人形机器人相关项目占比超30%，覆盖硬件、运动控制、VLA全链条，与近期全球人形机器人产业融资热潮、VLA模型工业落地加速的行业趋势形成明显共振。

---

## 社区关注热点
- **[ruvnet/RuView](https://github.com/ruvnet/RuView)**：利用WiFi信号实现空间感知的方案无需摄像头、隐私性强、成本极低，可广泛应用于服务机器人、智能家居、工业监测等场景，今日登榜反映边缘具身感知的需求正在爆发。
- **[dora-rs/dora](https://github.com/dora-rs/dora)**：Rust编写的数据流导向机器人中间件，低延迟、可组合的特性完美适配AI机器人的多模态数据处理需求，是当前最活跃的下一代机器人中间件项目，生态正在快速扩张。
- **[OpenBMB/SimpleMemVLA](https://github.com/OpenBMB/SimpleMemVLA)**：带原生视频记忆的VLA模型解决了长时程操作的记忆痛点，流式推理的设计更适配真实机器人的实时交互需求，代表了VLA技术的重要迭代方向。
- **[enactic/openarm](https://github.com/enactic/openarm)**：全开源的人形机械臂是接触富集任务研究的关键硬件参考，3k+ stars反映社区对人形操作硬件开源的强烈需求，有望推动人形操作研究的普惠化。
- **[RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)**：无ROS的轻量sim2real框架大幅降低了VLA模型的部署门槛，原生支持多种主流机械臂，适合中小团队快速验证VLA落地效果，是极具潜力的新兴工具。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*