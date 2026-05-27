# Chapter 11 — What Changes, What Doesn't

*AI capability trajectory and the durable human layer*

---

## Opening case

In May 2022, six months before ChatGPT's public launch, a senior brand strategist at a global agency told a client roundtable that AI was "five to ten years away from producing usable marketing copy for a Fortune 500 brand." She was widely regarded as one of the more technically literate people in the room. Within twelve months her own agency was using GPT-4 for first drafts of campaign briefs, paid social variants, and ghostwritten LinkedIn posts for executive clients. The forecast had been wrong about timing by roughly a factor of ten.

In the same room, a junior planner said agents would be "running entire campaigns end-to-end by 2025." By the end of 2025, agentic systems were running narrow workflow segments (comment triage, paid-creative variation, scheduling optimization) reliably; running entire campaigns end-to-end remained Guard List work for anyone with a brand to protect. That forecast was wrong about scope.

Both forecasters were intelligent people in good faith. They were wrong in opposite directions. The senior strategist anchored on what was plausible from the current capability level and missed how steep the curve was. The junior planner anchored on the curve and missed how much consequential work lives downstream of capability — in trust, accountability, and contract.

The risk in writing a chapter on AI capability trajectory in May 2026 is repeating those mistakes in print, with longer shelf life. This chapter does not try to predict 2030. It teaches you to forecast at the *task family* level, distinguish capability-bound problems from attribution-bound problems, and run a quarterly calibration on your own Delegate/Guard map so the map does not age into uselessness while you keep using it.

The honest version of the chapter is: some things are about to change a lot, some things are not, and you can do better than guessing.

---

## The pattern-shaped work in this task (Delegate List)

Forecasting itself decomposes. The pattern-shaped pieces — what AI can help you with as you build a forecasting practice:

1. **Capability-claim surfacing.** Given a vendor announcement, technical report, or system card, AI can extract the specific capability claims, their benchmarked support, and the gap between benchmark and production reliability.
2. **Track-record assembly.** Given a forecast you (or anyone else) made 12 or 24 months ago, AI can pull the specific claim, the timeline, and what actually happened — useful raw material for calibration.
3. **Scenario draft generation.** Given a task family on your Delegate/Guard map, AI can draft three scenarios for that family at a chosen horizon (continuation-scaling / plateau / capability-overhang) for you to refine.
4. **Forecast register formatting.** AI can take your forecasts and structure them into a register with probability ranges, horizons, falsification conditions, and review dates — the Tetlock-style discipline made portable.
5. **Capability-watch monitoring.** Given a watchlist (a small set of capabilities you are tracking), AI can produce weekly or monthly summaries of vendor disclosures, evaluation papers, and red-team findings.
6. **Decomposition drafts.** Given a high-level forecast question ("will paid social copy variation be 95% AI by 2028?"), AI can produce a decomposition into sub-claims you can forecast individually.
7. **Counterargument generation.** AI is reliably good at producing the strongest case against any forecast you make — useful for stress-testing your own confidence.

---

## The judgment-shaped work in this task (Guard List)

Forecasting currently requires a human for the following:

1. **The probability calibration itself.** Tetlock's empirical work (*Expert Political Judgment*, 2005; *Superforecasting*, 2015) shows that calibration improves with deliberate practice. AI can offer a number; whether that number reflects your actual evidence and your actual uncertainty is a human judgment. Outsourcing the number is outsourcing the calibration.
2. **The "structurally requires" versus "currently requires" distinction.** This is the central judgment call of the chapter. AI can list reasons a task is hard for current models; whether the difficulty is contingent (better models close it) or structural (the task requires accountability, relationship, or context the model cannot acquire) is a judgment you have to make and defend.
3. **The local-context read.** What is going to happen *in your industry, on your account, with your audience* over the next 24 months. The model has a training cutoff and a context window; you have the lived stream.
4. **The stake-setting.** What is at risk if a particular Guard List item moves to Delegate prematurely. Only you can score the downside.
5. **The willingness to be wrong in writing.** Forecasting is a discipline only if the forecasts are recorded and reviewed. The discipline to write down a falsifiable claim, schedule the review, and update on the evidence is a human commitment AI cannot make on your behalf.
6. **The attribution call.** Whether your audience, your customers, your regulator, and your brand will *attribute* judgment, accountability, or trust to an AI-produced action. Attribution is a social fact about AI, not a capability question. AI cannot tell you what your audience will treat as authoritative.
7. **The decision to act on a forecast.** A forecast that goes 80% confident on a Delegate move is not an instruction. The call to actually move a task from Guard to Delegate carries reputational and contractual consequences only a person can sign for.

---

## The empirical track record — what to keep in front of you

Before any framework, sit with the track record. This is the calibration data.

**Forecasts that overshot timing.** Most observers in 2019–2020 said photorealistic AI-generated faces were several years out; they were widely deployed by 2022. Most observers in 2021 said long-form video generation was unsolved for the decade; Sora's first technical report appeared February 2024 and the field moved fast through 2024–2025 (Veo, Runway Gen-3, Kling). Most observers in 2022 said autonomous multi-step agents were a research curiosity; by late 2024 ("computer use" from Anthropic; Operator from OpenAI in January 2025) they were product-class for narrow workflows.

**Forecasts that overshot scope.** Most "AI will replace marketers by [year]" claims have repeatedly failed on the *scope* axis even when partly right on the *timing* axis. Specific tasks have been heavily automated; the role has not disappeared. The Eloundou et al. *GPTs are GPTs* paper (OpenAI / Penn / OpenResearch, March 2023, arXiv:2303.10130) was careful to label its measurement "exposure" rather than replacement — a careful framing the trade press generally dropped.

**Forecasts that aged well.** The 2015 Autor essay ("Why Are There Still So Many Jobs?", *Journal of Economic Perspectives*) made the Polanyi's Paradox case for the durability of tacit-knowledge work. A decade later it has held up better than most forecasts of the same vintage. The 2018 Daugherty and Wilson framing in *Human + Machine* — the "missing middle" where humans complement AI and vice versa — has aged reasonably well as a structural claim even where specific examples dated.

**The trajectory measurement worth knowing.** METR's work on "Measuring AI Ability to Complete Long Tasks" (2024–2025) finds that the time-horizon AI can autonomously complete tasks at meaningful reliability is doubling on roughly a seven-month rhythm, but starting from a low base. [verify against most recent METR publication] This is the most defensible quantitative trajectory claim in current circulation. Treat it as one data point, not a law. The Kaplan et al. scaling-laws paper (OpenAI, January 2020, arXiv:2001.08361) and the Hoffmann et al. Chinchilla correction (DeepMind, March 2022, arXiv:2203.15556) describe loss-vs-compute relationships, not real-world capability — keep the distinction.

**Three contested framings as of writing.** [contested]

- The *continuation-scaling* camp (Amodei in "Machines of Loving Grace," October 2024; Altman in various) holds that current trajectories continue through general-purpose agentic reliability in 3–7 years.
- The *plateau* camp (LeCun consistently; Marcus consistently; Subbarao Kambhampati on planning limits) holds that returns to pre-training scale have already started diminishing and the next jump requires architectural change.
- The *capability-overhang* camp holds that current models are more capable than deployed systems suggest and the next two years yield large gains from scaffolding.

None has been empirically validated. Treat the camps as a stress-test set for your own forecasts, not as authority.

---

## Do This with AI

A quarterly forecasting protocol you can run in 60–90 minutes per Delegate/Guard map.

**Step 1 — Snapshot the map (10 min).** Re-open your Chapter 10 map. Pick the five to ten items most relevant to your current quarter's work. These are your forecast subjects.

**Step 2 — For each item, ask the two-question test (20 min).**
- *What changes?* Is there a current capability gap that better models could plausibly close in the next 12, 24, 36 months? If yes, name the specific gap (reliability, context length, multimodal grounding, agentic reliability, etc.).
- *What doesn't?* Is there a structural reason a human is required regardless of capability? If yes, classify the reason: **accountability** (someone must be answerable to a regulator, a customer, a board), **relationship** (trust runs to a person, not an interface), or **context** (operationally relevant facts not in training data or the prompt).

A Guard List item with a closeable capability gap and no structural reason is a *capability-bound* item. A Guard List item with a structural reason is an *attribution-bound* item. The distinction is the central tool of the chapter.

**Step 3 — Assign a probability range and horizon (15 min).** For each capability-bound item, estimate the probability range (e.g., 40–70%) that the gap closes at production-grade reliability by a specific horizon (12, 24, 36 months). Use ranges, not point estimates. Use horizons, not "soon."

**Step 4 — Name a falsifier (10 min).** For each forecast, write down what would change your mind. "I would revise this forecast downward if [specific event]; I would revise upward if [specific event]." A forecast without a falsifier is a vibe. This is the Tetlock discipline; it is also exactly what separates calibrated forecasting from rhetorical forecasting in the trade press.

**Step 5 — Score the move (10 min).** For each item where you forecast a meaningful capability shift, ask: what would have to be true for me to actually move this task from Guard to Delegate? Compliance sign-off? A 90-day pilot? A logged-output requirement? Name the conditions.

**Step 6 — Run the three scenarios (15 min).** For one or two items where the stakes are highest, walk through the three scenarios — continuation-scaling, plateau, capability-overhang — and ask: under which scenarios does my move make sense? Under which does it not? The exercise surfaces the invariants.

**Step 7 — Log and schedule (5 min).** Write the forecast register entries with: claim, probability range, horizon, falsifier, review date. Put the review date on your calendar 90 days out. Without the scheduled review, the discipline collapses.

**Sample register entry.**

> *Item:* AI-drafted comment responses on routine product questions (currently Guard List for our brand because of voice fidelity concerns).
> *Forecast:* 50–70% probability that production-grade AI comment response with brand-voice fidelity will be reliable enough for our risk tolerance by Q4 2027.
> *Falsifier (downward):* if our brand-voice eval (the same 25-prompt test we ran in Q1) shows worse fidelity in two consecutive quarterly runs.
> *Falsifier (upward):* if a documented peer brand at our scale runs the workflow for two quarters without a flagged incident and publishes the eval.
> *Move conditions:* CCO and head-of-brand sign-off; 90-day pilot on a single product line; logged outputs; weekly voice audit.
> *Next review:* [date 90 days out]
> *Structural test:* this item is capability-bound, not attribution-bound. Audiences attribute comment responses to the brand, not to a specific human; the relationship layer is not load-bearing here.

---

## Never Do This with AI

Forecasting failure modes worth naming explicitly.

1. **"AI will never X" claims.** Almost always wrong on engineering grounds. You have to be extremely confident about a mathematical limit to make a never-claim, and you almost never have that confidence. "Never" is rhetoric, not calibration.
2. **"AI will replace all X by [year]" claims.** Track record is poor. The trade press's history of these claims since 2017 is a graveyard. Replace with task-family forecasts and probability ranges.
3. **Point estimates without ranges.** "By 2028, this will happen" is less honest than "55–75% probability by 2028." The range is the calibration.
4. **Forecasts without falsifiers.** A forecast that cannot be wrong is not a forecast. It is a feeling.
5. **Treating capability and attribution as the same problem.** A model can produce convincing accountability-shaped output without being accountable. A model can produce relationship-shaped output without being in a relationship. Whether your audience and your regulators *attribute* accountability or relationship to AI output is a social fact, not a capability question, and it is evolving very slowly even where capability is moving fast.
6. **Anchoring on a single forecaster.** Including the most articulate one. The continuation-scaling and plateau camps both contain very intelligent people in good faith. The honest stance is calibrated uncertainty across the camps, not adoption of one camp.
7. **Refusing to forecast.** Tetlock's research disconfirms the "it's impossible to predict" pose. Calibrated forecasting is teachable. Refusing to forecast is itself a forecast — a forecast of "no useful information," which is almost never accurate.
8. **Forecasting at the role level.** "Will the social media manager exist in 2030?" is not a tractable question. "What share of paid social copy variation will be AI-led by 2028?" is. Forecast at the task family.

---

## The +1

The +1 in this chapter is the practitioner becoming a calibrated forecaster about their own work. Earlier chapters taught you to make the delegation call for current capability; this chapter teaches you to make the call *prospectively* — to design today's map with awareness of how the boundary will move, and to schedule the revisits that catch the movement.

What you bring that AI cannot:

- **The willingness to be answerable for a forecast.** A forecast in your name on your team's record is a different object than a forecast generated by a model. The first is your reputation; the second is not.
- **The attribution read.** Whether your customers, regulators, and audience will treat AI-produced action as carrying judgment, accountability, or trust. This is the load-bearing distinction the chapter asks you to make for each Guard List item.
- **The cross-time discipline.** Re-opening the forecast register in 90 days, scoring the entries, and revising. A model can format the register; only a person can keep the practice alive across quarters.
- **The stakes calibration.** What you can afford to be wrong about and what you cannot. The model does not know your downside.

The deeper thesis the chapter asks you to hold: as capability grows, the *quantity* of human work in social marketing decreases, the *judgment density* of the remaining human work increases, and the *consequences* of judgment errors get amplified because each judgment now governs more downstream automated output. This is the inverse of the trade-press story (humans are obsolete); it is also more honest about what is changing. The practitioner who develops judgment density is the practitioner whose role compounds in value. That is a forecast this chapter is willing to make and defend, with the explicit caveat that it depends on brands continuing to attribute trust through persons — a social fact that could in principle change, and one to watch.

The chapter's three falsifiable forecasts, for the record:

- *Forecast 1:* The frontier of AI capability in pattern-shaped social marketing work will continue to expand through the next 36 months. (Easy to confirm; safe.)
- *Forecast 2:* The judgment, accountability, and relationship layer in trust-dependent brand work will not collapse on the same horizon. (Falsifiable; the chapter defends it on the structural argument that attribution is a social fact and social facts evolve slowly.)
- *Forecast 3:* The practitioner who articulates and develops their judgment surface will be more economically valuable at the same horizon than the practitioner who does not. (Falsifiable; depends on Forecast 2.)

If any of these gets falsified, revise the chapter. Falsifiability is the chapter's honesty.

---

## Claude Code prompt

*Illustrative — likely to age within 12–18 months. The forecasting discipline is the durable element; the specific invocation will change.*

```text
You are helping me run a quarterly forecasting audit on my
Delegate/Guard map for social media marketing. This is the
Chapter 11 protocol from Social Media Marketing +1.

CONTEXT
- My current map (paste): [paste Chapter 10 map]
- Items I want to forecast this quarter (paste 5–10 items):
  [paste subset]
- My last quarter's forecast register, if any (paste):
  [paste]
- Capability developments I've noticed in the last 90 days
  (paste 3–5): [paste]

FOR EACH ITEM, DO THIS
1. Apply the two-question test:
   - What current capability gap, if any, makes this item Guard?
   - Is there a structural reason a human is required regardless
     of capability? Classify as accountability / relationship /
     context, or none.
2. Label the item: capability-bound, attribution-bound, or both.
3. For capability-bound items, propose a probability range
   (e.g., 40–70%) and a horizon (12, 24, 36 months) for when
   the gap might close at production-grade reliability for
   my risk tolerance.
4. Write a downward falsifier and an upward falsifier — specific
   events that would change my mind.
5. Propose the move conditions: what would have to be true for
   me to actually move this item from Guard to Delegate.
6. Score against three scenarios (continuation-scaling /
   plateau / capability-overhang). Under which does the
   move make sense?

DO NOT
- Use point estimates. Use ranges.
- Make never-claims or all-by-year-Y claims.
- Treat capability and attribution as the same problem.
- Pick a side in the trajectory debate.
- Tell me what to do. Help me see the forecast clearly.

OUTPUT FORMAT
- Markdown.
- One section per item, with the seven outputs above.
- A summary table at the end with: item / label /
  probability range / horizon / next review date.
- A short note flagging any items where my last quarter's
  forecast looks wrong and should be revised.
```

---

## Key terms

**Capability-bound.** A Guard List item that is on Guard because of a current model capability gap. By definition, capability-bound items can in principle move to Delegate as capability grows. The question is when and at what reliability threshold.

**Attribution-bound.** A Guard List item that is on Guard because of a structural reason — accountability, relationship, or context — that does not collapse when capability grows. Attribution is a social fact about who and what audiences, regulators, and contracts treat as authoritative; it evolves slowly even where capability moves fast.

**Falsifier.** A specific event or observation that would change your forecast. Without a falsifier, a forecast is not a forecast. Tetlock's discipline; the chapter's.

**Probability range.** A pair of probabilities (e.g., 40–70%) attached to a forecast, expressing your uncertainty about your own estimate. More honest than a point estimate and more useful for decision-making.

**Horizon.** The time window the forecast applies to (12, 24, 36 months). Forecasts without horizons are unfalsifiable.

**Continuation-scaling / plateau / capability-overhang.** The three current camps about near-term AI trajectory. None empirically validated. Useful as a stress-test set across which your forecasts should survive, not as authority.

**Polanyi's Paradox.** Michael Polanyi's 1966 formulation, "we know more than we can tell," applied to automation by David Autor in 2015. Tacit knowledge resists external description; tasks that depend on tacit judgment resist delegation to systems that can only execute described patterns.

**Forecast register.** A maintained list of your forecasts with claims, probability ranges, horizons, falsifiers, and scheduled review dates. The artifact of a calibrated forecasting practice. Empty without the scheduled reviews.
