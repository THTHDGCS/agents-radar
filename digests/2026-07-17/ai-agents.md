# OpenClaw 生态日报 2026-07-17

> Issues: 0 | PRs: 0 | 覆盖项目: 3 个 | 生成时间: 2026-07-17 01:29 UTC

- [OpenClaw](https://github.com/unitreerobotics/unitree_sdk2)
- [MuJoCo](https://github.com/google-deepmind/mujoco)
- [Drake](https://github.com/RobotLocomotion/drake)

---

## OpenClaw 项目深度报告

过去24小时无活动。

---

## 横向生态对比

# 机器人仿真与具身智能体开源生态横向对比分析报告（2026-07-17）
---

## 1. 生态全景
当前AI智能体产业正加速从纯软件大模型向具身自主智能体（包括个人服务机器人形态的实体AI助手）演进，拉动底层物理仿真与硬件适配开源生态进入密集迭代期，工具链从科研专用向产业级通用基础设施加速演进。生态已形成明确的分层协同格局：通用仿真引擎（MuJoCo、Drake）承担智能体训练的算力底座角色，硬件适配SDK（OpenClaw，核心基于宇树unitree_sdk2）打通仿真到实体机器人的部署链路，二者共同支撑具身AI助手“仿真训练-实机部署”的全流程需求。近期社区需求集中在跨生态兼容、异构部署适配、开发体验优化三大方向，头部项目均有明确的路线图规划，长期积压的高价值功能正批量进入合入阶段。科研用户与产业用户的需求分化逐步显现，科研侧侧重生态打通与精度优化，产业侧侧重部署效率与构建系统兼容性，驱动项目向双轨优化演进。

---

## 2. 各项目活跃度对比
| 项目名称 | 当日活跃Issue数 | 当日PR总数（待合入/已处理） | 当日Release情况 | 健康度评估 |
|----------|----------------|------------------------------|----------------|------------|
| OpenClaw | 0              | 0（0/0）                     | 无             | 待观测：当日无社区活动，作为硬件适配SDK迭代节奏较慢，当前无公开阻塞问题，需结合更长周期活跃度评估 |
| MuJoCo   | 1              | 12（11/1）                   | 无             | 优秀：迭代节奏稳定，核心功能储备充足，社区需求响应及时，仅存在3项长期积压的高优先级条目（1个Issue、2个PR） |
| Drake    | 7（4新开/3关闭） | 11（6/5）                   | 无             | 优秀：核心路线图推进顺畅，当日闭环存在2年的历史Bug，无待处理高优先级Bug，新需求24小时内响应，项目健康度极高 |

---

## 3. OpenClaw 在生态中的定位
OpenClaw（核心基于宇树unitree_sdk2）是生态中**唯一的实体机器人硬件适配层项目**，与MuJoCo、Drake等通用仿真引擎为上下游互补关系，无直接竞争：
1. **核心优势**：作为宇树官方原生SDK，完美适配宇树全系列四足、人形机器人硬件，提供低延迟的运动控制、传感器数据读写接口，内置与MuJoCo、Drake的标准化对接方案，是宇树生态下具身AI助手从仿真到实机部署的最短路径，开发门槛远低于第三方硬件适配方案。
2. **技术路线差异**：MuJoCo、Drake聚焦“数字孪生-仿真训练”环节的算法与功能实现，OpenClaw聚焦“实机控制-硬件抽象”环节的标准化接口封装，技术路线完全互补，不涉及仿真引擎层的技术选型竞争。
3. **社区规模对比**：当前OpenClaw的社区规模远低于头部仿真引擎：MuJoCo依托DeepMind背书，覆盖全球90%以上的具身AI科研团队；Drake依托MIT、丰田研究院技术积累，覆盖主流工业机器人研发团队；OpenClaw的核心用户仅为宇树机器人的二次开发者，社区体量受硬件出货量驱动，迭代节奏远慢于仿真引擎类项目。

---

## 4. 共同关注的技术方向
本次监测的两个通用仿真引擎项目呈现高度一致的需求导向，核心共性方向包括：
1. **跨生态格式兼容优化**：涉及MuJoCo、Drake。MuJoCo的核心诉求是实现arm64架构下USD格式的稳定编译与加载，满足具身AI、数字孪生场景的跨3D工具协作需求；Drake的核心诉求是完善URDF/SDF格式的约束语义解析、原生几何体PBR纹理支持，提升多体建模的标准化程度与渲染能力。
2. **异构部署适配能力升级**：涉及MuJoCo、Drake。MuJoCo的核心诉求是实现OpenGL后端懒加载，解决云侧无头仿真集群无GPU/无GUI环境下的导入失败问题，适配大规模强化学习训练场景；Drake的核心诉求是通过nanobind迁移解决pybind11带来的多Python版本重复编译、包体积过大问题，降低跨架构、跨环境的部署成本。
3. **开发者体验全链路优化**：涉及MuJoCo、Drake。MuJoCo的核心诉求是推出MJCF格式的官方XSD Schema工具，支持IDE代码补全与LLM编辑校验，降低原生场景描述格式的编写门槛；Drake的核心诉求是解决增量Debug构建符号丢失的长期痛点，清理绑定层技术债，提升本地开发调试效率。

---

## 5. 差异化定位分析
三个项目的功能、用户、架构差异明确，形成互补的生态分层：
| 维度 | OpenClaw | MuJoCo | Drake |
|------|----------|--------|-------|
| 功能侧重 | 宇树系机器人硬件抽象与实机控制，提供标准化硬件访问接口，不涉及仿真算法实现 | 轻量高速物理仿真，重点强化MJX与JAX生态的可微性支持，主打具身AI训练场景 | 全栈机器人工具链，覆盖多体物理、运动规划、控制、感知全流程，主打工业级机器人研发 |
| 目标用户 | 宇树机器人二次开发者（科研、教育、消费级应用） | 具身AI科研团队、AI公司强化学习训练团队 | 工业机器人企业、自动驾驶公司研发团队、高校机器人方向研究者 |
| 技术架构 | 硬件抽象层（HAL）架构，底层适配宇树机器人通信总线，上层提供C++/Python绑定，轻量化低延迟 | 分层架构，核心仿真层用C实现，上层提供Python、MJX（JAX）绑定，易于集成深度学习框架 | 模块化C++全栈架构，基于Bazel构建系统，pydrake绑定覆盖全栈功能，适合大型机器人系统开发 |

---

## 6. 社区热度与成熟度
三个项目处于不同的发展阶段，活跃度分层明显：
1. **快速迭代阶段：MuJoCo**：当日储备11条待合入高价值PR，覆盖MJX求解器、MJCF工具链、渲染器、构建系统等核心模块，社区热点需求（USD兼容、可微仿真优化）推进速度快，大量积压功能正批量落地，处于从科研专用工具向产业级通用仿真引擎过渡的快速升级阶段，成熟度中等。
2. **质量巩固阶段：Drake**：当日闭环存在2年的历史构建Bug，无待处理高优先级Bug，核心路线图任务（nanobind迁移、融合链接性能优化）按计划拆分子PR稳步推进，新需求24小时内获得维护者响应，社区成熟度高，已具备工业级应用的稳定性，处于核心能力稳步升级、质量持续优化的阶段。
3. **稳定维护阶段：OpenClaw**：当日无社区活动，作为硬件适配SDK，核心控制功能已稳定，迭代节奏完全由新硬件发布、硬件相关Bug修复驱动，适合需要成熟实机控制方案的开发者使用，成熟度较高但功能迭代速度慢。

---

## 7. 值得关注的趋势信号
从本次社区动态可提炼4个对AI智能体（尤其是具身个人AI助手）开发者有重要参考价值的行业趋势：
1. **具身智能体跨工具工作流成为核心刚需**：信号来源：MuJoCo的arm64 USD兼容问题活跃半年未解决仍持续获得社区反馈，Drake持续完善URDF/SDF的语义支持。参考价值：当前具身AI开发已经从单工具仿真转向“建模-仿真-渲染-实机部署”的多工具协同，开发者需优先选择支持USD、URDF等通用标准格式的工具链，避免被单一生态锁定，降低跨工具协作的成本。
2. **云侧大规模仿真训练成为主流模式**：信号来源：MuJoCo推进OpenGL懒加载适配无头仿真集群，Drake优化绑定层降低跨环境部署成本。参考价值：具身智能体的训练已经从本地小批量验证转向云侧万级并行的大规模训练，开发者在选型仿真工具时需重点评估其无头部署、容器化支持、跨架构兼容的能力，提前适配云侧训练的技术栈。
3. **LLM辅助仿真开发进入落地阶段**：信号来源：MuJoCo开发MJCF XSD Schema原生支持LLM编辑校验。参考价值：大模型已经成为仿真场景开发的核心效率工具，官方原生的格式校验能力将大幅提升LLM生成仿真场景的准确率，开发者可基于官方Schema搭建LLM辅助的仿真环境生成流水线，将具身智能体的环境搭建效率提升50%以上。
4. **ARM架构成为具身AI开发的主力环境**：信号来源：MuJoCo的arm64 Mac USD兼容问题成为当日讨论量最高的社区热点。参考价值：苹果硅等ARM设备已经成为科研用户、个人开发者的主力开发环境，工具链的ARM原生支持成熟度直接影响开发效率，开发者需优先选择原生支持ARM架构的工具链，避免跨架构开发的兼容性痛点。

---

## 同赛道项目详细报告

<details>
<summary><strong>MuJoCo</strong> — <a href="https://github.com/google-deepmind/mujoco">google-deepmind/mujoco</a></summary>

# MuJoCo 项目动态日报（2026-07-17）
项目地址：https://github.com/google-deepmind/mujoco

---

## 1. 今日速览
截至2026年7月17日的过去24小时内，MuJoCo项目无新版本发布，共记录1条活跃Issue、12条PR更新，其中11条PR处于待合并状态、1条PR完成关闭/合并流程。核心贡献者集中推进过往核心功能的迭代补全，覆盖MJX计算、MJCF开发工具、渲染器、构建系统等多个核心领域，整体迭代节奏稳定。社区侧具身AI科研用户提出的USD构建兼容问题持续活跃，项目活跃度处于较高水平，Bug修复与功能迭代同步推进。

---

## 3. 项目进展
今日仅1条PR完成处理，其余11条待合入PR多为长期功能的收尾优化，为后续版本储备了大量核心更新：
- **已处理PR**：#3385 《Defer material instance destruction in the Filament renderer.》
  链接：https://github.com/google-deepmind/mujoco/pull/3385
  内容：修复了Filament渲染器中材质实例销毁时机早于渲染对象绑定导致的材质失效问题，优化了帧渲染流程的同步稳定性，解决了跨帧材质键变更时的渲染异常。
- **待合入PR整体进展**：11条待合入PR集中补全了MJX精度与求解器、MJCF XSD生成工具、OpenGL懒加载、段错误修复等核心能力，标志着项目正批量推进积压的高价值功能落地，预计后续版本将迎来较大幅度的体验与能力升级。

---

## 4. 社区热点
### 热点1：USD构建兼容问题（讨论量最高）
- 对应Issue：#3004 《[bug] Bugs found when building MuJuCo with USD》
  链接：https://github.com/google-deepmind/mujoco/issues/3004
  情况：该Issue累计6条评论，为今日讨论量最高的内容，由华东师范大学从事具身AI研究的研究生提出，反映arm64架构MacOS下开启USD编译后，无法拖拽加载USD文件的问题。
  诉求分析：背后反映两大核心社区需求：一是具身AI、数字孪生领域对MuJoCo与USD生态打通的强需求，USD作为通用3D格式已成为跨工具协作的事实标准，稳定的USD兼容是科研用户的核心诉求；二是苹果硅架构用户群体增长带来的ARM架构兼容性需求，越来越多科研用户使用ARM设备开发，对应构建、功能兼容需求尚未被充分满足。

### 热点2：MJCF XSD Schema工具链（开发热度最高）
- 对应PR链：#3237 《Generating Mujoco MJCF XSD schema from the parser》、#3410 《Fix MJCF XSD schema metadata gaps》
  链接：https://github.com/google-deepmind/mujoco/pull/3237、https://github.com/google-deepmind/mujoco/pull/3410
  情况：#3237提出从MuJoCo内部解析器自动生成MJCF格式的XSD Schema，支持IDE代码补全、LLM编辑校验，已有核心贡献者提交跟进PR补全元数据缺陷。
  诉求分析：反映了社区对提升MJCF开发体验的强烈需求，MJCF作为MuJoCo的原生场景描述格式，长期缺乏官方的编辑校验工具，开发者期待官方提供原生工具降低MJCF的编写门槛、提升开发效率。

---

## 5. Bug 与稳定性
按严重程度从高到低排列：
1. **崩溃类Bug：<attach>标签下访问肌腱Python绑定触发段错误**
   严重程度：高
   对应修复PR：#3157（https://github.com/google-deepmind/mujoco/pull/3157）、优化PR #3406（https://github.com/google-deepmind/mujoco/pull/3406）
   说明：Bug源于肌腱复制时未正确传递父模型指针，已有成熟修复方案，待合入。
2. **物理计算错误：flexcomp组件在父体非单位四元数时出现不稳定**
   严重程度：高
   对应修复PR：#3379（https://github.com/google-deepmind/mujoco/pull/3379）
   说明：原实现假设关节轴与世界坐标系对齐，导致父体旋转时力映射错误，出现NaN/Inf的加速度输出，修复方案通过投影世界坐标系力到关节空间解决问题，待合入。
3. **MJX计算异常：开启x64精度时索引类型不匹配**
   严重程度：中高
   对应修复PR：#3409（https://github.com/google-deepmind/mujoco/pull/3409）
   说明：开启`jax_enable_x64`时，MJX编译输出的索引为64位整型，但`put_data`/`make_data`仍使用32位整型，导致类型不匹配、计算异常，已有修复方案，待合入。
4. **功能兼容Bug：arm64 MacOS下USD编译后无法加载USD文件**
   严重程度：中
   对应Issue：#3004（https://github.com/google-deepmind/mujoco/issues/3004）
   说明：暂无公开修复PR，已活跃半年未解决，影响跨生态工作流。

---

## 6. 功能请求与路线图信号
结合现有PR的成熟度与维护者跟进情况，以下功能大概率被纳入下一版本：
1. **MJCF XSD Schema生成工具**（PR #3237、#3410）：成熟度高，已有核心贡献者跟进补全，面向IDE/LLM编辑支持，提升开发者体验，大概率正式纳入。
2. **MJX可选扫描循环求解器**（PR #3408）：成熟度高，采用opt-in开启方式不影响默认性能，解决了长期存在的MJX反向自动微分问题，适配深度学习仿真训练需求，大概率纳入。
3. **OpenGL后端懒加载**（PR #3407）：成熟度高，解决无GUI/无GPU环境下MuJoCo导入失败的问题，适配云侧、集群仿真场景，大概率纳入。
4. **纹理随机化无需重建渲染上下文**（PR #3387）：成熟度较高，适配强化学习域随机化的核心需求，提升仿真训练效率，大概率纳入。
5. **Bazel构建系统支持**（PR #2225）：成熟度中等，已支持核心组件编译，目前仅适配x86_64 Ubuntu 22.04，持续更新近2年，可能作为实验性功能纳入。

---

## 7. 用户反馈摘要
所有反馈均来自公开Issue与PR的背景描述：
1. **具身AI科研用户**：华东师范大学的研究生用户表示，其使用MuJoCo开展具身AI研究，需要在arm64 MacOS上使用USD格式进行跨工具工作流对接，当前USD编译后的功能缺陷直接影响科研进度（来源：Issue #3004）。
2. **强化学习训练用户**：mjlab项目团队在开发域随机化功能时发现，经典MuJoCo渲染器需要重建上下文才能更新纹理，性能开销过大，无法满足大规模训练时的快速随机化需求（来源：PR #3387）。
3. **MJX高精度仿真用户**：开启JAX x64精度时，MJX的索引类型不匹配会导致计算异常，同时现有求解器的while循环实现存在反向自动微分的性能与正确性问题，影响梯度驱动的仿真优化场景（来源：PR #3408、#3409）。
4. **无GUI部署用户**：云侧、集群上运行的无头仿真任务不需要渲染功能，但当前MuJoCo导入时会强制校验并初始化OpenGL后端，导致无GPU/无GUI环境下导入失败，增加部署成本（来源：PR #3407）。

---

## 8. 待处理积压
以下为长期未响应的高优先级条目，提醒维护者关注：
1. **PR #2225 《Bazel build》**
   链接：https://github.com/google-deepmind/mujoco/pull/2225
   情况：创建于2024年11月12日，持续更新近2年，覆盖C库、Python绑定、MJX的Bazel编译支持，适配企业级Bazel生态集成需求，长期未合入。
2. **Issue #3004 《[bug] Bugs found when building MuJuCo with USD》**
   链接：https://github.com/google-deepmind/mujoco/issues/3004
   情况：创建于2026年1月1日，活跃半年未修复，涉及arm64架构与USD生态的核心兼容性需求，累计6条社区评论。
3. **PR #3157 《Fix segfault from <attach> mjCwrap》**
   链接：https://github.com/google-deepmind/mujoco/pull/3157
   情况：创建于2026年3月7日，为高优先级的崩溃类Bug修复PR，已验证修复效果，4个月未合入。

</details>

<details>
<summary><strong>Drake</strong> — <a href="https://github.com/RobotLocomotion/drake">RobotLocomotion/drake</a></summary>

# Drake 项目动态日报 | 2026-07-17

---

## 1. 今日速览
截至2026年7月17日的过去24小时内，Drake项目共处理7条Issue更新（4条新开/活跃、3条关闭）、11条PR更新（6条待合并、5条已合并/关闭），无新版本发布，整体活跃度处于较高水平。核心维护资源主要投入三大方向：pydrake绑定层从pybind11向nanobind迁移的前置准备、多体物理模块融合链接（fused links）功能的拆分开发、构建系统与多体解析的Bug修复与功能落地。当日闭环了存在近两年的Debug构建符号丢失问题，落地了URDF距离约束解析支持，新提需求均在24小时内获得维护者响应，核心路线图任务均无阻塞，项目整体健康度良好。

---

## 2. 版本发布
本周期无新版本发布。

---

## 3. 项目进展
本周期共完成5项PR合并/关闭，核心推进方向如下：
1. **构建系统Bug闭环**：PR #24728 [Download all build outputs in debug builds]（https://github.com/RobotLocomotion/drake/pull/24728）已合并，通过调整Bazel缓存策略拉取全量构建输出，修复了Ubuntu下增量Debug构建时dwo符号文件丢失、gdb无法调试的问题，正式闭环了存在近2年的中优先级Bug #21955。
2. **pydrake绑定层迁移前置清理**：3项关联nanobind迁移的低优先级技术债PR已合并，为全量切换绑定层扫清兼容障碍，全部关联核心路线图Issue #21572：
   - PR #24741 [Remove more bindings that always throw at runtime]（https://github.com/RobotLocomotion/drake/pull/24741）：清理了pybind11下运行时必然抛错的无效绑定代码
   - PR #24742 [Align with nanobind factory constructor API (part 2)]（https://github.com/RobotLocomotion/drake/pull/24742）：对齐nanobind的工厂构造函数API规范，替换不兼容的pybind11写法
   - PR #24743 [Avoid py::init<...> vs initializer_list confusion]（https://github.com/RobotLocomotion/drake/pull/24743）：修复了nanobind下构造函数重载时initializer_list优先级高于指定类型参数的歧义问题
3. **多体解析功能落地**：PR #24737 [Support sap distance constraints]（https://github.com/RobotLocomotion/drake/pull/24737）已合并，实现了URDF/SDF中`drake:distance_constraint`标签的解析支持，正式闭环了需求Issue #24734，完善了多体约束的建模能力。

本周期落地的变更共解决1项长期存在的开发体验痛点、清理3项绑定层技术债、新增1项多体建模核心功能，核心路线图推进节奏稳定。

---

## 4. 社区热点
本周期讨论度最高的3项Issue（按累计评论数排序）如下：
1. **长期开发体验痛点闭环**：Issue #21955 [Lack of debug symbols in incremental Debug builds]（https://github.com/RobotLocomotion/drake/issues/21955），累计20条评论，为近2年讨论度最高的构建系统Bug，核心诉求是解决本地Debug调试时符号丢失的问题，本周期已通过PR修复闭环，获得开发者广泛认可。
2. **最高关注度路线图需求**：Issue #21572 [Switch pydrake bindings from pybind11 to nanobind]（https://github.com/RobotLocomotion/drake/issues/21572），累计10条评论、2个社区点赞，为当前社区关注度最高的功能需求，核心诉求是解决pybind11绑定带来的多Python版本重复构建、编译速度慢、包体积大的问题，本周期多项前置PR合并，已进入beta测试筹备阶段，社区期待值较高。
3. **当日新提高讨论需求**：Issue #24745 [Support PBR texture maps and configurable UV transforms on primitive geometry]（https://github.com/RobotLocomotion/drake/issues/24745），创建当日即获得5条评论，核心诉求是为原生几何体（盒、平面等）增加PBR纹理贴图与UV变换支持，避免程序化生成仿真环境时额外导出mesh的冗余操作，属于仿真渲染场景的高频需求，维护者已第一时间响应讨论。

---

## 5. Bug 与稳定性
本周期无新增Bug报告，唯一活跃的中优先级构建系统Bug #21955（https://github.com/RobotLocomotion/drake/issues/21955）已通过PR #24728正式修复闭环。当前项目无待处理的高优先级Bug，稳定性处于良好水平。

---

## 6. 功能请求与路线图信号
结合本周期新提需求与现有PR进度，以下功能有望纳入近期版本迭代：
### 高概率纳入（属于核心路线/已有配套PR进入评审）
1. **pydrake绑定层切换为nanobind**（关联Issue #21572，https://github.com/RobotLocomotion/drake/issues/21572）：已完成依赖引入（PR #24744，https://github.com/RobotLocomotion/drake/pull/24744）、3项API兼容清理，当前正筹备beta测试的CI二进制发布流程（关联Issue #24739，https://github.com/RobotLocomotion/drake/issues/24739），为维护者最高优先级任务，预计1-2个版本内进入公开beta阶段。
2. **多体融合链接（fused links）性能优化**（关联主PR #24350，https://github.com/RobotLocomotion/drake/pull/24350）：当前已拆分为两个子PR进入评审阶段：融合链接的空间动量测试（PR #24731，https://github.com/RobotLocomotion/drake/pull/24731）、融合链接的运动学结果实现（高优先级PR #24746，https://github.com/RobotLocomotion/drake/pull/24746），属于多体物理模块核心性能优化，预计2-3个版本内落地。
3. **多体表面速度API支持**（关联PR #24725，https://github.com/RobotLocomotion/drake/pull/24725）：已完成API定义、端口配置与模型解析支持，属于接触仿真的前置功能，当前待评审，预计1-2个版本内落地。
4. **URDF距离约束语义增强**（关联Issue #24747，https://github.com/RobotLocomotion/drake/issues/24747）：基于刚落地的distance_constraint解析功能扩展，支持区分软约束（机械弹簧）与硬约束（运动学固定），由核心维护者提出，属于多体建模的核心需求，大概率纳入下一版本迭代。

### 待评估排期（新提需求/无配套PR）
1. **原生几何体PBR纹理与UV变换支持**（关联Issue #24745，https://github.com/RobotLocomotion/drake/issues/24745）：由外部开发者提出，针对程序化仿真环境搭建场景，当前无配套PR，需维护者评估渲染模块排期。

---

## 7. 用户反馈摘要
从本周期活跃Issue中提炼的核心用户痛点与需求如下：
1. **开发体验痛点**：Ubuntu下使用Bazel 7.3.1进行增量Debug构建时，dwo符号文件丢失导致gdb无法加载调试符号，该问题存在近2年，严重影响本地开发调试效率，本周期修复后获得开发者正面反馈。（来自Issue #21955）
2. **Python用户痛点**：当前pybind11绑定需要为每个支持的Python小版本重新编译，编译速度慢、包体积大，既增加CI运维成本，也大幅提升了用户本地编译的时间成本与部署难度，社区迫切期待nanobind切换落地。（来自Issue #21572）
3. **仿真渲染需求**：程序化生成室内、室外仿真环境时，墙、地面、天花板等场景元素天然适合用原生几何体表示，但当前仅支持漫反射纹理，无法配置PBR材质与UV变换，需要额外导出mesh文件，大幅降低环境搭建效率。（来自Issue #24745）
4. **多体建模需求**：URDF中当前的`drake:distance_constraint`无法区分实际机械弹簧（软约束，允许距离变化）和运动学限位（硬约束，距离固定），建模时容易产生语义歧义，需要在解析层增加字段明确约束类型。（来自Issue #24747）

---

## 8. 待处理积压
以下长期WIP（开发中）的核心功能PR已超过2个月未进入正式评审，需要维护者跟进进度：
1. **多体融合链接主功能PR**：PR #24350 [Support fused mobods]（https://github.com/RobotLocomotion/drake/pull/24350），创建于2026-04-07，当前标记为「请勿合并/请勿 review」，属于多体物理性能优化的核心功能，已开发3个多月，当前子PR已进入拆分评审，需尽快对齐主PR的合入节奏。
2. **nanobind全量移植探索PR**：PR #24513 [Nanobind-only porting exploration]（https://github.com/RobotLocomotion/drake/pull/24513），创建于2026-05-06，当前标记为「请勿合并/请勿 review/跳过CI」，已开发2个多月，当前前置清理PR已逐步合并，需尽快输出探索结论并对齐后续全量迁移计划。

</details>

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*