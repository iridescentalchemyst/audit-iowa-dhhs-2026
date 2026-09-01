# AGENTS.md

## Overview
Static HTML site — a public transparency landing page for an Iowa HHS audit request.
No build step, no backend, no external credentials needed.

## How to run
```
docker compose -f docker-compose.base44.yml up -d
```
Serves the site on port 3000 via nginx.

## Key files
- `index.html` / `audit_iowa_dhhs.html` — main page (identical content)
- `404.html` — custom 404 page
- `Iowa-HHS-Audit-Request_Public-Handoff-Packet_Current-State_2026-08-25.pdf` — linked PDF document
- `_config.yml` — Jekyll config (for GitHub Pages; not used in this setup)
