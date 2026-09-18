---
name: pms-limits
description: >-
  What is not established by the available evidence. Use when the reading is about to be treated as fact. Invoke with /pms-limits or /limits.
when-to-use: The reading is about to be treated as fact. Also: /pms-limits, /limits, limits of this reading.
argument-hint: (no argument)
user-invocable: true
metadata:
  author: Junction AI
  short-description: "What is not established by the available evidence."
  phase: understand
---

# Limits of this reading

/pms-limits — What is not established by the available evidence.

Phase: **02 Understand**. See what drives it.

Also invoked as `/limits`.

## When
The reading is about to be treated as fact.

## Reads
Current frame, missing sources, untested claims.

## Writes
An uncertainty list. Does not fill gaps.

## Steps
1. List claims that exceeded their evidence.
2. List missing sources. Do not fill them.

## Will not do
- Will not 'balance' uncertainty by adding a confident summary.

## Output
## Limits
- not_established: []
- missing_sources: []

## Example
`/pms-limits`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
