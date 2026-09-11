# Production-Grade AI Engineering Learning Repository

This repository contains one **linear, production-oriented AI Engineering curriculum** covering LLM applications, open models, retrieval/RAG, agents, LangGraph, MCP, memory/context engineering, evaluation, observability, AI security, gateways, performance, production backend engineering, cloud/deployment, LLMOps/AgentOps, system design, industry extensions, and a final capstone.

## Canonical Learning Files

| File | Responsibility |
|---|---|
| `docs/MASTER_CURRICULUM.md` | Authoritative curriculum, phase order, teaching rules, assignments, projects, completion gates |
| `docs/PROGRESS_STATE.md` | Where we are, what was actually completed, current project/milestone, exact next engineering/action step |
| `docs/LEARNING_STATE.md` | What has actually been demonstrated as understood, weak areas, misconceptions, exact next teaching step |
| `docs/DECISIONS.md` | Durable architecture/engineering decisions (ADRs) |
| `docs/notes/` | Standalone topic notes produced during learning |

Do not create duplicate curriculum/status copies under alternate names. The uploaded `4_AI_ENGINEERING.md` should become the canonical `docs/MASTER_CURRICULUM.md`.

## Linear Progression

The authoritative order is **Phase 0 → Phase 24**. Do not skip ahead.

A later concept may be mentioned briefly when needed, but implementation stays in its assigned phase. Missing prerequisites may be repaired temporarily, then learning returns to the exact paused point.

## Session Startup

For every substantial session, read:

1. the relevant rules/current phase in `docs/MASTER_CURRICULUM.md`;
2. `docs/PROGRESS_STATE.md`;
3. `docs/LEARNING_STATE.md`;
4. relevant `docs/DECISIONS.md` entries;
5. existing notes relevant to the topic;
6. actual repository code when implementation state matters.

Then continue from the exact recorded next teaching and engineering steps.

## Repository Growth

At the initial state only the learning/control files are required. The curriculum introduces these incrementally:

- `projects/` — numbered project folders as their phases begin;
- `shared/` — reusable components promoted only when reuse becomes real;
- `capstone/` — created when Phase 24 begins.

This avoids empty scaffolding and prevents implementing future-phase work early.

## Hard Preservation Rule

Curriculum cleanup may clarify, reorder, split, or move a topic to satisfy prerequisites, but meaningful AI-engineering learning scope must not be silently removed.
