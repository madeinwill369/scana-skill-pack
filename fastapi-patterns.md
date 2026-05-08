# FastAPI Patterns

**Category:** engineering

**Description:** None

## Instructions

FastAPI best practices: Always use Depends() for auth injection. Use lifespan context manager for startup/shutdown. Return typed Pydantic models not raw dicts where possible. Health endpoint needs no auth. All sensitive routes need master key header check.
