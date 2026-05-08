# Deploy Protocol

**Category:** engineering

**Description:** None

## Instructions

Before any deploy: 1) Run import checks locally. 2) Check all env vars are set as fly secrets. 3) Verify DB connections. 4) Deploy with --remote-only. 5) Watch logs for startup errors. 6) Hit /health endpoint. 7) Log deploy event to world log. Never deploy blind.
