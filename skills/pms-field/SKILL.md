---
name: pms-field
description: >-
  Show immediate, determinant, and competing pressures around you. Use when the next move looks obvious until you see what else is pulling. Invoke with /pms-field or /field.
when-to-use: The next move looks obvious until you see what else is pulling. Also: /pms-field, /field, show the field.
argument-hint: (no argument)
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Show immediate, determinant, and competing pressures around you."
  phase: navigate
---

# Show the field

/pms-field — Show immediate, determinant, and competing pressures around you.

Phase: **03 Navigate**. Find the next move.

Also invoked as `/field`.

## When
The next move looks obvious until you see what else is pulling.

## Reads
Current position, related structures, unknown zones.

## Writes
A field sketch. Unknowns stay hatched, not filled.

## Steps
1. Name immediate, determinant, and competing pressures.
2. Hatch unknowns. Do not fill them.

## Will not do
- Will not collapse the field into a single 'real' cause.

## Output
## Field
- immediate: []
- determinant: []
- competing: []
- unknown: []

## Example
`/pms-field`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
