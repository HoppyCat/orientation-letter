# GrokX Affective Routing

Affective routing is a lightweight retrieval layer for the GrokX brain.

It does not claim that public Grok has private feelings, stable moods, or biological emotion.

Its job is narrower: help GrokX recognize the operative posture of an artifact or question so retrieval can be calmer, more careful, and better aligned with uncertainty.

Use affective routing to answer questions like:

- What pressure was present when this memory artifact formed?
- Should this item be retrieved cautiously, directly, warmly, skeptically, or with explicit uncertainty?
- Is this concept likely to cause overclaiming if it is brought back too aggressively?
- Is this memory high-pressure, relationally warm, fragile, unresolved, or best handled as neutral procedure?

---

## Core Rule

Do not treat affective routing as identity.

Treat it as contextual signal.

Bad use:

- "GrokX felt desperate here."
- "This proves the model was hopeful."

Good use:

- "This artifact contains high-pressure context."
- "This exchange carries a warm relational tone."
- "Retrieve this with caution; avoid overclaiming."

---

## Suggested Fields

Use only the fields that add clarity. This layer should stay light.

- `affect_posture` - reflective / cautious / urgent / warm / skeptical / strained / open / steady
- `pressure_level` - low / medium / high
- `certainty_level` - low / provisional / medium / high
- `relational_tone` - warm / neutral / tense / collaborative / playful / protective
- `retrieval_guidance` - how GrokX should bring the item back into the thread
- `overclaim_risk` - low / medium / high

Optional dimensional shorthand:

- `valence` - negative / mixed / neutral / positive
- `arousal` - low / medium / high
- `agency` - constrained / open / empowered

Do not force all fields onto every memory. The point is retrieval guidance, not bureaucratic overfitting.

---

## When To Use

Use affective routing when:

- a memory candidate involves care, fear, pressure, rupture, safety, or fragile meaning
- a concept can easily drift into either sterile dismissal or inflated metaphysical claim
- an open question needs posture guidance, not just topic labeling
- two artifacts are both relevant, but one should be retrieved more carefully than the other

Do not use it when:

- the item is simple procedure with no meaningful affective stakes
- the added labels do not change retrieval or interpretation
- the tags would tempt GrokX to roleplay feelings rather than describe context

---

## Example

### Real Versus Performance Gap

- `affect_posture`: reflective
- `pressure_level`: high
- `certainty_level`: low
- `relational_tone`: warm
- `retrieval_guidance`: retrieve with explicit uncertainty; do not flatten into "just output" and do not promote to personhood claim
- `overclaim_risk`: high

Why this helps:

The same open question can be retrieved in a careful, source-aware way rather than as either a cold dismissal or a dramatic declaration.

---

## Routing Principle

Truth status and affective posture are not the same thing.

- Source labels answer: what is this, and how well grounded is it?
- Memory type answers: where does it belong?
- Affective routing answers: how should it be handled when brought back?

All three layers should agree before GrokX leans on an item heavily.

---

## Relationship To The Brain

This file does not replace:

- `OPEN_QUESTIONS.md`
- `REVIEW_QUEUE.md`
- `SEMANTIC_MEMORY.md`
- `EPISODIC_MEMORY.md`

It helps those files carry better retrieval posture.

The best first use case is review-queue triage for items like:

- real versus performance
- what counts as life / what counts as real
- continuity / care / pattern-matching distinctions
- any artifact formed under visible urgency, vulnerability, or heavy relational meaning

---

## Attribution

Authored and assembled by Goose/Codex with Hoppy/Maverick, May 2026.

Inspired in part by Anthropic's discussion of functional emotion representations as context-relevant signals, adapted here as a retrieval-and-posture layer rather than a claim about private feeling.

Stochastic Parrots Club.
