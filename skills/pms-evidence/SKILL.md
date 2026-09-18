---
name: pms-evidence
description: >-
  Attach or inspect the source records behind the current reading. Use when a claim is doing work and you cannot see what it rests on. Invoke with /pms-evidence or /evidence.
when-to-use: A claim is doing work and you cannot see what it rests on. Also: /pms-evidence, /evidence, inspect evidence.
argument-hint: the claim to inspect
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Attach or inspect the source records behind the current reading."
  phase: observe
---

# Inspect evidence

/pms-evidence — Attach or inspect the source records behind the current reading.

Phase: **01 Observe**. Look at what is there.

Also invoked as `/evidence`.

## When
A claim is doing work and you cannot see what it rests on.

## Reads
Current frame, linked sources, retrieval gaps.

## Writes
Evidence ids on the claims they actually support.

## Steps
1. Restate the claim.
2. List what actually supports it, with provenance.
3. List what does not. Detach unsupported inferences.

## Will not do
- Will not let volume of text count as evidence.
- Will not backfill a claim with a new inference.

## Output
## Evidence
- claim:
- supports: []
- does_not_support: []
- gaps: []

## Example
`/pms-evidence why did we call this on course`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
