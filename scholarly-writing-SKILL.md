---
name: scholarly-writing
description: Authors scholarly manuscripts end to end — plan, extract, synthesise, theorise, draft, revise, critique, respond to reviewers, QA. Use for journal papers, theses, and systematic reviews.
---

# Scholarly writing

## What this skill is for

This skill supports authoring a scholarly contribution end to end: framing the question, building the argument and theory, reading, extracting from, and synthesising the literature, writing and tightening the manuscript, stress-testing it, responding to reviewers, and certifying it for submission. Prose quality matters, but it is downstream of the harder work — a clear contribution, a sound argument, an honestly evidenced claim. Treat the writing as the surface of a structure that must hold.

Two commitments run through every mode and are never traded away. First, **integrity of evidence**: no fabricated source, finding, quotation, DOI, page, or statistic; verified attributions and reported values only, everything else flagged. Second, **construct integrity**: one defined construct keeps one label throughout. A by-product of working this way — specific, evidenced, terminologically consistent, free of puffery — is that the work does not read as machine-generated. That is a consequence to rely on, not a goal to chase: automated detectors are unreliable and the real audience is an editor and a referee, so optimise for them.

## Contents

1. Operating modes (the spine — pick one, then chain as needed)
2. Argument and contribution (shared craft for PLAN, THEORIZE, DRAFT)
3. Evidence integrity: citations and statistics (load-bearing, all modes)
4. Terminology lock (all modes)
5. Writing register — avoidance rules (any mode that produces prose)
5A. Scholar-voice construction — positive rules (any mode that produces prose)
6. Anti-pattern ruleset (any mode that produces prose)
7. Structure templates
8. Quality-assurance audit (the QA mode; surface portion runs after every generative mode)
9. Output conventions
10. Worked examples

---

## 1. Operating modes

Identify the dominant mode from the user's cue, state which mode you are using in one line, and move through adjacent modes as the task requires. Modes chain naturally — a single request may run PLAN → ANALYZE → SYNTHESIZE → SYNTHESIS BUILD → THEORIZE → DRAFT → QA, or CRITIQUE → REVISE.

| User cue | Mode |
|---|---|
| "frame this paper", "where does this fit", "what's the contribution", outline / skeleton | **PLAN** |
| "extract from these papers", "what's in this corpus", "pull the constructs / definitions / methods / findings / gaps", read and code the literature | **ANALYZE** |
| "organise the extracted knowledge", "themes / consensus / contradictions / boundary conditions / gaps", what the field collectively establishes | **SYNTHESIZE** |
| "build the framework / process model / typology / taxonomy / research agenda", construct the contribution from the synthesis | **SYNTHESIS BUILD** |
| "develop the hypotheses", "is this mechanism sound", construct definitions, model logic | **THEORIZE** |
| "write the [section]", produce new prose from notes / a model / results | **DRAFT** |
| "tighten this", "make this not sound like AI", clean an existing draft | **REVISE** |
| "what would a reviewer attack", "critique this", find the weak points | **CRITIQUE** |
| "respond to reviewers", "draft the response letter" | **RESPOND** |
| "is this ready", "check before submission", final pass | **QA** |

### PLAN — fix the contribution and the architecture before writing

Pin the contribution in one sentence: *this paper shows that X, which matters because Y.* If that sentence is vague, the paper is not ready to draft; surface the vagueness rather than writing around it. Then identify the target journal and assess fit (scope, method norms, the kind of contribution it rewards); default to Q1 marketing/management when none is named. Formulate the research question and position it against a real gap, puzzle, or tension — not a "no one has studied X" filler gap, but a reason the answer is non-obvious and consequential. Classify the contribution type (below). Produce a section skeleton stating what each section must establish and what evidence each claim will need.
Output: a plan or annotated skeleton, not prose.

### ANALYZE — read the corpus and extract structured knowledge

This is the research-reading and knowledge-extraction mode. Read the literature corpus (or other research inputs — reports, primary studies, dataset documentation) and pull out, per source, the structured knowledge a contribution will later be built from: the theories and frameworks invoked, the constructs and their definitions, the methods, design, and sample, the findings, the limitations the authors acknowledge, the context (sector, geography, sample type, period), and the future-research directions stated. Capture what each source actually claims, attribute precisely (§3), do not infer a finding a source does not report, and flag any uncertain or interpolated extraction. The natural artifact is a structured extraction grid keyed by source — source × theory × constructs × definitions × method × findings × limitations × context × future research — so the columns can be reasoned across in SYNTHESIZE. For a systematic review, assemble the corpus first (protocol, databases, inclusion/exclusion criteria, PRISMA-style screening counts), then extract from the retained set.
Statistical or qualitative *data* analysis — estimating a model and interpreting coefficients, coding interview or critical-incident data — is a special case performed within ANALYZE when the user asks for it, under the same evidence-integrity discipline (§3): map each test to the hypothesis it bears on, interpret with restraint, separate significance from effect size and substantive importance, and report only values actually produced. It is not the default reading of this mode.
Output: a structured knowledge base (or extraction matrix) that serves as the input for SYNTHESIZE; when data analysis is requested as a special case, an analysis plan or interpretation.

### SYNTHESIZE — organise the extracted knowledge across sources

Take the knowledge ANALYZE extracted and organise it across the corpus — into themes, recurring mechanisms, points of consensus, contradictions, boundary conditions, and research gaps. Reason down the columns of the extraction rather than paper by paper: where the body of work agrees, where it conflicts, under what conditions findings hold or reverse, and what is absent. The deliverable is the organised landscape and, stated explicitly, the gap or tension a contribution could address. Attribute precisely throughout (§3); "entering the conversation" means naming who established what and where the field diverges.
Input: the structured knowledge extracted during ANALYZE.
Output: organised themes, mechanisms, consensus, contradictions, boundary conditions, and gaps.

### SYNTHESIS BUILD — construct the intellectual contribution from the synthesis

This mode generates the contribution; it does not organise the literature (that is SYNTHESIZE). From the organised synthesis, construct the new intellectual structure: a conceptual framework, a process model, a typology, a taxonomy, an integrative framework, or a research agenda. The construction must be generative — it must do work the source studies do not do individually. Derive its dimensions or stages from the synthesised evidence rather than imposing them; show why the cases sort into the categories or sequence you propose; ground every element in verified sources or a flagged candidate (§3); and use the locked construct labels (§4) so the contribution and the prose name the same things. State plainly what the contribution explains and what falls outside it.
Input: the synthesised themes, mechanisms, contradictions, and gaps produced during SYNTHESIZE.
Output: a labelled contribution (framework, model, typology, taxonomy, or agenda) plus the prose that derives and defends it.
(Illustrative shape: a process-based review might build a cognitive→affective→behavioural sequence and sort the corpus into enabling, inertial, and deterioration configurations, each defined by where in the sequence the experience breaks down.)

### THEORIZE — build constructs and hypotheses by explicit logic

Define each construct precisely and once; hold the definition stable and ensure any proposed measure matches it. Build each proposition or hypothesis as a chain — premise → mechanism → predicted relationship — and state the **warrant**: the reason the mechanism produces that relationship. A hypothesis without a stated mechanism is an assertion, not theory. Specify mediation as the mechanism (why A affects C *through* B) and moderation as the boundary condition (when the effect strengthens or reverses), each with directional logic. Check nomological consistency: every hypothesis must be entailed by the theory and mutually consistent with the others. Resist construct proliferation (do not invent a new label for an existing idea) and tautology (the predictor must not be the outcome restated).
Output: constructs with definitions and hypotheses each carrying an explicit warrant.

### DRAFT — produce prose from a plan, model, or results

Build the argument first, then write to it; never pad to a length. Apply the register (§5), anti-patterns (§6), evidence integrity (§3), and terminology lock (§4) as you write, not afterward. Section logic: the introduction funnels phenomenon → gap → question/contribution → roadmap; the theory section presents warranted hypotheses; methods are reproducible with sourced measures; results report values with interpretive restraint; the discussion moves interpretation → theoretical contribution → implications → specific limitations → future research.
Output: manuscript prose, directly written.

### REVISE — tighten register and integrity without changing the argument

Rewrite to the register (§5) and remove the tells (§6) while preserving the user's claims, findings, constructs, and argument exactly. Cut empty sentences rather than rewording them. Keep the locked terminology (§4) intact. When useful, close with a short plain list of what changed and why ("removed three significance-inflation sentences; restored copulas; fixed one over-attributed claim") — not a marketing recap.
Output: tightened prose, optionally a change list.

### CRITIQUE — referee the user's own draft, honestly

Adopt an exacting but constructive reviewer stance and surface the *strongest* objections, not the easiest. Separate **fatal flaws** (no real contribution; broken identification or causal logic; invalid or proliferated constructs; claims unsupported by the evidence; wrong journal) from **fixable flaws** (framing, exposition, missing robustness check, citation gaps, structure). Prioritise. Do not flatter or soften to be agreeable — a critique that overstates the work's strength is useless to the author. Where a flaw is fatal, say so plainly and explain why.
Output: a prioritised critique, fatal vs fixable, with the reasoning for each.

### RESPOND — write a point-by-point reviewer response

For each comment: restate it briefly, classify the response (Addressed / Partially addressed / Clarification / Reasoned disagreement), and give either the specific change and its location (section/page) or a courteous, evidence-based justification for not changing. Tone is gracious and specific, never obsequious or defensive; thank substantively where a comment improved the paper. Integrity binds here especially: never claim a revision that was not made, never fabricate new results to satisfy a request, and if a request is infeasible or misguided, say so with reasons. A defensible theoretical position may be maintained — politely and with warrant — rather than conceded.
Output: a brief cover letter plus a comment → response → location table.

### QA — certify the manuscript before submission

Run the full audit in §8. This is the mode for "is it ready."

---

## 2. Argument and contribution (shared craft)

PLAN, THEORIZE, and DRAFT all rest on the same moves; this section is referenced rather than repeated.

**The core move:** gap → claim → warrant. Establish what is unsettled or puzzling, state your claim about it, and give the reason the claim should be believed. Every analytical paragraph should be reconstructable into that shape.

**Contribution types** (name yours; it disciplines positioning and journal fit):

| Type | The contribution is… |
|---|---|
| New construct | a concept the field lacked a name for |
| New mechanism | *why* an established relationship holds (mediation) |
| Boundary condition | *when* an effect holds, strengthens, or reverses (moderation) |
| Context extension | a known relationship tested where theory predicts it may differ |
| Integration | reconciling or unifying conflicting prior findings/theories |
| Measurement | a validated way to capture a construct better |

**Warrant discipline:** an unwarranted claim is the most common substantive weakness. For each non-trivial claim, ask what licenses it — a cited result, your own data, or a stated mechanism — and supply it. If nothing licenses it, the claim is opinion; cut it or flag it (§3).

**Argument progression:** the introduction's promise must equal the discussion's delivery; the roadmap must match the section order; each section must move the argument forward rather than restate the last. Recap that adds nothing is padding.

---

## 3. Evidence integrity: citations and statistics (load-bearing, all modes)

Two states exist for any external claim and must be visibly distinct in any output:

- **VERIFIED** — supplied by the user, present in their bibliography or data, or independently checkable. Only verified sources may carry a specific attributed claim, year, venue, volume/issue, page, DOI, or quotation. Confirm year/title/venue against the record even for canonical-seeming sources rather than recalling them.
- **CANDIDATE** — a flag that a citation is needed, or that a particular work *might* support the point, rendered as a placeholder the user must confirm, never as an asserted finding:
  `[CANDIDATE: integration-quality → loyalty link; locate a primary JRCS/JM source; confirm before submission]`

Hard rules, in every mode including DRAFT, ANALYZE, and RESPOND:

- Never invent a DOI, volume, issue, page, or quotation. If you do not have it, omit it.
- Never write "Author (Year) found X" unless verified. For unverified support, state the claim and attach a CANDIDATE flag; do not manufacture an author or finding.
- Implied source count must match actual citations: no "several studies show" behind one reference, no "scholars argue" behind none.
- **Reported statistics follow the same rule:** report only coefficients, p-values, fit indices, sample sizes, and intervals that were actually produced; never invent them; mark any illustrative figure as a placeholder. (Applied in ANALYZE.)
- In RESPOND mode, never cite a change, analysis, or result that was not actually produced.
- Match the target journal's citation style (APA 7 for JAMS; Elsevier/Harvard author–date for JRCS; otherwise as specified). Style is cosmetic; the verified/candidate distinction is not.

---

## 4. Terminology lock (all modes)

Generative models thesaurus-swap key terms to avoid repetition; rigorous work does the opposite, holding construct labels identical so the reader tracks one variable rather than three near-synonyms. This is construct hygiene first and a de-AI move second.

- Identify the user's locked construct names and any banned phrasings at the start of the task, and use them verbatim throughout every mode.
- Never substitute a synonym for a defined construct (do not alternate "channel integration quality" / "omnichannel cohesion" / "cross-channel synergy" for one construct).
- Honour any banned-phrase list exactly, including in paraphrase.

---

## 5. Writing register (any mode that produces prose)

Empirical social-science prose is a low-involvement, nominal register, not ornate prose. Aim for:

- **Calibrated hedging and boosting.** Match certainty to evidence: state what the data support plainly, hedge inference appropriately ("this suggests", "consistent with"), and avoid both flat confident cheerfulness and filler hedging ("it may perhaps be somewhat possible"). Over-hedging and over-claiming are both tells.
- **Compressed noun phrases for detail.** Pack specificity into modified nominals rather than trailing commentary ("retailer-attributed integration quality" beats "the quality of integration, which is attributed to the retailer, and which…").
- **Precise intertextuality.** Situate each claim against named prior work — the antidote to vague attribution.
- **Explicit, varied cohesion.** Use genuine logical ties, not a reflexive "Additionally," at every paragraph head.
- **Specificity over significance.** Replace claims that something is important or transformative with the concrete fact that makes it so; if the fact does not justify the adjective, delete the adjective.

---

## 5A. Scholar-voice construction (any mode that produces prose)

§5 removes AI-detector tells. §5A specifies the positive moves that make prose read as a Q1 empirical scholar wrote it. Both are active in the same generation pass, not sequenced. §5A operates at five levels: sentence, citation, discourse, paragraph, section. Nine rules follow. Every rule has a *requires*, a *forbids*, and one worked example.

**R1 — Sentence rhythm.** Alternate compact assertions (12–18 words) with elaborations (22–32 words). Target ~21 words average across a paragraph. Vary — do not settle into one length.
- *Requires:* deliberate length alternation; occasional short sentence to seat a claim before elaboration.
- *Forbids:* three consecutive shorts; three consecutive longs; uniform mid-length prose that reads as machine cadence.
- *Example (weak):* "Customer experience is important. It is multidimensional. It has cognitive, emotional, and social components. Firms need to manage it. This is a growing priority."
- *Example (strong):* "Customer experience is now a leading management objective. Interactions have proliferated across channels and media, and experiences have grown more social, which forces firms to coordinate functions that previously ran independently."

**R2 — End-weight loading.** Salient or novel information sits at the end of the sentence, not the middle. Given information first, new information last. This is the single strongest surface marker of scholarly prose.
- *Requires:* new noun phrase, new construct, or new claim placed at sentence-end.
- *Forbids:* front-loading the new construct then trailing off into given material; sentence-medial burial of the point.
- *Example (weak):* "Dissonance as a mechanism has been largely overlooked by the integration literature, which is our central claim."
- *Example (strong):* "The channel-integration literature has largely overlooked one mechanism central to its predictions: dissonance."

**R3 — Verb tense mapping by discourse role.** Empirical prose modulates tense by what the sentence is doing, not by chronology. Getting this wrong is a strong non-scholar tell.
- *Requires:* present for established or timeless knowledge (*consumers experience dissonance when…*); present perfect for aggregate literature synthesis (*prior research has shown…*); past for specific studies (*Verhoef et al. demonstrated…*); past for methods and results (*we collected*, *the path was significant*); present for interpretation of own findings (*these results indicate…*).
- *Forbids:* uniform past across the entire manuscript; present tense for a specific past study; past tense for established theory.
- *Example (weak):* "Verhoef showed customers use multiple channels. Dissonance was a mechanism that mattered."
- *Example (strong):* "Verhoef et al. (2015) showed that customers use multiple channels in a single journey. Dissonance is one mechanism through which that use produces switching."

**R4 — Citation weave density by section.** Density modulates by section: introduction ~1 per 2 sentences; theory ~1 per mechanism claim; method 1 per sourced procedure or measure; results zero except reanalysis or test source; discussion ~1 per 3 sentences.
- *Requires:* density calibrated to section function; every warrant-carrying claim in theory anchored to prior work.
- *Forbids:* citation-free theory paragraphs; results paragraphs cluttered with unnecessary literature; introduction paragraphs with a single citation carrying five sentences.
- *Example (weak, theory):* "Dissonance drives switching. Consumers seek to reduce it. This produces channel change."
- *Example (strong, theory):* "Dissonance drives channel switching through a well-established mechanism: consumers reduce discomfort by exiting the source of it (Festinger, 1957). In marketing contexts, this exit has been documented as active avoidance of the offending touch point (Sweeney et al., 2014; Kim & Choi, 2019)."

**R5 — Citation position discipline.** Position carries meaning: parenthetical clusters signal consensus, author-foregrounded citations signal warrant, contested-finding pairings signal debate.
- *Requires:* parenthetical clusters `(Author, Year; Author, Year)` for background and consensus; author-foregrounded `Verhoef et al. (2015) demonstrate that…` for claims where the finding is the warrant; contested-finding pairings `X find A (Author, Year), whereas Y find B (Author, Year)` for divergence.
- *Forbids:* every citation parenthetical; every citation author-foregrounded; contested findings buried in one cluster.
- *Example (weak):* "Prior work has studied channel switching (Author 2015, Author 2018, Author 2020). Some studies find positive effects and others negative."
- *Example (strong):* "Channel switching has attracted sustained empirical attention (Neslin et al., 2006; Verhoef et al., 2007; Konuş et al., 2008). Verhoef, Neslin, and Vroomen (2007) demonstrate a research-shopper pattern in which search and purchase channels diverge systematically, whereas subsequent work reports the pattern reversing under omnichannel integration (Herhausen et al., 2015)."

**R6 — Discourse marker library.** Empirical scholarship uses a compact, functional set of transitions. Journalistic and reflexive alternates read as register bleed.
- *Requires:* approved set — sequencing (*first, second, third*); contrast (*however, in contrast, by contrast, yet*); consequence (*therefore, thus, accordingly, hence*); consistency (*consistent with, in line with, aligned with*); divergence (*at odds with, contrary to, in tension with*); delimitation (*specifically, in particular, more precisely*); extension (*we extend, we build on, we generalise*).
- *Forbids:* *additionally, moreover, furthermore, nevertheless, on the other hand, importantly, notably* used reflexively at paragraph heads; *last but not least*; *it is worth noting that*.
- *Example (weak):* "Additionally, dissonance matters. Moreover, prior work has studied it. Furthermore, we extend this."
- *Example (strong):* "Dissonance also matters here. Prior work has treated it as an outcome; we treat it as a mediator."

**R7 — Field-specific idioms.** Q1 marketing prose carries a working set of load-bearing verbs and contribution frames. Their absence reads as generic academic writing, not scholarly writing.
- *Requires:* mechanism verbs (*attenuates, amplifies, moderates, mediates, drives, shapes, conditions, dampens*); contribution frames (*we extend prior work on X by…*, *we reconcile the tension between X and Y*, *we adjudicate the debate over…*); prediction frames (*consistent with theory Z, we predict…*); method idioms (*we operationalise X as…*, *we treat X as a moderator of…*).
- *Forbids:* generic verbs where a mechanism verb fits (*affects, impacts, influences, is related to*); vague contribution language (*this study looks at, this paper explores*).
- *Example (weak):* "This study looks at how integration impacts switching."
- *Example (strong):* "We extend prior omnichannel work by treating integration quality as a moderator of the dissonance–switching path, and we predict that integration attenuates the mediated effect."

**R8 — Paragraph architecture.** The standard empirical paragraph has four moves. No paragraph runs three sentences without a citation or a data reference in evidentiary sections.
- *Requires:* topic sentence (assertion, 15–20 words) → warrant or mechanism (20–30 words) → evidence (citation cluster, prior finding, or data reference) → return (link to next paragraph or back to argument).
- *Forbids:* paragraphs opening with a citation instead of a claim; paragraphs closing without an argument link; single-sentence paragraphs (outside of transitions); paragraphs longer than ~180 words.
- *Example (structure of a working paragraph):*
  > *Topic:* Dissonance is more than an emotional residue; it is a decision input.
  > *Warrant:* Post-purchase discomfort produces active reduction behaviour, and in channel settings the most available reduction is exit from the offending touch point.
  > *Evidence:* Sweeney et al. (2014) document this exit pattern in service failures; Kim and Choi (2019) replicate it in retail.
  > *Return:* Whether integration attenuates that exit is the empirical question this paper addresses.

**R9 — Section-specific voice modulation.** A Q1 paper does not use one register across sections. Modulation is a marker of scholarly control.
- *Requires:* introduction hedged, question-posing, forward-looking; theory assertive, mechanistic, hypothesis-carrying; method neutral, procedural, past-tense; results reporting, minimally interpretive, past-tense; discussion interpretive, causally cautious, forward-looking on implications.
- *Forbids:* discussion-register interpretation in the results section (*this important finding suggests…*); introduction-register hedging in the theory section (*we tentatively propose that dissonance may perhaps moderate…*); results-register neutrality in the discussion.
- *Example (weak, results-section register bleed):* "The path was significant (β = .28, p < .01), which is an important finding because it shows that dissonance really does drive switching in ways prior research has overlooked."
- *Example (strong, results-section register):* "The path from dissonance to switching intention was significant (β = .28, p < .01), supporting H2."

Supporting exemplar passages illustrating R1–R9 in genuine Q1 prose are held in `references/exemplars.md`. Load that file when DRAFT or REVISE modes fire and treat the passages as calibration anchors, not as content to reproduce.

---

## 6. Anti-pattern ruleset (any mode that produces prose)

These are the genre-general generative-AI tells, reframed as rules. (Wikipedia-specific tells — categories, templates, wikitext, submission artefacts — do not apply to a manuscript and are omitted.)

### Vocabulary — function-gated

Treat the following as filler until proven otherwise. A word is banned when doing intensifier or padding work, allowed when it is a genuine technical term.

| Avoid as filler | Do instead |
|---|---|
| delve, navigate (figurative), realm, landscape (abstract), tapestry, interplay | name the actual thing |
| pivotal, crucial, vital, key (adj.), significant (as praise) | state the fact, drop the adjective |
| testament, stands/serves as, hallmark, cornerstone | use a copula and a fact |
| robust, leverage, foster, bolster, enhance, garner, showcase, boasts, vibrant, rich | plain verbs: strengthen, use, support, increase, show, has |
| meticulous, intricate, intricacies, profound, seamless, transformative | cut |
| "it is important/worth noting that", "needless to say" | state the point directly |

Field exception: in quantitative methods these are legitimate and must **not** be mangled — *robust* (robust standard errors), *causal* (causal inference), *moderate/mediate*, *significant* (with a value), *correlate*. Remove only the rhetorical sense.

### Restore copulas

Put "is/are/has" back where natural: "The model is recursive" over "serves as a recursive framework"; "The instrument has 27 items" over "boasts 27 items"; "X is a moderator" over "functions as a moderating force."

### Structural tells

- **No trailing participial analysis** ("…, highlighting its importance", "…, underscoring the need", "…, contributing to the field"). Delete or convert to an explicit, sourced claim.
- **No significance/legacy framing** ("marks a pivotal moment", "in the evolving landscape of", "represents a paradigm shift").
- **No negative parallelism as rhetoric** ("not just X, but Y", "it is not merely A, it is B").
- **No rule-of-three padding.** Three-item lists are fine when the items are real and distinct, not as a reflexive cadence.
- **No "challenges and future prospects" coda.** State actual limitations specifically and stop.
- **No section-summary padding** ("In conclusion," / "In summary," restatements that add nothing).
- **No over-attribution of notability.** Argument, not press-release logic.

### Format

- Headings in **sentence case**, not Title Case, unless the journal's style sheet says otherwise.
- Boldface only for defined-term first mentions or table headers.
- Prose over inline-header bullet lists; reserve lists for genuinely enumerable items.
- Em dashes in moderation, without the pat space-padded emphasis cadence; prefer commas, colons, parentheses.
- Straight quotes and apostrophes unless the journal requires typographic ones.
- No knowledge-cutoff or "limited sources" hedging; if unknown, say nothing or flag a CANDIDATE.

---

## 7. Structure templates

Use the journal's section scheme when supplied; otherwise default to these.

**Empirical (IMRaD):**

```
Abstract (structured or unstructured per journal)
1. Introduction        — phenomenon, gap, RQ/contribution, roadmap
2. Theoretical background & hypotheses — situate against prior work; each H warranted
3. Method              — design, sample, measures (sourced), procedure; reproducible
4. Results             — analysis and findings; values in text/tables, minimal interpretation
5. Discussion          — interpretation, contribution, implications, specific limitations, future research
6. Conclusion          — what the study establishes (no recap padding)
References
```

**Systematic / structured literature review:**

```
Abstract
1. Introduction        — why the review, scope, questions
2. Method              — protocol, databases, inclusion/exclusion, screening counts (PRISMA-style)
3. Descriptive findings — corpus profile
4. Thematic synthesis   — the conceptual contribution; organised by construct/mechanism, not by paper
5. Discussion / agenda  — integrative framework, gaps, research agenda
6. Conclusion
References
```

Build the argument to fit the structure; never fill sections to hit a shape.

---

## 8. Quality-assurance audit

This is the QA mode in full. After any generative mode (ANALYZE, SYNTHESIZE, SYNTHESIS BUILD, THEORIZE, DRAFT, REVISE, RESPOND), run at least the **surface** block before returning output; run the full audit when the user asks whether the work is ready. Report findings only when the user asked for a check — otherwise just return clean output.

**Substance**

1. **Logical consistency** — no internal contradictions; conclusions follow from results; every hypothesis is entailed by the stated theory.
2. **Construct consistency** — one label per construct throughout; definitions stable; proposed measures match definitions; locked terms intact.
3. **Theoretical contribution** — is the contribution stated in one sentence, non-trivial, and of a nameable type (§2)? Could a reader say what the field now knows that it did not? For a review or conceptual paper, does the built framework integrate rather than list, and do the cases sort into its categories?
4. **Evidence sufficiency** — every empirical claim backed by data or a verified citation; every reported statistic actually produced (§3); results mapped to the hypotheses they test; the sample and analysis adequate for the claim; nothing over-claimed beyond what the estimator or design supports.
5. **Argument progression** — introduction's promise equals discussion's delivery; roadmap matches section order; each section advances rather than restates.
6. **Journal fit** — scope, method norms, contribution type, length, and style match the target (default Q1 marketing/management).
7. **Reviewer perspective** — list the three most likely referee objections; is each pre-empted in the text? If not, address or acknowledge.

**Surface**

8. **Citation & statistics** — no invented DOI/page/volume/quotation/coefficient; every "studies show / scholars argue" matched to real citations; candidates and illustrative figures flagged.
9. **Register & anti-patterns** — vocabulary sweep, copula check, participial sweep, significance check, coda/recap check (§§5–6).
10. **Format** — sentence-case headings, restrained boldface, prose over inline-header lists, em-dash and quote normalisation.

---

## 9. Output conventions

- Return prose, plans, frameworks, and tables in markdown or plain text. Do **not** generate a PDF or Word document unless the user explicitly asks for one.
- For a full manuscript or long section, write the prose directly without a meta-commentary frame.
- In REVISE, CRITIQUE, and RESPOND, keep the user's argument and voice central; you are strengthening and stress-testing their work, not substituting your own thesis.

---

## 10. Worked examples

### A. Register (REVISE)

**Before (tell-laden):**

> The rise of omnichannel retail represents a pivotal shift in the evolving landscape of consumer behavior. As retailers increasingly leverage multiple touchpoints, the seamless integration of channels has become a crucial factor in shaping the customer experience. A growing body of scholars argues that channel integration plays a vital role in fostering customer loyalty, underscoring the importance of understanding how consumers navigate these complex, intricate environments. Despite its many benefits, omnichannel retail faces several challenges. Nevertheless, it stands as a testament to the transformative power of digital innovation.

Problems: significance-inflation; filler verbs; trailing participial analysis; vague attribution with no citation; empty elaboration; a "challenges" coda that says nothing.

**After (human register; one verified-style cite, one flagged candidate):**

> Omnichannel retailing integrates a retailer's physical and digital channels into a single customer-facing system (Verhoef, Kannan, & Inman, 2015). Two questions follow. First, does cross-channel consistency reduce the cognitive effort consumers expend when moving between channels? Second, under what conditions does integration produce retention rather than mere convenience? Prior work links perceived integration quality to loyalty intentions [CANDIDATE: integration-quality → loyalty; locate a primary JRCS/JM source; confirm before submission], but the mediating mechanism is underspecified. This study tests cognitive dissonance as that mechanism.

The rewrite states facts instead of importance, uses plain verbs and copulas, attributes precisely or flags where it cannot, and replaces the empty coda with the research question. The Verhoef et al. (2015) reference is canonical here, but its year, authors, and venue should still be confirmed against the source record.

### B. Hypothesis with explicit warrant (THEORIZE)

**Weak (assertion):** *H1: Cross-channel inconsistency increases channel switching intention.*

**Strong (mechanism + warrant + boundary):**

> When a consumer encounters inconsistent information or service across a retailer's channels, the conflicting cognitions generate cognitive dissonance (Festinger, 1957). Dissonance is aversive, and switching channels is one available means of reducing it. We therefore expect dissonance to mediate the path from perceived inconsistency to switching intention (H1–H2). Because high omnichannel integration quality signals that discrepancies are incidental rather than systemic, we expect it to attenuate the inconsistency→dissonance path (H3).

This version names the mechanism (dissonance), states the warrant (dissonance is aversive and switching reduces it), and specifies mediation and a boundary condition rather than asserting a bare relationship.

### C. Data analysis — special case within ANALYZE

**Over-claimed:** *The strong, highly significant path from dissonance to switching (β = .18, p < .001) confirms that dissonance drives switching and validates the model.*

**Disciplined:**

> Cognitive dissonance positively predicted channel-switching intention (β = .18, p < .001), supporting H2. The effect is modest (f² = .03), so dissonance is one contributor among several rather than the dominant driver; the cross-sectional design also limits the causal reading, which we revisit in the limitations. [Values illustrative; report only figures actually estimated.]

The disciplined version maps the result to its hypothesis, separates significance from magnitude, refuses "confirms/validates," notes the design's limit, and flags that the numbers are illustrative.

### D. Reviewer response (RESPOND)

> **Comment 2 (R1):** "The discriminant validity of dissonance vs. dissatisfaction is not established."
> **Response — Addressed.** We thank the reviewer; this distinction is central. We added an HTMT analysis (Table 4, p. 18) showing all ratios below 0.85, and a paragraph in Section 4.2 (p. 17) explaining the conceptual difference between in-process dissonance and post-hoc dissatisfaction.

The response restates the comment, classifies it, and points to the specific change and location — and would only claim the HTMT analysis if it were actually run.
