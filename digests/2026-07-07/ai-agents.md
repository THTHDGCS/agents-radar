# OpenClaw 生态日报 2026-07-07

> Issues: 500 | PRs: 500 | 覆盖项目: 3 个 | 生成时间: 2026-07-07 09:17 UTC

- [OpenClaw](https://github.com/openclaw/openclaw)
- [NanoBot](https://github.com/HKUDS/nanobot)
- [Hermes Agent](https://github.com/nousresearch/hermes-agent)

---

## OpenClaw 项目深度报告

# OpenClaw 项目动态日报 2026-07-07

## 今日速览
2026年7月7日OpenClaw项目活跃度处于高位，过去24小时共更新500条Issues、500条PR，其中110条Issues已闭环，216条PR已合并或关闭，无新版本发布。当日迭代核心聚焦消息链路稳定性修复、跨端功能对齐、安全边界加固三大方向，社区讨论热度集中在跨平台客户端、多代理编排、私有化部署三类核心需求，整体处于高密度功能迭代与历史问题清理阶段，项目健康度良好。

## 项目进展
过去24小时共闭环216条PR、110条Issues，核心推进方向及重要成果如下：
1. **飞书消息链路优化闭环**：PR #73399 [CLOSED]（openclaw/openclaw#73399）已合并，补全飞书单聊场景的显示名 fallback 逻辑，对齐群聊标签实现，解决飞书会话标识混乱的历史问题。
2. **systemd部署稳定性优化闭环**：PR #66444 [CLOSED]（openclaw/openclaw#66444）已合并，修复systemd托管场景下单元文件迁移 regression，解决`ExecStart`缺失、`WorkingDirectory`陈旧导致的启动失败问题，简化托管环境配置逻辑。
3. **高优先级需求闭环**：长期高热度需求「预编译Android APK发布」Issue #9443 [CLOSED]（openclaw/openclaw#9443）已闭环，后续版本将提供官方预编译APK下载，无需用户自行编译Android端代码。
4. **核心Bug闭环**：
   - Issue #98416 [CLOSED]（openclaw/openclaw#98416）：v2026.6.11版本重入 guard 缺失导致的会话初始化冲突问题已修复。
   - Issue #53599 [CLOSED]（openclaw/openclaw#53599）：Chrome扩展浏览器中继移除的跨机器访问回归问题已闭环。
   - Issue #45388 [CLOSED]（openclaw/openclaw#45388）：TUI会话模式无法实时流式接收消息的问题已修复。

## 社区热点
过去24小时社区讨论热度最高的内容均为Issues（PR评论数据暂缺），按热度排序及诉求分析如下：
1. **跨平台桌面客户端需求**：Issue #75 [OPEN]（openclaw/openclaw#75），评论110条、获赞81，为社区长期最高热度需求。用户诉求为补充Linux、Windows端的Clawdbot桌面客户端，功能与现有macOS端对齐，核心驱动为企业用户需要统一的多桌面端部署方案。
2. **工具调用文本泄漏Bug**：Issue #25592 [OPEN]（openclaw/openclaw#25592），评论33条，为当日最高热度Bug。用户反馈代理工具调用过程中的中间文本（错误提示、处理确认、内部 narration 等）会泄漏到Slack、iMessage等外部消息通道，严重影响用户体验与信息安全，核心诉求为严格隔离内部处理逻辑与外部消息输出。
3. **私有网络访问权限需求**：Issue #39604 [OPEN]（openclaw/openclaw#39604），评论13条、获赞11，为私有化部署场景核心需求。用户诉求为新增`tools.web.fetch.allowPrivateNetwork`配置项，允许显式开启内网地址访问权限，解决私有化部署场景下工具无法访问内部服务的问题。
4. **多代理知识隔离需求**：Issue #63829 [OPEN]（openclaw/openclaw#63829），评论12条、获赞9，为企业多代理部署核心需求。用户诉求为支持每个代理配置独立的memory-wiki vault，避免多代理共享全局知识库导致的信息泄漏与逻辑冲突。

## Bug 与稳定性
按严重程度排序今日活跃的核心Bug，标注修复进展：
### P0级（阻塞发布）
- **会话压缩超时死循环**：Issue #43661 [OPEN]（openclaw/openclaw#43661），当会话上下文过大触发压缩超时后，代理进入无自动恢复的死循环，每10分钟重试发送同一条消息，导致用户收到大量重复内容。当前无关联修复PR，为最高优先级待处理问题。

### P1级（高影响）
1. **工具调用文本泄漏到外部通道**：Issue #25592 [OPEN]（openclaw/openclaw#25592），影响所有外部消息渠道的UX与安全，已有关联修复PR待合并。
2. **Signal daemon重启竞态条件**：Issue #22676 [OPEN]（openclaw/openclaw#22676），SIGUSR1重启时旧进程未退出就启动新进程，导致端口占用、配置锁冲突，引发孤儿进程与消息发送失败，已有关联修复PR待合并。
3. **doctor --fix 命令性能严重回归**：Issue #85333 [OPEN]（openclaw/openclaw#85333），2026.5.20版本的`openclaw doctor --fix`命令执行耗时从55秒升至229秒以上，核心原因为会话快照路径遍历逻辑瓶颈，当前无修复PR。
4. **agentDir 配置的bootstrap文件被静默忽略**：Issue #29387 [OPEN]（openclaw/openclaw#29387），仅全局workspace下的bootstrap文件生效，单代理专属配置不生效，导致多代理配置混乱，已有关联修复PR待合并。
5. **多代理编排稳定性问题**：Issue #43367 [OPEN]（openclaw/openclaw#43367），并发创建代理时配置被覆盖、会话锁失效、子任务脱离管控，导致批量任务失败率高，已有关联修复PR待合并。
6. **exec工具不继承skills环境变量**：Issue #31583 [OPEN]（openclaw/openclaw#31583），回归问题，无法通过skills配置注入密钥等环境变量，影响工具执行的安全性与灵活性，当前无修复PR。
7. **Gemini模型兼容性回归**：Issue #38327 [OPEN]（openclaw/openclaw#38327），2026.3.2版本使用google-vertex/gemini-3.1-pro时触发「无法将undefined或null转换为对象」错误，导致代理完全不可用，当前无修复PR。
8. **心跳机制阻塞Telegram消息处理**：Issue #40611 [OPEN]（openclaw/openclaw#40611），2026.3.7版本的心跳漂移修复导致活跃会话期间Telegram消息处理被阻塞，已有关联修复PR待合并。

### P2级（中影响）
1. **WebChat/Control UI头像加载失败**：Issue #38439 [OPEN]（openclaw/openclaw#38439）、Issue #41201 [OPEN]（openclaw/openclaw#41201），头像接口返回404或本地路径无法加载，影响UI体验，当前无修复PR。
2. **内存管理逻辑不一致**：Issue #43747 [OPEN]（openclaw/openclaw#43747），不同用户的代理实例内存存储逻辑不统一，部分存入SQLite、部分存入本地文件，导致数据同步与迁移困难，当前无修复PR。
3. **write工具/exec heredocs换行符转义错误**：Issue #93139 [OPEN]（openclaw/openclaw#93139），内容中的转义换行符`\n`被作为字面量写入，而不是实际换行，影响脚本与文件生成的正确性，当前无修复PR。

## 功能请求与路线图信号
结合用户需求与现有PR进展，判断以下功能的落地可能性：
### 已确认纳入下版本
- **预编译Android APK发布**：Issue #9443 [CLOSED]（openclaw/openclaw#9443），关联PR已合并，下版本将提供官方APK下载。

### 大概率纳入下版本（已有PR待合并）
1. **Android端LaTeX数学公式渲染**：PR #101435 [OPEN]（openclaw/openclaw#101435），已实现聊天界面的LaTeX渲染，与iOS端功能对齐，待维护者审核后合并。
2. **Android端链接预览OG图片支持**：PR #101396 [OPEN]（openclaw/openclaw#101396），已实现链接预览卡的OpenGraph图片加载，与iOS端功能对齐，待维护者审核后合并。
3. **Cron任务日历时间线视图**：PR #41892 [OPEN]（openclaw/openclaw#41892），已实现Control UI的24小时Cron任务时间线视图，截图验证充分，待作者完成修改后合并。
4. **备份CLI .gitignore式排除规则**：Issue #40786 [OPEN]（openclaw/openclaw#40786），关联PR已提交，支持备份时排除指定文件/目录，解决备份体积过大、敏感数据泄漏问题，待审核后合并。
5. **Telegram Business Bot支持**：Issue #20786 [OPEN]（openclaw/openclaw#20786），关联PR已提交，支持接收Telegram Business连接的个人账号消息，待审核后合并。

### 已纳入路线图（方案确认待开发）
1. **单代理独立memory-wiki vault**：Issue #63829 [OPEN]（openclaw/openclaw#63829），高赞企业需求，方案已明确，待开发排期。
2. **网关层代理成本预算管控**：Issue #42475 [OPEN]（openclaw/openclaw#42475），企业级成本管控需求，方案已明确，待开发排期。
3. **分级bootstrap文件加载**：Issue #22438 [OPEN]（openclaw/openclaw#22438），解决大工作空间下的token浪费问题，方案已明确，待开发排期。

## 用户反馈摘要
从今日活跃Issues中提炼的真实用户反馈如下：
1. **跨端部署痛点**：大量企业用户缺乏Linux/Windows桌面客户端支持，只能通过浏览器或命令行使用，部署与维护成本高；Android用户普遍反馈自行编译APK门槛高，官方预编译包的需求极为强烈，该需求闭环后获得社区积极反馈。
2. **多代理编排痛点**：使用多代理进行批量编码、客服任务的企业用户反馈，当前多代理编排的稳定性不足，并发场景下的配置覆盖、会话锁失效问题导致任务失败率高，无法支撑生产级部署。
3. **私有化部署痛点**：内网部署用户反馈`web.fetch`默认禁止私有网络访问、硬编码SQLite存储的设计，导致无法对接内部服务、无法复用现有PostgreSQL基础设施，运维成本大幅提升。
4. **消息链路痛点**：面向外部用户的客服场景用户反馈，工具调用的中间文本泄漏到聊天窗口会严重影响专业形象，甚至泄漏内部处理逻辑，是核心的体验与安全痛点。
5. **开发体验痛点**：Windows用户反馈exec工具硬编码PowerShell，复杂命令的转义成本极高；TypeScript二次开发者反馈核心代码的非空断言导致静态分析报错，影响二次开发效率。
6. **正面反馈**：近期上线的iOS端LaTeX渲染、链接预览功能获得用户高度认可，用户普遍期待Android端同步上线对应功能，相关PR提交后社区反应积极。

## 待处理积压
以下为长期未响应、影响面广的重要Issue/PR，提醒维护者关注：
1. **跨平台桌面客户端需求**：Issue #75 [OPEN]（openclaw/openclaw#75），2026年1月1日创建，社区最高热度需求，当前仅标注「需要产品决策」，无明确排期，建议尽快确认跨端客户端的落地路线。
2. **PostgreSQL存储支持需求**：Issue #90370 [OPEN]（openclaw/openclaw#90370），2026年6月4日创建，标注stale，企业级核心需求，当前无维护者响应，建议尽快确认架构适配方案与排期。
3. **多代理协作增强RFC**：Issue #35203 [OPEN]（openclaw/openclaw#35203），2026年3月5日创建，涉及多代理能力画像、共享黑板、分层内存、成本治理四大核心能力，为长期架构演进方向，当前无后续进展，建议尽快确认路线图优先级。
4. **Cron日历时间线视图PR**：PR #41892 [OPEN]（openclaw/openclaw#41892），2026年3月10日创建，状态为「等待作者反馈」，功能验证充分，建议维护者主动跟进作者完成剩余修改，尽快合并。
5. **Discord媒体上传修复PR**：PR #41265 [OPEN]（openclaw/openclaw#41265），2026年3月9日创建，状态为「需要实际运行证明」，建议维护者主动引导作者补充验证材料，解决Discord动图、WebP图片上传的质量问题。
6. **doctor --fix性能回归问题**：Issue #85333 [OPEN]（openclaw/openclaw#85333），2026年5月22日创建，标注stale，P1级性能问题，当前无修复进展，建议优先安排排查修复。

---

## 横向生态对比

# 个人AI助手/自主智能体开源生态横向对比分析报告
**数据周期：2026-07-07 | 分析对象：OpenClaw、NanoBot、Hermes Agent**

---

## 1. 生态全景
2026年Q3个人AI助手与自主智能体开源生态已完成原型验证阶段，全面进入生产级落地的核心迭代周期。当日三大主流项目均处于高位活跃度，核心迭代方向从早期的功能堆料，转向跨端体验对齐、安全基线加固、企业级特性补全三大主线。社区需求高度集中于私有化部署适配、多代理编排稳定性、消息链路安全隔离三类生产级痛点，企业用户诉求占比显著提升。同时第三方开发者的深度贡献（如全量代码审计、核心功能PR）占比持续提升，生态协作的深度与成熟度快速提升。

---

## 2. 各项目活跃度对比
| 项目名称 | 24h Issues 总更新/闭环数 | 24h PR 总更新/闭环数 | 当日Release情况 | 健康度评估 |
| --- | --- | --- | --- | --- |
| OpenClaw | 500 / 110 | 500 / 216 | 无新版本发布 | 优秀：高密度功能迭代与历史问题清理并行，核心需求响应及时，仅1项待处理P0级Bug，生产级可用性高 |
| NanoBot | 43 / 2 | 34 / 12 | 无新版本发布 | 良好：代码审计与0.2.x版本回归问题集中暴露，核心安全问题修复响应快，需强化版本兼容性测试与默认安全基线 |
| Hermes Agent | 50 / 10 | 50 / 18 | 无新版本发布 | 优秀：当日全部P1级Bug完成闭环，稳定性迭代优先级高，社区需求响应积极，核心运行时成熟度高 |

---

## 3. OpenClaw 在生态中的定位
OpenClaw是当前开源智能体生态的核心标杆项目，与同类项目的差异清晰：
### 核心优势
1. 消息链路适配最完善，已覆盖飞书、Slack、Telegram、iMessage等主流IM通道，跨端能力（iOS、Android、桌面端）布局最全面；
2. 企业级特性积累最深，多代理编排、私有化部署、权限管控等需求的响应优先级最高，生产级落地案例最多。
### 技术路线差异
走「全通道消息接入+多代理统一编排+私有化部署底座」的一体化全栈路线，不同于NanoBot的轻量个人自托管定位、Hermes Agent的MoA（混合代理架构）与模型能力优先定位，更侧重普适性的生产级可用性与兼容性。
### 社区规模对比
单日Issue/PR更新量均达500量级，是NanoBot的11倍、Hermes Agent的10倍；核心需求的评论/点赞量（最高110条评论、81个赞）是另外两个项目的10-20倍，为当前生态中社区规模最大、用户覆盖最广的项目。

---

## 4. 共同关注的技术方向
三大项目的迭代需求高度重合，核心共同方向如下：
1. **生产级安全基线加固**（涉及所有3个项目）：核心诉求为补齐默认安全配置、修复权限与数据泄露风险。OpenClaw聚焦工具调用内部文本泄漏、安全边界加固；NanoBot集中修复SSRF、未授权API token签发、密钥明文存储等35项审计出的安全问题；Hermes Agent修复会话重放触发高危操作、Cron任务路径安全拦截等风险。
2. **多代理架构稳定性优化**（涉及OpenClaw、Hermes Agent）：核心诉求为解决并发场景下的状态冲突、资源隔离问题。OpenClaw修复多代理并发创建时的配置覆盖、会话锁失效问题，落地单代理独立知识库能力；Hermes Agent修复MoA架构下的自定义模型凭证传递问题，新增会话前置内存健康钩子避免长会话溢出。
3. **消息通道链路稳定性与兼容性**（涉及所有3个项目）：核心诉求为保障多IM通道的消息隔离、送达与功能一致性。OpenClaw修复飞书会话标识混乱、Telegram心跳阻塞消息处理问题；NanoBot修复WhatsApp群组白名单回归、Slack通道依赖缺失问题；Hermes Agent修复网关会话历史丢失、Telegram待澄清状态下忽略语音消息问题。
4. **私有化部署场景适配**（涉及所有3个项目）：核心诉求为降低自托管与内网部署的运维成本、满足离线使用需求。OpenClaw新增私有网络访问权限配置、支持PostgreSQL存储替代硬编码SQLite；NanoBot优化工作区默认权限隔离、提升自托管默认安全基线；Hermes Agent新增本地STT/TTS/媒体生成的配置UI、修复自定义模型路由错误问题。

---

## 5. 差异化定位分析
| 维度 | OpenClaw | NanoBot | Hermes Agent |
| --- | --- | --- | --- |
| 功能侧重 | 全通道消息接入、多代理统一编排、跨端客户端覆盖，优先满足企业级生产部署需求 | 轻量运行时、CLI/极简WebUI、低资源消耗，优先满足个人/小团队轻量自托管需求 | MoA混合代理架构、多模型路由、MCP工具标准化，优先满足AI研发团队前沿能力探索需求 |
| 目标用户 | 中大型企业团队、私有化部署运维团队、需要统一多入口AI助手的组织 | 个人开发者、小团队、低资源环境自托管用户 | AI研发团队、技术极客、需要自定义多代理架构的专业用户 |
| 技术架构 | 一体化全栈架构，内置完整的消息网关、代理编排引擎、权限管控体系、跨端客户端套件，重可用性与兼容性 | 微内核轻量架构，核心运行时仅数百KB，依赖少，可扩展性强，注重部署便捷性与资源占用 | 模型能力优先的模块化架构，核心围绕LLM调用、MoA编排、工具标准化设计，注重架构灵活性与前沿能力落地 |

---

## 6. 社区热度与成熟度
按活跃度与成熟度可分为三个层级：
1. **第一梯队（超高活跃度，成熟度最高）：OpenClaw**
   PR闭环率43.2%、Issue闭环率22%，核心功能已稳定，当前处于**高密度功能迭代+历史问题清理并行的质量巩固阶段**，迭代重点为补全企业级特性、对齐跨端体验、清理历史遗留问题，是当前生态中唯一具备大规模生产部署能力的标杆项目。
2. **第二梯队（中高活跃度，成熟度较高）：Hermes Agent**
   PR闭环率36%、Issue闭环率20%，当日所有P1级Bug全部完成闭环，当前处于**稳定性优先的质量巩固+前沿能力探索阶段**，核心运行时稳定性达标，迭代重点为补全企业集成适配、桌面端体验、MoA架构优化。
3. **第三梯队（中高活跃度，成熟度中等）：NanoBot**
   PR闭环率35.3%、Issue闭环率仅4.7%（大量安全与回归问题当日新开），当前处于**大版本升级后的快速迭代修复阶段**，0.2.x版本新功能上线后集中暴露安全与兼容性问题，迭代重点为修复核心漏洞、补齐默认安全基线、解决版本回归，向生产可用的稳定版演进。

---

## 7. 值得关注的趋势信号
从社区反馈中可提炼四大行业趋势，对AI智能体开发者具有明确参考价值：
1. **企业级生产部署已成为核心需求**：三大项目的高优先级需求中，企业级诉求占比超过60%，开源智能体已从个人玩具转向企业生产工具，开发者需优先补齐企业级特性、安全基线、运维能力，而非仅堆加AI功能。
2. **安全基线成为自托管智能体的核心准入门槛**：NanoBot单轮代码审计披露35项安全问题，三大项目的最高优先级修复项均涉及安全风险，用户对自托管智能体的默认安全配置、权限隔离、数据保护的要求已达到企业级软件标准，开发者需将安全左移到架构设计阶段。
3. **跨端体验一致性成为核心竞争力**：OpenClaw的跨平台桌面端需求为全生态最高热度（110条评论），Android预编译APK需求闭环后获得大量正面反馈，说明用户需要在不同设备、不同入口获得一致的智能体体验，跨端覆盖能力已成为项目差异化的核心因素。
4. **多代理架构的生产级稳定性是核心技术瓶颈**：OpenClaw与Hermes Agent均将多代理并发稳定性、资源隔离、状态一致性作为最高优先级修复项，当前多代理架构的落地瓶颈已从功能实现转向生产级稳定性，开发者需在架构设计阶段重点解决并发锁、状态隔离、错误重试等分布式系统问题。

---

## 同赛道项目详细报告

<details>
<summary><strong>NanoBot</strong> — <a href="https://github.com/HKUDS/nanobot">HKUDS/nanobot</a></summary>

# NanoBot 项目动态日报（2026-07-07）
项目地址：[HKUDS/nanobot](https://github.com/HKUDS/nanobot)

---

## 1. 今日速览
2026年7月7日NanoBot项目活跃度处于高位，过去24小时共产生43条Issue更新（41条新开/活跃、2条关闭）、34条PR更新（22条待合并、12条合并/关闭），无新版本发布。今日核心事件为第三方开发者提交的全量代码审计报告共披露35项安全、功能、性能与代码质量问题，同时集中出现多起0.2.x版本的功能回归与高危安全漏洞报告，维护者已同步推进多项高优先级修复PR，整体处于问题集中暴露与快速迭代修复的阶段。

---

## 2. 版本发布
今日无新版本正式发布，无GitHub Releases更新。

---

## 3. 项目进展
今日共完成12项PR的合并/关闭，覆盖核心安全修复、WebUI体验优化、CLI能力升级、代码质量治理四大方向，代码审计披露的问题已启动批量修复，核心能力的稳定性与安全性持续提升：
1. 【P0 安全修复】PR #4671（已合并）：修复SSRF DNS重绑定TOCTOU漏洞，对应Issue #4611，通过固定验证后的解析IP彻底解决了URL校验与实际请求之间的DNS篡改风险，覆盖web_fetch、MCP HTTP探针等所有出站请求场景，是核心安全基线的重要升级。
   链接：[HKUDS/nanobot PR #4671](https://github.com/HKUDS/nanobot/pull/4671)
2. 【P1 WebUI重构】PR #4766（已合并）：重构WebUI斜杠命令实现，将命令生命周期、参数规则等元数据统一由后端管控，移除前端硬编码逻辑，大幅提升了斜杠命令的可扩展性与一致性。
   链接：[HKUDS/nanobot PR #4766](https://github.com/HKUDS/nanobot/pull/4766)
3. 【P2 代码质量优化】PR #4824（已合并）：清理11项孤儿函数、8项测试专用函数等死代码，对应审计Issue #4806，降低代码冗余与维护成本。
   链接：[HKUDS/nanobot PR #4824](https://github.com/HKUDS/nanobot/pull/4824)
4. 【P2 CLI功能增强】PR #4614（已合并）：新增CLI交互模式下Alt+Enter多行输入能力，解决了此前CLI无法编辑长文本的痛点。
   链接：[HKUDS/nanobot PR #4614](https://github.com/HKUDS/nanobot/pull/4614)
5. 【P1 CLI体验修复】PR #4654（已合并）：修复交互模式下流请求失败时丢失响应内容的问题，保障用户在流式传输异常时仍能获取完整输出。
   链接：[HKUDS/nanobot PR #4654](https://github.com/HKUDS/nanobot/pull/4654)

---

## 4. 社区热点
按讨论热度与社区影响力排序如下：
1. 【最高讨论Issue】Issue #4013（已关闭）：LLM流式请求90秒以上中断Bug，共6条评论。用户反馈从0.1.5post2升级到0.2.0版本后出现该问题，导致长任务无法正常执行，需要反复手动触发AI继续。背后诉求为0.2.x版本需保障核心流式请求的稳定性，对齐旧版的生产可用性。
   链接：[HKUDS/nanobot Issue #4013](https://github.com/HKUDS/nanobot/issues/4013)
2. 【热门回归Issue】Issue #4823（新开）：WhatsApp群组白名单功能回归，共2条评论。用户反馈0.2.2版本后群组权限配置失效，消息会发送到账号所在的所有群组，严重影响生产环境使用。背后诉求为通道配置的向后兼容性，保障多租户场景下的消息隔离能力。
   链接：[HKUDS/nanobot Issue #4823](https://github.com/HKUDS/nanobot/issues/4823)
3. 【核心安全热点】系列WebUI未授权token签发漏洞（Issue #4825、#4826、#4827，新开）：由安全研究员YLChen-007集中提交，披露本地部署未配置密钥时，任意本地进程可通过`/webui/bootstrap`接口获取全权限API token。虽然暂未产生大量评论，但属于高危通用漏洞，引发社区对自托管默认安全配置的广泛关注，背后诉求为提升默认安全基线，避免无感知的权限泄露。
   链接：[#4825](https://github.com/HKUDS/nanobot/issues/4825)、[#4826](https://github.com/HKUDS/nanobot/issues/4826)、[#4827](https://github.com/HKUDS/nanobot/issues/4827)
4. 【代码质量热点】Issue #4815（新开）：全量代码审计总览，共披露35项覆盖安全、功能、性能、重构的问题，是近年来NanoBot项目最全面的第三方代码审计贡献，体现了社区对项目质量的高关注度与开源协作的深度。
   链接：[HKUDS/nanobot Issue #4815](https://github.com/HKUDS/nanobot/issues/4815)

---

## 5. Bug 与稳定性
按严重程度从高到低排列，标注修复状态：
### 高危（P0/P1，可导致权限泄露、数据丢失、服务不可用）
1. WebUI未授权API token签发（#4825、#4826、#4827）：本地部署未配置token时，任意本地进程可获取全权限API密钥，暂无公开修复PR。
2. API密钥明文存储（#4803）：所有提供商、通道的API密钥与token明文存储在`~/.nanobot/config.json`中，存在泄露风险，暂无公开修复PR。
   链接：[HKUDS/nanobot Issue #4803](https://github.com/HKUDS/nanobot/issues/4803)
3. 文件系统默认无工作区限制（#4796）：`restrict_to_workspace`配置默认值为False，Agent可读写执行整个文件系统的任意文件，暂无公开修复PR。
   链接：[HKUDS/nanobot Issue #4796](https://github.com/HKUDS/nanobot/issues/4796)
4. 符号链接TOCTOU漏洞（#4790）：文件系统工具存在校验与访问之间的时间窗口，并发场景下可绕过工作区限制，暂无公开修复PR。
   链接：[HKUDS/nanobot Issue #4790](https://github.com/HKUDS/nanobot/issues/4790)
5. ✅ 已修复：SSRF DNS重绑定TOCTOU漏洞（#4611）：已通过PR #4671合并修复。
   链接：[HKUDS/nanobot Issue #4611](https://github.com/HKUDS/nanobot/issues/4611)

### 中危（P1/P2，可导致功能失效、体验受损、资源耗尽）
1. WhatsApp群组白名单功能回归（#4823）：0.2.2版本后群组权限配置失效，消息群发，暂无修复PR。
2. 流式LLM请求无超时限制（#4795）：流式请求可无限运行，无墙钟超时保护，易导致资源耗尽，暂无修复PR。
   链接：[HKUDS/nanobot Issue #4795](https://github.com/HKUDS/nanobot/issues/4795)
3. 工具准备异常静默吞错（#4805）：Agent调用工具时的参数校验错误会被静默忽略，导致工具使用原始参数执行，已有修复PR #4811（待合并）。
   链接：[Issue](https://github.com/HKUDS/nanobot/issues/4805)、[PR](https://github.com/HKUDS/nanobot/pull/4811)
4. 并发文件写无锁导致损坏（#4798）：多会话同时写入同一文件时无锁保护，可能导致数据交错损坏，暂无修复PR。
   链接：[HKUDS/nanobot Issue #4798](https://github.com/HKUDS/nanobot/issues/4798)
5. Slack构建依赖缺失（#4829）：`pyproject.toml`中Slack通道依赖遗漏`aiohttp`，导致Slack插件无法启用，已有修复PR #4830（待合并）。
   链接：[Issue](https://github.com/HKUDS/nanobot/issues/4829)、[PR](https://github.com/HKUDS/nanobot/pull/4830)
6. 会话锁GC导致并发冲突（#4789）：会话锁使用`WeakValueDictionary`存储，GC回收后可能创建新锁导致并发操作冲突，已有修复PR #4819（待合并）。
   链接：[Issue](https://github.com/HKUDS/nanobot/issues/4789)、[PR](https://github.com/HKUDS/nanobot/pull/4819)

### 低危（P2，性能、代码质量问题，无直接业务影响）
1. LLM请求热路径无效内存分配（#4809）：OpenAI兼容层的`setdefault`逻辑导致每次请求创建并丢弃空字典，暂无修复PR。
   链接：[HKUDS/nanobot Issue #4809](https://github.com/HKUDS/nanobot/issues/4809)
2. JSON序列化替代深拷贝导致数据丢失（#4808）：三处代码使用`json.loads(json.dumps())`做深拷贝，性能差且可能丢失`datetime`等非JSON类型，暂无修复PR。
   链接：[HKUDS/nanobot Issue #4808](https://github.com/HKUDS/nanobot/issues/4808)
3. 多通道markdown转换代码重复（#4810）：Telegram、Signal、飞书三个通道存在重复的markdown转富文本逻辑，暂无修复PR。
   链接：[HKUDS/nanobot Issue #4810](https://github.com/HKUDS/nanobot/issues/4810)

---

## 6. 功能请求与路线图信号
结合今日提交的PR与用户需求，以下功能大概率纳入下一版本迭代：
1. 【WebUI体验增强】PR #4828（待合并）：新增WebUI文件编辑diff视图，支持以GitHub风格展示Agent对文件的修改内容，对齐代码类Agent的核心使用场景，与近期WebUI系列优化方向一致，落地概率高。
   链接：[HKUDS/nanobot PR #4828](https://github.com/HKUDS/nanobot/pull/4828)
2. 【WebUI能力扩展】PR #4771（待合并）：支持WebUI上传PDF等文档附件，除图片外新增多类型文档输入能力，已完成测试用例开发，落地概率高。
   链接：[HKUDS/nanobot PR #4771](https://github.com/HKUDS/nanobot/pull/4771)
3. 【核心工具增强】PR #4430（待合并）：新增可配置的`web_fetch`提供商，支持`auto`、`tavily`、`jina`、`readability`四种模式，替代原有的二进制开关，满足不同用户的网页抓取需求，已存在较长时间讨论，落地概率高。
   链接：[HKUDS/nanobot PR #4430](https://github.com/HKUDS/nanobot/pull/4430)
4. 【Agent能力分层】PR #4833（待合并）：将长目标功能封装为显式开启的runtime模式，仅在启用时加载对应工具与提示词，降低普通场景的prompt冗余，对齐Agent能力模块化的路线，落地概率高。
   链接：[HKUDS/nanobot PR #4833](https://github.com/HKUDS/nanobot/pull/4833)

此外，从今日集中暴露的0.2.x版本回归问题、安全漏洞来看，下一版本将重点强化核心功能稳定性、通道向后兼容性与默认安全基线，预计会推出0.2.x系列的补丁版本。

---

## 7. 用户反馈摘要
从今日Issues的用户提交内容提炼真实反馈：
1. 版本升级痛点：用户mxnbf连续提交两起0.2.x版本的核心功能回归问题（#4013、#4823），反馈从0.1.5稳定版升级后，流式中断、WhatsApp群组隔离失效的问题直接导致生产不可用，反映出0.2.x版本的灰度测试与兼容性验证覆盖不足，生产用户升级风险较高。
2. 多通道部署痛点：用户alekwo反馈Slack通道的依赖配置遗漏（#4829），说明非核心通道的构建测试覆盖不足，边缘场景的部署体验有待提升。
3. 安全诉求：两名安全研究员（hamb1y、YLChen-007）累计提交近20项安全漏洞，覆盖密钥存储、权限隔离、默认配置等多个维度，反映出自托管用户群体对NanoBot的生产级安全能力有较高要求，当前默认配置的安全基线尚未满足生产部署需求。
4. 正面反馈：用户mxnbf在#4013中明确提及0.1.5post2版本的WebUI体验优秀，认可旧版核心功能的稳定性与可用性，说明项目的核心价值已得到用户验证。

---

## 8. 待处理积压
以下为超过1个月未处理、存在冲突或高优先级的重要Issue/PR，提醒维护者关注：
1. PR #1290（冲突）：2026年2月27日创建，修复心跳机制的旧版兼容性问题，已存在4个多月，处于冲突状态未处理，影响旧版用户的平滑升级。
   链接：[HKUDS/nanobot PR #1290](https://github.com/HKUDS/nanobot/pull/1290)
2. PR #2060（冲突）：2026年3月15日创建，新增shell工具的路径白名单配置，解决`restrict_to_workspace`开启后无法访问`/dev/null`等系统路径的问题，已存在4个月，处于冲突状态未处理，影响安全配置下的工具可用性。
   链接：[HKUDS/nanobot PR #2060](https://github.com/HKUDS/nanobot/pull/2060)
3. PR #3232（冲突）：2026年4月17日创建，简化Agent任务回调逻辑并恢复意外删除的代码，已存在3个月，处于冲突状态未处理，影响Agent核心逻辑的可维护性。
   链接：[HKUDS/nanobot PR #3232](https://github.com/HKUDS/nanobot/pull/3232)
4. 流式稳定性遗留问题：Issue #4013虽已关闭，但用户反馈的0.2.x版本流式请求中断的根本原因尚未明确说明，需跟进验证修复效果，避免影响其他升级用户。
   链接：[HKUDS/nanobot Issue #4013](https://github.com/HKUDS/nanobot/issues/4013)

---
**数据统计周期**：2026-07-06 00:00 至 2026-07-07 23:59
**生成时间**：2026-07-07

</details>

<details>
<summary><strong>Hermes Agent</strong> — <a href="https://github.com/nousresearch/hermes-agent">nousresearch/hermes-agent</a></summary>

# Hermes Agent 项目动态日报（2026-07-07）
数据源：NousResearch/hermes-agent GitHub 仓库更新

---

## 1. 今日速览
2026年7月7日Hermes Agent项目活跃度处于高位，过去24小时共产生50条Issue更新（40条新开/活跃、10条已关闭）、50条PR更新（32条待合并、18条已合并/关闭），无新版本发布。今日维护重点聚焦高危会话状态Bug修复、多平台兼容性优化，所有P1级核心Bug全部完成闭环。同时社区围绕桌面端体验、多模型路由、第三方平台适配的需求讨论活跃，整体项目稳定性持续提升，社区参与度保持较高水平。

---

## 3. 项目进展（今日合并/关闭的重要PR）
今日共完成18条PR的合并/关闭，核心推进内容如下：
- 【P1 会话状态修复】PR #60108：显式在消息INSERT语句中设置`active=1`，并在启动时自动修复历史NULL值行，彻底解决网关平台会话历史全部丢失的高危问题（对应Issue #51646）。
  链接：https://github.com/NousResearch/hermes-agent/pull/60108
- 【P1 Cron调度修复】PR #60109：对Cron任务的绝对技能路径进行标准化处理，绕过安全检查拦截，解决Cron任务静默失败、通知无法送达的问题（对应Issue #59824）。
  链接：https://github.com/NousResearch/hermes-agent/pull/60109
- 【P1 安全风控修复】PR #60110：会话重放时自动过期 stale 的高危操作确认语，避免主机重启后残留的确认语被二次触发导致破坏性操作。
  链接：https://github.com/NousResearch/hermes-agent/pull/60110
- 【内存工具兼容性修复】PR #46356：修复`memory`工具`target`参数为null时无法写入默认存储的问题，对齐行业同类工具行为。
  链接：https://github.com/NousResearch/hermes-agent/pull/46356
- 【MCP 工具优化】PR #47506：将MCP工具默认调用超时从120秒提升至300秒，适配网页抓取、沙箱构建、深度调研等长耗时工具场景。
  链接：https://github.com/NousResearch/hermes-agent/pull/47506

---

## 4. 社区热点（评论/反应最多的内容）
今日社区讨论热度集中在企业集成、核心运行时优化、桌面端本地化三大方向，Top 热点内容如下：
- 【最高热度功能请求】Issue #5826：为网关新增Linear项目管理平台适配器，支持用户在Linear Issue评论中@Hermes完成Bug排查、Issue摘要、状态更新等操作，获得6条评论、8个点赞，是今日社区关注度最高的需求。
  链接：https://github.com/NousResearch/hermes-agent/issues/5826
- 【核心运行时需求】Issue #25061：在`run_conversation()`中新增会话前置内存健康钩子，解决LLM优先处理用户消息、忽略内存压缩等系统规则的问题，获得4条评论。
  链接：https://github.com/NousResearch/hermes-agent/issues/25061
- 【桌面端本地化需求】Issue #46337：在Hermes Desktop中新增本地STT/TTS、媒体生成提供商的配置UI，支持用户完全离线使用语音、多媒体功能，获得4条评论。
  链接：https://github.com/NousResearch/hermes-agent/issues/46337
- 【高危Bug讨论】Issue #51646：网关消息插入时遗漏`active`列导致所有会话历史丢失的P1级Bug，获得4条评论，已完成修复闭环。
  链接：https://github.com/NousResearch/hermes-agent/issues/51646

---

## 5. Bug与稳定性（按严重程度排序）
### P1 级（已全部修复闭环）
1. Issue #51646：网关消息INSERT遗漏`active`列，导致所有网关平台加载不到会话历史，已通过PR #60108修复。
   链接：https://github.com/NousResearch/hermes-agent/issues/51646
2. Issue #59824：Cron调度器因绝对技能路径被安全检查拦截，导致任务静默失败、通知无法送达，已通过PR #60109修复。
   链接：https://github.com/NousResearch/hermes-agent/issues/59824

### P2 级（部分已有修复PR）
1. Issue #60064/#60065/#60068（重复）：MoA架构下自定义提供商的凭证未传递给参考模型，导致请求返回401，对应修复PR #60082待合并。
   链接：https://github.com/NousResearch/hermes-agent/issues/60064
2. Issue #56739：Telegram平台下代理处于待澄清状态时，忽略用户发送的语音消息，仅支持文本回复，对应修复PR #50925待合并。
   链接：https://github.com/NousResearch/hermes-agent/issues/56739
3. Issue #32097：简单查询响应耗时超过3分钟，更换API密钥升级后出现，需进一步复现，暂无修复PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/32097
4. Issue #58688：桌面端模型选择器错误将自定义提供商的模型路由至OpenRouter，导致自定义模型无法使用，暂无修复PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/58688
5. Issue #60105：Dashboard仅配置密码认证时，未认证用户访问根路径返回500而非登录页，暂无修复PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/60105
6. Issue #57395：GitHub Copilot提供商下，MoA的非GPT参考模型（Claude、Gemini）调用返回400，暂无修复PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/57395
7. Issue #60046：主模型故障触发fallback切换时，无任何用户通知，用户无法感知当前使用的模型，暂无修复PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/60046
8. Issue #52945：Desktop设置的`HERMES_WEB_DIST`环境变量被Dashboard继承，导致Dashboard加载错误的前端资源，暂无修复PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/52945

### P3 级
1. Issue #59890：Kanban任务事件通知从未送达，18个订阅全部无推送，暂无修复PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/59890
2. Issue #33079：Telegram网关测试存在mock污染，导致测试结果依赖执行顺序，偶发失败，暂无修复PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/33079
3. Issue #60091：DeepSeek定价表缺失`deepseek-v4-flash`模型、以及所有模型的缓存读定价，导致成本估算错误，暂无修复PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/60091
4. Issue #60047：会话标题解析器未按来源隔离，导致跨来源同标题会话冲突，暂无修复PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/60047

---

## 6. 功能请求与路线图信号
结合社区需求热度与PR成熟度，以下功能大概率纳入下一版本迭代：
- 【高概率合并】PR #37167：为`hermes sessions browse`命令新增`--sort`参数，支持按创建时间、最后活跃时间排序，无破坏性变更，文档齐全。
  链接：https://github.com/NousResearch/hermes-agent/pull/37167
- 【高概率合并】PR #40630：桌面端Markdown文件预览支持Mermaid图表渲染，复用现有聊天界面的渲染组件，无破坏性变更。
  链接：https://github.com/NousResearch/hermes-agent/pull/40630
- 【高优先级路线图候选】Issue #5826：Linear平台网关适配器，企业用户需求明确，社区热度最高，暂无对应PR，预计纳入v0.19.0迭代。
  链接：https://github.com/NousResearch/hermes-agent/issues/5826
- 【核心运行时优化候选】Issue #25061：会话前置内存健康钩子，解决长会话内存溢出的核心痛点，暂无对应PR，优先级较高。
  链接：https://github.com/NousResearch/hermes-agent/issues/25061
- 【桌面端迭代候选】Issue #46337：本地STT/TTS/媒体生成提供商配置UI，是本地化部署的核心需求，暂无对应PR，预计纳入桌面端下一迭代。
  链接：https://github.com/NousResearch/hermes-agent/issues/46337

---

## 7. 用户反馈摘要
从今日Issue中提炼用户真实痛点与使用场景：
1. **企业协作场景**：使用Linear做项目管理的团队希望将Hermes深度集成到现有工作流，无需在多个工具间切换同步上下文，提升研发效率。
2. **桌面端体验痛点**：① 聊天界面默认字体过小，非Retina屏/小屏长时间阅读疲劳；② 长回复自动滚动导致用户无法从开头阅读内容；③ 无Intel macOS官方安装包，Intel设备用户无法使用桌面端；④ 自定义模型配置容易被错误路由到OpenRouter，影响本地部署体验。
3. **核心功能痛点**：① LLM经常忽略内存压缩等系统规则，长会话内存溢出风险高；② MoA架构无法正常使用私有部署的自定义模型；③ 模型切换无通知，用户无法感知当前调用的模型；④ Telegram下语音交互不完整，待回复状态无法识别语音消息。
4. **本地化部署痛点**：桌面端缺少本地语音、多媒体模型的配置入口，无法实现完全离线使用。

---

## 8. 待处理积压（长期未响应的重要内容）
以下Issue/PR创建时间超过2周，尚未得到维护者响应或review，建议优先处理：
1. Issue #25061：会话前置内存健康钩子，2026-05-13创建，属于核心运行时优化，已提出2个月，无维护者响应、无对应PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/25061
2. PR #37167：会话浏览排序功能，2026-06-02创建，功能完整、文档齐全，已提交1个多月，尚未完成review。
   链接：https://github.com/NousResearch/hermes-agent/pull/37167
3. Issue #33079：Telegram网关测试mock污染问题，2026-05-27创建，影响CI稳定性，已提出1个多月，无维护者响应、无对应PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/33079
4. PR #40630：桌面端Mermaid渲染功能，2026-06-06创建，无破坏性变更，已提交1个月，尚未完成review。
   链接：https://github.com/NousResearch/hermes-agent/pull/40630
5. Issue #49378：智能模型路由功能，2026-06-20创建，用户呼声较高的体验优化，已提出半个多月，无维护者响应、无对应PR。
   链接：https://github.com/NousResearch/hermes-agent/issues/49378

</details>

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*