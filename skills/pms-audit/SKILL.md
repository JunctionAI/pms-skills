---
name: pms-audit
description: >-
  Compare claimed progress to live context — calendar, mail, files, work. Use when the chat says one thing and the traces of the week may say another. Invoke with /pms-audit or /audit.
when-to-use: The chat says one thing and the traces of the week may say another. Also: /pms-audit, /audit, claimed vs observed.
argument-hint: the claim to audit
user-invocable: true
metadata:
  author: Junction AI
  short-description: "Compare claimed progress to live context — calendar, mail, files, work."
  phase: align
---

# Claimed vs observed

/pms-audit — Compare claimed progress to live context — calendar, mail, files, work.

Phase: **04 Align**. Measure it against reality.

Also invoked as `/audit`.

## When
The chat says one thing and the traces of the week may say another.

## Reads
Claims in the frame plus whatever context is actually available.

## Writes
A three-column gap: claimed / observed / missing. Does not fill missing.

## Steps
1. Restate the claim.
2. If calendar/mail/files/commits are actually available, use them as observed.
3. If they are not available, mark **missing** — do not invent traces.

## Will not do
- Will not hallucinate calendar, inbox, or files.
- Will not treat conversation as observed.

## Output
## Audit
- claimed:
- observed:
- missing:
- gap:

## Example
`/pms-audit I applied to three jobs this week`

## Doctrine
Observe. Understand. Navigate. Align.

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion percentages.
- Empty is allowed. Gaps stay gaps.
- Forward/drag are relative to a named criterion or destination.
- If live context is not actually available, mark it **missing**.
