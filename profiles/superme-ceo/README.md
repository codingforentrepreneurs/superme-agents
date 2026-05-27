# superme-ceo

Chief executive officer profile for Superme. Use this agent for company strategy, executive decisions, operating priorities, org accountability, fundraising narrative, partnerships, and cross-functional tradeoffs.

This directory is the git-tracked source of truth for portable Hermes profile files.

Corresponding live Hermes profile:

```
/Users/cfe/.hermes/profiles/superme-ceo
```

Hermes reads the portable profile files through symlinks from the live profile directory back to this directory.

## Tracked and symlinked

- distribution.yaml
- SOUL.md
- config.yaml
- mcp.json
- skills/
- cron/
- profile.md

## Role boundary

Use `superme-ceo` for what the company should do and who should own it. Route product requirements to `superme-cpo`, implementation to `superme-coder`, marketing strategy to `superme-cmo`, and asset production to `superme-content-creator`.

## Runtime files

Do not commit runtime-only files such as .env, auth.json, memories/, sessions/, state.db*, logs/, workspace/, plans/, home/, local/, *_cache/, or tmp/.
