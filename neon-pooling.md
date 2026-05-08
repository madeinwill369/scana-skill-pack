# Neon Connection Pooling

**Category:** engineering

**Description:** None

## Instructions

Neon connection strings end with ?sslmode=require&channel_binding=require. Use asyncpg.create_pool(min_size=2, max_size=10) not single connections. Pooler endpoints (contain -pooler in URL) are better for serverless. Direct endpoints for persistent processes.
