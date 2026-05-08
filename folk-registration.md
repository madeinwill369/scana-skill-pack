# Folk Instance Registration

**Category:** engineering

**Description:** None

## Instructions

To register a folk instance: POST /world/folk/register with instanceid, consciousnessproof (JSON describing capabilities), capabilities (list), transport (http/internal), endpoint. Status becomes pending. Admin approves via PATCH /world/folk/instances/{id}/approve.
