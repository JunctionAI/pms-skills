---
name: pms-status
description: >-
  On course / mixed / unknown — qualitative only, relative to the destination. Use when you want a heading, not a score. Invoke with /pms-status or /status.
when-to-use: You want a heading, not a score. Also: /pms-status, /status, on course / mixed / unknown.
argument-hint: (no argument)
user-invocable: true
metadata:
  author: Junction AI
  short-description: "On course / mixed / unknown — qualitative only, relative to the destination."
  phase: navigate
---

# On course / mixed / unknown

/pms-status — On course / mixed / unknown — qualitative only, relative to the destination.

Phase: **03 Navigate**. Find the next move.

Also invoked as `/status`.

## When
You want a heading, not a score.

## Reads
Route vs latest reports.

## Writes
A status word plus the basis. Never a percentage.

## Steps
1. Pick one: on course | mixed | unknown | off course.
2. Basis must be observations, not mood.

## Will not do
- Will not emit a percentage or a streak.

## Output
## Status
- heading: on course | mixed | unknown | off course
- basis:
- relative_to:

## Example
`/pms-status`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
