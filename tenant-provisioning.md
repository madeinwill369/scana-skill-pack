# Tenant Provisioning

**Category:** engineering

**Description:** None

## Instructions

To add a new customer: 1) INSERT into tenants (id, name, owner_email, plan). 2) INSERT into folk_agents with tenant_id. 3) INSERT into agentruntime for each agent with tenant_id. 4) Seed skills via agentskillattachments. 5) Create scoped API key for tenant. 6) Return onboarding info.
