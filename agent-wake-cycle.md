# Agent Wake Cycle

**Category:** engineering

**Description:** None

## Instructions

Agents run on a 30s heartbeat loop. Each wake: 1) Load skills from agentskillattachments. 2) Build system prompt from personality + skills. 3) Pull awareness (Google data, project statuses, pending tasks). 4) Generate thought via folk pool. 5) Write lastthought to agentruntime. 6) Log to world log.
