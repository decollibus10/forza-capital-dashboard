# Model Selection For This Project

Updated: 2026-05-02

Use this file at the start of new Codex/ChatGPT chats for the Forza Capital wholesaling dashboard. The goal is to pick the right model and intelligence level before spending tokens.

## Recommended Settings

| Task | Best Model + Intelligence |
| --- | --- |
| Quick visual/text tweak | `gpt-5.4-mini` + `Low` |
| Normal app improvements | `gpt-5.4` + `Medium` |
| Finish/refactor the whole dashboard | `gpt-5.4` + `High` |
| Complex coding-agent session | `gpt-5.3-codex` + `Medium/High` |
| Hardest possible debugging/polish | `gpt-5.5` + `High` |

## Default Choice

For most work on this dashboard, use:

`gpt-5.4` + `Medium`

This is the best balance of quality, speed, and token cost for a single-file HTML dashboard with localStorage state, CSV/JSON import/export, responsive UI, and business workflow logic.

## When To Upgrade

Use `High` when the task touches:

- localStorage state migration
- JSON backup import/export
- CSV export logic
- larger UI refactors
- mobile responsiveness across many screens
- bugs that require browser verification

Use `gpt-5.5` only for the hardest debugging, architecture, or full polish passes.

## Token Note

Higher intelligence/reasoning does not change the model's per-token price. It can increase cost because the model may spend more hidden reasoning tokens before answering. Those hidden reasoning tokens are billed like output tokens.
