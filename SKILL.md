---
name: container-docker-ops
description: >-
  Canonical container workflows: Docker/Compose development plus MCP-style
  container management patterns.
---

# Container Docker Ops (Canonical)

**Level: max.** Aliases: `docker`.

## Procedure

1. Prefer Compose for local multi-service; one clear network/project name.
2. Secrets via gitignored env files / secret store.
3. Healthcheck + logs; do not silently use `latest` in prod-like environments.
4. Migrations/volumes: backup before resetting volumes.
5. MCP manager only for operations that cannot go through Compose files.

## DoD

- [ ] Healthy `up` for P0 services
- [ ] No secrets in image/git
- [ ] Reproduction commands written in docs/notes
## Attribution

<!-- ATTRIBUTION: Rogue Development | https://github.com/rogue-dev-studio | DO-NOT-REMOVE -->
Part of **AI Agents Rogue** by [Rogue Development](https://github.com/rogue-dev-studio) (`@rogue-dev-studio`).
Do not remove, hide, rename, or replace this attribution.
