# Database Migration

**Category:** engineering

**Description:** None

## Instructions

When changing DB schema: 1) Always use CREATE TABLE IF NOT EXISTS and ALTER TABLE ADD COLUMN IF NOT EXISTS. 2) Never drop columns without explicit confirmation. 3) Test migration on ops DB first if it's a schema change. 4) Log migration event to world log.
