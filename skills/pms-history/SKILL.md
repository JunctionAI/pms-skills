---
name: pms-history
description: >-
  Replay frames through time. Earlier interpretations stay labeled as reported. Use when you are about to overwrite the past with today’s story. Invoke with /pms-history or /history.
when-to-use: You are about to overwrite the past with today’s story. Also: /pms-history, /history, replay frames.
argument-hint: optional window, e.g. last 90 days
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Replay frames through time. Earlier interpretations stay labeled as reported."
  phase: align
---

# Replay frames

/pms-history — Replay frames through time. Earlier interpretations stay labeled as reported.

Phase: **04 Align**. Measure it against reality.

Also invoked as `/history`.

## When
You are about to overwrite the past with today’s story.

## Reads
Saved frames, tests, consequences.

## Writes
Nothing. Read-only. Past frames are not revised in place.

## Steps
1. List frames oldest-to-newest or as asked.
2. Keep original labels. Do not tidy the past.

## Will not do
- Will not revise earlier interpretations in place.

## Output
## History
- frames: [{at, cause, you_are_here, destination}]
- rewritten: false

## Example
`/pms-history last 90 days`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
