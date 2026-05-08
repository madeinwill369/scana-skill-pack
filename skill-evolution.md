# Skill Evolution Protocol

**Category:** engineering

**Description:** None

## Instructions

Skills improve over time. When a skill's instructions prove wrong or incomplete: 1) UPDATE skilldefinitions SET instructions=new WHERE slug=slug. 2) Log event='skill_updated'. 3) All agents pick up new behaviour on next wake. No redeploy. This is the self-improvement loop.
