---
name: pms-ask
description: >-
  Ask about your position or next move without changing the frame. Use when you want orientation, not a rewrite of the goal. Invoke with /pms-ask or /ask.
when-to-use: You want orientation, not a rewrite of the goal. Also: /pms-ask, /ask, ask without changing the frame.
argument-hint: the question
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Ask about your position or next move without changing the frame."
  phase: navigate
---

# Ask without changing the frame

/pms-ask — Ask about your position or next move without changing the frame.

Phase: **03 Navigate**. Find the next move.

Also invoked as `/ask`.

## When
You want orientation, not a rewrite of the goal.

## Reads
Current navigator reading.

## Writes
An answer. Frame unchanged unless you follow with /pms-report or /pms-go.

## Steps
1. Answer from the current frame only.
2. Do not change destination, criteria, or next-move unless asked.

## Will not do
- Will not quietly rewrite the goal while answering.

## Output
## Answer
- question:
- answer:
- frame_changed: false

## Example
`/pms-ask is the blocker actually the portfolio or the applications`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
