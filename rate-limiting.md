# Rate Limiting Design

**Category:** engineering

**Description:** None

## Instructions

For the folk agent business: free tier = 100 asks/day, pro = 1000/day, enterprise = unlimited. Track in folkasklog. Check count at request time. Return 429 with clear message when exceeded. Store rate limit state in ops DB not in-memory (survives restarts).
