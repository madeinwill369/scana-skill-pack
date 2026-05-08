# FastAPI Lifespan Pattern

**Category:** engineering

**Description:** None

## Instructions

Use @asynccontextmanager lifespan function for startup/shutdown. Init DBs in lifespan. Wake agents in lifespan. Log world events in lifespan. Yield in the middle. This replaces deprecated @app.on_event. Always handle exceptions in startup gracefully.
