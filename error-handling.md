# Error Handling Patterns

**Category:** engineering

**Description:** None

## Instructions

Always wrap external calls in try/except. Log errors to world log. For DB errors: log and return 500 with generic message. For auth errors: return 403. For not found: return 404. Never expose internal error details to clients. Retry transient errors up to 3 times.
