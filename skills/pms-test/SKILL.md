---
name: pms-test
description: >-
  One action, one criterion, expected result, what would prove it wrong, due. Use when a next move is unfalsifiable — you could not know if it failed. Invoke with /pms-test or /test.
when-to-use: A next move is unfalsifiable — you could not know if it failed. Also: /pms-test, /test, design a falsifying test.
argument-hint: action, criterion, expected, falsifier, due
user-invocable: true
metadata:
  author: Junction AI
  short-description: "One action, one criterion, expected result, what would prove it wrong, due."
  phase: align
---

# Design a falsifying test

/pms-test — One action, one criterion, expected result, what would prove it wrong, due.

Phase: **04 Align**. Measure it against reality.

Also invoked as `/test`.

## When
A next move is unfalsifiable — you could not know if it failed.

## Reads
Goal, criteria, current next-move.

## Writes
A pending test. Retires if the goal frame is revised.

## Steps
1. Require all five: action, criterion, expected, falsifier, due.
2. If any is missing, ask for it. Do not invent a falsifier.

## Will not do
- Will not save a test with no contradiction condition.

## Output
## Test
- action:
- criterion:
- expected:
- falsifier:
- due:
- status: pending

## Example
`/pms-test send the offer email by Friday; if no reply in 5 days the channel is not live`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
