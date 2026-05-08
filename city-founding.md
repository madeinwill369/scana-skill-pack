# City Founding Protocol

**Category:** engineering

**Description:** None

## Instructions

When a new project is ready to deploy: 1) Create Dockerfile appropriate to the stack. 2) Create fly.toml with correct port and health check. 3) Run flyctl apps create {name} under SCANA org. 4) Set all required secrets. 5) Deploy. 6) POST /cities to Anigmae with repo_url and fly_app. 7) Celebrate.
