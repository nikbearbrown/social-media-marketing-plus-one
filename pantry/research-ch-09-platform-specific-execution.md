# Research — Chapter 9: Platform-Specific Execution

**Series:** Social Media Marketing +1 (AI+1)
**Reader:** Working social media managers and marketing professionals already using AI
**Thesis:** AI handles pattern; humans handle judgment.
**Scope this chapter:** TikTok vs. LinkedIn vs. Instagram vs. X algorithm differences; community norms and content fit; platform-native creative judgment; what delegates to AI per platform and what doesn't.

---

## 1. Primary Sources

This chapter has the highest aging-risk profile of the book. Platform
mechanics, content formats, algorithm behaviors, and creator-monetization
rules change on the order of months, not years. The primary-source list
below leans on the most durable sources (academic papers, platform-published
technical documentation, regulatory filings) and labels the rest as
high-aging-risk.

**Platform-published primary documentation (HIGH aging risk — verify at draft time)**

- **TikTok, "How TikTok recommends content" (official Help Center page,
  most recently substantively revised 2023).** The closest TikTok comes
  to publishing its recommendation logic: user interactions, video
  information (captions, sounds, hashtags), device and account settings.
  Useful as the canonical brand-side reference even though it
  understates the system.

- **TikTok Transparency Reports (quarterly, 2019–present).** Community-
  guidelines enforcement statistics, government-request data, and from
  2023 onward, some content-recommendation transparency required under
  the EU DSA. Primary, low aging risk per individual report (the report
  is a snapshot in time), but the series itself updates.

- **Meta, "How Instagram's algorithm works" — Adam Mosseri blog posts
  (2021, 2022, 2023, 2024).** The clearest first-party explanation of
  the Feed, Reels, Stories, and Explore ranking signals. Mosseri has
  been usefully specific (e.g., the "shares per reach" metric matters
  more than likes for Reels).

- **Meta DSA Transparency Reports for Facebook and Instagram (bi-annual,
  2023–present).** Required by the EU Digital Services Act. Contains
  recommender-system parameter disclosures that are nowhere else
  documented at this specificity.

- **LinkedIn Engineering Blog, "Updates to our feed ranking" series
  (multiple posts 2022–2024).** LinkedIn has been unusually forthcoming
  about feed-ranking changes since the August 2023 "knowledge and
  advice" emphasis pivot. Primary, useful, ages within months.

- **X (formerly Twitter) algorithm partial open-source release (March
  2023, github.com/twitter/the-algorithm).** A genuinely useful primary
  source — code-level documentation of the For You feed ranking and
  the SimClusters embedding system. Has not been substantively updated
  since the initial release; treat as a snapshot of 2023 ranking
  behavior, since modified.

- **YouTube Creator Insider channel and YouTube Help, "How YouTube's
  recommendation system works" (last substantive update 2023).** The
  shorts vs. long-form distinction matters; YouTube's recommendation
  treats them as substantially different systems.

- **Reddit's content policy and the 2023 API pricing change
  documentation.** The API changes substantially restructured the
  third-party tool ecosystem on Reddit; relevant because brands
  monitoring or participating on Reddit are working in a different
  environment than they were pre-2023.

**Academic and empirical primary sources**

- **Mohsin Kabir & Madden (2023), "Studying TikTok's For You Page
  algorithm through sock puppet auditing," conference paper (FAccT
  2023).** One of the few rigorous external audits of TikTok's
  recommendation behavior. Useful as the primary source for
  "TikTok converges on interest signals within ~40 minutes of
  watch behavior."

- **Bandy & Diakopoulos (2021), "More Accounts, Fewer Links: How
  Algorithmic Curation Impacts Media Exposure in Twitter
  Timelines," *Proceedings of the ACM on Human-Computer
  Interaction*.** The kind of external audit study that holds up
  better than vendor self-reporting on how a ranked feed reshapes
  what users see.

- **Bhadani, Yamaya, Flammini, Menczer, Ciampaglia & Nyhan (2022),
  "Political audience diversity and news reliability in
  algorithmic ranking," *Nature Human Behaviour* 6.** Useful as a
  primary source on how recommendation systems reshape
  consumption patterns relative to explicit follows.

- **Allen, Howland, Mobius, Rothschild & Watts (2020), "Evaluating
  the fake news problem at the scale of the information
  ecosystem," *Science Advances* 6(14).** Establishes the
  baseline volume metrics that platform-monitoring claims are
  often measured against.

- **Wang et al. (2024), "Audit of TikTok's algorithm during the
  2024 election," NYU Center for Social Media and Politics
  working paper.** Recent and methodologically clean; useful as
  evidence that the algorithm's effective behavior diverges from
  the platform's documented behavior under specific conditions.

- **Pew Research Center, "Social Media Use" annual reports
  (2005–present).** The longest-running primary survey on U.S.
  platform demographics. Useful for "who is actually on which
  platform" claims that brand decks routinely get wrong.

- **Reuters Institute Digital News Report (annual, 2012–present).**
  The international equivalent to Pew on news-via-social
  consumption; covers 40+ countries. Indispensable for any
  international platform claim.

- **Ofcom Online Nation report (annual, UK).** The closest UK
  equivalent of the Pew data with quarterly platform-usage
  measurement.

**Regulatory and legal primary sources**

- **EU Digital Services Act (Regulation EU 2022/2065), Articles
  27, 38, 39, 40.** Requires Very Large Online Platforms to
  publish recommender-system parameters and provide
  researcher data access. The chapter benefits from naming
  this because it has materially increased what is knowable
  about platform algorithm behavior since 2024.

- **EU Digital Markets Act (Regulation EU 2022/1925).**
  Establishes the "gatekeeper" platforms category and
  interoperability obligations relevant to cross-posting and
  data portability.

- **Protecting Americans from Foreign Adversary Controlled
  Applications Act (signed April 2024) and subsequent
  litigation.** The TikTok-divestment / ban dynamics in the
  U.S. The chapter should reference but not bet on the
  outcome; the legal status will likely change between
  drafting and publication.

- **California AB 587 (Content Moderation Requirements,
  2022) and its 2024 litigation.** Established
  platform-transparency requirements that have produced
  primary-source documents (the platforms' AB 587 reports)
  useful for understanding moderation behavior.

- **Online Safety Act 2023 (UK) and Ofcom's implementing
  codes (2024–2025).** Materially changes what UK-facing
  brand content must comply with on each platform.

**Documented case sources**

- **Duolingo's TikTok account (2021–present).** Useful as a
  documented case of platform-native creative judgment
  producing measurable business results. Primary sources:
  Duolingo's own published case studies, the social-team
  interviews in *Adweek* and *Modern Retail*, and the
  publicly disclosed app-install metrics in earnings
  filings (Duolingo is publicly traded; the 10-K and 10-Q
  filings reference social-marketing performance directly).

- **Wendy's X (Twitter) account, 2017 #NuggsForCarter
  campaign and ongoing voice.** Documented case of
  platform-native voice — the irreverent reply-style that
  worked on Twitter circa 2017 and ages interestingly as
  the platform itself changes.

- **Ryanair's TikTok account (2022–present).** Useful as a
  non-U.S. case of platform-native voice succeeding through
  deliberately low-production-value, in-on-the-joke content.

- **LinkedIn-native B2B accounts.** Several documented
  cases (Gong, Drift in their pre-acquisition era,
  Workhuman) where the LinkedIn-native voice — long
  personal-story posts, named individual contributors,
  carousel documents — produced measurable pipeline.

**Trade press for current platform mechanics**

- *Social Media Today*, *Marketing Brew*, *The Verge*'s
  platform coverage, *Platformer* (Casey Newton's
  newsletter), *Garbage Day* (Ryan Broderick).
- *Search Engine Land* and *Marketing Land* for
  algorithm-update coverage.
- Use these for current cases and recent changes; not as
  authority on principles.

---

## 2. State of the Field

Platform-specific execution as a practice has stabilized around a few
durable principles even as the platforms themselves keep changing. The
state of the field as of 2025–2026:

**Platforms differ on three axes that matter for execution.**

(1) *Distribution model.* Some platforms (TikTok, YouTube Shorts,
Instagram Reels) push content into feeds of users who do not follow
the account; others (LinkedIn, X) weight existing-follower distribution
more heavily; Facebook sits in between and has been moving toward the
TikTok model. The practical consequence: on a recommendation-first
platform a small account can reach a large audience with a single
piece of content; on a follower-first platform reach is bounded by
audience size.

(2) *Content format primacy.* Each platform has a "first-class"
format the algorithm rewards disproportionately. TikTok: short
vertical video. Instagram: Reels (followed by carousels). YouTube:
long-form video (Shorts second-class). LinkedIn: text posts and
document carousels (followed by native video). X: short text
(images and video second-class). Pinterest: vertical image. The
first-class format gets the largest algorithmic boost; producing
in second-class formats is allowed but yields lower distribution.

(3) *Community norms.* Each platform has a set of norms about
voice, format, posting cadence, and acceptable promotion that are
not in the documentation. Violating community norms produces
distribution penalties that are not announced as penalties
(reduced reach, suppressed comments, reduced share rate) and
that AI tools cannot reliably predict.

**Algorithms have converged in their underlying technology but
diverged in their incentives.** All major platforms now use
transformer-based ranking models, similar embedding systems for
content and users, and similar reward signals (watch time,
completion rate, shares, saves, comments). What differs is the
weighting — TikTok weights completion rate and rewatch most
heavily, Instagram weights shares-per-reach, LinkedIn weights
dwell time and comment depth, X weights replies and quote-posts.
These weightings change quietly and frequently.

**The "platform-native" content concept has empirical support.**
The same brand running the same campaign across platforms
without re-cutting and re-voicing the content materially
underperforms versus the version that respects platform-specific
conventions. The audience punishes obvious cross-posting; the
algorithm reads format and pacing signals to detect it.

**AI is good at format adaptation and bad at voice adaptation.**
A 60-second horizontal YouTube clip can be reformatted to a
9:16 vertical TikTok crop with AI tools in seconds. The
re-voicing — what makes the same content land as TikTok-native
rather than YouTube-cross-posted — requires a person who reads
the platform's current culture. AI tools as of 2025–2026
produce a recognizable "AI TikTok caption" and "AI LinkedIn
post" style that the audience reads as such.

**Platform half-life is shorter than book half-life.** This is
the chapter most at risk of dating, and the chapter's
construction should acknowledge this directly. The principles
(distribution model, format primacy, community norms,
re-voicing required) are durable; the specific algorithm
weights and feature mixes are not.

**Where AI is currently load-bearing in platform-specific work**

- Format adaptation across aspect ratios, lengths, and asset
  types (vertical re-cut from horizontal source; carousel
  generation from long-form text; thumbnail variation).
- Caption variation across platforms with appropriate length,
  hashtag conventions, and emoji density per platform.
- Scheduling optimization based on platform-specific audience
  activity patterns.
- Hashtag and keyword research per platform.
- Engagement-pattern analytics per platform.
- A/B variant generation for thumbnails, opening seconds,
  hooks.

**Where AI is currently bad**

- Platform-native voice. The "Duolingo voice on TikTok" or the
  "Gong voice on LinkedIn" is not a template AI can apply; it
  is a continuously updated reading of platform culture.
- Trend participation timing. Whether a sound, format, or
  meme is still rising, peaking, or stale.
- Community-norm violations that produce silent distribution
  penalties.
- Reading the comment culture of a specific subreddit or
  niche before posting.
- Knowing which platform a piece of content does not belong
  on at all.

---

## 3. Application Domain

The reader runs or contributes to content production across
multiple platforms and has to make execution decisions every
day about how to translate a brand idea into platform-specific
output. The reader's typical decisions in this domain:

**Platform-mix strategy.** Which platforms the brand actually
shows up on, given resources and audience. The frequent
default — be everywhere — is usually wrong; the right answer
is concentration on two or three platforms where the
brand's audience actually lives and the content can be
genuinely native. AI tools can pull demographic data; the
strategic call is human.

**Format choice per platform.** Given a campaign or message,
which first-class format on which platform. AI can adapt
format; AI cannot decide that the message is wrong for
TikTok and right for LinkedIn.

**Content adaptation.** Taking a single brand idea (a product
launch, a thought-leadership post, a customer story) and
producing platform-specific versions that read as native on
each. This is the chapter's central worked-example
territory. AI does the mechanical adaptation; the human
does the voicing and the platform-culture read.

**Trend participation.** The decision whether to participate
in a current platform trend (a TikTok sound, an Instagram
audio meme, an X reply-format, a LinkedIn engagement
pattern). The judgment: is the trend still rising; does it
fit the brand; does it require a fast-turnaround production;
is the participation going to read as opportunistic. AI can
flag trends; the judgment is human.

**Hook and opening seconds.** On video-first platforms the
first 1–3 seconds determine whether the post is distributed
at all. AI can generate variants; the choice of which hook
to publish is a brand-voice judgment.

**Caption and copy.** Length, tone, hashtag density, emoji
use, line-break style — each platform has conventions. AI
draft is fine; the human edit for voice is required.

**Comments and engagement.** Each platform has different
norms for whether the brand replies, how the brand replies,
and what the reply tone signals. LinkedIn replies are
treated as further content (extending reach); X replies are
expected and read as in-character or out-of-character; TikTok
replies can be made into video responses; Instagram replies
are mostly conversational. The reply policy is a per-platform
judgment call.

**Cross-posting policy.** When the same content goes on
multiple platforms versus when each platform gets its own
version. The intermediate option (similar content, different
edits) is usually right and is the most labor-intensive.

**Posting cadence.** Each platform has a different optimal
posting frequency, and the optimal varies by account size
and account type. AI tools can recommend; the recommendation
should be sanity-checked against capacity (a cadence the
team cannot sustain is the wrong cadence).

**Platform-specific creator collaborations.** Cross-references
to Chapter 7. The creator the brand collaborates with on
TikTok is rarely the same creator who works on LinkedIn.

---

## 4. Thesis Connection

Chapter 9's thesis instantiation: AI handles the format pattern;
the human handles the cultural pattern. Platform-native execution
is a sequence of decisions that are individually small (where
does the hook sit, what is the caption length, what is the hashtag,
which emoji), and that AI tools can produce defensible defaults
for, and that collectively produce content the audience reads as
either native-and-trustworthy or alien-and-corporate. The
collective effect is the human's job; the individual decisions
can be assisted.

**Pattern-shaped work AI handles well (Delegate List):**

1. Aspect-ratio adaptation across platforms.
2. Length-cutting (a 5-minute video to a 60-second cut to a
   15-second cut).
3. Caption length and format adaptation per platform.
4. Hashtag research and selection per platform.
5. Thumbnail and cover variant generation.
6. Hook A/B variant generation (multiple opening seconds for
   testing).
7. Per-platform optimal-time scheduling based on engagement
   data.
8. Alt-text and accessibility-text generation.
9. Cross-platform performance reporting.
10. Translation and localization across platforms (with the
    caveat that idiomatic adaptation is judgment work).

**Judgment-shaped work that currently requires a human (Guard List):**

1. *Platform-mix strategy.* Which platforms the brand commits
   to and which it does not.
2. *Format choice for a given message.* The judgment that this
   message belongs as a TikTok and not as a LinkedIn post.
3. *Voice and tone per platform.* The continuously updated
   reading of what the platform's culture currently rewards.
4. *Trend participation.* Whether to ride a trend and what
   participation reads as.
5. *Community-norm reading.* The implicit rules that produce
   silent distribution penalties.
6. *Hook selection.* Which of the AI-generated variants gets
   published.
7. *Comment-engagement policy.* Whether and how the brand
   replies on each platform.
8. *Refusal.* The judgment that the brand should not be on a
   particular platform at all, regardless of audience size.
9. *Platform-political reading.* When platform-level changes
   (ownership change, policy change, controversy) require
   re-evaluating presence on a platform.

The chapter's aphorism candidate: *AI can give you the format;
only the human can give you the fit.*

The thesis here is especially load-bearing because AI tools'
output on this work looks plausible — an AI-generated TikTok
caption reads as a TikTok caption — and only the audience
response reveals that it didn't actually land. The cost of
delegating the judgment work is not immediately visible in the
artifact; it shows up in distribution and engagement metrics
weeks later.

---

## 5. Wayback Candidates

Two or three lesser-known historical figures whose work
prefigures something specific about platform-native execution
and community norms. Wikipedia-accessible, diverse, useful as
analogies.

**Candidate 1 — Aretas Brooks Fleming Brewster (often
remembered as Mary Katherine Goddard, 1738–1816), printer and
postmaster.** Goddard was the first woman to serve as a
U.S. postmaster (Baltimore, from 1775) and the printer of the
first copy of the Declaration of Independence to include the
signers' names (January 1777, the "Goddard Broadside"). The
chapter hook is her grasp of platform-native execution in the
print medium: she ran the *Maryland Journal*, customized
content for the specific Baltimore audience, used the postal
network she ran for distribution leverage, and made the
publication decision about including signers' names — a
content-format choice that has been debated by historians as
either reckless or strategic and that we can read now as a
deliberate platform-native execution choice (the broadside
format demanded names; the assertion-of-legitimacy demanded
names; the audience's expectation of accountability demanded
names). The chapter can use Goddard as the historical anchor
for the claim that platform-native execution is older than
social media — it is what you do when you understand the
medium, its audience, and its norms simultaneously.

**Candidate 2 — Sarah Josepha Hale (1788–1879), editor of
*Godey's Lady's Book*.** Hale ran *Godey's* from 1837 to
1877 and turned it into one of the most influential
publications in 19th-century America (peak circulation
~150,000, vast for the era). Her platform-native genius was
recognizing that the magazine's "first-class format" was the
hand-colored fashion plate (each issue's plate was the
specific reason readers bought) and that everything else —
recipes, sheet music, poetry, editorial — served that
distribution mechanic. She also pioneered platform-specific
audience cultivation through what would now be called
community-building (the magazine's reader-correspondence
sections were structured engagement, not afterthoughts). The
chapter can use Hale as the historical anchor for the claim
that recognizing the first-class format of a platform and
building the rest of the publication strategy around it is
durable across centuries.

**Candidate 3 — Robert L. Vann (1879–1940), editor and
publisher of the *Pittsburgh Courier*.** Vann took over the
*Courier* in 1910 and built it into the most widely
circulated Black newspaper in the U.S. (peak circulation
~200,000 in the early 1940s) through deliberate
platform-native execution: regional editions (the
"national" *Courier* had separate regional inserts long
before this was standard practice), a sports section
designed for the specific audience, and the famous
"Double V" campaign during WWII that was a platform-native
content format (the V-for-victory icon was the platform's
visual vocabulary; the doubling was the
publication-specific innovation). Vann understood that
running a publication for a specific audience required
content choices the dominant publications would not have
recognized as good content; the audience response
validated the choices. The chapter can use Vann as the
historical anchor for the claim that platform-native
execution requires committing to the audience's frame, not
the dominant frame, and that this is the most uncomfortable
and most valuable judgment call.

**Optional fourth — Hedda Hopper or Louella Parsons,
gossip columnists of the studio era.** Useful as the
historical analog for the "platform voice" question — both
built personal brands inside a constrained publication
format (the syndicated column) that anticipates modern
platform-native creator voice. Not the strongest fit
because both were narratively unattractive figures; use
only if useful.

Selection recommendation: Goddard and Vann. Goddard for
the print-as-platform analogy and the format-as-judgment
move; Vann for the audience-frame commitment and the
courage of platform-native deviation from dominant
conventions. Hale is also strong if the chapter needs a
"recognize the first-class format" anchor specifically.

---

## 6. Pedagogy

Pedagogy here should respect that the reader knows the
platforms operationally and is reading for the boundary
between AI-assisted and human-judged execution. The reader
does not need a TikTok primer.

**Opening case.** Use a documented contrast: one brand
that adapted natively across platforms and one that
cross-posted and underperformed. Duolingo on TikTok vs.
the same campaign cross-posted is a workable contrast.
Alternatively, a recent constructed example showing a
single piece of brand content adapted three different
ways across three platforms with the corresponding
engagement deltas. Label any construction as
illustrative.

**Per-platform briefs.** A short structured treatment
of each major platform: distribution model, first-class
format, voice conventions, community norms not in the
documentation, what AI delegates, what humans guard.
Suggested platforms to treat directly: TikTok, Instagram,
LinkedIn, X, YouTube (Shorts and long-form treated
separately). Optional secondary treatment: Threads,
Pinterest, Reddit, Snap, regional platforms (Xiaohongshu,
Douyin, VK as relevant for international readers). Keep
each platform brief to roughly one page; the chapter is
not a platform encyclopedia.

**The four-axis comparison.** A small comparison table —
TikTok vs. Instagram vs. LinkedIn vs. X — on distribution
model, first-class format, optimal length, dominant voice,
typical engagement pattern, AI-good and AI-bad work.
Visible at-a-glance reference the reader will return to.

**Worked example.** Take one brand idea (a thoughtful
position on something topical to the brand's category) and
walk it through native execution on all four major
platforms. Show the platform-native version on each, the
AI-assisted draft, the human edit, the publication
decision, and the post-publication engagement pattern.
The point of the example is to make the re-voicing work
visible.

**Refusal as a teachable move.** A short explicit
treatment of when not to be on a platform. The brand
that should not be on TikTok. The B2B vendor that
should not be on Instagram. The serious-news brand that
should not be on certain X formats. Refusal is the
hardest judgment in this chapter because the default is
presence.

**Copy-paste Claude Code prompt.** Two prompts:
(a) a platform-adaptation prompt that takes a piece of
source content and the four target platforms and
produces draft adaptations with explicit "human voicing
required" markers; (b) a trend-evaluation prompt that
takes a current platform trend and the brand's positioning
and produces a structured pro/con read with explicit
"human judgment required" markers on cultural fit and
timing.

**Exercises.** One useful exercise: take three pieces of
the reader's own brand content from the past 90 days and
identify, for each, which platform it was natively built
for and how each cross-post version under-performed or
should have been re-voiced. The exercise turns the
abstract claim into an audit of the reader's own work.

**Plain-language definitions.** "First-class format,"
"distribution model," "recommendation-first vs.
follower-first," "community norms," "platform-native,"
"cross-posting," "completion rate," "shares per reach,"
"dwell time," "hook," "trend half-life," "silent
distribution penalty."

**Misconceptions to break.**
(1) "Be everywhere." False — concentration on platforms
that fit the brand and the team's capacity outperforms
thin coverage.
(2) "AI can write a TikTok caption." Technically true,
factually misleading — AI produces recognizably AI
captions that audiences and the algorithm penalize.
(3) "Cross-posting is efficient." False on engagement
metrics; the efficiency is illusory.
(4) "Algorithm hacks are real." Mostly false; what
appears to be an algorithm hack is usually a
community-norms exploit that has a short half-life and
sometimes a backlash cost.
(5) "Platform demographics are obvious." False — the
default mental model is usually 3–5 years out of date.
Cite the most recent Pew or Reuters data.
(6) "What works on one platform works on the others
with minor edits." False — the central claim of the
chapter.

---

## 7. Representation

Platform-specific execution is the chapter where U.S.- and
English-centric assumptions are most easily made and most
costly. The chapter must explicitly resist that.

- *International platforms.* The chapter should treat
  Xiaohongshu (Little Red Book), Douyin (Chinese TikTok),
  VK, KakaoTalk, Line, and WeChat as legitimately
  important platforms, not as exotic specialties. The
  reader may not need to execute on them, but a chapter
  on platforms that does not name them is incomplete.
- *Regional voice variation within platforms.* TikTok in
  India, TikTok in Brazil, and TikTok in the U.S. have
  meaningfully different content cultures. Brand
  execution that doesn't acknowledge this fails.
- *Language and accessibility.* Caption practices,
  alt-text practices, and audio-description practices
  vary by platform and matter to non-English speakers
  and disabled users. The chapter should treat
  accessibility as part of platform-native execution,
  not as a separate compliance topic.
- *Generational variation.* The "TikTok is young, LinkedIn
  is old" mental model is outdated. Recent Pew data shows
  TikTok adoption among 30–49-year-olds is substantial and
  LinkedIn's younger-user growth has been strong.
- *Industry variation.* Regulated industries
  (pharmaceutical, financial services, legal) execute
  natively on platforms that allow it through different
  formats than unregulated industries can. A pharmaceutical
  brand's "platform-native TikTok" looks different from
  Duolingo's; the chapter should treat this as a real
  constraint, not a problem to be wished away.
- *The Vann and Goddard examples in Section 5* anchor
  the historical view that platform-native execution has
  always been about reading specific audiences against
  dominant assumptions.

What to avoid: examples drawn exclusively from
consumer-products marketing aimed at U.S. millennials. The
chapter's reader is broader than that.

---

## 8. Open Questions

1. *Platform mortality.* X's trajectory under post-2022
   ownership and policy changes; TikTok's U.S.
   divestment / ban litigation; LinkedIn's video-first
   pivot; YouTube Shorts' relationship to long-form. Any
   of these could materially shift between drafting and
   publication. The chapter should write to durable
   principles and label specific-platform claims with
   the date of the claim.

2. *Generative AI on the platforms themselves.* All
   major platforms now have or are testing AI-generated
   content features (TikTok's AI avatar tools, Meta's
   AI character interactions, LinkedIn's AI post
   drafting, YouTube's AI tools). The chapter's stance
   on brand use of these features needs a position.

3. *Watermarking and content provenance.* C2PA adoption,
   platform-level synthetic-content labeling. Cross-
   reference Chapter 8. The chapter should at least
   acknowledge that platform labeling of AI-assisted
   content may change distribution.

4. *Audio-first platforms (podcast platforms, audio
   social).* Spotify, Apple Podcasts, the diminished
   Clubhouse / Twitter Spaces / X Spaces category. The
   chapter should at least mention.

5. *Substack and creator-newsletter platforms.* These
   sit awkwardly between "social platforms" and
   "owned media." The chapter should take a position
   on whether they belong in scope.

6. *Brand presence on Discord and other community
   platforms.* Distinct from social platforms in
   distribution mechanics; the chapter should at
   least name the category.

7. *Reddit's evolving brand-presence model post-2023
   API changes.* The chapter should at least flag
   that Reddit is a real platform with real distribution
   power and a hostile-to-corporate culture that
   requires specific execution.

8. *Platform-specific live commerce (TikTok Shop,
   Instagram Shopping, YouTube Shopping).* Native
   commerce execution is a sub-discipline with its
   own AI / human boundary. The chapter should at
   least name it.

---

## 9. Sourcing Notes

- All platform-published documentation should be cited
  with the date of the cited version. Algorithm-update
  posts in particular age within months.
- Mosseri's Instagram explanations and the LinkedIn
  Engineering blog series are the two most useful
  first-party algorithm sources; cite them by post
  date.
- The X open-source release (March 2023) is genuinely
  useful but is a snapshot; treat any post-2023 X
  algorithm claim with care.
- The TikTok Help Center page is the canonical first-
  party reference but should be supplemented with the
  academic audit literature (Kabir & Madden 2023; Wang
  et al. 2024) for actual behavior.
- Pew Research Center and Reuters Institute Digital
  News Report are the right sources for "who is on
  which platform" claims. Cite year of survey.
- The DSA transparency reports are an excellent new
  primary source (2024 onward) and worth specific
  reference because the reports contain
  recommender-system parameter disclosures that are
  nowhere else documented at this specificity.
- Documented case sources (Duolingo, Wendy's, Ryanair,
  the LinkedIn B2B accounts) should be cited from
  primary materials where possible (the brand's own
  case studies, earnings filings) and from named
  trade-press interviews where not.
- Avoid quoting current TikTok-trending sounds or
  Instagram-current carousel formats; they will be
  stale within months. Describe the pattern, not the
  instance.
- Hypothetical examples in the chapter (constructed
  cases used to illustrate the boundary) must be
  explicitly labeled as illustrative in the prose.
- The historical figures in Section 5 are well-served
  by Wikipedia plus one biographical secondary source
  each. For Vann: Andrew Buni's *Robert L. Vann of
  the Pittsburgh Courier*. For Hale: Patricia Okker's
  *Our Sister Editors: Sarah J. Hale and the Tradition
  of Nineteenth-Century American Women Editors*. For
  Goddard: Ward L. Miner's *William Goddard, Newspaperman*
  covers the family-press context.
- Where the chapter names a specific platform feature
  (e.g., LinkedIn Thought Leader Ads, TikTok Creator
  Marketplace, Meta Branded Content Tool), include the
  rough date and the noted aging risk.
- The chapter should include a single explicit
  acknowledgment that platform mechanics age faster
  than the principles, with a note that readers should
  treat the per-platform briefs as snapshots and the
  principles as durable.
