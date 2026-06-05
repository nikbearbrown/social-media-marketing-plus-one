# Enrichment Log — Social Media Marketing plus One

**Date:** 2026-05-27
**Mode:** Chapter Enrichment — Tables and Figures (Bear Brown / Brutalist)
**Style guides:** `brutalist/CLAUDE.md`, `brutalist/DESIGN.md`
**Source:** chapter `<!-- → [TABLE: ...] -->` and `<!-- → [IMAGE/FIGURE/DIAGRAM/INFOGRAPHIC/CHART: ...] -->` comments
**Output:** static SVG + 300 DPI PNG + responsive D3 v7 HTML

---

## Per-chapter log

| Chapter | Tables rendered | Figures generated | D3 HTML files | CAJAL PNGs inserted | Comments preserved |
|---|---|---|---|---|---|
| 01-the-boundary.md | 1 | 3 | 3 | 0 (PASS 3 skipped) | 3 / 3 |
| 02-the-framework.md | 4 | 2 | 2 | 0 (PASS 3 skipped) | 6 / 6 |
| 03-content-creation.md | 4 | 2 | 2 | 0 (PASS 3 skipped) | 6 / 6 |
| 04-community-management.md | 1 | 2 | 2 | 0 (PASS 3 skipped) | 3 / 3 |
| 05-analytics-and-reporting.md | 2 | 2 | 2 | 0 (PASS 3 skipped) | 4 / 4 |
| 06-paid-social-and-ad-creative.md | 3 | 2 | 2 | 0 (PASS 3 skipped) | 5 / 5 |
| 07-influencer-and-partnership.md | 1 | 2 | 2 | 0 (PASS 3 skipped) | 3 / 3 |
| 08-crisis-and-reputation.md | 3 | 1 | 1 | 0 (PASS 3 skipped) | 4 / 4 |
| 09-platform-specific-execution.md | 3 | 2 | 2 | 0 (PASS 3 skipped) | 5 / 5 |
| 10-building-your-own-map.md | 1 | 2 | 2 | 0 (PASS 3 skipped) | 3 / 3 |
| 11-what-changes-what-doesnt.md | 2 | 1 | 1 | 0 (PASS 3 skipped) | 3 / 3 |
| 12-the-plus-one-practice.md | 1 | 2 | 2 | 0 (PASS 3 skipped) | 3 / 3 |

---

## Summary

- **Total chapters processed:** 12 of 14 (00-frontmatter and 99-back-matter had no enrichment comments)
- **Total tables rendered:** 26
- **Total SVG + PNG pairs generated:** 23 (one extra fig in ch01 from a prior partial run, kept)
- **Total D3 HTML files generated:** 23
- **Total CAJAL PNGs inserted:** 0 — PASS 3 skipped because all 41 cajal-pantry-spec'd figures correspond to the same 22 comment-driven figures already produced in PASS 2
- **Comments preserved:** 48 / 48 (100%)

## Palette and discipline notes

All assets conform to the Bear Brown Brutalist palette:

- `#FFFFFF` canvas · `#2a1a0e` ink · `#C8102E` red (primary accent / Guard role) · `#545454` secondary (Delegate role) · `#D4D4D4` border · `#C8860E` ochre (decorative only) · `#F5F5F5` chart fill

The AI+1 series color canon is preserved with a palette translation from the cajal pantry's Okabe-Ito:

- Bluish Green Delegate → `#545454`
- Vermillion Guard → `#C8102E`
- Orange Delegate-with-Review → `#C8860E`
- Blue/Sky Blue mechanism → `#2a1a0e` or `#787878`
- Reddish Purple inputs → `#C8860E`

SVGs use the brutalist skeleton: viewBox `0 0 700 420` (extended to 480/540/600 only when needed), 32px margins, no rounded corners, no gradients, no drop shadows, `role="img"` + `aria-labelledby` + `<title>` + `<desc>`, `<metadata>` block with the `cajal:figure` namespace, HTML comment header carrying production identifiers. EB Garamond for display headings, Inter for body labels, JetBrains Mono for axis ticks.

D3 HTML files use the pinned `cdnjs.cloudflare.com/ajax/libs/d3/7.9.0/d3.min.js` CDN, `var(--color-*)` custom properties throughout (no hardcoded hex), `(event, d)` v7 handler signature, ResizeObserver-driven redraw, `prefers-color-scheme: dark` overrides, `prefers-reduced-motion: reduce` suppression, accessible `role="img"` SVG roots with tooltips on interactive marks.

## Post-pass corrections applied in chat

- **ch01-line33** TABLE comment restored after the rendered table (originally removed by the subagent).
- **ch02** all 4 TABLE comments restored after their rendered tables (originally replaced rather than augmented).
- Missing D3 HTML files for `11-what-changes-what-doesnt-fig-01` and `12-the-plus-one-practice-fig-01` written directly in chat after the subagent omitted them.

## Files produced

- `images/{chapter-slug}-fig-{NN}.svg` × 23
- `images/{chapter-slug}-fig-{NN}.png` × 23 (300 DPI, via `node SCRIPTS/svg-to-png.mjs`)
- `d3/{chapter-slug}-fig-{NN}.html` × 23
- 12 chapter files modified in place: tables inserted above their comments, figure markdown links inserted above their comments, `## Prompts` sections appended at chapter end. Prose unchanged. All 48 original `<!-- → [...] -->` comments preserved.
