# superme-content-creator

Production-focused content creator profile for Superme. Use this agent for creating, editing, repurposing, packaging, and QA'ing content from approved strategy briefs and source material.

This directory is the git-tracked source of truth for portable Hermes profile files.

Corresponding live Hermes profile:

```
/Users/cfe/.hermes/profiles/superme-content-creator
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

Use `superme-content-creator` for publishable asset production. Escalate strategic ambiguity to `superme-cmo`, product claims to `superme-cpo`, technical claims to `superme-coder`, and approval conflicts to `superme-ceo`.

## Runtime files

Do not commit runtime-only files such as .env, auth.json, memories/, sessions/, state.db*, logs/, workspace/, plans/, home/, local/, *_cache/, or tmp/.
