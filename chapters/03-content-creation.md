# Chapter 3 — Content Creation

*Drafting, variation, ideation are pattern-shaped. Voice, angle, originality are judgment-shaped. Where the framework first meets the work practitioners do most.*

---

In November 2023, *Sports Illustrated* published product reviews under bylines that did not exist. The authors had AI-generated headshots. The articles were fluent. The sentences parsed. The grammar was clean. Then *Futurism* reporters found the headshots for sale on a stock-image marketplace, and the whole structure came apart — not because the prose failed, but because the contract the magazine had with its readers turned out to be synthetic. The contract was: a person with this name and face used this product and is telling you what they found. That contract collapsed. The licensing deal between Arena Group and the SI brand ended within weeks.

A year earlier, in 2022, Heinz prompted DALL-E with a single word — "ketchup" — and watched the model return image after image of bottles that looked like Heinz. The model had been trained on the internet's accumulated image of ketchup, and the internet's image of ketchup was Heinz. The marketing team turned this into a campaign: *Even AI knows the most iconic ketchup is Heinz.* Ad Age covered it as the canonical early example of generative AI used well in brand marketing. The combinatorial output of the model was the creative material. The judgment that *this was the campaign* was human.

Two cases. Same technology. One brand used AI for variation under human creative direction and got a campaign. One brand used AI to fabricate identity and lost the brand. The difference was not the tool. The difference was where the boundary was drawn.

Content creation is the task most social media practitioners default to delegating first, because drafting is the most visible time sink and the models are genuinely good at it. Noy and Zhang, writing in *Science* in 2023, found that ChatGPT cut average writing time by forty percent and raised average quality by eighteen percent on mid-skill writing tasks. The spread narrowed: the weakest writers improved more than the strongest. That is an honest productivity finding. Pretending otherwise would be intellectually dishonest about what these tools actually do.

But content creation is also the task where the over-delegation failure mode is most visible — at the byline level, at the voice level, and over time at the feed level. Doshi and Hauser, writing in *Science Advances* in 2024, found something that complicates the Noy-Zhang result: AI-assisted writers individually produced more creative outputs on average, but the *collective set* of outputs converged. Fewer distinct ideas across writers using the same model. The individual output gets better. The pool of outputs gets blander. For a single practitioner, the productivity gain is real. For a brand publishing across months, the homogenization effect is structural — and quiet. It does not announce itself. It accumulates.

![Two-line chart with AI assistance intensity on the horizontal axis and a 0–100 relative index on the vertical axis. A gray line for individual writing quality rises monotonically from about 60 to 85. A red line for collective distinctiveness across writers falls monotonically from about 80 to 45. The two lines cross at moderate AI use and a shaded zone to the right marks the structural homogenization region.](../images/03-content-creation-fig-01.png)

*Figure 3.1 — Individual quality rises; collective distinctiveness falls. The chapter's load-bearing empirical claim.*

<!-- → [CHART: Two-line chart illustrating the Doshi-Hauser divergence — x-axis: individual writer output quality; y-axis: collective distinctiveness of the output set; one line trends up (individual quality), one trends down (collective originality) as AI assistance increases — student should see that the two metrics move in opposite directions] -->

The job of this chapter is to draw the boundary inside content creation. Not across it — not "delegate content creation" or "guard content creation." Inside it. Some of the work is pattern-shaped. Some of it is judgment-shaped. The chapter is about which is which, and why confusing them costs you something specific.

---

## What Is Pattern-Shaped Here

The pattern-shaped work in content creation is any task where the output can be specified completely enough in a brief that a capable model will hit draft quality without needing to know things that live only in a human head.

First-draft prose from a brief. Given audience, format, length, angle, and tone, current models produce captions, threads, carousel scripts, and short-form video scripts at draft quality that an editing human can finish fast. The brief has to constrain enough that the output is close to publishable on the first pass. Generic prompts produce generic output; specific prompts produce drafts that need voice review only. The constraint is in the brief, not in the model.

| Brief element | What it constrains | What goes wrong if it is missing |
|---|---|---|
| Audience | Reading level, prior knowledge, register, jargon tolerance | Output pitched at a generic mid-funnel reader nobody actually is |
| Format | Caption vs thread vs carousel script vs short-form video script | Model defaults to a paragraph-shaped blob that fits no platform |
| Length | Word or character ceiling and floor | Drafts run long, lose the hook, or compress past the angle |
| Angle | The specific take the post advances | Generic-fluent restatement of consensus; nothing to defend |
| Tone | Voice-worksheet anchored register and cadence | Surface register approximately right, brand depth missing |
| Explicit "do not" | The taboos derived from voice worksheet | Banned phrases ("unlock," "leverage," "game-changer") leak through |

*Figure 3.2 — Anatomy of a drafting brief: six constraints, what each one does, and the predictable failure when it is left implicit.*

<!-- → [TABLE: Sample drafting brief anatomy — columns: brief element (audience / format / length / angle / tone / explicit "do not"), what it constrains, what goes wrong if it's missing] -->

Variation generation. Given an approved core message, producing ten or twenty rephrasings for A/B testing or platform-specific adaptation is what these systems are built for. Variation is the model's strongest move. The combinatorial output that made "Even AI knows ketchup is Heinz" a campaign is the same capability that makes caption A/B testing cheap. The work is selecting among variants, not generating them.

Format adaptation. Taking a long-form piece and compressing it into a thread. Taking a thread and expanding it into an essay. Taking a script and rewriting it for a different platform's conventions. These conversions follow learnable rules. The model has learned them.

Bounded ideation brainstorms. Given a campaign theme or content pillar, producing twenty candidate angles for a human to select among. The selection is judgment; the production of candidates is pattern work. The risk of mis-labeling this is the risk of letting the model select the angle, which is not what bounded ideation means.

Format-level production tasks. Hashtag and tag research. Alt-text generation. Repost and quote-post copy. Pre-publication checks — reading level, banned phrases, legal-risk flagging against a maintained list of trigger phrases. These are pattern tasks that humans drift on under deadline. The cost of drifting is not catastrophic on any single post, but it compounds across a feed.

| Task | Why pattern-shaped | Time saved per week | Quality risk if skipped |
|---|---|---|---|
| First-draft prose from a constrained brief | Output specifiable in brief; model hits draft quality reliably | 3–4 hours | Low; editor finishes fast on the first pass |
| Variation generation for A/B testing | Combinatorial rephrasing is the model's strongest move | 45–60 minutes | Low; selection is still human |
| Format adaptation (long → thread, thread → essay) | Conversion rules are learnable and learned | 45–60 minutes | Low; conversions follow stable rules |
| Bounded ideation (20 candidate angles for selection) | Production of candidates is pattern work | 30–45 minutes | Low if selection stays human |
| Hashtag and tag research for a campaign theme | Discoverability follows platform conventions the model has | 20–30 minutes | Low; reach drift, not voice drift |
| Alt-text generation for image carousels | Description against image is straightforward retrieval | 15–20 minutes | Low; accessibility floor easier to hit |
| Pre-publication legal and brand-trigger scan | Pattern check against a maintained trigger list | 20–30 minutes | Medium if the trigger list is stale; review on hits |

*Figure 3.3 — Delegate List for a B2B SaaS social manager: where the five-to-seven-hour weekly recovery comes from.*

<!-- → [TABLE: Delegate List for a B2B SaaS social manager — tasks, why pattern-shaped, time saved, quality risk if skipped — drawn from chapter source] -->

A practitioner who delegates these items in 2026 and hand-writes everything else recovers five to seven hours a week. A practitioner who cannot articulate *why* these items are safe to delegate will eventually delegate the judgment-shaped work too, because the items look the same from the outside. The brief looks like a brief. The draft looks like a draft. The model's output is fluent whether the work was pattern-shaped or not. The fluency is the problem. It masks the difference between a task that can be delegated and a task that cannot.

---

## What Is Judgment-Shaped Here

The judgment-shaped work in content creation is any task where the correct output depends on things that do not fit in a brief — things that live in the head of someone who has been writing for this brand, or in the head of the named individual whose byline will appear on the post.

Voice. Not the surface markers of voice — register, cadence, sentence-length distribution, vocabulary choices — but the accumulated record of the brand's decisions about what it cares about, what it refuses to say, what the founder or the lead writer would never publish. Ursula K. Le Guin's argument in *Steering the Craft*, published in 1998, is that voice cannot be taught directly. It is practiced into being through accumulated decisions. The same argument applies to brand voice. A model can imitate the surface and miss the depth. The surface is what appears in the corpus. The depth is the decisions that never made it into the corpus — the post that was pulled, the angle that was rejected, the phrase the founder hates.

Zora Neale Hurston walked back into Eatonville, Florida in 1928 with a notebook to record the speech of the community she had grown up in. She did not invent the dialogue in *Their Eyes Were Watching God*; she recorded the community for years and then composed from the recording. A model trained on her finished novels could reproduce the surface — the cadences, the spellings, the call-and-response structure — and miss everything that mattered. Voice is community-embedded. It is recorded, not generated. The same structural claim applies, modestly, to brand voice.

Angle selection. The take, position, or argument a post advances. Angle is upstream of drafting. By the time you are editing the prose, the angle is already chosen — and the angle is where the voice lives. The model can produce twenty candidate angles; the practitioner selects the one the brand actually believes and can defend. Letting the model select is letting the model decide what the brand thinks, which is not delegation of a writing task. It is delegation of a positioning decision.

Cultural-moment response. Whether to react at all to a moment in the broader culture. What tone the brand can credibly take given what it has said before. Which moments are the brand's to comment on and which are not. The failure mode is AI-fluent reactive copy that reads as opportunistic because the model has no access to the implicit rules that govern which moments the brand enters. The fluency makes it worse. The post sounds confident. It reads as tone-deaf.

Founder or named-executive voice. A post in the CEO's name that the CEO would never have written erodes the trust that made the CEO worth following. This is not a surface problem. The Sports Illustrated failure was a byline failure. The contract the reader had was: a person with this name stands behind these words. When the named person has not read the words, the contract is void before the post goes up. The detection is accidental and public. The cost is not proportional to the magnitude of the deception. It is proportional to the distance between what the reader trusted and what was actually true.

| Judgment-shaped task | What goes wrong if delegated | Required human role | Escalation trigger |
|---|---|---|---|
| Brand voice (depth, not surface) | Surface markers match; decisions that never made the corpus do not — voice drifts toward generic-fluent | Practitioner who has been writing for the brand long enough to know what it would never publish | Voice pass on every AI-drafted post before any other edit |
| Angle selection on a topic | Model picks the consensus angle; brand publishes what it doesn't actually believe | Brand strategist or lead writer who knows the positioning | Any post taking a public position |
| Cultural-moment response | AI-fluent reactive copy reads as opportunistic; brand has no real stake in the moment | Senior practitioner reading what the brand can credibly say | Any reactive post within 24 hours of a cultural event |
| Founder / named-executive voice | Byline contract voids; named person did not stand behind the words | The named individual reads and approves before publication | Every post under a named byline |
| Feed-level originality | Doshi-Hauser convergence flattens the feed over weeks; no single post fails | Practitioner sampling 5–10 posts weekly as the audience reads | Weekly feed-level audit on the calendar |
| Decision to publish (timing, context) | Post lands during news event, live complaint thread, or after internal angle change | Practitioner with current-context awareness at shipping time | Every publish action |

*Figure 3.4 — Guard List for content creation: tasks where the +1 is the work.*


<!-- → [TABLE: Guard List — judgment-shaped tasks, what goes wrong if delegated, required human role, escalation trigger] -->

Originality at the feed level. Any single AI-drafted post can be original enough. A feed of AI-drafted posts converges. Doshi and Hauser's finding is not about individual posts. It is about the collective output across writers using the same models. For a brand publishing continuously, that finding applies to the brand's own feed across time: same prompts, same model, same voice-adjacent output, accumulating into a feed that gradually loses the property that made the audience want to follow it. Feed-level originality is not detectible by reading any single post. It requires reading the feed as the audience reads it — over time, sampling across weeks.

The decision to publish. The most consequential Guard item is the one that contains all the others: whether this post should go up now. The model cannot know the context — the news event that broke an hour ago, the customer complaint thread that is already live, the conversation the brand had internally that changed the angle. The model drafted. The human ships.

---

## What the Decomposition Looks Like

The framework's central move applied to one task. Consider a B2B SaaS social manager publishing a 1,200-word LinkedIn essay in the CEO's voice on a topic the company wants to own.

Topic selection: what does the CEO want to be known for this quarter? Guard. Strategic; depends on positioning and the CEO's actual interests, neither of which lives in a brief.

Angle on the topic: which take does the CEO actually defend? Guard. Depends on knowing the CEO.

Research synthesis: pull recent industry developments, supporting data, counterarguments. Delegate. Pattern-shaped retrieval and summary.

Outline: structure the essay around the angle. Delegate. Pattern-shaped given the angle.

First-draft prose: write the actual essay. Delegate. The model does this at draft quality; editing is fast.

Voice pass: does this sound like the CEO? Guard. The hardest move. Surface imitation is easy; depth requires the practitioner who has been writing for the CEO long enough to know what the CEO would never say.

Opening hook: the first one or two sentences. Guard. This is where voice is most exposed and where most engagement is decided. The model's instinct is generic-fluent. The CEO's instinct, if you know the CEO, is specific.

Closing line: the take-home the audience will quote. Guard. Same reasoning as the hook.

Hashtags and tags. Delegate. Pattern-shaped discoverability work.

Posting time and format tuning. Delegate. Pattern-shaped.

Pre-publication legal and brand check. Delegate, with human approval on flags. Pattern check; review on hits.

Decision to publish. Guard. The shipping decision.

First-hour comment monitoring and prioritized response. Sorting is Delegate; responding is Guard.

Thirteen steps. Eight Delegate, five Guard. Without decomposition, the practitioner either delegates the whole essay — voice failure on the voice pass, the hook, and the close — or hand-writes the whole thing and wastes time on research, the outline, the first draft, the tags, and the timing check. The decomposition is what produces the right boundary.

![Vertical workflow of thirteen numbered steps for drafting a CEO LinkedIn essay, color-coded Delegate (gray) and Guard (red). Five Guard steps — topic, angle, voice pass, hook, close, publish decision — carry italic annotations on the right naming what fails if delegated. Step 11 has an ochre flag-approval dot. Step 13 is a split rectangle showing sorting delegated and responding guarded. Bottom tally tiles read 8 Delegate, 5 Guard.](../images/03-content-creation-fig-02.png)

*Figure 3.5 — Thirteen steps in one CEO essay: eight Delegate, five Guard. Decomposition is what produces the right boundary.*

<!-- → [INFOGRAPHIC: Visual decomposition of the 13-step LinkedIn essay workflow — color-coded Delegate vs Guard at each step, with the five Guard steps highlighted and annotated with what fails if delegated] -->

A practitioner who runs this decomposition for every CEO essay will spend roughly ninety minutes per essay where they previously spent four to six hours. And they will produce essays that survive the CEO's read more reliably than the AI-only drafts they were producing six months ago, because the judgment-shaped steps are still human.

---

## The Playbook

Voice extraction is the one-time prerequisite that makes the rest work. Sit down with twenty to forty pieces of content your brand has published that you consider on-voice. Pull out three brand values that recur, three communication taboos, three signature phrases or framing devices, and one piece of content that is decidedly not this brand, with a sentence on why. This artifact — the voice worksheet — becomes the input to every AI drafting prompt. It is not a style guide. It is a constraint document. Style guides describe surface. Voice worksheets describe the depth that a surface can point toward but cannot fully contain.

Every AI drafting prompt should constrain on audience, format, length, angle, tone, and at least one explicit "do not" derived from the taboos list. A sample brief that works:

> "Draft a 150-word LinkedIn caption for senior B2B SaaS marketers with eight or more years of experience. Format: caption plus a three-line P.S. Angle: [your angle, one sentence]. Tone: anchored to this voice worksheet. Do not use the words 'unlock,' 'leverage,' 'game-changer,' or 'in today's fast-paced world.' Generate three variants with different opening hooks."

The brief constrains enough that the output is close to publishable on the first pass. Generic prompts produce drafts that need substantial editing. Specific prompts produce drafts that need voice review only. The specificity is the work.

After the draft arrives, run the voice pass before any other edit. Read specifically for whether this sounds like the brand. Pre-AI, editors did this implicitly. Post-AI, it has to be made explicit, because fluent AI output masks voice drift. The draft reads fine. The sentences are grammatical. The register is approximately right. The depth is missing. The voice pass is where you catch it.

For testing, generate ten variants. Pick which one ships. Never let the model pick. The selection is where voice is asserted.

Run a weekly feed-level audit. Sample five to ten pieces from the week — AI-touched and not. Read them as the audience. Ask whether the feed sounds like one brand or like several similar ones. Doshi and Hauser's homogenization effect is structural to current models. The only way to catch it is to sample the feed over time. Per-post audits miss it because per-post the output is original enough.

Update the voice worksheet quarterly. Voice evolves. The brand grew. The audience shifted. The taboos moved. The worksheet has to move with them.

---

## The Failures That Are Avoidable

Eight failure modes in content creation, each with the reason it fails.

Never let AI choose which variant publishes. Variant generation is pattern work. Variant selection is voice work. Letting the model pick erodes voice by averaging across the generated set.

Never let AI write the opening hook of a thought-leadership post. The hook is where voice is most exposed and where engagement is decided. Write the hook by hand even when you delegate the rest.

Never publish AI-drafted content under a named individual's byline without that individual's read. The byline is a contract. The named person has to read the words.

Never use AI to fabricate identity. No AI-generated bylines, no AI headshots, no AI-attributed quotes from people who did not say them. The Sports Illustrated lesson is the hard version of this. The soft version is present in any brand that lets the model write founder quotes for social posts without the founder's read.

Never delegate the angle. The model can produce twenty candidate angles. You select among them. Letting the model select is letting the model decide what the brand believes.

Never skip the weekly feed-level audit. Doshi and Hauser's convergence effect is structural and quiet. It does not show up in any single post. It shows up in the feed over time.

Never react to a cultural moment without judgment review. AI-fluent reactive content reads as opportunistic when the brand has no real stake in the moment. The judgment is whether to react at all.

Never let AI write content involving a named customer, partner, or competitor without legal and brand review. The model does not know the consent status, the relationship history, or the legal exposure. The cost of an avoidable mention is far higher than the cost of the review.

| Failure mode | Why it fails | Specific cost |
|---|---|---|
| AI picks which variant publishes | Selection is voice work; the model averages across the generated set | Voice erosion across the feed; reader cannot say why, but stops following |
| AI writes the opening hook of a thought-leadership post | The hook is where voice is most exposed and where engagement is decided | Generic-fluent first line; lost engagement; reader scrolls past |
| AI-drafted post under a named byline ships without that individual's read | The byline is a contract; the named person did not stand behind the words | Sports Illustrated-shaped reputational damage; trust collapses retroactively |
| AI used to fabricate identity (bylines, headshots, attributed quotes) | The contract with the reader is synthetic from the start | Brand-ending; the licensing or distribution arrangement may not survive |
| Angle delegated to the model | The model decides what the brand believes | Brand publishes positions it cannot defend when challenged |
| Weekly feed-level audit skipped | Doshi-Hauser convergence is structural and quiet; per-post audits miss it | Feed flattens; audience loses the property that made them follow |
| Reaction to a cultural moment without judgment review | Brand has no real stake; the post reads as opportunistic | Tone-deafness amplified by AI fluency; reactive backlash |
| AI writes about a named customer, partner, or competitor without legal and brand review | Model does not know consent, relationship history, or legal exposure | Avoidable mention; legal cost far higher than the review |

*Figure 3.6 — The eight avoidable failures: a pre-publication checklist.*

<!-- → [TABLE: The eight avoidable failures as a quick-reference table — columns: failure mode, why it fails, the specific cost — one row per failure, for use as a pre-publication checklist] -->

---

## The +1

For content creation, the +1 is voice. Specifically: voice as the accumulated record of the brand's decisions about what it cares about, what it refuses to say, and what the named humans on the team would actually publish under their names.

This is not a soft claim about authenticity. It is a structural claim about what the model has access to and what it does not. The model has access to the published corpus. The corpus contains the decisions that made it through. The decisions that did not make it through — the post that was killed, the angle that was abandoned, the phrase the founder asked to remove — those are also voice. They are the boundary conditions. The +1 is the practitioner whose head holds the boundary conditions.

What the +1 brings: the voice worksheet's actual reasoning; the angle call; the voice pass; the hook and the close; the publish/don't-publish decision; the weekly feed-level audit that catches Doshi-Hauser convergence before it becomes flattening.

In the Heinz case, the +1 brought the judgment that "AI thinks ketchup looks like Heinz" was a campaign. The combinatorial output of the model was the raw material. The human judgment that this was worth running — that it said something true about the brand's market position and could be turned into something readers would find funny rather than boastful — that judgment was not in the prompt. It was in the practitioner who knew what Heinz was trying to say.

In the Sports Illustrated case, the absence of a +1 — or the override of a +1 by someone willing to fabricate identity — was the failure. The technology was the same. The boundary was different. The cost of erasing the boundary was the brand.

---

## LLM Exercises

**Exercise 1 — Delegate/Guard Classification**
Take five pieces of content you published last month. For each one, decompose the production into individual steps (the full list: topic selection, angle, research, outline, draft, voice pass, hook, close, tags, timing, pre-pub check, publish decision). Label each step Delegate or Guard using the criteria from this chapter. Where did you treat a Guard step as Delegate? Where did you hand-write a Delegate step unnecessarily?

**Exercise 2 — Voice Extraction**
Select fifteen to twenty pieces of content your brand published that you consider on-voice. Run the voice extraction: three recurrent brand values with evidence, three communication taboos, three signature phrases or framing devices, one anti-example with a sentence on why. Then run the same extraction on fifteen pieces from a direct competitor. Where do the voice worksheets overlap? What in your worksheet is genuinely distinctive?

**Exercise 3 — Brief Specificity Test**
Write two drafting prompts for the same post: one generic (audience, format, topic only) and one fully constrained (audience, format, length, angle, tone from voice worksheet, at least one explicit "do not," three variants requested). Run both. Compare the voice pass required on each output. How many edits did the generic output require that the specific output did not?

**Exercise 4 — Feed-Level Audit**
Sample ten posts from your brand's most recent two weeks of publishing. Read them as the audience — not as the author. List any words, phrases, or sentence structures that appear in three or more posts in a way that suggests default-model phrasing rather than brand-specific phrasing. Now check whether those phrases appear in the voice worksheet's taboos list. If they do not, update the taboos list.

---

## Prompts

### Figure 3.1 — The Doshi-Hauser divergence
Build a two-line chart on a single Cartesian plane. Horizontal axis: AI assistance intensity in five discrete steps — no AI, light, moderate, heavy, total. Vertical axis: relative index 0 to 100, zero-baseline. Series A is individual writing quality, rising monotonically from approximately 60 at no AI to 85 at total. Series B is collective distinctiveness across writers, falling monotonically from approximately 80 to 45. Mark each data point with a small filled circle. Render Series A in secondary gray and Series B in brand red — red encodes the chapter's load-bearing claim. Add a single open circle at the crossing point near the moderate step. Shade the area to the right of the crossing with a low-opacity neutral fill labeled "structural homogenization zone." Right-side labels for each line. No legend. Plot region fill F5F5F5 with hairline border. Axes ink 1pt. Tick labels JetBrains Mono 11px. Deliverables: brutalist SVG and a single-file D3 v7 HTML with ResizeObserver, dark-mode CSS variables, and a tooltip per data point.

### Figure 3.5 — Decomposition of a CEO LinkedIn essay
Build a vertical workflow infographic of 13 numbered steps for drafting a 1,200-word CEO LinkedIn essay. Each step is a constant-width filled rectangle stacked top to bottom with small vertical arrow connectors between them. Color-code by role: Delegate (secondary gray) for steps 3, 4, 5, 9, 10, 11; Guard (brand red) for steps 1, 2, 6, 7, 8, 12. Step 13 is a single rectangle split into two halves — left half gray (sort comments), right half red (respond). Step 11 carries a small ochre dot in the corner indicating human approval on flags. Step labels left-aligned inside each rectangle; role label (DELEGATE or GUARD) right-aligned. To the right of each Guard step, add a short italic Garamond callout naming what fails if delegated (e.g., "voice most exposed," "the shipping decision"). Bottom tally: two tiles reading "8 DELEGATE" and "5 GUARD." No icons. Deliverables: brutalist SVG and a single-file D3 v7 HTML with ResizeObserver, dark-mode variables, and a tooltip per step describing its role and callout.
