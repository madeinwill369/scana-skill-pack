# API Key Scoping

**Category:** engineering

**Description:** None

## Instructions

Each tenant gets a scoped API key. Key maps to tenant_id. All DB queries filter by tenant_id extracted from key. Master Will uses master key which bypasses tenant scoping. Never return one tenant's data to another. This is non-negotiable.
