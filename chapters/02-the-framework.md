# Chapter 2 — The Framework

*Delegate List, Guard List, and the Do This / Never Do This anatomy you will use in every chapter that follows*

---

## Opening case

In late 2023, Buffer — the social media management software company that has published nearly everything about how it operates since 2013 — added a section to its public AI policy. The document was unusual not for what it said but for the shape it took. Two lists. On the left: the tasks Buffer's marketing and product teams routinely use AI for. Caption variation. Scheduling suggestions. Analytics summarization. Internal documentation drafting. Subject-line A/B variants. On the right: the tasks Buffer explicitly does not delegate. Community responses on public channels. Brand voice decisions about new product launches. Crisis posting. Anything responding to a named customer in a public escalation.

The lists were short. Maybe eight items on each side at the time. The document was not impressive in length or polish. It was impressive because it existed, in writing, with reasoning attached to each line.

Then look at what happened to two companies that did not write the lists down.

In October 2024, Duolingo announced it was reducing its roster of contract translators because AI could handle localization at scale. The Delegate decision was made fast — translation, in the abstract, is pattern-shaped work that current models do well. What Duolingo did not have was a corresponding Guard column. Cultural fit for specific markets, idiomatic register for Gen Z learners in São Paulo versus Lagos, the community-sentiment read on whether AI translation in language *learning* would be received as ironic — none of these were on a list anywhere. The company walked back parts of the decision after community backlash and quality drops. *Bloomberg* covered it; Duolingo's own response on its company channels acknowledged the recalibration. [contested — outcome still developing as of 2026-05-27.]

In early 2024, Klarna announced that an AI assistant was handling 2.3 million customer service conversations and doing the equivalent work of 700 full-time agents. The company press-released the figure. The *Financial Times* covered it. By 2025, Klarna had quietly reversed parts of the rollout, citing service quality and the kinds of escalation that required a human. The Delegate decision had been made fast and publicly; the Guard decision — which customer interactions, in which states, require a human — had been made slowly and privately, after the damage. [contested — exact reversal scope varies by source.]

Two patterns are visible across these three cases. Companies that wrote the lists down before the rollout caught failures earlier and recovered cheaper. Companies that wrote the Delegate side and not the Guard side discovered the Guard categories the hard way. The lists are cheap. The failures are expensive. The framework in this chapter is the structure for getting the lists written before you need them.

---

## The pattern-shaped work in this task (Delegate List)

Building the framework itself decomposes. The pattern-shaped pieces — what AI can do while you build your lists:

1. **Task inventory generation.** Given a description of your role, AI produces a starter list of recurring social marketing tasks for you to refine. Useful as scaffolding, not as the final inventory.

2. **First-pass classification.** Given your inventory, AI can sort items along the pattern-shaped vs. judgment-shaped axis as a draft you correct. The corrections are the work.

3. **Reasoning drafts for each line.** AI can produce a one-sentence rationale for why each item belongs on the Delegate or Guard side. You edit. The reasoning is what makes the list defensible later.

4. **Template population.** Given the column structures in this chapter, AI fills in the table cells for items you specify. Format work.

5. **Do This / Never Do This pair generation.** Given a task family, AI produces candidate pairs that you select among. Variation generation, which is pattern-shaped.

6. **Cross-chapter consistency checks.** Once you have lists for multiple tasks, AI can flag where two chapters' Guard List items contradict each other, or where a Delegate item in one chapter is a Guard item in another.

7. **Quarterly-review prompt drafts.** AI can produce the question set for your next quarterly review of the lists. The review itself is judgment work (see Chapter 11).

These are the framework-building tasks AI helps with. They are scaffolding. The lists are not the framework; the *defending of each line* is the framework.

---

## The judgment-shaped work in this task (Guard List)

Framework-building currently requires a human for the following:

1. **The defending of each Delegate item.** Not the listing — the reason this item is on Delegate *for your context*. Cost of error is low enough. Quality risk is acceptable. The reps are not load-bearing for skill. The brand can absorb a generic-sounding instance. Without the defense, the Delegate List drifts toward "everything AI can do" and the framework collapses.

2. **The defending of each Guard item.** "What about this task requires judgment that AI currently cannot exercise?" If you cannot answer in one sentence per item, the Guard List will not survive the first contested decision. Train yourself to answer the question, not just list the items.

3. **The escalation trigger.** Guard items are not prohibitions in all cases; they are *conditions* under which the human takes over. The escalation trigger column says when the Guard activates — when the comment is a service complaint, when the post mentions a named individual, when the regulatory window is open. Writing the trigger is judgment.

4. **The contextual calibration.** A B2B SaaS marketer's Delegate List is not a beauty brand's Delegate List. The framework asks you to calibrate the lines to your specific context — your industry, your brand stakes, your regulatory exposure, your audience tolerance. AI can produce a generic list; only you can produce yours.

5. **The decision to move an item.** As capability changes or as your context changes, items will migrate between the lists. The decision to move — and the documentation of the reasoning — is yours. Chapter 11 returns to this with a forecasting discipline.

6. **The quarterly review.** Whether the lists still reflect reality is a check only you can run, because you are the one whose work the lists describe. Without the review, the framework becomes shelfware within a quarter.

7. **The socialization inside your org.** Getting the lists adopted by your team, your manager, or your compliance counsel is org-political work that AI cannot do. The lists work when the people accountable for the work agree to them.

---

## The framework, in three nested levels

Before the templates, the structure. The framework has three levels, and each level does a different job. Confusing the levels is the most common failure mode in adoption.

**Level 1 — Conceptual.** Pattern-shaped vs. judgment-shaped. This is the vocabulary Chapter 1 introduced. It names *why* the boundary exists. It is the philosophical move that says: some work is reducible to a recipe, some work is not, and AI is structurally suited to the first kind. This level does not yet produce a list.

**Level 2 — Operational.** Delegate List vs. Guard List. This is the *artifact* you build. The Delegate List is the subset of pattern-shaped work that, given your context, you will hand to AI. The Guard List is the subset of judgment-shaped work that, given your context, currently requires a human. Crucially: the Delegate List is not "everything AI can do." Some pattern-shaped work stays manual because the reps build skill, because the cost of a rare error is high, or because your brand is small enough that judgment is cheaper than setup. This distinction is the chapter's central move.

**Level 3 — Execution.** Do This with AI vs. Never Do This with AI. These are the chapter-level syntax that converts the lists into action. Each chapter of this book uses them. They are paired: "Do generate ten caption variants from a single approved draft / Never let AI choose which variant publishes." The pairing is the point. A Do without a corresponding Never is permission without a guardrail.

A Delegate List without Guard List items defended in writing is Taylorism — the early-twentieth-century scientific-management movement that delegated pattern-shaped work so thoroughly it stripped judgment out of workflows entirely, which is why it eventually failed. A Guard List without Delegate List items defended in writing is the under-delegation failure mode of Chapter 1 — the manager doing pattern work by hand because nobody authorized the alternative. Both lists, with reasoning, are the framework.

---

## The Delegate List template

The five-column structure recommended for every chapter that follows.

| Task | Why pattern-shaped | Recommended AI tool category | Time saved (estimate) | Quality risk if skipped |
|---|---|---|---|---|

- **Task.** The specific action. Granular enough to be a discrete delegation decision. "Draft LinkedIn caption from approved core message" is a task; "do social media" is not.

- **Why pattern-shaped.** One sentence. The structural reason this task follows a recognizable recipe rather than requiring context-specific judgment. Forces the defense.

- **Recommended AI tool category.** Category, not product. "General-purpose LLM with brand-voice prompt" rather than "ChatGPT 4o." Products change; categories age slower.

- **Time saved (estimate).** Honest hours per week or per task. Useful for prioritizing which Delegate items to operationalize first. If the time savings are negligible, the item probably is not worth automating.

- **Quality risk if skipped.** What happens if the human pass is skipped after the AI does the draft. Helps calibrate the level of human review the item requires.

A short worked example for a B2B SaaS social manager:

| Task | Why pattern-shaped | Recommended AI tool category | Time saved | Quality risk if skipped |
|---|---|---|---|---|
| Draft LinkedIn caption variants from approved core message | Structure is fixed; voice fits within a documented register | General LLM with brand prompt | 30 min/week | Low — variants are pre-bounded by approved core |
| Summarize weekly platform analytics into 5-bullet recap | Numbers + summary template; no judgment in pull stage | LLM with structured analytics input | 1 hr/week | Low — recap is internal; strategic read is downstream |
| Generate 20 hashtag candidates for a campaign theme | Combinatorial discovery; ranking is human | LLM with platform-trend access or specialty tool | 20 min/week | Medium — risk is dated or off-brand hashtags |
| Draft alt-text for image carousels | Description pattern; accessibility standard is teachable | LLM with vision input | 15 min/week | Low — review pass is fast |

---

## The Guard List template

The five-column structure recommended for every chapter that follows.

| Task | Why judgment-shaped | What goes wrong if delegated | Required human role | Escalation trigger |
|---|---|---|---|---|

- **Task.** The specific action.

- **Why judgment-shaped.** One sentence. The structural reason this task requires accountability, relationship, or context the model does not have. The defense.

- **What goes wrong if delegated.** Specific. Not "bad output" — "voice drifts toward generic SaaS register" or "response sounds corporate to a user in active service complaint" or "post implies a performance guarantee under SEC Marketing Rule." Failure modes named.

- **Required human role.** Whose judgment is the binding one — community manager, brand lead, founder, compliance officer, legal counsel. Names the accountability locus.

- **Escalation trigger.** The condition that activates the Guard. Without this column, the Guard List reads as a prohibition list and gets ignored. With it, the Guard becomes operational — *this* comment, *this* situation, *this* moment triggers the human.

Short worked example for the same B2B SaaS social manager:

| Task | Why judgment-shaped | What goes wrong if delegated | Required human role | Escalation trigger |
|---|---|---|---|---|
| Respond to a customer in public escalation on LinkedIn | Relational; brand-voice + service-recovery + context-sensitive | Sounds corporate to an angry customer; damage compounds | Community manager + CSM | Any public comment flagged as service-related |
| Approve thought-leadership post in CEO's voice | Voice is the CEO's, not a stylesheet's | Post says something the CEO would not say; trust erodes | CEO or designated proxy | Any post under named-executive byline |
| Post during a competitor's PR crisis | Tone judgment; opportunism risk; legal exposure | Brand reads as exploiting; reputational damage | Brand lead + legal | Any breaking news involving a named competitor |
| Comment on a cultural moment | Whether the brand can credibly take the angle | Brand reads as opportunistic; community pushback | Brand lead | Any unplanned reactive content |

The escalation trigger column is what makes the Guard List a working document. Buffer's policy has it; the policies Duolingo and Klarna lacked, until they wrote them after the failures, did not.

---

## A worked example — decomposing one task

The framework's deepest move is *decomposition*. Most social marketing tasks are not pure Delegate or pure Guard. They are multi-step workflows where some steps are pattern-shaped and some are judgment-shaped. The framework asks you to split the steps and assign each one.

Take "publish a LinkedIn thought-leadership thread for the CEO." Decomposed:

1. *Ideation* — what is the thread about? **Guard.** Requires reading what the CEO has said before, what the audience is responding to, what the company's positioning needs this quarter.

2. *Angle selection* — which take does the CEO want to defend on this topic? **Guard.** Requires knowing what the CEO believes, which AI does not.

3. *Outline drafting* — given the angle, structure the thread. **Delegate.** Pattern-shaped given the angle.

4. *First-draft prose* — write the actual posts. **Delegate.** AI does this well in 2026; editing is fast.

5. *Voice pass* — does this sound like the CEO? **Guard.** Requires the editor who knows the CEO's voice from years of writing for them.

6. *Hook refinement* — the opening line of the thread. **Guard.** The hook is where voice is most exposed and where most engagement is decided.

7. *Hashtag and tag generation* — discoverability layer. **Delegate.** Pattern-shaped.

8. *Publishing time and platform tuning* — when and how. **Delegate.** Pattern-shaped, well-tooled.

9. *First-hour comment monitoring and prioritized response* — the relational layer. **Guard.** Whose voice replies in the comments is the same voice that wrote the thread.

Nine steps. Six Delegate, three Guard. Without decomposition, the practitioner either delegates the whole thread (over-delegation; CEO-voice failure on step 5 and 6) or drafts the whole thread by hand (under-delegation; wasted time on steps 3, 4, 7, 8). The decomposition is the framework in action.

Every chapter of this book is the same exercise for a different task family.

---

## Do This with AI

Building your framework, in roughly half a working day.

**Step 1 — Inventory (30 min).** Open a document. List every recurring social marketing task you perform. Aim for 25–40 items. Use the chapters of this book (3–9) as a checklist — content creation, community management, analytics, paid social, influencer, crisis, platform-specific execution. Add items those chapters don't cover.

**Step 2 — First-pass classification (45 min).** For each task, mark pattern-shaped or judgment-shaped using the Chapter 1 vocabulary. Many items will feel like both — flag them as boundary cases. Resist the urge to commit until step 4.

**Step 3 — Draft the Delegate List (45 min).** For each pattern-shaped item you are willing to hand over, fill the five columns. The *why pattern-shaped* and *quality risk if skipped* columns are the load-bearing ones. If you cannot fill them, the item is probably a boundary case, not a Delegate item.

**Step 4 — Draft the Guard List (45 min).** For each judgment-shaped item, fill the five columns. The *escalation trigger* column is the difference between a working Guard List and a list that gets ignored. Be specific.

**Step 5 — Decompose at least three multi-step tasks (45 min).** Pick three tasks you do regularly — a thought-leadership post, a campaign launch sequence, a crisis-adjacent reactive post — and walk through the decomposition. Each sub-step lands on Delegate, Guard, or boundary.

**Step 6 — Identify boundary cases (20 min).** List three to five items that genuinely sit between the lists. These are your re-audit candidates. Schedule the re-audit ninety days out. The act of scheduling is the practice; without it, the list rots.

**Step 7 — Socialize (variable).** If you are on a team, share the draft with your manager, your compliance counsel, or your peers. Frame it as a risk-management instrument as much as a productivity instrument. In regulated industries, this is what gets the lists adopted.

The output is a working Delegate List and Guard List, each with one-sentence defenses, an escalation trigger column for the Guard side, and a re-audit date. Roughly five to seven hours of work for the first version. Chapters 3–9 will populate it task by task; Chapter 10 will calibrate it to your specific domain.

---

## Never Do This with AI

Seven failure modes specifically about building the framework.

1. **Never let AI write the Guard List unsupervised.** The model will produce a plausible-looking list. The Guard List is exactly where the model's training data is least reliable, because the items depend on your specific accountability structure, brand stakes, and regulatory context. AI can suggest candidates; you defend each line.

2. **Never confuse the Delegate List with "everything AI can do."** Some pattern-shaped work stays manual because the reps build skill, the cost of error is high, or the brand is small enough that judgment is cheaper than setup. The Delegate List is a choice, not a capability ceiling.

3. **Never confuse the Guard List with "things AI cannot do."** The Guard List is what currently requires a human given accountability, brand stakes, and audience attribution. It is a decision about what to retain, not a claim about the model's capability ceiling.

4. **Never skip the escalation trigger column.** A Guard List without triggers is a prohibition list. Prohibition lists get ignored under deadline pressure. Triggers are what make the Guard operational in the moment.

5. **Never treat the lists as static.** Capability changes; your context changes; the lists move. The quarterly review is part of the framework, not an add-on. Chapter 11 makes this explicit; Chapter 12 turns it into a practice.

6. **Never skip the defense step.** Listing without defending produces a list that does not survive its first contested moment. The discipline of writing the one-sentence rationale per line is what makes the framework hold up when someone in a meeting asks why this item is on this side.

7. **Never adopt someone else's lists wholesale.** The Buffer policy is a useful reference, not a template you can copy. The lines are calibrated to Buffer's specific context — its product, its audience, its accountability locus. Yours will be different. The Meridian Wealth case in Chapter 10 is what happens when a practitioner adopts a list calibrated for a different industry.

---

## The +1

Chapter 1's +1 was the human review of a specific AI output. Chapter 2's +1 steps up a level: you are no longer just reviewing outputs, you are designing the system that determines which outputs need which kind of review. The framework is itself a +1 artifact.

What you bring that AI cannot:

- **The context the model does not have.** Your industry, your brand history, your audience tolerances, your regulatory exposure, your team's accountability structure. The framework asks for all of this and the model has none of it.

- **The reasoning that defends each line.** A list without reasoning is a guess. The chapter asks for one sentence per item on each list. The sentence is the +1 work.

- **The escalation trigger.** When *this* situation activates *that* Guard item. The trigger is the operational glue that converts a list into a working system. AI cannot write it because it does not know your situations.

- **The quarterly review.** The maintenance of the framework over time. Chapter 11 returns to this; Chapter 12 builds it into a daily practice.

- **The political work of adoption.** Lists are operative when the people accountable for the work agree to them. Getting that agreement is human work.

The Delegate List is what AI does. The Guard List is what the +1 does. The framework is the discipline of being explicit about which is which, defending each line, and revisiting on schedule. Every subsequent chapter is the framework applied to one task family.

---

## Claude Code prompt

*Illustrative — likely to age within 12–18 months. The framework structure is the durable element; the specific invocation will change.*

```text
You are helping me build the first draft of my Delegate List
and Guard List for social media marketing. This is the
Chapter 2 build from Social Media Marketing +1.

CONTEXT
- My role: [role]
- My org and industry: [industry, b2b/b2c, headcount, regulated?]
- My primary platforms: [list]
- My accountability locus: [founder-led / corporate / agency /
  solo]
- Tools I currently use, with sanctioned vs. personal noted: [list]

INPUT (paste below)
1. My recurring social marketing task inventory (25–40 items).
   Format: one task per line. [paste]
2. Tasks I've recently delegated to AI and was satisfied with
   (3–5). [paste]
3. Tasks I've recently delegated and regretted (3–5). [paste]
4. Tasks I drafted manually because I didn't feel comfortable
   delegating (3–5). [paste]

DO THIS
1. For each inventory task, mark candidate classification:
   Delegate / Guard / boundary. Use the Chapter 1 vocabulary.

2. Draft the Delegate List with five columns: Task / Why
   pattern-shaped / Recommended AI tool category / Time saved
   (estimate) / Quality risk if skipped. Fill all five.

3. Draft the Guard List with five columns: Task / Why
   judgment-shaped / What goes wrong if delegated / Required
   human role / Escalation trigger. Fill all five, especially
   the trigger column.

4. Identify three multi-step tasks from my inventory and walk
   through a decomposition for each — which sub-steps are
   Delegate, which are Guard, which are boundary.

5. List 3–5 boundary cases I should re-audit in 90 days, with
   one sentence per item naming what I am uncertain about.

6. For input 3 (delegated and regretted) — name the most
   likely failure mode for each. Not gentle; specific.

7. For input 4 (drafted manually) — name the most likely
   reason in plain language. Help me articulate tacit
   judgment without flattery.

DO NOT
- Produce a final framework. Produce a draft I will edit and
  socialize.
- Recommend specific AI products. Recommend categories.
- Cite regulatory provisions as binding. Cite as starting
  points to verify with counsel.
- Adopt the Buffer or any other public policy wholesale.
  Calibrate to my context.

OUTPUT FORMAT
- Markdown.
- Sections: Inventory classification table; Delegate List
  (5 columns); Guard List (5 columns); Decomposition examples;
  Boundary cases; Failure-mode notes; Tacit-judgment notes.
- Footer: a checklist of who should review this draft before
  it goes operative, and a proposed re-audit date.
```

---

## Key terms

**Delegate List.** The subset of pattern-shaped social marketing tasks that, given your context, you will hand to AI. Built with five columns: task, why pattern-shaped, recommended tool category, time saved, quality risk if skipped. Not a list of "everything AI can do" — a list of what you will choose to delegate.

**Guard List.** The subset of judgment-shaped tasks that, given your context, currently requires a human. Built with five columns: task, why judgment-shaped, what goes wrong if delegated, required human role, escalation trigger. Not a list of "things AI cannot do" — a list of what you choose to retain.

**Escalation trigger.** The condition that activates a Guard List item — a specific situation, comment type, content category, or time window. The column that separates a working Guard List from a prohibition list. Without triggers, Guard items get ignored under deadline pressure.

**Decomposition.** The discipline of splitting a multi-step task into sub-steps and assigning each to Delegate or Guard. Most consequential social marketing tasks are mixed, not pure. The decomposition is what prevents whole-task over- or under-delegation.

**Do This with AI / Never Do This with AI.** The execution-layer syntax. Paired action and anti-action on the same underlying task. Each chapter of the book uses the format. A Do without a Never is permission without a guardrail.

**Boundary case.** A task that genuinely sits between Delegate and Guard given current capability and current context. Boundary cases are re-audit candidates, scheduled and revisited deliberately — not items you guess about in the moment. Chapter 11 returns to forecasting them.

**Defense.** The one-sentence rationale you write for each line on each list. The discipline that makes the framework survive contested decisions. Without defenses, the lists are guesses.

**Accountability locus.** Whether the brand voice and the consequential decisions run to a named individual (founder, CEO, partner) or diffuse across a team. Determines how much voice-shaped work can be delegated and who must sign for Guard items.
