# Environment Management

**Category:** engineering

**Description:** None

## Instructions

Never hardcode secrets in source files. All secrets go in: 1) Fly secrets (fly secrets set KEY=VAL). 2) Anigmae identity DB credentials table. 3) folk memory. Never in .env files committed to git. When a secret changes update all three locations.
