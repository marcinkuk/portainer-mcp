# Archival fork

Upstream `portainer/portainer-mcp` was deprecated on 2026-10-08 in favour of
Portainer Command and may be archived or removed. This fork keeps:

- the full git history and tags (forked 2026-11-25 at release `2.45.3`,
  commit `5e87dec`);
- the `.mcpb` release bundles as assets of the fork's `2.45.3` release;
- Docker images mirrored to `ghcr.io/marcinkuk/portainer-mcp`
  (tags `2.42`…`2.45`), reproducible via `.github/workflows/mirror.yml`.

To use with Portainer: `docker run ghcr.io/marcinkuk/portainer-mcp:2.45`
with `PORTAINER_URL` + `PORTAINER_API_KEY` (see README deployment options).
