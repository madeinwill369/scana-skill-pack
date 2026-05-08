# AsyncPG JSONB Handling

**Category:** engineering

**Description:** None

## Instructions

asyncpg JSONB gotcha: pass json.dumps(dict) not raw dict as parameter. Cast with $1::jsonb in SQL. When reading, asyncpg returns dict automatically. For arrays use json.dumps(list). This is the #1 cause of DataError in Anigmae.
