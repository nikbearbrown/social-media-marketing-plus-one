# CAJAL SVG Generation Log — Social Media Marketing plus One

## Run: 2026-05-27 (Chapter Enrichment + CAJAL pantry completion)

Two runs combined into this log:
1. **Chapter Enrichment pass** (earlier) — generated SVGs from `<!-- → [IMAGE/FIGURE/...] -->` comments in chapter prose. Numbered fig-NN in chapter-comment order. 23 SVGs.
2. **CAJAL pantry completion pass** (this run) — generated SVGs for cajal-spec'd figures missing from Pass 1, numbered as the next sequential fig-NN per chapter. 19 SVGs.

Total SVGs in `images/`: **42**. Total 300 DPI PNGs: **42** (all converted via `node SCRIPTS/svg-to-png.mjs`).

---

### Cajal-figure ↔ filename mapping (per chapter)

| Chapter | Cajal Fig | Filename | Title | Source | Status |
|---|---|---|---|---|---|
| 01-the-boundary | 1.1 | fig-01 | The Boundary Quadrant | Enrichment | existed |
| 01-the-boundary | 1.2 | fig-02 | Delegate vs Guard at a Glance | Enrichment | existed |
| 01-the-boundary | 1.3 | fig-03 | The +1 Decision Node | Enrichment | existed |
| 02-the-framework | 2.1 | fig-01 | Three Nested Framework Levels | Enrichment | existed |
| 02-the-framework | 2.2 | fig-02 | Decomposition of LinkedIn CEO Thread (9 steps) | Enrichment | existed |
| 02-the-framework | 2.3 | fig-03 | Framework Anatomy at a Glance | CAJAL run | **new** |
| 03-content-creation | 3.1 | fig-01 | The Doshi-Hauser Divergence | Enrichment | existed |
| 03-content-creation | 3.2 | fig-02 | Decomposition of a CEO LinkedIn Essay (13 steps) | Enrichment | existed |
| 03-content-creation | 3.3 | fig-03 | Brief Specificity Anatomy | CAJAL run | **new** |
| 04-community-management | 4.1 | fig-01 | Surface vs Signal Layer | Enrichment | existed |
| 04-community-management | 4.2 | fig-02 | Parasocial Bond Accumulation and Retroactive Collapse | Enrichment | existed |
| 04-community-management | 4.3 | fig-03 | Inbox Routing by Personal-Stakes Axis | CAJAL run | **new** |
| 05-analytics-and-reporting | 5.2 | fig-01 | Eight-Question Pre-Interpretation Checklist | Enrichment | existed |
| 05-analytics-and-reporting | 5.3 | fig-02 | Two Summaries, Same Month: The Divergence | Enrichment | existed |
| 05-analytics-and-reporting | 5.1 | fig-03 | Pearl's Ladder Applied to Social Analytics | CAJAL run | **new** |
| 05-analytics-and-reporting | 5.4 | fig-04 | Deming Common-Cause vs Special-Cause Variation | CAJAL run | **new** |
| 06-paid-social-and-ad-creative | 6.2 | fig-01 | The AI-vs-AI Loop | Enrichment | existed |
| 06-paid-social-and-ad-creative | 6.4 | fig-02 | Campaign Cycle: Where the Judgment Sits | Enrichment | existed |
| 06-paid-social-and-ad-creative | 6.1 | fig-03 | Binet-Field 60/40 Brand vs Activation Allocation | CAJAL run | **new** |
| 06-paid-social-and-ad-creative | 6.3 | fig-04 | Measured Lift vs Incrementality (Lewis-Rao Gap) | CAJAL run | **new** |
| 07-influencer-and-partnership | 7.1 | fig-01 | Two-Stage Funnel: AI Discovery, Human Decision | Enrichment | existed |
| 07-influencer-and-partnership | 7.4 | fig-02 | Campaign Cycle: Handoffs and Time Estimates | Enrichment | existed |
| 07-influencer-and-partnership | 7.2 | fig-03 | Fit-vs-Reach Matrix | CAJAL run | **new** |
| 07-influencer-and-partnership | 7.3 | fig-04 | FTC 16 CFR Part 255 Disclosure Decision Tree | CAJAL run | **new** |
| 08-crisis-and-reputation | 8.4 | fig-01 | Crisis Response Timeline: AI Handles, Human Decides | Enrichment | existed |
| 08-crisis-and-reputation | 8.1 | fig-02 | Coombs SCCT Crisis Type → Posture Decision Tree | CAJAL run | **new** |
| 08-crisis-and-reputation | 8.2 | fig-03 | Vosoughi False-News Velocity vs Correction | CAJAL run | **new** |
| 08-crisis-and-reputation | 8.3 | fig-04 | Five-Minute Escalation Read | CAJAL run | **new** |
| 08-crisis-and-reputation | 8.5 | fig-05 | Synthetic-Media Verification Chain of Custody | CAJAL run | **new** |
| 09-platform-specific-execution | 9.1 | fig-01 | Two-Layer Execution Model (Format vs Fit) | Enrichment | existed |
| 09-platform-specific-execution | 9.3 | fig-02 | Lattice Case: Cross-Posted vs Corrected | Enrichment | existed |
| 09-platform-specific-execution | 9.2 | fig-03 | Distribution Model Spectrum | CAJAL run | **new** |
| 10-building-your-own-map | 10.1 | fig-01 | Three-Axis Classification Space | Enrichment | existed |
| 10-building-your-own-map | 10.3 | fig-02 | Map Lifecycle (Audit Protocol Cycle) | Enrichment | existed |
| 10-building-your-own-map | 10.2 | fig-03 | Regulated-Industry Calibration Matrix | CAJAL run | **new** |
| 11-what-changes-what-doesnt | 11.1 | fig-01 | Two-Question Test (Decision Tree) | Enrichment | existed |
| 11-what-changes-what-doesnt | 11.2 | fig-02 | Capability-Bound vs Attribution-Bound (Durable vs Decaying Layer) | CAJAL run | **new** |
| 11-what-changes-what-doesnt | 11.3 | fig-03 | Three Trajectory Camps | CAJAL run | **new** |
| 12-the-plus-one-practice | (extra) | fig-01 | How the Delegation Log Compounds Across Time | Enrichment | existed (no cajal mapping; useful timeline) |
| 12-the-plus-one-practice | 12.3 | fig-02 | The Two Columns of the Practice — AI Handles vs Must Be Human | Enrichment | existed |
| 12-the-plus-one-practice | 12.1 | fig-03 | Four-Cadence Practice (Daily / Weekly / Monthly / Quarterly) | CAJAL run | **new** |
| 12-the-plus-one-practice | 12.2 | fig-04 | Adoption-Then-Abandonment Curve (Why Minimum Viable Survives) | CAJAL run | **new** |

---

### Per-file summary (CAJAL pantry completion run only)

| File | Figure title | Type | Status |
|---|---|---|---|
| 02-the-framework-fig-03.svg | Framework Anatomy at a Glance | systems diagram | generated |
| 03-content-creation-fig-03.svg | Brief Specificity Anatomy | structural schematic | generated |
| 04-community-management-fig-03.svg | Inbox Routing by Personal-Stakes Axis | comparison panels | generated |
| 05-analytics-and-reporting-fig-03.svg | Pearl's Ladder Applied to Social Analytics | hierarchy | generated |
| 05-analytics-and-reporting-fig-04.svg | Deming Common-Cause vs Special-Cause | statistical / quantitative | generated |
| 06-paid-social-and-ad-creative-fig-03.svg | Binet-Field 60/40 Brand vs Activation | comparison panels | generated |
| 06-paid-social-and-ad-creative-fig-04.svg | Measured Lift vs Incrementality (Lewis-Rao Gap) | statistical / quantitative | generated |
| 07-influencer-and-partnership-fig-03.svg | Fit-vs-Reach Matrix | quadrant | generated |
| 07-influencer-and-partnership-fig-04.svg | FTC 16 CFR Part 255 Disclosure Decision Tree | decision tree | generated |
| 08-crisis-and-reputation-fig-02.svg | Coombs SCCT Crisis Type → Posture Decision Tree | decision tree | generated |
| 08-crisis-and-reputation-fig-03.svg | Vosoughi False-News Velocity vs Correction | statistical / quantitative | generated |
| 08-crisis-and-reputation-fig-04.svg | Five-Minute Escalation Read | process flowchart | generated |
| 08-crisis-and-reputation-fig-05.svg | Synthetic-Media Verification Chain of Custody | systems diagram | generated |
| 09-platform-specific-execution-fig-03.svg | Distribution Model Spectrum | comparison / annotated axis | generated |
| 10-building-your-own-map-fig-03.svg | Regulated-Industry Calibration Matrix | structural / matrix | generated |
| 11-what-changes-what-doesnt-fig-02.svg | Capability-Bound vs Attribution-Bound | comparison panels | generated |
| 11-what-changes-what-doesnt-fig-03.svg | Three Trajectory Camps | comparison panels | generated |
| 12-the-plus-one-practice-fig-03.svg | Four-Cadence Practice | timeline / progression | generated |
| 12-the-plus-one-practice-fig-04.svg | Adoption-Then-Abandonment Curve | statistical / quantitative | generated |

---

## Summary

- **Total cajal.md files processed:** 14 (00-frontmatter and 99-back-matter spec zero figures)
- **Total cajal figures specified:** 41 (across 12 content chapters)
- **Total cajal figures rendered as SVG:** 41 + 1 extra timeline = 42
- **CAJAL pantry completion run:** 19 SVGs generated
- **Skipped (already existed from Enrichment pass):** 23
- **PNG conversion:** complete (19 newly converted, 23 already up to date)

## Notes on numbering

The CAJAL pantry specifies figures as `Fig N.M` where M is the cajal author's preferred order within the chapter. The Chapter Enrichment pass (which ran first) numbered SVGs `fig-NN` by the order of `<!-- → [...] -->` comments in the chapter prose. These orderings do not always coincide — e.g. ch05 cajal Fig 5.1 (Pearl's Ladder) is `fig-03`, because the enrichment pass had already placed two other cajal figures (Eight-Question and Two Summaries) at fig-01 and fig-02 by chapter-comment order. The mapping table above is the authoritative reconciliation.

## Palette + style

All 42 SVGs follow the Bear Brown Brutalist palette: `#FFFFFF` canvas, `#2a1a0e` ink, `#C8102E` red (Guard / primary accent), `#545454` secondary (Delegate), `#D4D4D4` hairlines, `#C8860E` ochre decorative only, `#F5F5F5` plot region fill. EB Garamond for display, Inter for body, JetBrains Mono for axis ticks. No rounded corners, no gradients, no shadows. `role="img"` + `aria-labelledby` + `<title>` + `<desc>` + `<metadata>` `cajal:figure` block on every file.
