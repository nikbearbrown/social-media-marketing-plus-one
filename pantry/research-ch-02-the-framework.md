# Research: Chapter 02 — The Framework
## Social Media Marketing +1
**Chapter one-line:** Delegate List, Guard List, Do/Never Do anatomy.
**Research date:** 2026-05-27

---

## 1. Primary Sources

### Foundational papers and texts

1. **Parasuraman, R., Sheridan, T. B., & Wickens, C. D. (2000).** "A Model for Types and Levels of Human Interaction with Automation." *IEEE Transactions on Systems, Man, and Cybernetics,* 30(3), 286–297.
   The canonical four-stage model of automation (information acquisition, information analysis, decision selection, action implementation), each at variable levels of human involvement. The Delegate List / Guard List framework is a marketing-domain translation of this engineering framework: each task can be decomposed into stages, and each stage assigned an automation level. Chapter 2 should not cite Parasuraman directly to the practitioner reader, but the intellectual scaffolding is here.

2. **Bainbridge, L. (1983).** "Ironies of Automation." *Automatica,* 19(6), 775–779.
   The classic short paper that names the central irony: the more you automate, the more critical and the harder to perform the residual human tasks become. The Guard List is precisely the residual — and Bainbridge's warning is that residuals get harder, not easier, as the system around them automates. Chapter 2's framing of the Guard List as "the work that gets more important as you delegate more" rests on this paper.

3. **Davenport, T. H. & Kirby, J. (2016).** *Only Humans Need Apply: Winners and Losers in the Age of Smart Machines.* Harper Business.
   Introduces the "five steps" framework for humans positioning themselves alongside AI (step up, step aside, step in, step narrowly, step forward). The Do This / Never Do This taxonomy in Chapter 2 is an operational simplification of Davenport & Kirby's strategic frame — and citing them gives the practitioner reader a way into the broader literature without academic overhead.

4. **Atkinson, R. C. & Shiffrin, R. M. (1968).** "Human Memory: A Proposed System and its Control Processes." Reprinted in *The Psychology of Learning and Motivation,* Vol. 2.
   Cognitive scientists' working-memory model — relevant because the Delegate List is, functionally, an external working memory for delegation decisions. The chapter's argument for *writing the lists down* (not holding them in your head) is the same argument cognitive psychology has made for externalized memory aids for 60 years.

5. **Gawande, A. (2009).** *The Checklist Manifesto: How to Get Things Right.* Metropolitan Books.
   The trade-book ancestor of the chapter. Gawande's argument — that explicit checklists outperform expert intuition under cognitive load because they offload pattern-matching and free judgment for the residual — is the same argument Chapter 2 makes for the Delegate/Guard structure. The practitioner reader will recognize the move.

### Key empirical cases

1. **Buffer's published AI policy (2023, ongoing, documented on Buffer's blog and Open Salaries repo).** Buffer publicly documents which tasks it delegates to AI (caption variation, scheduling suggestions, analytics summarization) and which it explicitly does not (community responses, brand voice decisions, crisis posting). This is the cleanest real-world example of a documented Delegate List / Guard List that a practitioner reader will find immediately useful.

2. **Duolingo's translation team restructuring (October 2024, documented by Bloomberg and Duolingo's own response).** Duolingo cut contract translators and announced AI handling of localization, then walked back parts of the decision after community backlash and quality drops. Useful as a *boundary-drawn-wrong* case: the company had a Delegate List but no functioning Guard List for cultural fit and community sentiment. Cite as documented and contested.

3. **Klarna's customer support AI rollout (2024, documented in Klarna press releases, FT, and later walkback in 2025).** Klarna initially announced AI handling 2.3M customer service conversations equivalent to 700 FTEs; later (2025) admitted quality issues and partially reversed the rollout. Useful for the same reason as Duolingo: the Delegate decision was made fast, the Guard category (when does a customer need a human?) was made slow. Label as company-reported then independently revised.

---

## 2. The Core Concept — State of the Field

### What is settled

- Explicit decision frameworks outperform implicit ones under time pressure and cognitive load (broad consensus from checklist research, Gawande 2009; Hales & Pronovost, 2006; Haynes et al., NEJM 2009).
- Automation introduces new failure modes that are categorically different from manual failure modes — primarily, the operator loses calibration on whether the automation is in a regime where it works (Parasuraman & Manzey, 2010; Endsley, 2017).
- For knowledge work, the cost of a wrong automation decision is borne later than the cost of a wrong manual decision — meaning the feedback signal is weaker, meaning the decision needs to be made more deliberately up front. (Brynjolfsson, Li, & Raymond, NBER 2023.)

### What is disputed

- Whether the Delegate/Guard boundary should be drawn by task or by sub-task. Some (Davenport) argue task-level is sufficient for most workflows; others (Parasuraman, Endsley) argue sub-task is necessary because every task has steps at different automation levels.
- Whether the boundary should be drawn by the individual practitioner or by the organization. Practitioner-side flexibility is faster; organization-side standardization is auditable. Most enterprise AI governance literature (NIST AI RMF 2023, ISO/IEC 42001:2023) leans organizational; practitioner-side autonomy literature leans individual.
- Whether the boundary is dynamic — does a Delegate item ever move to Guard, or only the reverse? Empirically, both happen. Crisis lessons frequently move items from Delegate back to Guard.

### What has changed recently (last 5 years)

- Frameworks have proliferated. Microsoft's "Copilot for Work" framing (2023), Anthropic's "Claude for Business" (2024), and IBM's WatsonX governance documentation (2024) all converge on something Delegate/Guard-shaped, even when the language differs. The Chapter 2 framework benefits from being in the same conceptual neighborhood as these but more practitioner-facing.
- The regulatory environment has caught up. EU AI Act (2024) operational since Feb 2025 for some provisions; requires documentation of which tasks are AI-assisted in high-risk categories. The Delegate/Guard List, written down, is closer to regulatory-ready than most practitioner documentation.
- The number of organizations with published AI policies has grown sharply (estimated 60%+ of Fortune 500 by end of 2025, per Gartner). Few of those policies are practitioner-actionable; most are governance-shaped. There is a real gap for a list-based framework a working manager can implement on Monday morning.

---

## 3. Application Domain Examples

1. **A solo marketing consultant managing five client accounts.** Builds one Delegate List per client (because each brand's voice tolerance is different) and one shared Guard List (because crisis judgment and partnership decisions don't vary by client). The list architecture saves the consultant from re-deciding delegation per client per task.

2. **An in-house team of three at a 200-employee company.** Builds role-specific Delegate Lists (writer, community manager, analyst) and a shared Guard List (anything that touches legal, anything that touches a named individual outside the company, anything in a crisis window). Onboarding new hires becomes a list-handoff rather than a culture transfer.

3. **An agency social team servicing twelve brands.** Builds a Guard List by industry vertical (healthcare brands have one Guard List, consumer goods another, B2B SaaS a third) and a Delegate List by deliverable type (caption, thread, carousel, video script). Agencies particularly benefit from the explicit list because turnover is higher and the institutional memory is thinner.

4. **A creator-led brand where the founder is the voice.** The Delegate List is unusually narrow (almost all voice-shaped work is Guard); the Guard List is unusually wide. The framework still works — in fact, the explicitness protects the founder from delegating things that look pattern-shaped but carry voice signal (e.g., reply tone in DMs).

5. **A nonprofit communications team operating under donor scrutiny.** Guard List items include anything that names a beneficiary, anything that frames a funder, anything in a fundraising window. The Delegate List is small but consequential — meeting notes, event recaps, low-stakes social. The framework's value here is auditability: when a donor asks "did AI write this?" the team has a documented answer.

---

## 4. The Book's Thesis Connection

Chapter 2 operationalizes the thesis. Chapter 1 named the boundary; Chapter 2 builds the tool that draws it.

The chapter does three thesis-specific moves:

- **It separates the pattern vs. judgment distinction from the Delegate vs. Guard decision.** Pattern/judgment is the *conceptual* boundary (Level 1 of the framework). Delegate/Guard is the *operational* boundary (Level 2). The chapter must show that the Delegate List is not the pattern list — it is the subset of pattern work this practitioner, in this context, today, chooses to hand over. Some pattern work stays manual (because the practitioner wants the reps, or the cost of error is high, or the brand is small enough that judgment is cheaper than setup). The thesis demands this distinction; without it, Delegate becomes "everything AI can do" and the framework collapses into a prompt library.

- **It makes Guard List items defensible, not arbitrary.** Each Guard item should answer the question "what about this task requires judgment that AI currently cannot exercise?" The chapter must train the reader to justify Guard items, not just list them. This is the thesis in active voice: the Guard List is where the +1 lives, and the +1 needs a reason.

- **It establishes Do This / Never Do This as the chapter-level execution syntax.** Every subsequent chapter (3–9) follows this anatomy. Chapter 2's job is to make the syntax familiar, so that Chapter 3's content creation Do/Never lines read as instances of a pattern the reader already knows. The thesis depends on this rhythm — if every chapter looks unique, the framework is not generalizing.

---

## 5. The AI Wayback Machine — Candidate Figures

1. **Atul Gawande (b. 1965).** Surgeon and writer; *The Checklist Manifesto* (2009) is the direct intellectual ancestor of the Delegate/Guard structure. His core observation — that under cognitive load, expert judgment fails predictably on small things, and that an explicit list protects judgment by removing those small things from its load — is what Chapter 2 is reproducing for AI delegation. Living figure, well-known, accessible Wikipedia page, directly relevant; the connection to AI is the freshness.
   *Anchor prompt example:* "Atul Gawande in 2007 walking through an operating room with a 19-item checklist. Three surgeons told him it was insulting. The checklist cut mortality 47%. What is he protecting that the surgeons did not see?"

2. **Frederick Winslow Taylor (1856–1915).** Mechanical engineer; *The Principles of Scientific Management* (1911). Taylor is the original "delegate the pattern, retain the judgment" thinker — though in practice he over-delegated by stripping the judgment side out of work entirely. Useful as a *cautionary* anchor: the Delegate List without a Guard List is Taylorism, and Taylorism failed for the reasons the Guard List exists. Well-known, white male, but the angle (Taylor as warning, not model) is fresh.
   *Anchor prompt example:* "Frederick Taylor in 1911 timing a steelworker shoveling pig iron. He builds a system that quadruples output. Within ten years the system breaks down because the workers stop being able to think about their work. What did he take away that he didn't know he was taking?"

3. **Mary Parker Follett (1868–1933).** Management theorist; argued in the 1920s that authority should flow from the situation, not the hierarchy — meaning the right person to make a decision is the person closest to the relevant judgment. Follett's "law of the situation" is the philosophical basis for letting the Guard List items stay with the human nearest the audience. Lesser-known, woman, accessible Wikipedia page, strong fit for a chapter about who decides what.
   *Anchor prompt example:* "Mary Parker Follett in 1925 advising a factory manager. She tells him to stop giving orders. Instead, identify what the situation demands and let the person closest to the situation do that. Why is this not chaos?"

Diversity balance: two men (Gawande, Taylor — though Taylor is framed critically), one woman (Follett). All Western. Gawande is Indian-American, providing some non-white representation. The trio represents three eras (early 20th c., mid-20th c., contemporary) and three professional vantage points (engineering, management theory, medicine).

---

## 6. Pedagogical Delivery Research

**Prior knowledge the reader brings.** The reader has internalized Chapter 1's pattern/judgment distinction (or will skim back to it). They have not yet seen a practitioner-grade framework for translating that distinction into daily decisions. They have probably tried to make ad-hoc decisions about what to delegate and gotten inconsistent results.

**Misconceptions to surface and correct.**
1. *"The Delegate List is just 'things AI does well.'"* It is not. It is the subset of pattern-shaped tasks the practitioner *chooses* to hand over, given context. The chapter must show a case where pattern-shaped work stays manual (e.g., a founder writing their own captions because the voice is the brand).
2. *"The Guard List is what AI can't do."* It is not exactly. It is what *currently requires* a human, given accountability, brand stakes, and audience. The Guard List is a decision, not a capability ceiling.
3. *"Once the lists are made, they're stable."* They are not. Quarterly review is part of the framework. The chapter should preview this — Chapter 11 returns to it explicitly.

**Instructional sequence that works for Chapter 2.**
- Show a worked example of a single task being decomposed into Delegate-side sub-steps and Guard-side sub-steps (e.g., "publishing a thread" → ideation/Guard, drafting/Delegate, hashtag/Delegate, reply tone/Guard).
- Build a full Delegate List and Guard List for a single practitioner archetype (e.g., the solo consultant), showing reasoning at each line.
- Introduce the Do This / Never Do This format with two pairs of examples.
- Hand the reader a template (likely as a Claude Code prompt) for building their own.

**Failure modes in teaching this chapter.**
- *Making the lists feel like rules.* They are tools, not laws. The reader who treats them as rules either freezes (over-following) or rejects them (under-following). The chapter should frame them as living documents.
- *Burying the practitioner in taxonomy.* The temptation is to enumerate every task. The chapter should resist this — show the *method* of building a list, give one fully worked list, and let Chapters 3–9 produce the rest.
- *Skipping the justification step.* If the reader copies a Guard List without internalizing why each item is on it, the list won't survive the first contested decision. The chapter must train the *defending* of each line, not just the listing.

---

## 7. Representation and Display Research

Chapter 2 is the chapter that defines the display conventions for every chapter that follows. It should specify and demonstrate:

- **Delegate List columns.** Recommended: Task / Why Pattern-Shaped / Recommended AI Tool Category / Time Saved Estimate / Quality Risk if Skipped. Five columns is the maximum that fits a page; four (drop time-saved) if space is tight.
- **Guard List columns.** Recommended: Task / Why Judgment-Shaped / What Goes Wrong if Delegated / Required Human Role / Escalation Trigger. The escalation trigger column is what distinguishes a usable Guard List from a prohibition list — it says *when* the Guard item activates.
- **Do This with AI / Never Do This with AI format.** Recommended: two-column side-by-side, each row a paired action and anti-action on the same underlying task. Visually, this is the chapter's most distinctive display element and should be consistent across all chapters.
- **Worked example display.** A "before / after" of one task being decomposed (e.g., publishing a thread) into the Delegate and Guard sub-steps, with the reasoning beside each line.

Chapter 2 should include the full template that Chapters 3–9 will populate. Reader should be able to photocopy the page (or print the template from a companion repo) and use it directly.

---

## 8. Open Questions and Research Gaps

- **Whether Delegate List items have a half-life.** Anecdotally, yes — as models improve, items shift. No good longitudinal study yet. Flag.
- **Whether Guard List items vary more by industry or by individual brand.** Industry effects are strong (healthcare vs. consumer); brand-level variation within industry is also strong but less studied. The chapter should acknowledge both without forcing a hierarchy.
- **Whether the framework scales to teams of >10.** Most case studies are solo practitioners or small teams. Enterprise rollout literature is governance-shaped, not list-shaped. Flag as outside the chapter's scope.
- **Sources likely outdated within 3 years:** EU AI Act implementation details, Klarna and Duolingo case status (both currently in flux), Buffer's specific policy as published (subject to revision).
- **Disputed claim flagged:** the claim that "explicit frameworks outperform expert intuition" is well-supported in time-pressured, high-stakes domains (surgery, aviation). The transfer to marketing is suggestive but not as well-documented. State carefully.

---

## 9. Sourcing Notes

- **Parasuraman, Sheridan, & Wickens (2000):** *IEEE Trans.* paywalled; widely available via institutional access. Cite carefully.
- **Bainbridge (1983):** *Automatica* paywalled; widely cited; quotes verifiable through secondary sources.
- **Davenport & Kirby (2016):** trade book, available.
- **Atkinson & Shiffrin (1968):** classic, available in academic libraries.
- **Gawande (2009):** trade book, widely available.
- **Buffer's AI policy:** company blog, no independent verification of internal adherence. Treat as documented intent.
- **Duolingo restructuring:** Bloomberg coverage primary; Duolingo's response on company blog. Both verifiable, but the *outcome* is still developing — note as of 2026-05-27.
- **Klarna AI rollout:** Klarna press releases (claim) and FT plus later coverage (walkback). Provenance is strong for the announcement, weaker for internal metrics.
- **Microsoft, Anthropic, IBM enterprise frameworks:** vendor documentation; useful as evidence of convergence, not as independent validation.
- **NIST AI RMF 2023 and ISO/IEC 42001:2023:** publicly available standards documents; URLs stable.
- **Gartner Fortune-500 AI policy estimate:** Gartner reports are subscription; cite the report title and date, acknowledge access limitation.
