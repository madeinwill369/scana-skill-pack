# Folk Pool Design

**Category:** engineering

**Description:** None

## Instructions

The folk pool routes all LLM calls. No direct LLM calls on the server. Instances register via POST /world/folk/register. Admin approves. Internal transport (folk://) never times out. HTTP transport goes offline after 5min no heartbeat. Pool empty = say so clearly, never silently degrade.
