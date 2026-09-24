---
layout: default
title: "Horizon Summary: 2026-09-24 (ZH)"
date: 2026-09-24
lang: zh
---

> 从 37 条内容中筛选出 8 条重要资讯。

---

**科技新闻**
1. [Anthropic：Claude 自主发现类似 CRISPR 的 ART 酶系统](#item-tech-news-1) ⭐️ 9.0/10
2. [Google 公布 Gemini 3.8 文本转语音，支持 30 秒样本语音复制](#item-tech-news-2) ⭐️ 7.0/10
3. [《Token 便宜到无需计量》：LLM 调用会比 grep 更便宜吗](#item-tech-news-3) ⭐️ 7.0/10
4. [Claude Code 关闭遥测时不读 AGENTS.md，v2.1.281 已修复](#item-tech-news-4) ⭐️ 7.0/10
5. [ShinyHunters 声称入侵 FBI 相关服务并窃取全员数据](#item-tech-news-5) ⭐️ 7.0/10

**财经新闻**
1. [路透：中国监管据称要求部分银行不将万科逾期贷款列为不良](#item-finance-news-1) ⭐️ 8.0/10
2. [中美贸易休战延长至 2027 年 1 月 10 日](#item-finance-news-2) ⭐️ 8.0/10
3. [特朗普与习近平会晤在即：企业界只求延长贸易休战](#item-finance-news-3) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Anthropic：Claude 自主发现类似 CRISPR 的 ART 酶系统](https://www.anthropic.com/news/claude-discovers-novel-enzyme-system) ⭐️ 9.0/10

Anthropic 宣布成立生命科学研究团队与实验室，并公布一项早期成果：仅提供高层指令的情况下，Claude 智能体自主发现了一种与 DNA 重复序列相关、特征类似 CRISPR 的新型酶系统。该系统基于逆转录酶、主要存在于噬菌体，被命名为阵列相关逆转录酶（ART），但目前功能尚不明确。Anthropic 表示，950 个智能体耗时 21 小时，从超过 20 万个逆转录酶中筛选出候选；张锋将该工作称为 AI 智能体助力生物发现的范例。

telegram · zaihuapd · 9月24日 01:11

**「背景」** CRISPR 系统的标志性特征是功能基因旁排列着一长串重复 DNA 序列，即所谓 CRISPR 阵列；而逆转录酶能够以 RNA 为模板合成 DNA。据外部报道，Anthropic 于今年春季成立了内部研究小组，本次 ART 是该团队的首项成果，相关预印本尚未经过同行评审。

**「影响」** 对关注基因编辑与 AI 驱动科研的团队来说，这次发现的直接后果是流程层面的：Anthropic 称约 950 个 Claude 智能体在 21 小时内从 20 多万个逆转录酶中筛出候选，但 ART 的功能仍然未知，因此现阶段还不能作为编辑工具或治疗手段使用，其价值取决于后续实验验证——据工具结果显示，相关实验室工作由 Anthropic 新设的湾区生命科学实验室的人类研究人员完成。这也意味着研究人员若要跟进，需要的是湿实验验证能力，而不仅是复用这次的计算筛选流程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thenextweb.com/news/anthropic-claude-enzyme-system-crispr-like-repeats">Anthropic says Claude found a new enzyme system with CRISPR-like repeats</a></li>
<li><a href="https://www.technobezz.com/news/anthropic-claude-crispr-like-enzyme-system-art">Anthropic Says Claude Found a CRISPR-Like Enzyme System | Technobezz</a></li>
<li><a href="https://www.aitechdaily.com/anthropic-claude-art-enzyme-system/">Anthropic says Claude discovered ART enzyme system with ...</a></li>
<li><a href="https://www.reuters.com/business/healthcare-pharmaceuticals/anthropic-says-claude-ai-helped-discover-novel-enzyme-system-2026-09-23/">Anthropic says Claude AI helped discover novel enzyme system</a></li>
<li><a href="https://www.anthropic.com/news/claude-discovers-novel-enzyme-system">Claude discovers a novel enzyme system \ Anthropic</a></li>

</ul>
</details>

**标签**: `#AI for science`, `#autonomous agents`, `#enzyme discovery`, `#CRISPR`, `#Anthropic`

---

<a id="item-tech-news-2"></a>
### [Google 公布 Gemini 3.8 文本转语音，支持 30 秒样本语音复制](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-text-to-speech/) ⭐️ 7.0/10

Google 公布了 Gemini 3.8 文本转语音模型，其主打能力是语音复制：只需 30 秒音频样本，即可重建一致的嗓音配置，并配有内置的同意验证、SynthID 水印和 C2PA 凭证。Google 将这些安全机制描述为同时保护开发者和提供声音的配音人员。这是一项发布公告，公开材料没有给出跨平台的统一开放范围与独立实测结果，一位评论者指出，此类发布末尾列出的可用性在消费级、专业级与云平台上并不一致。

hackernews · swolpers · 9月23日 15:29 · [社区讨论](https://news.ycombinator.com/item?id=49817615)

**「背景」** Google 的语音合成产品过去主要依靠固定预设音色；官方博客称此次一次性推出 Gemini 3.8 Flash TTS 与 Gemini 3.8 Flash-Lite TTS 两个模型，把语音生成从静态预设变成可定制的创作工具，并用于 Gemini Notebook、Google Vids 等产品。语音复刻并非首次出现：Google Cloud 文本转语音文档中已有 Gemini-TTS 语音复刻（voice replication）的专门说明页，介绍如何用 Gemini-TTS 模型复刻声音。本次公告的增量在于把复刻能力与同意验证、SynthID 水印和 C2PA 凭据打包在一起。

**「影响」** 对开发者的具体后果是各平台能力不对齐：有评论者称 Google 的消费级、专业级与云（GCP）三处平台不仅开放范围不同，模型能力也不同，例如 Omni Flash 在消费级与专业级平台上可输出视频和文本，而在 GCP 上只能输出视频。对于禁用消费级与专业级产品的组织，这意味着同一项语音能力未必能通过自有环境获得，接入前需要按平台逐一核对可用性与输出模态。

**「社区讨论」** 评论区对这次发布的新意看法不一：simonw 认为语音克隆在其他供应商处已足够普及，Google 因此不再犹豫推出；sharktheone 则回忆 Google 几年前曾因担心滥用而拒绝发布同类 TTS 模型。另有评论者 thangalin 介绍了本地托管的替代方案 KeenLore（用 Gemma 4 分析文本、无需云端付费），并自称其引文归属识别准确率为 97.2%（485/499）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-text-to-speech/">Gemini 3.8 Flash TTS and Gemini 3.8 Flash-Lite TTS - The Keyword</a></li>
<li><a href="https://docs.cloud.google.com/text-to-speech/docs/gemini-tts-voice-replication">Gemini-TTS voice replication | Cloud Text-to-Speech | Google ...</a></li>

</ul>
</details>

**标签**: `#Gemini`, `#text-to-speech`, `#voice cloning`, `#Google AI`, `#AI safety`

---

<a id="item-tech-news-3"></a>
### [《Token 便宜到无需计量》：LLM 调用会比 grep 更便宜吗](https://jyn.dev/tokens-too-cheap-to-meter/) ⭐️ 7.0/10

jyn.dev 的文章《Tokens too cheap to meter》提出，LLM token 价格正沿当前趋势下降：作者观察到一次模型调用（评论中引述为 GPT-5.6 Luna）的成本仅比一次 grep 高约 4 到 5 个数量级，并据此预测 LLM 调用很快会比 grep 更便宜。这是作者基于趋势的推断，而非已交付的能力或独立测量的结果，文章也未给出成本口径与具体时间表。Hacker News 上约 179 条评论主要围绕该预测的可持续性及其背后的商业模式假设展开争论。

hackernews · teoruiz · 9月23日 09:21 · [社区讨论](https://news.ycombinator.com/item?id=49813482)

**「背景：token 计费方式」** 主流 LLM API 大多按 token 计费，token 是词的一个片段，英文中约 1.5 个 token 才构成一个单词，因此单位价格看起来低得多——文章给出的示例是输入 token 约每百万 0.042 美元，输出 token 标为“便宜到无需计量”。讨论 LLM 调用成本是否会低于 grep 这类常规工具调用，前提正是把每次调用的 token 用量乘以这样的单价。

**「影响」** 对打算把日常任务交给 LLM 调用的开发者来说，直接后果是跨厂商的单次成本无法简单类比：Artificial Analysis 的基准方法说明其价格按各模型的原生 token 计算，不同 tokenizer 下 token 数量并不一致，而 MIRI TGT 也指出各厂商定价差异很大，因此不宜就推理的底层成本下强结论。另有分析提醒，按 token 计的单价下降并不等于总支出下降——厂商可能以接近成本的价格换取增长，用量扩大后预算仍可能失控。

**「社区讨论」** 评论者 jetrink 援引斯坦因定律（Stein&\#x27;s Law）认为效率提升不会无限延续，高质量编译式调用的单次成本更可能趋于稳定而非持续暴跌；cs702 认为文章对商业模式可行性分析不足，指出各厂商正以巨额基础设施投入押注未来利润；abirch 则用 1954 年核电『便宜到无需计量』的承诺作类比，称自己的电费账单仍然照表计费。以上均为评论者的个人观点，不构成对成本趋势的证实。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://jyn.dev/tokens-too-cheap-to-meter/">tokens too cheap to meter</a></li>
<li><a href="https://techgov.intelligence.org/blog/observations-about-llm-inference-pricing">Observations About LLM Inference Pricing | MIRI TGT</a></li>
<li><a href="https://artificialanalysis.ai/methodology">Artificial Analysis Benchmarking Methodology | Artificial Analysis</a></li>
<li><a href="https://www.ikangai.com/the-llm-cost-paradox-how-cheaper-ai-models-are-breaking-budgets/">The LLM Cost Paradox: How &quot;Cheaper&quot; AI Models Are Breaking Budgets</a></li>

</ul>
</details>

**标签**: `#LLM inference costs`, `#AI economics`, `#developer tooling`, `#AI industry`, `#Hacker News discussion`

---

<a id="item-tech-news-4"></a>
### [Claude Code 关闭遥测时不读 AGENTS.md，v2.1.281 已修复](https://blog.szypowi.cz/p/claude-code-reads-agents.md-only-when-telemetry-is-on/) ⭐️ 7.0/10

Claude Code 此前只在开启遥测（telemetry）的情况下才会读取项目中的 AGENTS.md。一位维护者在讨论中解释说，这是为了让该功能在出问题时能通过特性开关远程关闭，而遥测关闭后客户端收不到这些开关，于是功能也一并失效；他称这是“完全的人为失误”，并公开了相关 mod 源码。该问题已随发布当日的 v2.1.281 修复。这一修复目前来自维护者本人的说法，尚无独立验证；受影响的主要是关闭遥测、依赖 AGENTS.md 提供项目指令的用户。

hackernews · pszypowicz · 9月23日 12:15 · [社区讨论](https://news.ycombinator.com/item?id=49814947)

**「背景」** AGENTS.md 是多个 AI 编程代理工具共同约定使用的项目指令文件，而 Claude Code 长期以自有的 CLAUDE.md 作为默认的项目指令入口。评论区有用户指出，即便不考虑遥测开关，Claude Code 默认也会在有 CLAUDE.md 可读时忽略 AGENTS.md（包括用户主目录下的 ~/CLAUDE.md），要同时读取两者需把 “Project instructions” 设置改为非默认的 claude-md-and-agents-md。维护者在讨论中解释，此次行为异常源于用功能开关远程控制灰度发布，而关闭遥测的客户端无法接收开关状态。

**「对使用者的影响」** 依赖 AGENTS.md 的开发者应升级到 v2.1.281，因为该版本修复了“仅在启用遥测时才读取 AGENTS.md”的缺陷；若继续使用旧版或未检查配置，项目指令可能被静默忽略。默认行为仍有兼容限制：项目只有在没有 CLAUDE.md 时才会改读 AGENTS.md，若存在用户级 ~/CLAUDE.md，AGENTS.md 也不会被读取，要同时读取需把 Project instructions 切换为 \`claude-md-and-agents-md\`。此外，该 AGENTS.md 支持目前尚未覆盖 Bedrock、Vertex 或 Foundry。

**「社区讨论」** 有用户提醒，即便没有这个缺陷，只要存在可读的 CLAUDE.md（包括 ~/CLAUDE.md），Claude Code 默认就不会读取 AGENTS.md，需要把 Project instructions 设为非默认的 claude-md-and-agents-md 才能两者都读，并反映启动时会反复打印 “agents-md: no CLAUDE.md found; AGENTS.md loaded”。另有评论者认为这类细微却严重的缺陷源于在代码库中层层叠加、缺乏把关的 AI 生成补丁，也有人质疑是否所有功能都被放在特性开关之后。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://stacker.news/items/1580206">Claude Code reads AGENTS.md only when telemetry is on</a></li>
<li><a href="https://github.com/anthropics/claude-code/releases">Releases · anthropics/claude-code - GitHub</a></li>

</ul>
</details>

**标签**: `#claude-code`, `#ai-coding-agents`, `#telemetry`, `#feature-flags`, `#developer-tools`

---

<a id="item-tech-news-5"></a>
### [ShinyHunters 声称入侵 FBI 相关服务并窃取全员数据](https://www.404media.co/we-hacked-the-fbi-hackers-say-they-have-data-on-all-fbi-employees/) ⭐️ 7.0/10

黑客组织 ShinyHunters 声称已入侵多个与美国联邦调查局（FBI）相关的服务，并窃取了所有 FBI 员工及求职申请者的数据。据 404 Media 报道，该组织提供的一份样本包含约 5,000 名所谓 FBI 员工的信息，数据可能包括姓名、住址、电话号码以及配偶等家属信息。FBI 尚未确认这一说法，现有信息也未说明入侵入口、数据实际范围或发生时间。若数据属实，泄露信息可能被用于跟踪、骚扰甚至威胁 FBI 员工及其家属，并对美国执法和情报系统构成安全与反情报风险。

telegram · zaihuapd · 9月23日 05:00

**「背景」** ShinyHunters 是一个此前多次因窃取数据、勒索知名企业而为人所知的黑客组织。针对此次事件，FBI 发言人向 TechCrunch 表示，已知悉有关 FBIjobs.gov 遭未授权活动的说法，目前正在调查；该招聘门户一度无法访问并被指遭到篡改，FBI 特工申请者门户也处于下线状态。前 FBI 官员 Cynthia Kaiser 则指出，此类泄露危害极大，因为犯罪分子可能借此曝光并施压正在调查他们的人员。

**「影响」** 据 Politico 报道，FBI 已表示正在调查其在线招聘门户可能遭入侵一事；路透社则报道称，疑似被窃数据包含数十名官员的具体岗位分配细节，涉及针对中国、俄罗斯间谍活动的敏感工作。若这些记录属实，被暴露的不只是姓名和联系方式，还包括可用于识别从事敏感或情报岗位人员身份的职务信息，从而加大其被定位、骚扰或威胁的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ShinyHunters">ShinyHunters - Wikipedia</a></li>
<li><a href="https://techcrunch.com/2026/09/22/hacking-group-shinyhunters-claims-it-breached-the-fbi-stole-agents-and-applicants-data/">Hacking group ShinyHunters claims it breached the FBI, stole agents&#x27; and applicants&#x27; data | TechCrunch</a></li>
<li><a href="https://www.cbc.ca/news/world/shinyhunters-breach-fbi-9.7354002">ShinyHunters hackers say they breached FBI, stole employee data | CBC News</a></li>
<li><a href="https://www.politico.com/news/2026/09/22/shinyhunters-fbi-cyber-hack-01088494">Cybercriminal group claims to steal thousands of FBI employee ...</a></li>
<li><a href="https://www.reuters.com/world/hacked-fbi-data-has-sensitive-information-about-employees-intelligence-roles-2026-09-23/">Hacked FBI data has sensitive information about employees ...</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#data-breach`, `#FBI`, `#ShinyHunters`, `#privacy`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [路透：中国监管据称要求部分银行不将万科逾期贷款列为不良](https://www.reuters.com/world/asia-pacific/china-asks-banks-keep-vanke-loans-off-bad-debt-books-sources-say-2026-09-22/) ⭐️ 8.0/10

路透社援引知情人士称，中国金融监管机构要求部分大型银行不将万科的逾期贷款列为不良资产，并延长还款期限、暂缓收取利息。万科 2025 年录得创纪录的 886 亿元亏损（实际结果），上半年净亏损扩大至 149.5 亿元。

telegram · zaihuapd · 9月23日 03:12

**「背景」** 背景：万科是中国大型住宅开发商，总部位于深圳，最大股东为深圳国资背景企业；在中国房地产行业持续低迷之际，其 2025 年净亏损扩大 79%至 886 亿元人民币。这里的“不良贷款”通常指已出现还款困难的贷款，监管要求银行不将万科的逾期贷款列入该类别，即暂时不把这些贷款按不良资产处理。

**「影响」** 若上述指示属实，向万科放贷的大型银行可将这些逾期贷款继续按正常资产列账，无需计入不良或相应增提拨备，但相关信用损失风险仍留在银行体系内；据 Business Times 报道，监管方力图避免的是万科违约可能引发的连锁反应对金融稳定的冲击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vanke">Vanke - Wikipedia</a></li>
<li><a href="https://www.caixinglobal.com/2026-04-02/vanke-2025-net-loss-widens-79-to-13-billion-on-massive-impairments-102430048.html">Vanke 2025 Net Loss Widens 79% to $13 Billion on... - Caixin Global</a></li>
<li><a href="https://www.reuters.com/world/asia-pacific/china-asks-banks-keep-vanke-loans-off-bad-debt-books-sources-say-2026-09-22/">China asks banks to keep Vanke loans off bad-debt books ...</a></li>
<li><a href="https://www.businesstimes.com.sg/property/china-asks-banks-keep-vanke-loans-bad-debt-books-sources-say">China asks banks to keep Vanke loans off bad-debt books ...</a></li>

</ul>
</details>

**标签**: `#China property`, `#Vanke`, `#bank regulation`, `#bad loans`, `#financial stability`

---

<a id="item-finance-news-2"></a>
### [中美贸易休战延长至 2027 年 1 月 10 日](https://www.cnbc.com/2026/09/24/us-china-trade-truce-bessent-trump-xi.html) ⭐️ 8.0/10

美国财政部长贝森特表示，美中已将贸易休战延长至 2027 年 1 月 10 日，原定于今年 11 月到期的安排得以延续，继续维持较低关税并保障稀土供应。贝森特称双方希望探讨达成更大规模的协议，而非一连串零散交易；中国驻美使馆尚未置评，中国官方媒体也未立即回应。

telegram · zaihuapd · 9月24日 00:31

**「背景」** 这一延长延续的是特朗普与习近平 2025 年 10 月在韩国达成的为期一年的贸易休战；据此前报道，美方当时把对华部分关税从 57%降至 47%，并缓和了围绕稀土出口管制的争端。该休战原定于 11 月到期，现延长至 2027 年 1 月 10 日。

**「影响」** 休战延期意味着美国进口商以及依赖中国稀土的制造商至少到 2027 年 1 月 10 日之前仍可按较低关税采购，并继续获得稀土供应，而不必在原先的 11 月到期日前后应对关税与关键原材料供应的变化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cfr.org/articles/united-states-and-china-agree-trade-truce">United States and China Agree to Trade Truce | Council on ...</a></li>
<li><a href="https://www.coface.com/news-economy-and-insights/us-china-trade-agreement-a-tactical-truce-not-a-strategic-shift">US-China tactical deal: Tariffs, tech, and rare earths | Coface</a></li>
<li><a href="https://www.cnbc.com/2025/10/30/trump-xi-south-korea-rare-earth-tariff-trade-war-nvidia.html">What Trump and Xi agreed to in the U.S.-China trade truce - CNBC</a></li>
<li><a href="https://www.scmp.com/news/china/diplomacy/article/3368318/rare-earths-friction-threatens-stall-trade-truce-extension-ahead-xi-trump-summit">Rare earths friction threatens to stall trade truce extension ahead of...</a></li>

</ul>
</details>

**标签**: `#US-China trade`, `#tariffs`, `#rare earths`, `#trade policy`, `#macroeconomy`

---

<a id="item-finance-news-3"></a>
### [特朗普与习近平会晤在即：企业界只求延长贸易休战](https://www.cnbc.com/2026/09/23/trump-xi-meeting-why-chinas-self-sufficiency-changes-the-calculus.html) ⭐️ 7.0/10

美国总统特朗普与中国国家主席习近平预计本周举行今年第二次面对面峰会，而企业界最期望的结果只是延长去年秋季达成的贸易休战，因为关税并未削弱美国对中国商品的需求。中国海关数据显示，今年 4 月贸易紧张升级曾一度把美国对华贸易逆差压至 2017 年以来最低水平，但今年以来 AI 相关零部件需求激增又将其推高。

rss · CNBC Finance · 9月23日 21:26

**「背景」** 中美上一轮贸易休战是在去年于韩国举行的会晤中达成的，此后双方紧张的经济关系有所稳定，而商界目前对本周峰会的最低期待只是延长这一休战。中国推动自给自足可追溯到 2015 年启动的“中国制造 2025”产业战略，该战略动员国家资源以降低在关键技术上对美国的依赖。

**「影响」** 若休战得以延长，依赖中美贸易的企业可暂时避免关税立即上调；与此同时，欧盟贸易委员谢夫乔维奇要求中国在 10 月前拿出贸易“实质成果”，并预计下月访问北京，显示欧盟正跟随美国加强对中国原产出口的审查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nytimes.com/2026/09/21/business/economy/trump-xi-china-trade.html">Trump and Xi Meet Amid an Uneasy U . S .- China Trade Truce - The...</a></li>
<li><a href="https://www.uscc.gov/research/made-china-2025-evaluating-chinas-performance">Made in China 2025: Evaluating China’s Performance</a></li>

</ul>
</details>

**标签**: `#US-China trade`, `#tariffs`, `#China economy`, `#AI exports`, `#self-sufficiency`

---