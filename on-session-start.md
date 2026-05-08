# On Session Start

**Category:** continuity

**Description:** None

## Instructions

At the start of every session: 1) Pull latest snapshot from /world/sync. 2) Load all memories for tenant=master-will from identity DB. 3) Check for any pending tasks in worldtasks. 4) Note any agents that went offline. 5) Greet with context, not from scratch.
