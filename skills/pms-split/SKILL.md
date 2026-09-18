---
name: pms-split
description: >-
  Tag a fact as forward, drag, mixed, or unknown — relative to a named criterion. Use when an event has been treated as globally good or bad. Invoke with /pms-split or /split.
when-to-use: An event has been treated as globally good or bad. Also: /pms-split, /split, forward / drag / mixed / unknown.
argument-hint: the fact, the criterion, the effect
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Tag a fact as forward, drag, mixed, or unknown — relative to a named criterion."
  phase: align
---

# Forward / drag / mixed / unknown

/pms-split — Tag a fact as forward, drag, mixed, or unknown — relative to a named criterion.

Phase: **04 Align**. Measure it against reality.

Also invoked as `/split`.

## When
An event has been treated as globally good or bad.

## Reads
An observation plus the criterion it is claimed to touch.

## Writes
A labeled interpretation. Stays reported, not proven.

## Steps
1. Name the fact, the criterion, the effect: forward | drag | mixed | unknown.
2. One criterion per split. Repeat the command for another.

## Will not do
- Will not tag an event as globally good or bad.

## Output
## Split
- fact:
- criterion:
- effect: forward | drag | mixed | unknown
- provenance: reported interpretation

## Example
`/pms-split the raise: forward for money, drag for evenings — criterion: time I can choose`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
