# Health Check Design

**Category:** engineering

**Description:** None

## Instructions

Every service needs GET /health with no auth. Returns {status: ok}. Fly.io uses this for liveness. Set grace_period=15s for DB-connecting apps. Check actual DB connectivity in /services endpoint. Health check should be fast (<100ms ideally).
