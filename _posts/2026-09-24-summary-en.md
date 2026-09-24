---
layout: default
title: "Horizon Summary: 2026-09-24 (EN)"
date: 2026-09-24
lang: en
---

> From 37 items, 8 important content pieces were selected

---

**Technology News**
1. [Anthropic says Claude agents autonomously found CRISPR-like ART enzyme system](#item-tech-news-1) ⭐️ 9.0/10
2. [Gemini 3.8 text-to-speech adds 30-second voice replication](#item-tech-news-2) ⭐️ 7.0/10
3. [Essay Argues LLM Token Costs Are Trending Toward Grep-Level Calls](#item-tech-news-3) ⭐️ 7.0/10
4. [Claude Code read AGENTS.md only when telemetry was on, fixed in v2.1.281](#item-tech-news-4) ⭐️ 7.0/10
5. [ShinyHunters claims FBI breach covering all employees and applicants](#item-tech-news-5) ⭐️ 7.0/10

**Financial News**
1. [China Said to Tell Banks to Keep Vanke&\#x27;s Overdue Loans Out of Bad-Debt Categories](#item-finance-news-1) ⭐️ 8.0/10
2. [US and China extend trade truce to January 10, 2027](#item-finance-news-2) ⭐️ 8.0/10
3. [Trump-Xi meeting expected as businesses seek trade truce extension](#item-finance-news-3) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Anthropic says Claude agents autonomously found CRISPR-like ART enzyme system](https://www.anthropic.com/news/claude-discovers-novel-enzyme-system) ⭐️ 9.0/10

Anthropic announced a new life sciences research team and laboratory and reported an early result: Claude agents, given only high-level instructions, autonomously identified a novel enzyme system with CRISPR-like features that is based on reverse transcriptase and found mainly in phages, named array-associated reverse transcriptase \(ART\). According to Anthropic, 950 agents ran for 21 hours and narrowed more than 200,000 reverse transcriptases down to candidates. The company says the system&\#x27;s function remains unknown, and it presents the finding as an early, vendor-reported example of AI-driven biological discovery rather than an established result; CRISPR researcher Feng Zhang framed it as an example of AI agents assisting biological discovery.

telegram · zaihuapd · Sep 24, 01:11

**「Background」** CRISPR systems are typically recognized by a long run of repeating DNA — a CRISPR array — next to a gene for an associated enzyme, and it was a similar repeat array beside a reverse-transcriptase gene that pointed toward the system Anthropic calls array-associated reverse-transcriptases, or ART. ART is reported to turn up mainly in bacteriophages. The finding is the first result from a molecular-biology group and Bay Area laboratory Anthropic launched this spring; the lab operates at BSL-1 and BSL-2 and handles no human pathogens, and the work was released as a preprint that has not been peer reviewed.

**「Limited near-term utility」** ART is an uncharacterized candidate rather than a usable tool: its function is still unknown and validation involved human lab work at Anthropic&\#x27;s new life-sciences lab, so researchers cannot yet substitute or compare it with CRISPR for gene editing. The more transferable element is the screening setup — roughly 950 Claude agents narrowing more than 200,000 reverse transcriptases in about 21 hours — though the available reports relay Anthropic&\#x27;s account without describing independent replication or an error rate for that pipeline.

<details><summary>References</summary>
<ul>
<li><a href="https://thenextweb.com/news/anthropic-claude-enzyme-system-crispr-like-repeats">Anthropic says Claude found a new enzyme system with CRISPR-like repeats</a></li>
<li><a href="https://www.investing.com/news/stock-market-news/anthropics-claude-finds-new-enzyme-system-4913724">Anthropic’s Claude finds new enzyme system By Investing.com</a></li>
<li><a href="https://www.technobezz.com/news/anthropic-claude-crispr-like-enzyme-system-art">Anthropic Says Claude Found a CRISPR-Like Enzyme System | Technobezz</a></li>
<li><a href="https://www.aitechdaily.com/anthropic-claude-art-enzyme-system/">Anthropic says Claude discovered ART enzyme system with ...</a></li>
<li><a href="https://www.reuters.com/business/healthcare-pharmaceuticals/anthropic-says-claude-ai-helped-discover-novel-enzyme-system-2026-09-23/">Anthropic says Claude AI helped discover novel enzyme system</a></li>
<li><a href="https://www.anthropic.com/news/claude-discovers-novel-enzyme-system">Claude discovers a novel enzyme system \ Anthropic</a></li>

</ul>
</details>

**Tags**: `#AI for science`, `#autonomous agents`, `#enzyme discovery`, `#CRISPR`, `#Anthropic`

---

<a id="item-tech-news-2"></a>
### [Gemini 3.8 text-to-speech adds 30-second voice replication](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-text-to-speech/) ⭐️ 7.0/10

Google announced Gemini 3.8 text-to-speech, which adds voice replication that can recreate consistent vocal profiles from a 30-second audio sample, according to the announcement quoted in Hacker News comments. The described safeguards include built-in consent verification, SynthID watermarking, and C2PA credentials. Commenters said availability and even capabilities differ across Google&\#x27;s consumer, prosumer, and cloud platforms, so what ships where is not uniform.

hackernews · swolpers · Sep 23, 15:29 · [Discussion](https://news.ycombinator.com/item?id=49817615)

**「Background」** Google&\#x27;s announcement covers two models, Gemini 3.8 Flash TTS and Gemini 3.8 Flash-Lite TTS, and frames them as a move away from static preset voices toward what the company calls a dynamic creative studio. A separate Google Cloud Text-to-Speech documentation page also describes Gemini-TTS voice replication, indicating the replication capability is exposed through the Cloud TTS surface in addition to the Gemini API and Google AI Studio, where the new models are available.

**「Impact」** For organizations that disable consumer and prosumer AI surfaces, the practical consequence is that access may depend on Google Cloud: one commenter said Google&\#x27;s three platforms often differ in model availability and capabilities, so a Gemini 3.8 TTS feature may not be reachable or may behave differently through the cloud API.

**「Community discussion」** Commenters split on novelty and governance: simonw said Google likely ships voice cloning now because it is widely available from other providers, while sharktheone contrasted this with Google&\#x27;s past reluctance to release a TTS model over abuse concerns. The most detailed complaint was about platform fragmentation, with rcr-anti saying the consumer, prosumer, and cloud platforms differ in availability and even capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-text-to-speech/">Gemini 3.8 Flash TTS and Gemini 3.8 Flash-Lite TTS - The Keyword</a></li>
<li><a href="https://docs.cloud.google.com/text-to-speech/docs/gemini-tts-voice-replication">Gemini-TTS voice replication | Cloud Text-to-Speech | Google ...</a></li>
<li><a href="https://www.latestly.com/technology/gemini-3-8-flash-tts-gemini-3-8-flash-lite-tts-introduced-by-google-with-custom-voice-design-and-synthid-watermarking-7617618.html">Gemini 3.8 Flash TTS, Gemini 3.8 Flash-Lite TTS ... - LatestLY</a></li>

</ul>
</details>

**Tags**: `#Gemini`, `#text-to-speech`, `#voice cloning`, `#Google AI`, `#AI safety`

---

<a id="item-tech-news-3"></a>
### [Essay Argues LLM Token Costs Are Trending Toward Grep-Level Calls](https://jyn.dev/tokens-too-cheap-to-meter/) ⭐️ 7.0/10

An essay titled “Tokens too cheap to meter” argues that LLM token pricing is trending toward calls that cost less than routine developer tool calls such as grep, according to the Hacker News discussion. A commenter summarizes the essay as observing that a GPT-5.6 Luna call is only 4–5 orders of magnitude more expensive than grep and predicting that at current rates of progress, LLM calls will soon be cheaper than grep. The item supplies no source text, so the essay’s underlying measurements and assumptions could not be independently checked here. HN commenters contest the projection’s economics, questioning both unbounded efficiency gains and the business models behind massive AI infrastructure spending.

hackernews · teoruiz · Sep 23, 09:21 · [Discussion](https://news.ycombinator.com/item?id=49813482)

**「Background」** LLM providers typically bill inference per token — a fragment of a word, about 1.5 tokens per English word — metering input and output tokens separately and pricing them per million; the essay&\#x27;s own example lists input at $0.042 per million tokens and output as free. That per-token meter is the unit that makes a comparison with a local utility such as grep meaningful, since grep carries no per-invocation charge. The essay&\#x27;s title also invokes the &quot;too cheap to meter&quot; phrase, which commenters trace to a 1954 promise about nuclear-generated electricity.

**「Cost-planning caveats」** Developers weighing whether to swap routine tool calls like grep for LLM calls face measurement problems before any cost decision: Artificial Analysis normalizes throughput metrics to OpenAI tokens while publishing prices in each model&\#x27;s native tokens, so cross-provider price charts are not directly comparable \(tool-3-2\). MIRI&\#x27;s review of inference pricing likewise warns that per-token prices vary so widely across providers that narrow datasets do not support strong conclusions about underlying costs \(tool-3-1\). A separate cost analysis argues falling per-token prices can still break budgets as usage expands \(tool-3-3\), so the essay&\#x27;s &quot;cheaper than grep&quot; trajectory is not yet a dependable basis for pushing LLM calls into routine developer workflows.

**「Community Discussion」** Commenters challenge the essay’s trajectory: jetrink invokes Stein’s Law to argue that efficiency improvements cannot continue forever, while cs702 says the essay underanalyzes business-model viability because infrastructure investors expect future profits to justify massive spending. abirch compares the “too cheap to meter” framing to Lewis Strauss’s 1954 nuclear-power promise and notes his own power bill was metered and large, illustrating the skepticism in the thread.

<details><summary>References</summary>
<ul>
<li><a href="https://jyn.dev/tokens-too-cheap-to-meter/">tokens too cheap to meter</a></li>
<li><a href="https://techgov.intelligence.org/blog/observations-about-llm-inference-pricing">Observations About LLM Inference Pricing | MIRI TGT</a></li>
<li><a href="https://artificialanalysis.ai/methodology">Artificial Analysis Benchmarking Methodology | Artificial Analysis</a></li>
<li><a href="https://www.ikangai.com/the-llm-cost-paradox-how-cheaper-ai-models-are-breaking-budgets/">The LLM Cost Paradox: How &quot;Cheaper&quot; AI Models Are Breaking Budgets</a></li>

</ul>
</details>

**Tags**: `#LLM inference costs`, `#AI economics`, `#developer tooling`, `#AI industry`, `#Hacker News discussion`

---

<a id="item-tech-news-4"></a>
### [Claude Code read AGENTS.md only when telemetry was on, fixed in v2.1.281](https://blog.szypowi.cz/p/claude-code-reads-agents.md-only-when-telemetry-is-on/) ⭐️ 7.0/10

Claude Code reportedly honored a project&\#x27;s AGENTS.md instructions only when telemetry was enabled, a bug the author of the linked post documented and that a maintainer in the discussion thread acknowledged as a rollout artifact. That maintainer said the feature sat behind a flag so it could be turned off remotely if it broke something, and that with telemetry disabled users never received the flag state; the comment states it is fixed in v2.1.281, described as releasing the same day. The fix and the explanation are vendor claims made in the thread rather than independently verified results, and no source document beyond the post itself was available.

hackernews · pszypowicz · Sep 23, 12:15 · [Discussion](https://news.ycombinator.com/item?id=49814947)

**「Background」** AGENTS.md is a vendor-neutral convention that several AI coding agents use for repository-level instructions, while Claude Code ships its own project-instruction file, CLAUDE.md. Because the two can coexist, Claude Code&\#x27;s default setting gives CLAUDE.md precedence; users who want both read must opt into the non-default \`claude-md-and-agents-md\` project-instructions setting.

**「What affected users should do」** Anyone who had telemetry disabled and relied on an AGENTS.md file was running without those project instructions until they update to v2.1.281, which restores the same behavior regardless of telemetry settings. Even after updating, AGENTS.md is only read in projects that have no CLAUDE.md unless the &quot;Project instructions&quot; setting is changed to \`claude-md-and-agents-md\`, and the release notes state that AGENTS.md support is not yet available on Bedrock, Vertex, or Foundry.

**「Community discussion」** Commenters added practical detail about how AGENTS.md is loaded: one reported that Claude Code ignores AGENTS.md by default whenever a CLAUDE.md exists, including a home-directory ~/CLAUDE.md, and that reading both requires changing the non-default &\#x27;Project instructions&\#x27; setting to claude-md-and-agents-md. Another said the tool now prints &\#x27;agents-md: no CLAUDE.md found; AGENTS.md loaded&\#x27; on every startup, while a third argued the defect resembles the kind of subtle failure introduced by accumulating AI-generated patches — an opinion, not a verified cause.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/anthropics/claude-code/releases">Releases · anthropics/claude-code - GitHub</a></li>

</ul>
</details>

**Tags**: `#claude-code`, `#ai-coding-agents`, `#telemetry`, `#feature-flags`, `#developer-tools`

---

<a id="item-tech-news-5"></a>
### [ShinyHunters claims FBI breach covering all employees and applicants](https://www.404media.co/we-hacked-the-fbi-hackers-say-they-have-data-on-all-fbi-employees/) ⭐️ 7.0/10

The hacking group ShinyHunters claims it breached multiple FBI-related services and stole data on all FBI employees and job applicants. According to 404 Media, the group provided a sample covering roughly 5,000 alleged FBI employees, with data that may include names, home addresses, phone numbers, and information about family members such as spouses. The FBI has not confirmed the claim, and the reporting provides no technical detail on how the alleged access was obtained. If the data is authentic, the exposed information could be used to track, harass, or threaten FBI personnel and their families.

telegram · zaihuapd · Sep 23, 05:00

**「Background」** ShinyHunters is an established data-theft and extortion group that has previously been linked to large corporate breaches, including a RingCentral incident noted in its Wikipedia entry. The target in this claim is FBIjobs.gov, the FBI&\#x27;s recruitment portal, which TechCrunch reported was displaying a &quot;currently down for maintenance&quot; notice and whose special-agent applicant portal was also down at the time of publication.

**「Impact」** Politico reports the FBI said it is investigating a possible breach of its online jobs portal, while Reuters reports the allegedly stolen data carries granular detail about officials&\#x27; job assignments, including sensitive counterintelligence work. For the roughly 5,000 employees and applicants in the reported sample, that means exposure extends beyond names and phone numbers to material usable for targeting or social engineering, though the bureau has not confirmed the claim.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ShinyHunters">ShinyHunters - Wikipedia</a></li>
<li><a href="https://techcrunch.com/2026/09/22/hacking-group-shinyhunters-claims-it-breached-the-fbi-stole-agents-and-applicants-data/">Hacking group ShinyHunters claims it breached the FBI, stole agents&#x27; and applicants&#x27; data | TechCrunch</a></li>
<li><a href="https://www.politico.com/news/2026/09/22/shinyhunters-fbi-cyber-hack-01088494">Cybercriminal group claims to steal thousands of FBI employee ...</a></li>
<li><a href="https://www.reuters.com/world/hacked-fbi-data-has-sensitive-information-about-employees-intelligence-roles-2026-09-23/">Hacked FBI data has sensitive information about employees ...</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#data-breach`, `#FBI`, `#ShinyHunters`, `#privacy`

---

## Financial News

<a id="item-finance-news-1"></a>
### [China Said to Tell Banks to Keep Vanke&\#x27;s Overdue Loans Out of Bad-Debt Categories](https://www.reuters.com/world/asia-pacific/china-asks-banks-keep-vanke-loans-off-bad-debt-books-sources-say-2026-09-22/) ⭐️ 8.0/10

Reuters reported, citing unnamed sources, that Chinese financial regulators asked some large banks not to classify China Vanke&\#x27;s overdue loans as non-performing, to extend repayment deadlines and to hold off collecting interest. Vanke, the report says, posted a record 88.6 billion yuan loss for 2025, with its first-half net loss widening to 14.95 billion yuan.

telegram · zaihuapd · Sep 23, 03:12

**「Background」** Vanke is one of China&\#x27;s largest residential developers, based in Shenzhen, where a state-owned firm is its largest shareholder and the local government holds significant influence over it. The reported forbearance follows a record 2025 net loss of 88.6 billion yuan \(about $12.9 billion\), 79% wider than the previous year, amid China&\#x27;s prolonged property downturn.

**「Impact」** If the guidance is followed, the large banks holding Vanke&\#x27;s overdue loans would delay the provisioning and lost interest that normally follow a bad-loan classification, keeping their reported asset quality higher than the underlying risk; Vanke, with total assets of close to 1 trillion yuan \(about US$149 billion\), would avoid a default that sources say could set off a chain reaction in the financial system.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vanke">Vanke - Wikipedia</a></li>
<li><a href="https://www.caixinglobal.com/2026-04-02/vanke-2025-net-loss-widens-79-to-13-billion-on-massive-impairments-102430048.html">Vanke 2025 Net Loss Widens 79% to $13 Billion on... - Caixin Global</a></li>
<li><a href="https://www.reuters.com/world/asia-pacific/china-asks-banks-keep-vanke-loans-off-bad-debt-books-sources-say-2026-09-22/">China asks banks to keep Vanke loans off bad-debt books ...</a></li>
<li><a href="https://www.businesstimes.com.sg/property/china-asks-banks-keep-vanke-loans-bad-debt-books-sources-say">China asks banks to keep Vanke loans off bad-debt books ...</a></li>
<li><a href="https://tradersunion.com/news/financial-news/show/3427743-china-vanke-loan-regulatory-support/">China regulators seek to keep Vanke loans from bad-debt ...</a></li>

</ul>
</details>

**Tags**: `#China property`, `#Vanke`, `#bank regulation`, `#bad loans`, `#financial stability`

---

<a id="item-finance-news-2"></a>
### [US and China extend trade truce to January 10, 2027](https://www.cnbc.com/2026/09/24/us-china-trade-truce-bessent-trump-xi.html) ⭐️ 8.0/10

US Treasury Secretary Scott Bessent said the US and China extended their trade truce to January 10, 2027, keeping tariffs lower and rare earth supplies flowing; the truce had been set to expire in November. Bessent, speaking on Fox News as Chinese President Xi Jinping arrived in Washington for a state visit, said Beijing still needs to fulfill more deliverables, and Chinese state media did not immediately report his comments.

telegram · zaihuapd · Sep 24, 00:31

**「Background」** The truce being extended dates to a meeting between President Donald Trump and President Xi Jinping in South Korea in October 2025, under which the US cut tariffs on Chinese exports from 57% to 47% and China eased rare-earth export restrictions, according to the Council on Foreign Relations. That agreement was originally due to expire in November before the extension announced by Treasury Secretary Scott Bessent.

**「Impact」** U.S. importers keep paying the truce&\#x27;s lower tariff rates, and manufacturers that depend on rare earth minerals for magnets, electronics and defense components keep receiving shipments — although U.S. Trade Representative Jamieson Greer has said China is still limiting rare earth exports, leaving that supply exposed if the truce lapses after January 10, 2027.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cfr.org/articles/united-states-and-china-agree-trade-truce">United States and China Agree to Trade Truce | Council on ...</a></li>
<li><a href="https://www.scmp.com/news/china/diplomacy/article/3368318/rare-earths-friction-threatens-stall-trade-truce-extension-ahead-xi-trump-summit">Rare earths friction threatens to stall trade truce extension ahead of...</a></li>

</ul>
</details>

**Tags**: `#US-China trade`, `#tariffs`, `#rare earths`, `#trade policy`, `#macroeconomy`

---

<a id="item-finance-news-3"></a>
### [Trump-Xi meeting expected as businesses seek trade truce extension](https://www.cnbc.com/2026/09/23/trump-xi-meeting-why-chinas-self-sufficiency-changes-the-calculus.html) ⭐️ 7.0/10

U.S. President Donald Trump and Chinese President Xi Jinping are expected to meet this week for their second in-person summit of the year, with businesses hoping for only an extension of the trade truce reached last fall, according to a CNBC analysis. The analysis says China&\#x27;s self-sufficiency push has reduced the threat to its domestic market from global trade developments, while the U.S. trade deficit with China briefly fell to its lowest level since 2017 in April after trade tensions escalated but rose again so far this year as demand for AI-related parts grew, according to China Customs data accessed through Wind Information.

rss · CNBC Finance · Sep 23, 21:26

**「Background」** The trade truce that businesses now hope to extend was struck at the two leaders&\#x27; earlier in-person meeting in South Korea about a year ago, when the relationship was threatening to spin out of control \[tool-1-1\]. China&\#x27;s push for self-sufficiency traces back to its &quot;Made in China 2025&quot; industrial strategy, which mobilized state resources and private enterprise behind domestic technology \[tool-2-2\].

<details><summary>References</summary>
<ul>
<li><a href="https://www.nytimes.com/2026/09/21/business/economy/trump-xi-china-trade.html">Trump and Xi Meet Amid an Uneasy U . S .- China Trade Truce - The...</a></li>
<li><a href="https://www.uscc.gov/research/made-china-2025-evaluating-chinas-performance">Made in China 2025: Evaluating China’s Performance</a></li>

</ul>
</details>

**Tags**: `#US-China trade`, `#tariffs`, `#China economy`, `#AI exports`, `#self-sufficiency`

---