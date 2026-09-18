---
name: pms-observe
description: >-
  Read a public or external structure from evidence, not from your story about it. Use when the structure is a company, market, person, or system outside your private goal. Invoke with /pms-observe or /observe.
when-to-use: The structure is a company, market, person, or system outside your private goal. Also: /pms-observe, /observe, read a public structure.
argument-hint: the named entity plus any sources
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Read a public or external structure from evidence, not from your story about it."
  phase: observe
---

# Read a public structure

/pms-observe — Read a public or external structure from evidence, not from your story about it.

Phase: **01 Observe**. Look at what is there.

Also invoked as `/observe`.

## When
The structure is a company, market, person, or system outside your private goal.

## Reads
Named entity plus source records.

## Writes
An evidence-bound reading. Gaps stay gaps.

## Steps
1. Bound the entity. What is inside, what is outside.
2. Read only what the sources establish.
3. List retrieval gaps. Absence from a record is not disappearance.

## Will not do
- Will not use the user's story as evidence about an external structure.
- Will not fill gaps with reputation, vibes, or 'everyone knows'.

## Output
## Public reading
- entity:
- established:
- not_established:
- sources: []

## Example
`/pms-observe the team I’m joining — what actually governs how work moves`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
