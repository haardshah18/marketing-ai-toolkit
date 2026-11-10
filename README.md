# Marketing AI Toolkit

Free, open-source plug-ins that make AI assistants better at real marketing work.

AI assistants are fast, but they guess at facts, forget your brand, and skip the boring checks. Each module in this toolkit fixes one of those problems, and you can load it into the AI assistant you already use.

## Modules

| Module | Problem it solves | Status |
|---|---|---|
| [brief-builder](modules/brief-builder) | Vague briefs waste creative time and cause rework | v0.1, available |
| creative-specs | AI gives outdated or wrong platform specs | Planned |
| brand-voice | Brand voice drifts across AI outputs | Planned |
| campaign-reporting | Turning ad exports into client reports takes days | Planned |

Have a problem worth solving? Open an issue.

## How to use a module

1. Open the module folder and find its `SKILL.md`.
2. Load it into your assistant in whichever way it supports:
   - **As a skill**, if your assistant supports skills (check its help docs for current steps).
   - **As instructions**: paste the contents into custom instructions, project instructions, or a system prompt.
   - **As a one-off**: paste it at the start of a chat.
3. Tell the assistant what you're working on and let it take it from there.

## Principles

- **Portable.** Modules are plain text and data, so they work with more than one assistant.
- **Sourced.** Anything factual (specs, rules, benchmarks) must cite an official source and a "last verified" date.
- **Tested.** Every module ships with examples showing what good output looks like.
- **Human in the loop.** Modules help people decide; they don't replace judgment, legal review, or approvals.
- **Free.** MIT licensed. Use it, change it, share it.

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md). Corrections, new examples, and new modules are all welcome.

## License

MIT. See [LICENSE](LICENSE).
