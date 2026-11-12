# Agent instructions for the Romp

This repo holds skills and agents for training. It is one of the AgenticED guild repos.

## Layout

- `skills/<skill>/SKILL.md`: one skill per folder. `skills/_template/` is the starting point.
- `agents/<agent>/`: one agent per folder. `agents/otter/` is the guild steward.
- `.claude/skills/`: tooling for contributors to this repo. These are not published skills.

## Rules

- Change one skill per pull request.
- Keep every skill folder self-contained. Do not reference files outside it.
- Keep `name` and `description` in every `SKILL.md` frontmatter. CI rejects a skill without them.
- Do not change LICENSE, CODEOWNERS, or files under `.github/` unless a human asks.
- Do not merge pull requests. A human guild lead merges.
- Never commit credentials, tokens, or an organization's private data.

## Style

Write in active voice. Prefer short sentences and concrete instructions.
