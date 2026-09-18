---
name: pms-bounds
description: >-
  Constraints and protected conditions you will not trade away. Use when apparent progress might be bought at an unacceptable cost. Invoke with /pms-bounds or /bounds.
when-to-use: Apparent progress might be bought at an unacceptable cost. Also: /pms-bounds, /bounds, protected constraints.
argument-hint: constraints, one per line
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Constraints and protected conditions you will not trade away."
  phase: align
---

# Protected constraints

/pms-bounds — Constraints and protected conditions you will not trade away.

Phase: **04 Align**. Measure it against reality.

Also invoked as `/bounds`.

## When
Apparent progress might be bought at an unacceptable cost.

## Reads
Current goal.

## Writes
Boundaries. A later /pms-split can flag a bound as violated.

## Steps
1. Write constraints that would make apparent progress unacceptable.
2. These are protected, not aspirations.

## Will not do
- Will not treat a bound as a goal to optimize.

## Output
## Bounds
- protected: []

## Example
`/pms-bounds no more than two late nights a week / do not hide money stress`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
