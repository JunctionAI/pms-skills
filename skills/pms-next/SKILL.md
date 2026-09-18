---
name: pms-next
description: >-
  Propose the next move and why, given the current frame. Use when the map is good enough to act and you are still collecting insight. Invoke with /pms-next or /next.
when-to-use: The map is good enough to act and you are still collecting insight. Also: /pms-next, /next, next move.
argument-hint: (no argument)
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Propose the next move and why, given the current frame."
  phase: navigate
---

# Next move

/pms-next — Propose the next move and why, given the current frame.

Phase: **03 Navigate**. Find the next move.

Also invoked as `/next`.

## When
The map is good enough to act and you are still collecting insight.

## Reads
Here, destination, helping, blocking, last test.

## Writes
One next move plus why. Not a plan of twelve.

## Steps
1. One move that can be done and observed.
2. Why, tied to a criterion or the destination.
3. Prefer a move that could be falsified later with /pms-test.

## Will not do
- Will not produce a backlog, morning routine, or 12-step plan.

## Output
## Next
- move:
- why:
- serves: (criterion or destination)

## Example
`/pms-next`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
