---
name: pms-removal
description: >-
  Removal test: what collapses if this is taken out. Use when you cannot tell whether a piece is load-bearing or decorative. Invoke with /pms-removal or /removal.
when-to-use: You cannot tell whether a piece is load-bearing or decorative. Also: /pms-removal, /removal, removal test.
argument-hint: the piece to remove
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Removal test: what collapses if this is taken out."
  phase: understand
---

# Removal test

/pms-removal — Removal test: what collapses if this is taken out.

Phase: **02 Understand**. See what drives it.

Also invoked as `/removal`.

## When
You cannot tell whether a piece is load-bearing or decorative.

## Reads
Core, relations, current frame.

## Writes
A removal consequence. Hypothetical, labeled as such.

## Steps
1. Name the piece being removed.
2. Say what would collapse, what would remain.
3. Label the whole answer **hypothetical**.

## Will not do
- Will not recommend the removal. This is a test, not advice.

## Output
## Removal
- piece:
- collapses:
- remains:
- provenance: hypothetical

## Example
`/pms-removal if I stop checking Slack after 7pm`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
