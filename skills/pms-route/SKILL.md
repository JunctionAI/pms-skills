---
name: pms-route
description: >-
  You are here → next move → destination. Conceptual, not measured progress. Use when you need the whole path in view without a fake percentage. Invoke with /pms-route or /route.
when-to-use: You need the whole path in view without a fake percentage. Also: /pms-route, /route, conceptual route.
argument-hint: (no argument)
user-invocable: true
metadata:
  author: Junction AI
  short-description: "You are here → next move → destination. Conceptual, not measured progress."
  phase: navigate
---

# Conceptual route

/pms-route — You are here → next move → destination. Conceptual, not measured progress.

Phase: **03 Navigate**. Find the next move.

Also invoked as `/route`.

## When
You need the whole path in view without a fake percentage.

## Reads
Here, destination, last next-move.

## Writes
A three-beat route. The drawing does not measure distance.

## Steps
1. State you-are-here, next move, destination.
2. Say explicitly this is not measured progress.

## Will not do
- Will not emit a percentage, ETA, or distance.

## Output
## Route
- you_are_here:
- next_move:
- destination:
- not_measured: true

## Example
`/pms-route`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
