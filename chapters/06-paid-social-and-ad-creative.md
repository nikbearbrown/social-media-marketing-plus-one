# Chapter 6 — Paid Social & Ad Creative

*Copy variation, targeting, A/B testing, bid optimization vs. brand voice, audience context, what crosses a line*

---

In January 1984, Apple's agency commissioned standard recall testing on the "1984" spot before it aired. The scores came back poor. The ad was too dark, too cinematic, too remote from any product demonstration. The Apple board reportedly recommended killing the Super Bowl buy. Steve Jobs and the team overruled them. The ad ran, the Macintosh launched two days later, and the spot has held a place near the top of every "greatest ad of all time" list for four decades.

What is interesting about this case is not that Apple was right. They might have been wrong. What is interesting is the *structure* of the decision. There was no data underwriting it. An A/B testing protocol would have killed it. An AI bid-management system, fed the early recall scores, would have throttled it back. The bet was a human bet, made by people with enough brand context and enough authority to accept being wrong.

Now put the Pepsi Kendall Jenner ad next to it. April 2017. Pulled within twenty-four hours after sustained public backlash for trivializing the imagery and language of the Black Lives Matter movement. Nothing in the creative tripped any standard safety filter. No slur, no profanity, no obviously unsafe placement. The failure was on a dimension the testing frame did not cover — the cultural-political read of how that specific imagery would land with that specific audience at that specific moment in 2017. Pepsi had the same testing capability as every other major advertiser. The capability did not catch it. It could not, because what needed to be caught was not a content violation but a contextual read.

These two cases bracket everything that follows. AI tools handle the testable. Brand judgment handles the bet. The chapter is about not confusing them.

---

## What AI can actually do here

The Delegate List in paid social is large and, unlike some task families, the gains are genuine and documented. Automated bidding has outperformed manual bidding for direct-response goals since roughly 2018. Producing two hundred headline variants from a single approved concept now costs nothing. Audience expansion through lookalike modeling, retargeting pool maintenance, and interest-graph extension is mechanical work that scales without degradation. Budget pacing, frequency capping, placement optimization across formats and platforms — all of it executes reliably and saves real time.

The full-stack auto-campaign tier — Meta Advantage+, Google Performance Max, TikTok Smart Performance Campaigns, their equivalents — is worth treating seriously rather than dismissively. These tools genuinely produce better measured cost-per-result for direct-response goals than manually-tuned campaigns. Meta has published joint research with NielsenIQ through 2023–2024 supporting this [verify]. The practitioner reflex to resist platform automation is, in most cases, a defense of the time they used to spend on work that the automation does better.

| Task | Why pattern-shaped | Recommended AI tool category | Time saved | Quality risk if skipped |
| --- | --- | --- | --- | --- |
| Creative variation (headline, hook, body, crop) | Combinatorial expansion of a fixed concept | Generative creative inside ad platform suite | Hours per campaign | None — variation without a concept is the failure mode |
| A/B and multivariate test execution | Statistical bookkeeping over many cells | Native platform experiment tool | Days per cycle | Underpowered tests still possible — set MDE manually |
| Audience expansion (lookalikes, retargeting pools) | Similarity modeling at scale | Platform audience tools | Days per quarter | Erosion of new-audience reach if left unattended |
| Automated bidding (direct-response goals) | Real-time optimization at clock speed humans cannot match | Platform bid manager (Advantage+, PMax) | Weeks of analyst time | None below saturation; brand effects invisible |
| Full-stack auto-campaign tier | Bundled targeting + creative + placement + bidding | Meta Advantage+, Google PMax, TikTok SPC | Setup time, ongoing tuning | Opaque incrementality; brand drift |
| Placement optimization across formats | Per-impression decisioning | Native cross-placement engine | Continuous | Minor — frequency capping still required |
| Budget pacing and frequency capping | Mechanical pacing math | Platform pacing tools | Hours per week | Burnouts and audience fatigue if absent |
| Performance reporting and dashboarding | Aggregation and visualization over a fixed schema | Reporting/BI tool of choice | Days per month | Spot-check denominators monthly |
| AI-generated creative from approved brief | Constrained text/image generation from a brief | Adobe Firefly, Meta/Google generative ad tools | Hours per variant | High if no concept upstream — see Guard list |
| Policy-error triage and rejection appeals | Pattern-matching rule violations to remedies | Platform policy assistants | Hours per incident | Minor — appeal escalations still need a human voice |

*Figure 6.1 — Delegate list for paid social: ten pattern-shaped tasks, the tool category, the cost saved, and the quality risk if delegated without spot-check.*

<!-- → [TABLE: Delegate List for paid social — rows covering creative variation, A/B test execution, audience expansion, automated bidding, full-stack auto-campaigns, placement optimization, budget pacing, performance reporting, AI-generated creative from brief, policy-error triage — five columns: Task / Why pattern-shaped / Recommended AI tool category / Time saved / Quality risk if skipped] -->

But there are three qualifications that matter, and none of them show up in the dashboard.

First, the auto-campaign optimizes for the metric you specified. The metric you specified is not the same as the brand outcome you want. If you specified cost-per-acquisition, the system will minimize cost-per-acquisition. The effect on brand-search-volume next quarter is not in the system's loss function.

Second, the measurement of "winning" conflates touched with caused. Lewis and Rao demonstrated in 2015, in the *Quarterly Journal of Economics*, that measuring incremental lift requires statistical power most campaigns cannot achieve. Blake, Nosko, and Tadelis showed the same year, in *Econometrica*, that eBay's paid search spend was largely cannibalizing organic traffic — the "winning" variants were winning against a counterfactual the measurement system could not see. The AI-reported winner is a measured-lift winner. Whether it produced incremental lift is a separate question the dashboard cannot answer.

Third, the auto-campaign commoditizes the optimization layer. Every competitor with the same budget has access to the same tools. The differentiator that remains at the strategic layer is the brand judgment that goes into the brief before the auto-campaign touches it.

---

## What AI cannot do here

The concept is the bet. Ogilvy's claim in *Ogilvy on Advertising* — that the headline is roughly 80% of the work — points at the same thing Bernbach understood when he wrote "Think Small" for Volkswagen in the late 1950s. The headline has to be guessed into existence and then tested. AI multiplexes variations of a concept; the concept itself is a human call about what to say and whether to say it in this moment. Apple "1984," Dove "Real Beauty Sketches" (2013), Old Spice "The Man Your Man Could Smell Like" (2010) — each was a creative decision no scoring system would have surfaced. The role of the practitioner is to recognize the bet, sponsor it, and accept the downside if it fails.

Brand safety on cultural-political dimensions is a different kind of Guard item than most. AI flags slurs, profanity, and obvious unsafe placements. AI does not flag the ad that is technically clean but reads tone-deaf because of something that happened in the news cycle yesterday afternoon. Pepsi/Kendall Jenner was not blocked by any safety system. The Balenciaga campaign incident in late 2022 cleared multiple review steps and still produced a brand-equity collapse. What needed to be caught in both cases was not a content violation but a contextual read — and that read requires someone who knows what the audience has been through recently.

| Task | Why judgment-shaped | What goes wrong if delegated | Required human role | Escalation trigger |
| --- | --- | --- | --- | --- |
| Creative concept (the bet) | A guess about what to say at this moment | Convergence to category median | Senior creative + brand lead | Always — concept is never auto-served |
| Choice of which creative bet to sponsor | Backing one direction against alternatives | Risk-averse, regression-to-the-mean choices | Brand lead with authority to accept downside | Before production starts |
| Cultural-political brand safety | Contextual read of audience moment | Pepsi/Jenner, Balenciaga-class failures | Practitioner with cultural fluency in target audience | Within 72 hours of any news event in adjacent territory |
| Audience-context call | Relationship state matters: aware vs. cold | Aggressive lookalikes dilute a deepening strategy | Brand lead + media planner | When auto-campaign proposes audience expansion |
| Long-term vs. short-term allocation (60/40) | Mental availability is built across years | Activation-only spend erodes brand growth | CMO / brand owner | At budget cycle and quarterly review |
| "What crosses a line" for this brand | Brand-specific lines no model knows | Compliance-grade safety, brand-grade harm | Brand lead | Pre-production and at any new creative direction |
| Creator-relationship judgment | Trust, voice, drift over time | Creators treated as media inventory | Relationship owner | Before contracting, at renewal |
| Metric selection upstream of optimization | What "winning" means for the business | Optimization against the wrong target | Marketing leadership | At campaign planning |
| Incrementality assessment | Touched is not caused | Over-credit to platform; cannibalized organic | Analyst with stats training | Quarterly and at any major spend reallocation |
| Pause-during-crisis decision | A pre-scheduled ad lands inside a news cycle | Cheapest brand-equity loss available | On-call brand lead | Any unplanned news event |

*Figure 6.2 — Guard list for paid social: ten judgment-shaped tasks, the failure mode if delegated, and the escalation trigger.*

<!-- → [TABLE: Guard List for paid social — rows covering creative concept, choice of creative bet, cultural-political brand safety, audience-context call, long-term vs. short-term allocation, "what crosses a line" for this brand, creator relationship judgment, metric selection upstream of optimization, incrementality assessment, pause-during-crisis decision — five columns: Task / Why judgment-shaped / What goes wrong if delegated / Required human role / Escalation trigger] -->

The long-term versus short-term allocation is the Guard item with the most empirical support. Binet and Field's *The Long and the Short of It*, published by the IPA in 2013, documented that healthy brands invest roughly 60% of communications budgets in long-term brand-building and 40% in short-term activation. AI-optimized paid social maximizes the short-term metric by default — that is what it is designed to do. The 60/40 allocation is a human decision with rigorous backing that the auto-campaign has no mechanism to enforce. Field's 2019 follow-up, *The Crisis in Creative Effectiveness*, documented that creative effectiveness as measured by the IPA's database declined as targeting precision rose. The mechanism predates large language models. It applies directly to them.

The metric upstream of the metric is related but distinct. Choosing what "winning" actually means for this brand over the next eighteen months is the consequential call. Marc Pritchard at P&G publicly walked back precision targeting in 2017 and 2019 [verify, Ad Age coverage] on the grounds that it produced fraud, opacity, and worse brand outcomes than broader reach buys. Adidas's CMO Simon Peel acknowledged in 2019 that the company had over-attributed sales to performance marketing for roughly a decade and had stalled brand growth in the process [verify, Marketing Week]. The AI optimizes whichever metric you specify. The choice of metric is yours.

---

## The brief is the only place the brand judgment goes in

The practitioner who understands the structure of paid social in 2026 understands that the auto-campaign tier is real, the creative variation tools are real, and the optimization infrastructure is competent. The question is not whether to use these tools — the question is what to put into them and what to keep out.

The brief is where the answer lives.

Here is what an AI-generated brief looks like when it has not been given a real strategic premise:

*Objective: drive consideration and conversion for the Spring product line. Target audience: women 25–44 with interest in skincare and wellness. Key messages: clean ingredients, dermatologist-approved, customer-loved. Creative direction: bright, inviting, social-proof-forward. Success metric: cost per acquisition under $X.*

This brief is fluent. It is also unreadable as strategy. It could describe any skincare brand in the current market. It contains no bet, no tension, no constraint that would distinguish this campaign from the median of everything else the auto-campaign tier has seen.

Here is what the same brief looks like when a practitioner has done the upstream judgment work:

*Objective: protect the Spring launch from cannibalizing the brand position we built in 2024 around "slow beauty, not fast routines." Target: brand-aware audience first, expansion second — aggressive lookalikes are off the table this quarter because we want to deepen rather than dilute. Key tension: the Spring line has a higher AOV and our current creative cues quietness — we need ads that earn attention without shouting. Creative direction: keep it editorial; do not use the bright/inviting performance-creative template our competitors are flooding the feed with. Lines we won't cross: no skin-condition before-after, no influencer language approaching medical claims, no ads served within 48 hours of any wellness-industry news cycle event. Success metric: blended view of CPA, brand-search-volume, and share-of-voice; we will not optimize for CPA alone this quarter.*

The second brief names a bet. It contains constraints that could not have been inferred from category best practices. It will produce a different campaign than any other brief the auto-campaign tier has processed, because it contains context the auto-campaign cannot generate.

| Brief element | AI-generated version | Practitioner version |
| --- | --- | --- |
| Objective | Drive consideration and conversion for the Spring product line. | Protect the Spring launch from cannibalizing the brand position we built in 2024 around "slow beauty, not fast routines." |
| Target audience | Women 25–44 with interest in skincare and wellness. | Brand-aware audience first, expansion second — aggressive lookalikes are off the table this quarter; we want to deepen, not dilute. |
| Key tension | (None named.) | Spring line has a higher AOV; current creative cues quietness. We need ads that earn attention without shouting. |
| Creative direction | Bright, inviting, social-proof-forward. | Editorial register; do not use the bright/inviting performance template our competitors are flooding the feed with. |
| Lines not to cross | (Not specified.) | No before-after skin-condition imagery; no influencer language approaching medical claims; no ads served within 48h of any wellness-industry news event. |
| Success metric | Cost per acquisition under $X. | Blended view: CPA, brand-search-volume, share-of-voice. We will not optimize for CPA alone this quarter. |

*Figure 6.3 — AI-generated brief vs. practitioner brief: where the strategic content lives, and where the auto-generated version is empty.*

<!-- → [TABLE: Side-by-side comparison — AI-generated brief vs. practitioner-written brief — columns: Brief element / AI-generated version / Practitioner version — rows covering objective, audience, creative direction, lines not to cross, success metric — student should see where the strategic content lives and where the auto-generated version is empty] -->

The campaign log is the other piece. When a concept works — or fails — the reasoning that went into the bet should be documented. Not the metrics. The reasoning. The metrics are in the dashboard. The reasoning is what makes the next bet better.

---

## The AI-vs-AI loop

There is a failure mode in paid social that is harder to name than the obvious ones. Call it the AI-vs-AI loop: generative creative, optimized by AI media buying, served to AI-modeled audiences, measured by AI attribution. Each layer is competent. The loop produces fluent, optimized, brand-shallow output that performs on the dashboard and erodes the brand on the time horizon the dashboard does not cover.

The way the loop produces this outcome is not through error. It is through the absence of constraint. The generative creative converges toward the median of the training data, which is the median of every other brand's advertising. The media buying optimizes against whoever converts most reliably, which is the existing customer base, which is the audience the brand already has. The attribution system counts the conversions it touches and reports a winner. The entire cycle is technically correct and strategically circular.

![Circular diagram showing four AI layers — generative creative, AI media buying, AI-modeled audiences, AI attribution — connected by clockwise arrows, with ochre markers at each transition labelling what drops out (concept, new-audience reach, brand signal, incrementality). A central red brief node connects to all four layers with dashed radial arrows, marking the only human intervention points.](../images/06-paid-social-and-ad-creative-fig-01.png)

*Figure 6.4 — The AI-vs-AI loop: competent at each step, brand-shallow as a whole.*

<!-- → [INFOGRAPHIC: The AI-vs-AI loop — circular diagram showing generative creative → AI media buying → AI-modeled audiences → AI attribution → back to creative brief — with four annotation points showing what drops out at each step: concept/bet, new audience acquisition, brand-building signal, incrementality] -->

Byron Sharp's *How Brands Grow* (2010) argued for broad reach over precision targeting years before privacy changes forced the issue. The argument is that mental availability — the probability that a brand comes to mind in a purchase situation — is built through reach, not frequency with existing converters. The AI-optimized campaign serves the existing converter pool efficiently and underspends on the people who have never heard of the brand. The efficiency is real. The strategic problem is also real.

The competence required to interrupt this loop at the right moment — the brief, the concept, the brand-safety review, the quarterly brand-metric check — is now the central paid social skill. It is not the skill that shows up in most platform certifications. It is the skill that explains why some brands grow their category share under conditions of identical tool access.

---

## Building your paid social framework

The protocol that follows is not a checklist of tasks. It is a sequence for locating where the judgment work actually sits in a paid social campaign cycle.

Write the brief yourself, before any model touches the work. Name the audience, the strategic objective distinct from the optimization metric, the brand voice constraints, the cultural moments the campaign window overlaps with, and the lines the campaign may not cross. A page, not more, but a page that names the bet.

Use AI for the brief's mechanical sections: competitive scan, audience demographic summaries, format performance benchmarks, recent platform-policy updates. These are pattern-shaped and save real time. The strategic sections are not delegable.

Once the concept is approved by a human, let AI multiply the executions. Twenty or fifty or two hundred variants of headline, hook, body copy, and asset crop. The marginal cost is effectively zero. The selection of which variants ship is human judgment, informed by the brand constraints in the brief.

Run the brand-safety review as a list of questions, not rules. The questions are read by a human against context the AI does not have: What news event from the last seventy-two hours could this ad land near? What is the worst-faith screenshot of this creative? Who is named, depicted, or implied, and how will they read it? Is the placement appropriate to the moment, or will an unrelated organic post reframe the ad alongside it? These questions are not encodable. That is why they are on the Guard List.

Delegate the bid management and let it run. The auto-campaign is the right tool for the direct-response slice once the upstream judgment work is done. Check daily for anomalies; do not micromanage the bidding.

Check brand metrics on a quarterly cadence. Brand-search-volume, share-of-search, prompted and unprompted awareness if a tracker is funded. The platform dashboard will not show the drift before it shows up in revenue eighteen months later. Only the brand-side review catches it early.

![Seven-stage horizontal flow diagram of the campaign cycle: brief, competitive scan, concept, variant generation, brand-safety review, bid management, and quarterly brand-metric check. Stages alternate red (Guard) and secondary (Delegate). The brief and brand-safety review carry ochre stars marking them as the consequential-judgment stages where all human work sits.](../images/06-paid-social-and-ad-creative-fig-02.png)

*Figure 6.5 — The campaign cycle: alternating Delegate and Guard, with the brief and brand-safety review carrying all the consequential judgment.*

<!-- → [INFOGRAPHIC: Campaign cycle diagram — seven stages from brief through quarterly brand review, color-coded Delegate vs. Guard at each stage, with the brief and brand-safety review highlighted as the two stages where all the consequential judgment sits] -->

---

## The seven failure modes

One. Letting AI generate the creative concept. The concept is the bet. AI multiplexes; it does not bet. Concept generation handed entirely to AI converges toward the median of the training data, which is the median of every other brand's creative, which is not a brand position.

Two. Optimizing for the platform-default metric without a brand-side check. Binet and Field's data is the warning. Short-term performance metrics under-invest in the brand-building work that drives the largest long-term returns. If you specified CPA, the effect on mental availability next year is invisible to the system.

Three. Treating brand safety as filter compliance. The filter did not fail in the Pepsi case. The frame failed. Brand safety is a contextual read, not a content scan.

Four. Targeting precision as a substitute for creative quality. Nielsen's repeated findings through 2017, 2019, and 2023 [verify] attribute roughly 50% of campaign sales lift to creative quality — far more than targeting or media plan. Byron Sharp's reach argument is the theoretical backing. The targeting-precision reflex is the field's most durable misconception.

Five. Believing the auto-campaign's incrementality claim. The campaign reports conversions it touched. Lewis and Rao (2015) and Blake et al. (2015) are the rigorous demonstrations that touched is not caused. The honest read is: this variant performed well on the platform's metric; whether it produced incremental lift is a separate question.

Six. Running political or advocacy paid social on auto-campaign rails. The Guard List for this category is wider than any other. Almost nothing should be auto-served.

Seven. Serving any ad during a crisis without explicit human re-approval. The auto-campaign flags the performance change. The pause is the practitioner's call. A pre-scheduled creative that runs during an unrelated news cycle event is the cheapest brand-equity loss available.

---

## What the practitioner brings

The brief is the answer. Not the brief as a template or a form — the brief as the document where someone made a real call about what this brand should say and to whom and why and at what cost to other possible things it could have said. The auto-campaign tier is capable of executing that brief with a competence that was not available to any prior generation of practitioners. The brief itself is not delegable.

Howard Luck Gossage, working in San Francisco in the 1960s on Beethoven sweatshirts and Pink Air promotions, treated his ads as communications to people he respected. That stance — the belief that the audience is people, not a targeting parameter — is what current AI-optimized creative most consistently drops. It is not something that can be engineered back in at the placement or variant-selection layer. It has to be in the brief.

The accountability is the other thing. When the bet fails, a person is answerable. The auto-campaign is not answerable; the brief writer is. That accountability is not a burden the practitioner should want to shed — it is the reason the brief takes effort to write and the reason the effort is worth taking.

---

## LLM Exercises

**Exercise 1 — Generate and examine.** Describe a real or hypothetical brand, its category, and its current strategic position to an AI. Ask it to generate a creative brief for a paid social campaign. Examine the output: where is the brief fluent but empty? Where does it contain real strategic constraint? What would you have to add to make the brief represent an actual bet?

**Exercise 2 — Apply to known context.** Take a recent paid social campaign you have run or observed. Decompose it into sub-steps — brief, concept, variant generation, audience targeting, bid management, brand-safety review, measurement. Classify each sub-step as Delegate or Guard. Where did the actual campaign treat a Guard item as Delegate? What was the consequence?

**Exercise 3 — Stress-test a brand-safety call.** Pick an ad concept — real or hypothetical — and generate the brand-safety question checklist from the Do This protocol. Run the checklist against the concept. Does the checklist surface anything the content-filter approach would have missed? Write one sentence naming the specific contextual read that no AI filter could catch for this concept.

**Exercise 4 — Draft a practitioner brief.** Take the AI-generated brief from Exercise 1. Rewrite it as a practitioner brief: name the bet, specify the audience relationship state, name the lines the campaign may not cross, and add a brand-side success metric distinct from the platform's optimization metric. Note what you had to know about the brand — context the model did not have — to write the practitioner version.

---

## Key Terms

**The 60/40 rule.** Binet and Field's IPA finding (*The Long and the Short of It*, 2013) that healthy brands invest roughly 60% in long-term brand-building and 40% in short-term activation. AI-optimized paid social maximizes the short-term metric by default. The 60/40 call is a human allocation decision with empirical backing.

**Incrementality vs. measured lift.** Incrementality is the conversions that would not have happened without the ad. Measured lift is the conversions the platform attributes to the ad. Lewis and Rao (2015) and Blake, Nosko, and Tadelis (2015) showed the gap is large and most campaigns lack the statistical power to measure incrementality. AI-reported winning variants are usually measured-lift winners.

**Auto-campaign tier.** The platform-native programmatic offering — Meta Advantage+, Google Performance Max, TikTok Smart Performance Campaigns, equivalents [verify current names within 12–18 months]. Delegates targeting, creative selection, placement, and bid optimization to the platform. Effective on the platform's metric; opaque on incrementality and brand effect.

**Brand safety as contextual reading.** The judgment that an ad is technically clean but reads tone-deaf because of context — news event, recent platform incident, depicted individual, audience moment. Pepsi/Kendall Jenner (2017) and the Balenciaga incident (2022) are the canonical cases where no content filter caught what needed to be caught.

**Creative concept vs. creative variation.** The concept is the bet about what to say and how to say it. The variation is the multiplexed executions of that bet. AI handles variation at near-zero marginal cost; the concept is human work.

**Brand-side success metric.** A metric the brand cares about that is not the platform's optimization metric — brand-search-volume, share-of-search, prompted and unprompted awareness. The platform does not optimize against these. They must be measured separately on a longer cadence.

**The AI-vs-AI loop.** Generative creative optimized by AI media buying against AI-modeled audiences and measured by AI attribution. Competent at each layer; produces fluent, brand-shallow output that performs on the dashboard and erodes the brand on a longer horizon. The brief and the concept are the only intervention points.

**Targeting precision reflex.** The assumption that narrower targeting outperforms broader targeting. Byron Sharp's *How Brands Grow* (2010) argued for broad reach years before privacy changes forced the issue. P&G's Marc Pritchard walked back precision targeting in 2017 and 2019 on similar grounds [verify].

---

## Prompts

**Figure 6.4 — The AI-vs-AI loop (INFOGRAPHIC).** Render a circular flow with four cardinal nodes — generative creative (north), AI media buying (east), AI-modeled audiences (south), AI attribution (west) — each as a `#F5F5F5` rounded-zero rectangle outlined in secondary `#545454`. Connect the nodes clockwise with ink arrows. Place an ochre `#C8860E` circle at each of the four transition midpoints (NE, SE, SW, NW), annotated in secondary with what drops out: "concept drops out," "incrementality drops out," "brand signal drops out," "new-audience reach drops out." Centre the loop on a red `#C8102E` rectangle labelled "The brief" in EB Garamond with the subtitle "(human)" in Inter. Run four dashed red radial arrows from the brief to each loop node. Footer legend distinguishes Delegate (fill) / Guard (red) / drop-out (ochre). Cite Byron Sharp 2010, Binet &amp; Field 2013, Lewis-Rao 2015 in the source line.

**Figure 6.5 — Campaign cycle, where the judgment sits (INFOGRAPHIC).** Render a horizontal seven-stage flow: 1. Brief (Guard), 2. Competitive scan + benchmarks (Delegate), 3. Concept (Guard), 4. Variant generation (Delegate), 5. Brand-safety review (Guard), 6. Bid management (Delegate), 7. Quarterly brand-metric check (Guard). Guard stages fill red `#C8102E`; Delegate stages fill secondary `#545454`. Each stage box carries its number, label, and one-line subtitle in white. Highlight stages 1 and 5 with ochre `#C8860E` 3px stroke and a small ochre star above the box. Above the two highlighted stages, set the phrase "consequential judgment" in EB Garamond italic in ochre. Place stage 7 below the row, connected from stage 6 with a curved ink arrow. Below the row of stages 1-2, draw a dashed secondary timeline labelled "campaign duration." Legend distinguishes Guard / Delegate / consequential-judgment stage. Cite Binet &amp; Field 2013, Byron Sharp 2010, Lewis-Rao 2015, Pritchard P&amp;G 2017/2019 [verify] in the source line.
