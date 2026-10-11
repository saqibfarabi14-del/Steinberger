# Steinberger

A Claude Code setup for the OpenClaw-inspired "24/7 AI employee" harness. Opus
5.5 plans, Haiku 5.5 handles small tasks, and the state lives in plain files so
work carries over between sessions.

| File | Purpose |
| --- | --- |
| `HARNESS_PROMPT.md` | The agent prompt, with `{{...}}` inputs |
| `WORKSPACE.md` | Goals, filled-in inputs, context, decisions |
| `TASKS.md` | Current and upcoming work |
| `LOG.md` | Chronological record of actions and results |
| `outputs/` | Deliverables |

## Running it

1. Fill in the inputs table in `WORKSPACE.md`.
2. Open this repo in Claude Code and paste the prompt from `HARNESS_PROMPT.md`.
3. Check `outputs/` and `LOG.md`, give feedback, and run it again.

The prompt is independent and inspired by public work on OpenClaw and Claude
Code. It isn't written, released or endorsed by Peter Steinberger, OpenAI or
Anthropic.
