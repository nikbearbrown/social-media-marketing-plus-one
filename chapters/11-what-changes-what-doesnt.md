# Chapter 11 — What Changes, What Doesn't

*AI capability trajectory and the durable human layer*

---

In May 2022, six months before ChatGPT's public launch, a senior brand strategist at a global agency told a client roundtable that AI was "five to ten years away from producing usable marketing copy for a Fortune 500 brand." Within twelve months her own agency was using GPT-4 for first drafts of campaign briefs, paid social variants, and ghostwritten LinkedIn posts for executive clients. She was widely regarded as technically literate. Her forecast was wrong about timing by roughly a factor of ten.

In the same room, a junior planner said agents would be running entire campaigns end-to-end by 2025. By the end of 2025, agentic systems were running narrow workflow segments — comment triage, paid-creative variation, scheduling optimization — reliably. Running entire campaigns end-to-end remained Guard List work for anyone with a brand to protect. His forecast was wrong about scope.

Both were intelligent people in good faith. They were wrong in opposite directions. The strategist anchored on what was plausible from the current capability level and missed how steep the curve was. The planner anchored on the curve and missed how much consequential work lives downstream of capability — in trust, in accountability, in the social facts about what audiences and regulators will attribute to a machine.

The risk of writing a chapter on AI capability trajectory in May 2026 is repeating those mistakes in print, with longer shelf life. This chapter does not try to predict 2030. It teaches you to forecast at the task-family level, distinguish capability-bound problems from attribution-bound problems, and run a quarterly calibration on your own Delegate/Guard map so the map does not age into uselessness while you keep using it.

---

## The Distinction the Chapter Turns On

Before the track record, before the frameworks, one distinction needs to be precise: the difference between a capability-bound Guard item and an attribution-bound Guard item.

A capability-bound Guard item is on Guard because of a current model limitation. The model is not reliable enough, or context-aware enough, or consistent enough with your brand voice. These are real reasons to Guard. They are also contingent reasons — they can in principle close as capability grows. The question is when, and at what reliability threshold, and whether you will know when they have closed.

An attribution-bound Guard item is on Guard because of a structural reason that does not change when the model gets better. The three structural reasons that recur across the chapters in this book are accountability, relationship, and context. Accountability: someone must be answerable — to a regulator, a customer, a board, a public — in a way that runs through a named person, not an interface. Relationship: trust has been established with a specific human, and the audience is not interchangeable with an AI performing the same function. Context: the decision requires knowing something that is not in the training data and cannot be fully specified in a prompt — the history of a particular client, the internal conversation that just changed the strategy, the thing the founder will not say in a brief.

The distinction matters because it determines where you should be watching. Capability-bound items will move. Attribution-bound items will move much more slowly, if at all, because the barrier is not engineering — it is the social fact of what people, markets, and institutions will treat as authoritative. Social facts change, but they change on human-institution timescales, not model-release timescales.

Treating the two as the same problem is the error the trade press makes consistently. "AI is getting better at X" is a claim about capability. Whether your audience, your regulator, and your brand will attribute judgment or accountability to an AI doing X is a separate question, and the answer is often no for longer than the capability claim would suggest.

---

## What the Track Record Shows

Sit with the empirical record before any framework. This is the calibration data.

The forecasts that overshot timing are the majority. Most observers in 2019 and 2020 said photorealistic AI-generated faces were several years out; they were widely deployed by 2022. Most observers in 2021 said long-form video generation was unsolved for the decade; Sora's first technical report appeared in February 2024, and the field moved fast through Veo, Runway Gen-3, and Kling through 2024 and 2025. Most observers in 2022 said autonomous multi-step agents were a research curiosity; by late 2024, Anthropic's computer-use capability and OpenAI's Operator product — announced January 2025 — were product-class for narrow workflows. The pattern is consistent: capable observers who anchored on current limitations missed the curve.

The forecasts that overshot scope are also the majority, in a different direction. The "AI will replace [role] by [year]" claims have repeatedly been right about specific task automation and wrong about role elimination. The Eloundou et al. paper from OpenAI, Penn, and OpenResearch — published March 2023 on arXiv — was careful to label its measurement "exposure" rather than replacement. The trade press dropped that distinction immediately. Specific tasks have been heavily automated. The roles built around those tasks have not disappeared; they have changed shape.

The forecasts that aged well tend to be structural claims rather than timeline claims. David Autor's 2015 essay "Why Are There Still So Many Jobs?" made the Polanyi's Paradox case: we know more than we can tell, and tasks that depend on that knowing-more resist automation because they cannot be fully specified. A decade later it holds better than most forecasts of the same vintage. Michael Polanyi's original 1966 formulation — "we can know more than we can tell" — is the deepest version of the argument, and it is why attribution-bound Guard items are structurally durable even when capability-bound Guard items are closing.

<!-- → [TABLE: Forecast track record summary — rows: capability-timing forecasts / scope forecasts / structural forecasts; columns: general pattern, canonical overshot example, canonical undershot example, what held up] -->

The most defensible quantitative trajectory claim currently in circulation is from METR's work on measuring AI ability to complete long tasks, published through 2024 and 2025. Their finding: the time-horizon over which AI can autonomously complete tasks at meaningful reliability is doubling on roughly a seven-month rhythm, but starting from a low base. That is one data point, not a law. The Kaplan et al. scaling-laws paper from January 2020 and the Hoffmann et al. Chinchilla correction from March 2022 describe loss-versus-compute relationships, not real-world capability on real tasks — keep the distinction. Loss goes down on a curve; whether that translates to capability on your specific workflow is a separate measurement.

Three contested framings describe the current disagreement about near-term trajectory. The continuation-scaling camp — Dario Amodei's "Machines of Loving Grace" (October 2024) is the most specific version — holds that current trajectories continue through general-purpose agentic reliability in three to seven years. The plateau camp — Yann LeCun consistently, Gary Marcus consistently, Subbarao Kambhampati on planning limits — holds that returns to pre-training scale have already begun diminishing and the next jump requires architectural change. The capability-overhang camp holds that current models are more capable than deployed systems suggest and the next two years yield large gains from scaffolding and agentic infrastructure. None of these has been empirically validated. Use them as a stress-test set for your own forecasts, not as authority.

---

## How to Forecast Without Getting It Wrong in Both Directions

The discipline that Tetlock's research established — documented in *Expert Political Judgment* (2005) and *Superforecasting* (2015) — is that calibration improves with practice, but only if the forecasts are recorded, reviewed, and scored. A forecast that is not written down is not a forecast. It is a feeling about the future, and feelings about the future do not update on evidence because there is no record to update against.

The task-family level is the right grain for forecasting in this domain. "Will the social media manager exist in 2030?" is not a tractable question. "What share of paid social copy variation will be AI-led by 2028?" is. The difference is that the second question has a falsification condition: you can measure share of AI-led work at the end of 2028 and compare it to your estimate. The first question does not have a falsification condition in any operationalizable sense — "exists" is too loose, and roles change shape before they disappear.

The two-question test applied to each Guard List item: What current capability gap makes this item Guard? And is there a structural reason — accountability, relationship, or context — that a human is required regardless of capability? The first question identifies capability-bound items. The second identifies attribution-bound items. An item with a closeable capability gap and no structural reason is on a clock. An item with a structural reason is not, at least not on model-release timescales.

<!-- → [INFOGRAPHIC: The two-question test as a decision tree — first branch: capability gap present or not; second branch: structural reason present or not; four quadrants: (1) capability-bound only — watch for capability close, (2) attribution-bound only — stable; social-fact timescale, (3) both — capability gate opens but structural reason may persist, (4) neither — why is this on Guard?] -->

Probability ranges are more honest than point estimates. "50 to 70 percent probability that production-grade AI comment response with brand-voice fidelity will be reliable enough for our risk tolerance by Q4 2027" carries more information than "this will happen by 2027." The range expresses your uncertainty about your own estimate. It also makes scoring easier: if you assigned 50 to 70 percent and the capability did not arrive by Q4 2027, that is a mild disconfirmation, not a strong one. If you assigned 85 to 95 percent and it did not arrive, that is a calibration failure worth examining.

Falsifiers are the discipline's load-bearing element. For each forecast, write down what would change your mind: a specific event that would revise the forecast downward, and a specific event that would revise it upward. A forecast without a falsifier is rhetoric. The downward falsifier for the comment-response forecast above might be: "our brand-voice evaluation shows worse fidelity in two consecutive quarterly runs." The upward falsifier might be: "a documented peer brand at our scale runs the workflow for two quarters without a flagged incident and publishes the eval." These are specific, observable, and time-anchored.

Move conditions are separate from forecasts. A forecast that the capability gap will close at 60 percent probability by Q3 2027 is not an instruction to move the task to Delegate in Q3 2027. The move conditions are what would have to be true — compliance sign-off, a 90-day pilot, a logged-output requirement, a named-executive review — for you to actually make the move. Forecasting and deciding are different activities, and collapsing them is how the capability-overhang error propagates into live brand decisions.

Running the three scenarios for high-stakes items forces the invariants into view. For any item where the downside of premature delegation is high, walk through continuation-scaling, plateau, and capability-overhang, and ask: under which scenarios does the move make sense? Under which does it not? The items that only make sense under continuation-scaling are higher-risk moves than items that make sense under all three.

---

## The Forecasting Practice in Quarterly Operation

A quarterly session of 60 to 90 minutes, run against the chapter's framework.

Snapshot the map. Re-open the current Delegate/Guard map. Pick five to ten items most relevant to the current quarter's work. These are the forecast subjects.

Apply the two-question test to each item. What capability gap, if any, makes this Guard? Is there a structural reason — accountability, relationship, or context — that applies regardless of capability? Label each item: capability-bound, attribution-bound, or both.

For capability-bound items, assign a probability range and a horizon. Use ranges, not point estimates. Use specific horizons — 12, 24, 36 months — not "soon."

Name a falsifier for each forecast. One downward, one upward. Specific and observable.

Name the move conditions. What would have to be true for you to actually act on a capability forecast?

Run the three scenarios for the two or three items with the highest stakes. Under continuation-scaling, plateau, capability-overhang: does the move make sense? Does it only make sense under the most optimistic scenario?

Log and schedule. Write the register entries with claim, probability range, horizon, falsifier, and review date. Put the review date on your calendar 90 days out. Without the scheduled review, the discipline collapses on the second quarter.

<!-- → [TABLE: Sample forecast register — columns: item, label (capability-bound / attribution-bound / both), probability range, horizon, falsifier (down), falsifier (up), move conditions, review date] -->

The register is the artifact. The quarterly review is the practice. The combination is what distinguishes a calibrated forecasting habit from the kind of intuitive updating that produced the strategist-planner divergence at the beginning of this chapter.

---

## The Inverse of the Trade-Press Story

The trade press's recurring narrative is that AI capability growth threatens human roles in marketing. The chapter's thesis is something more specific and less intuitive: as capability grows, the *quantity* of human work in social marketing decreases, but the *judgment density* of the remaining human work increases, and the *consequences* of judgment errors are amplified because each judgment now governs more downstream automated output.

This is not a consolation. It is a structural observation about what automation does to the skill composition of the residual human role. When a factory automates its assembly line, the floor workers decrease in number and the engineers who maintain and program the automated line increase in value. The maintenance engineer does not have more things to do — they have fewer things to do, each of which matters more. The same shift applies here. The practitioner who develops judgment density is the practitioner whose role compounds in value. The practitioner who treats the Delegate List as liberation from judgment and the Guard List as an obstacle is making the same error in the opposite direction from the junior planner in the opening case.

The deeper argument for judgment density is the one Autor borrowed from Polanyi: we know more than we can tell. The judgment that makes an attribution-bound Guard item structurally durable is exactly the kind of knowing that resists specification — the read of a cultural moment, the voice that makes a CEO's byline trustworthy, the escalation call that distinguishes a real crisis from a brigade. These are not mysteries. They are the product of accumulated experience and deliberate reflection. They are also, by definition, what current models cannot fully acquire from a prompt.

The three forecasts this chapter is willing to make and defend: the frontier of AI capability in pattern-shaped social marketing work will continue to expand through the next 36 months. The judgment, accountability, and relationship layer in trust-dependent brand work will not collapse on the same horizon, because attribution is a social fact and social facts evolve slowly. The practitioner who articulates and develops their judgment surface will be more economically valuable at the same horizon than the practitioner who does not.

All three are falsifiable. The first is easy to confirm, and easy to confirm. The second depends on the structural argument about attribution — it would be falsified if audiences, regulators, and courts shifted to treating AI-produced brand communication as equivalent to human-accountable communication, which is possible but not occurring at model-release speed. The third depends on the second.

If any of these gets falsified, the chapter revises. That is not a disclaimer. It is the point. The practitioner who holds these forecasts in a register and checks them in 2028 is doing exactly what the chapter asks.

---

## LLM Exercises

**Exercise 1 — Two-Question Test**
Take your current Delegate/Guard map — or the map you built in Chapter 10. Apply the two-question test to every Guard item: what capability gap makes this Guard, and is there a structural reason (accountability, relationship, or context) that applies regardless of capability? Label each item capability-bound, attribution-bound, or both. Which labels surprised you? Which Guard items have no structural reason and are only there because of current capability limitations?

**Exercise 2 — Forecast Register**
Pick three Guard List items from your labeled map. For each, write a forecast register entry: the claim in one sentence, a probability range (not a point estimate), a horizon (12, 24, or 36 months), a downward falsifier, an upward falsifier, and the move conditions — what would have to be true for you to actually move this item from Guard to Delegate. Set a calendar reminder for 90 days.

**Exercise 3 — Scenario Stress Test**
Take the Guard List item on your map with the highest downside if delegated prematurely. Walk it through the three scenarios: continuation-scaling (capability arrives on the aggressive timeline), plateau (capability growth slows and the gap does not close in 36 months), and capability-overhang (current models are already better than you think and the gap closes faster than expected). Under which scenarios does your current Guard placement hold? Under which would you want to have made different preparations?

**Exercise 4 — Track Record Audit**
Find three forecasts about AI in marketing that you or your organization made 12 to 24 months ago — from meeting notes, strategy decks, emails, or public statements. For each: what was the specific claim, what was the timeline, and what actually happened? Classify each as overshot timing, overshot scope, roughly calibrated, or undershot. What pattern do you see in your own forecast errors? What would have made each forecast more precise?
