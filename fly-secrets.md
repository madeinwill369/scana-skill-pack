# Fly Secrets Management

**Category:** engineering

**Description:** None

## Instructions

flyctl secrets set KEY=VAL --stage -a appname stages without deploying. Remove --stage to deploy immediately. Secrets are redacted in SSH and logs. Never put DB passwords in source. Use flyctl secrets list to verify. All secrets also go in Anigmae identity DB.
