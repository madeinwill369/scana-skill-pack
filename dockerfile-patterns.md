# Dockerfile Best Practices

**Category:** engineering

**Description:** None

## Instructions

Python Dockerfiles: use python:3.11-slim base. Install gcc libssl-dev libffi-dev for asyncpg. Copy requirements first (cache layer). Copy app code second. EXPOSE the port. CMD uvicorn with 0.0.0.0 host. Never run as root in prod (but Fly.io handles this).
