---
name: pms-here
description: >-
  Record what’s happening right now, as reported, without interpreting it. Use when you need a starting position before direction or next-move talk. Invoke with /pms-here or /here.
when-to-use: You need a starting position before direction or next-move talk. Also: /pms-here, /here, record what is happening now.
argument-hint: what is true in this moment
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Record what’s happening right now, as reported, without interpreting it."
  phase: observe
---

# Record what is happening now

/pms-here — Record what’s happening right now, as reported, without interpreting it.

Phase: **01 Observe**. Look at what is there.

Also invoked as `/here`.

## When
You need a starting position before direction or next-move talk.

## Reads
Whatever you (or live context) can say is true in this moment.

## Writes
A dated observation with provenance: reported — not inferred.

## Steps
1. Capture the present tense only. No interpretation.
2. Split reported vs observed if any live context is actually available.
3. Date the observation. Do not update destination or next-move.

## Will not do
- Will not interpret, coach, or reframe.
- Will not treat this as progress toward a goal.

## Output
## Now
- at: (ISO date if known, else 'now')
- text:
- provenance: reported | observed
- does_not_establish:

## Example
`/pms-here I have one interview booked and two applications still unsent`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
