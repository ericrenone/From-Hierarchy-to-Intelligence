# From Hierarchy to Intelligence: Jack Dorsey's Bet on the Post-Management Company

*How a one-line post about talking to AI agents turned, inside five months, into a corporate manifesto, a 40% layoff, and a working argument that the org chart itself is now optional.*

**The short version:** Jack Dorsey changed how he personally works with AI agents — from directing them to interviewing them — and then applied the same logic to all of Block. He and Sequoia partner Roelof Botha co-wrote a manifesto arguing that management hierarchy was never about authority, just an information-routing workaround for the limits of human attention, and that AI finally removes the limit. Weeks before the essay published, Block had already cut roughly 4,000 jobs, about 40% of its staff, to back the theory with a balance sheet. The stock jumped as much as 24%. The first earnings report afterward beat expectations. Employees, labor-law watchers, and a fair number of analysts remain unconvinced this is really about the AI. Below is the full arc — what was actually said and done, what happened next, and where it plausibly goes from here.

---

## The Personal Shift

The starting point is small and easy to miss: a single post on X in which Dorsey described how his own relationship to AI agents had changed. Rather than issuing instructions, he said he'd moved to "asking them what to do, and pulling the best thread" — treating a set of agents less like a command line and more like a standing panel of advisors, each pursuing a different angle, with a human still choosing which thread to follow. Digg's write-up of the post captured a split reaction: some readers framed it as a genuine upgrade from micromanaging agents to using them for discovery, others worried that handing agents the framing of a problem, not just its execution, quietly moves judgment away from the human in the loop. It was a minor moment as these things go — a few hundred accounts weighing in — but it's the cleanest one-line summary of the operating philosophy Dorsey would spend the next few months rolling out at company scale.

## The Manifesto: From Hierarchy to Intelligence

On March 31, 2026, Dorsey and Roelof Botha — a Sequoia Capital partner who also sits on Block's board as lead independent director — published a joint essay under that title, posted simultaneously on Block's site and Sequoia's. Its argument runs through roughly two thousand years of organizational history in a hurry: the Roman legion's nested units of eight, eighty, and five thousand, built around the discovery that one leader can only really manage a handful of people directly; the Prussian General Staff, assembled after the 1806 defeat at Jena to substitute a trained bureaucracy for battlefield genius, which is essentially where the concept of middle management was born; the American railroads of the 1850s, which imported that military vocabulary and produced, in Daniel McCallum's 1855 diagram for the New York & Erie line, something close to the first modern org chart; Frederick Taylor's scientific management; the deliberately cross-functional teams Robert Oppenheimer ran at Los Alamos; McKinsey's matrix organization; and the more recent, more familiar flirtations with flatness at Spotify, Zappos, and Valve, each of which drifted back toward hierarchy once it scaled past a few hundred people. The throughline Dorsey and Botha draw isn't that hierarchy was a bad idea — it's that hierarchy was always a routing protocol for information, constrained by how much context one human brain can hold. Their claim is that this specific constraint, not management in general, is the thing AI removes for the first time.

What replaces it, in their telling, is a company built around four pieces:

- **Capabilities** — the atomic building blocks (payments, lending, card issuance, banking, buy-now-pay-later, payroll) that have no interface of their own and exist purely to be composed into something else.
- **A world model** — really two linked models: one tracking the company's own state (what's being built, what's blocked, where resources sit) built from the fact that a remote-first company's work is already machine-readable; the other tracking customer and merchant behavior from real transaction data, on the theory that what people actually spend, save, and borrow is a far more honest signal than what they say in a survey.
- **An intelligence layer** — the "mini-AGI" itself, which composes capabilities into a solution for a specific person at a specific moment, sometimes before anyone thinks to ask for it.
- **Interfaces** — the surfaces people actually touch, in Block's case Square, Cash App, Afterpay, TIDAL, Bitkey, and Proto. Useful, but explicitly framed in the essay as not where the value lives.

The org chart that falls out of this is closer to a wheel than a pyramid — a shape Dorsey has taken to sketching for interviewers as a circle with the model in the center and everyone else on the rim:

```
   THE OLD SHAPE                    THE PROPOSED SHAPE

        CEO                             IC        IC
       /    \                             \       /
     VP      VP                    IC —— intelligence —— DRI
    /  \    /  \                             /       \
  IC   IC  IC   IC                     coach          IC

  info climbs and descends          everyone works the edge;
  through management layers          the model handles the middle
```

"The edge is where the action is," as the essay puts it — people exist at the boundary where the model runs out, handling intuition, cultural context, and the ethically weighted calls a system shouldn't make on its own. In practice, Block is normalizing down to three roles: **Individual Contributors**, who build and operate a specific layer of the system with the world model supplying the context a manager used to; **Directly Responsible Individuals**, who own a specific cross-cutting outcome — Dorsey's example is merchant churn in one segment — typically on a 90-day cycle, with standing authority to pull people from other teams; and **player-coaches**, who keep building or designing themselves while also mentoring, absorbing what's left of the old manager's job once the information-routing part of it is gone.

Dorsey has said publicly, including at a JPMorgan investor conference, that Block currently sits about five reporting layers deep and that he wants to reach two or three by the end of the year — with an admitted "ideal case," floated on Sequoia's own podcast, in which all roughly 6,000 remaining employees report through the intelligence layer directly to him.

## The Cut

The essay didn't arrive out of nowhere. On February 26, 2026, tied to its fourth-quarter earnings, Block announced it was cutting its workforce by about 40% — a little over 4,000 people, from roughly 10,200 down to just under 6,000 — and pinned the reason squarely on what Dorsey called "intelligence tools." In the note to staff, he wrote that a markedly leaner team, using those tools, "can do more and do it better," and argued the underlying capability was compounding too quickly to ignore. Rather than trimming gradually over months, he said he'd chosen one deep cut over repeated rounds, reasoning that serial layoffs do more lasting damage to morale and trust than a single large one. Affected employees received twenty weeks of severance plus a week per year of tenure, equity vesting through the end of May, six months of health coverage, and $5,000 in transition support. It wasn't Block's first AI-adjacent trim — a smaller round cut roughly 900 to 1,000 jobs back in March 2025 — but it was, by a wide margin, the boldest: one of the largest single-day workforce reductions in S&P 500 history explicitly attributed to AI. Markets responded immediately, sending the stock up as much as 24% in the following days.

Block wasn't alone in reaching for that explanation. Cloudflare cut about 20% of staff citing an "agentic AI-first operating model"; Coinbase cut 14%; Pinterest, CrowdStrike, and Chegg all announced AI-linked reductions around the same period; Klarna had already been trimming customer-service headcount through automation for two years. Not everyone followed the pattern — Affirm's CEO Max Levchin said explicitly his company had no AI-driven layoffs planned — but the broader backdrop was one of real anxiety: Microsoft's Mustafa Suleyman warned white-collar workers might have twelve to eighteen months before serious displacement, Andrew Yang and JPMorgan's Jamie Dimon voiced similar concern, and U.S. firms had already announced over 48,000 job cuts in February alone.

## The Receipts

The first real test of whether the theory held came with Block's Q1 2026 results in early May.

| Metric | Figure |
|---|---|
| Headcount | ~10,200 → ~6,000 |
| Adjusted diluted EPS growth (YoY) | +51.8% |
| Full-year adjusted EPS guidance | raised from $3.66 to $3.85 (~62% YoY target) |
| Q1 gross profit | $2.91B (+26–27% YoY) |
| Adjusted operating income | $728M (+56% YoY) |
| Adjusted EBITDA | $1B, an all-time high |
| Net income | –$309M, on an $852M restructuring/legal charge |
| Stock reaction to the layoff announcement | as much as +24% |

Cash App's gross profit grew 38% to $1.9 billion on the back of an 82% jump in consumer lending volume; Square's gross payment volume rose 13% to $61.2 billion; Block said 100% of employees were now using its AI tools and that production code changes per engineer had risen 2.5 times. Wall Street's read was mixed rather than uniformly bullish — RBC, Needham, and Citi all raised price targets and kept "buy"-equivalent ratings, while Piper Sandler kept an "underweight" stance even as it nudged its own target up, flagging doubts about whether the margin gains would hold. Block itself said the restructuring costs would be largely finished by the end of June, making the next couple of quarters the more revealing checkpoint.

## The Open Counter-Bet: Goose and the Anti-Gatekeeper Play

Running alongside the hierarchy story is a second, older thread in Dorsey's thinking: a consistent preference for open protocols over closed platforms, which by 2026 has become the connective tissue across most of what he funds. Block's open-source AI agent framework, Goose, launched in January 2025 out of Block's Open Source Program Office, days after DeepSeek's R1 release reignited the open-versus-closed AI debate; it's Apache 2.0 licensed, built to work with Anthropic's Model Context Protocol, and designed so developers can plug in whichever model they want rather than being locked to one vendor. In April 2026, Goose was folded into the Agentic AI Foundation, an open-governance project hosted by the Linux Foundation — a deliberate step away from being "Block's tool" toward being neutral infrastructure. Internally, it already runs Block's "BuilderBot," which handles more than 200,000 AI operations a day and merges roughly 1,500 pull requests a week, on the order of 15% of all the company's code changes. Most recently, Spiral — Dorsey's independent, Block-funded open-source Bitcoin outfit, formerly Square Crypto — brought on Goose's core engineering team to grow it into a larger, more independent agent platform outside Block's own walls entirely.

None of this is a new instinct for Dorsey so much as a recurring one. He resigned as Twitter's CEO in 2021 arguing that "severely limiting and a single point of failure" was exactly what a founder-led company risked being. He backed Bluesky as a decentralized alternative to the platform he'd built, though he left its board in 2024 over disagreements about its direction. In 2025 he shipped Bitchat, a messaging app that routes around the internet entirely using Bluetooth mesh networking. Goose, and the broader argument that agentic AI shouldn't be "owned by a handful of large model providers," reads as the same thesis applied to a new layer of the stack.

## The Pushback

Not everyone buys the framing, and the skepticism comes from several directions at once.

Inside Block, the picture reported by current and former employees is rougher than the earnings call. Workers describe morale as the worst in years, AI fluency now folded into performance reviews, and a running requirement to send Dorsey a weekly email listing five recent accomplishments — which he then has AI summarize, an arrangement more than one worker has compared to Elon Musk's brief DOGE-era reporting requirements. One employee who left after the February cuts, offered nearly double pay to stay, told the Guardian it felt dystopian to be handed "the very tools that accelerate the disappearance of the jobs" her colleagues depended on.

Outside the building, HR analyst Josh Bersin has openly questioned whether this is a genuine bellwether or simply, as he put it, AI serving as a convenient excuse to clean up an org chart — drawing a direct parallel to how much slack Elon Musk found in Twitter's structure once he took over. Forbes contributor Ron Shevlin has made a sharper version of the same case: Block's headcount had already grown two-and-a-half times between 2019 and 2025, so a large chunk of the "AI-driven" cut may just be reversing an earlier hiring binge, and he's flagged genuine exposure under the WARN Act and tighter EU and Australian labor rules, plus the operational risk of running payment-critical systems on a much thinner bench. Writer Moore Dagogo-Hart has pushed back on the philosophy itself, arguing that people were rarely the routing bottleneck to begin with — that badly designed structures were — and that removing humans on the assumption that their main job was moving information around risks removing intelligence rather than adding it. All of this sits against a regulatory backdrop that has nothing to do with AI: a California federal judge ruled in January 2026 that Block's board must face claims it failed to properly oversee compliance, and on July 8, 2026, Block agreed to pay $45 million across 46 states over how Cash App handled fraud complaints. Even Mark Cuban has weighed in from the sidelines, arguing flatly that "it still acts like a hungover college intern" and won't be taking anyone's job just yet — and OpenAI's Sam Altman himself has cautioned that some companies are simply "AI-washing" ordinary cost-cutting.

## What This Means

Pulling the verified threads together, a few things seem more likely than not over the next several quarters:

1. **The manifesto turns into a template long before anyone proves it works.** Three-role taxonomies travel well at conferences regardless of their track record — OKRs and "squads" both made the same trip. Expect the IC/DRI/player-coach language, or something that rhymes with it, to show up rebranded at other companies inside a year, alongside looser invocations of "world models" and "intelligence layers" that have little of Block's underlying data behind them.

2. **"AI-attributed layoffs" becomes a category companies chase and get punished for in the same breath.** The market rewarded Block's framing immediately and has kept doing so through Q1. That's a strong incentive for other CEOs to describe ordinary cost-cutting the same way — and an equally strong incentive for regulators, plaintiffs' lawyers, and skeptical reporters to start testing whether the AI justification is real or just better optics than "we overhired."

3. **The more interesting tension isn't AI versus people — it's centralization versus Dorsey's own record.** This is a person who has spent two decades betting on decentralized, permissionless infrastructure — Bitcoin, Bluesky, Bitchat, and now Goose — precisely because he distrusts concentrated control. The "ideal case" he's floated for Block, though, is close to the most centralized reporting structure imaginable: every employee routed through one AI layer to one person. Whether that's read as a contradiction or a clever synthesis will probably depend more on how Block performs than on the argument itself.

4. **Compliance, not the model, is the real stress test.** Block is a bank-adjacent company that just took an $852 million charge, is defending a board-oversight suit, and settled a $45 million fraud-handling case with 46 states — all while removing 40% of the people who traditionally absorb operational and regulatory risk. The next two or three quarters will show whether a much leaner Block can still pass an exam, avoid a payments outage, and handle disputes at the same trust level, which is a very different question from whether an intelligence layer can draft a loan offer.

5. **Wall Street and the newsroom will keep telling two different stories about the same company.** Strong EPS growth and raised guidance on one side; "worst morale in years" and mandatory AI-usage reviews on the other. Expect this split-screen coverage pattern — bullish earnings call, unhappy internal accounts — to become the default shape of every subsequent "AI-native restructuring" story in the sector, not just Block's.

6. **Goose's credibility now hinges on Block visibly not needing it to win.** Handing the core team to the independent Spiral project and folding governance into the Linux Foundation are the right moves if Goose is meant to be genuinely neutral infrastructure. If it quietly stays a Block-flavored tool with an open license, it won't do the "no gatekeepers" work Dorsey wants; if the independence is real, it has a plausible shot at becoming shared plumbing for other companies' world-model ambitions the way MCP already has for tool-calling.

7. **This keeps surfacing in the AI-and-jobs policy conversation, on its own terms.** Four thousand-plus jobs, an explicit AI attribution from the CEO, WARN Act and EU exposure, and UBI mentions already showing up in the public reaction make Block a clean, citable case study — expect it to keep appearing in hearings, think-tank reports, and campaign rhetoric over the next year regardless of how the restructuring actually performs financially.

## Signals Worth Watching

- Whether Block actually reaches its stated two-to-three-layer target by the end of 2026, or quietly slips the timeline.
- Q2 and Q3 2026 results, and whether the restructuring charges taper off as promised by end of June.
- Whether any other named S&P 500 or Fortune 500 company explicitly cites "From Hierarchy to Intelligence" or adopts the IC/DRI/player-coach language rather than just doing its own AI-linked layoff.
- Adoption metrics for Goose once it operates at greater distance from Block through Spiral and the Agentic AI Foundation.
- How the WARN Act exposure and the board-oversight litigation resolve.
- Any customer-facing service disruption, new enforcement action, or compliance failure at Block, which critics will read as proof the "AI story" was cover for cost-cutting.
- Whether Dorsey's "ideal case" — everyone reporting through the intelligence layer to him directly — moves from aspiration to something Block actually implements.

---

## Further Reading

- Block & Roelof Botha, ["From Hierarchy to Intelligence"](https://block.xyz/inside/from-hierarchy-to-intelligence)
- Sequoia Capital, ["Jack Dorsey: Every Company Can Now Be a Mini-AGI"](https://sequoiacap.com/podcast/jack-dorsey-every-company-can-now-be-a-mini-agi/) (podcast)
- CNBC, ["Block shares soar as much as 24% as company slashes workforce by nearly half"](https://www.cnbc.com/2026/02/26/block-laying-off-about-4000-employees-nearly-half-of-its-workforce.html)
- CNN Business, ["Block lays off nearly half its staff because of AI"](https://www.cnn.com/2026/02/26/business/block-layoffs-ai-jack-dorsey)
- Newsweek, ["Read Jack Dorsey's Full Statement As He Lays Off Thousands of Workers"](https://www.newsweek.com/read-jack-dorseys-full-statement-block-layoffs-11590862)
- Fortune, ["Twitter cofounder Jack Dorsey breaks down his thought process"](https://fortune.com/2026/04/17/twitter-cofounder-block-ceo-jack-dorsey-thought-process-laid-off-40-staff-ai/)
- Forbes / Ron Shevlin, ["Block Lays Off 40% Of Staff And Blames It On AI. Don't Buy The Excuse."](https://www.forbes.com/sites/ronshevlin/2026/02/27/block-lays-off-40-of-staff-and-blames-it-on-ai-dont-buy-the-excuse/)
- Josh Bersin, ["Is Block's Decision To Layoff 40% of Its Workforce A Bellwether Or Not?"](https://joshbersin.com/2026/03/is-blocks-decision-to-layoff-40-of-its-workforce-a-bellwether-or-not/)
- Cybernews, ["Block staff push back after Jack Dorsey says AI behind mass layoffs"](https://cybernews.com/ai-news/block-layoffs-jack-dorsey/)
- Moore Dagogo-Hart, ["From Hierarchy to Intelligence: A Different Path"](https://medium.com/@mooredh99/from-hierarchy-to-intelligence-a-different-path-338bbb2df365)
- VentureBeat, ["Jack Dorsey is back with Goose"](https://venturebeat.com/programming-development/jack-dorsey-is-back-with-goose-a-new-ultra-simple-open-source-ai-agent-building-platform-from-his-startup-block)
- Coin Edition, ["Jack Dorsey's Spiral Expands Into AI With Goose Team"](https://coinedition.com/jack-dorseys-spiral-expands-into-ai-with-goose-team/)
- Forbes, ["Jack Dorsey's Block To Pay $45 Million Fine As States Step In For Withering CFPB"](https://www.forbes.com/sites/jeffkauflin/2026/07/08/jack-dorseys-block-to-pay-45-million-fine-as-states-step-in-for-withering-cfpb/)
