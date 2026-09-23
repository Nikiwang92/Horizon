---
layout: default
title: "Horizon Summary: 2026-09-23 (ZH)"
date: 2026-09-23
lang: zh
---

> 从 48 条内容中筛选出 18 条重要资讯。

---

**科技新闻**
1. [OpenAI 公告 GPT-6 Sol 与 Luna，条目缺少正文细节](#item-tech-news-1) ⭐️ 9.0/10
2. [Anthropic 发布 Claude Opus 5.5，token 价格下调](#item-tech-news-2) ⭐️ 9.0/10
3. [WordPress 未认证路径遍历可致条件性 RCE，修复已回移植](#item-tech-news-3) ⭐️ 9.0/10
4. [Claude Opus 5.5 与 GPT-6 Sol/Luna 同日发布并降价](#item-tech-news-4) ⭐️ 9.0/10
5. [vLLM v0.30.0 发布：持久权重缓存与多模型支持](#item-tech-news-5) ⭐️ 8.0/10
6. [Claude Opus 5.5 max 推理档评测：成本减半与 128K 预算耗尽](#item-tech-news-6) ⭐️ 8.0/10
7. [五角大楼称过度依赖 AI 致伊朗学校遭袭](#item-tech-news-7) ⭐️ 8.0/10
8. [Cloudflare Python Workers 正式全面可用](#item-tech-news-8) ⭐️ 8.0/10
9. [黑客声称掌握全部 FBI 员工数据，尚未获证实](#item-tech-news-9) ⭐️ 7.0/10
10. [Trail of Bits 博文批评 SAML 设计缺陷](#item-tech-news-10) ⭐️ 7.0/10
11. [Complex KDA：扩展 Kimi Delta Attention 的表达力](#item-tech-news-11) ⭐️ 7.0/10
12. [Qonto 发布 QontoFAQ 检索基准与相关性新指标](#item-tech-news-12) ⭐️ 7.0/10
13. [阿里发布真武 V900，宣称国产 AI 芯片算力达 M890 三倍](#item-tech-news-13) ⭐️ 7.0/10
14. [DeepSeek 与清华发布 DSec 沙箱平台报告：日服务 300 万沙箱](#item-tech-news-14) ⭐️ 7.0/10
15. [DeepSeek 本周将向联合国安理会通报 AI 风险](#item-tech-news-15) ⭐️ 7.0/10
16. [中国监管机构调查 DeepSeek 与月之暗面涉数据转发指控](#item-tech-news-16) ⭐️ 7.0/10
17. [OpenAI 拟让外部机构更早评估模型安全](#item-tech-news-17) ⭐️ 7.0/10
18. [高通发布骁龙 8 Elite Extreme Gen 6 移动平台](#item-tech-news-18) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [OpenAI 公告 GPT-6 Sol 与 Luna，条目缺少正文细节](https://openai.com/index/introducing-gpt-6-sol-and-luna/) ⭐️ 9.0/10

OpenAI 官方站点的条目显示，公司发布了名为 GPT-6 Sol 与 Luna 的新模型公告。但所提供的条目没有任何正文内容，因此这两款模型的具体能力、参数规模、定价、上线时间和兼容性均无法从现有材料核实。Hacker News 上相关讨论热度很高，但评论中的价格、性能与使用体验说法均来自用户个人，不能视为官方确认的信息。

hackernews · OfficialTurkey · 9月22日 18:00 · [社区讨论](https://news.ycombinator.com/item?id=49805509)

**「背景」** GPT-6 Sol 与 GPT-6 Luna 是 OpenAI 此前 GPT-5.6 系列中同名型号的直接后继者。据媒体报道，GPT-6 Sol 的 API 定价为每百万输入 token 2 美元、每百万输出 token 10 美元，而 GPT-5.6 Sol 为 4 美元和 20 美元；GPT-6 Luna 则从每百万输入 0.20 美元、输出 1.20 美元降至 0.10 美元和 0.50 美元。

**「对 API 用户的实际影响」** 对使用 API 的开发者而言，直接后果是 agent 类工作负载的单任务成本明显下降：OpenAI 报告 GPT-6 Luna 在 AutomationBench 上比 GPT-5.6 Luna 高 5.4 个百分点，同时每任务成本低 58%，VentureBeat 也称本次 API 价格下调幅度在 50% 以上。需要注意，上述数字均来自 OpenAI 自报的对比测试，实际账单仍取决于具体用量、努力档位与所选模型。

**「社区讨论」** 评论者 Simon Willison 认为 GPT-6 Luna 定价为 GPT-5.6 Luna 的一半“是件大事”，并贴出多个模型生成“鹈鹕”图像的对比链接；m\_fayer 则表示 GPT-5.6 Sol 是自己用起来最顺手的模型，担心技术更强的后继模型未必同样自然。另有用户 jeffnash 围绕 Claude Code 20x 与 Codex Pro 20x 的用量限制进行比较，称目前更倾向 Codex，这些都属于个人使用体验而非一致结论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://newscord.org/article/openai-launches-gpt-6-sol-and-gpt-6-luna-with-half-price-api-costs--Story_20260922_OpenAIlaunchesGPT6Soc784929c">OpenAI Launches GPT-6 Sol And GPT-6 Luna With Half-Price API Costs: 11 outlets compared | NewsCord</a></li>
<li><a href="https://pulse2.com/openai-launches-gpt-6-sol-and-luna/">OpenAI Launches GPT-6 Sol And Luna With 50% Lower API Pricing</a></li>
<li><a href="https://venturebeat.com/technology/openai-releases-gpt-6-sol-and-luna-models-slashing-api-costs-50-or-more">OpenAI releases GPT-6 Sol and Luna models, slashing API costs 50% or more | VentureBeat</a></li>
<li><a href="https://kingy.ai/blog/gpt-6-sol-luna-specs-benchmarks-pricing-comparison/">GPT-6 Sol and GPT-6 Luna: Specs, Benchmarks, Pricing and How They Compare to Claude Opus 5.5, Fable 5.1 and Gemini - Kingy AI</a></li>
<li><a href="https://www.zdnet.com/innovation/openai-gpt-6-sol-luna-release/">OpenAI&#x27;s GPT-6 Sol doubles its accuracy rate - for half the cost - ZDNET</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#GPT-6`, `#large language models`, `#AI agents`, `#model pricing`

---

<a id="item-tech-news-2"></a>
### [Anthropic 发布 Claude Opus 5.5，token 价格下调](https://www.anthropic.com/claude-opus-5-5) ⭐️ 9.0/10

Anthropic 发布了 Claude Opus 5.5，这是其前沿模型的新版本，官方称相较 Opus 5 有进一步的能力提升，并下调了按 token 计费的价格。社区评论转述的定价表显示，每百万 token 的输入从 5 美元降至 4 美元、输出从 25 美元降至 20 美元、缓存读取从 0.50 美元降至 0.20 美元、缓存写入从 6.25 美元降至 5 美元。发布文案称这是自其呼吁“为前沿发展定速”以来的首个发布，并称 Opus 5.5 在沟通表达上比前代更自然，更适合长时间协作。上述能力与定价信息均来自发布方描述及评论转述，本条没有可用的独立评测或实测数据。

hackernews · km144 · 9月22日 16:29 · [社区讨论](https://news.ycombinator.com/item?id=49803892)

**「背景」** Claude Opus 5 是 Anthropic 的上一代前沿模型，每百万输入 token 定价 5 美元、每百万输出 token 定价 25 美元，缓存读取为每百万 0.50 美元。在编码和 agent 类长时任务中，缓存读取占成本的大头，因此这一定价结构直接决定了此类工作负载的使用成本。

**「对开发者与选型的影响」** 对已经调用 Opus 5 的开发者，按 token 计费下降（社区评论列出的每百万 token 输入 $5→$4、输出 $25→$20、缓存读取 $0.50→$0.20）会直接缩小长上下文、代理式工作流的账单，切换模型即可生效；外部报道也把这次发布概括为成本约降低 40%。但价格优势并不稳定：有媒体报道称 OpenAI 的 GPT-6 Sol 在输入和输出价格上比 Claude Opus 5.5 低约 50%，因此团队在选型或做预算时应重新跨模型比价，而不是假定 Anthropic 的优势会持续。

**「社区讨论」** 评论者普遍关注降价的影响面，有人指出 Opus 5 是 OpenRouter 上支出最高的模型，因此这次降价牵涉的用量很大；也有人批评发布文案一面呼吁为前沿发展定速，一面用具体数字展示自己并未减速。在能力方面，有用户用同一段提示把动画转成 3D 动画，称 Opus 5.5 相比 Opus 5 改进显著，另有用户表示自己更愿意继续使用 DeepSeek v4.1。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/opus">Claude Opus \ Anthropic</a></li>
<li><a href="https://qz.com/anthropic-claude-opus-55-cost-performance-092226">Anthropic launches Claude Opus 5.5 at lower cost, higher performance</a></li>
<li><a href="https://wccftech.com/openai-unleashes-a-new-price-war-with-gpt-6-sol-and-gpt-6-luna-now-priced-below-claude-opus-5-5-and-deepseeks-v4-1-flash-respectively-negating-the-rationale-for-open-weight-models/">OpenAI Unleashes A New Price War, With GPT-6 Sol And GPT-6 Luna Now Priced Below Claude Opus 5.5 And DeepSeek&#x27;s V4.1 Flash, Respectively, Negating The Rationale For Open-Weight Models</a></li>
<li><a href="https://coingape.com/anthropic-launches-claude-opus-5-5-with-40-lower-costs-ahead-of-2t-ipo/">Anthropic Launches Claude Opus 5.5 With 40% Lower Costs Ahead of $2T IPO</a></li>

</ul>
</details>

**标签**: `#AI models`, `#Anthropic Claude`, `#LLM pricing`, `#frontier AI`, `#Hacker News`

---

<a id="item-tech-news-3"></a>
### [WordPress 未认证路径遍历可致条件性 RCE，修复已回移植](https://github.com/WordPress/wordpress-develop/security/advisories/GHSA-7hp8-65ch-5whp) ⭐️ 9.0/10

WordPress 官方安全公告披露一个未认证路径遍历漏洞，在特定条件下可导致远程代码执行（RCE），影响相应版本分支上的站点。公告称修复已发布，并回移植到 4.7 以来的所有分支；社区评论引用的发布说明称 7.1.2 已包含该修复。由于目前未提供更多触发条件细节，“条件性 RCE”的具体前提仍应以官方公告和补丁为准。

hackernews · vntok · 9月22日 16:33 · [社区讨论](https://news.ycombinator.com/item?id=49803959)

**「背景」** 该问题被编号为 CVE-2026-87902，属于 WordPress 页面模板解析（page-template resolution）环节的未认证目录遍历漏洞，由 Robert Ressl 发现并负责任地披露；GitHub 上已出现针对该 CVE 的概念验证仓库（tool-1-2）。WordPress 7.1.2 已包含修复，并出于对旧分支用户的照顾，把补丁回溯移植到 4.7 以来的所有分支（tool-1-1）。

**「影响与处置」** 未认证攻击者可借由 get\_page\_template\(\) 的页面模板解析流程，把活动主题目录之外的可读本地 .php 文件纳入包含范围；只有在服务器环境与当前启用主题同时满足特定前置条件时，才会进一步造成远程代码执行（tool-3-1）。对站点管理者而言，可行的处置是升级到 7.1.2 或对应的回溯修复分支；监测显示补丁发布数小时后已出现针对 WordPress 站点的探测流量，但若请求缺少能解析到真实页面的页面 id，查询即返回 404，模板解析流程不会被触达，漏洞代码也就不会执行（tool-3-3）。截至该报道时点，尚无已确认的在野利用或公开的概念验证代码（tool-3-2）。

**「社区讨论」** HN 讨论中，有评论者引用发布说明指出 WordPress 7.1.2 已修复该漏洞并回移植到 4.7 以来的所有分支，同时提醒约三分之一安装量仍不在 7.x 分支；另有评论者贴出补丁提交，并引用九年前的文档留言称 locate\_template\(\) 本就不防目录遍历。也有人表示因此把网站迁移到 Hugo 等静态托管方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/WordPress/wordpress-develop/security/advisories/GHSA-7hp8-65ch-5whp">Unauthenticated path traversal in page-template resolution leading to...</a></li>
<li><a href="https://github.com/ressl/cve-2026-87902-poc">GitHub - ressl/ cve -2026-87902-poc: PoC for CVE -2026-87902...</a></li>
<li><a href="https://github.com/WordPress/wordpress-develop/security/advisories/GHSA-7hp8-65ch-5whp">Unauthenticated path traversal in page-template resolution leading to conditional RCE · Advisory · WordPress/wordpress-develop · GitHub</a></li>
<li><a href="https://securityonline.info/wordpress-rce-vulnerability-cve-2026-87902/">CVE-2026-87902: Critical WordPress RCE Flaw Fixed in Version 7.1.2</a></li>
<li><a href="https://patchstack.com/articles/cve-2026-87902-attackers-started-probing-wordpress-sites-hours-after-the-patch/">CVE-2026-87902: Attackers Started Probing WordPress Sites Hours After the Patch - Patchstack</a></li>

</ul>
</details>

**标签**: `#WordPress`, `#security vulnerability`, `#path traversal`, `#remote code execution`, `#open source`

---

<a id="item-tech-news-4"></a>
### [Claude Opus 5.5 与 GPT-6 Sol/Luna 同日发布并降价](https://simonwillison.net/2026/Sep/22/opus-and-sol-and-luna/) ⭐️ 9.0/10

Anthropic 发布 Claude Opus 5.5，约一小时后 OpenAI 发布 GPT-6 Sol 和 GPT-6 Luna，两家在同一天同时下调了主力模型价格。GPT-6 Luna 定价为每百万输入 token 0.10 美元、输出 0.50 美元，正好是 GPT-5.6 Luna（0.20/1.20 美元）的一半；GPT-6 Sol 也从 4/20 美元降至 2/10 美元。Claude Opus 5.5 则从此前 Opus 4.5 至 5 一直沿用的 5/25 美元下调 20% 至 4/20 美元，缓存读取价格下降 60%，但 Simon Willison 目前只给出初步使用印象，尚无基准评测数据。他同时提醒，GPT-5.6 计划在 11 月涨价 25%，所以“半价”是相对促销价而言；他还两次遇到 Opus 5.5 在 max 思考级别下耗尽 128,000 输出 token 上限、最终没有返回结果。

rss · Simon Willison · 9月22日 23:46

**「分层产品线与定价档位」** OpenAI 的 GPT 系列按能力与价格分层发布：GPT-6 Astra 属更高端档位，GPT-6 Sol 在能力与成本之间折中，GPT-6 Luna 则优先压低价格；Anthropic 的 Opus 一直是其产品线中定价最高的型号，因此两家的同日发布主要在中端与低价档位正面竞争。Anthropic 公布 Opus 5.5 在 FrontierCode Main 上得分 54.4%、GDPval-AA 为 1,846 Elo，但这是厂商自报数据，目前可见的独立评测仅将其列为有力候选。

**「对开发者的影响」** 按 Simon Willison 的说法，他此前构建应用的首选 GPT-5.6 Luna 现在可以直接换成成本减半的 GPT-6 Luna，而 GPT-5.6 Terra 与 GPT-6 Sol 同价，继续使用 Terra 的理由基本消失。Anthropic 表示 Sonnet 5.5 和 Haiku 5.5 即将推出，而现有 Haiku 4.5 的 1/5 美元定价是 GPT-6 Luna 的十倍，低价档位的竞争压力明显。需要注意的是，Opus 5.5 在 max 思考级别两次因触及 128,000 输出 token 上限而未能返回结果，使用该档位时需权衡成本与失败风险（两次失败各花费 2.56 美元、耗时近 20 分钟）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://kingy.ai/blog/claude-opus-5-5-vs-gpt-6-astra-vs-gpt-5-6-sol/">Claude Opus 5.5 vs GPT-6 Astra, Sol &amp; Luna: Costs &amp; Benchmarks</a></li>
<li><a href="https://9to5google.com/2026/09/22/claude-opus-5-5-and-openai-gpt-6-sol-luna-both-launch-today-with-lower-costs/">Claude Opus 5.5 and OpenAI GPT-6 Sol &amp; Luna both launch today with lower costs</a></li>

</ul>
</details>

**标签**: `#AI models`, `#LLMs`, `#Anthropic`, `#OpenAI`, `#AI pricing`

---

<a id="item-tech-news-5"></a>
### [vLLM v0.30.0 发布：持久权重缓存与多模型支持](https://github.com/vllm-project/vllm/releases/tag/v0.30.0) ⭐️ 8.0/10

vLLM 发布 v0.30.0，包含来自 315 位贡献者的 762 次提交，新增 DeepSeek-V4.1-Flash、DeepSeek-V4-Flash-Vision-Exp、GLM-5.3-Flash、K2-Horizon、Cohere Compass、Bailing V3 VL 等模型支持，并提供 CUDA 13.0/12.9、ROCm、CPU、XPU 的 PyPI wheel 和 Docker 镜像。该版本的重点服务端特性是 Fast Start：持久化每 GPU 权重缓存守护进程把量化后、TP 分片的权重保留在 GPU 内存中，重启引擎时通过 \`--load-format ipc\_cache\` 经 CUDA IPC 映射，现已覆盖 FP4 检查点和多节点 TP。破坏性变更方面，scale-out 端点改为通过 \`--enable-scale-out\` 显式启用，GPTQ \`g\_idx\` 被移除，0.29 弃用项和多个环境变量被删除，\`python -m vllm.entrypoints.grpc\_server\` 被 \`vllm serve --grpc\` 取代。

github · khluu · 9月22日 05:20

**「背景」** vLLM 是开源的大模型推理与服务引擎，本次发布的是 0.30.0 版本，紧随此前的 0.29 版本。发布说明明确指出，0.29 中已标记弃用的项目在本次被正式移除，包括 VLLM\_PREFIX\_CACHE\_RETENTION\_INTERVAL 和 VLLM\_MM\_HASHER\_ALGORITHM 两个环境变量，这意味着从旧版本升级的用户需要检查并迁移相关配置。

**「影响」** 对仍依赖旧 scale-out 端点、旧 gRPC 启动方式或 GPTQ \`g\_idx\` 的部署，升级前需要替换为 \`--enable-scale-out\`、\`vllm serve --grpc\` 并重新处理相关量化检查点，否则相关启动参数或模型加载会失效。

**标签**: `#vLLM`, `#LLM inference`, `#model serving`, `#open source release`, `#GPU optimization`

---

<a id="item-tech-news-6"></a>
### [Claude Opus 5.5 max 推理档评测：成本减半与 128K 预算耗尽](https://artificialanalysis.ai/models/claude-opus-5-5) ⭐️ 8.0/10

Artificial Analysis 上线了 Claude Opus 5.5 在「max」推理档位下的智能、性能与价格评测页面，同一站点还提供 xhigh 与 medium（默认）档位的独立页面。该评测页本身没有可用的正文内容，可核实的细节主要来自 Hacker News 评论：hglaser 引用页面数据称，在 high effort 对 high effort 的比较下，Opus 5.5 的每任务成本约为 Opus 5 的一半。simonw 则报告 max 档位下 128,000 token 预算会在模型仍在推理时耗尽，他两次尝试生成「骑自行车的鹈鹕」SVG 都因此失败。以上均为评论者转述页面数据或个人单次体验，并非独立复核的结果。

hackernews · theanonymousone · 9月22日 16:51 · [社区讨论](https://news.ycombinator.com/item?id=49804316)

**「背景」** Artificial Analysis 的模型评估按推理努力程度分为不同档位（如 medium、xhigh、max），本次页面针对的是最高档 max。该机构在 2026 年 7 月 24 日的页面上给 Claude Opus 5（max）的 Intelligence Index 评分为 51，而当前 Claude Opus 5.5（max）的评分为 58，两者可直接对比。

**「影响」** 对使用该模型的开发者而言，成本节省与任务可完成性都取决于推理档位：Anthropic 称 Opus 5.5 在默认（medium）档的智能体编程任务中以约一半的轮次、时间和输出 token 达到 Opus 5 的质量，成本下降 40%–50%，Artificial Analysis 也把低 effort 档列为每任务成本最低（$0.55），但这些数据并不覆盖 max 档。有 HN 评论者报告，在 max 档下模型两次因把 128,000 token 预算耗尽在推理过程中而未能完成任务，因此实际使用中可能需要在 max 之外选择 xhigh 或 medium 档。

**「社区讨论」** 评论中出现了两类主要担忧：breckenedge 质疑这类评测是否会在发布数周后重跑，并称自己内部数据集的一次运行显示 Sol 的表现回落到与 Luna 持平（他本人强调这只是单次运行），担心厂商先快速证明最强、等用户迁移后再「抽地毯」；cmiles8 则认为前沿模型只比开源权重模型略好，价格却高约 100 倍。此外 linuxrebe1 表示已从 Opus 5 退回使用 Opus 4.8，理由是后者更擅长记住任务目标和遵循指令，而 Opus 5 常中途跑偏。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://artificialanalysis.ai/models/claude-opus-5-5">Claude Opus 5.5 (max with fallback) - Intelligence, Performance &amp; Price Analysis | Artificial Analysis</a></li>
<li><a href="https://artificialanalysis.ai/models/claude-opus-5">Claude Opus 5 (max) - Intelligence, Performance &amp; Price Analysis | Artificial Analysis</a></li>
<li><a href="https://artificialanalysis.ai/models/releases/claude-opus-5-5">Claude Opus 5 . 5 Models - Intelligence... | Artificial Analysis</a></li>
<li><a href="https://www.anthropic.com/claude-opus-5-5">Introducing Claude Opus 5 . 5 \ Anthropic</a></li>

</ul>
</details>

**标签**: `#LLM benchmarks`, `#AI model pricing`, `#Claude Opus`, `#reasoning models`, `#AI evaluation`

---

<a id="item-tech-news-7"></a>
### [五角大楼称过度依赖 AI 致伊朗学校遭袭](https://www.bloomberg.com/graphics/2026-iran-school-attack/) ⭐️ 8.0/10

彭博的一项报道（在 Hacker News 上引发讨论）称，五角大楼的审查认定，过度依赖 AI 是伊朗一所学校遭导弹袭击的原因之一。报道引述的结论称，美方“未能履行尽一切可行努力核实”该学校属于军事目标的义务，相关失误“超出了单纯疏忽”，并指美方在明知存在击中民用物体的重大风险下仍实施打击。报道还称，Minab 的一处设施因数据过时被登记为伊斯兰革命卫队设施，与其他候选目标一起输入 Maven 系统后，成为第一天打击的推荐目标，原本耗时数小时的目标清单工作被压缩到几分钟。上述内容来自报道及评论者的转述，并非独立核实，评论者对其是否应归咎于 AI 存在分歧。

hackernews · devonnull · 9月22日 19:03 · [社区讨论](https://news.ycombinator.com/item?id=49806430)

**「背景」** 2026 年 2 月，两枚战斧导弹击中了伊朗南部米纳布的 Shajarah Tayyebeh 小学，造成超过 150 人死亡，其中包括至少 123 名儿童。此前有报道指出，美军依赖过时的卫星图像，将该学校误判为军事基地的一部分。

**「影响」** 彭博社报道称，这起针对伊朗米纳卜学校的打击之后，美国军方已修改其人工智能与致命目标打击流程（tool-3-2）；另有报道指出，被误判为军事目标的该地点是因数据过时而进入 AI 目标推荐，暴露出人工复核环节的缺失（tool-3-1）。对向军方出售模型的 AI 公司而言，Anthropic 首席执行官表示自己并不清楚 Claude 是否被用于此次打击，说明供应商对自家工具在实战中的使用方式缺乏可见性（tool-3-3）。

**「社区讨论」** 评论者对责任归属看法不一：legitster 认为细读报道后“AI”并不是真正的罪魁祸首，而 jmathai 强调问题在于过时数据被送入 Maven、目标筛选从数小时压缩到数分钟，并称“我们优化错了指标”。macintux 还提到一起相关事件：AI 曾误判一艘中国船只载有核武器材料，美军几乎登船检查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gizmodo.com/pentagon-investigators-say-overreliance-on-palantir-ai-tech-contributed-to-u-s-strike-that-killed-123-iranian-children-2000814477">Pentagon Investigators Say Overreliance on Palantir AI Tech...</a></li>
<li><a href="https://rtrunews.com/news/646000-overreliance-on-ai-contributed-to/">US overreliance on AI contributed to deadly Iran school strike ...</a></li>
<li><a href="https://www.prospectmagazine.co.uk/world/middle-east/72906/mikail-mirdoraghi-iran-school-strike-ai">His mother waved him off to school . He didn’t return—and AI may be...</a></li>
<li><a href="https://www.bloomberg.com/news/articles/2026-09-22/us-military-modifies-ai-combat-targeting-after-iran-minab-school-strike">US Military Modifies AI , Combat Targeting After Iran Minab School ...</a></li>
<li><a href="https://thenextweb.com/news/anthropic-amodei-claude-iran-school-strike-military-ai">Anthropic’s CEO says he doesn’t know if Claude was used in the Iran ...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#military AI`, `#targeting systems`, `#AI governance`, `#human oversight`

---

<a id="item-tech-news-8"></a>
### [Cloudflare Python Workers 正式全面可用](https://blog.cloudflare.com/python-workers-ga/) ⭐️ 8.0/10

Cloudflare 于 9 月 21 日宣布 Python Workers 正式全面可用（GA），Python 成为其开发者平台的一级支持语言。该功能两年前推出，现在原生支持 FastAPI、Django、Flask 等框架，并新增底层网络能力。开发者可在 Workers 中直接运行 PostgreSQL 等数据库及 LangChain 等 AI 库，并与 Workers AI、R2、D1 等服务无缝集成。

telegram · zaihuapd · 9月22日 04:00

**「背景」** Python Workers 约两年前推出，此前长期处于预览阶段，其实现方式是将 Python 通过 Pyodide 编译为 WebAssembly，运行在基于 V8 的 workerd 运行时中（tool-2-2、tool-2-3）。在正式全面可用之前，Cloudflare 曾发布博客介绍如何实现更快的冷启动、更完整的包支持以及以 uv 为先的依赖处理流程（tool-2-1）。该架构同时带来限制：据 Simon Willison 的说明，WebAssembly 虚拟机中多进程与线程均无法使用（tool-2-2）。

**「影响」** 对使用 FastAPI、Django 或 Flask 的 Python 开发者而言，最直接的变化是可以在 Workers 上复用这些框架，并直接调用 Workers AI、R2、D1、PostgreSQL 和 LangChain，从而减少为边缘或无服务器环境另选运行时的需要。公告未说明各框架在 Workers 上的兼容性差异或限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.cloudflare.com/python-workers-advancements/">Python Workers redux: fast cold starts, packages, and a uv-first...</a></li>
<li><a href="https://simonwillison.net/2026/Sep/21/cloudflare-python-worker/">Cloudflare Python Workers are now generally available</a></li>
<li><a href="https://www.brocker.org/cloudflare-python-workers-general-availability">Cloudflare Python Workers Reach General Availability</a></li>

</ul>
</details>

**标签**: `#Python`, `#Cloudflare Workers`, `#serverless`, `#edge computing`, `#AI`

---

<a id="item-tech-news-9"></a>
### [黑客声称掌握全部 FBI 员工数据，尚未获证实](https://www.404media.co/we-hacked-the-fbi-hackers-say-they-have-data-on-all-fbi-employees/) ⭐️ 7.0/10

据 404 媒体（404 Media）2026 年 9 月 22 日的报道，有黑客声称“我们黑进了 FBI”，并宣称已获取美国联邦调查局（FBI）全体员工的资料，此事在 Hacker News 上引发讨论。这是黑客单方面的说法：目前没有 FBI 或独立安全机构的确认，条目也未提供数据规模、字段范围或入侵途径等可核实的技术细节。

hackernews · spenvo · 9月22日 17:46 · [社区讨论](https://news.ycombinator.com/item?id=49805278)

**「背景」** ShinyHunters 是一个自 2019 年起活跃的黑帽黑客与勒索组织，此前已卷入大量数据泄露事件。据媒体报道，该组织称此次拿到的 FBI 数据来自一起 PeopleSoft 零日漏洞入侵后的后续访问，涉及据称存放员工与申请人信息的 FBI AWS GovCloud 环境；截至报道时 FBI 尚未回应该说法。

**「对联邦雇员的具体风险」** 若此次泄露属实，直接受影响的是被波及的 FBI 雇员本人：404media 指出，ShinyHunters 同一生态圈的犯罪分子此前曾利用窃取的通话记录追踪、恐吓和骚扰 FBI 探员，因此这批员工数据可能被用于针对个人的定位与施压，而不只是情报层面的问题。需要留意的是，涉事组织自称掌握“所有 FBI 员工”的数据，而 CBC 报道称其声称窃取的是数千名员工的数据，实际范围尚未核实，雇员在确认前难以判断应对哪些个人信息采取补救措施。

**「社区讨论」** 评论中最实质的讨论是把此事与 2015 年美国人事管理局（OPM）约 2210 万条政府雇员记录被中国黑客窃取的事件相类比，认为大型数据库如今很难保证安全。另有评论引述据称是 ShinyHunters 代表的说法，称其计划“不是我会称之为勒索的东西，或许是胁迫”，且并非出于金钱动机；其余回复多为调侃，例如玩笑称黑客被误加进了存放数据的 Signal 群聊或 Google Drive。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ShinyHunters">ShinyHunters - Wikipedia</a></li>
<li><a href="https://kfdm.com/news/nation-world/high-profile-hacking-group-claims-it-hacked-the-fbi-and-stole-data-on-employees-extortion">High profile hacking group claims it hacked the FBI and stole data ...</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/shinyhunters-claims-fbi-hack-data-theft-in-peoplesoft-zero-day-breach/">ShinyHunters claims FBI hack , data theft in PeopleSoft zero-day...</a></li>
<li><a href="https://www.404media.co/we-hacked-the-fbi-hackers-say-they-have-data-on-all-fbi-employees/">‘We Hacked the FBI :’ Hackers Say They Have Data on All FBI ...</a></li>
<li><a href="https://www.cbc.ca/news/world/shinyhunters-breach-fbi-9.7354002">ShinyHunters hackers say they breached FBI , stole employee data</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#data breach`, `#FBI`, `#privacy`, `#hacking`

---

<a id="item-tech-news-10"></a>
### [Trail of Bits 博文批评 SAML 设计缺陷](https://blog.trailofbits.com/2026/09/21/saml-a-fractal-of-bad-design/) ⭐️ 7.0/10

Trail of Bits 发布博文《SAML: A fractal of bad design》，系统性地批评 SAML 协议的设计缺陷，该文在 Hacker News 上引发了讨论。批评的重点是 XML 签名的验证风险，并把 SAML 与 OIDC 放在一起做权衡。这是安全厂商的技术评述，不是新披露的漏洞或产品变更；评论中提到的具体实现缺陷属于读者的个人回忆与经验，未经独立核实。

hackernews · aray07 · 9月22日 18:57 · [社区讨论](https://news.ycombinator.com/item?id=49806335)

**「背景」** SAML（Security Assertion Markup Language）是基于 XML 的企业单点登录标准，身份断言以 XML 文档的形式在 IdP 与 SP 之间传递并依赖 XML Signature（xmlsig）完成签名校验（tool-2-3）。这一设计带来了长期存在的验证陷阱，例如攻击者可在保持签名有效的前提下改动 XML 结构实施签名包装（XML Signature Wrapping），或利用外部实体（XXE）等问题（tool-2-2）。作为较新的替代方案，OIDC 更适合现代 SaaS、API 与开发者优先的场景，而同时支持两者正变得越来越常见（tool-2-1）。

**「影响」** 对正在实现 SSO 的开发者，评论区给出的具体动作项是收紧 XML 签名校验：先明确签名究竟覆盖文档的哪一部分，再限制可接受的信任来源与算法。bawolff 回忆称，某些 XML 签名库曾默认同时接受攻击者文档中指定的 HMAC 密钥，甚至用 Web PKI 证书来验证签名，说明不能依赖库的默认行为。这些说法来自社区经验，现有材料无法确认博文是否给出同样的建议。

**「社区讨论」** 评论区的分歧在于 OIDC 是否真的更好：tehnoslow 认为文章只罗列 SAML 的问题，却没有对 OIDC 做同等剖析，并点出 JWT 算法混淆、none 算法、缺少 audience 校验以及 JOSE 库缺陷等问题；cameronh90 则主张 SAML 在 IdP 发起的登录等企业 SSO 场景仍有 OIDC 缺少的能力，且 OIDC 各产品支持不一致，面向企业应同时支持两者。jmbwell 把问题追溯到 XML 被视为万能工具的年代，并提醒 OIDC 自身也带着服务大厂的假设。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ssojet.com/blog/oidc-vs-saml">OIDC vs SAML – Which Is Better for SSO ?</a></li>
<li><a href="https://blog.magicauth.app/articles/oauth-vs-saml-comparison">OAuth 2.0 vs SAML : Complete Technical Comparison for Enterprise ...</a></li>
<li><a href="https://www.linkedin.com/posts/huzaifa-afraz_oktaintegration-oidc-identitymanagement-activity-7398918364909187072-ryPO">#oktaintegration # oidc #identitymanagement #nodejsdevelopment...</a></li>

</ul>
</details>

**标签**: `#SAML`, `#authentication`, `#security`, `#XML`, `#SSO`

---

<a id="item-tech-news-11"></a>
### [Complex KDA：扩展 Kimi Delta Attention 的表达力](https://www.reddit.com/r/MachineLearning/comments/1wn5uv9/understanding_and_enhancing_kimi_delta_attention_r/) ⭐️ 7.0/10

Reddit r/MachineLearning 上的一篇帖子总结了论文《Complex KDA: Understanding and Enhancing the Expressivity of Kimi Delta Attention》，说明 Gated Deltanet（GDN）与 Kimi Delta Attention（KDA）在表达力上的差异。作者指出，KDA 的完整对角门可以充当反射，从而在单步内完成二维旋转，但前提是把门的取值范围扩展到 \[-1,1\]、把 delta 规则的学习率扩展到 \[0,2\]，这一形式被称为 Complex KDA（CKDA）。其理论表明该形式可以表达任意正交的对角加秩一矩阵，并追踪 S3、S4、A5 群，但无法追踪 S5。实验显示 CKDA 能学会 S3 与 S4，在音频续写任务上结果有前景，并且在语言建模中训练稳定、与标准 KDA 竞争力相当。这些均为论文作者在帖子中转述的理论与实验主张，帖子未提供完整论文细节。

reddit · r/MachineLearning · /u/Yossarian\_1234 · 9月22日 10:34

**「背景」** 该帖是对论文《Complex KDA: Understanding and Enhancing the Expressivity of Kimi Delta Attention》（arXiv:2609.24797，作者包括 Julien Siems 等 11 人）的转述与讨论，而非独立研究。所讨论的 Kimi Delta Attention（KDA）属于用 delta 规则更新快速权重记忆的线性注意力，其门控为逐通道的满对角门；源帖关注的正是它与 Gated DeltaNet（GDN）在表达能力上的差异。论文摘要称，KDA 能把单次 delta 规则变换与其逐通道门提供的第二次反射组合起来，从而实现二维旋转。

**「影响」** 对想复现或采用该方法的序列建模研究者来说，具体改动是把门的取值范围放宽到 \[-1,1\]、把 delta 规则学习率放宽到 \[0,2\]；帖子报告这种放宽在语言建模上仍能稳定训练且与标准 KDA 竞争力相当，但其表达力保证只覆盖正交的对角加秩一矩阵，并明确无法追踪 S5 群，说明收益存在明确边界。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/papers/2609.24797">Paper page - Complex KDA : Understanding and Enhancing the ...</a></li>
<li><a href="https://arxiv.org/abs/2609.24797">[2609.24797] Complex KDA : Understanding and Enhancing the ...</a></li>

</ul>
</details>

**标签**: `#Kimi Delta Attention`, `#linear attention`, `#expressivity`, `#sequence modeling`, `#group theory`

---

<a id="item-tech-news-12"></a>
### [Qonto 发布 QontoFAQ 检索基准与相关性新指标](https://www.reddit.com/r/MachineLearning/comments/1wn9xqk/qontofaq_a_better_information_retrieval_benchmark/) ⭐️ 7.0/10

Reddit 用户 /u/espadrine 于 2026 年 9 月 22 日发帖介绍了 QontoFAQ：一个用于评估嵌入模型在产品 FAQ 检索任务上表现的信息检索基准数据集，以及一个作者称“与文档相关性更成比例”的新相关性指标。帖子称现有检索基准有时显得被模型“刷榜”（benchmaxxed），因此团队希望把评测尽量贴近“找出真正回答产品问题的文章”这一目标。相关方法说明发布在 Qonto 的 Medium 博客上，配套代码托管在 GitHub 的 qonto/qonto-faq-benchmark 仓库。该基准出自公司博客而非同行评审论文，其影响范围限于信息检索／FAQ 检索领域。

reddit · r/MachineLearning · /u/espadrine · 9月22日 13:45

**「背景」** 信息检索模型的评测通常依赖公开基准和排序指标，例如 BEIR 是一个覆盖 18 个数据集、九类检索任务的零样本基准，并以 nDCG@10 作为头条指标，用来评估 RAG 的检索环节（tool-2-3）。这类评测度量的是索引、搜索引擎或数据库返回结果满足用户查询的程度，因此是判断检索系统表现的基础（tool-2-1）。QontoFAQ 提出的相关性度量与配套数据集正建立在这一既有评测框架之上。

**「影响」** 由于数据集、指标说明与代码均已公开，做嵌入模型选型的开发者可以直接在 Qonto 自建的产品 FAQ 场景上复现比较；但需注意其来源是公司博客而非同行评审，指标定义与数据构建方式是否适配自有语料，仍需自行核对后再作为选型依据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Evaluation_measures_%28information_retrieval%29">Evaluation measures ( information retrieval ) - Wikipedia</a></li>
<li><a href="https://benchmarkingagents.com/beir/">BEIR: The Zero-Shot Retrieval Benchmark for RAG...</a></li>

</ul>
</details>

**标签**: `#information retrieval`, `#benchmarks`, `#embeddings`, `#NLP`, `#machine learning`

---

<a id="item-tech-news-13"></a>
### [阿里发布真武 V900，宣称国产 AI 芯片算力达 M890 三倍](https://finance.sina.com.cn/stock/bxjj/2026-09-22/doc-inissitf7048094.shtml) ⭐️ 7.0/10

在 2026 云栖大会上，阿里平头哥发布自称最强国产 AI 芯片真武 V900，称其算力为真武 M890 的 3 倍，单一集群可扩展至 50 万卡。阿里 CEO 吴泳铭表示，自研 M890 超节点已支撑 2 万亿参数大模型推理，本季度将规模化上架阿里云。阿里方面还称 Qwen 计划训练 5 至 10T 参数新模型，目标是到 2032 年阿里云全球数据中心规模超过 20GW。上述算力倍数、参数规模与数据中心容量均为阿里单方面披露，尚无第三方验证。

telegram · zaihuapd · 9月22日 03:30

**「前代真武 M890 与超节点基础」** 真武 V900 的算力对比基准是平头哥上一代自研 AI 芯片真武 M890。据大会报道，阿里全新升级的超节点服务器把真武 V900 与 ICN Switch、磐脉智能网卡及镇岳 SSD 主控做算、存、网全栈系统级协同，以此为单一 AI 集群扩展到 50 万卡规模的基础；此次发布发生在 2026 年 9 月 22 日于杭州开幕的云栖大会上。

**「对云客户与开发者的影响」** 对阿里云客户和模型开发者而言，短期内可用的算力路径仍是本季度规模化上架的 M890 超节点，而真武 V900 按报道计划在 2027 年一季度量产，容量与训练排期需要按这一时间差安排。T-Head 已公布 V900 为 216GB 显存、1200 GB/s 带宽，但这些规格与“3 倍算力”同属厂商口径，尚无第三方实测，选型时应作为待验证参数对待。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://juejin.cn/post/7687995393330413622">一颗 真 武 V 900 ，平头哥的“算力野心”藏不住了9月22日的 2026 ...</a></li>
<li><a href="http://news.cnfol.com/zhengquanyaowen/20260922/32378054.shtml">阿 里 重磅发布叠加Muse催化 AI ...</a></li>
<li><a href="https://thenextweb.com/news/alibaba-zhenwu-v900-ai-chip-20gw-data-centres-qwen-5">Alibaba says its new Zhenwu V 900 is China’s most powerful AI chip</a></li>
<li><a href="https://twiscan.com/en/x/wallstengine/2102324961688060243">Wall St Engine(@wallstengine):$ BABA UNVEILS NEW AI CHIP ...</a></li>
<li><a href="https://www.caixinglobal.com/2026-09-22/alibaba-unveils-new-ai-chip-as-it-deepens-ai-infrastructure-push-102487686.html">Alibaba Unveils AI Chip as Cloud Infrastructure Push... - Caixin Global</a></li>

</ul>
</details>

**标签**: `#AI chips`, `#Alibaba`, `#AI infrastructure`, `#Qwen`, `#datacenter`

---

<a id="item-tech-news-14"></a>
### [DeepSeek 与清华发布 DSec 沙箱平台报告：日服务 300 万沙箱](https://arxiv.org/abs/2609.22978) ⭐️ 7.0/10

DeepSeek-AI 与清华大学联合发布技术报告《DeepSeek Elastic Compute \(DSec\)》，公开其支撑大规模 Agent 训练与评测的沙箱基础设施。DSec 用统一 SDK 提供 FnCall、容器、Firecracker microVM 和完整 VM 四种后端，覆盖 OJ 判题、软件工程、安全渗透、电脑操作等负载，并把有状态的 rollout 执行与可被抢占的 GPU 训练解耦。报告称单个生产单元约 160 个节点，每天服务约 300 万个沙箱实例，峰值并发超 38 万、创建速度超每秒 5000 个，单节点可承载 3200 个容器或 800 个 microVM；基于 3FS 按需加载 EROFS 镜像相比传统 Docker 全量拉取使任务完成时间快 1.7 倍、磁盘写入减少 57%，内存共享与回收机制使峰值内存占用下降约 40%。这些数字与性能对比均出自该报告自身，目前仅见二手 Telegram 摘要转述，尚无独立验证或第三方复现。

telegram · zaihuapd · 9月22日 04:45

**「背景」** 智能体强化学习需要在隔离环境中反复执行模型生成的代码与命令，沙箱的创建速度、隔离强度和单机密度因此直接决定训练与评测的吞吐上限。arXiv 页面摘要显示，DSec（DeepSeek Elastic Compute）是一个生产环境沙箱平台，通过统一 SDK 对外提供 FnCall、容器、microVM 和完整 VM 四类后端，与来源所述技术报告一致（tool-2-1、tool-2-2）。不过，本条目本身仍是二手转述，具体规模与性能数字应以报告原文为准。

**「影响」** 对自建智能体强化学习训练环境、需要同时运行大量隔离执行环境的团队，这份报告指出的瓶颈在于镜像分发与内存开销：DSec 以 3FS 上按需加载 EROFS 镜像替代全量拉取，并靠内存共享与回收压低占用，是其单节点高密度承载的前提条件。需要注意的是，报告描述的是 DeepSeek 自身的生产平台，材料未说明是否开源或对外提供服务，外部团队目前只能参考其架构设计，而非直接部署。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.22978">[ 2609 . 22978 ] DeepSeek Elastic Compute ( DSec ): A Sandbox ...</a></li>
<li><a href="https://arxiv.org/html/2609.22978">DeepSeek Elastic Compute ( DSec ): A Sandbox Infrastructure for...</a></li>

</ul>
</details>

**标签**: `#AI agent training`, `#sandbox infrastructure`, `#reinforcement learning`, `#DeepSeek`, `#distributed systems`

---

<a id="item-tech-news-15"></a>
### [DeepSeek 本周将向联合国安理会通报 AI 风险](https://www.reuters.com/world/asia-pacific/deepseek-brief-un-security-council-ai-this-week-sources-say-2026-09-22/) ⭐️ 7.0/10

路透社援引两名知情人士报道，中国 AI 初创公司 DeepSeek 将于本周向联合国安理会通报人工智能带来的风险。由 15 个成员组成的安理会定于周三开会讨论 AI 与国际安全，OpenAI 首席执行官 Sam Altman 计划出席简报，Anthropic 的高层代表预计也会参加。知情人士称，DeepSeek 和月之暗面（Moonshot）等中国 AI 公司受邀发言，但 DeepSeek 创始人梁文锋不打算出席。上述安排均来自匿名消息人士，尚未获得官方确认，且仍可能临时变动。

telegram · zaihuapd · 9月22日 11:34

**「背景」** 联合国安理会由 15 个成员国组成，曾于 2023 年首次就 AI 风险召开会议（tool-2-2）。据本周早些时候的报道，OpenAI 首席执行官萨姆·奥尔特曼计划在本次会议上发言，Anthropic 高级代表也可能出席（tool-2-1）。

**「影响」** 对 AI 治理观察者与在多国部署前沿模型的组织而言，本次简报把 AI 风险议题正式带入联合国安理会议程，使中美主要实验室同场就 AI 风险向安理会发言。据工具结果，Anthropic 的 Dario Amodei 于 9 月 12 日发文呼吁前沿实验室减少能力研究并向外部评估者开放持续审查，这一主张是否会被政府层面采纳、进而转化为新的审计或评估要求，是相关企业后续需要关注的具体合规变量。DeepSeek 创始人梁文锋不打算出席，中方发言主要由公司代表承担，实际承诺力度仍待观察。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.vbnvbn.com/article/detail/r21t.html">消息称 DeepSeek 本周参加 联 合 国 安 理 会 ，讲解 AI 安 全 风险 - 微比恩</a></li>
<li><a href="https://www.guancha.cn/GongYe%C2%B7KeJi/2026_09_22_901773.shtml">“本周， DeepSeek 将向 安 理 会 通报”</a></li>
<li><a href="https://qz.com/altman-amodei-un-security-council-ai-safety-092226">Sam Altman and Dario Amodei to brief UN Security Council on AI</a></li>

</ul>
</details>

**标签**: `#AI governance`, `#United Nations`, `#DeepSeek`, `#OpenAI`, `#AI policy`

---

<a id="item-tech-news-16"></a>
### [中国监管机构调查 DeepSeek 与月之暗面涉数据转发指控](https://www.theinformation.com/articles/china-probes-deepseek-moonshot-potential-data-leaks-anthropic) ⭐️ 7.0/10

据 The Information 援引知情人士报道，中国互联网监管机构正在调查 DeepSeek 和月之暗面，起因是 Anthropic 指控两家公司把敏感用户数据转发给 Claude 模型。Anthropic 于 9 月 10 日发布的 154 页报告称，共有 7 家中国公司大规模违规使用 Claude，并举例称 DeepSeek 曾把一名警方监控系统开发工程师的请求转发给 Claude。上述指控目前均来自 Anthropic 一方，调查进展以及涉事公司的回应在现有材料中未获独立证实。

telegram · zaihuapd · 9月22日 14:37

**「背景」** 此次调查的直接背景是 Anthropic 于 9 月 10 日发布的一份 154 页威胁情报报告，该报告点名 DeepSeek、月之暗面（Moonshot AI）、阿里巴巴、智谱、小米、MiniMax 和商汤七家中国机构，指控其在 2025 年 12 月至 2026 年 8 月间违规蒸馏 Claude，并将相关行为归入七个类别（tool-2-2、tool-2-3）。有报道进一步称，DeepSeek 与 Kimi 曾把客户请求连同数据转发给 Claude，以复制其输出（tool-2-1）。

**「影响」** 对使用境外模型接口的中国 AI 开发者与企业来说，被调查的核心是“用户请求被转发到 Claude、进而落到美国服务器”这一数据流向——据 The Information 引述知情人士，中国互联网监管机构正就此调查 DeepSeek 与月之暗面（tool-3-1、tool-3-2）。在 Anrhopic 的指控尚未被独立证实、调查结论也未公布的情况下，以境外模型作为中转或兜底通道的团队已需要能够说明哪些提示词含有敏感用户数据，而 Anthropic 9 月 10 日报告点名的 7 家公司也可能同时面临模型访问权限方面的限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://qiaeru.com/en/blog/deepseek-et-kimi-servaient-du-claude-a-l-insu-de-leurs-clients/">DeepSeek and Kimi quietly served their customers Claude · Qiaeru</a></li>
<li><a href="https://timewell.jp/en/columns/anthropic-distillation-report-moonshot-kimi-claude-relay-2026">Anthropic Names Seven Chinese Labs for &quot;Illicit...&quot; | TIMEWELL Inc.</a></li>
<li><a href="https://yellow.com/news/deepseek-moonshot-claude-answers">DeepSeek And Moonshot Passed Off Claude Answers As... | Yellow</a></li>
<li><a href="https://cryptobriefing.com/china-probes-deepseek-moonshot-anthropic-data-leaks/">China probes DeepSeek and Moonshot over alleged data leaks to...</a></li>
<li><a href="https://www.theinformation.com/articles/china-probes-deepseek-moonshot-potential-data-leaks-anthropic">China Probes DeepSeek , Moonshot Over Potential Data Leaks to...</a></li>

</ul>
</details>

**标签**: `#AI regulation`, `#DeepSeek`, `#Moonshot AI`, `#Anthropic`, `#data privacy`

---

<a id="item-tech-news-17"></a>
### [OpenAI 拟让外部机构更早评估模型安全](https://www.bloomberg.com/news/articles/2026-09-22/openai-to-let-outside-groups-evaluate-ai-models-at-earlier-phase) ⭐️ 7.0/10

OpenAI 计划允许第三方机构在其模型训练、评估和发布流程的更早阶段进行技术安全评估，并称将于周二通过博客文章公布这一安排。此前这类外部评估多安排在模型发布前，公司要求评估具备独立机制、科学严谨性和清晰的责任划分。据彭博报道，OpenAI 正与 METR、Redwood Research 等机构洽谈，可能让外部评估者进入办公室处理敏感工作；这仍是报道中的计划，具体评估流程、权限和公布内容尚未披露。

telegram · zaihuapd · 9月22日 17:39

**「背景」** METR 是一家评估前沿 AI 模型能力与风险的非营利研究机构，在此次报道中被列为 OpenAI 潜在的外部评估合作方之一（tool-2-3、tool-2-1）。在此之前，OpenAI 模型的安全评估通常安排在发布前进行，外部机构难以更早介入；彭博社将这一新安排描述为 OpenAI 应对 AI 潜在危害担忧的既有努力的一部分（tool-2-1）。据《纽约邮报》报道，今年早些时候 OpenAI 与 Anthropic 还曾就互相“压力测试”对方模型的安全缺陷进行过谈判（tool-2-2）。

**「影响」** 若该计划落地，前沿模型开发团队需在训练和发布之间为外部机构开放对未发布模型及内部敏感工作的访问权限，并相应建立保密与操作流程，评估时点也将更直接影响发布节奏。目前 METR、Redwood Research 是否最终参与，以及评估结果如何影响发布决策均未确认，因此短期内还不能视为已生效的第三方审计制度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bloomberg.com/news/articles/2026-09-22/openai-to-let-outside-groups-evaluate-ai-models-at-earlier-phase">OpenAI Will Allow Third-Party Groups to Assess AI ... - Bloomberg</a></li>
<li><a href="https://nypost.com/2026/09/21/business/openai-anthropic-held-talks-to-stress-test-each-others-ai-models-report/">OpenAI , Anthropic held talks to &#x27;stress-test&#x27; each other&#x27;s AI mod...</a></li>
<li><a href="https://metr.org/">METR</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#AI safety`, `#model evaluation`, `#AI governance`, `#third-party audit`

---

<a id="item-tech-news-18"></a>
### [高通发布骁龙 8 Elite Extreme Gen 6 移动平台](https://www.qualcomm.com/smartphones/products/8-series/snapdragon-8-elite-extreme-gen-6-mobile-platform) ⭐️ 7.0/10

高通发布骁龙 8 Elite Extreme Gen 6 移动平台，主打面向新一代 agentic AI 的场景。按高通公布的数据，其 Oryon CPU 为全球首款 5 GHz 手机 CPU、性能提升 13%，Adreno GPU 性能提升 44%、能效提升 40%，Hexagon NPU 提速 35%。平台支持 8K60 与 4K240 视频拍摄、全球首创的三颗 6400 万像素摄像头方案，并配备下行峰值 14.8 Gbps 的 X105 5G 调制解调器。上述性能与能效数字均为高通方面说法；极客湾对工程机的能效测试显示，该平台较上代的提升较为克制，远不及零售版 A20 Pro。

telegram · zaihuapd · 9月23日 00:52

**「背景」** 骁龙 8 Elite 是高通的年度旗舰移动平台，此次的 Gen 6 是该系列最新一代迭代，来源对其能效的评价即以“上代”为比较基准。竞品参照方面，外部资料把该平台与苹果 A20 Pro 放在一起对比：苹果 A20 Pro 在 Geekbench 6 中单核 4,707、多核 12,598 分，而一份泄露列表中骁龙 8 Elite Extreme Gen 6 为单核 4,327、多核 12,873 分，后者并非官方公布数据，只能作为未经确认的参照。

**「影响」** 对准备换机的用户来说，值得注意的落差在于能效：极客湾的工程机测试表明代际能效提升相对有限，因此不宜把 44% 的 GPU 性能提升直接等同于同等幅度的续航改善，最终表现仍取决于具体机型的散热与调校。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gadgets.beebom.com/guides/snapdragon-8-elite-extreme-gen-6-vs-apple-a20-pro-benchmark-specs">Snapdragon 8 Elite Extreme Gen 6 vs Apple A 20 Pro : Benchmarks...</a></li>

</ul>
</details>

**标签**: `#Qualcomm`, `#Snapdragon`, `#mobile SoC`, `#agentic AI`, `#smartphone hardware`

---