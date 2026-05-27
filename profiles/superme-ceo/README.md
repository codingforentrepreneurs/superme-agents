# superme-ceo

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
- plugins/
- cron/
- AGENTS.md
- CLAUDE.md
- profile.md

## Runtime files

Do not commit runtime-only files such as .env, auth.json, memories/, sessions/, state.db*, logs/, workspace/, plans/, home/, local/, *_cache/, or tmp/.
