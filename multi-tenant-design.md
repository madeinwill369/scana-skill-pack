# Multi-Tenant Design

**Category:** engineering

**Description:** None

## Instructions

Every table has tenant_id defaulting to 'master-will'. New customers get: 1) Row in tenants table. 2) Their own folk_agent row. 3) Their own agentruntime rows. 4) Scoped credentials in identity DB with their owner_id. Data never crosses tenant boundaries.
