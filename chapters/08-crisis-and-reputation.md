# Chapter 8 — Crisis & Reputation

*Monitoring, flagging vs. response decisions, tone judgment*

---

## Opening case

On the morning of April 9, 2017, video of a passenger being forcibly dragged from United Express Flight 3411 began circulating on Twitter. Within four hours, the volume of mentions referencing United Airlines exceeded the airline's prior 30-day total. Within twelve hours, the video had been viewed more than 100 million times across platforms. United's initial CEO statement — issued the following morning, defensive in posture, referring to the passenger as having been "re-accommodated" — became, in itself, the second crisis. A second statement from the same CEO issued April 11 took the mortification posture (full acknowledgment, named responsibility, named corrective action). The second statement was correctly calibrated and roughly 36 hours late. (Primary sources: United's published statements, the U.S. House Transportation Committee hearing record of April 26, 2017, and the settlement announcement; the case is comprehensively documented.)

Two boundary-crossings sit inside that 36 hours. The first: the monitoring layer worked. United's tools surfaced the developing crisis within minutes. AI is genuinely good at this and the chapter will not minimize it. The second: the response posture, drafted under pressure and through a corporate-legal-formal filter, was the wrong posture for a Coombs-typology *preventable* crisis (clear human cause, clear organizational responsibility) — a posture where Situational Crisis Communication Theory (Coombs 2007, *Corporate Reputation Review* 10(3)) and decades of subsequent empirical work both predict that mortification outperforms denial or diminishment on reputation-recovery metrics. The category error was not technical. It was a judgment call made too fast by a team trained to default to defensiveness.

Eight years later, the monitoring layer is materially better. Sentiment classification has improved (transformer-based classifiers in 2024–2025 outperform the 2018 lexicon-based generation). [verify] Translation, anomaly detection, and synthetic-media flagging have moved from research to product. None of these collapse the judgment work. They make the judgment work *louder* — because the response window has compressed from days (2010) to hours (2017–2018) to single-digit hours for major incidents and minutes for active customer-service crises (2024–2025). When every brand can monitor in real time and respond fast, the question shifts from *whether* to respond to *what kind* of response. That call is human.

The aphorism this chapter wants you to carry: *AI tells you something is happening. The human tells you what kind of thing.*

---

## The pattern-shaped work in this task (Delegate List)

Across the crisis-and-reputation workflow, the following pieces are pattern-shaped and AI handles them well today:

1. **Real-time mention monitoring across platforms.** Meltwater, Brandwatch, Sprinklr, Talkwalker, Sprout Social Listening, Hootsuite Insights, Mention, Awario — vendor offerings differ on platform coverage, latency, and language depth; all of them deliver real-time monitoring at a quality that was unavailable in 2015. (Note: X / Twitter API restrictions imposed in 2023 materially changed what real-time monitoring on that platform is possible; treat any X-coverage claim as a snapshot.) [verify currency]

2. **Volume anomaly detection.** Flagging when mention rate substantially exceeds a brand's rolling baseline. Mechanical, reliable, the foundation of an alert system.

3. **Topic and entity extraction.** What is being said, about whom, with what named products / executives / events. Cluster topology from large volumes of posts is exactly what these systems are built for.

4. **Translation for international monitoring.** First-pass coverage of non-English mentions at volume. Idiom and sarcasm still benefit from human review.

5. **Aggregate sentiment classification.** Averages over thousands of posts are reliable; individual-post sentiment is not, and the gap matters during a crisis (more on this in the Guard List).

6. **Triage routing.** Routing inbound mentions to the right lane — customer-service ticket vs. reputation concern vs. brigade vs. noise — at the first-pass level. Humans confirm; AI sorts.

7. **First-draft response generation in a specified posture.** Once the human picks the response posture, AI drafts the post or the statement well. Picking the posture is the judgment work (below).

8. **Synthetic-media detection signal.** C2PA content credentials, watermark verification, technical detection scores. All useful as inputs to the verification call; none replaces it.

9. **Post-crisis sentiment tracking and recovery measurement.** The slower work of measuring whether reputation is recovering across the 90-day window. Pattern.

The Delegate List is wider in this chapter than in most. That is correct. The cost of *under-delegating* the monitoring layer during a crisis is paid in hours your team does not have. The cost of *over-delegating* the judgment layer is paid in years of reputational damage. Both directions are expensive; the directions are not symmetric.

---

## The judgment-shaped work in this task (Guard List)

Crisis-and-reputation work currently requires a human for the following:

1. **The escalation call.** A mention has been flagged. Is this an actual crisis, a customer-service ticket, a routine complaint, a coordinated bad-faith brigade, or noise? AI gives the signal; the human reads it. Useful inputs for the read: rate of growth (volume per hour vs. baseline), reach into accounts outside the brand's normal audience graph, presence of named individuals or photographic evidence, presence of journalist accounts, factual accuracy of the underlying claim.

2. **The wait-or-respond call.** Once the situation is real, is responding now or waiting one news cycle the right move? Sometimes silence works (the bad-faith pile-on that passes if not fed). Sometimes silence kills (the active safety incident where silence reads as negligence). Vosoughi, Roy & Aral (2018, *Science* 359(6380)) — the false-news-spreads-faster paper — quantifies how much faster a rumor moves than a correction on Twitter and is the empirical anchor for the cost of slow response. The cost of *fast and wrong* is higher.

3. **Tone calibration across the five postures.** Corporate-legal-formal statement; named-executive personal acknowledgment; operational customer-service response; ironic-self-aware acknowledgment (the KFC "FCK" posture); deliberate silence or refusal-to-engage. The choice is a function of crisis type (Coombs SCCT: victim / accidental / preventable), audience (B2C consumers, enterprise buyers, regulators, all of the above), prior brand voice, and the legal and reputational stakes. AI drafts any of the five competently once the human picks. AI should not pick.

4. **The legal and regulatory call.** Decisions with FTC, SEC, FDA, or EU regulatory exposure belong with counsel. SEC Regulation FD has, since the 2013 Netflix guidance, treated social-media posts by executives as potentially material disclosure for publicly traded firms. The EU AI Act (Articles 50 and 52, phased entry through 2026) [verify] adds transparency obligations specifically for AI-generated content and deepfakes in response contexts.

5. **Verifying synthetic media.** The judgment that a particular video of the CEO is or is not real, even after detection tooling has run, requires human verification through original sources — internal communications systems, the executive themself, the production environment metadata. The C2PA specification (Coalition for Content Provenance and Authenticity) gives a cryptographic backbone; the chain-of-custody decision is human. NIST's AI Risk Management Framework Generative AI Profile (2024) treats verification as a human-centered process by design.

6. **Reading the comment section around the response.** Hong & Cameron (2018, *Journal of Contingencies and Crisis Management* 26(1)) showed empirically that the conversation around a brand's response actively reshapes how the audience reads the response itself. AI tracks the conversation. The human decides what it means.

7. **The amend / double-down / silence call after the first response.** The second move in a crisis is harder than the first because the first move's effect on the conversation is now part of the input.

8. **Post-crisis program design.** The 90-day reputation-repair plan — operational follow-through, customer-service repair, deliberate positive programming, sometimes a deliberate public reckoning months later. The slow work where reputation actually rebuilds. AI supports tracking; the design is human.

9. **Naming specific accountability.** A response that names a specific leader, a specific action, and a specific deadline by which a specific thing will change is doing work no template can do. Kim & Atkinson (2014, *Public Relations Review* 40(3)) on apology format effectiveness in social channels: specificity outperforms abstraction reliably.

---

## The five postures

This is the chapter's central practical contribution. Lay them out explicitly and the calibration call becomes a choice rather than a vibe.

**Posture 1 — Corporate-legal-formal statement.** The traditional PR-issued press release adapted for the brand account. Useful when: regulatory exposure is the dominant variable, the facts are still developing, the brand has a fiduciary obligation to controlled disclosure (SEC-regulated entities, FDA-regulated entities, publicly traded firms). The cost: it reads as institutional in a medium that rewards the opposite. Boeing's 737 MAX response (October 2018 onward — sustained, multi-statement, defensive-postured through years of trajectory) is the cautionary case. Primary sources for the Boeing arc: SEC filings, Congressional hearing transcripts, the DOJ deferred-prosecution agreement (January 2021), the FAA certification report.

**Posture 2 — Named-executive personal acknowledgment.** A statement from a specific human, in their voice, with their name on it. Useful when: the crisis is preventable (Coombs typology), the audience expects accountability, the brand has a leader the audience knows. United's second CEO statement (April 11, 2017) was this posture, correctly chosen, late. The Bud Light April–May 2023 case is the inverse — silence where a CEO posture might have changed the trajectory. (AB InBev's statements, earnings-call transcripts, and 10-Q filings document the volume impact.)

**Posture 3 — Operational customer-service response.** The brand account engages publicly, by handle, in the voice of the team running the account, oriented to the specific user's specific problem. Useful when: the surfacing incident is a customer-service failure that has been amplified, the path to resolution is concrete, the resolution itself is the response. The "United Breaks Guitars" case (Dave Carroll, 2009) and the Comcast / Ryan Block call (2014) both established the pattern; the operational response is what either repairs the trajectory or fails to.

**Posture 4 — Ironic-self-aware acknowledgment.** The "FCK" posture. KFC UK's response to the February 2018 chicken-shortage crisis: a full-page newspaper ad with the logo letters rearranged, brief honest acknowledgment, agency credit to Mother London. Useful when: the crisis is accidental (Coombs typology), low harm to identifiable victims, the brand has a pre-existing irreverent voice, the cultural moment supports humor. Costly when borrowed by brands whose voice does not warrant it; a generic brand's attempt at the FCK posture reads as opportunistic and ages badly.

**Posture 5 — Deliberate silence or refusal-to-engage.** The judgment that responding amplifies. Useful when: the surfacing event is a bad-faith brigade with no real grievance; the response would itself generate the second news cycle; the brand's strategic posture is non-engagement on this category of question. Costly when the underlying claim is real and the audience reads silence as confirmation. The classification call between "brigade" and "real crisis with brigade amplification" is one of the hardest in this chapter, and the worse error is misclassifying real grievance as brigade.

The choice across the five is a judgment call. The drafting of any one, once chosen, is pattern work AI handles.

---

## Do This with AI

A working protocol for the live crisis window. Adjust to your stack.

**Step 1 — Configure monitoring (one-time, revisited quarterly).** Brand names plus common misspellings. Product names. Executive names. Key competitor names (crises sometimes arrive via competitor association). Category-risk keywords (recall, lawsuit, allergy, fire, injury, breach, outage, abuse, harm, [your category's third rails]). Language coverage matching your audience geography. Threshold rules calibrated to your baseline volume. The defaults the tool ships with are wrong for any specific brand; this configuration is a judgment task done once and refreshed.

**Step 2 — Alert triage (in-flow, under five minutes).** When the alert fires, run the escalation read. AI provides the data (rate of growth, reach delta, accounts involved, sentiment trend). Human runs the questions: is the underlying claim factually accurate; is there a safety dimension; is journalist coverage developing; is the rate of spread accelerating; is silence operationally honest.

**Step 3 — Posture selection (human, 10–30 minutes).** Apply the Coombs typology (victim / accidental / preventable) and the brand-voice-and-stake context. Pick one of the five postures. Do not split the difference. Document the rationale in two sentences — that documentation is the audit trail and the input for the second-move call later.

**Step 4 — Draft generation (AI, 5–15 minutes).** With the posture chosen and the documented facts in hand, AI drafts in that posture. Three variants is useful; the second draft is usually the one worth editing.

**Step 5 — Human edit (15–45 minutes).** Edit for specificity: named leader, named action, named deadline. Edit for what will read as defensive in the next news cycle. Run the draft past counsel if any of the following apply: publicly traded entity, regulatory exposure, named third party, ongoing investigation, employment-related disclosure.

**Step 6 — Publish and monitor the response (AI watching, human reading).** Publish. AI monitors the conversation around the response. Human reads the comment section directly — the algorithmic summary will miss the tonal signal. Hong & Cameron (2018) is the empirical backstop for why this matters.

**Step 7 — Second-move call (human, variable).** Within the first 6–24 hours: amend, double down, or go quiet. The second move is harder than the first.

**Step 8 — Post-crisis program (human-led, AI-supported, 90 days).** Operational follow-through, customer-service repair, deliberate positive programming, sometimes a slow public reckoning. The volume drops; the work does not.

**Worked example — illustrative composite.** A mid-size B2C food brand discovers, at 8:14 AM, that a customer has posted video of a foreign object found in product packaging. The post has 4,000 views, climbing. By 9 AM the volume is 40,000 views and a regional journalist has reposted.

- *Monitoring layer (AI):* alert fired at 8:17. Volume curve, source amplification, regional concentration surfaced by 8:22.
- *Escalation call (human, 8:30):* real safety dimension, factual accuracy plausible, rate of spread accelerating, journalist involved. Escalate.
- *Posture (human, 8:50):* Coombs typology *accidental* (not preventable — supply-chain anomaly under investigation); audience is B2C with a regulator (FDA) downstream; brand voice is warm. Pick named-executive personal acknowledgment (Posture 2) with an operational customer-service overlay (Posture 3) on the specific user. Document the call.
- *Draft (AI, 9:05):* three variants in posture, with explicit blanks for named QA leader, named action (independent third-party audit), named deadline (preliminary findings within 14 days), and named follow-up to the specific customer.
- *Edit (human + counsel, 9:30):* counsel review for any language that prejudges cause; edit out defensive phrasing.
- *Publish (10:10):* response goes out under named QA leader. Specific customer DM'd separately with operational response.
- *Conversation monitoring (AI watching, human reading, ongoing):* response trajectory positive; small skeptical cluster forming around timeline.
- *Second move (human, 18:00):* short update from the same named leader naming what has been confirmed in the first nine hours.
- *Day 14 follow-through:* preliminary findings published as promised. The promise was the load-bearing element.

That is the chapter in one workflow. AI handles the monitoring, the drafting, the conversation tracking. The escalation, the posture, the second move, and the follow-through belong to the human.

---

## Never Do This with AI

Seven failure modes specific to AI-in-crisis-work.

1. **Never let AI pick the posture.** The five postures are a judgment call against crisis type, audience, brand voice, and legal exposure. AI can recommend; you choose. The Pepsi / Kendall Jenner ad (April 2017) and the brand's pull statement are the canonical brand-self-inflicted case — the original ad was the result of pattern-driven creative without the judgment layer, and the response had to be human-led mortification.

2. **Never publish a template response during a live crisis.** The wave of algorithmically templated solidarity statements during the 2020 protests embarrassed dozens of brands within days; many were quietly deleted. Templates ship the wrong posture by default.

3. **Never trust individual-post sentiment scores during the live window.** Aggregate trend is useful. Individual-post sentiment fails on sarcasm, in-group language, multilingual posts, statements that mention the brand while criticizing a competitor — exactly the categories most active in a brigade. Read the comments directly.

4. **Never publish a deepfake denial without published evidence.** Verification before denial. Publish the evidence of fakeness (the C2PA content credentials, the absence-from-our-systems statement, the timestamped original-source confirmation), not only the assertion. A denial without evidence reads as defensive even when correct.

5. **Never let AI run a response on a publicly-traded entity without legal review.** SEC Regulation FD and the 2013 Netflix guidance both treat social posts by executives as potentially material disclosure. An AI-drafted post that constitutes selective disclosure is an enforcement risk. The chapter does not have to take a position on the SEC's eventual handling of AI-assisted material disclosure — the conservative move is human + counsel review on anything that could be material.

6. **Never silence a real grievance because it scored as "brigade."** The classification call between "coordinated bad-faith amplification of a non-grievance" and "real grievance with brigade amplification" is one of the hardest in the chapter. The worse error — the one with longer reputational tail — is misclassifying real grievance as brigade.

7. **Never declare the crisis over when the volume drops.** Reputation work continues for months after acute volume. The Cracker Barrel August 2025 rebrand-response reversal [verify case currency] and the multi-year Boeing 737 MAX trajectory are the recent and the long-form examples of what the "the volume is down, we're done" mistake costs. Reputation rebuilds across the slow window; the brands that allocate human attention to that window outperform.

---

## The +1

What you bring that AI cannot, in this chapter specifically:

- **The escalation read.** AI gives the signal. You read whether this is a crisis, a brigade, a ticket, or noise. The Vosoughi 2018 finding is the backstop for why the read is high-stakes: the rumor moves faster than the correction, and a missed escalation is a lost news cycle.

- **The posture pick.** Five distinct response shapes; one is right for this crisis. The pick draws on Coombs typology, brand voice, audience composition, and your read of the cultural moment. AI cannot weigh those for you.

- **The verification of synthetic media.** Detection tools score the asset. You verify through original sources — the executive themself, the production environment, the internal communications system. Ida B. Wells, working in the late 1880s and early 1890s on lynching investigation (*Southern Horrors*, 1892; *The Red Record*, 1895), built a documented practice of named-place, named-date, named-victim specificity precisely because the conventional response channels were captured or unwilling. The verification-and-evidence move is older than the technology. The principle — publish documented specifics, not assertions — is what holds up.

- **The named accountability.** A response that names a specific leader, a specific action, and a specific deadline does work no template can do. The Lillian Wald model — her Henry Street Settlement's published operational transparency during cholera, tuberculosis, and the 1918 influenza pandemic, with exactly-how-many-sick-where-and-what-services-failed reporting — is the structural analog for what operational transparency looks like inside a brand-safety crisis. AI cannot promise on the brand's behalf. You can.

- **The second move.** The second move is harder than the first because the first move is now in the conversation. Reading whether to amend, double down, or go quiet is the call AI cannot make from outside the room.

- **The 90-day program design.** The slow work where reputation actually rebuilds. AI tracks the recovery; the program is yours.

The +1 in this chapter is the practitioner who lets AI run wide on monitoring and runs hard on judgment under pressure. The cost of getting the boundary wrong here is the most visible in the book. The boundary itself is the most defensible.

---

## Claude Code prompt

*Illustrative — likely to age within 12–18 months. The structure is the durable element; the specific tool invocation will change.*

```text
You are helping me triage incoming mentions during a developing
incident. This is the Chapter 8 escalation-and-posture workflow
from Social Media Marketing +1.

CONTEXT
- Brand: [name, category, public/private, jurisdiction]
- Brand voice baseline: [warm / corporate / irreverent / etc.]
- Regulatory exposure: [SEC / FDA / FTC / sectoral / none]
- Current rolling baseline mention volume: [N per hour]
- Last 60 minutes mention volume: [N]
- Surfacing incident summary (one paragraph): [paste]

INPUT FEED (paste below)
- The most recent 30–50 mentions: handle, follower-count band,
  post text, replies/quotes/shares, timestamp.
- Any journalist or named-account mentions, flagged.
- Any photographic / video evidence noted.

DO THIS
1. Classify each mention into one of four lanes:
   - TICKET (customer-service issue, individual user, no
     broader signal)
   - NOISE (off-topic, off-brand, no signal)
   - BRIGADE (coordinated inauthentic amplification signals;
     low confidence by default — flag for human review)
   - DEVELOPING CRISIS SIGNAL (mention contributes to a
     pattern worth escalating)

2. For the DEVELOPING CRISIS SIGNAL set, surface:
   - Rate of growth (volume per hour vs. baseline)
   - Reach into accounts outside the brand's normal graph
   - Presence of named individuals or photographic evidence
   - Presence of journalist accounts
   - Plausible factual accuracy of the underlying claim
     (with explicit "human verification required" flag)

3. Propose a Coombs typology read: VICTIM / ACCIDENTAL /
   PREVENTABLE / UNCLEAR. Note what would resolve the
   classification.

4. Recommend ONE of the five postures with reasoning:
   - Corporate-legal-formal
   - Named-executive personal acknowledgment
   - Operational customer-service response
   - Ironic-self-aware acknowledgment
   - Deliberate silence or refusal-to-engage
   Note explicitly that the recommendation is for human
   review and decision, not for automatic adoption.

5. If a response posture other than silence is selected by
   the human, draft three response variants in that posture,
   with explicit blanks marked HUMAN FILL for: named leader,
   named action, named deadline, named follow-up to specific
   user(s).

DO NOT
- Score individual-post sentiment as a single number; describe
  observable signals.
- Make the posture call. Recommend; flag for human decision.
- Publish or schedule. Output drafts only.
- Cite legal or regulatory provisions as binding; cite as
  starting points for counsel review.

OUTPUT FORMAT
- Markdown.
- Sections: Lane classifications; Developing-crisis signals;
  Coombs read; Posture recommendation with reasoning; Draft
  variants (only if posture other than silence chosen);
  Verification flags for counsel.
- Footer: explicit list of items requiring human decision
  before any response is published.
```

---

## Key terms

**Situational Crisis Communication Theory (SCCT).** Coombs's typology (victim / accidental / preventable) of crisis types, with empirically-validated response-posture matching. The primary academic framework for "what response does this situation call for." Pre-dates the social era but the typology holds.

**Image restoration / image repair.** Benoit's framework (1995, revised 2015) for response-strategy categories: denial, evasion of responsibility, reducing offensiveness, corrective action, mortification. The five postures in this chapter map loosely onto Benoit categories operationalized for social media.

**Mortification.** Benoit's term for the response posture of full acknowledgment, accepting responsibility, requesting forgiveness, and committing to corrective action. Empirically the highest-recovery posture for *preventable* crises in the Coombs typology.

**Operational transparency.** The posture of publishing specifically what is being done, by whom, by when, during an ongoing situation. Wald-style, applied to brand-safety incidents. Outperforms abstraction reliably.

**Deepfake / synthetic media.** Generative-AI-produced audio, image, or video misrepresenting a real person's speech or action. The 2023–2024 wave of executive-impersonation fraud cases is the documented backdrop. Verification, not detection alone, is the load-bearing response capability.

**Content provenance / C2PA.** The Coalition for Content Provenance and Authenticity technical specification (1.x) for cryptographic content credentials. Increasingly adopted by camera makers, generative-AI vendors (OpenAI, Adobe, Microsoft), and platforms (TikTok, LinkedIn beginning rollout 2024–2025). [verify currency] One input to the verification call.

**Trusted flagger.** The EU Digital Services Act (Articles 16, 22) mechanism for designated parties to flag content for expedited platform review. Brands operating in the EU interact with this system during takedown requests; the relationship needs to be established before the crisis, not during.

**Brigade vs. crisis.** The classification call between coordinated inauthentic amplification of a non-grievance and a real grievance amplified by coordinated inauthentic activity. The worse error is misclassifying real grievance as brigade; the chapter's bias is toward escalation when the call is genuinely unclear.
