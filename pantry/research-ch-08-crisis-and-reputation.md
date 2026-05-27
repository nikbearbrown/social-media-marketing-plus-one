# Research — Chapter 8: Crisis & Reputation

**Series:** Social Media Marketing +1 (AI+1)
**Reader:** Working social media managers and marketing professionals already using AI
**Thesis:** AI handles pattern; humans handle judgment.
**Scope this chapter:** Real-time monitoring tools, escalation criteria, tone calibration (PR-corporate vs. authentic apology), when to wait vs. when to respond, deepfake / synthetic-media detection, post-crisis reputation repair.

---

## 1. Primary Sources

The crisis-and-reputation literature is split between PR scholarship (older,
deeper, mostly pre-social-media), corporate-comms practitioner texts, the
much newer monitoring-tool documentation, and a small but rapidly growing
empirical literature on social-media crisis response. Primary sources below
are the load-bearing ones for this chapter. Where a source is itself a
secondary write-up, that is flagged.

**Theoretical and academic primary sources**

- **Coombs, W. Timothy. *Situational Crisis Communication Theory (SCCT)* —
  primary papers, especially "Protecting Organization Reputations During a
  Crisis: The Development and Application of Situational Crisis
  Communication Theory," *Corporate Reputation Review* 10(3), 2007.** SCCT
  is the most cited framework in academic crisis communications and is
  directly usable for "what response posture does this situation call
  for." Coombs's crisis typology (victim, accidental, preventable) maps
  cleanly onto the escalation decisions the chapter cares about.

- **Benoit, William L. *Accounts, Excuses, and Apologies: A Theory of
  Image Restoration Strategies* (1995; revised 2015).** The other major
  framework. Useful as the source for the apology / mortification /
  corrective-action / bolstering / denial taxonomy. Pre-dates social
  media but the typology survived the transition essentially intact.

- **Coombs & Holladay, "Helping Crisis Managers Protect Reputational
  Assets: Initial Tests of the Situational Crisis Communication
  Theory," *Management Communication Quarterly* 16(2), 2002.** The
  empirical validation that produced the SCCT response-matching
  matrix. Useful as the source for the "match response posture to
  attribution of responsibility" claim.

- **Schultz, Utz & Göritz (2011), "Is the medium the message?
  Perceptions of and reactions to crisis communication via Twitter,
  blogs and traditional media," *Public Relations Review* 37(1).**
  One of the first rigorous studies showing channel choice itself
  affects crisis-response evaluation. Predates much of the modern
  tooling but the framing is durable.

- **Pang, Jin & Cameron, "Contingency Theory of Strategic Conflict
  Management," in *Handbook of Crisis Communication* (2010, eds.
  Coombs & Holladay).** Useful for the "advocacy to accommodation
  continuum" framing — the chapter's tone-calibration spectrum has
  an academic home.

**Regulatory, legal, and platform-governance sources**

- **FTC Act Section 5 — "unfair or deceptive acts or practices."**
  Underlies enforcement when a crisis involves the brand making
  misleading claims either in the original conduct or in the
  response. Specifically relevant for product-safety crises and for
  "we have investigated ourselves and found no wrongdoing"
  responses that turn out to be false.

- **SEC Regulation FD (Fair Disclosure) and the Netflix / Reed
  Hastings 2012 SEC investigation (closed 2013, no enforcement).**
  Establishes that social media posts by executives can
  constitute material disclosure for publicly traded firms. The
  related 2013 SEC guidance is the primary document. Aging
  risk: low.

- **EU Digital Services Act (Regulation EU 2022/2065), Articles
  16, 22, 35.** Establishes platform obligations for content
  takedown and trusted-flagger systems that brands operating in
  the EU now interact with during crises.

- **NIST AI Risk Management Framework (AI RMF 1.0, 2023) and the
  AI RMF Generative AI Profile (2024).** Includes synthetic-media
  detection guidance, content-provenance recommendations, and the
  C2PA standard reference — directly relevant to the deepfake
  detection section.

- **Coalition for Content Provenance and Authenticity (C2PA)
  Technical Specification 1.x.** The cryptographic
  content-credential standard increasingly adopted by camera
  makers, generative-AI vendors (OpenAI, Adobe, Microsoft),
  and platforms (TikTok, LinkedIn beginning rollout 2024–2025).

- **EU AI Act (Regulation EU 2024/1689), Articles 50 and 52.**
  Transparency obligations for AI-generated content and deepfakes,
  with phased entry into force through 2026. Primary text matters
  because press summaries are inconsistent on what is required of
  whom by when.

**Empirical primary sources on social-media crises**

- **Hong & Cameron (2018), "Will comments change your opinion?
  The persuasion effects of online comments and heuristic cues
  in crisis communication," *Journal of Contingencies and Crisis
  Management* 26(1).** Comment sections actively reshape how the
  audience reads the brand's response. Useful for the "monitor
  the conversation around the response, not only the response"
  claim.

- **Vraga, Bode & Tully (2022), "The Effects of a News Literacy
  Video and Real-Time Corrections to Video Misinformation
  Related to Sunscreen and Skin Cancer," *Health Communication*
  37(13).** One of the cleanest studies on real-time correction
  effectiveness. Cites a small but real backfire risk and a
  substantially larger correction benefit when the response is
  fast, factual, and from a credible source.

- **Vosoughi, Roy & Aral (2018), "The spread of true and false
  news online," *Science* 359(6380).** The "false news travels
  faster than true news on Twitter" study. Sample size and
  methodology are rigorous and well-documented. Relevant to
  the "when to respond" timing decision because it quantifies
  how much faster the rumor moves than the correction.

- **Kim & Atkinson (2014), "Responding to crises on social
  media: The impact of acknowledgment and corporate social
  responsibility on apology effectiveness," *Public Relations
  Review* 40(3).** Empirical work on apology format
  effectiveness in social channels specifically.

**Documented case sources (use these for cases, not the press summaries)**

- **United Airlines / Dr. David Dao incident, April 9, 2017.**
  The flight 3411 forcible-removal video. Useful for the
  speed-of-response failure mode and for the contrast between
  the initial CEO statement (defensive) and the second
  statement (mortification). Primary sources: United
  Airlines's published statements, the U.S. House Transportation
  Committee hearing record (April 26, 2017), the eventual
  settlement announcement.

- **KFC UK "FCK" chicken-shortage response (February 2018).**
  Usually cited as a model response: full-page newspaper ad,
  rearranged logo letters, brief honest acknowledgment.
  Primary: the actual ad image (in the public record), KFC UK's
  statements, the agency credit (Mother London).

- **Tylenol cyanide tampering response (1982, Johnson &
  Johnson).** Pre-social-media but is the canonical case
  taught in every PR program. Primary: the J&J public
  statements, the FDA's contemporaneous reports, the
  Congressional hearing record. The "Tylenol playbook"
  reference can be made carefully; readers should know it
  was specific to a unique situation.

- **Pepsi / Kendall Jenner ad (April 2017).** A planned
  campaign rather than an external crisis but illustrative of
  brand-self-inflicted crisis. The ad and Pepsi's statement
  pulling it are both public.

- **Boeing 737 MAX response timeline (October 2018 onward).**
  The opposite of the J&J Tylenol playbook — sustained,
  multi-year, multi-statement, and instructive on what
  defensive posture costs reputationally and financially.
  Primary: SEC filings, Congressional hearing transcripts,
  the DOJ deferred-prosecution agreement (January 2021),
  the FAA's certification report.

- **Bud Light / Dylan Mulvaney response, April–May 2023.**
  Useful as a case where the silence-or-respond decision was
  the entire crisis. Primary: AB InBev's statements,
  earnings-call transcripts, the SEC 10-Q filings showing
  the volume impact.

- **Cracker Barrel rebrand response, August 2025.** A recent
  reputation-management case where the rebrand was reversed
  in days under social-media pressure. Useful because it is
  recent enough to feel live and old enough to have a
  documented arc.

**Platform / tool documentation (aging risk: high — flag for re-verification)**

- Meltwater, Brandwatch, Sprinklr, Talkwalker, Sprout Social
  Listening, Hootsuite Insights, Mention, Awario — vendor
  documentation on monitoring, sentiment, and alerting. Treat
  feature-level claims as snapshot.
- TikTok and Meta crisis-escalation channels for brands.
- X's API restrictions post-2023 and what they did to
  monitoring practice (substantial — many tools lost real-time
  X access in 2023 and rebuilt around partial sampling).

**Trade press for current cases (not for principles)**

- *PRWeek*, *Holmes Report* / PRovoke Media, *Adweek*,
  *Ad Age*, *Communications Week*. Use for case discovery
  and verification; not as authority on best practice.

---

## 2. State of the Field

Crisis-and-reputation work in social-media-era marketing sits at the
intersection of three older practices (corporate communications, PR,
customer service) and one new one (real-time platform monitoring at
volume). The state of the field as of 2025–2026:

**Monitoring has become genuinely good.** The category of tools that
do real-time mention monitoring, sentiment classification, anomaly
detection, and topic clustering across platforms is mature. A
mid-budget brand in 2025 can detect a developing crisis within
minutes of the inflection point, where in 2015 the same brand might
have learned about it through a journalist's call. This is real
progress and the chapter should not minimize it.

**Sentiment classification is still bad in important ways.** Off-the-
shelf sentiment scores are reliable in aggregate (averages over
thousands of posts) and unreliable at the individual-post level
where it matters most during crisis. The failure modes are
predictable: sarcasm, in-group language, multilingual posts,
context-dependent slang, and statements that mention the brand in
the third person while criticizing a competitor. Tools have
improved (transformer-based classifiers in 2024–2025 outperform
the lexicon-based ones common in 2018) but the individual-post
ceiling is still below what an attentive human reader achieves.

**Response timing has compressed.** The window between an incident
becoming visible and the audience expecting a brand statement has
been compressing for fifteen years. In 2010 it was measured in
days. In 2017–2018 (United, KFC) it was measured in hours. In
2024–2025 it is measured in single-digit hours for major
incidents and minutes for active customer-service crises. The
compression has not stopped.

**Tone calibration has become the differentiator.** When every
brand can monitor in real time and respond fast, the question
shifts to what kind of response. The chapter's central practical
contribution is the calibration framework: when does a situation
call for a corporate-formal statement, when for an authentic
human apology in the voice of a specific leader, when for
silence, and when for refusing to engage on the asker's terms.
This is judgment, not pattern.

**Deepfakes and synthetic media are no longer hypothetical.**
The 2023–2024 wave of fake voice and video content targeting
specific executives (most prominently the spoofed CEOs used in
2024 fraud cases) means brands now have to think about
provenance, denial-with-proof, and the C2PA / content-credential
infrastructure. By 2026, "is this video of our CEO real" is a
question the social team has to be able to answer in minutes,
not days.

**Customer-service crisis and reputation crisis are merging.**
The pattern where a single unresolved customer complaint becomes
a viral reputation event (the United guitar case, the Comcast
Ryan Block call, the Peloton wife video) has stabilized as a
category. Monitoring needs to cover both lanes and routing
between them is itself a judgment call.

**Where AI is currently load-bearing**

- High-volume real-time mention monitoring across platforms.
- Anomaly detection — spike in mention volume, spike in
  negative sentiment, sudden coordinated posting patterns.
- Topic and entity extraction — what specifically is being
  said.
- Translation for international monitoring.
- Sentiment / emotion classification (with the caveats above).
- First-draft response generation for routine customer-service
  responses.
- Triage routing — what gets escalated to whom.
- Synthetic-media detection (early-stage but improving fast).

**Where AI is currently bad**

- Tone calibration in the specific crisis at the specific moment.
- Reading whether an audience wants an apology or a denial.
- Reading whether silence is the right move.
- Distinguishing a real crisis from a coordinated bad-faith
  pile-on that will pass if not fed.
- Judging whether a particular drafted response sounds like the
  CEO or sounds like a CEO.
- Crisis-response decisions that have legal exposure (those
  belong with counsel, not with the model).
- Recognizing the moment in a multi-week crisis when the brand
  should change posture.

---

## 3. Application Domain

The reader is a working social media manager or marketing
professional who is either (a) sitting in the crisis response
seat themselves, (b) the person who would be pulled into the
war room when one starts, or (c) running the monitoring layer
that detects them. The reader's day-to-day decisions in this
domain look like this:

**Monitoring configuration.** What keywords, accounts, languages,
hashtags, and threshold rules trigger an alert. AI tools come
with defaults; the defaults are usually wrong for any specific
brand. The configuration is a one-time judgment task, revisited
periodically. The chapter should provide a checklist for
calibration: brand names + common misspellings, product names,
executive names, key competitor names (because crises sometimes
arrive via competitor association), category-risk keywords
(recall, lawsuit, allergy, fire, injury), and language coverage.

**The escalation decision.** A mention has been flagged. Is this
an actual crisis, a customer-service ticket, a routine
complaint, a bad-faith brigade, or noise? The triage decision is
the highest-leverage judgment call in the chapter. AI can give
the signal; the human has to read it. Useful criteria for the
chapter to surface: rate of growth (volume per hour vs.
baseline), reach into accounts outside the brand's normal
audience graph, presence of named individuals or photographic
evidence, presence of journalist accounts, and whether the
complaint is factually correct.

**The wait-or-respond decision.** Once a crisis is real, the
question is whether responding now or waiting one news cycle
helps more. Sometimes silence works (the bad-faith pile-on that
will pass). Sometimes silence kills (the active safety incident
where the brand looks negligent). This is the most subjective
judgment in the chapter and the one that most needs a
framework. Coombs's SCCT typology and Benoit's image-restoration
framework both have something to say here.

**Tone calibration.** Corporate-legal-formal vs. CEO-personal-
authentic vs. operational-customer-service vs. ironic-self-
aware (KFC FCK) vs. silent vs. refusing-to-engage. The choice
is not a vibe call — it is a function of crisis type
(SCCT victim / accidental / preventable), audience (B2C
consumers vs. enterprise buyers vs. regulators vs. all of the
above), and prior brand voice. AI is genuinely useful for
drafting any of the five postures once the human picks one.
AI should not pick.

**Drafting the response.** First drafts in the chosen tone.
AI does this competently. The judgment work is editing for
specificity (the names of specific people, the named action
the brand will take, the date by which) and for the absence
of language that will read as defensive in the next news
cycle.

**Live monitoring during the response window.** Once a
response is published, the conversation around the response
is itself the next crisis (Hong & Cameron 2018). AI monitors
that. Humans decide whether to amend, double down, or go
quiet.

**Deepfake / synthetic-media response.** A fake video of the
CEO surfaces. The decisions: verify (using C2PA content
credentials, original-source confirmation, technical
detection tooling), publish a denial (with the evidence of
fakeness, not just the assertion), request takedown from
platforms (using the trusted-flagger channels), and decide
whether to escalate to law enforcement. AI helps with
detection and with drafting the denial; the verification and
escalation calls are human.

**Post-crisis reputation repair.** The first 72 hours are
acute; the next 90 days are reputational. The chapter should
acknowledge that this slower work — quiet operational
follow-through, customer-service repair, deliberate positive
content programming, sometimes a slow public reckoning months
later — is where reputation actually rebuilds. AI helps with
monitoring and content production; the program design is
human.

---

## 4. Thesis Connection

Crisis-and-reputation is the chapter where the thesis is
sharpest, because the cost of a category error in either
direction is most visible. Delegating pattern work the human
shouldn't do (drafting tones, monitoring at scale) wastes the
crisis team's hours during the window when they are most
expensive. Delegating judgment work AI shouldn't do (response
posture, wait-or-respond, tone calibration, the public denial
of a deepfake) produces outputs that read as either
indifferent or wrong, and either failure mode makes the
underlying crisis worse.

**Pattern-shaped work AI handles well (Delegate List):**

1. Real-time mention monitoring across platforms, including
   the long tail (Reddit, Discord, regional platforms).
2. Volume-anomaly detection — flag when mention rate
   substantially exceeds baseline.
3. Topic and entity clustering — what specifically is being
   said about whom.
4. Translation for international monitoring at scale.
5. Aggregate sentiment classification (averages reliable;
   individual posts not).
6. Triage routing of incoming customer-service mentions
   versus reputation mentions versus noise.
7. Drafting first-pass responses in a specified posture.
8. Synthetic-media detection signal (one input to the
   verification decision, not the decision itself).
9. Post-crisis sentiment tracking and recovery
   measurement.

**Judgment-shaped work that currently requires a human (Guard List):**

1. *The escalation call.* Is this a crisis, a brigade, a
   ticket, or noise. AI can flag; the human decides.
2. *The wait-or-respond call.* Whether silence is strategic
   or negligent in this specific situation.
3. *Tone calibration.* Which of the five postures (corporate-
   formal, executive-personal, operational, ironic-self-
   aware, silent) the situation requires.
4. *The legal and regulatory call.* Decisions with FTC, SEC,
   FDA, or EU regulatory exposure belong with counsel and
   the human team.
5. *Verifying synthetic media.* The judgment that a
   particular video is or isn't real, even after detection
   tooling has run, requires human verification through
   original sources.
6. *Reading the comment section around the brand's response.*
   Whether the audience has accepted the response or is
   reading it as defensive.
7. *The amend / double-down / silence call after the first
   response.* The second move in a crisis is harder than the
   first.
8. *Post-crisis program design.* The 90-day reputation-repair
   plan.
9. *Naming specific accountability.* A response that names a
   specific leader, a specific action, and a specific
   deadline is doing work no template can do.

The chapter's strongest aphorism candidate: *AI watches; the
human responds.* Or more carefully: *AI tells you something is
happening; the human tells you what kind of thing.*

---

## 5. Wayback Candidates

Two or three lesser-known historical figures whose work
prefigures something specific about crisis-and-reputation
judgment. Wikipedia-accessible, diverse, useful as analogies.

**Candidate 1 — Ida B. Wells (1862–1931), journalist,
investigator, organizer.** Wells's investigative pamphlets
on lynching — particularly *Southern Horrors* (1892) and *The
Red Record* (1895) — are the founding documents of
data-driven crisis reporting. The chapter hook: Wells faced
a coordinated information environment hostile to her
findings and chose a specific reputational strategy — relentless
documentation with named places, dates, and victims, published
through her own channels, with deliberate distribution to
international audiences who could pressure U.S. institutions
the U.S. press would not pressure. This is structurally a
crisis-response playbook: when the conventional response
channels (mainstream press, established institutions) are
captured or unwilling, you build the alternative channel and
let the evidence carry. The chapter can use Wells as the
historical anchor for the claim that documented specificity
beats vague reassurance, and that the channel decision is
itself part of the response posture.

**Candidate 2 — Edward Bernays (1891–1995), publicist and
propagandist.** Bernays is in some ways the wrong figure for
this book — he was a manipulator and the genealogy from
Bernays to modern PR is partly a genealogy of the things this
book is trying to push back against. But that is precisely
why he is useful: the chapter can use Bernays specifically as
the negative example, the figure who built the corporate-PR
machinery whose default mode is exactly the
corporate-legal-formal posture that no longer works in
social-media crises. Cite him to make a sharper point about
why the modern landscape rewards mortification over the
Bernays playbook of strategic distraction. (Caution: Bernays
is widely known; the "lesser-known" criterion is better
served by Wells. Use Bernays only as a foil if at all.)

**Candidate 3 — Madeleine Albright (1937–2022), diplomat and
U.S. Secretary of State.** Albright's career provides an
excellent model for tone calibration under hostile attention.
The pin-language work — her use of brooches as deliberate
signals during diplomatic crises, documented in her memoir
*Read My Pins* — is a charmingly specific example of
non-verbal response design in environments where every word
is over-read. More substantively, her handling of the 1996
"60 Minutes" Iraq sanctions interview (the much-quoted
"we think the price is worth it" exchange) is a documented
case of a single response in a high-pressure moment shaping
years of reputational consequence. The chapter can use
Albright to make the point that, in a media environment
that captures every word, the moment of response is itself
the message and there is no separate "correction" later.

**Candidate 4 — Lillian Wald (1867–1940), nurse and reformer.**
Wald founded the Henry Street Settlement in New York and was
a master of what would now be called stakeholder
communications during cholera, tuberculosis, and influenza
outbreaks on the Lower East Side. Her practice of
transparent operational reporting (publishing exactly how
many people were sick where, what services were being
provided, what was failing) during the 1918 flu pandemic
is structurally identical to the modern "operational
transparency during product-safety crisis" posture. Useful
as a counter-example to the corporate-defensive default.

Selection recommendation: Wells and Wald together. Wells
for the "build your own channel, document specifically"
move; Wald for the "operational transparency during ongoing
crisis" move. Both Wikipedia-accessible, both diverse, both
materially useful as analogies for working practitioners.

---

## 6. Pedagogy

The reader is being trained to make decisions under time
pressure, often without complete information, sometimes with
career or legal consequences. Pedagogy should reflect that
this is the chapter where getting the boundary wrong is most
expensive.

**Opening case.** Use a documented case where the
AI-or-template response was published when a human-calibrated
response was needed. Several recent candidates: the early
2020s wave of brands posting algorithmically templated
Black-square / solidarity statements during the 2020 protests
(many subsequently embarrassing); the wave of brands using
Threads' early auto-suggestions to post default greetings
that read as oblivious during simultaneous news events; or
constructed examples drawn from documented public cases. Use
a real one if it can be sourced cleanly; label any
construction as illustrative.

**Coombs SCCT typology, briefly.** A one-page treatment of
the victim / accidental / preventable distinction and how
the appropriate response posture changes across the three.
This is the academic scaffold the chapter borrows. Do not
overdo it; the practitioner reader wants the framework, not
the citation tree.

**The five postures.** Lay out the response postures
explicitly: (1) corporate-legal-formal statement, (2) named
executive personal acknowledgment, (3) operational
customer-service response, (4) ironic-self-aware
acknowledgment (the KFC FCK posture), (5) deliberate
silence or refusal-to-engage. For each, give an example
case and the conditions under which it is the right choice.

**The wait-or-respond decision tree.** A small flowchart or
checklist: is the underlying claim factually accurate; is
there a safety dimension; is the rate of spread accelerating;
are journalists picking it up; does silence have an honest
operational reason. The chapter does not need to make every
decision for the reader; it needs to give them the questions.

**Worked example.** Walk one crisis end-to-end. A
constructed example involving a mid-size B2C brand, a
viral customer-service video, and a 72-hour response
window is sufficient. Show the monitoring layer (AI), the
escalation call (human), the wait-or-respond decision
(human, with AI-provided context on rate-of-spread), the
posture choice (human), the draft (AI), the edit
(human), the publication, the post-publication monitoring
(AI), the second-move decision (human), the 90-day plan
(human, with AI-supported tracking).

**Deepfake response drill.** A short separate section on
synthetic-media incidents, because the response pattern
is materially different (verification-first rather than
response-first) and the chapter would otherwise blur the
two.

**Copy-paste Claude Code prompt.** Two prompts:
(a) a triage prompt that takes the live mention feed and
classifies items as ticket / noise / brigade / developing
crisis with explicit confidence scoring and "escalate to
human" flags; (b) a response-drafting prompt that takes
the chosen posture and the documented facts and produces
a first draft, with explicit blanks for the named
executive, the named action, and the named deadline.

**Exercises.** One useful exercise: take three publicly
documented crisis responses (e.g., United 2017, KFC 2018,
Bud Light 2023) and classify them on the Coombs typology
and the five-posture framework. Then identify what the
response would have looked like under each of the other
four postures. The exercise is to make the calibration
choice feel like a choice.

**Plain-language definitions.** "Situational Crisis
Communication Theory (SCCT)," "image restoration,"
"mortification," "bolstering," "operational transparency,"
"deepfake / synthetic media," "content provenance / C2PA,"
"trusted flagger," "share of voice," "earned-media value,"
"brigade vs. crisis."

**Misconceptions to break.**
(1) "Always respond fast." False — silence is sometimes
the right move; the worst response is fast and wrong.
(2) "Apologize for everything." False — apologizing for
something that isn't your fault confuses attribution and
weakens the next apology.
(3) "Sentiment scores tell you whether you're winning."
False at the individual-post level; useful only in
aggregate trend.
(4) "Deepfakes can be solved by detection tools alone."
False — the verification chain is human-centered;
detection is one input.
(5) "The crisis is over when the volume drops." False —
reputation work continues for months after acute volume.

---

## 7. Representation

Crisis-and-reputation is a domain where representation
shows up in two ways: who appears in the examples and
whose experience the framework implicitly centers.

- *Geography.* The case literature in this field is heavily
  U.S.-centric and English-language-centric. The chapter
  should include at least one non-U.S. case (Volkswagen
  diesel response in Europe, the Samsung Galaxy Note 7
  response in South Korea and globally, the Maggi noodle
  lead-contamination crisis in India 2015, the Domino's
  Russia response 2022) and at least one non-English-
  language consideration in the monitoring section.

- *Industry.* Crisis communication research over-indexes on
  airlines, fast food, and consumer-products recalls. The
  chapter should include at least one B2B case (the
  SolarWinds breach response, the CrowdStrike July 2024
  outage response, the Okta 2022 disclosure), at least
  one nonprofit / NGO case, and at least one government /
  public-sector case where the dynamics differ usefully.

- *Crisis type.* Product safety, executive misconduct,
  workplace-treatment disclosures, accidental
  cultural-insensitivity, deliberate-but-contested
  political stances, and supply-chain disclosures all
  call for different postures. The chapter should not
  treat "crisis" as one thing.

- *Wells in Section 5* anchors a historical example from
  outside the corporate-PR tradition. Use it.

- *Voice in the writing.* The chapter is about response
  posture; the chapter itself should not adopt the
  corporate-legal-formal posture it warns against.

What to avoid: presenting crisis communication as a
neutral technical practice. The decisions it covers have
political, ethical, and human-cost dimensions; the
chapter can acknowledge those without becoming a
philosophy lecture.

---

## 8. Open Questions

1. *Generative-AI-produced crisis content.* What is the
   chapter's position when the original crisis-causing
   content is itself AI-generated by a hostile party? The
   verification-first framing partially handles this, but
   the response-design question (do you publicly
   acknowledge the AI provenance) is contested.

2. *Coordinated inauthentic amplification.* When the
   "crisis" is actually a bot-driven amplification of a
   real but small grievance, the right response is
   genuinely different from a real crisis. The chapter
   should take a position, with the caveat that
   misclassifying a real grievance as a brigade is the
   worse error.

3. *The role of the CEO in social-media crisis.* When
   does the CEO personally post, when does the brand
   account post, when does a third party (a trade
   association, a regulator, an investigator) speak for
   the brand. The Boeing trajectory suggests the CEO
   should speak earlier than corporate practice
   generally does; the chapter should take a position.

4. *AI-assisted response under regulatory disclosure
   rules.* If a publicly traded company uses AI to draft
   a material-disclosure-affecting social post, who is
   responsible for accuracy. The SEC has not yet ruled
   directly; the chapter should flag the question.

5. *Crisis communication as labor.* Real crisis response
   on social media is brutal on the team running the
   account — sleep loss, abuse exposure, sometimes
   threats. The chapter should at least acknowledge this
   in the operational section.

6. *International disclosure asymmetries.* A single
   incident may require different responses in U.S.,
   EU, UK, and APAC jurisdictions for legal reasons.
   The chapter should flag this without becoming a
   compliance treatise.

7. *Wayback for synthetic media.* The deepfake-response
   section will age fastest. Frame the principles
   ("verification before denial," "publish evidence
   not assertion," "use platform takedown channels")
   not the specific tools.

---

## 9. Sourcing Notes

- Coombs's SCCT papers and Benoit's image-restoration work
  are the two academic frameworks worth citing directly. Both
  predate the modern social era but their typologies have
  held.
- The Vosoughi 2018 *Science* paper is the empirical
  source most worth citing for the "false news spreads
  faster" claim. Cite it once, accurately.
- The Tylenol case is over-cited in PR textbooks. Use it
  briefly, with explicit acknowledgment of how unusual
  the situation was (a third-party poisoning, not a
  brand failure).
- The United 2017 case is fully documented and the
  primary materials are accessible (the Congressional
  hearing record is the cleanest source).
- The Bud Light 2023 case is recent enough that
  reputable analysis is still mixed; use it carefully
  and prefer SEC filings to commentary.
- The Cracker Barrel August 2025 case is the most recent
  documented brand-driven crisis-response reversal at
  the time of drafting; appropriate for an opening
  scene because it is recent enough to feel live.
- The C2PA specification and the NIST AI RMF Generative
  AI Profile are the right primary sources for the
  synthetic-media section. The EU AI Act articles are
  also primary; the press summaries of the EU AI Act
  are inconsistent on what is required when.
- Vendor documentation (Meltwater, Brandwatch, Sprinklr,
  Talkwalker, Sprout Social) should be linked, not
  quoted at length. Feature claims age within months.
- The X / Twitter API changes of 2023 should be
  acknowledged once — they materially changed what
  real-time monitoring is possible on that platform —
  without becoming a chapter on platform politics.
- The historical figures in Section 5 are well-served by
  one biographical secondary source each (Paula Giddings's
  *Ida: A Sword Among Lions* for Wells, Marjorie Feld's
  *Lillian Wald: A Biography* for Wald).
- Constructed examples must be labeled as illustrative
  in the prose. The reader trusts the chapter more for
  the labeling.
- Where a recent platform-specific feature is named
  (e.g., TikTok's developing trusted-flagger system,
  LinkedIn's content-credentials rollout), give the
  rough date and flag that the reader should verify
  current state.
