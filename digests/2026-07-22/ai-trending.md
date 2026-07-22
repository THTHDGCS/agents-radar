# AI 开源趋势日报 2026-07-22

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-22 01:25 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-22）
---
## 今日速览
今日具身智能与机器人开源社区核心动向集中在VLA落地工具链、人形机器人技术栈两大方向：一方面，IROS 2026接收的轻量端侧VLA、新型VLA微调方法、统一评测框架等项目密集开源，社区正从VLA模型的精度竞赛转向落地适配；另一方面，无ROS的轻量sim2real部署框架、高性能机器人运行时、低成本开源人形硬件持续涌现，大幅降低实机部署门槛。此外，面向机器人硬件设计的AI Agent工具首次登上GitHub Trending，打通具身智能从软件到硬件的研发链路，国内开源生态的VLA教程、模型贡献突出，覆盖从入门到产业落地的全链路需求。

---
## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、中间件、评测）
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7722  
   基于NVIDIA Isaac Sim的统一机器人学习框架，是目前工业界和学术界最主流的具身智能仿真训练基座，持续支持VLA、人形机器人等前沿方向的研发。
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3850  
   数据流驱动的低延迟机器人中间件，支持分布式、可组合的AI机器人应用构建，专为VLA模型的实机部署设计，生态快速扩张。
3. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124  
   无ROS的轻量sim2real框架，原生支持MuJoCo Gymnasium封装，可直接部署VLA和RL策略到Franka、UR5e等主流机械臂，大幅降低落地门槛。
4. [softmata/horus](https://github.com/softmata/horus) ⭐391  
   Rust开发的高性能机器人运行时系统，定位为机器人领域的Android，解决异构硬件与AI模型的适配问题，近期社区关注度快速上升。
5. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14276  
   通用多关节接触物理仿真引擎，是几乎所有VLA和机器人学习项目的默认仿真环境，生态完善且持续优化。
6. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐12  
   VLA/物理AI模型的统一评测框架，一次定义基准即可在任意机器人/仿真上运行不同策略，填补VLA标准化评测的空白。
7. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4197  
   专为具身和Agentic AI设计的强化学习基础设施，简化从仿真训练到实机部署的RL pipeline。

---
### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、RL策略、世界模型）
1. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐507  
   商汤开源的InternVLA-A1，统一理解、生成、动作能力的机器人操作VLA，是国内首个全栈开源的通用VLA系列模型，近期热度持续走高。
2. [Open-X-Humanoid/XR-1](https://github.com/Open-X-Humanoid/XR-1) ⭐186  
   面向人形机器人的通用VLA模型，通过学习统一视觉-运动表征实现多任务跨场景泛化，是人形VLA的代表性开源工作。
3. [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐5  
   IROS 2026接收的轻量VLA模型，基于Mamba架构仅179M参数，适合边缘端机器人部署，是VLA轻量化的前沿代表性工作。
4. [dexmal/opendm](https://github.com/dexmal/opendm) ⭐101  
   面向通用具身智能的开放世界基础模型，支持跨机器人、跨任务的零样本泛化，为新晋开源的高性能具身基础模型。
5. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐590  
   地平线上线的人形全身控制基础模型，实现人形机器人行走、操作、避障等全技能的统一建模。
6. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2795  
   国内首个面向入门者的具身智能实战教程，从0搭建VLA/OpenVLA/SmolVLA/Pi0全栈，仅需Python基础即可上手，是开发者进入具身领域的核心学习资源。
7. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐417  
   全中文VLA学习/面试手册，聚焦机器人领域特有挑战，覆盖算法、工程、落地全流程，是VLA算法工程师的必备参考。

---
### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务、操作基准）
1. [enactic/openarm](https://github.com/enactic/openarm) ⭐2749  
   完全开源的人形机械臂，专为接触富集环境的物理AI研究和部署设计，是目前开源社区最成熟的人形操作硬件方案。
2. [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐4  
   基于Inspect Robots的双手厨房操作VLA基准，覆盖切菜、摆盘等复杂长程接触任务，填补VLA复杂操作评测的空白。
3. [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) ⭐39  
   双向对齐的具身Agent框架，专为长horizon机器人操作任务设计，解决VLA长程任务遗忘的核心痛点。
4. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐80  
   将自然语言指令编译为可验证的机器人操作技能图，支持仿真和实机执行，大幅提升VLA操作的可靠性。
5. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐36  
   开源双手操作数据采集和重定向软件，支持将人类演示数据重定向到任意双臂机器人，降低VLA操作数据的采集成本。
6. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐258  
   UMI-3D SLAM和数据处理pipeline，为通用操作接口（UMI）提供三维感知支撑，适配各类机器人操作场景。

---
### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划、运动控制）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63191  
   开源机器人操作系统，目前已支持300+车型的驾驶辅助升级，是全球落地规模最大的具身智能系统之一。
2. [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx) ⭐259  
   基于JAX的模型预测控制库，支持足式和人形机器人的高速运动控制，可微优化的特性适合与VLA pipeline深度集成。
3. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4493  
   ROS 2官方导航框架，是移动机器人导航的工业级标准方案，支持多传感器融合、动态避障等核心能力。
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐132  
   轻量可扩展的人形机器人全身遥操作框架，支持低成本动捕设备采集演示数据，为人形运动策略训练提供数据支撑。
5. [Rhoban/microban](https://github.com/Rhoban/microban) ⭐38  
   3D打印的低成本开源人形机器人，基于树莓派Zero 2W，是人形机器人研究和学习的高性价比入门平台。
6. [mstoelzle/focodyn](https://github.com/mstoelzle/focodyn) ⭐6  
   可微浮基动力学和接触位姿雅可比库，专为足式机器人的CBF/CLF控制、轨迹优化和学习workflow设计。

---
### 📦 具身应用（sim2real、遥操作、自主系统、落地部署、硬件原型）
1. [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) ⭐0 (+291 today)  
   今日Trending唯一机器人相关项目，面向CAD、机器人、硬件设计的Agent技能集合，支持自然语言生成机器人硬件设计，打通具身智能从软件到硬件的研发链路。
2. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐838  
   基于Agent工作流的自进化具身AI操作系统，支持多机器人协同和实机自主迭代，是具身系统级方案的代表性项目。
3. [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) ⭐221  
   最小化软硬一体具身架构，为大模型提供带自感知闭环的物理实体，可快速验证LLM的物理交互能力。
4. [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3419  
   开源AI助手生态，支持MCP集成、多模态工作流、IoT控制和跨平台语音交互，是消费级具身助手的代表性项目。
5. [provael/provael](https://github.com/provael/provael) ⭐3  
   开源VLA红队测试工具，可在仿真中测试VLA策略的鲁棒性并输出攻击成功率，填补具身智能安全测试工具的空白。

---
## 趋势信号分析
今日数据显示，**VLA轻量化与落地工具链是当前社区爆发性关注的方向**：仅179M参数的端侧VLA SUREFlow（IROS 2026）登榜，无ROS的sim2real部署框架、统一VLA评测工具等项目密集开源，反映社区已从VLA模型的精度竞赛转向解决落地适配的核心痛点。其次，**AI辅助机器人硬件设计是首次登榜的新兴方向**：text-to-cad项目进入今日Trending，支持自然语言生成机器人硬件，与近期行业“软硬一体具身智能”的趋势完全呼应。此外，人形相关项目占比超35%，涵盖VLA、运动控制、开源硬件全栈，与特斯拉Optimus、Figure 01等人形产品落地的行业事件强相关，开源社区正在为人形量产积累基础技术栈。

---
## 社区关注热点
- 👉 关注[tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026)：基于Mamba架构的179M超轻量VLA，专为边缘端机器人部署设计，是VLA从云端走向端侧的代表性预研工作。
- 👉 关注[RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)：无ROS的轻量sim2real框架，原生支持主流机械臂的VLA/RL策略部署，大幅降低VLA实机验证的门槛，适合中小团队快速落地。
- 👉 关注[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)：国内首个面向入门者的具身智能实战教程，从0搭建VLA全栈，仅需Python基础，是开发者进入具身领域的最优学习路径。
- 👉 关注[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)：VLA统一评测框架，一次定义基准即可跨机器人、跨仿真运行，解决目前VLA性能评估标准不统一的核心痛点，有望成为行业通用工具。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*