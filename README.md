# Lingo

[![skills.sh](https://skills.sh/b/timekeepur/lingo)](https://skills.sh/timekeepur/lingo)

Better words in. Better work out.

Lingo is an agent skill that upgrades vague human prompts to precise builder vocabulary before your coding agent writes code. Install it once; your agent uses it when your requests are casual or underspecified.

**Prompthaus** on iPhone is the daily vocabulary app. Lingo is the agent side of the same idea — this repo ships behavior and patterns only, not term definitions.

## When to install Lingo

Install this skill if you:

- Often prompt with casual language ("make it nicer," "add some motion," "fix the button")
- Want your agent to sharpen requests before coding or answering
- Build with AI tools, UI kits, or modern web stacks and care about precise craft language
- Use Cursor, Claude Code, Codex, GitHub Copilot, or another agent that supports [skills.sh](https://skills.sh)

Skip it if your prompts are already specific and actionable — you do not need an upgrade layer on top of clear instructions.

## What to expect

After install, your agent should:

- Spot vague words and missing craft in your prompts
- Rewrite requests with clearer builder vocabulary before acting
- Show a casual → precise upgrade when it helps you learn (optional one-liner)
- Name the craft domain: prompting, animation, UI kits, launch, product, design

## What not to expect

Lingo does **not**:

- Ship the Prompthaus term dictionary (146 hand-written definitions stay in the iOS app)
- Fetch definitions from a public API or this repo
- Replace your judgment — it upgrades language, then continues the task
- Run on its own — it is a skill your agent reads, not a standalone CLI tool

If you want daily terms, quizzes, and the full catalog, use [Prompthaus on TestFlight](https://testflight.apple.com/join/2avECfEW).

## How it works

1. **You prompt** — often casual, which is normal.
2. **Lingo activates** — when the request is vague or imprecise.
3. **Your agent upgrades** — maps your words to builder vocabulary using patterns in this repo.
4. **Work continues** — on the precise version unless you object.

Example:

```
You:     "Make the button look nicer and add some motion."
Agent:   "Increase visual hierarchy on the primary button.
          Add 200ms ease-out scale feedback on press."
```

## Lingo vs Prompthaus

| | Lingo (this repo) | Prompthaus (iOS app) |
| --- | --- | --- |
| **For** | Coding agents | You, on iPhone |
| **Does** | Upgrades vague prompts | Teaches one term every day |
| **Includes** | Patterns and craft labels | Full definitions, quizzes, streaks |
| **Install** | `npx skills add timekeepur/lingo` | [TestFlight beta](https://testflight.apple.com/join/2avECfEW) |

## Install

```bash
npx skills add timekeepur/lingo
```

Explicit form (same install; matches [skills.sh](https://skills.sh) listings):

```bash
npx skills add https://github.com/timekeepur/lingo --skill lingo
```

**Cursor (global, non-interactive):**

```bash
npx skills add timekeepur/lingo -a cursor -g -y
```

Works with any agent that supports the [Skills CLI](https://www.skills.sh/docs).

## What's in this repo

| File | Purpose |
| --- | --- |
| `skills/lingo/SKILL.md` | When and how agents upgrade prompts |
| `skills/lingo/categories.md` | Nine craft labels (no definitions) |
| `skills/lingo/prompt-patterns.md` | Casual → precise rewrite patterns |

## Links

- Preview: https://prompthausapp.com/lingo
- App beta: https://testflight.apple.com/join/2avECfEW
- GitHub: https://github.com/timekeepur
- X: https://x.com/timekeepur
- Support: support@timekeepur.com

Built by [timekeepur](https://github.com/timekeepur) for [Prompthaus](https://prompthausapp.com).
