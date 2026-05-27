# Chapter 10 — Building Your Own Map

*Domain calibration: turning the framework into your Delegate/Guard List*

---

## Opening case

A mid-size registered investment adviser — call the firm Meridian Wealth, a roughly $1.4B AUM RIA in the Midwest — rolled out an "AI content acceleration" program in Q2 2024. The plan was unobjectionable on paper: a marketing coordinator would draft LinkedIn posts in ChatGPT, the CCO would approve in batch on Fridays, and the firm would triple its publishing cadence inside a quarter. (Illustrative composite; the pattern is documented across multiple FINRA enforcement summaries and compliance trade press through 2024–2025.)

Three things happened in the first month.

First, output tripled, as predicted. Second, the CCO's Friday review went from a 45-minute task to a 4-hour task, because every post now needed line-by-line testing against the SEC Marketing Rule's prohibitions on testimonials, performance implications, and any language that could be read as a guarantee. The "approval bottleneck" Hammer warned about in 1990 — "Don't automate, obliterate" — had moved, not disappeared. Third, in week six, one post slipped through. A coordinator had asked ChatGPT to "make it punchier," and the model produced a sentence that read, in context, as a performance promise. It was up for 90 minutes before a junior compliance analyst caught it. The firm's outside counsel spent two weeks documenting the incident in case of a subsequent exam.

The lesson the firm drew was not "stop using AI." It was that the Delegate/Guard List they had borrowed from a general-purpose marketing podcast had no idea what an RIA's content even is. Static, pre-approved, retainable content under FINRA 17-18 lives in one regulatory universe; interactive, real-time response lives in another; performance language lives in a third. A delegation map calibrated for a B2B SaaS startup or a DTC apparel brand will get an RIA fined.

The map has to be yours.

---

## The pattern-shaped work in this task (Delegate List)

The map-building task itself is partly patterned. AI can do the following pieces well:

1. **Inventory generation.** Given a description of your role, AI can produce a starter list of recurring social marketing tasks — captions, scheduling, paid copy variants, comment triage, analytics summaries, monthly recaps. You then add brand-specific tasks the model couldn't know.
2. **Taxonomy proposal.** AI can sort your inventory along the chapter's three axes (pattern vs. judgment shape; regulatory weight; reputational tail-risk) as a first cut you correct.
3. **Regulatory citation lookup.** For named regulatory regimes — FINRA, SEC, FDA, HIPAA, FTC, the EU AI Act — AI can surface the canonical citations and produce a plain-language summary of what each one constrains. You verify against the agency's site before relying on it.
4. **Workflow-diagram draft.** Given your inventory and classification, AI can produce a swim-lane diagram (text or Mermaid) showing AI lanes, human lanes, and handoffs. You refine the boundary.
5. **Delegation-profile template-filling.** AI can produce the boilerplate of a brand-by-brand or client-by-client delegation profile (sanctioned tools, content types eligible for AI drafting, mandatory review steps, platform-specific Guards) for you to edit.
6. **Calibration prompt drafts.** AI can write the prompts that go into your prompt library for each Delegate List task — captions, A/B variants, analytics narration, hashtag research.
7. **Memo drafting.** AI can draft the socialization memo you'll take to compliance, legal, or your manager to get the map adopted. You bring the politics.

These are pattern-shaped because the structure of the output is determined by the structure of the input plus a known framework. Nothing in this list requires a judgment call about *your* brand, *your* audience, or *your* regulatory exposure.

---

## The judgment-shaped work in this task (Guard List)

Building the map itself currently requires a human for the following:

1. **The regulatory exposure call.** Whether your business is in fact regulated by FINRA, the SEC, the FDA, HIPAA, state bar rules, Reg FD, charitable-solicitation registration, or some combination — and at what threshold — is a determination only your legal/compliance counsel can make. AI can summarize the rules; only a person accountable to your organization can attest to which ones apply.
2. **The reputational tail-risk assessment.** What happens to your brand if a given post goes wrong? AI cannot tell you whether your audience will forgive a tone-deaf caption or whether your investors will not. That call requires your knowledge of audience, market position, and history.
3. **The "judgment surface" articulation.** Why you, specifically, draft a particular kind of post rather than delegating it. Practitioners often discover the answer is "I can't quite say." That is Polanyi's Paradox surfacing in your own workflow — what David Autor named in 2015 borrowing from Polanyi's 1966 *The Tacit Dimension*: we know more than we can tell. The articulation itself is a human task, because tacit knowledge resists external description.
4. **The accountability locus decision.** Whether your brand voice runs to a named person (a founder, a CEO, a partner) or diffuses across a team determines what can be delegated. Only you can map that for your org.
5. **The agency meta-judgment.** If you are at an agency, the call about which delegation profile applies to which client is itself a judgment task. Two clients in nominally the same industry can have different risk tolerances, different general counsel, different platform commitments.
6. **The boundary-case selection.** Which tasks sit on the line between Delegate and Guard right now, and which you will re-audit next quarter, is a calibration call about *your* tolerance for risk and *your* org's appetite for experimentation.
7. **The socialization politics.** How you present the map to compliance, legal, your manager, or your CEO — what framing they will accept, what they will reject, what tradeoffs they will pre-approve — is org-political work. AI can draft the memo; it cannot read your CCO.

---

## Do This with AI

A working protocol you can run in roughly half a working day. This draws on value-stream mapping (Womack and Jones, *Lean Thinking*, 1996) and the Lillian Gilbreth lineage of process mapping that treats the worker's tacit skill as part of the system being measured.

**Step 1 — Inventory (30 min).** Open a document. List every social marketing task you have touched in the last two weeks. Use the chapter sequence (Chs 3–9) as a checklist: content creation, community management, analytics, paid social, influencer, crisis monitoring, platform execution. Add brand-specific tasks the chapters don't cover. Aim for 25–40 line items.

Prompt block to seed it:

> "I'm a [role] at a [industry] [org type]. Based on my last two working weeks, here are the social marketing tasks I performed: [paste inventory]. Group these into 6–8 task families. Flag any standard task families typical for my role that I haven't listed."

**Step 2 — Classify (45 min).** For each task, score on three axes:
- *Shape:* pattern-shaped (rule-following, repeatable, decomposable) or judgment-shaped (context-dependent, accountability-bound, novel).
- *Regulatory weight:* none / light (FTC endorsement only) / heavy (FINRA, SEC, FDA, HIPAA, state bar, Reg FD).
- *Reputational tail-risk:* low (a bad post embarrasses no one), medium (a bad post costs goodwill), high (a bad post becomes a news cycle, a regulatory inquiry, or a customer-trust event).

A task that is judgment-shaped + heavy regulatory + high tail-risk goes on the Guard List by default. A task that is pattern-shaped + light + low goes on the Delegate List by default. Everything else is a boundary case.

**Step 3 — Tool audit (30 min).** For each task currently touched by AI: which tool, on what account (enterprise or personal), with what logging, with what review? The Salesforce 2024 *State of Marketing AI* survey and Microsoft's 2024–2025 *Work Trend Index* both document that the majority of knowledge workers using AI at work do so on personal accounts on unsanctioned tools. [verify] Surface this without scolding — you cannot calibrate what you cannot see.

**Step 4 — Draft the Delegate List (45 min).** Write out, in active voice, the tasks where AI will do the bulk of the work and a human will review. For each, specify: which AI tool category, what the prompt looks like, what the human reviewer checks, what gets logged.

**Step 5 — Draft the Guard List (45 min).** Write out the tasks where humans do the bulk of the work and AI assists at most (research, summary, outline). For each, specify: what AI may *not* do (e.g., "may not draft any post mentioning a brand-name drug"), what the human must do, what the documentation trail looks like.

**Step 6 — Identify boundary cases (20 min).** List three to five tasks that should plausibly move from one list to the other within the next two quarters. These are your re-audit candidates. Schedule the re-audit now.

**Step 7 — Test the map (one week).** Run a one-week trial. At the end of the week, note where the map broke — over-delegation that produced a bad output, under-delegation that wasted time, a task that fell through both lists. Revise.

**Step 8 — Socialize (variable).** Draft the memo for compliance, legal, or your manager. Frame the map as a risk-management document, not just a productivity document. That framing is what gets it adopted in regulated organizations.

**Sample worked output — the Meridian RIA case.**

*Delegate List (excerpt):* draft static, evergreen educational LinkedIn posts on diversification, market history, retirement planning principles — for principal pre-approval and Form 17a-4 retention. Generate three caption variants for an already-approved core claim. Summarize quarterly market commentary into a five-bullet recap. Draft monthly analytics recap for internal use. Produce hashtag research and post-time recommendations.

*Guard List (excerpt):* any post implying performance, any testimonial-adjacent language, any interactive response in comments or DMs, any post about a specific holding or recommendation, any response to a client identified by name in a public post, any content during a quiet period before earnings of a held position, any AI-generated image of a real client or employee.

*Boundary cases:* AI-assisted compliance review (currently Guard; possibly Delegate by Q1 next year with vendor sign-off); AI-drafted comment response with mandatory CCO release-to-send (currently Guard; trial proposed); AI-summarized client question intake for advisor triage (currently Delegate with PII review; needs HIPAA-style audit even though firm is not HIPAA-regulated, because the data is sensitive).

---

## Three contrast cases — same method, different maps

**Founder-led DTC brand (consumer apparel, US-based, ~$30M revenue).** Founder's voice on Instagram and TikTok is the asset. Delegate List is wide on production work — scheduling, paid copy variation, comment triage, analytics narration. Guard List is narrow but load-bearing: anything attributed to the founder's voice, anything responding to a customer with a service complaint, anything political, anything about supply chain that could become contractual. The founder's *call about which posts get made* is itself the irreducibly human input. AI cannot tell her whether today is the day to post the bit about her father's funeral; she has to.

**Hospital system (Midwest academic medical center, ~$3B revenue).** HIPAA dominates. PHI — the 18 identifiers under 45 CFR Part 164 — is the third rail. Delegate List: disease-awareness content not tied to any patient, generic wellness content, event promotion, recruiting content for clinical staff. Guard List: anything that could be a patient testimonial without HIPAA authorization, anything responding to a public patient post, anything touching protected health information in any form, anything about specific clinical outcomes. The Cleveland Clinic, Mayo Clinic, and similar academic centers have published their own social policies that practitioners can reference as documented examples. [verify currency]

**B2B SaaS startup (Series B, ~$40M ARR).** Light regulatory regime; the constraint is sales-marketing alignment and account-based marketing. Delegate List: top-of-funnel thought leadership drafts, paid copy variants for testing, webinar promotion, analytics summaries, comment triage on non-account posts. Guard List: any content touching a named account in an active deal cycle, any executive quote attributed to a founder without sign-off, any response to a customer in a public escalation, any competitive comparison. The salesperson context — what is happening in deal cycles right now — becomes the gating Guard item. AI cannot see the CRM unless you wire it in, and you may not want it to.

The method generalizes. The lists do not.

---

## Never Do This with AI

Six failure modes specifically about the map-building process.

1. **Borrowing someone else's map wholesale.** The Meridian case at the top of this chapter is what happens. A general-purpose AI marketing prompt library has not done your regulatory analysis. It cannot.
2. **Treating the map as static.** A map written in January and untouched in October is misleading by October. Capability changes; regulatory guidance changes; your org changes. Quarterly review is non-negotiable.
3. **Skipping the tool audit step.** If you do not surface shadow AI use — personal accounts, unsanctioned tools, unlogged prompts — your map describes a workflow that does not exist. The audit is the data, not an accusation.
4. **Letting AI write the Guard List unsupervised.** AI will generate a plausible-looking list. Plausible is not safe. The Guard List is exactly where the model's training data is least reliable, because regulatory specificity varies by jurisdiction, by year, by ruling, and by enforcement priority.
5. **Outsourcing the judgment-surface articulation.** If you ask AI to explain *why* you personally guard a certain kind of post, you get a confident-sounding answer that is probably not your actual reason. The discomfort of articulating tacit knowledge is the work. Do it yourself.
6. **Building the map without bringing compliance into the conversation.** In regulated industries, a delegation map that does not have the CCO's or general counsel's fingerprints on it is shelfware. You will revert to manual drafting the first time something feels uncertain, because nobody has authorized you to delegate. Bring them in early.

---

## The +1

In every previous chapter, the +1 was the human review of a specific AI output. In this chapter, the +1 steps up a level: you become the *designer* of your own delegation system. You stop being a consumer of the framework and become a practitioner of it.

What you bring that AI cannot:

- **Accountability for the map itself.** If a post goes wrong because the map allowed it, you are answerable. That answerability is what makes the map worth anything. You cannot delegate accountability to a model that is structurally incapable of being answerable.
- **Local knowledge.** Your industry, your org, your client roster, your specific regulatory exposure, your audience's tolerances. The model does not have these. You do.
- **The political work.** A map that compliance has signed off on is operative. A map compliance has not seen is theatre. Only a human can read a CCO.
- **The tacit-knowledge audit.** Mary Parker Follett, writing in the 1920s on the "law of the situation," argued that authority comes from the specific facts of the case, not from a generic rule. Your delegation map is the law of *your* situation. AI can offer a generic rule; only you can describe the situation.
- **The discipline to maintain it.** The map is a living document. Quarterly review is a habit. Habits require a person.

The chapter 10 +1 is the practitioner as calibrator. Pattern is universal. Judgment is local. The map is local because judgment is local.

---

## Claude Code prompt

*Illustrative — likely to age within 12–18 months. The structure is the durable element; the specific tool invocation will change.*

```text
You are helping me build a domain-calibrated Delegate/Guard map
for my social media marketing work. This is the Chapter 10
audit from Social Media Marketing +1.

CONTEXT
- My role: [role]
- My org: [industry, org type, headcount, geography]
- Regulatory regimes I think apply: [FINRA / SEC / FDA / HIPAA /
  FTC / state bar / Reg FD / EU AI Act / GDPR / none / other]
- Brand voice / accountability locus: [founder-led / corporate /
  multi-client agency / sole proprietor]
- Tools currently in use: [list, noting personal vs. enterprise]

INPUTS (paste below)
1. Two-week task inventory: [paste]
2. Recent posts I drafted manually because I did not feel
   comfortable delegating: [paste 3–5 examples]
3. Recent posts where I delegated to AI and was satisfied:
   [paste 3–5 examples]

DO THIS
1. Group my inventory into 6–8 task families.
2. For each task family, propose a classification on the three
   axes: pattern-shape vs. judgment-shape; regulatory weight;
   reputational tail-risk.
3. Draft a starter Delegate List and Guard List I will edit.
4. Identify three boundary cases I should re-audit next quarter
   and explain why each is on the boundary.
5. For tasks I drafted manually (input 2), name the most likely
   reason in plain language — not flattering, not dismissive.
   Help me articulate tacit judgment.
6. For tasks I delegated (input 3), name any failure mode that
   could surface in the next quarter that I should monitor.

DO NOT
- Cite specific regulatory provisions as binding. Cite as
  starting points I will verify with counsel.
- Produce a final map. Produce a draft I will edit and have
  reviewed by compliance and legal.
- Recommend specific AI products. Recommend categories.

OUTPUT FORMAT
- Markdown.
- Sections: Inventory grouping; Three-axis classification;
  Delegate List (draft); Guard List (draft); Boundary cases;
  Judgment-surface notes; Watch items.
- Footer: a checklist of who should review this draft before
  it is operative.
```

---

## Key terms

**Delegation profile.** A brand- or client-specific document naming which AI tools are sanctioned, which content types are eligible for AI drafting, what review steps are non-negotiable, and what platform-specific guards apply. Built at onboarding, refreshed quarterly.

**Judgment surface.** The area of your work where tacit, context-dependent, accountability-bound decisions live. It is what cannot be reduced to a pattern even after the pattern-shaped work is delegated. Wider in regulated industries, in founder-led brands, and in crisis-adjacent communications.

**Boundary case.** A task that plausibly sits on the line between the Delegate List and the Guard List given current capability and current org constraints. Boundary cases are the items you re-audit deliberately, not the items you guess about in the moment.

**Pattern-shape / judgment-shape.** The Chapter 2 distinction: pattern-shaped work is rule-following, repeatable, decomposable; judgment-shaped work is context-dependent and accountability-bound. The map sorts your inventory along this axis first.

**Shadow AI.** AI use on personal accounts on unsanctioned tools, undocumented in the org's official workflow. Empirically dominant in 2024–2025 workforce surveys. [verify] Surface it during the audit; do not punish it; design around it.

**Accountability locus.** Whether the brand voice runs to a named individual (founder, CEO, partner) or diffuses across a team. Determines how much of voice work can be delegated.

**Value-stream map (applied to marketing).** Borrowed from Womack and Jones (*Lean Thinking*, 1996) and the Gilbreth process-chart tradition. A diagram showing each step in a workflow with explicit lanes for which work is automatable, which requires human judgment, and where handoffs occur. The Delegate/Guard map is a value-stream map with AI as one lane.

**Socialization memo.** The document you take to compliance, legal, or your manager to get the map operative inside your org. Frames the map as a risk-management instrument, not just a productivity instrument. The Guard List is the load-bearing part for this audience.
