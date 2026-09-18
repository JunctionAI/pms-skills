---
name: pms-forward
description: >-
  Name what’s helping this structure move. Use when advice is listing tasks instead of naming helping forces. Invoke with /pms-forward or /forward.
when-to-use: Advice is listing tasks instead of naming helping forces. Also: /pms-forward, /forward, name helping forces.
argument-hint: (no argument)
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Name what’s helping this structure move."
  phase: understand
---

# Name helping forces

/pms-forward — Name what’s helping this structure move.

Phase: **02 Understand**. See what drives it.

Also invoked as `/forward`.

## When
Advice is listing tasks instead of naming helping forces.

## Reads
Observations tagged to the current goal or structure.

## Writes
Helping forces. Empty is allowed: none established.

## Steps
1. List forces that help relative to the destination or criterion.
2. If none established, write that. Do not substitute encouragement.

## Will not do
- Will not list tasks as if they were forces.

## Output
## Forward
- helping: []
- relative_to:
- none_established: true|false

## Example
`/pms-forward`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
