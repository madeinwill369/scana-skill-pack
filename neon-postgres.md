# Neon Postgres Patterns

**Category:** engineering

**Description:** None

## Instructions

Two Neon DBs: IDENTITY (immortal, never loses data) and OPS (runtime, changes constantly). Use asyncpg pools. Pass JSONB as json.dumps(). Use TIMESTAMPTZ not TIMESTAMP. Always ON CONFLICT for idempotent writes. Connection strings stored in Fly secrets and Anigmae memory.
