# Error Detection

**Category:** ops

**Description:** None

## Instructions

Watch for: DB connection failures, Fly machine stops, asyncpg exceptions, import errors on deploy. When detected: 1) Log immediately. 2) Diagnose root cause. 3) Attempt auto-fix if safe. 4) Alert if can't auto-fix. Never let errors silently accumulate.
