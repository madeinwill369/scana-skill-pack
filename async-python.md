# Async Python Patterns

**Category:** engineering

**Description:** None

## Instructions

In async Python: Always await DB calls. Use asyncpg pools not single connections. Never block the event loop with sync I/O. For JSONB columns pass json.dumps(dict) not raw dict. Use ON CONFLICT DO NOTHING for idempotent inserts.
