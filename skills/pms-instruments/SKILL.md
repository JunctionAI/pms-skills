---
name: pms-instruments
description: >-
  Read the full deck: core, direction, forward, drag, continuity, movement, now, evidence. Use when you want the glance, not a single lens. Invoke with /pms-instruments or /instruments.
when-to-use: You want the glance, not a single lens. Also: /pms-instruments, /instruments, read the instrument deck.
argument-hint: (no argument)
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Read the full deck: core, direction, forward, drag, continuity, movement, now, evidence."
  phase: understand
---

# Read the instrument deck

/pms-instruments — Read the full deck: core, direction, forward, drag, continuity, movement, now, evidence.

Phase: **02 Understand**. See what drives it.

Also invoked as `/instruments`.

## When
You want the glance, not a single lens.

## Reads
Latest saved reading.

## Writes
Nothing unless a lens is unresolved — then it names the gap.

## Steps
1. Fill each lens from the current frame only.
2. Unresolved stays unresolved. Do not average or invent.

## Will not do
- Will not skip a lens by padding it with guesses.

## Output
## Instruments
- core:
- direction: from → toward
- forward:
- drag:
- continuity:
- movement:
- now:
- evidence:
Each: state + provenance + unresolved?

## Example
`/pms-instruments`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
