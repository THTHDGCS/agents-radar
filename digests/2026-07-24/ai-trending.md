# AI 开源趋势日报 2026-07-24

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-24 01:29 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-24）

---

## 今日速览
1. NVIDIA今日集中开源Alpamayo系列自动驾驶VLA模型及完整开发工具链，带因果链推理的垂直场景VLA成为社区核心关注焦点。
2. 轻量端侧VLA架构、人形机器人全身控制基础模型接连发布，覆盖操作、运动两大具身核心场景，技术栈持续向端侧落地优化。
3. VLA评测、红队测试、故障检测等工具类项目密集涌现，标志VLA技术已从实验室研发阶段进入工程化验证与安全测试阶段。
4. 低成本开源人形硬件、无ROS依赖的sim2real部署框架持续完善，大幅降低具身智能落地的技术与成本门槛。

---

## 各维度热门项目
### 🤖 机器人框架/SDK
1. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,747
   NVIDIA官方推出的基于Isaac Sim的统一机器人学习框架，是当前VLA模型仿真训练、sim2real迁移的主流基础设施，生态完善度持续提升。
2. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,853
   Rust开发的数据流导向机器人中间件，主打低延迟、可组合、分布式特性，成为替代ROS的轻量型具身系统开发热门选项。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,301
   行业通用的多关节物理仿真器，是当前机器人操作、足式运动、人形机器人研发的核心仿真工具，近期持续新增VLA训练适配能力。
4. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐124
   无ROS依赖的轻量sim2real框架，原生支持VLA模型和RL策略部署，适配Franka、UR5e等主流机械臂，大幅降低VLA落地门槛。
5. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,232
   专为具身智能和代理AI设计的强化学习基础设施，统一RL训练、部署、评测流程，适配多类机器人硬件和仿真环境。

---

### 🧠 VLA/基础模型
1. [NVlabs/alpamayo](https://github.com/NVlabs/alpamayo) ⭐1,932
   NVIDIA最新开源的10B参数推理型VLA，专为自动驾驶场景设计，首次将因果链推理与驾驶轨迹生成结合，是当前VLA垂直场景落地的标杆项目。
2. [NVlabs/alpamayo1.5](https://github.com/NVlabs/alpamayo1.5) ⭐340
   Alpamayo的升级版本，新增RL增强推理、导航引导、VQA能力，覆盖更复杂的自动驾驶与具身导航场景，配套完整的微调工具链。
3. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) ⭐508
   国产VLA代表项目，统一机器人操作的理解、生成、动作三大能力，在多项操作基准上达到SOTA，开源权重可直接用于工业场景验证。
4. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐423
   国内首份全中文实战导向VLA学习面试手册，聚焦机器人场景特有的技术挑战，是开发者入门VLA领域的核心学习资源。
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐19
   首个通用VLA/物理AI模型评测框架，支持一次定义基准、在任意机器人/仿真环境运行多类策略，填补了VLA工程化评测的工具空白。
6. [tanvirnwu/SUREFlow_IROS_2026](https://github.com/tanvirnwu/SUREFlow_IROS_2026) ⭐6
   IROS 2026收录的轻量VLA架构，仅179M参数，基于Mamba实现，在机器人操作任务上达到与大参数模型相当的效果，适合端侧部署。

---

### 🦾 操作与抓取
1. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐42
   开源双手UMI数据采集与重定向软件，支持同步采集、校准、遥操作、重定向到任意双臂机器人，是VLA操作数据采集的主流工具。
2. [graph-robots/graph-as-policy](https://github.com/graph-robots/graph-as-policy) ⭐82
   将自然语言指令编译为可验证的机器人技能图的框架，支持仿真和真实机器人执行，解决了VLA操作任务的可解释性与可靠性问题。
3. [LFGfg/TransDex](https://github.com/LFGfg/TransDex) ⭐8
   基于点云重建预训练的3D视触觉融合电机策略，大幅提升灵巧手在接触富集场景的操作精度，是当前灵巧操作的前沿技术方案。
4. [robocurve/kitchenbench](https://github.com/robocurve/kitchenbench) ⭐5
   专为VLA模型设计的双手厨房操作基准，覆盖复杂日常操作任务，填补了面向真实家庭场景的VLA操作评测基准空白。

---

### 🚶 运动与导航
1. [HorizonRobotics/HoloMotion](https://github.com/HorizonRobotics/HoloMotion) ⭐595
   地平线开源的全身人形控制基础模型，支持多模态输入生成人形全身运动，是当前人形机器人运动控制的核心代表性项目。
2. [Tsinghua-MARS-Lab/OMG](https://github.com/Tsinghua-MARS-Lab/OMG) ⭐94
   清华MARS实验室开源的多模态人形运动生成模型，支持语言、视觉等多类输入生成自然的人形运动，相关论文已入选顶会。
3. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,197
   全球最大的开源机器人操作系统之一，目前已适配300+车型的高级辅助驾驶，是VLA技术在自动驾驶场景落地的标杆平台。
4. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) ⭐259
   港大开源的UMI-3D SLAM与数据处理管线，支持具身机器人在未知环境的高精度建图与定位，适配多类深度相机硬件。
5. [iit-DLSLab/mpx](https://github.com/iit-DLSLab/mpx) ⭐263
   基于JAX实现的高性能模型预测控制库，专为人形机器人、足式机器人的全身运动控制优化，支持GPU加速的实时控制。

---

### 📦 具身应用
1. [ruvnet/RuView](https://github.com/ruvnet/RuView) ⭐0 (+1708 today)
   今日Trending热榜顶流项目，无需摄像头即可通过WiFi信号实现实时空间感知、生命体征监测、存在检测，为具身机器人提供低成本、隐私友好的环境感知方案。
2. [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) ⭐0 (+230 today)
   今日Trending热榜项目，面向CAD、机器人硬件设计的Agent技能集合，支持通过自然语言生成机器人硬件设计方案，大幅降低机器人硬件开发门槛。
3. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,837
   国内最热门的具身智能入门实战教程，仅需Python基础即可从0搭建VLA、具身机器人系统，覆盖OpenVLA、Pi0等主流模型的动手实践。
4. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,753
   完全开源的人形机械臂硬件与软件方案，专为物理AI研究和接触富集场景部署设计，成本仅为商用机械臂的1/10，适合中小团队研发使用。
5. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐994
   首个自进化具身AI操作系统，基于代理工作流实现机器人的自主任务规划、学习、迭代，支持多类机器人硬件接入，是具身系统落地的核心载体。
6. [Rhoban/microban](https://github.com/Rhoban/microban) ⭐42
   3D打印的低成本开源人形机器人，仅需树莓派Zero 2W和19个舵机即可搭建，总成本低于1000元，是入门人形机器人研发的高性价比平台。

---

## 趋势信号分析
今日社区核心热度集中在**垂直场景VLA落地与工程化工具链**方向：NVIDIA连续开源Alpamayo系列自动驾驶VLA及配套开发工具，标志VLA正从通用机械臂操作场景向自动驾驶等高价值垂直场景快速渗透，头部厂商正在主导VLA生态的标准化。其次，**轻量端侧VLA架构**首次成为热点，仅179M参数的Mamba架构VLA入选IROS 2026，证明小参数模型在端侧机器人部署的可行性，匹配当前人形机器人、边缘具身设备的算力约束。此外，VLA评测、红队测试、故障检测等工具类项目密集涌现，对应行业近期对VLA可靠性、安全性的普遍关切，意味着VLA已从实验室研发阶段进入工程化验证、落地前的安全测试阶段。结合近期人形机器人商业化加速的行业背景，低成本开源人形硬件、全身运动控制模型的热度持续上升，反映社区对降低具身智能落地门槛的迫切需求。

---

## 社区关注热点
- **NVIDIA Alpamayo系列VLA**：作为头部厂商推出的垂直场景VLA标杆，其因果推理设计、配套工具链代表了VLA落地的主流技术路线，建议开发者重点关注其微调、部署方法。
- **无ROS依赖的sim2real框架**：RobotControlStack等轻量框架大幅降低了VLA从仿真到真实机器人的部署门槛，适合中小团队快速验证VLA模型的落地效果。
- **VLA安全与评测工具**：inspect-robots、provael等项目填补了VLA工程化验证的工具空白，是当前VLA落地前必须的测试环节，提前布局可抢占工程化红利。
- **低成本开源人形硬件**：openarm、microban等开源硬件将人形机器人研发成本降至万元甚至千元级，大幅降低了开发者进入人形机器人领域的准入门槛。
- **轻量端侧VLA架构**：基于Mamba的小参数VLA在操作任务上达到SOTA效果，适合端侧机器人部署，是未来具身终端的核心技术方向。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*