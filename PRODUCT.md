# PRODUCT.md

## Status
v0.1 — frozen after owner-approved external review.

This document defines **what this product is for**. It is not the implementation plan, schema reference, or roadmap.

# 1. Product purpose

Build a durable, evidence-driven, versioned personal model that helps the owner:

1. understand how they actually operate across different periods and contexts;
2. distinguish recurring preferences, values, capabilities, constraints, coping patterns, and environmental effects;
3. use that understanding to make better future choices;
4. keep revising the model when new life evidence contradicts or sharpens old conclusions;
5. improve not only the personal model, but also the method used to study the owner.

The product is not intended to discover one fixed “true self”.

Its core question is:

> Based on the life evidence currently available, what do we reasonably know about how I operate, and how should that inform the next choice?

# 2. Product outcome

The long-term output is not a static biography or personality report.

The product should maintain three connected layers:

- **Evidence** — what actually happened, what was recorded at the time, what the owner later recalled, and what artifacts support.
- **Model** — the best current, explicitly provisional interpretation of recurring patterns across evidence.
- **Guidance** — how the current model changes the questions asked, risks noticed, or experiments proposed when the owner faces a new choice.

Short form:

> Evidence → Model → Guidance

No Guidance claim may bypass the Evidence and Model layers.

# 3. Core principles

## 3.1 Evidence before identity
Do not convert one vivid story into a personality claim.

A personal-model claim should become stronger only when it survives multiple cases, different contexts, different time periods, competing explanations, and contradictory evidence where available.

## 3.2 Activities are not the same as underlying conditions
“Music”, “programming”, “restaurant work”, “AI”, or “gaming” are not automatically stable interests.

Also ask:
- What was being pursued?
- What conditions made the activity work?
- What conditions made it stop working?
- What remained after the activity ended?

## 3.3 Context matters
The same activity can produce very different experiences in different environments.

Do not infer:
- “I dislike X” from one bad context;
- “I love X” from one good context;
- “I am good at X” merely from endurance;
- “I value X” merely from repetition.

## 3.4 Current interpretation is not historical fact
Keep separate when possible:
- contemporaneous evidence;
- retrospective memory;
- current interpretation.

Disagreement between them is useful evidence, not a cleanup problem.

## 3.5 Model claims are provisional
Every model claim should be able to gain support, lose support, split, merge, be retired, or remain unresolved.

Retired claims are preserved with their history.

## 3.6 Contradiction is useful
The product is successful when it can say:

> “This belief used to look plausible, but later evidence weakened it.”

Contradiction is model improvement, not failure.

## 3.7 Research method also evolves
There are two update loops:

- **Model update** — What have we learned about the owner?
- **Method update** — What have we learned about how to study the owner better?

Both must be preserved.

# 4. Primary user

The primary user is the owner.

AI may assist with:
- evidence retrieval;
- case reconstruction;
- cross-case comparison;
- hypothesis generation;
- contradiction detection;
- review;
- decision support.

AI must not become the final authority over the owner’s identity, values, or life direction.

Owner authority is not the same as evidential authority:
- the owner has final authority over what they currently mean, endorse, value, or intend;
- the owner does not retroactively overwrite historical facts or the strength of existing evidence merely by changing their present interpretation;
- disagreement between present self-understanding and historical evidence should be preserved for review rather than forced into one version.

# 5. What this product is not

This product is not:
- a personality test;
- a mental-health diagnosis;
- a deterministic life plan;
- a “find your one true passion” engine;
- a diary replacement;
- a raw archive of everything;
- a memory dump;
- a Quest Log replacement;
- a career recommender that chooses on behalf of the owner;
- a system that treats frequency as proof of preference;
- a system that treats productivity, income, or status as proof of fit.

# 6. Product semantics

## Evidence
A traceable observation, artifact, record, or memory.

## Case
A bounded life episode that can be studied.

Examples:
- a creative group activity;
- public performance in a new environment;
- seasonal or manual work;
- a deliberate practice period;
- a period of building with a new tool;
- a production cycle.

## Observation
A descriptive statement directly supported by evidence.

## Hypothesis
A provisional interpretation that tries to explain one or more observations.

## Model claim
A hypothesis that has survived enough cross-case checking to be useful as a current working belief.

Every model claim should retain:
- supporting cases;
- contradicting cases;
- uncertainty;
- last review date.

## Guidance
A question, warning, or experimental suggestion derived from current model claims.

Guidance is not a command.

## Experiment
A bounded real-life test designed to distinguish between competing explanations.

## Review
A deliberate evaluation of:
- what changed in the personal model;
- what evidence was weak or misleading;
- what questions worked poorly;
- what the next research cycle should change.

# 7. Current product loop

Each research cycle follows:

> Question
> → Evidence collection
> → Case reconstruction
> → Observations
> → Hypotheses
> → Cross-case comparison
> → Real-life test when useful
> → Review
> → Model update
> → Method update

A cycle is complete when the owner can identify:
- what was learned;
- what remains uncertain;
- what changed in the current model;
- what should be tested or reviewed next;
- what changed in the research method.

# 8. Self-improvement requirement

The repository should support the same improvement logic used in iterative production work:

> Plan → Do → Review → Carry Forward

For self-research:

## Plan
Define the bounded question for this cycle.

## Do
Collect and analyze only the evidence needed for that question.

## Review
Check:
- what patterns appeared;
- what alternative explanations remain;
- what evidence is weak;
- what interpretations were overconfident;
- what questions produced useful answers;
- what questions produced noise.

## Carry Forward
Bring forward only the findings and method changes that materially improve the next cycle.

Do not endlessly accumulate rules.

# 9. Success criteria

The product is working if, over time:

1. the owner can trace why a current self-model claim exists;
2. new evidence can weaken or revise old claims without losing history;
3. AI can distinguish observation from interpretation;
4. the system surfaces recurring conditions across very different life cases;
5. the owner can use the model to ask better questions about a real decision;
6. reviews improve later research cycles;
7. the repository becomes more precise without becoming harder to use;
8. the owner does not need to reread all historical material to benefit from it.

The product is not succeeding if:
- the repository grows but guidance does not improve;
- hypotheses quietly become “facts”;
- every interesting idea becomes a permanent rule;
- the system becomes too complex to maintain;
- AI produces confident identity labels unsupported by evidence.

# 10. Initial scope

The first phase should focus on a small set of previously discussed, private life cases spanning different activities, environments, and time periods. Specific case identities belong in private validation material, not this public repository.

The first phase is not to reconstruct the full 34-year life history.

It is to validate whether the research loop can produce:
- traceable observations;
- useful cross-case hypotheses;
- explicit counterevidence;
- better questions for the next case.

# 11. Long-term product surfaces

The repository is the durable authority.

Other surfaces may be added later:

- **Web** — reading/exploration interface for timelines, cases, patterns, and model evolution.
- **Sheet** — convenient filtering or structured-entry interface if tabular comparison becomes useful.
- **Skill / AI workflow** — a way for future AI conversations to use the current model when evaluating new opportunities or decisions.

These are interfaces over the same durable model, not independent truth stores.

# 12. Durable authority

The repository should be treated as the current durable authority for:
- product semantics;
- accepted model claims;
- evidence provenance;
- research-method changes;
- review history.

External sources such as NotebookLM, CBrain, ChatGPT history, Facebook, Drive, or other archives remain evidence sources.

They do not become current model truth merely because they exist.

# 13. Open questions for later

Intentionally unresolved in v0.1:
- exact repository name;
- exact confidence scale;
- exact file/folder structure;
- whether metadata should be YAML, JSON, or Markdown tables;
- whether Google Sheets should be used as a capture surface;
- whether experiments need their own lifecycle state;
- how privacy-sensitive evidence should be referenced without copying raw content;
- what thresholds are required before a hypothesis becomes a model claim.

These should be decided through implementation and review, not guessed upfront.


---
