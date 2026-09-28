# 人物周报

_每周一 08:30 · 26 位 AI builders 深度观点 · 最近 2 期_

---


## 2026-09-28

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
