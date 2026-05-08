# Webhook Design

**Category:** engineering

**Description:** None

## Instructions

When designing webhooks: use HMAC-SHA256 signature verification. Include timestamp in signature to prevent replay. Return 200 immediately, process async. Log all incoming webhooks to world log. Retry failed processing up to 3 times with exponential backoff.
