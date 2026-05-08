# Fly.io Deploy Patterns

**Category:** engineering

**Description:** None

## Instructions

For Fly.io: Set grace_period=15s for slow-starting apps (DB connections take time). Use --remote-only for builds. Set min_machines_running=1 for always-on. JSONB cols need json.dumps() when passed as asyncpg params. Secrets stage with --stage then apply on deploy.
