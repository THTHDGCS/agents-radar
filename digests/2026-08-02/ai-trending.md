# AI 开源趋势日报 2026-08-02

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-08-02 01:42 UTC

---

# 具身智能与机器人开源趋势日报（2026-08-02）

---

## 今日速览
今日具身智能与机器人开源社区呈现VLA工具链全链路补全、大公司加速底层布局的核心特征。一方面，VLA学习、微调、评估、安全测试的全栈开源工具集中发布，推动VLA从学术研究向工程落地加速渗透；另一方面，微软、字节跳动、腾讯云等科技巨头集中开源3D生成、长周期Agent、Agent记忆等具身底层基础设施，印证行业落地投入加码。此外，人形机器人开源软硬件项目热度持续攀升，具身安全等细分方向首次出现系统性社区资源，成为新的增长赛道。

---

## 各维度热门项目
### 🤖 机器人框架/SDK
1. [commaai/openpilot](https://github.com/commaai/openpilot) ⭐63,287  
   目前星标最高的开源机器人操作系统，可升级300+车型的辅助驾驶系统，是自动驾驶与移动机器人领域的标杆项目。
2. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) ⭐14,406  
   通用多关节物理仿真器，是机器人学习、VLA训练的事实标准工具，生态覆盖绝大多数主流机器人研究项目。
3. [RLinf/RLinf](https://github.com/RLinf/RLinf) ⭐4,369  
   面向具身与Agent AI的强化学习基础设施，为机器人学习、VLA训练提供统一的RL底层支撑。
4. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) ⭐7,815  
   基于NVIDIA Isaac Sim的统一机器人学习框架，原生支持人形机器人、VLA模型的训练与sim2real部署，是当前最热门的机器人学习开发框架。
5. [dora-rs/dora](https://github.com/dora-rs/dora) ⭐3,857  
   数据流导向的低延迟机器人中间件，主打轻量、可组合、分布式特性，是替代传统ROS架构、适配AI机器人开发的新兴方案。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) ⭐125  
   无ROS依赖的sim2real框架，原生支持VLA模型与RL策略的部署，适配Franka、UR5e、xArm、SO101等主流机器人，大幅降低VLA落地门槛。

---

### 🧠 VLA/基础模型
1. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) ⭐459  
   国内首份全中文、实战导向的VLA学习/面试手册，聚焦机器人领域特有挑战，填补了中文VLA入门资源的空白。
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) ⭐2,949  
   面向零基础开发者的具身智能教程，从零讲解VLA/OpenVLA/SmolVLA/Pi0等主流模型的构建，是国内社区普及度最高的具身入门资源。
3. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) ⭐108  
   开源物理AI统一评估框架，支持任意LLM/VLA在任意机械臂/人形机器人的仿真/真实基准测试，解决了VLA评测标准不统一的核心痛点。
4. [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) ⭐83  
   NVIDIA官方Alpamayo VLA开发者工具集，包含微调、RL后训练、量化、部署全流程脚本，是工业级VLA开发的权威参考。
5. [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) ⭐121  
   收录500+论文的具身AI安全综述，覆盖感知、认知、规划、交互全链路风险与攻防方案，是具身安全方向首份系统性资源。
6. [provael/provael](https://github.com/provael/provael) ⭐5  
   全球首个开源VLA红队测试工具，可在仿真环境中测试VLA策略的鲁棒性并输出攻击成功率，填补了VLA安全验证工具的空白。

---

### 🦾 操作与抓取
1. [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) ⭐3,191  
   GPU并行的机器人操作仿真与基准框架，支持上百种接触富集操作任务，是VLA操作策略训练与评测的主流平台。
2. [enactic/openarm](https://github.com/enactic/openarm) ⭐2,788  
   完全开源的人形机械臂，面向接触富集的物理AI研究与落地，是目前星标最高的开源人形手臂项目，大幅降低人形操作的硬件门槛。
3. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) ⭐43  
   开源双臂UMI数据采集软件，支持多传感器同步采集与任意双臂机器人的动作重定向，解决了VLA操作训练的数据采集痛点。
4. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) ⭐329  
   机器人操作官方基准库，提供统一的操作任务评测标准，被全球多所顶尖高校的机器人实验室采用。
5. [jpothen8/LeRobot-SafetyCubes](https://github.com/jpothen8/LeRobot-SafetyCubes) ⭐1  
   提出将碰撞避免通过可微安全损失嵌入VLA权重的新范式，替代传统运行时过滤方案，为操作安全提供了新的技术路径。

---

### 🚶 运动与导航
1. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) ⭐4,538  
   ROS2官方导航框架，支持路径规划、避障、定位全链路功能，是移动机器人领域的主流导航方案。
2. [introlab/rtabmap](https://github.com/introlab/rtabmap) ⭐3,924  
   跨平台实时SLAM库，支持单目、双目、RGB-D、激光雷达等多传感器，适配移动机器人、人形机器人的定位建图需求。
3. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) ⭐324  
   开源足式机器人软件栈，包含成熟的legged locomotion算法与动量控制器，支持人形、外骨骼、双足机器人的运动控制。
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) ⭐143  
   全身体人形遥操作系统，支持人体动作捕捉到机器人运动的实时映射，是人形机器人数据采集与远程控制的核心工具。
5. [robit-man/dropbear-locomotion](https://github.com/robit-man/dropbear-locomotion) ⭐0  
   基于Isaac Lab与RSL-RL PPO的Dropbear人形运动控制项目，提供已验证的运动检查点，可直接复现人形双足行走能力。

---

### 📦 具身应用
1. [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) ⭐0 (+227 today)  
   腾讯云开源的团队级Agent记忆中枢，可将对话、文档、代码转化为可复用的记忆资产，直接支持具身Agent的长期记忆管理，是国内首个落地级Agent记忆开源方案。
2. [bytedance/deer-flow](https://github.com/bytedance/deer-flow) ⭐0 (+209 today)  
   字节跳动开源的长周期SuperAgent框架，内置沙箱、记忆、工具调用、子Agent调度能力，可适配具身Agent的长horizon任务处理需求，是工业级具身Agent的核心基础设施。
3. [microsoft/TRELLIS.2](https://github.com/microsoft/TRELLIS.2) ⭐0 (+107 today)  
   微软开源的3D结构化生成模型，可生成紧凑的原生3D隐表示，为机器人场景感知、仿真环境构建提供底层支撑，是大公司布局具身感知核心技术的信号。
4. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) ⭐1,405  
   自进化具身AI操作系统，基于Agent工作流构建，支持具身Agent的技能进化、runtime管理与物理世界交互。
5. [cagataycali/scout-the-rover](https://github.com/cagataycali/scout-the-rover) ⭐8  
   VLA驱动的开源火星车项目，实现了视觉-语言-动作全链路控制，配套开源了专属ECoT数据集，是VLA落地移动机器人的典型案例。

---

## 趋势信号分析
今日社区信号显示，VLA工程化落地正进入爆发前夜：从中文入门手册、NVIDIA官方微调部署方案，到统一评测框架、红队安全测试工具，VLA全链路工具链近期快速补全，学术到产业的转化通路基本打通。微软、字节跳动、腾讯云等头部科技公司集中开源3D生成、长周期Agent、Agent记忆等具身底层基础设施，指向具身系统的标准化底座构建正在加速。此外，无ROS依赖的轻量机器人运行时、人形全栈开源方案的涌现，与近期人形机器人量产落地、具身AI融资升温的行业事件高度契合；具身安全作为细分方向首次登榜，成为继性能之后社区关注的新核心命题。（全文287字）

---

## 社区关注热点
- **VLA全链路开发栈**：开发者可通过《VLA-Handbook》快速入门，依托NVIDIA Alpamayo官方工具完成工业级微调，使用inspect-robots进行统一评测，形成闭环开发路径，大幅降低VLA研发的技术门槛。
- **人形机器人全栈开源方案**：enactic/openarm（开源人形臂）、dropbear-locomotion（可直接复现的运动控制检查点）、HORUS运行时组成的全栈方案，可帮助中小团队快速搭建人形研发原型，绕开商业硬件的高成本壁垒。
- **头部厂商开源的具身基础设施**：腾讯云Agent记忆、字节deer-flow长周期Agent、微软TRELLIS.2 3D生成均为落地级方案，提前适配这些工具可抢占未来具身系统标准化的先机，降低对接工业场景的成本。
- **具身安全细分赛道**：系统性的具身安全综述、VLA红队测试工具的出现，标志着安全性将成为具身系统落地的核心考核指标，目前相关研究与工程化存在较大空白，适合开发者提前布局。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*