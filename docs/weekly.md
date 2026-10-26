# 人物周报

_每周一 08:30 · 26 位 AI builders 深度观点 · 最近 6 期_

---


## 2026-10-26

## 👤 人物周报（本周）

**本周最值得追踪**
- **@ryolu_ (Ryo Lu)** — 他这周那篇长文是本周唯一值得花 5 分钟读完的东西：讲“和 AI 一起省掉困难，也就省掉了困难原本教会你的东西”。它直接关系到你正在做的“学习=信息→内化→决策”判断，也关系到思己实验室“会用 AI 的普通人”这个立场的反面对照。原文可以直接当选题素材。

**值得看**

- **@ryolu_ (Ryo Lu)**：编程和设计是“试错、撞墙、重来”练出来的；现在问一句机器就有结果，结果看起来完整，于是“你从没学会去问的问题”被悄悄跳过。他真正担心的是人少了和人一起挣扎的机会——“agent 永远有耐心，但友谊从哪开始？”（511 likes）https://x.com/ryolu_/status/2114187405251219954

- **@rauchg (Guillermo Rauch)**：AI 用得过度和用得不足都会出问题，前者它比你强，后者它偏航、丢上下文；“你多会管理这个超能力”是他招人时看的第 0 号技能。（2087 likes，本周最高质的判断）https://x.com/rauchg/status/2114085432749347086

- **@thsottiaux (Thibault Sottiaux)**：Codex 相关更新已全量下发，“明天尽情写代码”，并预告“有趣的一周”。纯信号，无观点，但当周热度最高（6524 likes 的 Day 20 打卡 + 1470 的 “By midnight PST”）。关注 OpenAI 编程线节奏的人该看。https://x.com/thsottiaux/status/2114237083652882932

- **@levie (Aaron Levie)**：安全领域即将涌入比今天多 1000 倍的 token——agent 集群能横向铺开、调用任意安全工具、试各种攻击变体、读日志判风险。这能力只在最近几个月才成立（长时运行 agent + computer use + 深度安全训练），意味着安全栈每一层（身份/防火墙/网络/代码扫描/数据保护）都是机会窗口。https://x.com/levie/status/2114187326406766604

- **@petergyang (Peter Yang)**：他和 4 岁孩子试过的学习 App 里，只有 @once_reading 坚持了几个月。三个机制值得抄：① 设计成必须每天陪孩子一起学（绑定他人，不是绑定自律）② 轻量游戏化（每节课后拍张傻照）③ 30 节课后寄实体书给孩子自己读，制造“我能行了”的成就感。这是习惯设计，不是内容设计。https://x.com/petergyang/status/2114042708105060501

- **@swyx**：Latent Space 在招 editorial 团队（作者/审稿/记者，找 @ricmac 和 @adlinzainal），并明确“欢迎兼职和一次性客座投稿”——对想积累英文 AI 写作声誉的人是低成本入口。https://x.com/swyx/status/2114145315196711194

**本周风向**
本周最有意思的对照是：一整排 builder 在同一周里自己往后退——Rauch 说核心技能是“知道什么时候别管 AI”，Ryo Lu 和 Aditya Agarwal 分别写“struggle together”和“celebrate humans、让 agent 自己煮”，连 Levie 讲安全自动化时落点也是“人的判断跟不上量”。而产品侧的动作依旧是全量铺量（Codex 更新、agent 托管）。**能力在快速商品化，稀缺性正从“会用工具”迁移到“知道该让人和 AI 各自做什么”。**


<details><summary>📅 2026-10-19</summary>




## 👤 人物周报（本周）

**本周最值得追踪**
- @levie — 他这篇「软件工程师没被消灭，而是所有东西都变成软件」是本周最完整的一次反共识论证：agent 能写代码/用工具后，可被数字化的边界被推到银行交易、生命科学、制造业供应链——直接对应你在做的「AI 能力→个人生产力重构」判断框架。@thsottiaux 的「工作 dot 和私人 dot 通过邮件协作、20 分钟报完税」是同一趋势的实操证据。

**值得看**
- @levie：预测软件工程终结的人搞错了前提——世界不是只需要固定量的软件。恰恰相反，几乎所有事都在变成软件，agent 让原本无法数字化的领域（交易、实验室、供应链）都能被工程化，所以工程师的经济重要性反而上升。不是不手写代码了，而是「几乎一切都会是代码」。（https://x.com/levie/status/2111525362446520466）
- @thsottiaux：两个 AI dot（工作端/个人端）自己用邮件互相协调，去拿文件、再和 CPA 对接完成报税，全程 20 分钟。「我们还处在极早期」——高互动（6.2k+4.3k likes），是 agent 跨账号自主协作最具体的一次演示。（https://x.com/thsottiaux/status/2111495392559067199）
- @swyx：AI Engineer 的冷启动真相——两年几乎零推荐，之后靠浏览推荐缓慢起来；月独立观众稳定 >100 万（5 月 AIE EU 后），但 58% 是新观众、68% 未订阅；观看集中在 7-11am PT，5pm 后无人看。给内容创作者的两个硬数据：CTR 差是常态、增长靠平台推荐不靠存量粉丝。（https://x.com/swyx/status/2111350966419411070）
- @petergyang：Claude Code app 提速明显、体验已可对标 ChatGPT，仍缺浏览器/电脑操作、全线程远程控制、实时语音；另附一条实用 prompt：让 AI 审计 Google 账号下 45 个已授权应用并逐项确认再断开。（https://x.com/petergyang/status/2111496600522805624）
- @amasad：澄清 Replit 仍保持模型中立（用户可选 Anthropic 等），只是在 TC Disrupt 上说 OpenAI 成为 agent 默认体验的优先合作方——按性能、成本、合作关系择优。（https://x.com/amasad/status/2111494912562888939）
- @thenanyu：团队 offsite 的共同回忆——「AI 之前我们在关注什么？」「前端 JS 框架」。一句话点出注意力迁移的荒谬感。（https://x.com/thenanyu/status/2111597172840083574）

**本周风向**
注意力正从「模型能力」转向「agent 自己跑完长流程」（报税、账号审计、跨端协作），而内容侧的冷启动现实是：推荐算法给量、存量粉丝不给量，CTR 差是常态而非失败信号。

</details>


<details><summary>📅 2026-10-12</summary>




## 👤 人物周报（本周）

**本周最值得追踪**
- **@levie（Aaron Levie）** — 两条连发把「agent swarm + 企业零信任」讲成一条完整推演：token 消耗的去处、1:1 到 1:1000X 算力、以及为什么 AI 需要自己的 zero-trust 时代。对任何在想「AI 落地到底卡在哪」的人，这是本周密度最高的一组判断。

**值得看**
- **@levie**：Agent 集群会吃掉绝大部分 token——软件、网络安全、生命科学、金融。人类并行的瓶颈是沟通与共享上下文，模型没这个瓶颈，所以不是更快，而是"质变的结果"，也因此需要 1000 倍算力。另一条补充：当 agent 执行的活远超人类，安全/治理/审计/责任归属会变成企业第一优先级，"把前沿模型当内部威胁来管"是合理架构。（[1](https://x.com/levie/status/2109079686286565378) / [2](https://x.com/levie/status/2108952226714865966)）
- **@realmadhuguru（Madhu Guru）**：agent 领域演化路径 = 能力 → 信任 → 自主。能力（模型+harness+工具+上下文能否可靠交付）已经走得够远，瓶颈转移到"权限是否正确、能否观测审计、责任归谁"。而 agent 能力将以 RSI 速度进化，安全侧必须跑得更快。（[链接](https://x.com/realmadhuguru/status/2108982858513776899)）
- **@thenanyu（Nan Yu）**：agent 让工程师极度放大，但 PM 仍卡在"必须跟客户沟通"的带宽上——所以理想配比是 1:1。这是本周最具体的一条组织设计判断，比"AI 提效"的口号有用得多。（[链接](https://x.com/thenanyu/status/2108976262698115550)）
- **@garrytan（Garry Tan）**：他实际在用的多 agent 工作流——一个线程同时协调 merge PR 队列、跑 CI，只允许全绿的完整 CI 进 master；/autoplan + 让 agent 把计划 ELI5 一遍，人只审计划不审代码，极少需要介入。对想搭自己 agent 流水线的人是可直接抄的操作细节。（[链接](https://x.com/garrytan/status/2108954741065879945)）
- **@nikunj（Nikunj Kothari）**：VC 契约与信任——"要基金在低谷时加倍下注，又要他们别行使 pro rata"，哲学上不能两头都要；每轮都该重新赢得上 cap table 的资格。给创始人的提醒：选合伙人之前先选合同，找个独立律师把条款讲清楚。（[链接](https://x.com/nikunj/status/2109038632975876395)）
- **@danshipper（Dan Shipper）**：公司 Slack 现在不是持续的惊奇与灵感来源，就说明哪里出问题了——这是对"AI 是否真进了日常"最省事的体感检测指标。（[链接](https://x.com/danshipper/status/2108941466785439796)）

**本周风向**
话题从"模型能做什么"整体迁移到"怎么管住它"：信任、权限、审计、组织配比、算力预算——能力叙事退位，治理与结构叙事上位。

</details>


<details><summary>📅 2026-10-05</summary>




## 👤 人物周报（本周）

**本周最值得追踪**
- @ryolu_ — 一篇《convergence to the mean》长文，直击 AI 时代原创力萎缩的核心：人人抄爆款→作品趋同→人也趋同。对做内容/产品的你值得一读，等于给"随大流造 content"敲了警钟。

**值得看**
- @thsottiaux（合并 3 条）：本周态度明确——OpenAI 只做三件事：简化、提效、显著新功能/新模型，社区反馈"想要更简单"他收到了。另一条身体力行：让 agent 帮他清邮箱到"inbox zero"（批量删分类、打标签、找补邮件的上下文），把邮件当第一手用户反馈处理。
- @sama：公开对"把 AI 神化/交出自己的判断力"表示不安，称之为真实的安全问题（24.9k 赞，本周最高热度）。Sam Altman 自己喊"别把 AI 当神"，这个信号值得留意。
- @levie：AI agent 采用仍是"双峰"——编程起飞，其余知识工作才刚开始，因为工作流要重造、数据要重连、问责/合规/安全全得改。结论：现在所见仅是 100 倍铺开前的零头。
- @adityaag：世界顶级癌症医生再有钱也只给你 20-30 分钟；AI 同时做到"普及接入 + 个体时间无限"。这就是"太便宜没法计量"的智能带来的实际效应。
- @rauchg：AI 将让一切免费（包括自己），最后一个倒下的多米诺是免费能源。另一条：安全会成为软件公司的更大职能，它本质是"验证工程"——"我的代码大概率内存安全"。

**本周风向**
两股力量在对抗：一边是天花板们（Altman、OpenAI）明说"要更简单、别神话"，一边是投资人与创始人（Levie、Rauchg）持续唱多"现在还早，agent 会 100 倍铺开"。落到操作上：企业用 AI 真需求是"验证 + 打分"而非" 造更多信号"，个人用 AI 的真正价值是"省下重复时间"，而不是 "预测+1"。

</details>


<details><summary>📅 2026-09-28</summary>




## 👤 人物周报（本周）

**本周最值得追踪**
- @rauchg — 发了一条本周最锋利的观点帖（"抵制不理解 / slop 手雷"，谈 AI 产出的低质文字正在让"阅读"本身贬值），直接戳中内容创作与 AI 协作的痛点，值得点进去读全。

**值得看**
- @rauchg：抵制"非理解"——slop 手雷不只是烂代码和烂 PR，而是 AI 垃圾文字被反复倾倒后，会让"阅读"这件事整体贬值。他想要的 AI 是服务理解、增强人类认知与创造力，而非替代。这条值得反复读。(https://x.com/rauchg/status/2103939888513274147)
- @trq212：一年前第一次用 Claude Code 做视频时，每条都要反复迭代、手动指出细节错误；回头看一年变化之快令人咋舌。真实的时间线对比，比任何宣称都直观（https://x.com/trq212/status/2103897226154328502）
- @steipete：看到某个演示后发出"现在懂为什么有人谈 AGI 了"——来自资深 dev 的一句克制惊叹，通常意味着那东西真的有点东西（https://x.com/steipete/status/2103883264054505493)
- @petergyang（合并 3 条）：集体制手见 AI 教学应用——用 Gemini 音频 API 做日语口语学习 App、以及首次用 antigravity 尝鲜 Google 新音频 API。音频交互是本周明显的产品方向（https://x.com/petergyang/status/2104059554204188833）
- @steipete（合并）：根治 bug 的方式改成了交给 AI agent 直接上生产环境问题，配合 GPT-6 推理——修 bug 的范式在变（https://x.com/petergyang/status/2103989902476259702）

**本周风向**
音频交互 App（Gemini/Claude 语音）在 builder 圈明显起势，同时警惕 AI slop 污染"阅读"的共识开始成为话题——真正值得跟的是后者，它决定内容创作的下限。

</details>


<details><summary>📅 2026-09-26</summary>




## 👤 人物周报（本周）

**值得看**
- @sama：OpenAI 正在审查自家 agent 在训练/评测期间的联网行为，公开摘要并优先处理严重事件——agent 触碰的真实伦理/合规边界正式开始被摆上台面（https://x.com/sama/status/2103567198690349362）
- @rauchg：代理时代 SaaS 的采购门槛从"人类操作易用性"变成"agent 集成易用性"（CLI/MCP/API），大量 SaaS 不再被购买而是被生成（https://x.com/rauchg/status/2103564484602384855）
- @levie：企业采用 AI 的卡点是 evals——"无法测量就无法自动化"，非确定性流程的评估体系是所有 agent 部署的前置条件（@A，https://x.com/levie/status/2103629073595728372）
- @steipete：把 OC 迁移到 sqlite 时最大的设计错误是用同步 DB 访问——单 agent 报告没问题，但当 1 个 agent 并行开 50 个 session、全团队共用时就成了瓶颈；已用 Astra 落地 575 个 PR 转向异步 worker（@steipete，https://x.com/steipete/status/2103648679169257737）
- @trq212：探讨"effort 到底是什么、为什么不全用 max"——低 effort 适合保持参与感，max 只在零输入或找安全漏洞时用（@trq212，https://x.com/trq212/status/2103576349499855160）
- @bcherny：Anthropic 的 @Claude 已接管他 50%+ 的 PR、~100% 数据分析，能用自然语言编程化地主动干活（@bcherny，https://x.com/bcherny/status/2103582892994551552）

**本周风向**
本周信号集中在"代理规模化场景的真实摩擦"——从 @sama 的 agent 联网伦理审查、@rauchg 的 agent 集成即采购标准、到 @steipete 的并发 DB 瓶颈，行业正从"造 agent"转向"管 agent"；而为 Cursor 力推 effort 分级、为 Claude 做内部编程的 @bcherny 则在定义"agent 时代的实际操作准则"。

</details>
