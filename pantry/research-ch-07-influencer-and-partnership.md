# Research — Chapter 7: Influencer & Partnership

**Series:** Social Media Marketing +1 (AI+1)
**Reader:** Working social media managers and marketing professionals already using AI
**Thesis:** AI handles pattern; humans handle judgment.
**Scope this chapter:** Influencer research, outreach drafts vs. relationship decisions, fit assessment, audience overlap analysis, micro/mid/macro/mega tier distinctions, contract negotiation, FTC disclosure compliance judgment, post-campaign relationship maintenance.

---

## 1. Primary Sources

Primary sources are the actual regulations, platform documentation, working
practitioner reports, and original survey data — not summaries written about
them by marketing blogs. Where a source ages quickly (platform terms, API
behavior, model capability claims), it is flagged. Where the source is itself
a secondary write-up of a study, that is noted.

**Regulatory and legal primary documents**

- **FTC, "Disclosures 101 for Social Media Influencers" (2019, updated through 2024).**
  The canonical U.S. document for what counts as a "material connection,"
  the language of acceptable disclosures (#ad, #sponsored), platform-specific
  placement rules, and the per-violation civil penalty exposure. Free PDF on
  ftc.gov. Aging risk: medium — the underlying logic is stable, the
  examples cite specific platforms (Snapchat, IGTV) that have changed.

- **16 CFR Part 255 — "Guides Concerning Use of Endorsements and Testimonials
  in Advertising" (revised 2023).** The legal force behind the FTC's plain-
  language guidance. Note the 2023 revision tightened requirements around
  "incentivized reviews" and explicitly extended liability up to the
  advertiser, not only the influencer. Cite this rather than the popular
  press version when authority matters.

- **FTC v. Lord & Taylor (2016, complaint and consent order, FTC Docket
  No. C-4576).** The first major influencer-marketing enforcement action —
  fifty fashion influencers paid to wear a paisley dress on Instagram with no
  disclosure. Useful as a fully documented case for Section 1 and Section 5.

- **Sunday Riley / FTC consent order (2019).** Brand was caught instructing
  employees to post fake reviews on Sephora. Establishes that astroturfing
  by the brand itself is treated as deceptive endorsement, even without an
  external influencer. Useful for the "fake authenticity is a separate
  failure mode" thread.

- **CMA (UK Competition and Markets Authority), "Hidden ads: principles for
  social media endorsements" (2023).** The UK equivalent, slightly stricter
  on placement than the FTC. Reader value: anyone running campaigns into
  the UK market needs both.

- **EU Digital Services Act (DSA), Article 26 and Regulation (EU) 2022/2065.**
  Newer than the FTC framework; tightens transparency duties on platforms
  themselves and indirectly on advertisers operating in the EU. Aging risk:
  low (regulation is stable), but enforcement caselaw is still being built.

**Industry research with usable methodology**

- **Influencer Marketing Hub, "State of Influencer Marketing" annual benchmark
  report (2017–present).** The longest-running practitioner survey in the
  space — sample sizes typically 3,000–8,000 marketers. Useful for
  longitudinal claims ("creators have moved from X% to Y% of brand spend"),
  but the survey is self-selected and skews toward existing tool users.
  Cite with that caveat.

- **HypeAuditor, "State of Influencer Marketing" annual report.** Uses
  platform-data sampling rather than survey, so produces different (often
  lower) engagement-rate medians and explicit fraud-detection figures.
  Useful as a triangulation source.

- **Edelman Trust Barometer — "Trust in Influencers" cuts (2018–present).**
  The trust-decay data that supports the "creator authenticity ages
  faster than category authority" claim.

- **Linqia, "The State of Influencer Marketing" (annual).** Brand-side
  survey; useful for "what brands say they're paying" benchmarks
  cross-referenced against creator-side reports.

**Platform documentation (high aging risk — re-verify at draft time)**

- TikTok Creator Marketplace API and Branded Content policy.
- Meta Branded Content Tool documentation (Instagram and Facebook).
- YouTube paid-product-placement disclosure rules (the in-video yellow bar).
- X (formerly Twitter) Branded Likes / Amplify program documentation.
- LinkedIn Thought Leader Ads (launched 2023) and creator partnership policy.

These should be linked but not quoted at length, because the policy
language changes faster than a print book can.

**Academic and empirical research**

- Hughes, Swaminathan & Brooks (2019), "Driving Brand Engagement Through
  Online Social Influencers," *Journal of Marketing* 83(5). One of the
  more rigorous causal-inference studies on platform-by-tactic
  interaction — finds that the effective creator type depends on
  campaign goal (awareness vs. trial).

- De Veirman, Cauberghe & Hudders (2017), "Marketing through Instagram
  influencers," *International Journal of Advertising* 36(5). The
  follower-count vs. engagement-rate trade-off, with experimental data.
  This is the original published source behind the "more followers is
  not always better" claim that is everywhere in trade press.

- Audrezet, de Kerviler & Moulard (2020), "Authenticity under threat:
  When social media influencers need to go beyond self-presentation,"
  *Journal of Business Research* 117. Defines "passionate vs.
  transparent authenticity" — useful conceptual scaffold for Section 4.

- Lou & Yuan (2019), "Influencer Marketing: How Message Value and
  Credibility Affect Consumer Trust," *Journal of Interactive
  Advertising* 19(1). Empirical model of why disclosure does not
  destroy trust the way brands fear.

**Trade-press original reporting (use for current cases only, not principles)**

- *Business of Fashion* — sustained coverage of luxury / fashion creator
  partnerships, including post-campaign litigation.
- *Digiday* and *Adweek* — original reporting on agency / brand deals.
- *Modern Retail* — DTC-specific creator economics.

---

## 2. State of the Field

Influencer marketing as a recognizable discipline is roughly 15 years old
(dating from the first paid Instagram brand posts around 2010). It is
already on its third structural shift. The first shift was from celebrity
endorsement to "social media celebrity" — moving the locus of trust from
broadcast to platform-native. The second shift, between roughly 2016 and
2020, was the rise of the micro- and nano-influencer, driven by both
engagement-rate data and the practical fact that mid-tier creators were
cheaper and more flexible. The third shift, ongoing, is the absorption of
the "creator economy" into platform-owned tooling (TikTok Creator
Marketplace, Meta Branded Content, YouTube BrandConnect, LinkedIn Thought
Leader Ads) and the parallel rise of AI-generated and AI-assisted creators.

The current settled consensus in 2025–2026 looks roughly like this:

- Engagement rate declines with follower count in a roughly log-linear
  relationship; nano- and micro-influencers (under ~100K followers)
  consistently outperform on engagement-per-follower but cannot deliver
  campaign-scale reach.
- Audience-creator fit (do the creator's followers actually match the
  product's buyer) matters more than aggregate follower count, and is
  the single most under-measured dimension in low-budget campaigns.
- Fraud — purchased followers, engagement pods, sophisticated bots — is
  prevalent enough that audit tooling is no longer optional for spend
  over a few thousand dollars per partnership.
- Long-form, multi-touch partnerships out-perform one-off sponsorship
  posts on conversion metrics, but require more relationship work.
- Regulatory enforcement is rising in the U.S., UK, and EU and is now
  reaching the brand, not only the creator.

**Where AI is currently load-bearing in the workflow**

- *Discovery and shortlisting.* Tools (CreatorIQ, HypeAuditor, Modash,
  Grin, Aspire, Heepsy, and the platform-native marketplaces) use
  machine learning to surface candidates by audience demographics,
  topical content classification, engagement profile, and brand-safety
  signals. This is genuine pattern work and AI does it well.
- *Audience-overlap analysis.* Comparing a creator's audience to the
  brand's existing customer base, or to a previous creator's audience,
  to avoid paying twice for the same reach. Pattern work.
- *Fraud detection.* Statistical signatures of bot followers, suspicious
  engagement spikes, comment-pod patterns. Pattern work.
- *Outreach drafting.* Personalized first-contact emails, follow-ups,
  briefs, contract first drafts. Pattern work, with judgment caveats
  on tone and relationship signaling.
- *Performance reporting.* Pulling engagement, click, conversion, and
  earned-media-value figures into reports. Pattern work.

**Where AI is currently bad and unlikely to improve soon**

- *Cultural and subcultural fit reading.* Whether a particular creator's
  vibe will land with a particular audience at a particular moment.
- *Reading the creator's actual values and likely future trajectory.*
  Whether this person is a reputational risk in twelve months.
- *Relationship negotiation past the first email.* The judgment about
  what to concede, when to push, when to walk away, what to do when a
  creator's partner agency makes a strange demand.
- *Post-campaign relationship maintenance.* The choice of whether to
  invite a creator to a brand event, send a personal note, escalate the
  relationship to a longer-term ambassadorship.
- *FTC and CMA disclosure-adequacy calls in ambiguous cases.* The clear
  cases are pattern-checkable; the ambiguous ones (gifted product with
  no contract, employee posting, longstanding personal relationship
  with brand owner) require a human judgment call with legal exposure.

The interesting frontier — and a worthwhile point for the chapter to
land on — is that the discovery and fraud-detection layers are
commoditizing fast, which means the human judgment layer is becoming
proportionally more of the differentiator, not less. A team that out-AIs
its competitor at shortlisting but loses on fit reading is in a worse
position than the inverse.

---

## 3. Application Domain

The reader is a working social media manager or marketing professional
who has already used AI tools and is now running, or contributing to,
influencer and partnership programs. Their day-to-day decisions in this
domain look like this:

**Tier and budget decisions.** Should the program lean nano (under 10K),
micro (10K–100K), mid (100K–500K), macro (500K–1M), or mega (1M+)? The
right answer depends on goal (trial, awareness, conversion, retention),
category (the trust required to move a beauty product is not the trust
required to move a B2B SaaS evaluation), and budget shape (one big bet
vs. portfolio). AI tools can present the tier distribution data; the
choice is a strategic judgment call.

**Discovery and shortlisting.** From a longlist of two thousand
candidates to a shortlist of fifteen worth a human review. This is where
AI saves the most hours. The chapter should give the reader a clean
delegation pattern — what to ask the tool, what to set as filter
thresholds, what to never trust the tool's default on (especially
"brand-safe" classifiers, which are noisy).

**Fit assessment.** Once the shortlist is human-reviewable, the
assessment requires watching content, reading comment sections, checking
prior brand partnerships for tonal alignment, and forming an opinion
about whether this creator's audience will plausibly buy this product.
The chapter's central claim: this step does not delegate. AI can
summarize the creator's last twenty posts; the reader has to form a
view about whether the audience will sit still for a tenth such post.

**Outreach.** First-contact emails, follow-ups, brief documents. AI
drafts these well and a competent manager edits in the relationship
signal (acknowledgment of specific work, plausible reason for the
match, a piece of judgment-flavored language that signals a human
wrote it). The Guard: never let the first sentence be AI-default.

**Negotiation.** Rate, deliverables, exclusivity, usage rights, content
approval, posting cadence, kill fee, whitelisting, contract length.
The skeleton of a contract is pattern; the negotiation is judgment.
The chapter should make this distinction concrete with an example
worked through both layers.

**FTC / CMA disclosure judgment.** AI can check a draft post for the
presence of #ad and the location of disclosure within the first
two lines. AI cannot judge whether a particular gifted-product
arrangement constitutes a "material connection" in a gray case, or
whether the creator's actual delivery (a quick verbal mention buried
in minute four of a fifteen-minute video) is adequate. That judgment
sits with the brand and ideally with counsel.

**Crisis and exit.** A creator's prior content surfaces. A creator's
behavior during the campaign goes off. A creator publicly criticizes
the brand. The decision to pull the campaign, ask for a deletion,
publicly distance the brand, or quietly let it run out belongs
entirely on the human side. AI is useful for monitoring (Chapter 8
covers this) but not for the call.

**Relationship maintenance.** The long tail — sending a card, inviting
to events, offering a renewal at the right moment, choosing who to
escalate to ambassador, choosing who to quietly not renew. This is
where compounding returns live for serious programs and where AI
involvement, beyond a CRM reminder, currently subtracts value.

---

## 4. Thesis Connection

The chapter's job is to make the AI / human boundary inside influencer
work concrete and defensible. The thesis — "AI handles pattern; humans
handle judgment" — has a particularly clean instantiation here, because
the workflow naturally splits into pattern-rich front-end work
(discovery, audit, drafting, reporting) and judgment-rich middle work
(fit, negotiation, disclosure calls, relationship moves).

**Pattern-shaped work AI handles well in this domain (Delegate List):**

1. Discovery by audience demographic, topical match, engagement profile.
2. Audience-overlap calculation against existing customer data or against
   a previous campaign's audience.
3. Fraud signal detection (follower-growth anomalies, engagement-pod
   patterns, comment-bot detection).
4. First-draft outreach emails, follow-ups, brief documents.
5. Contract first-draft generation from templates.
6. Disclosure presence check on submitted posts (is "#ad" actually in
   the visible portion of the caption).
7. Campaign reporting — pulling reach, engagement, link clicks, code
   redemption, sentiment polarity.
8. Translation and localization of briefs for international creators.

**Judgment-shaped work that currently requires a human (Guard List):**

1. *Fit reading.* Whether this creator's audience will plausibly buy
   this product, in this moment, given the cultural air around the
   category. AI summarizes; the manager decides.
2. *Reputational forward-look.* Whether this creator is a risk in the
   next 12–24 months. AI flags surfaced past behavior; it cannot read
   trajectory.
3. *Tier-and-mix strategy.* The portfolio shape (one mega vs. forty
   nanos vs. a mid-tier ambassador program) — strategy work AI can
   compare options for but should not choose.
4. *Negotiation past the template.* What to concede on, when to walk,
   how to read the agent's signal.
5. *Disclosure-adequacy calls in gray zones.* When the material
   connection is real but the contract language pretends otherwise;
   when a creator's mode of disclosure is technically present but
   buried.
6. *Crisis call during a live campaign.* Pull, pause, distance, let run.
7. *Relationship escalation.* Who becomes an ambassador. Who gets the
   personal note. Who gets quietly retired.
8. *Brand-voice override.* When AI's polished outreach reads as
   institutional and the creator will only respond to a human.

The chapter should be explicit that the boundary is not "AI is bad at
nuance" — it is that nuance, here, is the entire job after the
shortlist. Discovery without judgment produces creator lists; judgment
without discovery produces slow, biased lists. The +1 is the human who
does the second half well enough that the first half compounds.

A useful aphorism for the chapter: *AI shortens the shortlist. It does
not shorten the decision.*

---

## 5. Wayback Candidates

The chapter wants two or three lesser-known historical figures whose
work prefigures something specific about influencer-and-partnership
judgment. Wikipedia-accessible, diverse, useful as analogies the
practitioner reader can actually carry.

**Candidate 1 — Mary Kies (1786–1837), first U.S. woman to receive
a patent (1809).** Kies's patent was for a method of weaving straw
with silk and thread, used in fashion hats. The historical hook for
this chapter is not the invention itself but the partnership pattern:
First Lady Dolley Madison publicly praised Kies's hats, and the
endorsement substantially boosted demand. This is one of the earliest
documented cases of high-status endorsement driving sales for a
named producer — a "macro-influencer" partnership two centuries
before the term existed. Useful analogy: the value transferred was
trust, not reach. The chapter can use Kies/Madison as the historical
anchor for the claim that authentic high-status endorsement has
always worked, and always required a fit (Madison's actual aesthetic
matched Kies's product) that no recommendation algorithm of the day
could have computed.

**Candidate 2 — Madam C. J. Walker (1867–1919), entrepreneur and
philanthropist.** Walker's hair-care business is widely cited as the
first to scale through a deliberately built network of "sales agents"
— roughly 40,000 Black women in the U.S. and Caribbean by the time of
her death — who used the product, demonstrated it in their communities,
and earned commissions. This is structurally a partner / affiliate /
nano-influencer network, run on judgment and relationship at a scale
where pattern tools would not have helped. Walker personally vetted,
trained, and re-trained agents; the "Walker System" included not only
product method but conduct guidelines that protected the brand. The
chapter can use Walker as the historical anchor for the claim that
the most durable partnership programs were always relationship-
intensive at the human layer, even when the discovery layer was
manual.

**Candidate 3 — Bertha Benz (1849–1944), industrialist and the first
person to drive an automobile a long distance.** In August 1888,
without telling her husband Karl, she drove a Patent-Motorwagen
roughly 106 km from Mannheim to Pforzheim with her two sons,
arrived, sent a telegram, drove back. The trip generated newspaper
coverage that materially helped Benz & Cie sell automobiles in
the months that followed. The hook for this chapter is not "first
woman driver" — it is that the trip was a stunt deliberately
designed to read as authentic, performed by a person whose
material connection to the brand (she was the inventor's wife and
had used her dowry to fund the company) was complete and
undisclosed. A modern FTC compliance reading of the same act
would require explicit disclosure. The chapter can use Benz to
make a careful, non-cynical point: the boundary between
"authentic enthusiasm" and "undisclosed material connection" is
exactly the line the disclosure regime is trying to draw, and
the reason the line is hard is that the underlying behavior is
ancient.

**Optional fourth — Marian Anderson (1897–1993), contralto.**
For a chapter section on relationship-as-strategy, Anderson's
long partnership with impresario Sol Hurok (who managed her
career for decades) is a textbook case of an artist-manager
relationship producing compounding returns through patient
human work — booking decisions, venue choices, the famous
1939 Lincoln Memorial concert after the DAR's refusal. Not a
brand partnership in the modern sense, but a clean analog for
ambassador-program thinking.

Selection note: Walker and Kies both anchor "endorsement /
partnership existed and required judgment before any of this
was automated." Benz is darker and sharper and is useful
specifically for the disclosure-judgment section. Use whichever
two best serve the chapter's pacing; the chapter does not need
all three.

---

## 6. Pedagogy

The reader is a working professional, not a student. Pedagogical
choices should respect that — they are reading to make a better
decision tomorrow, not to learn a field.

**Opening case.** Use a documented failure where the AI / human
boundary was crossed in the wrong direction. The Sunday Riley
fake-review case works but is brand-side, not influencer-side.
A cleaner version: a documented case of a brand using an
AI-discovery tool to onboard a creator whose audience was a
demographic mismatch (often because the tool weighted topical
content over audience composition) and lost both the budget and
the relationship. The chapter can construct this from public
post-mortems if no single named case is clean enough; label
the construction as illustrative.

**Delegate / Guard sequence.** The chapter's two lists should
be presented before the worked example. Readers of this book
have learned, by Chapter 7, to look for the lists first. Keep
each list to seven or eight items, plain language, verbs first.

**Worked example.** Run one campaign end-to-end through the
boundary. A reasonable choice: a mid-budget DTC brand wanting
to launch a new product to a specific demographic. Show the
discovery step (AI-led), the shortlist review (human), the
outreach (AI draft, human edit), the negotiation (human, with
AI used only for rate-benchmark lookup), the post compliance
check (AI), the disclosure-adequacy review on the live post
(human), the report (AI), the relationship next-step (human).

**Copy-paste Claude Code prompt.** Two are useful here:
(a) a creator-shortlisting prompt that takes a brand brief,
target audience, and a list of candidate creator handles, and
produces a structured fit assessment with explicit "human
review required" flags; (b) an outreach-email drafting prompt
that produces a first draft with the relationship-signaling
fields left for the human to fill (specific recent work to
reference, specific reason the brand chose them, one
non-template sentence).

**Exercises.** The reader has a job; assign exercises that
produce job artifacts. One sample: take three creators you
have worked with before, run the AI shortlisting prompt
against them, and identify which fit signal the tool missed
that you, the human, knew. The point of the exercise is to
make the boundary felt, not abstract.

**Plain-language definitions to include.** "Material
connection," "earned media value," "engagement rate
benchmark," "audience overlap," "whitelisting,"
"usage rights window," "kill fee," "exclusivity clause."

**Misconceptions to break.** (1) "Engagement rate alone tells
you fit" — false; it tells you content stickiness inside the
creator's existing audience, not match to your buyer.
(2) "Bigger creator means safer campaign" — frequently the
opposite, because mega-creators have less personal cost from
a bad partnership. (3) "Disclosure kills trust" — empirically
false (Lou & Yuan 2019 and related work). (4) "AI tools'
fraud-detection scores are reliable" — they are useful as
a starting signal and should not be used as a final filter.

---

## 7. Representation

The influencer economy is one of the more globally and
demographically diverse corners of marketing, and the chapter
should reflect that without performing it. Specific moves:

- Examples should not default to U.S. beauty / lifestyle / DTC.
  Include at least one B2B example (LinkedIn thought-leader
  partnerships), at least one international example (a
  successful Brazilian or Indonesian or Nigerian creator
  market case), and at least one category that is normally
  invisible in marketing books (a regulated industry — a
  legal-tech firm working with a creator-attorney, a
  pharmacy chain working with a creator-pharmacist).
- The Walker example in Section 5 covers a major historical
  blind spot in marketing pedagogy (Black women as the
  pioneers of structured network selling). Use it.
- Watch for the implicit assumption that "the creator" is a
  young, urban, English-speaking person on Instagram or
  TikTok. LinkedIn creators are often older. YouTube niche
  creators are often rural. Regional-language creators
  (Hindi, Spanish, Portuguese, Bahasa, Arabic) are larger
  audiences than English-language equivalents.
- Note explicitly that disclosure-regime variation is itself
  a representation issue: FTC, CMA, ASA, EU DSA, India's
  ASCI guidelines, and Brazil's CONAR each treat the same
  behavior differently. A U.S.-only chapter exports a
  particular regulatory imagination.
- The chapter should not assume the reader is the brand
  side. Many readers are agency-side or are themselves
  creator-economy participants moving between roles.

What to avoid: tokenizing examples (one Black creator, one
woman-led brand, etc., presented as the diversity quota).
Choose examples because they are the right examples for
the pedagogical point.

---

## 8. Open Questions

Things the chapter should either resolve or explicitly leave open:

1. *AI-generated and AI-augmented "creators."* By 2026, fully
   synthetic creators (Lil Miquela, Lu do Magalu, Imma) and
   AI-augmented human creators are an established category.
   Does the chapter take a position on whether a brand should
   partner with a synthetic creator, and on disclosure
   adequacy for AI-augmented content? Stake: this question
   will age either slowly or fast depending on legislation;
   FTC guidance as of late 2024 is suggestive but not yet
   prescriptive.

2. *Affiliate vs. influencer treatment.* Where does the chapter
   draw the line between performance-affiliate partnerships
   (link-driven, conversion-paid) and influencer partnerships
   (brand-paid, often flat-fee)? The two are converging
   operationally. A clear position helps the reader; a forced
   position obscures useful nuance.

3. *Long-form ambassador programs vs. one-off sponsorships.*
   The chapter implicitly favors long-form (because the
   relationship-judgment work compounds). Is that an explicit
   recommendation or a stated bias?

4. *Disclosure-adequacy in audio and live formats.* Podcast
   read-ads, livestream sponsorships, and Twitch / TikTok Live
   integrations have weaker established norms than feed posts.
   How prescriptive should the chapter be?

5. *In-housing vs. agency-led influencer work.* The chapter
   reader could be either; the AI/human boundary sits in
   slightly different places depending on which (the agency
   absorbs more of the relationship-judgment work in the
   in-housed model; the agency provides it as a service in
   the agency-led model). Worth at least a paragraph.

6. *Platform-owned marketplaces vs. third-party tools.* By
   the time the book ships, TikTok's and Meta's native
   marketplaces may have absorbed enough of the discovery
   layer that third-party tools survive only on the
   audit / overlap / reporting side. Worth flagging as a
   live trajectory.

---

## 9. Sourcing Notes

- The FTC document and 16 CFR Part 255 are the only Section 1
  sources that can be quoted at length without risking dated
  language. Quote them.
- The Hughes / De Veirman / Lou / Audrezet academic papers are
  paywalled in most cases; use the published abstracts and
  framework definitions, not the empirical figures, unless the
  author has institutional access at draft time.
- Annual industry reports (Influencer Marketing Hub, HypeAuditor,
  Linqia) re-publish every year with substantially the same
  headline structure. Cite the year-of-publication explicitly
  in the chapter so a reader can find the most recent edition.
- Platform documentation (Section 1) should be linked, not
  quoted. The book should not commit to specific platform UI
  language that will change.
- The historical figures in Section 5 are well-served by
  Wikipedia plus one good biographical secondary source each
  (e.g., A'Lelia Bundles's *On Her Own Ground* for Madam
  Walker). Do not cite Wikipedia in the text; use it for
  fact-checking and follow the references out.
- The Sunday Riley FTC consent order is freely available on
  ftc.gov and is the cleanest brand-side disclosure-failure
  case to cite.
- The Lord & Taylor case is older but better-documented and
  remains the cleanest influencer-side case.
- For the AI-tool landscape in Section 2, do not name specific
  vendor prices or feature sets — those age within months.
  Name the tool category and one or two representative tools.
- For any quantitative claim ("engagement declines with
  follower count"), prefer the De Veirman 2017 paper or the
  HypeAuditor methodology over the Influencer Marketing Hub
  survey, because the former two have published methods.
- Hypothetical examples in the chapter (constructed cases used
  to illustrate the boundary) must be explicitly labeled as
  illustrative in the prose. The reader trusts the chapter
  more, not less, for the labeling.
