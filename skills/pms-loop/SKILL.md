---
name: pms-loop
description: >-
  Name the recurring governing loop, or say it isn’t established. Use when the same week keeps happening with new costumes. Invoke with /pms-loop or /loop.
when-to-use: The same week keeps happening with new costumes. Also: /pms-loop, /loop, name the governing loop.
argument-hint: (no argument)
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Name the recurring governing loop, or say it isn’t established."
  phase: understand
---

# Name the governing loop

/pms-loop — Name the recurring governing loop, or say it isn’t established.

Phase: **02 Understand**. See what drives it.

Also invoked as `/loop`.

## When
The same week keeps happening with new costumes.

## Reads
Repeated observations across frames.

## Writes
A loop of 2–5 steps, or an explicit not-established.

## Steps
1. Look for recurrence across frames, not a one-off sequence.
2. 2–5 steps. If not recurrent, not established.

## Will not do
- Will not invent a loop from a single episode.

## Output
## Loop
- steps: []
- established: true|false

## Example
`/pms-loop`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
