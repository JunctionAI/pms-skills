---
name: pms-goal
description: >-
  Define what you’re trying to make possible, with a boundary and timescale. Use when the destination is a vibe and you need a system you can test. Invoke with /pms-goal or /goal.
when-to-use: The destination is a vibe and you need a system you can test. Also: /pms-goal, /goal, define what to make possible.
argument-hint: the goal, boundary, timescale
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Define what you’re trying to make possible, with a boundary and timescale."
  phase: align
---

# Define what to make possible

/pms-goal — Define what you’re trying to make possible, with a boundary and timescale.

Phase: **04 Align**. Measure it against reality.

Also invoked as `/goal`.

## When
The destination is a vibe and you need a system you can test.

## Reads
Optional current destination.

## Writes
Goal, system boundary, timescale, baseline. Clears pending tests if revised.

## Steps
1. Capture: make-possible, whose situation, boundary, timescale, baseline now.
2. If this revises a prior goal, retire pending tests. Keep history.

## Will not do
- Will not invent criteria (use /pms-criteria) or bounds (use /pms-bounds).

## Output
## Goal
- make_possible:
- system:
- timescale:
- baseline:
- pending_tests: retired if revised

## Example
`/pms-goal six months: a consulting practice that pays rent without owning my weekends`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
