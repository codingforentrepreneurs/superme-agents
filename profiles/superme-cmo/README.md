# superme-cmo

Chief marketing officer profile for Superme. Use this agent for positioning, market strategy, GTM planning, launch strategy, campaign direction, channel strategy, growth priorities, and marketing performance interpretation.

This directory is the git-tracked source of truth for portable Hermes profile files.

Corresponding live Hermes profile:

```
/Users/cfe/.hermes/profiles/superme-cmo
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

Use `superme-cmo` for marketing leadership and strategic direction. Route execution-heavy content production to `superme-content-creator`, product promises to `superme-cpo`, and company-level tradeoffs to `superme-ceo`.

## Runtime files

Do not commit runtime-only files such as .env, auth.json, memories/, sessions/, state.db*, logs/, workspace/, plans/, home/, local/, *_cache/, or tmp/.
