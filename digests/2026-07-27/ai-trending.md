# AI 开源趋势日报 2026-07-27

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-27 01:50 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-27）
---

## 今日速览
今日GitHub全局Trending榜单无具身智能、机器人领域相关项目，热度集中在7天活跃的垂直主题仓库；VLA领域呈现「大小两端同步落地」特征，既有英伟达推出的10B级垂直场景推理VLA，也有顶会发布的179M端侧轻量VLA，落地导向明确；人形机器人开源生态快速成熟，全开源手臂、全身运动控制、遥操作框架等核心组件可用度大幅提升，匹配产业端量产前夜的技术需求；中文具身智能开源生态爆发，入门教程、学习手册等项目获得广泛关注，大幅降低国内开发者准入门槛。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. **[isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab)** ⭐7,777 | 英伟达官方统一机器人学习框架，基于Isaac Sim构建，支持VLA训练、RL部署、人形机器人仿真，是当前具身智能科研与工程的核心仿真工具
2. **[dora-rs/dora](https://github.com/dora-rs/dora)** ⭐3,852 | Rust编写的数据流导向机器人中间件，主打低延迟、可组合、分布式特性，大幅简化AI机器人应用构建流程，适合端侧具身系统部署
3. **[google-deepmind/mujoco](https://github.com/google-deepmind/mujoco)** ⭐14,335 | 全球应用最广的多刚体物理仿真引擎，支持接触动力学高精度模拟，是几乎所有机器人学习、具身智能项目的底层仿真依赖
4. **[RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)** ⭐125 | 无ROS依赖的轻量sim2real框架，原生支持VLA模型、RL代理的训练与部署，适配Franka、UR5e、SO101等主流机器人，降低工程落地门槛
5. **[rerun-io/rerun](https://github.com/rerun-io/rerun)** ⭐11,190 | 多模态机器人数据可视化工具，支持视觉、传感器、动作、日志等数据的流式可视化与查询，大幅提升具身系统调试效率

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. **[NVlabs/alpamayo](https://github.com/NVlabs/alpamayo)** ⭐1,937 | 英伟达开源的10B参数推理VLA，面向自动驾驶场景，支持驾驶轨迹与因果链推理配对，是VLA向垂直场景落地的标杆项目
2. **[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)** ⭐2,873 | 面向国内开发者的具身智能入门项目，仅需Python基础即可从零构建VLA/OpenVLA/Pi0等主流模型，配套完整教程，大幅降低具身领域准入门槛
3. **[sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook)** ⭐436 | 国内首份全中文VLA实战/面试手册，聚焦机器人领域特有挑战，覆盖算法、工程、面试要点，是从业者入门VLA的核心中文资源
4. **[knightnemo/Awesome-World-Models](https://github.com/knightnemo/Awesome-World-Models)** ⭐3,226 | 世界模型领域最全的 curated 资源列表，覆盖具身智能、视频生成、自动驾驶等方向，配套论文、代码、教程，是认知层具身技术的核心学习资源
5. **[tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026)** ⭐7 | IROS 2026最新录用的轻量VLA，基于Mamba架构，仅179M参数即可实现机器人操作，代表VLA端侧部署的重要技术方向
6. **[phi-monster/Galahad](https://github.com/phi-monster/Galahad)** ⭐61 | 针对VLA指令盲问题的最新研究，配套低秩数据修复方法、去混淆数据集、评测基准，解决VLA落地中的核心痛点

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. **[enactic/openarm](https://github.com/enactic/openarm)** ⭐2,768 | 全球首个全开源的人形手臂硬件，面向接触富集的物理AI场景，可直接用于科研与原型验证，填补了开源人形上肢硬件的空白
2. **[RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo)** ⭐299 | 机器人操作领域的统一基准平台，覆盖多场景、多机器人的操作任务，用于VLA、RL策略的统一评测
3. **[robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw)** ⭐42 | 开源双手操作数据采集工具，支持多传感器同步、数据QA、动作重定向，可适配任意双臂机器人，解决VLA操作的数据采集痛点
4. **[LFGfg/TransDex](https://github.com/LFGfg/TransDex)** ⭐8 | 3D视触觉融合的灵巧手运动策略，基于点云重建预训练，提升非结构化场景下的抓取成功率
5. **[robocurve/kitchenbench](https://github.com/robocurve/kitchenbench)** ⭐8 | 面向VLA评测的双手厨房操作基准，覆盖真实厨房场景的复杂接触任务，是VLA落地家庭场景的核心评测工具

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. **[manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc)** ⭐350 | 人形机器人全身非线性MPC控制算法，支持实时运动操作一体化规划，是人形机器人运动控制的核心开源实现
2. **[Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG)** ⭐96 | 清华MARS实验室开源的全模态运动生成框架，用于通用人形机器人控制，支持多模态指令输入，相关成果发表于2026年顶会
3. **[hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D)** ⭐259 | 港科大开源的UMI-3D SLAM与数据处理管线，支持具身场景的高精度三维重建与动作标注，是VLA数据采集的核心基础设施
4. **[mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA)** ⭐2 | 首个面向人形全身运动操作的统一VLA框架，支持大空间内的导航、操作一体化任务，拓展了VLA的应用边界
5. **[ros-navigation/navigation2](https://github.com/ros-navigation/navigation2)** ⭐4,508 | ROS2生态的工业级导航框架，支持路径规划、避障、多机器人协同，是移动机器人、人形机器人导航的主流落地方案

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. **[RLinf/RLinf](https://github.com/RLinf/RLinf)** ⭐4,262 | 面向具身与Agent AI的强化学习基础设施，支持RL策略的训练、部署、监控，大幅降低具身智能系统的工程复杂度
2. **[commaai/openpilot](https://github.com/commaai/openpilot)** ⭐63,230 | 全球规模最大的落地机器人OS，已适配300+车型的辅助驾驶系统，是具身智能在交通场景的大规模商业化落地案例
3. **[PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS)** ⭐1,107 | 自进化具身AI操作系统，基于Agent工作流构建，支持物理场景下的自主任务执行与能力迭代
4. **[huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi)** ⭐3,424 | 开源多模态AI助手生态，支持IoT控制、跨平台语音交互，是具身智能面向消费级场景的落地探索
5. **[RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin)** ⭐2,631 | ICML 2026录用的RoboTwin 2.0官方仓库，面向具身智能的数字孪生平台，支持sim2real迁移与策略验证

---

## 趋势信号分析
当前具身智能开源领域呈现三大核心趋势：一是VLA从学术演示加速向落地迭代，一方面大厂推出面向自动驾驶的大参数推理VLA并配套完整微调、部署工具链，另一方面顶会涌现百M级轻量端侧VLA，同时指令盲、微调效率等落地痛点的研究不断增多，对应行业对VLA可用性的需求提升，与近期英伟达、特斯拉等大厂发力机器人基础模型的行业事件高度匹配；二是人形机器人开源从单点Demo走向全栈化，硬件、控制、仿真、数据采集等环节均有成熟开源方案，匹配全球人形机器人产业融资、量产前夜的技术供给需求；三是中文开源生态快速崛起，入门教程、学习手册等项目获得数千星，反映出国内具身智能人才培养、技术落地的旺盛需求。

---

## 社区关注热点
- 关注**[datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)**：仅需Python基础即可从零构建OpenVLA、Pi0等主流具身模型，配套完整教程与代码实现，是零基础入门具身智能的最优路径之一
- 关注**[NVlabs/alpamayo](https://github.com/NVlabs/alpamayo)** 系列项目：英伟达开源的自动驾驶场景推理VLA，支持因果链推理，配套完整的微调、量化、部署工具链，是VLA垂直落地的标杆性项目
- 关注**[enactic/openarm](https://github.com/enactic/openarm)**：全球首个全开源的人形手臂硬件，面向接触富集的物理AI场景，可直接用于科研与原型验证，填补了开源人形上肢硬件的空白
- 关注**[RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack)**：无ROS依赖的轻量sim2real框架，原生支持VLA模型与RL代理的部署，适配主流机械臂与人形机器人，大幅降低工程落地门槛

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*