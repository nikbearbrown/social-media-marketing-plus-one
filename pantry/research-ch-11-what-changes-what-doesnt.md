# Research Pass — Chapter 11: What Changes, What Doesn't

**Working title:** What Changes, What Doesn't — AI capability trajectory, the durable human layer
**Reader:** Working social media managers and marketing professionals already using AI
**Thesis frame:** AI handles pattern; humans handle judgment. Chapter 11 separates "currently requires a human" from "fundamentally requires a human" and gives the reader a way to forecast the boundary's movement without absolutism or panic.
**Research scope:** Capability trajectory of generative AI (LLMs, video, voice, agentic systems). The empirical record of past forecasts. Frameworks for thinking about durable human work. Calibrated forecasting practice.

---

## 1. Primary Sources

**AI capability trajectory — primary technical sources**

- **Kaplan, Jared et al. — "Scaling Laws for Neural Language Models" (OpenAI, Jan 2020, arXiv:2001.08361).** The empirical scaling laws paper. Established the loss-as-power-law relationship that drove the 2020–2024 capability buildout. Foundational. Pair with **Hoffmann et al. (DeepMind) — "Training Compute-Optimal Large Language Models" (Mar 2022, arXiv:2203.15556)** — the "Chinchilla" paper, which corrected Kaplan's data-vs-parameters tradeoff.
- **Wei, Jason et al. — "Emergent Abilities of Large Language Models" (TMLR, 2022, arXiv:2206.07682)** and the response **Schaeffer, Miranda, Koyejo — "Are Emergent Abilities of Large Language Models a Mirage?" (NeurIPS 2023, arXiv:2304.15004).** The two-paper exchange on whether capability emergence is real or an artifact of metric choice. Important for the chapter's epistemics around forecasting.
- **Bommasani, Hudson, Adeli, Altman, et al. — "On the Opportunities and Risks of Foundation Models" (Stanford CRFM, Aug 2021, arXiv:2108.07258).** The "foundation model" framing paper. Useful for naming the abstraction the reader is delegating to.
- **Anthropic — Model Card and System Card releases for Claude (each major version, 2023–present).** The system cards include capability evaluations, refusal rates, safety testing. Cite specific cards with date.
- **OpenAI — System Cards for GPT-4 (Mar 2023), GPT-4o (May 2024), o1 (Sept 2024), and subsequent.** Cite with date and version.
- **Google DeepMind — Gemini technical reports (Dec 2023, Feb 2024, and subsequent).** Cite with date.
- **METR (Model Evaluation and Threat Research) — "Measuring AI Ability to Complete Long Tasks" (2024–2025 work).** Empirical measurement of agentic task completion vs. task duration; the "tasks AI can do are doubling in length every ~7 months" finding is the most defensible quantitative trajectory claim available as of writing. Cite with date and methodology caveats.
- **Bubeck et al. — "Sparks of Artificial General Intelligence: Early experiments with GPT-4" (Microsoft Research, Apr 2023, arXiv:2303.12712).** The "sparks" paper. Useful as a primary source because it is widely cited; also useful as a cautionary tale about overinterpretation.
- **Stanford HAI — "AI Index Report" (annual, 2017–2025).** The most comprehensive aggregator of capability benchmarks, deployment data, and economic impact. Cite the most recent edition at writing.

**Specific capability area sources (video, voice, agents)**

- **Brooks, Tim et al. — "Video generation models as world simulators" (OpenAI Sora technical report, Feb 2024)**, plus subsequent Sora release notes.
- **Runway — Gen-2 and Gen-3 Alpha technical communications (2023, 2024).**
- **Google DeepMind — Veo and Veo 2 technical communications (May 2024, Dec 2024).**
- **ElevenLabs — voice cloning capability disclosures and consent policies (2023–2025).** Practitioner-relevant for paid social voiceover.
- **Anthropic — "Computer use" capability (Oct 2024)** and follow-ups; representative of agentic capability moving into general-purpose assistants.
- **OpenAI — Operator (Jan 2025) and subsequent agentic releases.**

**Forecasting methodology — primary sources**

- **Tetlock, Philip — "Expert Political Judgment: How Good Is It? How Can We Know?" (Princeton, 2005, second edition 2017).** The original empirical work on forecaster accuracy. The "hedgehog/fox" distinction is essential.
- **Tetlock, Philip and Dan Gardner — "Superforecasting: The Art and Science of Prediction" (Crown, 2015).** The popularizer book; key practical content is the Good Judgment Project methodology.
- **Mellers, Stone, Tetlock et al. — "Psychological Strategies for Winning a Geopolitical Forecasting Tournament" (Psychological Science, 2014).** Empirical demonstration that calibration training improves accuracy. Direct relevance to Chapter 11's pedagogy.
- **Armstrong, J. Scott — "Principles of Forecasting: A Handbook for Researchers and Practitioners" (Kluwer, 2001).** Reference work for the broader forecasting literature.
- **Kahneman, Daniel — "Thinking, Fast and Slow" (FSG, 2011)**, especially Chapter 22 ("Expert Intuition: When Can We Trust It?") and the chapters on planning fallacy. The Klein-Kahneman synthesis on when expert judgment is reliable is exactly the question Chapter 11 asks about AI.
- **Klein, Gary — "Sources of Power: How People Make Decisions" (MIT, 1998).** The naturalistic decision-making and Recognition-Primed Decision (RPD) literature. Klein names what tacit expert judgment *is*, which is precisely what Chapter 11 must defend as the durable human layer.

**Economic and labor-market trajectory sources**

- **Eloundou, Manning, Mishkin, Rock — "GPTs are GPTs: An Early Look at the Labor Market Impact Potential of Large Language Models" (OpenAI / Penn / OpenResearch, Mar 2023, arXiv:2303.10130).** Task-level exposure analysis; identifies marketing-adjacent roles as among the most exposed. Cite with the exposure caveat (exposure ≠ replacement).
- **Acemoglu, Daron — "The Simple Macroeconomics of AI" (May 2024 working paper, NBER w32487).** Skeptical economic forecast; useful counterweight to bullish forecasts.
- **Brynjolfsson, Li, Raymond — "Generative AI at Work" (NBER, Apr 2023, w31161, published QJE 2025).** Field study of AI deployment in customer support; the "novices benefit most" finding has implications for the durable expert layer.
- **MIT FutureTech / Acemoglu work on automation index, 2024–2025.**
- **Goldman Sachs — "The Potentially Large Effects of Artificial Intelligence on Economic Growth" (Mar 2023, Hatzius et al.).** Industry forecast; widely cited; flag as bullish institutional estimate.
- **McKinsey Global Institute — "The economic potential of generative AI" (June 2023, updated periodically).** Industry forecast; treat as one data point.

**Durable-human-work theoretical sources**

- **Polanyi, Michael — "The Tacit Dimension" (1966).** The "we know more than we can tell" formulation. The source for Autor's "Polanyi's Paradox" framing.
- **Dreyfus, Hubert — "What Computers Still Can't Do: A Critique of Artificial Reason" (MIT, 1992, revised from 1972 *What Computers Can't Do*).** Phenomenological critique of GOFAI; many specific predictions did not survive deep learning. Cite carefully: Dreyfus was right about embodiment and skill, wrong about pattern recognition's reach. The chapter can use Dreyfus *both* as a model (his durable points) and as a cautionary tale (his failed specifics).
- **Suchman, Lucy — "Plans and Situated Actions: The Problem of Human-Machine Communication" (Cambridge, 1987).** The situated cognition argument. Useful for the chapter's account of why context-bound judgment resists automation.
- **Hubert Dreyfus and Stuart Dreyfus — "Mind Over Machine" (Free Press, 1986).** The skill acquisition model (novice → advanced beginner → competent → proficient → expert). The progression from rule-following to intuitive judgment is structurally what the chapter argues AI does well early (rules) and humans do at the top (expert intuition).
- **Crawford, Kate — "Atlas of AI" (Yale, 2021).** Useful as a corrective to the "AI as disembodied intelligence" frame; reminds readers that AI capability is grounded in labor, energy, data — all of which are subject to constraints that bound the trajectory.
- **Suleyman, Mustafa — "The Coming Wave" (Crown, 2023).** Industry-insider forecast. Treat as a primary data point on how AI lab leadership thinks, not as a neutral forecast.

---

## 2. State of the Field (as of May 2026)

**Three roughly distinct forecasting camps, none of which has been empirically validated.**

- **The continuation-scaling camp** holds that capability gains driven by compute, data, and algorithmic progress will continue at roughly the rate of 2020–2024, with general-purpose agents becoming reliable for most knowledge work in 3–7 years. Representative voices: Dario Amodei ("Machines of Loving Grace," Oct 2024), Sam Altman (various), the METR long-task trajectory result.
- **The plateau camp** holds that returns to scale have already started diminishing, that the most important post-training gains (reasoning, agentic reliability) face problems that pre-training scale alone does not solve, and that the next jump requires architectural or paradigm change. Representative voices: Yann LeCun (consistent on this), Gary Marcus (consistent on this in different terms), Subbarao Kambhampati on planning limitations. Empirical anchor: the contested 2024–2025 reports of slowing returns from GPT-4o → GPT-4.5 → GPT-5 generations.
- **The capability-overhang camp** holds that current models are already more capable than deployed systems suggest, that progress in real-world tasks is bottlenecked on scaffolding (agents, tools, memory) rather than base-model capability, and that the next two years will see large gains from better deployment of roughly the current generation. Representative voices: agentic-systems researchers; many startup founders.

The chapter's stance — and the AI+1 stance — is that the *direction* of capability movement is more forecastable than the *rate*, that the *types* of work that remain human are more forecastable than the *timeline*, and that practitioners should be calibrated rather than committed.

**The "current generation" capability snapshot relevant to social marketing (as of writing).**

- **Text drafting**: at or near professional baseline for most pattern-shaped tasks (captions, paid copy variants, summary, translation, transcription). Currently requires human for voice fidelity, brand stance, factual accuracy in claims, anything attribution-sensitive.
- **Image generation**: production-grade for stock-replacement use, social-tile use, mood-board use. Currently requires human for talent representation (deepfake / likeness consent), brand-specific visual identity systems, photojournalistic claims.
- **Video generation**: rapidly moving. As of writing, Sora, Veo, Runway Gen-3, Kling, and others produce shareable short-form video for many use cases. Production-grade for B-roll, atmosphere, and concept; currently requires human for narrative continuity, talent fidelity, anything with a person speaking on-camera.
- **Voice synthesis**: production-grade for synthetic narration; near-perfect cloning of any voice with seconds of reference audio. Currently requires human consent for any cloning use; reputational and legal Guard for cloning a real person.
- **Agents (multi-step, tool-using)**: rapidly improving; reliability is the constraint. METR's long-task trajectory suggests the time-horizon AI can autonomously complete is doubling on a ~7-month rhythm but starting from a low base. Currently requires human supervision for any consequential action — posting, payment, sending, replying to identified individuals.
- **Reasoning / chain-of-thought / "thinking" models**: meaningful gains on benchmarked reasoning; partial transfer to messy real-world judgment. Currently requires human for novel ethical situations, brand crises, anything with no precedent in training data.

**The "what doesn't change" thesis is being articulated by adjacent fields, not by the AI-marketing trade press.**

- Education research on the lasting value of human teaching (the August Bridge AI tutor study contrasted with the consistent finding that relationship-anchored teaching predicts long-term outcomes).
- Healthcare research on the AI-augmented clinician (the Eric Topol thesis that AI improves clinical work but does not replace the doctor-patient relationship layer).
- Journalism (Reuters Institute Digital News Reports; Tow Center work on AI in newsrooms) finds that AI handles aggregation, summarization, and translation but trust attribution still flows through named human reporters.
- Law (the Joshua Browder / DoNotPay collapse; Stanford and Vanderbilt empirical studies on hallucination in legal LLMs) suggests legal judgment under accountability is durably human.

The chapter can borrow the "what doesn't change" frame from these adjacent fields and translate it into social marketing.

**The framing-fight in the trade press is mostly performative, not analytical.** Most "AI will replace marketers" / "AI will never replace marketers" content is positioning content for the writer's brand or product. Chapter 11 should explicitly position itself as forecasting-as-practice (Tetlock-grade) rather than forecasting-as-rhetoric.

**Two specific 2024–2026 developments practitioners are tracking:**
- **Synthetic influencers.** Aitana López, Lil Miquela, Imma. Brand spend has continued through 2024–2026 despite predictions of collapse. The trajectory question is whether AI personas displace human creators on cost / control / scale grounds, or whether human creators retain trust attribution. Open question.
- **Watermarking and provenance.** C2PA / Content Credentials adoption (Adobe, Meta, Microsoft, OpenAI), SynthID (Google DeepMind), platform-level labels. The technical infrastructure for provenance is being built; the question is whether audiences will use it. Open question.

---

## 3. Application Domain — Social Media Marketing

How the trajectory and durability questions land in the practitioner's day.

**Tasks where the AI capability frontier is moving fastest right now (Delegate List candidates expanding):**

- **Short-form video production from a creative brief.** Two years ago this required a videographer, editor, and post-production cycle. Now a small team can produce platform-native short-form video from a brief in hours. The remaining human inputs: brief writing, talent direction, brand voice editing, distribution judgment.
- **Audience-segmented creative variation.** Once a brand brief and a core creative are set, AI can produce dozens of variants for paid social testing. The human input becomes the brief, the test design, and the read of results.
- **Comment routing and triage.** Mature platform tooling plus LLM classification can sort incoming comments by sentiment, urgency, intent. Human input moves to responses for the flagged set.
- **Analytics narrative.** AI can write the recap deck from the dashboard; the strategic implication and the recommendation for next quarter is the human input.

**Tasks where capability is currently improving but reliability is the constraint:**

- **Autonomous posting agents.** Technically feasible; deployed selectively in low-stakes contexts. Reliability constraint makes this Guard List for any consequential brand. The chapter should be specific: agentic posting is plausible for some accounts within the chapter's shelf life; the *judgment* about whether to deploy an agent on your account is itself a durable human call.
- **DM and customer-service response.** Mature in some categories (e-commerce returns), risky in others (anything reputational, anything emotional). Capability is improving; the boundary between "delegate with monitoring" and "human-required" is one the reader will have to redraw every six months.
- **Real-time crisis response.** Capability for *drafting* response options is at production grade; capability for *deciding* which option to send remains squarely human.

**Tasks where the chapter should argue the human layer is durable, not just current:**

- **Establishing or evolving a brand voice from scratch.** This requires synthesizing intent, market, culture, and audience in a way that does not exist in the training data because the brand itself does not yet exist. AI can produce plausible candidates; the call is human and the call carries the brand's identity forward.
- **High-trust relationship work.** Influencer relationships, partnership decisions, journalist outreach for owned-channel amplification, internal alignment with sales and product. The relationship is the asset; the relationship is between persons.
- **Crisis judgment under uncertainty.** Not response drafting — the call to engage, the call to apologize, the call to wait. These require accountability, which requires a human in the loop.
- **Boundary calls in ambiguous situations.** Whether a post is too political, too edgy, too on-the-nose, too off-brand. Pattern matching gives a plausibility distribution; the call requires a person who will be answerable for it.
- **Audience context that is not legible to the model.** Local events, recent industry conversations, what the founder said on a podcast yesterday that the audience is still reacting to. The model has a training cutoff and a context window; the practitioner has the lived stream.

**The durable human layer in social marketing, stated as a thesis:**

The work that remains human is the work that requires *accountability*, *relationship*, or *context the model cannot acquire*. Accountability because someone must be answerable. Relationship because trust is between persons. Context because the operationally relevant facts are often not in the training data or the prompt. These three are not "currently human" — they are structurally human. They are the durable layer.

**Forecasting framing for the chapter:**

- Forecast at the level of *task families*, not roles. "Will the social media manager be replaced?" is the wrong question. "Will paid social copy variation be 95% AI by 2028?" is a tractable question.
- Use probability ranges, not point estimates. Tetlock's research is unambiguous: "70% likely by 2028" is a more honest claim than "by 2028 this will happen."
- Decompose. If a task has five steps, the forecast horizon for each step may differ.
- Anchor on past wrong forecasts. Five years ago most observers said image generation would not produce photorealistic faces by mid-decade; it did. Most observers said long-form video would lag; it did, but is closing. Most observers said *judgment* would automate; it has not. The track record is informative.

**Anti-forecasting moves the chapter should avoid:**

- "AI will never X." This claim is almost always wrong on engineering grounds (you have to be very confident about a mathematical limit) and is rhetorically weak.
- "AI will replace all X by Y." This claim has a documented track record of being wrong about timelines and overstated about scope.
- "It's impossible to predict." Tetlock's research disconfirms this. Calibrated forecasting is teachable. Some forecasts are more defensible than others. Refusing to forecast is a forecast.

---

## 4. Thesis Connection — AI handles pattern; humans handle judgment

How Chapter 11's content reinforces and operationalizes the core thesis.

**Chapter 11 makes the thesis *time-aware*.** Chapters 1–10 state the thesis as a present-tense fact. Chapter 11 forces the thesis to defend itself against capability change. The defense has three moves:

1. **Concede the moving frontier.** Capability gains are real. Some tasks on today's Guard List will move to tomorrow's Delegate List. This concession is necessary credibility; without it the thesis reads as wishful thinking.
2. **Distinguish "currently requires" from "structurally requires."** Pattern-shaped work is what AI does; the boundary moves outward as capability grows. Judgment-shaped work — work that requires accountability, relationship, or local context — does not become pattern-shaped because capability grows. The boundary may move within pattern-shaped work; it does not collapse the distinction.
3. **Locate the durable layer.** The chapter names the human layer that survives capability gains: accountability, relationship, contextual judgment under uncertainty. These survive because their human-ness is constitutive, not contingent — a relationship between AI and a customer is a different object than a relationship between two persons, and brands that depend on the second cannot substitute the first.

**The thesis predicts a specific empirical pattern, which the chapter should name:** as capability grows, the *quantity* of human work in social marketing decreases, the *judgment density* of the remaining human work increases, and the *consequences* of judgment errors get amplified because each judgment now governs more downstream automated output. This is the inverse of the trade-press story (humans are obsolete); it is also more honest about what is changing.

**The +1 in Chapter 11 is the practitioner becoming a calibrated forecaster about their own work.** Earlier chapters teach the practitioner to make the delegation call for current capability; Chapter 11 teaches them to make the call *prospectively* — to design today's Delegate/Guard map with awareness of how the boundary will move, and to schedule the revisits.

**One risk to manage:** the chapter must not slide into either utopia or doom. Both are forecasting-as-rhetoric. The chapter's authority comes from calibrated uncertainty: some things will change a lot, some won't, and we can do better than guessing.

**The thesis also predicts what the chapter argues is the durable human layer's economic value.** As pattern-shaped work commoditizes, judgment-shaped work appreciates. The practitioner who can articulate and defend the judgment surface in their domain is the practitioner whose role compounds in value. This is a forecast the chapter is willing to make explicitly, with the caveat that it is conditional on the practitioner continuing to develop the judgment side.

---

## 5. Wayback Candidates — Historical Figures

Three figures whose work models calibrated forecasting and the recognition of durable human layers. Per the brief, candidates come from *adjacent* forecasting fields, not from AI/tech itself.

**Candidate A — Wassily Leontief (1905–1999), economist.**
Nobel laureate (1973) for input-output analysis. The lesser-told and Chapter 11–relevant work is his late-career writing on automation. In a 1983 paper ("National Perspective: The Definition of Problems and Opportunities") and a 1986 *Scientific American* piece with Faye Duchin, Leontief argued that the analogy between human labor and the horse was operative: just as horses were not "retrained" out of obsolescence by mechanization (their numbers collapsed) so too could human labor face displacement in sectors where economic forces favored capital substitution. *Why he fits Chapter 11:* Leontief is the under-cited forecaster of automation displacement, and his forecast turned out to be partly right (manufacturing employment in advanced economies did contract sharply) and partly wrong (aggregate employment did not collapse because new tasks emerged). The chapter can use Leontief as a model for forecasting that was calibrated about *direction* but uncertain about *what would offset*. Born in St. Petersburg, fled the Soviet Union for Berlin and then the US — biography itself a useful reminder that the most rigorous forecasters often come from elsewhere.

**Candidate B — Donella Meadows (1941–2001), systems thinker and lead author of *The Limits to Growth*.**
*Limits to Growth* (1972) is famous for being misread as a doomer prediction. The actual book offered scenario modeling — what happens under continued exponential growth in resource extraction, population, and pollution if no policy or technology change occurs. Meadows was explicit that the model showed leverage points, not destinies. Her later essay "Leverage Points: Places to Intervene in a System" (1999) is the masterclass on where to push when forecasting feels paralyzing. *Why she fits Chapter 11:* the chapter is teaching practitioners to think about capability trajectory without absolutism. Meadows modeled exactly this practice — taking trajectories seriously without claiming destiny, identifying durable structures and leverage points, treating "what does not change" as the load-bearing question. She also offers a representation choice: a woman whose forecasting work was systematically misread and undercredited in the trade press of her era, which is itself a story about how forecasts about complex systems get received.

**Candidate C — Atul Gawande (b. 1965), surgeon and writer — used here for the durable-human-layer argument, not the more famous checklist work.**
Gawande's *Complications* (2002) and *Better* (2007) build a sustained argument about which parts of medical practice survive process improvement and which parts are irreducibly judgment-bound. His *New Yorker* piece "The Itch" (2008) and his later writing on dying ("Letting Go," 2010; *Being Mortal*, 2014) make the same move Chapter 11 needs to make: name what can be standardized, defend what cannot, and refuse the false binary between "all judgment" and "all protocol." *Why he fits Chapter 11:* he is the contemporary master of the move "this part is patternable, this part is irreducibly human, here is how I tell the difference, here is why the difference matters." That is the chapter's argument structure. Gawande is not particularly lesser-known, but his less-cited work on the durability of the doctor-patient relationship under technological pressure is exactly the argument structure Chapter 11 borrows. (If a lesser-known alternative is preferred: **Sherry Turkle** for *Alone Together* and *Reclaiming Conversation* — the most rigorous chronicler of what relational work technology degrades and what it does not.)

**(Alternate, if a fourth is wanted:) Herman Kahn (1922–1983).** RAND futurist, author of *The Year 2000* (1967). Useful as a cautionary tale: many of his specific predictions failed, but his *method* — scenario planning rather than point forecasts — is exactly the methodology Chapter 11 endorses.

---

## 6. Pedagogy — How to Teach This

**Center the chapter on calibrated forecasting as a *practice* the reader will do for the rest of their career.** Chapter 10 taught the practitioner to build the map; Chapter 11 teaches them to maintain it under capability change. The chapter's central skill is forecasting-with-humility.

**Start with the empirical track record.** Show the reader, on a single page if possible, what people said five years ago about image generation, video, agents, "AGI by [year]" — and what actually happened. This calibrates the reader about how hard the forecasting problem is before any abstract framework lands. Source: AI Index trend lines plus selected quote/prediction archive.

**Then introduce the two-question frame the chapter is built on.**
- *What changes?* The set of tasks AI does well will expand. Be specific about which task families on the Delegate List border are most likely to expand next (paid copy variation; short-form video; audience segmentation; transcription; analytics narration; agentic posting in low-stakes contexts).
- *What doesn't?* The accountability layer, the relationship layer, the contextual judgment layer. Be specific about why each is structurally human, not contingently human.

**Teach the practitioner a forecasting protocol they can run on their own Delegate/Guard map quarterly.**

1. For each Guard List item, ask: is there a current capability gap, or a structural reason a human is required?
2. For each capability gap, estimate (with a probability range) when it might close at production-grade reliability.
3. For each structural reason, name the durable feature (accountability / relationship / context).
4. Move items between lists only when the capability test passes *and* the structural test does not apply.
5. Document the call. Re-audit in 90 days.

**Use Tetlock's superforecaster habits as a teachable skill.** Probabilistic thinking, decomposition, calibration training, anchor-and-update, willingness to be wrong. These are real, learnable, and underused in marketing. The chapter can teach them in marketing language without diluting them.

**Address the practitioner's emotional charge directly.** This is the chapter where the reader has the most personal anxiety (will my job exist in three years?). Don't pretend the question isn't there. Don't promise it'll be fine. The honest answer — pattern-shaped work commoditizes, judgment-shaped work appreciates, the practitioner who develops judgment becomes more valuable — is also the answer that earns trust. Underline that this is a forecast, not a guarantee.

**Use scenarios, not predictions.** Walk the reader through three scenarios for social marketing roles in 2028: continuation-scaling, plateau, capability-overhang. In each, what does the practitioner's job look like? In each, what is the durable human layer? The exercise teaches scenario thinking and surfaces the invariants — the things that hold across all three.

**End-of-chapter outputs:**
1. A forecast register: 5–10 items from the reader's Delegate/Guard map with probability-ranged forecasts about when (if) they move, to be revisited in 90 days.
2. A "what I'm watching" list: 3–5 capability developments the reader will track over the next quarter.
3. A "durable layer" statement for their role: one paragraph naming what part of their work is structurally human and why.

**Make the chapter shorter than it wants to be.** The temptation will be to survey the AI landscape; the chapter will age poorly if it does. Center on the *method* and use specific capabilities as illustrative examples with date stamps.

---

## 7. Representation

**Forecasters and traditions to draw from explicitly:** Tetlock (Good Judgment), Meadows (systems), Klein (naturalistic decision-making), Kahneman (heuristics and biases), Leontief (input-output, displacement), Gawande / Turkle (durable human layers). These cross gender, generation, and field — deliberately.

**Voices on AI capability the chapter should include without endorsement:** the continuation-scaling case (Amodei, Altman, the labs), the plateau case (LeCun, Marcus, Kambhampati), the labor-economics case (Acemoglu, Brynjolfsson, Autor). Quote each in their own terms. Do not strawman.

**Industries used as illustrative durability arguments:** medicine (Gawande, Topol), law (the documented LLM failure cases), journalism (Tow / Reuters Institute), education (the relationship-anchored teaching literature). Each is well-documented; each is adjacent to marketing enough to be analogically useful without claiming expertise the chapter does not have.

**Geographic frame:** the AI capability story is mostly US/UK/EU/China lab-driven, but the *labor impact* is global. The chapter should at minimum acknowledge that the trajectory question lands differently in markets with different regulatory regimes (EU AI Act; China's generative AI rules from August 2023) and different labor structures.

**Generational frame:** the reader spans roughly Gen X through Gen Z social marketers. The chapter should not assume the reader has lived through prior automation cycles (some have; some haven't) but should make the prior cycles legible — there have been other moments when "this will change everything by [year]" was the consensus, and the reader can learn from the track record.

**Skew of the chapter's own forecasts:** the chapter takes a calibrated, slightly pro-durability stance. It does not predict that human social marketers go to zero, and it should be honest that this is a position, not a neutral truth.

---

## 8. Open Questions

1. **How much capability detail to include?** The temptation is to survey current models (GPT-5, Claude, Gemini, etc.) in detail. Risk: ages in months. Recommend: name the categories (large reasoning models, video gen, voice synthesis, agentic systems) with one or two specific examples per category, date-stamped, framed as "as of writing."
2. **Does the chapter make a specific forecast about social marketer headcount in 2028 / 2030?** Recommend: no. Make forecasts at the task-family level and let the reader aggregate. Headcount forecasts have low information value and high arrogance cost.
3. **How to handle the "AGI" framing without being captured by it?** The trade press treats AGI / "drop-in remote worker" as a near-term question. Recommend: name the term once, frame as a contested concept, refuse the binary, route to the task-family decomposition.
4. **Does the chapter address AI labor implications beyond marketing?** Recommend: only lightly, via the adjacent-field examples. The reader is a marketer; respect that scope.
5. **How prescriptive about the quarterly re-audit?** Recommend: as prescriptive as Chapter 10. Worksheet, time-boxed, copy-paste prompts. Otherwise the practice doesn't survive contact with a busy quarter.
6. **Is "structurally human" a defensible claim?** The chapter is making a strong claim that some work is irreducibly human. The defense rests on three pillars (accountability, relationship, context). The chapter should anticipate the objection — "but couldn't AI eventually do those too?" — and answer: the question is not whether an AI system could *behave like* accountability, but whether brands and audiences will *attribute* accountability to it. Attribution is a social fact; social facts about AI accountability are evolving slowly even where capability moves fast.
7. **Does the chapter take a position on the labor-displacement question?** Recommend: yes — pattern-shaped work in marketing will compress; the displacement risk is real for practitioners who cannot articulate their judgment surface; the durable layer is the path forward. Frame as a calibrated forecast, not a prophecy.
8. **How to handle synthetic influencers and AI personas as a topic?** They are a live test of the durability thesis. Recommend: one section, treated as an open empirical question, citing the data both ways (Aitana López and Lil Miquela campaigns succeeding; the absence of broad displacement of human creators by AI personas).
9. **Where does the "AI as colleague" framing fit?** Microsoft, Salesforce, Anthropic, OpenAI have all promoted some version. The chapter should engage briefly — name the framing, note it conflates pattern-shaped task delegation (defensible) with judgment-shaped collaboration (not yet defensible), route back to the framework.

---

## 9. Sourcing Notes

**Aging risk by source class (high to low):**
- Specific model versions and benchmarks (GPT-N, Claude N, Gemini N): very high. Cite with date and model version; use as illustration of trajectory, not anchor of argument.
- Specific capability claims tied to release timing (Sora released X, computer use launched Y): high. Same treatment.
- AI Index annual report figures: medium. Use the most recent at writing; flag year.
- Scaling-law papers, Polanyi/Dreyfus/Klein/Polanyi/Suchman, Tetlock methodology, Leontief, Meadows: very low. These are the chapter's spine.
- Forecaster identity and stance (Amodei pro-continuation, LeCun skeptic, Acemoglu skeptic on macro): low — these positions are stable; cite specific essays / talks for the most current articulations.

**Verification rhythm:**
- Capability claims: verify against vendor system cards within 30 days of submission.
- "Currently requires human" claims: re-audit at copyedit and at print proof.
- Cited forecast statements: link to original (talk transcript, paper, blog post) with date.
- Quoted empirical numbers (METR doubling time, exposure-analysis percentages): cite the paper, not the press summary.

**Citation hygiene specific to forecasting claims:**
- Every forecast in the chapter should carry a probability range, a horizon, and a what-would-falsify-this clause. This is the methodological discipline the chapter is teaching. The chapter must model it.
- Every "this is structurally human" claim should be defended against the obvious AI-eventual-capability objection. The defense should distinguish *capability* from *attribution*.

**A non-source: industry survey claims that "X% of marketers will be replaced by Y."** These are mostly vendor-funded with leading methodology. Treat as data on what people are saying, not as data on what will happen. If cited, cite explicitly with methodology caveat.

**Two specific 2025–2026 developments to track during drafting:**
- EU AI Act phased implementation (especially Article 50 transparency obligations for AI-generated content, and the General Purpose AI obligations under the August 2025 deadlines).
- Any major lab's published deprecation of an earlier model's capability claim — these are useful evidence that capability descriptions age fast and should be cited with humility.

**The chapter's own forecasting commitments — kept short and falsifiable so the chapter ages well:**
- The frontier of AI capability in social marketing pattern-shaped work will continue to expand. (Easy to confirm; safe.)
- The judgment, accountability, and relationship layer in trust-dependent brand work will not collapse on the chapter's three-year horizon. (Falsifiable; defended in chapter.)
- The practitioner who articulates and develops their judgment surface will be more economically valuable in three years than the practitioner who does not. (Falsifiable; defended in chapter; depends on assumption that brands continue to attribute trust through persons.)

If any of those three forecasts gets falsified, the chapter (and the book's thesis) should be revised. That falsifiability is the chapter's epistemic honesty.
