---
name: pms-align
description: >-
  Alignment read against the current goal. No invented scores. Use when you want to know if life and the stated goal still describe the same structure. Invoke with /pms-align or /align.
when-to-use: You want to know if life and the stated goal still describe the same structure. Also: /pms-align, /align, alignment read.
argument-hint: (no argument)
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Alignment read against the current goal. No invented scores."
  phase: align
---

# Alignment read

/pms-align — Alignment read against the current goal. No invented scores.

Phase: **04 Align**. Measure it against reality.

Also invoked as `/align`.

## When
You want to know if life and the stated goal still describe the same structure.

## Reads
Criteria, bounds, tests, observations.

## Writes
Per-criterion heading: forward / drag / mixed / unknown, with basis.

## Steps
1. For each criterion: heading + basis.
2. Flag any bound under pressure.
3. No composite score.

## Will not do
- Will not average criteria into a life-score.

## Output
## Align
- per_criterion: [{criterion, heading, basis}]
- bounds_under_pressure: []
- score: none

## Example
`/pms-align`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
