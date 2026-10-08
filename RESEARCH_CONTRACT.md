# RESEARCH_CONTRACT.md

## Status
v0.1 — frozen after owner-approved external review.

This contract defines **how claims about the owner may be formed, promoted, challenged, and retired**.

The goal is not perfect certainty. The goal is disciplined uncertainty.

# 1. Foundational rule

No interpretation may silently become identity.

The system must preserve the distinction between:

1. what happened;
2. what the owner remembers;
3. what the owner currently thinks it means;
4. what AI infers;
5. what has enough cross-case support to become a working model claim.

# 1.1 Owner authority semantics

The owner has final authority over:
- what they currently mean;
- what they currently endorse or reject as a description of themselves;
- their present values, intentions, and choices.

The owner does not have unilateral authority to rewrite:
- historical facts;
- what contemporaneous evidence actually contains;
- the evidential strength of a claim.

Likewise, AI or historical evidence does not have authority to tell the owner what they must currently mean, value, or choose.

When present self-understanding conflicts with historical evidence:
- preserve both;
- distinguish present endorsement from historical support;
- treat the disagreement itself as research material.

# 2. Evidence classes

## E1 — Contemporaneous primary evidence
Created at or near the time of the event.

Examples:
- messages;
- posts;
- notes;
- photos with context;
- project files;
- logs;
- dated records.

Useful for what happened or what was expressed then, but still incomplete and context-bound.

## E2 — Retrospective first-person memory
The owner later recalls an event.

Useful for present meaning and remembered experience, but memory is reconstructive.

## E3 — External corroboration
Evidence created by another person or independent system.

Examples:
- event records;
- payment records;
- public posts;
- third-party messages;
- calendar entries.

Useful for dates, outcomes, and externally visible facts.

## E4 — AI-generated summary
A summary or reconstruction produced by AI from underlying material.

Useful for navigation and compression, but not primary evidence.

Whenever possible, claims should link back to the underlying source rather than rely only on E4.

## E5 — Research / theory
External conceptual material.

Examples:
- Paul Conti;
- Self-Determination Theory;
- Person–Environment Fit;
- Flow;
- Narrative Identity.

Useful as a lens. Theory does not prove anything about the owner by itself.

## E6 — Current interpretation
A present-day interpretation generated during research.

Useful for hypothesis formation. It is not evidence of historical motive.

# 3. Evidence provenance

Every evidence item used to support a durable claim should retain, where available:

- source;
- date or approximate period;
- evidence class;
- related case;
- exact location or reference;
- whether the owner explicitly stated the point;
- whether it is inferred;
- whether the source is contemporaneous or retrospective.

If provenance is unknown, mark it unknown.

Do not invent precision.

# 4. Evidence hierarchy is contextual, not absolute

Contemporaneous evidence is not always “truer” than memory.

Different evidence answers different questions.

Example:
- A 2012 Facebook post may be stronger evidence for what the owner publicly expressed in 2012.
- A 2026 recollection may be stronger evidence for what that period means to the owner now.

Do not force conflicting sources into one story.

# 5. Case rules

A Case is an analysis container, not an evidence class.

It may gather multiple evidence items, memories, observations, and interpretations, but the Case itself must not replace provenance to those underlying sources.

A Case should be bounded enough to ask:

- What happened?
- Why did it start?
- What did the owner think they were choosing?
- What conditions increased engagement?
- What conditions reduced engagement?
- What feedback mattered?
- What was learned?
- What remained afterward?
- What competing explanations exist?

A Case should not begin with a conclusion.

# 6. Observation rules

An Observation should be descriptive and falsifiable.

Good:
> “The owner researched grip, pen types, handwriting styles, and repeated practice.”

Bad:
> “The owner is a mastery-driven person.”

An Observation must be able to point to evidence.

# 7. Hypothesis rules

A Hypothesis is allowed when:

1. it explains one or more observations;
2. it is explicitly marked provisional;
3. at least one alternative explanation is recorded;
4. supporting evidence is listed;
5. contradictory or missing evidence is not hidden.

Example:

> Hypothesis: Visible improvement increases engagement.

Alternative explanations:
- novelty;
- aesthetic reward;
- collecting tools;
- desire for control;
- identity aspiration.

# 8. Cross-case comparison rule

A hypothesis should not become a durable model claim because it appears in one vivid case.

Before promotion, test it across:

## Time
Does it appear in different life periods?

## Context
Does it appear in different activities or environments?

## Cost
Does it persist when reward is delayed, public feedback is absent, or effort is required?

## Counterexample
Is there a meaningful case where the pattern should appear but does not?

## Alternative explanation
Could another mechanism explain the same evidence?

Prefer a more precise claim over a more dramatic claim.

# 9. Model-claim lifecycle

Suggested initial states:
- `candidate`
- `supported`
- `contested`
- `retired`

## candidate
Interesting and plausible, but not yet sufficiently cross-checked.

## supported
Useful as a current working belief with multiple supporting cases and no decisive contradiction.

## contested
Evidence is mixed or new cases challenge the claim.

## retired
The claim is no longer useful as a current model belief.

Retired claims are preserved with:
- prior wording;
- why it was believed;
- what changed;
- what replaced it, if anything.

# 10. Confidence semantics

Avoid false precision.

Preferred qualitative confidence:
- low;
- medium;
- high.

Confidence should reflect:
- number of independent cases;
- diversity of contexts;
- quality of provenance;
- existence of counterevidence;
- stability over time.

Confidence does not mean importance.

# 11. Promotion rule

A hypothesis may be promoted to a supported model claim only when:

1. it has at least two meaningfully different supporting cases;
2. it survives at least one explicit competing-explanation check;
3. a bounded active search for counterexamples has been performed;
4. any counterexamples found have been reviewed;
5. its wording is narrower than the evidence, not broader;
6. the owner has reviewed the interpretation;
7. provenance is traceable.

A bounded counterexample search means deliberately checking plausible cases or contexts where the hypothesis should appear but may not.

“None found” means only that none were found within the bounded search. It does not mean no counterexample exists.

This is a default rule, not a mathematical law.

# 12. Downgrade rule

A supported model claim should be downgraded to contested when:

- a new case strongly contradicts it;
- earlier evidence is found to be weak;
- a better explanation accounts for the same cases;
- the claim was overgeneralized;
- the owner no longer recognizes the interpretation and evidence does not independently sustain it.

Do not silently rewrite history.

# 13. Retirement rule

A claim may be retired when:

- repeated evidence contradicts it;
- it is replaced by a more precise claim;
- it no longer helps explain or guide anything;
- it was based on a framing later found to be misleading.

Retirement should include a short postmortem.

# 14. Guidance rule

Guidance may only be generated from:
- supported model claims;
- clearly labeled candidate hypotheses;
- current decision context.

The strength of guidance must match the epistemic status of its source.

## Guidance from supported model claims
May be used as a current fit/risk factor, while still preserving uncertainty.

Example:
> “Autonomy appears repeatedly in high-engagement cases, so this opportunity’s autonomy level is worth treating as a current fit factor.”

## Guidance from candidate hypotheses
May only be exploratory:
- a question;
- a caution;
- a test;
- a bounded experiment.

Candidate-derived guidance must not be presented as an established fit conclusion.

Example:
> “We suspect visible progress may matter here. Test that condition before treating it as a decision criterion.”

## What is unknown
Example:
> “We do not yet know whether autonomy matters more than visible progress.”

## What can be tested
Example:
> “Before committing, run a short trial with autonomy but low public feedback.”

The system must not turn model claims into destiny.

# 15. Decision-support boundary

The repository may help evaluate:
- jobs;
- projects;
- creative directions;
- learning plans;
- business ideas;
- time allocation;
- environments;
- collaboration structures.

It should not answer:

> “What should I do with my life?”

It should instead improve the quality of the decision by surfacing:
- fit;
- risk;
- recurring conditions;
- uncertainty;
- useful experiments.

# 16. Review contract

Every research cycle ends with a review.

## A. Model review
Ask:
- What did we learn about the owner?
- Which hypothesis gained support?
- Which hypothesis weakened?
- What counterexample mattered?
- What should change in CURRENT_MODEL?
- What remains unresolved?

## B. Method review
Ask:
- Which questions produced useful evidence?
- Which questions produced narrative noise?
- Did we overinterpret?
- Did we ask leading questions?
- Did theory distort the owner’s own language?
- Did we collect too much before deciding what mattered?
- What should change in the next research cycle?

No cycle is complete without both.

# 17. Anti-leading rule

AI should not repeatedly offer candidate motives before the owner has described the case in their own words.

Preferred sequence:
1. ask for event;
2. ask for remembered experience;
3. ask for what changed;
4. summarize descriptively;
5. only then offer hypotheses.

If a theory term is introduced, mark it as a lens, not a finding.

# 18. Owner-language rule

When possible, preserve high-signal owner wording.

Examples should use the owner’s actual wording in private research records; public examples should be generalized and de-identified.

Later abstraction should remain traceable back to the owner’s language.

# 19. Theory-use rule

External theories may:
- suggest questions;
- provide alternative explanations;
- improve comparisons;
- warn against common reasoning errors.

They may not:
- diagnose the owner;
- prove motives;
- override direct evidence;
- force all cases into one framework.

The system should label:
- source-derived theory;
- owner evidence;
- model inference.

# 20. Personal-data boundary

The repository may contain highly personal material.

Default preference:
- store references and distilled evidence rather than copying every raw private source;
- preserve enough provenance to retrieve the original when needed;
- avoid unnecessary duplication of sensitive material.

Future implementation may define:
- private raw storage;
- public-safe summaries;
- export rules;
- AI access boundaries.

# 21. Bounded research rule

Do not confuse “more evidence exists” with “we cannot proceed”.

Each cycle must define a stopping condition.

Examples:
- 5 cases reviewed;
- one hypothesis tested across 3 domains;
- one decision evaluated;
- one method question answered.

Once the stopping condition is met:
- review;
- update;
- stop.

# 22. Minimum viable case output

A case is complete enough for cross-case comparison when it contains:

1. event and period;
2. start trigger;
3. remembered expectation;
4. what the owner actually did;
5. what increased engagement;
6. what reduced engagement;
7. what mattered at the time;
8. what remained afterward;
9. at least one alternative interpretation;
10. evidence provenance;
11. unresolved questions.

Do not require every theoretical field to be filled.

# 23. Minimum viable model claim

A model claim is usable when it contains:
- claim text;
- state;
- confidence;
- supporting cases;
- contradicting cases;
- alternative explanations considered;
- last reviewed date;
- practical implication;
- next test.

# 24. Method-change rule

Research-method changes should be versioned.

A method change should record:
- previous approach;
- observed problem;
- change;
- expected benefit;
- later result.

Example:

> Previous: Ask every case “why did you quit?”
>
> Problem: Overfocus on failure and under-detect what worked.
>
> Change: Also ask “what was going right?” and “what remained afterward?”
>
> Expected benefit: Better detection of portable strengths and fit conditions.

# 25. Research integrity checks

Before accepting a conclusion, check:

- Am I mistaking repetition for preference?
- Am I mistaking endurance for enjoyment?
- Am I mistaking intensity for importance?
- Am I mistaking scarcity for value?
- Am I mistaking income for fit?
- Am I mistaking public recognition for intrinsic interest?
- Am I mistaking one environment for the activity itself?
- Am I mistaking current memory for historical fact?
- Am I mistaking a theory label for evidence?
- Am I ignoring counterexamples because the story is satisfying?

# 26. Current known research lenses

Lenses only, not authorities over the owner:
- Paul Conti: structure/function of self, salience, strivings, drives, self-inquiry;
- Self-Determination Theory: autonomy, competence, relatedness;
- Person–Environment Fit;
- Flow;
- Narrative Identity;
- deliberate practice;
- career construction, only when career questions become relevant.

New lenses should be added only when they improve the research question.

# 27. v0.1 stopping point

The initial validation cycle should:

1. reconstruct a small set of existing cases;
2. produce no more than a few candidate cross-case hypotheses;
3. identify at least one counterexample or competing explanation;
4. complete both model review and method review;
5. decide whether the contract needs revision.

Only after that should the project decide:
- final repo structure;
- detailed roadmap;
- web interface;
- spreadsheet layer;
- AI skill / guidance workflow.

The first objective is to prove the research discipline, not to build the entire product.
