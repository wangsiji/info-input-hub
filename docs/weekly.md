# 人物周报

_每周一 08:30 · 26 位 AI builders 深度观点 · 最近 1 期_

---


## 2026-09-26

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
