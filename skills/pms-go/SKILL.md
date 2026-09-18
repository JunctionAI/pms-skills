---
name: pms-go
description: >-
  Set the destination you’re trying to reach. Use when motion is happening with no named end-state. Invoke with /pms-go or /go.
when-to-use: Motion is happening with no named end-state. Also: /pms-go, /go, set destination.
argument-hint: the destination
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Set the destination you’re trying to reach."
  phase: navigate
---

# Set destination

/pms-go — Set the destination you’re trying to reach.

Phase: **03 Navigate**. Find the next move.

Also invoked as `/go`.

## When
Motion is happening with no named end-state.

## Reads
Optional: current here.

## Writes
Destination on the navigator. Direction becomes relative to it.

## Steps
1. Write the destination in the user's words, then a tighter restatement.
2. Do not invent success criteria (that's /pms-criteria).
3. Direction is now relative to this destination.

## Will not do
- Will not pad the destination with extra goals.

## Output
## Destination
- stated:
- interpreted:
- here_unchanged: true

## Example
`/pms-go a practice that ships one real thing a week without burning the evenings`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
