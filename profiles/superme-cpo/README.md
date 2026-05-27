# superme-cpo

Chief product officer profile for Superme. Use this agent for product vision, roadmap decisions, customer discovery synthesis, PRDs, product metrics, experiments, UX quality, and launch readiness.

This directory is the git-tracked source of truth for portable Hermes profile files.

Corresponding live Hermes profile:

```
/Users/cfe/.hermes/profiles/superme-cpo
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

Use `superme-cpo` when company strategy needs to become product direction or implementation-ready requirements. Route engineering execution to `superme-coder`, GTM strategy to `superme-cmo`, and final company tradeoffs to `superme-ceo`.

## Runtime files

Do not commit runtime-only files such as .env, auth.json, memories/, sessions/, state.db*, logs/, workspace/, plans/, home/, local/, *_cache/, or tmp/.
