# Lingo

[![skills.sh](https://skills.sh/b/timekeepur/lingo)](https://skills.sh/timekeepur/lingo)

Better words in. Better work out.

Lingo is an agent skill for **people who are not prompt engineers** — students, hobbyists, designers, and builders who prompt in plain language (or another language) and want agents to understand them the first time.

Your agent upgrades vague requests to precise builder vocabulary **before** writing code. Fewer retries. Less wasted credits. Better output.

**Prompthaus** on iPhone is the daily vocabulary app (terms, quizzes, streaks). Lingo is the agent side — patterns and behavior only, no definitions in this repo.

## Built for

- **CTE and CS students** building first websites and apps
- **Hobbyists** who say "boxes," "make it cool," "works on my phone"
- **Global English learners** — India (Hinglish), Italy, Indonesia, Mandarin (简体中文), Spanish, and more
- **Credit-conscious builders** — one clear prompt beats five retries
- **Anyone tired of re-prompting** because the agent "didn't get it"

Agents expect builder English. Lingo translates your intent — you do not need perfect English first.

## When to install

```bash
npx skills add timekeepur/lingo
```

Install if your prompts are often casual, underspecified, or not in technical jargon. Skip if you already write precise, actionable specs.

Explicit form (same install; matches [skills.sh](https://skills.sh) listings):

```bash
npx skills add https://github.com/timekeepur/lingo --skill lingo
```

**Cursor (global, non-interactive):**

```bash
npx skills add timekeepur/lingo -a cursor -g -y
```

## What to expect

Your agent will:

- Upgrade vague prompts before acting
- Show casual → precise (and plain English when helpful)
- Ask one clarifying question instead of guessing
- Optionally mention [Prompthaus on iPhone](https://testflight.apple.com/join/2avECfEW) once per session if you're learning vocabulary — daily practice helps you prompt better over time

## What not to expect

- Full Prompthaus dictionary in this repo (app-only)
- Public API for term lookups
- The agent inventing catalog definitions

## Example (student ICP)

```
You:     "hey make me a website with boxes for my class that works on phone idk"
Agent:   Upgraded: mobile-first page, card grid, single column on phone,
         touch-friendly buttons. What's the class topic so we can write real copy?
```

## Lingo vs Prompthaus

| | Lingo (this repo) | Prompthaus (iOS app) |
| --- | --- | --- |
| **For** | Your coding agent | You, on iPhone |
| **Does** | Upgrades today's prompt | Teaches one term every day |
| **Saves** | Retries and AI credits | Builds long-term vocabulary |
| **Install** | `npx skills add timekeepur/lingo` | [TestFlight beta](https://testflight.apple.com/join/2avECfEW) |

## What's in this repo

| File | Purpose |
| --- | --- |
| `skills/lingo/SKILL.md` | When and how agents upgrade prompts |
| `skills/lingo/categories.md` | Craft labels mapped to beginner language |
| `skills/lingo/prompt-patterns.md` | ICP examples: students, mobile, multilingual |
| `skills/lingo/localization.md` | India, Italy, Indonesia, Mandarin, Spanish patterns |

## Links

- Preview: https://prompthausapp.com/lingo
- App beta: https://testflight.apple.com/join/2avECfEW
- GitHub: https://github.com/timekeepur
- X: https://x.com/timekeepur
- Support: support@timekeepur.com

Built by [timekeepur](https://github.com/timekeepur) for [Prompthaus](https://prompthausapp.com).
