# CAJAL Figure Intelligence — Chapter 8: Crisis & Reputation

**Source:** `chapters/08-crisis-and-reputation.md`
**Mode:** `/scan silent`
**Domain note:** AI+1 practitioner handbook / social media marketing. Chapter opens with United Express Flight 3411 (April 9, 2017) — monitoring worked, the 36-hour posture error did not. W. Timothy Coombs SCCT (2007, *Corporate Reputation Review*) is the typology spine. Hong-Cameron (2018, *JCCM*) on the conversation-around-the-response. Vosoughi-Roy-Aral (2018, *Science*) on false-news velocity. NIST AI RMF Generative AI Profile (2024) and C2PA on synthetic-media verification. SEC Regulation FD + 2013 Netflix guidance + EU AI Act Articles 50/52. Author-marked figure slots at lines 33, 49, 73, 109.

---

## Density Recommendation

**5 figures, High-Stakes-Decision density.** This is the chapter where errors are most publicly legible, and the visual support needs to be denser than the other chapters. Figure 8.1 (Coombs SCCT decision tree mapping crisis type to posture) is the chapter's most consequential pedagogical contribution and author-marks it. Figure 8.2 (Vosoughi false-news velocity vs correction) makes the time-cost visceral. Figure 8.3 (escalation read decision flow) operationalizes the 5-minute classification. Figure 8.4 (crisis response timeline with AI/human zones) is author-marked. Figure 8.5 (synthetic-media verification chain of custody) is the new failure mode the chapter introduces. The Delegate List table and Guard List table are declined per CAJAL discipline.

---

## Zone Map

- **MC:** The five postures (corporate-legal-formal / named-executive personal acknowledgment / operational customer-service / ironic-self-aware / deliberate silence) mapped to Coombs SCCT crisis types (victim / accidental / preventable). The 36-hour gap as posture error, not monitoring error. Verification chain of custody for synthetic media.
- **VG:** Vosoughi false-news velocity curve vs correction curve. Escalation read decision tree (crisis / brigade / ticket / noise). Crisis response timeline with AI-handled and human-judgment nodes.
- **PQ:** United Flight 3411 (April 9, 2017) — 100M video views in 12 hours, 36-hour posture correction. Coombs SCCT (2007). KFC FCK chicken shortage (Feb 2018). Bud Light (Spring 2023). Boeing 737 MAX (Oct 2018 → Jan 2021 DOJ DPA). Pepsi/Kendall Jenner (April 2017). Comcast/Ryan Block (2014). Dave Carroll "United Breaks Guitars" (2009). Vosoughi-Roy-Aral 2018. Hong-Cameron 2018. Kim-Atkinson 2014. SEC Reg FD 2000 + 2013 Netflix guidance. EU AI Act Articles 50/52 phasing 2026. NIST AI RMF 2024. C2PA. Ida B. Wells *Southern Horrors* (1892), *The Red Record* (1895). Lillian Wald / Henry Street Settlement transparency reports.

---

## Figure 8.1 — Coombs SCCT Crisis Type → Posture Decision Tree

**Priority: Critical.** Author-marked at line 33. The chapter's central pedagogical contribution. Without this, the five postures stay as a list rather than a decision space.

### Block 1 — Illustrae paste block

A vertical decision tree composition. Top node: a Sky Blue `#56B4E9` filled diamond representing the entry question (Coombs crisis type?). Three branches descend. Left branch (Victim): descends to a Bluish Green `#009E73` filled circle representing the Operational Customer-Service posture, with a small Black `#000000` 1pt arrow alongside indicating Comcast/Ryan Block as the canonical case. Middle branch (Accidental): descends to a second Sky Blue diamond (brand voice irreverent?). Two sub-branches from this: yes-irreverent → an Orange `#E69F00` filled circle (Ironic-Self-Aware, KFC FCK); no → a Bluish Green `#009E73` filled circle (Operational + brief acknowledgment). Right branch (Preventable): descends to a third Sky Blue diamond (regulatory exposure?). Two sub-branches: yes-regulatory → a Vermillion `#D55E00` filled circle with a small Reddish Purple `#CC79A7` outlined ring (Corporate-Legal-Formal with counsel, Boeing); no-regulatory → a Vermillion `#D55E00` filled circle (Named-Executive Personal Acknowledgment, United Apr 11). To the right of the tree, separate: a small Blue `#0072B2` filled circle labeled in negative space as Deliberate Silence — applies only when the surfacing event is a bad-faith brigade with no real grievance; a dashed Black `#000000` 1pt connector signals the off-tree status. Connectors are Black `#000000` 1pt lines throughout. White background, flat vector, double-column 174mm preferred. Max 8 distinct component types.

### Block 2 — Full SCOPE prompt

[S] Double-column 174mm preferred, vector, white background.
[C] Vertical Coombs SCCT decision tree. Root: crisis type? Three branches: Victim → Operational; Accidental → split on brand voice (Ironic or Operational+ack); Preventable → split on regulatory exposure (Corporate-Legal with counsel ring, or Named-Executive). Deliberate-Silence terminal sits off-tree with dashed connector indicating its special-case status.
[O] Vertical tree. Three diamond decision nodes (one root, two sub). Five posture terminals (four on-tree, one off-tree). Counsel ring on the regulatory-exposure terminal.
[P] Decision diamonds Sky Blue. Operational-posture terminals Bluish Green. Ironic-posture terminal Orange. Named-Executive terminal Vermillion. Corporate-Legal terminal Vermillion with Reddish Purple counsel ring. Deliberate-Silence terminal Blue with dashed connector. Connectors Black 1pt.
[E] No posture names rendered in image, no canonical case names, no Coombs typology text, no decorative ornament, no shadows.

### Block 3 — Negative prompt

text labels, posture names, canonical case names, Coombs typology text, brand names, gibberish letters, titles, captions, decorative ornament, photographic elements, realistic 3D textures, drop shadows, gradient fills, gradient backgrounds, hand-drawn styles, sketch lines, decorative borders, colorful backgrounds, visual clutter, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 8.2 — Vosoughi False-News Velocity vs Correction

**Priority: Critical.** Makes the time-compression that frames the chapter visceral. Anchors the Vosoughi-Roy-Aral 2018 finding without which the 36-hour cost cannot be read.

### Block 1 — Illustrae paste block

A horizontal two-curve time-series composition. Horizontal axis: time, hours from t=0 (left) extending rightward. Vertical axis: cumulative reach, low-to-high. Two curves rise from the origin. Upper curve (false-news cascade): a steep Vermillion `#D55E00` 2pt curve climbing rapidly, leveling off high on the right. Lower curve (correction / counter-statement): a shallower Blue `#0072B2` 2pt curve climbing more slowly, with significant horizontal lag, never catching up to the upper curve in the visible window. Between the two curves, a vertical Reddish Purple `#CC79A7` 1pt double-headed arrow at the t=12h mark indicating the cumulative-reach gap at that decision point. A small Vermillion `#D55E00` filled triangle on the upper curve at t=12h marks the 100M-view threshold from the United case. A small Orange `#E69F00` filled circle on the lower curve at t=36h marks the late-correction moment — when United's second statement landed. Below the time axis, two small Bluish Green `#009E73` filled tick marks at t=0 and t=4h indicate the monitoring-tool flag-fire window — when AI alerted, well before either curve's inflection. White background, flat vector, double-column 174mm preferred. Max 7 distinct components.

### Block 2 — Full SCOPE prompt

[S] Double-column 174mm preferred, vector, white background.
[C] Two cumulative-reach curves over time. Upper curve is the false-news / crisis cascade (Vosoughi-style steep climb). Lower curve is the correction / brand response (slower climb, persistent lag). Vertical gap arrow at t=12h shows the cumulative-reach gap at decision point. Late-correction marker at t=36h shows the United-case posture-error cost. Monitoring tick marks early on the axis show that the AI flag fires long before either curve inflects.
[O] Horizontal time axis. Vertical reach axis. Two curves rising from origin. Gap arrow between them at t=12h. Markers at key moments. Monitoring ticks below axis at early time.
[P] Crisis cascade curve Vermillion 2pt. Correction curve Blue 2pt. Gap arrow Reddish Purple. 100M-view marker Vermillion triangle. Late-correction marker Orange. Monitoring tick marks Bluish Green.
[E] No axis numbers, no hour-mark labels rendered, no platform names, no brand names, no decorative ornament, no shadows.

### Block 3 — Negative prompt

text labels, axis numbers, hour labels, platform names, brand names, gibberish letters, titles, captions, decorative ornament, photographic elements, realistic 3D textures, drop shadows, gradient fills, gradient backgrounds, hand-drawn styles, sketch lines, decorative borders, colorful backgrounds, visual clutter, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 8.3 — The Five-Minute Escalation Read

**Priority: Important.** Operationalizes the chapter's most time-pressured judgment moment. Not author-marked but central to the protocol section.

### Block 1 — Illustrae paste block

A vertical decision tree composition. Top node: a Sky Blue `#56B4E9` filled diamond representing the alert-fired entry. Five inputs feed into the diamond from the left as small horizontal arrows: rate-of-growth (Bluish Green `#009E73`), reach delta (Bluish Green), accounts involved (Bluish Green), sentiment trend (Bluish Green), and journalist coverage (Bluish Green) — these are the AI-supplied data. Below the diamond, four sub-branches descend to four terminal circles arranged horizontally. Left terminal (Crisis): Vermillion `#D55E00` filled, with a small Reddish Purple `#CC79A7` outlined ring — escalate to posture decision (Fig 8.1). Center-left terminal (Brigade): Orange `#E69F00` filled — possible silence or watch-and-wait, classification call carries highest mis-classification risk. Center-right terminal (Ticket): Bluish Green `#009E73` filled — operational customer-service, route to support. Right terminal (Noise): a small Blue `#0072B2` outlined circle — no action. Below the four terminals, a horizontal Vermillion `#D55E00` 1pt dashed line indicates the misclassification-cost asymmetry, with a small Vermillion filled arrow pointing from Brigade toward Crisis indicating that the more dangerous error direction is mis-classifying real grievance as brigade. White background, flat vector, single-column 89mm. Max 8 distinct component types.

### Block 2 — Full SCOPE prompt

[S] Single-column 89mm, vector, white background.
[C] Five-minute escalation decision tree. Five AI-supplied inputs feed the central diamond. Four terminals: Crisis (escalate), Brigade (silence or watch), Ticket (operational), Noise (no action). Misclassification-asymmetry arrow shows that calling real grievance brigade is the costlier error direction.
[O] Vertical tree. Five input arrows from left. Central decision diamond. Four terminals arranged horizontally below. Misclassification-asymmetry indicator below terminals.
[P] Decision diamond Sky Blue. AI inputs Bluish Green arrows. Crisis terminal Vermillion with Reddish Purple ring. Brigade terminal Orange. Ticket terminal Bluish Green. Noise terminal Blue outline. Asymmetry indicator Vermillion dashed.
[E] No input names rendered, no terminal names in image, no decorative ornament, no shadows.

### Block 3 — Negative prompt

text labels, input names, terminal names, brand names, platform names, gibberish letters, titles, captions, decorative ornament, photographic elements, realistic 3D textures, drop shadows, gradient fills, gradient backgrounds, hand-drawn styles, sketch lines, decorative borders, colorful backgrounds, visual clutter, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 8.4 — Crisis Response Timeline: AI Handles / Human Decides

**Priority: Important.** Author-marked at line 109. Operationalizes the protocol by sequencing the timeline with handoffs explicit.

### Block 1 — Illustrae paste block

A horizontal seven-stage timeline composition. Seven sequential nodes drawn as rounded rectangles, connected by Black `#000000` 1pt directional arrows. Stage 1 (configure monitoring, quarterly): Vermillion `#D55E00` filled — human, pre-crisis. Stage 2 (alert fires): Bluish Green `#009E73` filled — AI. Stage 3 (escalation read, 5 min): Vermillion filled with a Reddish Purple `#CC79A7` ring — human, highlighted, load-bearing. Stage 4 (posture pick): Vermillion filled with a Reddish Purple ring — human, highlighted as the second high-stakes decision. Stage 5 (draft in posture, 30 min): split node, left half Bluish Green (AI drafts variants), right half Orange `#E69F00` (Delegate-with-Review, edit for specificity). Stage 6 (publish + read comments, 6 hr): split node, left half Bluish Green (AI tracks aggregate sentiment), right half Vermillion (human reads comment section directly, Hong-Cameron 2018). Stage 7 (second move, 6–24 hr): Vermillion filled with a Reddish Purple ring — human, highlighted as the third high-stakes decision. Below the seven-stage row: a Sky Blue `#56B4E9` 1pt horizontal timeline arrow with three time tick-marks indicating pre-crisis (left), live window (center), and 90-day program (right). White background, flat vector, double-column 174mm preferred. Max 8 distinct component types.

### Block 2 — Full SCOPE prompt

[S] Double-column 174mm preferred, vector, white background.
[C] Seven-stage crisis response timeline. Pre-crisis configure (human). Alert fires (AI). Escalation read, posture pick, second move — three high-stakes human decisions, each with highlight rings. Draft (split AI/Delegate-with-Review) and publish-and-read (split AI/human) show handoffs explicitly. Timeline below the row indicates pre-crisis, live, and 90-day program zones.
[O] Seven nodes in horizontal sequence. Highlight rings on three high-stakes decisions. Split nodes show left-half (AI) and right-half (human or Delegate-with-Review). Timeline arrow with time tick-marks below.
[P] Fully-human stages Vermillion. Fully-AI stages Bluish Green. Delegate-with-Review halves Orange. Mixed-stage AI halves Bluish Green, human halves Vermillion. Highlight rings Reddish Purple. Timeline Sky Blue. Connector arrows Black 1pt.
[E] No stage names rendered, no time durations as graphics, no decorative ornament, no shadows.

### Block 3 — Negative prompt

text labels, stage names, time durations, tool names, vendor logos, brand names, gibberish letters, titles, captions, decorative ornament, photographic elements, realistic 3D textures, drop shadows, gradient fills, gradient backgrounds, hand-drawn styles, sketch lines, decorative borders, colorful backgrounds, visual clutter, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 8.5 — Synthetic-Media Verification Chain of Custody

**Priority: Recommended.** The chapter introduces a new failure-mode class (executive impersonation, fabricated audio/video) that has no clean prior-era analog. The verification chain deserves its own diagram.

### Block 1 — Illustrae paste block

A horizontal pipeline composition. Five sequential nodes connected by Black `#000000` 1pt directional arrows. Node 1 (incoming asset): a Sky Blue `#56B4E9` filled rounded square representing the suspect video/audio/image arriving. Node 2 (detector score): a Bluish Green `#009E73` filled rounded square — AI confidence value. Node 3 (C2PA cryptographic check): a Bluish Green filled rounded square — provenance signal. Node 4 (chain-of-custody verification): a Vermillion `#D55E00` filled rounded square with a Reddish Purple `#CC79A7` outlined ring — human verification through the named executive, the production environment metadata, the internal communications system. Node 5 (public response): a Vermillion filled rounded square — denial published with evidence, not assertion alone. Above the pipeline, a small Orange `#E69F00` filled exclamation-shape hovering over Node 2 indicates the inadequate-without-Node-4 failure mode: a denial based on detector score alone reads as defensive. Below the pipeline, a Vermillion `#D55E00` 1pt dashed arrow loops from Node 5 back to Node 4 indicating that the published evidence is itself part of the chain of custody. White background, flat vector, double-column 174mm preferred. Max 7 distinct components.

### Block 2 — Full SCOPE prompt

[S] Double-column 174mm preferred, vector, white background.
[C] Five-stage synthetic-media verification pipeline. Incoming asset → detector score (AI) → C2PA check (AI) → chain-of-custody verification (human, highlighted) → public response with published evidence. Inadequate-without-Node-4 marker over the detector score. Looping arrow from response back to custody indicates published evidence is itself part of the verification record.
[O] Five nodes in horizontal pipeline. Directional arrows. Highlight ring on Node 4. Warning marker above Node 2. Looping arrow below from Node 5 back to Node 4.
[P] Incoming asset Sky Blue. AI nodes Bluish Green. Human verification node Vermillion with Reddish Purple ring. Public response Vermillion. Inadequate-detector warning Orange. Loop arrow Vermillion dashed.
[E] No node names rendered, no detector tool names, no executive names, no platform names, no decorative ornament, no shadows.

### Block 3 — Negative prompt

text labels, node names, tool names, vendor logos, executive names, platform names, gibberish letters, titles, captions, decorative ornament, photographic elements, realistic 3D textures, drop shadows, gradient fills, gradient backgrounds, hand-drawn styles, sketch lines, decorative borders, colorful backgrounds, visual clutter, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## What CAJAL Declines to Architect

- **Five-postures-mapped-to-Coombs table (line 33).** The decision tree in Fig 8.1 is the better visual — it makes the typology a decision space rather than a reference table.
- **Delegate List table (line 49).** Reference table; typography is the right register.
- **Guard List table (line 73).** Same.
- **Florence Nightingale coxcomb / Lillian Wald transparency reports.** Historical analogs referenced in text; reproducing or restyling them crosses into pastiche.
- **Specific brand video stills / screenshots (United, KFC, Pepsi, Boeing).** Vendor and brand assets are dropped per CAJAL discipline.

---

## Video Candidate Pass

**FIGURE 8.1 (Coombs SCCT decision tree):** STATIC SUFFICIENT. Decision trees read naturally as static.
**FIGURE 8.2 (Vosoughi velocity curves):** **STRONG VIDEO CANDIDATE.** The time-compression argument is fundamentally dynamic. Animation drawing both curves left-to-right with the monitoring tick marks firing early, the cumulative-reach gap widening visibly at t=12h, and the late-correction marker landing at t=36h, would make the 36-hour gap viscerally expensive in a way the static curves only suggest. The chapter's central time-cost claim lives in the animation.
**FIGURE 8.3 (Escalation read tree):** STATIC SUFFICIENT.
**FIGURE 8.4 (Crisis response timeline):** **MILD VIDEO CANDIDATE.** Sequential animation showing handoffs would clarify the rhythm, but the static flow is already legible.
**FIGURE 8.5 (Synthetic-media verification chain):** STATIC SUFFICIENT.

**Video candidates identified: 1 strong + 1 mild.** Recommended: **Fig 8.2 (Vosoughi velocity over time).** Of all the videos in this book, this is the one where animation most clearly carries argumentative weight — the gap between false-news velocity and correction velocity is the chapter's foundational time-pressure premise.

---

## Split-point note

Chapter cross-references Ch 05 (Vosoughi explicitly, Pearl-ladder-style escalation read), Ch 06 (Pepsi/Kendall Jenner as both ad-creative failure and crisis trigger, pause-during-crisis as Guard item), Ch 07 (creator-side crisis spillover when partnered creators become the flashpoint). The Delegate / Delegate-with-Review / Guard three-tier color canon is heavily exercised in Figs 8.1, 8.3, 8.4, 8.5 — coordinate with Ch 07 Fig 7.4 so the Orange Delegate-with-Review color reads consistently. The Reddish Purple counsel/load-bearing-decision ring appears more often in this chapter than anywhere else in the book — its specific meaning (regulatory exposure, high-stakes irreversible decision, or human verification step) is established by context but should be visually distinct from any other ring or outline used elsewhere.
