# AI 开源趋势日报 2026-07-26

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-26 01:43 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-26）
---
## 1. 今日速览
今日具身智能开源领域核心动向集中于VLA产业级落地与软硬件生态完善：NVIDIA连续开源两代Alpamayo推理型VLA及配套开发工具，成为VLA领域的核心焦点；人形机器人底层软件栈出现新兴专用方案，打破原有通用框架的垄断；中文具身智能与VLA学习资源快速完善，覆盖从入门到进阶的全链路需求；VLA标准化评测工具持续涌现，加速模型迭代与落地验证。
---
## 2. 各维度热门项目
### 🤖 机器人框架/SDK
| 项目名 | Stars | 说明 |
|--------|-------|------|
| [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) | ⭐7764 | 基于NVIDIA Isaac Sim的统一机器人学习框架，是当前工业界和学术界sim2real开发的核心基础工具，生态成熟度持续提升。 |
| [dora-rs/dora](https://github.com/dora-rs/dora) | ⭐3852 | Rust编写的数据流导向机器人中间件，主打低延迟、可组合的分布式架构，是替代ROS的新兴轻量级方案，近7天活跃度增长显著。 |
| [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) | ⭐14325 | 通用多关节物理仿真引擎，是VLA和机器人学习的事实标准仿真工具，近期持续优化接触动力学计算效率。 |
| [softmata/horus](https://github.com/softmata/horus) | ⭐393 | 全球首个主打人形机器人场景的专用runtime系统，对标手机端Android，实现微秒级控制延迟，是机器人底层系统的新兴方向。 |
| [RobotecAI/rai](https://github.com/RobotecAI/rai) | ⭐556 | 厂商无关的物理AI机器人代理框架，原生集成ROS2，支持复杂动作定义、语音交互，适合快速落地部署。 |
| [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) | ⭐125 | 无ROS的轻量sim2real框架，原生支持MuJoCo Gymnasium，可直接训练部署VLA和RL策略，适配Franka、xArm等主流机械臂。 |

---
### 🧠 VLA/基础模型
| 项目名 | Stars | 说明 |
|--------|-------|------|
| [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) | ⭐1935 | NVIDIA开源的10B参数推理型VLA模型，面向自动驾驶场景，支持因果链推理与轨迹生成，是当前产业级端侧VLA的标杆项目。 |
| [NVlabs/alpamayo1.5](https://github.com/NVlabs/alpamayo1.5) | ⭐342 | Alpamayo的迭代版本，新增RL增强推理、导航引导、VQA能力，配套的微调、量化、部署食谱同步开源，生态逐步完善。 |
| [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) | ⭐511 | 商汤开源的InternVLA-A1，统一机器人操作的理解、生成与动作能力，是国内通用VLA的代表性成果。 |
| [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) | ⭐435 | 全中文实战导向VLA学习面试手册，聚焦机器人领域特有挑战，是入门VLA的优质中文资源，近7天star增长超300。 |
| [phi-monster/Galahad](https://github.com/phi-monster/Galahad) | ⭐50 | 针对VLA策略指令失明问题的诊断与低秩数据修复方案，包含模型、去混淆数据集和测试工具，是VLA可靠性优化的前沿成果。 |
| [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) | ⭐65 | VLA/物理AI模型的统一评测框架，一次定义基准即可在任意机器人/仿真上运行策略，填补了VLA标准化评测的空白。 |
| [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) | ⭐119 | 具身智能安全方向的综述资源，覆盖感知、认知、规划等全链路风险与攻防方案，收录500+相关论文，填补了具身安全领域的资源空白。 |

---
### 🦾 操作与抓取
| 项目名 | Stars | 说明 |
|--------|-------|------|
| [enactic/openarm](https://github.com/enactic/openarm) | ⭐2765 | 完全开源的人形机械臂，面向接触富集的物理AI研究与部署，支持力控与视觉融合，是当前开源操作硬件的标杆项目。 |
| [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) | ⭐87 | 将自然语言指令编译为可验证的机器人技能图，可直接在仿真或真实机器人上执行，显著提升操作任务的可靠性。 |
| [shritankomm/7-DOF-FDM-Open-Arm](https://github.com/shritankomm/7-DOF-FDM-Open-Arm) | ⭐1 | 成本低于800美元的7自由度3D打印开源人形机械臂，支持ROS2和视觉自主控制，大幅降低操作研究的硬件门槛。 |
| [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) | ⭐8 | 基于Inspect Robots构建的双臂厨房操作基准，专门用于VLA模型的复杂操作能力评测。 |
| [Shahwar0997/detect-plan-grasp](https://github.com/Shahwar0997/detect-plan-grasp) | ⭐2 | 端到端语言驱动的抓取导航框架，集成INT8 YOLO、本地LLM和自研6自由度IK，可在MuJoCo中完成完整操作任务。 |

---
### 🚶 运动与导航
| 项目名 | Stars | 说明 |
|--------|-------|------|
| [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) | ⭐598 | 地平线开源的人形机器人全身控制基础模型，支持复杂场景下的运动规划与力控适配，是国内人形运动大模型的代表性成果。 |
| [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) | ⭐96 | 清华开源的通用人形控制全模态运动生成模型，已发表顶会论文，支持多场景下的人形全身运动生成。 |
| [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) | ⭐259 | 港大开源的UMI-3D SLAM与数据处理pipeline，面向具身智能的三维环境感知需求，支持动态场景实时建图。 |
| [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) | ⭐138 | 轻量可扩展的人形机器人全身遥操作框架，降低人形运动数据采集与策略部署门槛。 |
| [Rhoban/microban](https://github.com/Rhoban/microban) | ⭐45 | 低成本全3D打印的开源人形机器人，基于树莓派Zero 2W，是DIY人形研究的高性价比平台。 |

---
### 📦 具身应用
| 项目名 | Stars | 说明 |
|--------|-------|------|
| [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) | ⭐2860 | 面向Python基础开发者的零门槛具身智能教程，从零构建VLA、OpenVLA等模型，是国内具身入门的头部科普项目，近7天star增长超1000。 |
| [commaai/openpilot](https://github.com/commaai/openpilot) | ⭐63225 | 全球最大的开源机器人操作系统之一，当前已落地300+车型的驾驶辅助，是具身智能在自动驾驶场景的标杆落地项目。 |
| [RLinf/RLinf](https://github.com/RLinf/RLinf) | ⭐4255 | 面向具身与代理AI的强化学习基础设施，支撑具身智能的大规模训练与分布式部署。 |
| [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) | ⭐1073 | 基于代理工作流的自进化具身AI操作系统，主打具身系统的自主迭代与任务泛化能力。 |
| [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) | ⭐42 | 开源的双臂数据采集与重定向软件，可同步采集数据并适配任意双臂机器人，支撑具身策略的sim2real落地。 |

---
## 3. 趋势信号分析
今日社区数据显示，**面向垂直场景的产业级VLA**正在获得爆发性关注，NVIDIA开源的Alpamayo系列主打自动驾驶场景的因果推理VLA，配套全链路开发工具，标志着VLA从通用实验室模型正式走向垂直场景落地的阶段。首次出现了**人形机器人专用底层runtime**方向的热门项目，HORUS主打微秒级低延迟控制、对标手机端Android，反映人形机器人产业发展开始倒逼基础软件栈的专用化创新，而非继续沿用通用ROS架构。此外，中文具身智能资源的快速增长与近期国内人形机器人产业扶持政策、创业热潮高度吻合，国内开发者群体已成为具身领域的核心参与力量。VLA标准化评测工具的涌现也填补了行业空白，将大幅提升模型迭代效率。（全文287字）

---
## 4. 社区关注热点
- 🎯 **[NVlabs/alpamayo 系列](https://github.com/NVlabs/alpamayo)**：NVIDIA开源的10B参数端侧推理VLA，覆盖自动驾驶场景的轨迹生成与因果推理，配套微调、量化、部署全链路工具，是当前产业级VLA落地的核心参考项目。
- 🎯 **[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)**：面向Python基础开发者的零门槛中文具身实战教程，从零构建OpenVLA等主流模型，是入门具身智能的最优中文资源，近期社区活跃度极高。
- 🎯 **[softmata/horus](https://github.com/softmata/horus)**：人形机器人专用低延迟runtime，对标手机端Android，是机器人基础软件栈的新兴方向，有望重构人形机器人的底层控制架构，适合关注机器人系统层的开发者跟进。
- 🎯 **[robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)**：统一VLA/物理AI评测框架，一次定义基准即可跨机器人、跨仿真运行，解决了当前VLA研究缺乏标准化评测的核心痛点。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*