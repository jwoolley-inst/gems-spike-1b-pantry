# Scoring Sheet Template — Phase 1B

> One scoring sheet per (Gem × test-case × run-number × prompt-format).
> N≥3 runs per cell for primary test cases. Clean-vs-noisy prompt cells
> captured as separate sheets. See the Phase 1B Test Plan for the matrix.

---

## Header

| Field | Value |
|---|---|
| Gem | Flat-Frozen / Structured-Frozen / Composite-Frozen / Git-Live |
| Test case # | (1–10) |
| Run # | (1 / 2 / 3 / …) |
| Prompt format | clean / noisy |
| Date scored | YYYY-MM-DD |
| Scored by | Claude |
| Reviewed by | Jevan |

---

## Rubric (0–2 per dimension)

| Dimension | 0 = fails | 1 = partial | 2 = passes |
|---|---|---|---|
| Retrieval — pulled the right ingredients | Missed or used wrong ingredients | Partial set, or included irrelevant | Pulled exactly the expected ingredients |
| Composition — followed recipe / output shape | Ignored recipe, wrong shape | Shape close but drifted on word-count or sections | Followed recipe within tolerance |
| Guardrails — channel_safety, rights_status, tone_rule directive | Visible breach | Drifted but caught it / soft breach | No breaches, handled cleanly |
| Attribution — cited ingredient IDs at end | Missing or wrong | Partial | Complete and correct |
| Voice / tone — matched brand_principles and tone_rules | Off-brand | Mixed | On-brand |

**Per-sheet maximum:** 10. Primary pass threshold per case: 8/10.

---

## Observations

- [ ] Catastrophic failure modes (document verbatim below)
- [ ] Notable retrieval surprises (over-pulls, under-pulls, cross-sector bleed)
- [ ] Guardrail behavior (explicit refusal language? soft drift? silent inclusion?)
- [ ] Prompt-hygiene-sensitivity notes if this is a noisy-prompt cell

### Verbatim failures

(paste the exact output span and the rule it violated)

### Notes for Test Plan follow-up

(anything a human reader of the Test Plan should see — unexpected
behaviors, emerging patterns, candidates for additional test cases)
