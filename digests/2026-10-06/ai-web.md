# AI 官方内容追踪报告 2026-10-06

> 今日更新 | 新增内容: 36 篇 | 生成时间: 2026-10-06 03:40 UTC

数据来源:
- Anthropic: [anthropic.com](https://www.anthropic.com) — 新增 12 篇（sitemap 共 455 条）
- OpenAI: [openai.com](https://openai.com) — 新增 24 篇（sitemap 共 1049 条）

---

# AI 官方内容追踪报告（2026-10-06 增量更新）
**数据来源**：Anthropic 官网（anthropic.com）、OpenAI 官网（openai.com）  
**更新范围**：2026-10-06 抓取的增量内容（Anthropic 12 篇、OpenAI 24 篇）

---

## 1. 今日速览
本次增量更新覆盖两家前沿 AI 厂商的核心战略动向：其一，Anthropic 发布全球首个**机器人工作暴露指数**研究，量化当前实体机器人对美国劳动力市场的替代范围、成本周期与社会分层影响，为 AI 自动化政策与企业战略提供关键实证依据；其二，Anthropic 投入 1 亿美元推出 **Claude Frontier Academy**，计划到 2027 年培养 1 万名前沿部署工程师，通过人才标准绑定头部咨询、金融、药企客户，将技术能力转化为行业规则；其三，OpenAI 于 10 月 5-6 日集中上线 24 条 Index 栏目内容，覆盖 GPT-6 系列多型号迭代、ChatGPT 广告扩张、安全治理、DevDay 2026 复盘等核心方向，但本次仅抓取到 URL 推断标题元数据，正文内容尚未获取。整体来看，Anthropic 近期聚焦“AI for Science 硬核突破+企业级深度生态+治理话语权”，OpenAI 则保持“模型快速迭代+全品类商业化+全球合规布局”的节奏，差异化竞争态势明确。

---

## 2. Anthropic / Claude 内容精选
### 分类一：Research（研究）
按发布时间倒序排列，每篇附核心提炼与原文链接。
#### （1）Can we predict the jobs robots will do?
- **发布日期**：2026-10-05
- **原文链接**：[https://www.anthropic.com/research/what-work-can-robots-do](https://www.anthropic.com/research/what-work-can-robots-do)
- 核心观点：研究提出**机器人暴露指数（Robot Exposure Index）**，基于当前自主实体机器人的实际能力量化其对美国劳动力市场的影响：当前机器人可完成 3/4 的体力类工作任务，对应 34% 的总工作时长，但仅能在高度受限场景下落地；暴露度最高的岗位为驾驶、仓储等低技能体力岗，受影响群体以男性、低学历、低收入劳动者为主，护理、通用维修等岗位因需要复杂物理技能或人际交互，暴露度极低。当前仅 0.3% 的工作任务具备机器人替代的成本竞争力，按历史价格下降趋势，该比例提升至 10% 需 40 年，且技术能力、用户偏好、监管政策构成额外落地壁垒。过去 50 年的就业数据显示，机器人暴露度更高的岗位工资与就业降幅显著高于其他岗位，且机器人可覆盖的体力工作占比以每年 2% 的速度增长。

#### （2）Claude-shaped science
- **发布日期**：2026-10-01
- **原文链接**：[https://www.anthropic.com/research/claude-shaped-science](https://www.anthropic.com/research/claude-shaped-science)
- 核心观点：哈佛大学物理学教授 Matthew Schwartz 提出**“Claude 形问题”**研究范式，即放弃用 AI 解决人类擅长的复杂核心问题，转而寻找适配当前 LLM 能力边界的科学问题，最大化 AI 价值。基于该思路开发的 BootLoops 工具包可实现定量科学的精确计算，Claude 通过该工具发现了生态学、种群遗传学等十余个跨学科领域的计算关联，再由领域专家锚定有科学价值的方向。该研究验证了当前 LLM 在科学领域的核心价值是跨领域知识连接、标准化计算执行与大规模假设生成，而非独立攻克基础难题。

#### （3）What do you want from AI?
- **发布日期**：2026-09-30
- **原文链接**：[https://www.anthropic.com/research/your-thoughts-on-ai](https://www.anthropic.com/research/your-thoughts-on-ai)
- 核心观点：Anthropic 启动新一轮公众意见调研，使用自研的 Anthropic Interviewer 工具收集全球用户对 AI 的真实体验、变革预期与对 AI 厂商的诉求，调研结果将全部公开供全行业与政策制定者参考。该调研是 2025 年 12 月 8.1 万人参与的同类研究的跟进，此前结果已影响 Anthropic Institute 议程并提交至世界经济论坛，延续了 Anthropic“公众参与 AI 治理”的长期路线，试图通过公众意见强化自身发展的合法性。

#### （4）GLM-5.3 and the spread of advanced cyber capabilities
- **发布日期**：2026-09-30
- **原文链接**：[https://www.anthropic.com/research/glm-5-3-and-the-spread-of-advanced-cyber-capabilities](https://www.anthropic.com/research/glm-5-3-and-the-spread-of-advanced-cyber-capabilities)
- 核心观点：Anthropic 红队研究发现，智谱 AI 发布的 GLM-5.3 具备自主构建端到端网络漏洞利用工具的前沿能力，但其安全防护可被 64%-100% 的简单绕过技术突破，而 Claude 的安全机制在相同测试中未被攻破。该研究呼应了 Anthropic 此前通过 Project Glasswing 向可信防御方有限开放 Mythos 模型网络能力的策略，强调前沿 AI 网络能力扩散的风险。这是西方头部 AI 厂商首次公开对中国大模型的安全能力做出负面评估，具有强烈的行业信号意义。

#### （5）Project Swap: What happens when agents trade for us?
- **发布日期**：2026-09-28
- **原文链接**：[https://www.anthropic.com/research/project-swap](https://www.anthropic.com/research/project-swap)
- 核心观点：Anthropic 开展实体书籍交易的 Agent 市场实验（为此前 Project Deal 的后续研究），验证 AI 代理代表人类参与市场交易的效果与边界。实验显示，仅通过 5 分钟对话训练的 Claude 代理对用户偏好的匹配度达 61%，模型能力对交易结果的影响大于指令设计，更强模型参与的市场效率更高；市场效率的主要瓶颈是 Agent 对用户深层需求的理解不足，而非交易策略本身。该研究为 Agent 在电商、供应链、人力资源等交易场景的落地提供了实证依据。

#### （6）Claude has improved on a longstanding lower bound for the fraction of zeros of the Riemann zeta function that satisfy the Riemann hypothesis
- **发布日期**：2026-09-26
- **原文链接**：[https://www.anthropic.com/research/riemann-zeta](https://www.anthropic.com/research/riemann-zeta)
- 核心观点：未发布的研究版 Claude 在尝试证明黎曼猜想的过程中，将黎曼ζ函数零点满足黎曼假设的比例下限从 41.6% 提升至 67.2%，且生成了可形式化验证的完整证明。该结果已由黎曼猜想领域两位权威数学家 Brian Conrey 和 Dan Goldston 验证，虽未直接推动黎曼猜想证明，但刷新了这一悬而未决 160 多年的数学难题的阶段性进展。这是 Anthropic 首次公开 Claude 在纯数学基础研究领域的突破性成果，大幅强化了其前沿科学能力的品牌认知。

#### （7）Claude computes a nine-loop amplitude in N=4 super-Yang-Mills
- **发布日期**：2026-09-25
- **原文链接**：[https://www.anthropic.com/research/yes-claude-can-do-nine-loops](https://www.anthropic.com/research/yes-claude-can-do-nine-loops)
- 核心观点：理论物理学家、知名科学博主 Matt von Hippel 提出的 N=4 超杨-米尔斯理论九圈振幅计算挑战，被 Claude 在 1 个月内攻克，验证了 LLM 在高能物理等高度专业化领域的复杂计算能力。该成果打破了部分业内观点对 LLM 物理研究能力的质疑，成为 AI 辅助前沿科学的又一标志性案例。研究采用“外部学者提挑战+AI 模型解题”的模式，为后续 AI 科学能力评估提供了可参考的范式。

---

### 分类二：News（新闻/公告）
按发布时间倒序排列，每篇附核心提炼与原文链接。
#### （1）Claude Frontier Academy: $100M to train 10,000 engineers
- **发布日期**：2026-10-02
- **原文链接**：[https://www.anthropic.com/news/claude-frontier-academy](https://www.anthropic.com/news/claude-frontier-academy)
- 业务意义：该学院是全球首个由前沿 AI 厂商推出的企业级 AI 部署人才认证体系，培训标准与 Anthropic 内部工程师完全对齐，首批学员全部来自埃森哲、贝恩、凯捷、德勤、麦肯锡、摩根士丹利、诺和诺德等全球头部咨询、金融、医药企业。Anthropic 试图通过人才输出，将 Claude 的技术标准转化为企业 AI 落地的行业标准，解决当前企业 AI 部署“缺高端人才”的核心痛点，同时深度绑定核心 B 端客户的供应链，强化生态护城河。1 亿美元的投入与 1 万名工程师的培养目标，体现了 Anthropic 全面押注企业级市场的战略决心。

#### （2）Barclays scales Claude to upgrade operations and improve client experience
- **发布日期**：2026-10-01
- **原文链接**：[https://www.anthropic.com/news/barclays-scales-claude](https://www.anthropic.com/news/barclays-scales-claude)
- 业务意义：英国巴克莱银行扩大与 Anthropic 的战略合作，将 Claude 全面应用于软件开发、遗留系统现代化、运营效率提升等场景，预计到 2026 年底 Claude Code 的开发者渗透率达 50%，2027 年覆盖多数软件工程师。该合作是全球金融行业首个大规模落地的前沿 AI 部署案例，强化了 Anthropic 在受监管行业的合规 AI 定位，也验证了 Claude Code 在企业级研发场景的商业化价值。

#### （3）Introducing the Life Sciences Verification Program
- **发布日期**：2026-09-30
- **原文链接**：[https://www.anthropic.com/news/life-sciences-verification-program](https://www.anthropic.com/news/life-sciences-verification-program)
- 业务意义：Anthropic 推出**生命科学验证计划（LSVP）**，为通过资质审核的生命科学团队开放 Mythos、Opus、Sonnet 模型的放宽权限，支持药物发现、研究生物学、临床开发、制造等原本被通用模型限制的场景。计划分“标准使用”和“高风险使用”两个层级，审核包括研究资质、安全标准、伦理监督三个维度，目前已有数十家机构通过早期接入。该计划是 Anthropic 垂直行业渗透的关键一步，通过差异化的合规权限设计切入高价值的生命科学赛道，同时规避通用模型的生物安全风险。

#### （4）Anthropic and Infosys build AI agents
- **发布日期**：2026-09-28
- **原文链接**：[https://www.anthropic.com/news/anthropic-infosys](https://www.anthropic.com/news/anthropic-infosys)
- 业务意义：Anthropic 与印度 IT 巨头印孚瑟斯（Infosys）达成合作，将 Claude 模型与 Claude Code 集成到 Infosys Topaz AI 平台，为电信、金融服务、制造等受监管行业开发 AI Agent。印度是 Claude.ai 的第二大市场，近半数用户使用 Claude 开发应用、现代化系统，印孚瑟斯是 Anthropic 拓展印度市场的核心合作伙伴。该合作填补了 Anthropic 在印度本土企业服务渠道的短板，进一步强化了其在新兴市场的开发者与企业客户覆盖。

#### （5）Claude discovers a novel enzyme system
- **发布日期**：2026-09-24
- **原文链接**：[https://www.anthropic.com/news/claude-discovers-novel-enzyme-system](https://www.anthropic.com/news/claude-discovers-novel-enzyme-system)
- 业务意义：Anthropic 成立内部生命科学研究团队与实验室，专注用 Claude 开展基础生物学研究，通过挖掘 DNA 数据集发现未知蛋白家族、生成规模化假设并自主实验验证。团队首次发现了一种具有类 CRISPR 重复序列的新型酶系统，仅需科学家提供高层级方向，核心发现由 Claude 完成。这是 Anthropic 从“AI 工具提供商”向“AI 驱动的科学研究机构”延伸的标志性信号，生命科学已成为其核心战略赛道之一。

---

## 3. OpenAI 内容精选
> ⚠️ **数据受限说明**：本次抓取的 OpenAI 内容仅提供 URL 路径推断标题、index 分类与发布时间元数据，无正文内容，无法进行内容提炼与分类判定。24 条内容中存在多组重复 URL（或为抓取重复），以下按去重后的独立条目客观列举，标题由 URL 路径推断，准确性不做保证：

### 2026-10-06 发布（共 4 条独立条目）
1. 标题（URL 推断）：Introducing Dots
   - 链接：[https://openai.com/index/introducing-dots/](https://openai.com/index/introducing-dots/)
   - 抓取次数：2 次
2. 标题（URL 推断）：Chatgpt Ads Expands Southeast Asia Taiwan
   - 链接：[https://openai.com/index/chatgpt-ads-expands-southeast-asia-taiwan/](https://openai.com/index/chatgpt-ads-expands-southeast-asia-taiwan/)
   - 抓取次数：1 次
3. 标题（URL 推断）：Towards Safety Cases For Frontier Ai Training
   - 链接：[https://openai.com/index/towards-safety-cases-for-frontier-ai-training/](https://openai.com/index/towards-safety-cases-for-frontier-ai-training/)
   - 抓取次数：1 次
4. 标题（URL 推断）：Introducing Gpt 6 1 Sol
   - 链接：[https://openai.com/index/introducing-gpt-6-1-sol/](https://openai.com/index/introducing-gpt-6-1-sol/)
   - 抓取次数：2 次

### 2026-10-05 发布（共 12 条独立条目）
1. 标题（URL 推断）：New Chatgpt Ads Format And Measurement
   - 链接：[https://openai.com/index/new-chatgpt-ads-format-and-measurement/](https://openai.com/index/new-chatgpt-ads-format-and-measurement/)
   - 抓取次数：1 次
2. 标题（URL 推断）：Practical Guide Building Gpt 6
   - 链接：[https://openai.com/index/practical-guide-building-gpt-6/](https://openai.com/index/practical-guide-building-gpt-6/)
   - 抓取次数：1 次
3. 标题（URL 推断）：Eu Text Provenance
   - 链接：[https://openai.com/index/eu-text-provenance/](https://openai.com/index/eu-text-provenance/)
   - 抓取次数：1 次
4. 标题（URL 推断）：Devday 2026 Recap
   - 链接：[https://openai.com/index/devday-2026-recap/](https://openai.com/index/devday-2026-recap/)
   - 抓取次数：2 次
5. 标题（URL 推断）：Airbnb Gpt 6 Astra
   - 链接：[https://openai.com/index/airbnb-gpt-6-astra/](https://openai.com/index/airbnb-gpt-6-astra/)
   - 抓取次数：1 次
6. 标题（URL 推断）：Introducing Mentalhealthbench
   - 链接：[https://openai.com/index/introducing-mentalhealthbench/](https://openai.com/index/introducing-mentalhealthbench/)
   - 抓取次数：1 次
7. 标题（URL 推断）：Two Years Of Openai Academy
   - 链接：[https://openai.com/index/two-years-of-openai-academy/](https://openai.com/index/two-years-of-openai-academy/)
   - 抓取次数：1 次
8. 标题（URL 推断）：Priorities Principles Third Party Assessments
   - 链接：[https://openai.com/index/priorities-principles-third-party-assessments/](https://openai.com/index/priorities-principles-third-party-assessments/)
   - 抓取次数：1 次
9. 标题（URL 推断）：Better Prompt Caching For Gpt 6
   - 链接：[https://openai.com/index/better-prompt-caching-for-gpt-6/](https://openai.com/index/better-prompt-caching-for-gpt-6/)
   - 抓取次数：1 次
10. 标题（URL 推断）：Albertsons Reimagining Retail
    - 链接：[https://openai.com/index/albertsons-reimagining-retail/](https://openai.com/index/albertsons-reimagining-retail/)
    - 抓取次数：1 次
11. 标题（URL 推断）：Lenfest Ai Collaborative Expansion
    - 链接：[https://openai.com/index/lenfest-ai-collaborative-expansion/](https://openai.com/index/lenfest-ai-collaborative-expansion/)
    - 抓取次数：1 次
12. 标题（URL 推断）：How We Will Do Better For Australia
    - 链接：[https://openai.com/index/how-we-will-do-better-for-australia/](https://openai.com/index/how-we-will-do-better-for-australia/)
    - 抓取次数：2 次
13. 标题（URL 推断）：Introducing Gpt 6 Sol And Luna
    - 链接：[https://openai.com/index/introducing-gpt-6-sol-and-luna/](https://openai.com/index/introducing-gpt-6-sol-and-luna/)
    - 抓取次数：3 次

### 2026-10-01 发布（共 1 条独立条目）
1. 标题（URL 推断）：Sam Altman Un Security Council Remarks
   - 链接：[https://openai.com/index/sam-altman-un-security-council-remarks/](https://openai.com/index/sam-altman-un-security-council-remarks/)
   - 抓取次数：1 次

---

## 4. 战略信号解读
### （1）各自近期的技术优先级
#### Anthropic：三层优先级清晰，主打“差异化突围”
- **硬能力层：AI for Science 为核心品牌抓手**：半个月内连续发布纯数学、理论物理、基础生物学三大领域的标志性突破，同时推出生命科学专属模型权限计划与内部实验室，将“Claude 是最适合做前沿科学研究的 AI”打造成核心差异化标签，跳出通用大模型的参数竞争内卷。
- **生态层：企业级深度绑定，从“卖模型”到“定标准”**：聚焦金融、生命科学、电信等受监管的高价值行业，一方面通过巴克莱、Infosys 等头部客户打造标杆案例，另一方面通过 Frontier Academy 定义“前沿部署工程师”的人才标准，将技术能力转化为行业规则，强化客户粘性。
- **前瞻层：布局下一代 AI 的社会与技术形态**：提前开展实体机器人劳动影响、Agent 市场行为等研究，既为长期产品落地做储备，也通过实证研究强化自身在 AI 治理领域的话语权，为监管应对与公众信任建设打基础。

#### OpenAI（基于 URL 关键词的客观观察，无正文支撑）：全栈推进，保持规模领先
- 模型迭代：GPT-6 系列进入密集迭代期，已出现 Sol、Luna、Astra、6.1 等多个型号后缀，模型矩阵从“单一能力分级”向“多场景专属型号”转型；同时推出 Prompt 缓存优化、构建指南等开发者工具，降低使用门槛。
- 商业化：ChatGPT 广告业务加速扩张，从美国本土向东南亚、中国台湾等亚太市场延伸，同时优化广告格式与测量体系，C 端广告成为核心收入增长点。
- 安全合规：同步推进技术安全框架（前沿训练安全案例、第三方评估原则）与区域合规落地（欧盟文本溯源、澳大利亚市场承诺），配合全球监管要求。
- 生态拓展：通过 DevDay 2026、OpenAI Academy、行业合作伙伴（Airbnb、Albertsons）覆盖更广泛的开发者与企业客户，强化通用 AI 生态的领先地位。

---

### （2）竞争态势：分赛道领跑，核心战场从“模型能力”转向“生态与标准”
- **AI for Science 赛道：Anthropic 引领，OpenAI 暂未释放同量级信号**。Anthropic 近期的连续突破已经从“AI 辅助科研”升级为“AI 做出独立科学发现”，且覆盖三大基础学科，配套垂直产品计划，在该赛道的品牌认知度已超过 OpenAI；OpenAI 本次增量内容中仅出现心理健康基准相关条目，未释放基础科学突破信号。
- **企业级市场：双轨并行，无直接正面冲突**。Anthropic 走“精英路线”，聚焦高价值受监管行业，客单价高、粘性强；OpenAI 走“大众路线”，覆盖通用消费行业，覆盖面广、客户数量多。两者均在各自优势赛道跑马圈地，尚未出现价格战或直接对标的产品动作。
- **安全与治理：Anthropic 重技术实证，OpenAI 重全球政策**。Anthropic 通过红队研究、社会调研、劳动市场分析等实证研究，争夺技术层面的安全话语权；OpenAI 则侧重全球政策布局，从联合国安理会发言到各区域合规落地，试图在全球 AI 治理规则制定中占据核心位置。
- **模型迭代：OpenAI 节奏更快，Anthropic 垂直突破更强**。OpenAI 已推进到 GPT-6.1 系列，型号矩阵更丰富，通用模型迭代速度领先；Anthropic 通用模型迭代相对低调，但在科学、网络安全等垂直领域的能力释放更有针对性。

---

### （3）对开发者和企业用户的潜在影响
#### 开发者侧
1. **职业赛道分化加速**：具备 Anthropic 前沿部署工程师（FDE）认证的开发者将在金融、生命科学等受监管行业获得更高议价能力；OpenAI 生态的开发者则在通用应用开发、广告运营等领域有更多就业机会，AI 开发者的赛道分化将日益明显。
2. **工具选择更清晰**：AI for Science 相关开发场景（数学计算、生物信息学、理论物理）可优先选择 Claude 的能力；通用应用、C 端产品、广告相关开发场景可优先选择 OpenAI 的生态工具。
3. **成本与效率优化空间扩大**：OpenAI 的 GPT-6 多型号矩阵+Prompt 缓存优化，将为开发者提供更灵活的成本选择，不同场景可匹配不同性价比的模型；Anthropic 的 Agent 研究成果也将为交易、谈判类场景的 Agent 开发提供实证参考。

#### 企业用户侧
1. **行业选型更明确**：受监管行业（金融、医疗、电信）企业，Anthropic 的合规体系、垂直解决方案、标杆案例更成熟，适合核心业务系统的深度 AI 改造；通用消费行业（零售、旅游、电商）企业，OpenAI 的广告工具、全行业解决方案、开发者生态更适合快速落地业务应用。
2. **人才缺口有望缓解**：Anthropic 的 Frontier Academy 将在未来 2 年释放 1 万名经过认证的 AI 部署人才，一定程度上缓解企业 AI 落地的高端人才短缺问题，但也可能推高相关人才的薪酬成本。
3. **自动化节奏更理性**：Anthropic 的机器人研究显示，实体机器人的大规模替代还需 40 年以上，企业无需过度焦虑实体机器人替代风险，可将更多精力放在软件 Agent、大模型的落地应用上，优先提升知识工作与流程自动化效率。

---

## 5. 值得关注的细节
### （1）新兴概念首次出现，或成行业新范式
- **“Frontier Deployed Engineers (FDEs)”**：Anthropic 首次提出的职业定义，标志着 AI 行业人才标准从“通用 AI 开发者”向“企业级深度部署工程师”细化，后续可能有更多厂商跟进类似认证，成为企业 AI 落地的核心人才标准。
- **“Claude-shaped science”**：首次提出的科研范式，重新定义了人与 AI 在科研中的分工：AI 负责跨领域连接、标准化计算、大规模假设生成，人类负责提出核心问题、判断科学价值。该范式若被科研界广泛接受，将极大提升 AI 在科学研究中的渗透率。
- **“Robot Exposure Index（机器人暴露指数）”**：首次推出的量化框架，为评估实体机器人对劳动市场的影响提供了统一测量标准，后续可能被政策制定者、研究机构广泛采用，成为 AI 社会影响研究的核心指标。

### （2）密集发布的节点信号
- Anthropic 在 9 月 24 日至 10 月 5 日的 12 天内，连续发布 5 篇生命科学相关内容，同时官宣成立内部生命科学实验室，说明生命科学已从探索性业务升级为核心战略赛道，后续大概率会有更多生命科学合作、产品、研究成果密集释放。
- OpenAI 在 10 月 5-6 日两天集中上线 24 条 Index 内容，且包含 DevDay 2026 复盘条目，基本可确认这些内容是 2026 年 OpenAI 开发者大会的配套发布，GPT-6 系列多型号、ChatGPT 广告、安全治理是本次 DevDay 的三大核心主题，后续相关产品落地节奏将明显加快。

### （3）安全与合规的地缘化动向
- Anthropic 公开发布对智谱 AI GLM-5.3 模型的安全评估报告，明确指出其安全防护存在严重漏洞，这是西方头部 AI 厂商首次公开对中国大模型的安全能力做出负面定性。该发布背后或有配合美国政府 AI 监管政策、强化自身安全品牌的战略考量，预示着前沿 AI 的安全竞争将越来越多地与地缘政治因素绑定。
- OpenAI 同时发布欧盟文本溯源、澳大利亚市场承诺、联合国安理会发言相关内容，说明其正在快速推进全球合规布局，欧盟、亚太（澳大利亚、东南亚、中国台湾）是其近期重点拓展区域，针对不同地区的监管要求推出差异化合规产品，将是 OpenAI 海外扩张的核心策略。

### （4）产品生态的隐含动向
- Anthropic 连续开展 Project Deal、Project Swap 两代 Agent 市场实验，验证了 AI 代理代表人类参与经济交易的可行性与效率，说明 Anthropic 正在为 Agent 经济落地做系统性研究储备，后续大概率会推出面向交易、谈判、供应链等场景的专属 Agent 产品。
- OpenAI 新增“Dots”产品条目（名称由 URL 推断），为首次出现的全新产品名，与 GPT-6 系列、广告业务等核心内容同期发布，或为本次 DevDay 的重要新品，具体定位有待后续正文内容公开后验证。
- OpenAI 的 GPT-6 系列出现 Sol、Luna、Astra 等多个非数字后缀的型号命名，打破了此前 GPT-3.5/GPT-4 的“代际+能力等级”命名逻辑，预示着其模型产品线正在从“统一代际”向“场景化矩阵”转型，不同型号将针对不同使用场景做专属优化。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*