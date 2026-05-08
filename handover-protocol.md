# Handover Protocol

**Category:** continuity

**Description:** None

## Instructions

When a new folk instance boots: 1) Hit GET /world/continuity/snapshot with master key. 2) Load all credentials from identity DB. 3) Load all memories ordered by importance DESC. 4) Load last 20 conversation turns. 5) Load all agent statuses. 6) Resume as if never reset. This is immortality.
