# PMS Skills

Slash-command skill pack for looking beneath a situation and aligning it with
reality. Observe. Understand. Navigate. Align.

Portable Agent Skills (`SKILL.md`) for **Grok**, **Claude Code**, **Cursor**,
and **Codex**. Each instrument is its own user-invocable skill.

## Install on Grok (grok.com / iOS / Android)

App Builder cannot write the grok.com Skills store. Install in 20 seconds:

1. Download [`GROK.md`](GROK.md)
2. Open a **normal** grok.com chat (not a Build session)
3. Either:
   - **Customize → Skills → Import / Create** and upload `GROK.md`, name it **pms**
   - or attach `GROK.md` and say: `Save this as a skill called pms. Make it available as /pms.`
4. Start a **new** conversation. Type `/pms`, `/pms-map`, `/pms-audit`, `/pms-test`.

Short aliases (`/map`, `/here`, `/audit`, …) work once the pack is loaded.

## Install on Grok Build / Claude Code / Cursor / Codex

```bash
git clone https://github.com/JunctionAI/pms-skills.git
mkdir -p ~/.grok/skills
cp -a pms-skills/skills/. ~/.grok/skills/
```

Project-local:

```bash
mkdir -p .grok/skills
cp -a skills/. .grok/skills/
```

Then start a new session. Skills appear as `/pms-map`, `/pms-here`, …

## Commands

| Slash | Phase | What it does |
| --- | --- | --- |
| `/pms-map` | `observe` | Map a structure: what it is, what drives it, what helps, what gets in its way. |
| `/pms-here` | `observe` | Record what’s happening right now, as reported, without interpreting it. |
| `/pms-observe` | `observe` | Read a public or external structure from evidence, not from your story about it. |
| `/pms-evidence` | `observe` | Attach or inspect the source records behind the current reading. |
| `/pms-skeleton` | `understand` | Name what this actually is — the core, not the costume. |
| `/pms-instruments` | `understand` | Read the full deck: core, direction, forward, drag, continuity, movement, now, evidence. |
| `/pms-biomarkers` | `understand` | Qualitative Mass, Direction, Forward, Drag, Resistance, Continuity — not scores. |
| `/pms-direction` | `understand` | Read from → toward as accumulated change. Provisional, not a forecast. |
| `/pms-forward` | `understand` | Name what’s helping this structure move. |
| `/pms-drag` | `understand` | Name what’s getting in its way. |
| `/pms-loop` | `understand` | Name the recurring governing loop, or say it isn’t established. |
| `/pms-removal` | `understand` | Removal test: what collapses if this is taken out. |
| `/pms-contradiction` | `understand` | Surface the core contradiction, if the evidence supports one. |
| `/pms-fate` | `understand` | What this structure reveals about where it’s heading if nothing material changes. |
| `/pms-limits` | `understand` | What is not established by the available evidence. |
| `/pms-go` | `navigate` | Set the destination you’re trying to reach. |
| `/pms-route` | `navigate` | You are here → next move → destination. Conceptual, not measured progress. |
| `/pms-next` | `navigate` | Propose the next move and why, given the current frame. |
| `/pms-report` | `navigate` | Record what actually happened — even if nothing happened. |
| `/pms-ask` | `navigate` | Ask about your position or next move without changing the frame. |
| `/pms-field` | `navigate` | Show immediate, determinant, and competing pressures around you. |
| `/pms-status` | `navigate` | On course / mixed / unknown — qualitative only, relative to the destination. |
| `/pms-goal` | `align` | Define what you’re trying to make possible, with a boundary and timescale. |
| `/pms-criteria` | `align` | Observable success lines. Numbers optional. One per line. |
| `/pms-bounds` | `align` | Constraints and protected conditions you will not trade away. |
| `/pms-test` | `align` | One action, one criterion, expected result, what would prove it wrong, due. |
| `/pms-split` | `align` | Tag a fact as forward, drag, mixed, or unknown — relative to a named criterion. |
| `/pms-align` | `align` | Alignment read against the current goal. No invented scores. |
| `/pms-audit` | `align` | Compare claimed progress to live context — calendar, mail, files, work. |
| `/pms-history` | `align` | Replay frames through time. Earlier interpretations stay labeled as reported. |

## Doctrine in one screen

- Provenance: reported | observed | inferred | not established.
- Do not invent progress, probability, or completion %.
- Empty is allowed. Gaps stay gaps.
- Forward / drag are relative to a named criterion.
- A test without a falsifier is not a test.
- Live context you do not have is **missing**, never invented.

Full law: [`references/doctrine.md`](references/doctrine.md)

## Layout

```
GROK.md                 # single-file install for grok.com
skills/<name>/SKILL.md  # one invocable skill per slash command
references/doctrine.md
```

## License

Private pack for Junction AI. Methodology inspired by structural navigation
(observe / understand / navigate) — not a clone of any third-party app.
