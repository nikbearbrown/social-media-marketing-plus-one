# Chapter 2 — The Framework

*The lists are cheap. The failures are expensive.*

---

There is a document published by Buffer — the social media software company that has made a practice of publishing nearly everything about how it operates — that is not impressive in length or polish. It runs a few pages. It has two lists. On one side: the tasks Buffer's marketing teams routinely hand to AI. Caption variation. Scheduling suggestions. Analytics summarization. Internal documentation drafts. Subject-line variants. On the other side: the tasks Buffer explicitly does not hand to AI. Community responses in public escalations. Brand voice decisions for new product launches. Crisis posting. Anything requiring a response to a named customer in a public thread.

Maybe eight items on each side. Short sentences. A line of reasoning attached to each one.

What makes the document interesting is not what it says. It is that it exists, in writing, with the reasoning attached, before anyone needed to defend a decision under pressure.

Now look at what happened to companies that did not write the lists.

In late 2024, Duolingo reduced its roster of contract translators on the grounds that AI could handle localization at scale. The delegation decision was made fast — translation, in the abstract, is pattern-shaped work that current models handle reasonably well. What Duolingo did not have was a corresponding column for what to keep. Cultural fit for specific markets. Idiomatic register for Gen Z learners in São Paulo versus Lagos. The community-sentiment read on whether AI translation inside a *language-learning* product would land as ironic. None of this was on a list anywhere. The company recalibrated after community backlash and quality drops. [*Outcome still developing as of 2026-05-27.*]

Around the same time, Klarna announced that an AI assistant was handling 2.3 million customer service conversations — the equivalent workload of 700 full-time agents. They press-released the figure. By 2025, Klarna had walked back parts of the rollout, citing service quality and the kinds of escalations that turned out to require a human in ways the original system design had not anticipated. The delegation decision had been made fast and loudly. The retention decision — which customer interactions, in which situations, need a person — was made slowly and quietly, after the cost had been paid. [*Exact reversal scope varies by source.*]

The pattern is not subtle. Companies that write both lists before the rollout catch failures earlier and recover cheaper. Companies that write the delegation side and not the retention side discover the retention categories the hard way. The lists cost an afternoon. The failures cost months.

This chapter is about how to write the lists.

---

## What the framework actually is

Before the templates, the structure. There are three levels here, and confusing them is the most common failure mode in adoption. They do different jobs.

The first level is conceptual. Chapter 1 introduced the vocabulary: pattern-shaped work versus judgment-shaped work. Pattern-shaped means the task follows a recognizable recipe — the inputs are consistent enough, the acceptable outputs bounded enough, that you can describe the process without reference to context the model doesn't have. Judgment-shaped means the task requires accountability, relationship, or situational read that cannot be fully specified in advance. This level is the philosophical foundation. It explains *why* the boundary exists. It does not yet produce a list.

The second level is operational. The Delegate List is the subset of pattern-shaped work that, given your specific context, you will hand to AI. The Guard List is the subset of judgment-shaped work that, given your specific context, currently requires a human. Notice what those phrases are doing. "Given your specific context" is doing a lot of work. The Delegate List is not "everything AI can do." Some pattern-shaped work stays with the human because the repetitions build skill, or because a rare error in this domain carries consequences the brand cannot absorb, or because the volume is low enough that judgment is simply cheaper than the setup cost. The list is a choice, not a capability catalog.

The third level is execution. Each chapter in this book ends with two paired sections: *Do This with AI* and *Never Do This with AI*. These convert the lists into action. They are always paired. A Do without a corresponding Never is permission without a guardrail. The pairing is the mechanism.

![A concentric ring diagram. The outermost ring represents the conceptual level (pattern-shaped versus judgment-shaped). The middle ring represents the operational level (Delegate List versus Guard List). The innermost disc represents the execution level (Do This versus Never Do This). Each ring connects via a callout bracket to a short statement of what it produces.](../images/02-the-framework-fig-01.png)

*Figure 2.1 — Three nested framework levels. The outer ring produces vocabulary, the middle produces lists, the inner produces actions.*

<!-- → [INFOGRAPHIC: Three nested levels — Conceptual (pattern vs. judgment), Operational (Delegate List vs. Guard List), Execution (Do This / Never Do This) — shown as concentric rings or a stack, with a one-sentence description of what each level does and what it produces] -->

A Delegate List without a defended Guard List is what the early-twentieth-century scientific management movement produced — Taylorism stripped judgment out of workflows so thoroughly it eventually broke the systems it was supposed to optimize. A Guard List without a defended Delegate List is the under-delegation failure from Chapter 1: the manager doing pattern work by hand because nobody authorized anything different. Both lists, with reasoning, are the framework. Neither list alone is.

---

## The Delegate List

The template has five columns.

| Task | Why pattern-shaped | Recommended AI tool category | Time saved (estimate) | Quality risk if skipped |
|---|---|---|---|---|
| The specific action, granular enough to be a discrete decision — e.g. "Draft LinkedIn caption from approved core message." | One sentence naming the structural reason this task follows a recipe. If you can't write it, the item is probably a boundary case. | The category, not the product — e.g. "general LLM with brand prompt." Products change; categories age more slowly. | Honest hours per week or per task. Used to prioritize which Delegate items to operationalize first. | What happens if the human review pass is dropped after the AI does the draft. Calibrates how much oversight the item requires. |

*Figure 2.2 — The Delegate List template: five columns; the second column does the work.*

<!-- → [TABLE: Delegate List five-column template — Task / Why pattern-shaped / Recommended AI tool category / Time saved (estimate) / Quality risk if skipped — with one row of instructional placeholder text per column explaining what belongs there] -->

**Task** is the specific action, granular enough to be a discrete decision. "Draft LinkedIn caption from approved core message" is a task. "Do social media" is not.

**Why pattern-shaped** is one sentence. The structural reason this task follows a recipe rather than requiring context-specific judgment. This is the column that does the work. If you cannot write the sentence, the item is probably a boundary case, not a Delegate item.

**Recommended AI tool category** names the category, not the product. "General-purpose LLM with brand-voice prompt" rather than any specific tool by name. Products change. Categories age more slowly.

**Time saved** is honest hours per week or per task. Useful for prioritizing which Delegate items to actually operationalize first. If the savings are negligible, the automation probably isn't worth the setup.

**Quality risk if skipped** names what happens if the human review pass is dropped after the AI does the draft. This calibrates how much human oversight the item requires.

A worked example for a B2B SaaS social manager:

| Task | Why pattern-shaped | Recommended AI tool category | Time saved | Quality risk if skipped |
|---|---|---|---|---|
| Draft LinkedIn caption variants from approved core message | Structure is fixed; voice fits within a documented register | General LLM with brand prompt | 30 min / week | Low — variants are pre-bounded by approved core |
| Summarize weekly platform analytics into 5-bullet recap | Numbers + summary template; no judgment in pull stage | LLM with structured analytics input | 1 hr / week | Low — recap is internal |
| Generate 20 hashtag candidates for a campaign theme | Combinatorial discovery; ranking is human | LLM with platform-trend access | 20 min / week | Medium — risk is dated or off-brand hashtags |
| Draft alt-text for image carousels | Description pattern; accessibility standard is teachable | LLM with vision input | 15 min / week | Low — review pass is fast |

*Figure 2.3 — Worked Delegate List for a B2B SaaS social manager. The "why pattern-shaped" column is the load-bearing one.*

<!-- → [TABLE: Worked Delegate List — four rows: (1) Draft LinkedIn caption variants from approved core message / Structure is fixed; voice fits within a documented register / General LLM with brand prompt / 30 min/week / Low — variants are pre-bounded by approved core; (2) Summarize weekly platform analytics into 5-bullet recap / Numbers + summary template; no judgment in pull stage / LLM with structured analytics input / 1 hr/week / Low — recap is internal; (3) Generate 20 hashtag candidates for a campaign theme / Combinatorial discovery; ranking is human / LLM with platform-trend access / 20 min/week / Medium — risk is dated or off-brand hashtags; (4) Draft alt-text for image carousels / Description pattern; accessibility standard is teachable / LLM with vision input / 15 min/week / Low — review pass is fast] -->

The column worth dwelling on is *why pattern-shaped*. The discipline of writing it — not just listing the task, but naming the structural reason it belongs on this side — is what makes the list defensible later. A list without reasoning is a guess. The reasoning is what holds when someone in a meeting asks why this item is here.

---

## The Guard List

The template has five columns.

| Task | Why judgment-shaped | What goes wrong if delegated | Required human role | Escalation trigger |
|---|---|---|---|---|
| The specific action — e.g. "Respond to a customer in a public service complaint thread." | One sentence naming the accountability, relationship, or context the model lacks. | A specific, named failure mode — not "bad output." E.g. "sounds corporate to an angry user; damage compounds." | Whose judgment is binding — community manager, brand lead, founder, compliance officer. | The exact condition that activates the Guard — comment type, content category, time window. Without it, the item gets ignored under deadline pressure. |

*Figure 2.4 — The Guard List template: five columns; the fifth turns a prohibition into a working system.*

<!-- → [TABLE: Guard List five-column template — Task / Why judgment-shaped / What goes wrong if delegated / Required human role / Escalation trigger — with one row of instructional placeholder text per column] -->

**Task** is the specific action.

**Why judgment-shaped** is one sentence. The structural reason this task requires accountability, relationship, or context the model does not have.

**What goes wrong if delegated** is specific. Not "bad output" — "voice drifts toward generic SaaS register" or "response sounds corporate to a user in active service complaint" or "post implies a performance guarantee under SEC Marketing Rule." Named failure modes, not generic risk.

**Required human role** names whose judgment is binding — community manager, brand lead, founder, compliance officer. This column locates the accountability. Without it, the Guard item is a prohibition looking for an owner.

**Escalation trigger** is the condition that activates the Guard. This is the column that separates a working Guard List from a list that gets ignored under deadline pressure. Without the trigger, the Guard item reads as an absolute prohibition. With it, the Guard item becomes operational: *this* comment, *this* situation, *this* moment is when the human takes over.

| Task | Why judgment-shaped | What goes wrong if delegated | Required human role | Escalation trigger |
|---|---|---|---|---|
| Respond to a customer in a public escalation on LinkedIn | Relational; brand-voice + service-recovery + context-sensitive | Sounds corporate to an angry customer; damage compounds | Community manager + CSM | Any public comment flagged as service-related |
| Approve thought-leadership post in the CEO's voice | Voice is the CEO's, not a stylesheet's | Post says something the CEO would not say; trust erodes | CEO or designated proxy | Any post under a named-executive byline |
| Post during a competitor's PR crisis | Tone judgment; opportunism risk; legal exposure | Brand reads as exploiting; reputational damage | Brand lead + legal | Any breaking news involving a named competitor |
| Comment on a cultural moment | Whether the brand can credibly take the angle | Brand reads as opportunistic; community pushback | Brand lead | Any unplanned reactive content |

*Figure 2.5 — Worked Guard List. The escalation trigger column is the operational difference between a working list and one that gets ignored.*

<!-- → [TABLE: Worked Guard List — four rows: (1) Respond to customer in public escalation on LinkedIn / Relational; brand-voice + service-recovery + context-sensitive / Sounds corporate to an angry customer; damage compounds / Community manager + CSM / Any public comment flagged as service-related; (2) Approve thought-leadership post in CEO's voice / Voice is the CEO's, not a stylesheet's / Post says something the CEO would not say; trust erodes / CEO or designated proxy / Any post under named-executive byline; (3) Post during a competitor's PR crisis / Tone judgment; opportunism risk; legal exposure / Brand reads as exploiting; reputational damage / Brand lead + legal / Any breaking news involving a named competitor; (4) Comment on a cultural moment / Whether the brand can credibly take the angle / Brand reads as opportunistic; community pushback / Brand lead / Any unplanned reactive content] -->

Buffer's policy has the escalation trigger column. The policies Duolingo and Klarna lacked, until they wrote them after the failures, did not. That is the operational difference between a list that works and a list that gets ignored when it matters most.

---

## Decomposition

Most real social marketing tasks are not pure Delegate or pure Guard. They are multi-step workflows where some steps are pattern-shaped and some are not. The framework asks you to split the steps and assign each one. This is where the work actually happens.

Take "publish a LinkedIn thought-leadership thread for the CEO." Nine steps, decomposed:

Ideation — what is the thread about — is Guard. It requires reading what the CEO has said before, what the audience is responding to, what the company's positioning needs right now.

Angle selection — which take does the CEO want to defend — is Guard. It requires knowing what the CEO actually believes, which AI does not.

Outline drafting, given the angle, is Delegate. Pattern-shaped given the constraints.

First-draft prose is Delegate. AI handles this well; the editing pass is fast.

Voice pass — does this sound like the CEO — is Guard. It requires the editor who knows the CEO's voice from sustained proximity.

Hook refinement — the opening line of the thread — is Guard. The hook is where voice is most exposed and where most engagement is decided.

Hashtag and tag generation is Delegate. Combinatorial discovery work.

Publishing time and platform tuning is Delegate. Pattern-shaped, well-tooled.

First-hour comment monitoring and prioritized response is Guard. Whoever replies in the comments is the same voice that wrote the thread.

Nine steps. Six Delegate, three Guard. Without decomposition, the practitioner either hands over the whole thread — over-delegation, with CEO-voice failure at the voice pass and hook — or drafts the whole thing by hand, wasting significant time on the steps that were never judgment work in the first place.

![A vertical nine-step workflow diagram for a LinkedIn CEO thought-leadership thread. Six steps are color-coded as Delegate (secondary gray) and three as Guard (red). Callouts on the three Guard steps name their reason: angle selection requires knowing what the CEO believes; voice pass requires sustained proximity; hook is where voice is most exposed. A tally at the bottom shows six Delegate and three Guard.](../images/02-the-framework-fig-02.png)

*Figure 2.6 — Decomposition of a LinkedIn CEO thread: six Delegate steps, three Guard steps. Whole-task delegation hides the structure.*

<!-- → [INFOGRAPHIC: Decomposition diagram for the LinkedIn CEO thread — nine labeled steps in sequence, color-coded Delegate vs. Guard, with the three Guard steps called out and their reason named: Angle selection (requires knowing what CEO believes), Voice pass (requires sustained proximity), Hook (voice most exposed here)] -->

Every chapter in this book is the same exercise for a different task family. The decomposition is the framework in action.

---

## Building your framework

Building the first version takes roughly half a working day. Here is the sequence.

Start with a task inventory. List every recurring social marketing task you perform — aim for twenty-five to forty items. Use the chapter topics in this book as a checklist: content creation, community management, analytics, paid social, influencer work, crisis response, platform-specific execution. Add items that fall outside those categories for your specific role.

Run a first-pass classification. For each task, mark pattern-shaped or judgment-shaped using the Chapter 1 vocabulary. Many items will feel like both — flag them as boundary cases and keep moving. The goal at this stage is momentum, not precision.

Draft the Delegate List. For each pattern-shaped item you are willing to hand over, fill the five columns. The *why pattern-shaped* and *quality risk if skipped* columns are load-bearing. If you cannot fill them, the item is probably a boundary case.

Draft the Guard List. For each judgment-shaped item, fill the five columns. The *escalation trigger* column is the difference between a working list and a list that gets ignored. Be specific about the trigger.

Decompose at least three multi-step tasks. Pick three tasks you do regularly — a thought-leadership post, a campaign launch sequence, a crisis-adjacent reactive post — and walk through the sub-steps. Each sub-step lands on Delegate, Guard, or boundary.

Collect the boundary cases. List three to five items that genuinely sit between the lists. These are your re-audit candidates. Schedule the re-audit ninety days out. The scheduling is the practice; without it, the list rots.

Socialize. If you are on a team, share the draft with your manager, compliance counsel, or peers. Frame it as a risk-management instrument, not just a productivity instrument. In regulated industries, this framing is what gets the lists adopted.

The output of this work is a working Delegate List and Guard List, each with one-sentence defenses, an escalation trigger column on the Guard side, and a re-audit date. Every subsequent chapter will populate it task by task. Chapter 10 will calibrate it to your specific domain. Chapter 11 will return to it with a forecasting discipline for moving items between lists as capability and context evolve.

---

## What you bring that AI cannot

The Delegate List is what AI does. The Guard List is what the +1 does. But there is a specific catalogue of what the +1 actually provides — not generically, but in the act of building this framework.

The context the model does not have. Your industry, your brand history, your audience tolerances, your regulatory exposure, your accountability structure. The framework asks for all of this. The model has none of it.

The reasoning that defends each line. A list without reasoning is a guess that survived the first meeting. The one-sentence defense per item is what makes the framework hold when someone contests a decision under deadline pressure.

The escalation trigger. When *this* situation activates *that* Guard item. The trigger is the operational glue that converts a list into a working system. AI can suggest candidate triggers; only you can write the one that fits your actual situations.

The quarterly review. Whether the lists still reflect reality is a check only you can run, because you are the one whose work the lists describe.

The political work of adoption. Lists are operative when the people accountable for the work agree to them. Getting that agreement is human work.

---

## LLM Exercises

**Exercise 1 — Generate and examine.** Describe your role, your industry, and your primary platforms to an AI. Ask it to produce a starter inventory of recurring social marketing tasks for your context. Examine the output: which tasks did it include that you would actually delegate? Which did it include that should be Guard items? What did it miss entirely? The corrections are more valuable than the inventory.

**Exercise 2 — Apply to known context.** Take one multi-step task you perform regularly — a campaign post, a monthly analytics report, a community response to a common question type. Walk the AI through the task description and ask it to classify each sub-step as pattern-shaped or judgment-shaped. Compare its classification to yours. Where do you disagree, and why?

**Exercise 3 — Stress-test a Guard item.** Pick one item from your Guard List and present it to AI with the framing: "Why might someone argue this task is pattern-shaped and could be delegated?" Examine the argument it produces. Does it reveal a genuine boundary case, or does it confirm why the item belongs on Guard? Write one sentence articulating what the AI argument gets wrong about your specific context.

**Exercise 4 — Draft the escalation trigger column.** Take three Guard items from your list that currently lack escalation triggers — or that have triggers written as vague conditions like "when needed." Ask AI to generate three candidate trigger statements per item, specific enough to use in a moment-of-decision. Select the one that fits your context, edit it, and note what you had to change about the AI draft to make it accurate.

---

## Key Terms

**Delegate List.** The subset of pattern-shaped social marketing tasks that, given your context, you will hand to AI. Built with five columns: task, why pattern-shaped, recommended tool category, time saved, quality risk if skipped. Not a list of everything AI can do — a list of what you choose to delegate.

**Guard List.** The subset of judgment-shaped tasks that, given your context, currently requires a human. Built with five columns: task, why judgment-shaped, what goes wrong if delegated, required human role, escalation trigger. Not a list of things AI cannot do — a list of what you choose to retain.

**Escalation trigger.** The condition that activates a Guard List item — a specific situation, comment type, content category, or time window. The column that separates a working Guard List from a prohibition list that gets ignored under deadline pressure.

**Decomposition.** The discipline of splitting a multi-step task into sub-steps and assigning each to Delegate or Guard. Most consequential social marketing tasks are mixed. The decomposition is what prevents whole-task over- or under-delegation.

**Defense.** The one-sentence rationale written for each line on each list. The discipline that makes the framework survive contested decisions. Without the defense, the list is a guess.

**Boundary case.** A task that genuinely sits between Delegate and Guard given current capability and context. Boundary cases are re-audit candidates — scheduled, revisited deliberately, not decided in the moment.

**Accountability locus.** Whether consequential brand decisions run to a named individual or diffuse across a team. Determines how much voice-shaped work can be delegated and who must sign for Guard items.

---

## Prompts

### Figure 2.1 — Three Nested Framework Levels

Build a concentric ring diagram in D3 v7. Three centered, nested rings: outermost = Conceptual (pattern-shaped vs. judgment-shaped), middle = Operational (Delegate List vs. Guard List), innermost = Execution (Do This vs. Never Do This). Fill the outer ring with the secondary color at 18% opacity, the middle ring with red at 15% opacity, and the inner disc with ink at 25% opacity. Draw ring boundaries with 1pt ink strokes. To the right of the rings, place three small horizontal callout brackets (0.5pt ink with filled terminator dots) connecting each ring to a short label naming what that level *produces*: outer produces "vocabulary," middle produces "lists," inner produces "actions." Add an italic subtitle at the bottom: "Conceptual → Operational → Execution: the levels are a stack, not synonyms." Deliver as a standalone responsive HTML file with ResizeObserver, prefers-reduced-motion guard, role="img" and aria-labelledby on the SVG root.

### Figure 2.6 — Decomposition of a LinkedIn CEO Thread

Build a vertical nine-step workflow diagram in D3 v7. Each step is a rounded rectangle of consistent width, stacked top to bottom with a 1pt ink down-arrow connector between consecutive steps. Color-code: Delegate steps fill secondary gray at 25% opacity with secondary border; Guard steps fill red at 18% opacity with red border. The sequence: (1) Ideation — Guard; (2) Angle selection — Guard; (3) Outline drafting — Delegate; (4) First-draft prose — Delegate; (5) Voice pass — Guard; (6) Hook refinement — Guard; (7) Hashtag and tag generation — Delegate; (8) Publishing time and platform tuning — Delegate; (9) First-hour comment monitoring — Guard. On the right of steps 2, 5, and 6, draw a small ochre callout bracket terminating in a short ochre label naming the reason: "requires knowing what CEO believes," "requires sustained proximity," "voice most exposed here." At the bottom, draw two small tally tiles — a secondary tile with "6 Delegate" and a red tile with "3 Guard." Deliver as a standalone responsive HTML file.
