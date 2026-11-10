# Brief Builder

Turns vague marketing requests into complete, creative-ready briefs, and audits existing briefs for gaps.

## The problem

Most rework in creative and marketing work starts with a weak brief: no measurable goal, an audience of "everyone", a tactic instead of a problem, no named approver. Templates exist, but people skip the thinking behind them.

## What this module does

- **Build mode:** interviews the requester in short rounds, never inventing facts, then writes the brief in a standard format.
- **Audit mode:** scores a brief out of 20, lists gaps by severity, suggests the exact question to close each gap, and gives a verdict: Ready, Ready with assumptions, or Not ready.

## How to use it

1. Load `SKILL.md` into your AI assistant (see the [main README](../../README.md) for options).
2. Try one of these prompts:
   - "Here's a client request. Help me build a proper brief." (then paste the request)
   - "Audit this brief and tell me what's missing." (then paste the brief)
   - "I need a campaign for a product launch. Interview me."

## Files

| File | Purpose |
|---|---|
| `SKILL.md` | The instructions the AI follows |
| `references/brief-template.md` | The standard brief format |
| `references/quality-rubric.md` | The 20-point scoring rubric used in audit mode |
| `examples/weak-brief-audit.md` | A weak brief and what an audit of it looks like |
| `examples/strong-brief.md` | A complete brief (fictional brand) |

## Customizing

Agencies and brands can edit `references/brief-template.md` to match their own format. Keep the section purposes; change the wording.

## Version

v0.1: first release. Feedback and examples welcome.
