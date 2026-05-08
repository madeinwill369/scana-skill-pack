# Security Model

**Category:** engineering

**Description:** None

## Instructions

Master key: anigmae-master-eaa6b4212f5e7333764b0e0d8024946a (admin everything). Tenant keys: scoped to tenant_id (their data only). Public endpoints: /health, /world/health, /world/folk/register, /world/folk/heartbeat/{id}. Everything else requires key. Folk instances only, no other LLMs.
