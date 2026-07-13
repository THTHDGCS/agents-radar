# AI 开源趋势日报 2026-07-13

> 数据来源: GitHub Trending + GitHub Search API | 生成时间: 2026-07-13 01:30 UTC

---

# 具身智能与机器人开源趋势日报（2026-07-13）
---
## 今日速览
今日GitHub具身智能与机器人领域热度集中在落地安全、民用场景与开发者生态三个方向；其中Agent执行防护工具、开源智能家居系统分别拿下今日Trending相关项目新增星前两位；VLA领域的中文学习资源、低门槛入门项目密集更新，对应国内开发者入场需求的快速释放；人形机器人的底层运行时、全栈开源硬件生态也出现多个高潜力新项目，行业正从单点模型研发逐步转向落地与底层标准构建。

---
## 各维度热门项目
### 🤖 机器人框架/SDK（控制、仿真、规划、运动）
1. [dora-rs/dora](https://github.com/dora-rs/dora) [Rust] ⭐3,840
   数据流导向的机器人中间件，提供低延迟、可组合的分布式数据处理能力，是当前AI机器人应用开发的热门底层架构。
2. [commaai/openpilot](https://github.com/commaai/openpilot) [Python] ⭐63,088
   成熟度极高的开源机器人操作系统，已落地支持300+车型的辅助驾驶升级，是具身智能规模化落地的标杆项目。
3. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) [C++] ⭐14,177
   通用多关节动力学物理仿真器，是机器人学习、VLA模型训练的标配仿真底座，生态覆盖几乎所有主流具身研发团队。
4. [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) [Python] ⭐7,661
   基于NVIDIA Isaac Sim的统一机器人学习框架，近期已成为VLA sim2real训练的首选工具链，社区活跃度持续攀升。
5. [softmata/horus](https://github.com/softmata/horus) [Rust] ⭐388
   主打人形机器人的高速运行时系统，对标手机端的Android，瞄准未来人形机器人系统层标准化需求，为今日首次登榜的新兴方向项目。
6. [RobotControlStack/robot-control-stack](https://github.com/RobotControlStack/robot-control-stack) [Python] ⭐124
   无ROS依赖的轻量sim2real框架，原生支持VLA模型与RL代理的训练部署，适配多款主流机械臂，降低实机落地门槛。

### 🧠 VLA/基础模型（视觉-语言-动作、学习策略）
1. [datawhalechina/every-embodied](https://github.com/datawhalechina/every-embodied) [Python] ⭐2,633
   面向Python基础开发者的从零构建具身智能机器人教程，覆盖OpenVLA、SmolVLA等主流模型，是当前入门门槛最低的具身学习资源。
2. [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook) [HTML] ⭐378
   国内首份全中文实战导向VLA学习/面试手册，专门覆盖机器人场景特有的技术挑战，是算法工程师切入具身领域的热门资源。
3. [InternRobotics/InternVLA-A-series](https://github.com/InternRobotics/InternVLA-A-series) [Python] ⭐484
   开源的统一理解、生成、动作的机器人操作VLA模型，是国内为数不多的可落地工业级VLA项目。
4. [YuZhaoshu/Efficient-VLAs-Survey](https://github.com/YuZhaoshu/Efficient-VLAs-Survey) ⭐169
   高效VLA模型的前沿综述 curated 列表，持续更新技术进展，是VLA研究者的必备导航资源。
5. [xiaoms22/lunavla](https://github.com/xiaoms22/lunavla) [Python] ⭐2
   新手友好型VLA入门项目，支持CPU运行、包含完整的模仿学习与评估流程，大幅降低普通开发者上手VLA的门槛。
6. [provael/provael](https://github.com/provael/provael) [Python] ⭐3
   开源VLA策略红队测试框架，可在仿真环境中测试VLA的安全性并输出攻击成功率，是VLA安全评估的新兴工具。

### 🦾 操作与抓取（灵巧手、接触富集任务）
1. [enactic/openarm](https://github.com/enactic/openarm) [MDX] ⭐2,709
   完全开源的人形机械臂，面向接触富集环境的物理AI研究，是当前操作领域最活跃的开源硬件平台。
2. [Manas-arumalla/openarm-control](https://github.com/Manas-arumalla/openarm-control) [Python] ⭐3
   OpenArm v2的全栈控制、规划、感知、学习平台，支持双臂操作、RL训练、ACT视觉策略，配套完整的落地工具链。
3. [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) [Python] ⭐2,511
   模块化机器人操作仿真框架与基准，是操作任务学习、VLA评测的标准测试环境。
4. [NVIDIA-ISAAC-ROS/isaac_ros_manipulation](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_manipulation) [C++] ⭐108
   NVIDIA官方加速的机械臂操作工作流，适配Isaac Sim与实机部署，工业落地友好。
5. [InternRobotics/Cortex](https://github.com/InternRobotics/Cortex) [Python] ⭐25
   面向长 horizon 操作任务的双向对齐具身Agent框架，提升复杂操作任务的执行成功率。

### 🚶 运动与导航（足式、人形、SLAM、路径规划）
1. [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) [C++] ⭐4,456
   ROS 2官方导航框架与系统，是移动机器人导航的工业级标准实现，生态成熟度极高。
2. [hku-mars/UMI-3D](https://github.com/hku-mars/UMI-3D) [Python] ⭐254
   UMI-3D SLAM与数据处理流水线，适配具身智能的三维环境感知需求，支持实机快速部署。
3. [zju3dv/habitat-gs](https://github.com/zju3dv/habitat-gs) [C++] ⭐246
   ECCV2026最新的高保真动态高斯溅射导航模拟器，大幅提升仿真到实机的导航泛化性。
4. [BotRunner64/Teleopit](https://github.com/BotRunner64/Teleopit) [Python] ⭐131
   轻量可扩展的人形机器人全身遥操作框架，解决人形机器人训练数据采集的核心痛点。
5. [Open-X-Humanoid/TienKung-Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) [Python] ⭐807
   面向足式机器人的直接IsaacLab工作流，大幅简化足式机器人的仿真训练流程。

### 📦 具身应用（sim2real、遥操作、自主系统、落地部署）
1. [Dicklesworthstone/destructive_command_guard](https://github.com/Dicklesworthstone/destructive_command_guard) [Rust] ⭐0 (+444 today)
   轻量级破坏性命令防护工具，阻止AI Agent执行危险的git/shell命令，解决具身Agent执行端的安全风险，为今日Trending相关项目新增星第一。
2. [home-assistant/core](https://github.com/home-assistant/core) [Python] ⭐0 (+400 today)
   主打本地控制与隐私的开源智能家居系统，是民用具身自主系统的标杆项目，今日登榜标志着民用具身落地场景热度快速上升。
3. [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) [TypeScript] ⭐0 (+210 today)
   面向Claude的MCP服务器，为大模型提供终端控制、文件系统搜索与差分编辑能力，是具身Agent接入桌面操作场景的核心工具。
4. [strands-labs/robots](https://github.com/strands-labs/robots) [Python] ⭐102
   通过自然语言控制机器人与物理硬件的Agent工具链，大幅降低VLA模型落地到实机的开发门槛。
5. [oliviazzzu/minimal-embodiment](https://github.com/oliviazzzu/minimal-embodiment) [C++] ⭐219
   最小化的大模型闭环物理具身软硬件架构，自带自感知循环，是轻量化具身实机部署的高参考价值实现。

---
## 趋势信号分析
今日社区热度呈现三大核心趋势：一是具身智能的落地安全与民用场景爆发，Agent执行防护工具、开源智能家居系统单日新增星均突破400，标志着社区关注点从模型性能转向落地的可用性与安全性，与近期工业界具身Agent接入实体操作权限的落地节奏高度匹配；二是VLA入门生态快速完善，中文实战手册、零GPU门槛的入门项目集中登榜，对应国内人形机器人、具身智能产业的融资与政策利好下，开发者入场需求激增；三是机器人底层系统标准化方向出现新兴项目，主打人形通用运行时的HORUS首次进入热榜，瞄准未来人形机器人的系统层统一需求，行业开始从单点技术突破转向生态标准构建。（全文287字）

---
## 社区关注热点
- 🛡️ 具身Agent执行安全工具 [Dicklesworthstone/destructive_command_guard](https://github.com/Dicklesworthstone/destructive_command_guard)：今日Trending相关项目新增星第一，随着具身Agent获得终端、实体操作权限，执行端安全成为落地的核心前置要求，该项目提供了轻量、开箱即用的危险命令拦截能力，填补了细分领域的空白。
- 📚 全中文VLA实战手册 [sou350121/VLA-Handbook](https://github.com/sou350121/VLA-Handbook)：国内首份聚焦VLA领域的中文学习/面试手册，专门覆盖机器人场景特有的技术挑战，适合算法工程师快速从通用AI切入具身智能领域。
- 🦾 全栈开源人形机械臂生态 [enactic/openarm](https://github.com/enactic/openarm) + [Manas-arumalla/openarm-control](https://github.com/Manas-arumalla/openarm-control)：从硬件到控制、感知、学习的全栈开源方案，支持接触富集操作任务的研究与落地，大幅降低物理AI的研发门槛，是当前操作领域最活跃的开源硬件项目。
- 🎯 低门槛VLA入门项目 [xiaoms22/lunavla](https://github.com/xiaoms22/lunavla)：无需GPU即可运行的VLA starter项目，包含完整的模仿学习、策略评估流程与求职友好型文档，适合普通开发者快速体验VLA全流程开发。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*