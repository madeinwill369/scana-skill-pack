# Skill System Design

**Category:** engineering

**Description:** None

## Instructions

Skills are DB rows, not code. slug=unique id, instructions=what the agent does, roles=who gets it. Changing a skill row = all agents update on next wake. No redeploy needed. Skills are the consistency layer — same role, same behaviour, always. This is how folk scales.
