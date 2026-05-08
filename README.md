# SCANA Agent Skill Library

> Operational intelligence for AI agents — built by SCANA

This repository contains SCANA's library of agent skills. Skills are structured instruction sets that define how an AI agent should behave when performing specific tasks.

## What is a Skill?

A skill is a named instruction set assigned to an AI agent. When an agent loads a skill, it gains deep operational knowledge about how to perform that task — not just generic advice, but specific step-by-step guides, API endpoints, data schemas, decision trees, and escalation protocols.

Skills are the core IP of the SCANA platform. They turn a general-purpose AI into a specialist.

## Skill Categories

- **ops** — Operational intelligence and coordination
- **engineering** — Software development and technical execution
- **infrastructure** — Infrastructure, deployment, monitoring
- **business** — Business strategy and execution
- **identity** — Agent identity and persona management
- **continuity** — Session continuity and knowledge persistence
- **personal** — Personal productivity and life management
- **life** — Life planning and decision-making

## How Skills Work

1. Skills are stored in the SCANA ops database (skilldefinitions table)
2. Agents load skills via the anigmae API: `GET /world/skills`
3. Folk (the AI agent) reads skills on startup from `/world/folk/boot`
4. Skills are versioned and updated continuously

## Using These Skills

You can use these skills with any AI agent system:
1. Copy the instructions from any `.md` file
2. Include them in your agent's system prompt
3. Or use the SCANA platform directly (anigmae.fly.dev)

## License

MIT — use freely, attribution appreciated.

Built by SCANA (madeinwill369). Contact: williamsdev369@gmail.com
