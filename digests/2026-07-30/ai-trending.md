# AI 开源趋势日报 2026-07-30

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-30 01:18 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-30）

---

## 今日速览
今日GitHub Trending暂无直接面向具身智能、VLA与机器人领域的上榜项目，社区核心热度集中在主题标签下的基础设施、VLA落地工具与人形机器人相关方向。NVIDIA正式开源Alpamayo VLA的官方开发工具集，覆盖从微调到部署的全流程，标志着大厂主导的具身基础模型生态开始向普通开发者开放。面向国内开发者的中文VLA、具身智能入门教程与手册类项目持续获得高星，反映出国内该领域的人才需求与学习热情同步爆发。人形机器人的运动-操作一体化VLA控制、具身安全等务实落地方向的开源项目逐步增多，领域正在从学术研究向产业应用过渡。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、基础设施）
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,262（无今日新增）：全球最受欢迎的开源机器人操作系统，已支持300+款车型的驾驶辅助系统升级，是具身智能在自动驾驶场景的标杆落地项目。
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,375（无今日新增）：机器人领域事实标准的多关节动力学物理仿真器，是VLA训练、sim2real研究的核心工具。
3. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,855（无今日新增）：Rust开发的数据流导向机器人中间件，主打低延迟、可组合、分布式特性，是替代ROS的下一代AI机器人基础设施代表。
4. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,800（无今日新增）：基于NVIDIA Isaac Sim构建的统一机器人学习框架，支持VLA、RL等多种训练范式，目前被广泛应用于具身智能研究。
5. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,319（无今日新增）：专门面向具身与Agent AI场景优化的强化学习基础设施，简化RL在机器人任务中的开发与部署流程。
6. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) ⭐1,604（无今日新增）：斯坦福推出的具身AI研究加速平台，提供大规模真实场景模拟任务与基准测试集。

### 🧠 VLA/基础模型（视觉-语言-动作、策略优化、生态工具）
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,923（无今日新增）：面向Python基础开发者的从0到1具身智能实战教程，覆盖OpenVLA、SmolVLA、Pi0等主流VLA模型的构建，是国内入门具身领域的头部学习资源。
2. [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) ⭐83（无今日新增）：NVIDIA官方推出的Alpamayo VLA开发工具集，提供微调、RL后训练、量化、部署的开箱即用方案，标志着大厂VLA生态正式向开发者开放。
3. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐453（无今日新增）：国内首份全中文、实战导向的VLA学习/面试手册，聚焦机器人领域特有挑战，适配算法工程师的入门与求职需求。
4. [phi-monster/Galahad](https://github.com/phi-monster/Galahad) ⭐89（无今日新增）：针对VLA策略普遍存在的“指令失明”问题的诊断与优化工具包，包含去混淆数据集、测量 battery，解决VLA落地的核心痛点。
5. [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐120（无今日新增）：具身AI安全综述项目，收录500+篇相关论文，覆盖VLA从感知到交互的全链路风险与防御方案。

### 🦾 操作与抓取（灵巧手、UMI、操作基准、安全优化）
1. [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,172（无今日新增）：GPU并行加速的机器人操作仿真与基准平台，是目前VLA操作任务评测的主流标准数据集，支持上百种抓取、操作任务。
2. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,781（无今日新增）：完全开源的人形机械臂项目，面向接触富集场景的物理AI研究与部署，硬件可3D打印，软件支持ROS2与视觉控制，成本可控。
3. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐42（无今日新增）：开源的双手UMI（通用操作接口）数据采集与重定向工具，支持将人类操作数据同步到任意双臂机器人，是VLA操作数据采集的核心工具。
4. [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐8（无今日新增）：面向VLA模型的双手厨房操作基准，覆盖日常复杂接触任务，填补了真实生活场景操作评测的空白。
5. [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes) ⭐1（无今日新增）：将防撞安全损失直接嵌入Pi0 VLA模型训练的实践项目，替代传统运行时过滤方案，探索VLA操作安全的新路径。

### 🚶 运动与导航（人形机器人、足式控制、VLA+运动）
1. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐30,171（无今日新增）：全球最受欢迎的机器人算法开源教材，用Python实现了导航、运动控制、SLAM等核心算法，是机器人领域入门的必学资源。
2. [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) ⭐351（无今日新增）：人形机器人实时全身非线性模型预测控制库，支持运动与操作的一体化规划，是人形机器人运动控制的核心技术实现。
3. [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐2（无今日新增）：首个开源的人形全身VLA控制框架，实现用统一VLA模型完成人形机器人的运动与操作任务，拓展了VLA的应用边界。
4. [Yhx888/LocoVLA](https://github.com/Yhx888/LocoVLA) ⭐5（无今日新增）：面向轮足机器人的VLA开源课程，共58节，覆盖经典控制、RL、VLA部署、ROS2开发全流程，是轮足人形VLA入门的实战资源。
5. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,527（无今日新增）：ROS2生态的标准导航框架，支持路径规划、避障、定位等核心功能，是移动机器人导航的主流方案。

### 📦 具身应用（sim2real、遥操作、落地评测、消费级交互）
1. [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) ⭐3,426（无今日新增）：开源多模态AI助手生态，支持IoT控制、跨平台语音交互，是具身交互在消费级场景的代表性落地项目。
2. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) ⭐2,656（无今日新增）：ICML 2026顶会成果RoboTwin 2.0的官方仓库，探索数字孪生与具身智能的结合，支持机器人的sim2real训练与部署。
3. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,268（无今日新增）：基于Agent工作流的自进化具身AI操作系统，实现具身代理的技能学习与 runtime 升级。
4. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐94（无今日新增）：开源VLA统一评测平台，支持任意LLM/VLA模型在任意机械臂/人形机器人上的仿真/真实场景测试，解决VLA评测标准不统一的痛点。
5. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐140（无今日新增）：全身人形机器人遥操作系统，支持人类动作实时映射到人形机器人，是VLA数据采集与人机共融的核心工具。

---

## 趋势信号分析
当前VLA落地工具与开发者生态正在获得社区爆发性关注：NVIDIA Alpamayo VLA的官方开发工具集今日登榜，对应2026年上半年Google、NVIDIA等大厂密集发布具身基础模型的行业节奏，标志着VLA技术从学术原型走向产业落地的工具链已逐步成熟。其次，人形机器人的运动-操作一体化VLA方向首次出现专门开源项目（WholebodyVLA），对应今年人形机器人从单一功能向全场景任务演进的行业趋势，VLA的应用边界已从传统机械臂操作延伸至人形全身控制。此外，中文入门教程、安全评测类配套项目的高增长，反映国内具身智能领域正从追热点转向人才储备、落地保障的务实阶段。

---

## 社区关注热点
- 🔹 [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes)：NVIDIA官方推出的Alpamayo VLA全流程开发工具，覆盖微调、RL后训练、量化部署，是目前产业界最成熟的VLA落地工具链，适合快速落地具身应用的开发者。
- 🔹 [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)：零门槛的具身智能实战教程，仅需Python基础即可掌握主流VLA模型的构建，是国内开发者入门具身领域的首选学习资源，社区活跃度极高。
- 🔹 [dora-rs/dora](https://github.com/dora-rs/dora)：Rust编写的低延迟机器人中间件，解决传统ROS的性能瓶颈，适配AI机器人的实时VLA推理需求，是下一代机器人基础设施的标杆项目。
- 🔹 [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots)：开源VLA统一评测平台，支持跨模型、跨机器人、跨仿真/真实场景的标准化测试，解决当前VLA效果评估无统一标准的核心痛点。
- 🔹 [enactic/openarm](https://github.com/enactic/openarm)：全开源的人形机械臂软硬件方案，成本可控，支持接触富集场景的研究与部署，是实体具身智能研究团队的高性价比选项。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*