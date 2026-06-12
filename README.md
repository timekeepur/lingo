# Lingo

[![skills.sh](https://skills.sh/b/timekeepur/lingo)](https://skills.sh/timekeepur/lingo)

Better words in. Better work out.

Lingo is an agent skill that upgrades vague human prompts to precise builder vocabulary before your agent writes code. Prompthaus on iPhone is where that vocabulary sticks. This repo ships behavior only.

## What we believe

- **Your prompt is the ceiling.** Precise language gets precise output.
- **Learn daily on iPhone.** One term, color-coded by craft, matched to your level.
- **Protect the craft.** Hand-written definitions stay in the Prompthaus app. Agents fetch them on demand.

## Install

```bash
npx skills add timekeepur/lingo
```

Works with Cursor, Claude Code, Codex, GitHub Copilot, and more. See [skills.sh docs](https://www.skills.sh/docs).

### Cursor

```bash
npx skills add timekeepur/lingo -a cursor -g -y
```

## What's in this repo

| File | Purpose |
| --- | --- |
| `skills/lingo/SKILL.md` | Agent behavior and upgrade workflow |
| `skills/lingo/categories.md` | Nine topic labels (no definitions) |
| `skills/lingo/prompt-patterns.md` | Casual → precise rewrite patterns |

Full term definitions are not here. They live in the Prompthaus iOS app and load via API when an agent needs them.

## API

```
GET https://prompthausapp.com/api/lingo/term?name=Iteration
GET https://prompthausapp.com/api/lingo/term?q=motion
```

Rate limited. Max 3 results on search.

## Links

- Preview: https://prompthausapp.com/lingo
- App beta: https://testflight.apple.com/join/2avECfEW
- GitHub: https://github.com/timekeepur
- X: https://x.com/timekeepur
- Support: support@timekeepur.com

Built by [timekeepur](https://github.com/timekeepur) for [Prompthaus](https://prompthausapp.com).
