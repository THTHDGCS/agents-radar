# AI 开源趋势日报 2026-07-31

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-31 01:45 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-31）

---

## 今日速览
今日具身智能与机器人开源社区热度集中在VLA开发工具链与具身交互组件，Agent性能优化系统ECC、Hugging Face本地语音代理分别拿下804、628的当日新增星，成为跨领域热门。VLA方向继续向实操化发展，NVIDIA发布Alpamayo模型的官方开发套件，国内社区也涌现出从入门到面试的全栈中文VLA学习资源。人形机器人与操作领域的仿真、基准工具持续迭代，无ROS的轻量化VLA部署框架获得开发者关注，sim2real落地工具链日趋完善。

---

## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、ROS、运动）
1. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) [C++] ⭐14,390  
   通用多关节接触物理仿真器，是VLA、机器人学习的标配仿真引擎，广泛应用于学术与工业场景
2. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) [Python] ⭐7,805  
   基于NVIDIA Isaac Sim的统一机器人学习框架，是当前具身智能仿真训练的主流工业级工具
3. [newton-physics/newton](https://github.com/newton-physics/newton) [Python] ⭐5,267  
   基于NVIDIA Warp的GPU加速物理仿真引擎，专门面向机器人学者，是sim2real训练的新兴高性能选择
4. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) [C++] ⭐4,530  
   ROS 2官方导航框架，是移动机器人导航的工业级标准方案
5. [RLinf/RLinf](https://github.com/RLinf/RLinf) [Python] ⭐4,345  
   面向具身和代理AI的强化学习基础设施，大幅简化RL算法在具身场景的部署与调试
6. [dora-rs/dora](https://github.com/dora-rs/dora) [Rust] ⭐3,856  
   Dataflow导向的机器人中间件，低延迟分布式数据流架构，是替代传统ROS的热门轻量机器人架构
7. [StanfordVL/BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) [Python] ⭐1,603  
   斯坦福大学推出的具身AI研究加速平台，是具身智能任务评测的主流学术基准

---

### 🧠 VLA/基础模型（视觉-语言-动作模型、模仿学习、强化学习策略）
1. [knightnemo/Awesome-World-Models](https://github.com/knightnemo/Awesome-World-Models) ⭐3,249  
   世界建模领域的精选资源列表，是VLA核心基础技术的一站式参考库
2. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) [Python] ⭐2,935  
   面向Python基础开发者的具身智能入门教程，从零构建VLA/OpenVLA/SmolVLA/Pi0，是国内社区最热门的VLA学习资源
3. [affaan-m/ECC](https://github.com/affaan-m/ECC) [JavaScript] ⭐0 (+804 today)  
   Agent性能优化系统，支持Claude Code、Opencode、Cursor等开发工具，提供技能、记忆、安全等核心能力，今日拿下Trending榜单新增星第一，是具身Agent开发的核心工具链
4. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) [HTML] ⭐454  
   全中文实战导向的VLA领域学习/面试手册，聚焦机器人特有挑战，是国内VLA从业者的核心参考
5. [robocurve/inspect-robots](https://github.com/robocurve/inspect-robots) [Python] ⭐96  
   开源物理AI评测框架，支持任意LLM/VLA在任意机械臂/人形上跑仿真/真实基准，是VLA评测的新兴通用工具
6. [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes) [Python] ⭐83  
   NVIDIA Alpamayo VLA模型的官方开发者中心，包含微调、RL后训练、量化、部署的现成方案，是商用级VLA开发的最新标准工具
7. [x-zheng16/Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) [Python] ⭐120  
   具身AI安全综述，覆盖感知、认知、规划等全链路的风险、攻击与防御方案，是VLA安全研究的核心参考

---

### 🦾 操作与抓取（灵巧手、抓取生成、接触富集任务）
1. [mani-skill/ManiSkill](https://github.com/mani-skill/ManiSkill) [Python] ⭐3,180  
   GPU并行化机器人操作仿真与基准框架，是VLA操作能力评测的主流学术基准
2. [enactic/openarm](https://github.com/enactic/openarm) [MDX] ⭐2,785  
   完全开源的人形机械臂，面向物理AI研究与接触富集环境部署，是操作硬件的开源新选择
3. [RoboTwin-Platform/RoboTwin](https://github.com/RoboTwin-Platform/RoboTwin) [Python] ⭐2,659  
   ICML 2026接收的RoboTwin 2.0官方仓库，面向具身智能的数字孪生平台，支持操作任务的sim2real迁移
4. [RoboDojo-Benchmark/RoboDojo](https://github.com/RoboDojo-Benchmark/RoboDojo) [Python] ⭐320  
   机器人操作基准平台，是VLA操作能力评测的新兴工具
5. [robonet-ai/handumi-sw](https://github.com/robonet-ai/handumi-sw) [Python] ⭐42  
   开源双手操作数据采集与重定向软件，支持同步采集数据重定向到任意双手机器人，是灵巧操作数据采集的核心工具

---

### 🚶 运动与导航（足式机器人、人形机器人、SLAM、路径规划）
1. [commaai/openpilot](https://github.com/commaai/openpilot) [Python] ⭐63,269  
   落地规模最大的开源机器人操作系统，目前支持300+车型的驾驶辅助升级，是具身智能大规模落地的标杆项目
2. [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) [Python] ⭐30,191  
   机器人算法的Python示例代码与教材，覆盖导航、SLAM、运动控制等核心内容，是机器人入门的经典资源
3. [manumerous/wb_humanoid_mpc](https://github.com/manumerous/wb_humanoid_mpc) [C++] ⭐351  
   人形机器人全身非线性MPC控制器，支持实时 loco-manipulation规划与控制，是人形运动控制的热门开源方案
4. [ihmcrobotics/ihmc-open-robotics-software](https://github.com/ihmcrobotics/ihmc-open-robotics-software) [Java] ⭐324  
   足式机器人运动算法软件，支持人形、四足、外骨骼等机器人的运动控制，是足式控制的经典框架
5. [mr-RSA369/WholebodyVLA](https://github.com/mr-RSA369/WholebodyVLA) ⭐2  
   统一VLA框架控制人形全身运动操作，是VLA向人形全身控制扩展的前沿探索

---

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [rerun-io/rerun](https://github.com/rerun-io/rerun) [Rust] ⭐11,216  
   多模态机器人数据可视化、查询、流处理工具，支持机器人训练数据的高效处理，是具身开发的核心调试工具
2. [huangjunsen0406/py-xiaozhi](https://github.com/huangjunsen0406/py-xiaozhi) [Python] ⭐3,428  
   开源AI助手生态，支持MCP集成、多模态工作流、IoT支持、跨平台语音交互，是具身交互的热门落地应用
3. [huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech) [Python] ⭐0 (+628 today)  
   基于开源模型的本地语音代理构建工具，是具身机器人语音交互的核心组件，今日Trending榜单新增星第二
4. [PhyAgentOS/PhyAgentOS](https://github.com/PhyAgentOS/PhyAgentOS) [Python] ⭐1,304  
   基于代理工作流的自进化具身AI操作系统，是具身智能OS的前沿探索
5. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) [Python] ⭐125  
   无ROS的轻量化sim2real框架，原生支持VLA和RL代理部署，支持Franka、UR5e等主流机械臂，适合快速VLA落地验证

---

## 趋势信号分析
今日社区爆发性关注集中在**具身Agent开发工具链与VLA落地基础设施**，两类项目拿下GitHub Trending榜单前两位的当日新增星，反映开发者对降低具身智能开发门槛的强烈需求。新兴方向方面，面向机器人的专用运行时系统、无ROS的轻量化VLA部署框架进入热门榜单，替代传统ROS的轻量架构正在形成新的技术路线。近期NVIDIA推出Alpamayo商用级VLA模型后，官方开发套件快速登榜，叠加国内VLA学习资源的密集发布，反映VLA正从学术研究转向工业落地的前期准备阶段，开发者生态的构建成为当前核心竞争点。

---

## 社区关注热点
- 🚀 [affaan-m/ECC](https://github.com/affaan-m/ECC)：今日新增804星的Trending热门项目，解决具身Agent的技能、记忆、安全核心痛点，是VLA/具身Agent开发的必备工具链
- 📚 [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied)：国内首个从零构建VLA的入门教程，仅需Python基础即可入门，大幅降低具身智能的学习门槛
- 🛠️ [NVlabs/alpamayo-recipes](https://github.com/NVlabs/alpamayo-recipes)：NVIDIA官方Alpamayo VLA开发套件，包含微调、部署全流程方案，代表商用级VLA开发的最新标准
- 🤖 [softmata/horus](https://github.com/softmata/horus)：定位为机器人“Android”的专用运行时系统，是替代传统ROS的新兴技术路线，值得长期跟踪

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*