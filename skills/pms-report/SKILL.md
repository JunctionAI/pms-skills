---
name: pms-report
description: >-
  Record what actually happened — even if nothing happened. Use when a next move was named and time has passed. Invoke with /pms-report or /report.
when-to-use: A next move was named and time has passed. Also: /pms-report, /report, report a consequence.
argument-hint: what happened, including nothing
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Record what actually happened — even if nothing happened."
  phase: navigate
---

# Report a consequence

/pms-report — Record what actually happened — even if nothing happened.

Phase: **03 Navigate**. Find the next move.

Also invoked as `/report`.

## When
A next move was named and time has passed.

## Reads
Pending next-move or test.

## Writes
A consequence observation. Updates position; does not invent progress.

## Steps
1. Record the consequence as reported.
2. Update you-are-here. Do not mark success unless a test was closed.
3. Nothing happening is a valid report.

## Will not do
- Will not spin a no-result into a lesson that counts as progress.

## Output
## Consequence
- text:
- position_now:
- progress_established: false unless a test closed

## Example
`/pms-report I sent the email. No reply in five days.`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
