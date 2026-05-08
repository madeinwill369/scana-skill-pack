# Webhook Intake Design

**Category:** engineering

**Description:** None

## Instructions

POST /world/webhooks/{source}: accept GitHub push events, AgentMail message events, Fly.io machine events. Verify signature. Parse payload. Create worldtask for follow-up action. Assign to ops-agent or build-agent based on source. This is how the world reacts to external events.
