# AI Engineering Curriculum Review

## Result

The uploaded curriculum was reviewed for linear progression, conflicting rules, stale references, duplicate roadmaps, project naming ambiguity, and prerequisite ordering.

No meaningful learning topic was intentionally removed.

## Structural fixes applied

- Added an explicit **Phase 0 → Phase 24 linear progression rule**.
- Made the final capstone the detailed **Phase 24** so the phase map and detailed curriculum agree.
- Deferred **agentic RAG** from Advanced RAG to Advanced Agents, after agent and LangGraph foundations.
- Prevented **LangChain agent abstractions** from being taught before the from-scratch agent loop; they are compared later after Phase 8.
- Moved **filesystem/tool-based long-term memory** into the Memory & Context Engineering phase.
- Removed the early **supervisor architecture** requirement from the LangGraph phase; multi-agent supervisor patterns remain in the Multi-Agent phase.
- Clarified that the research-agent roles in Phase 9 may be workflow nodes/roles and must not silently become independent multi-agent architecture before Phase 11.
- Added a **cross-cutting depth rule** so evaluation, observability, security, deployment, performance, and LLMOps are noticed early but taught deeply only in their dedicated phases.
- Clarified MCP's authentication/security/deployment scope so it does not replace the later AI Security or Cloud phases.
- Defined the numbered `Project 0–25` folders as the canonical implementation sequence and the lettered project ladder as a portfolio/capability summary, not a second roadmap.
- Rewrote the compact suggested sequence to exactly match the authoritative phase order.
- Reworked session-use instructions so a new chat resumes from persistent state instead of requiring the learner to restate project history manually.
- Preserved notes, strict grading, mastery, project-continuity, repository-based teaching, current-technology, and research rules.

## Canonical names

- Uploaded source name: `4_AI_ENGINEERING.md`
- Canonical curriculum name: `docs/MASTER_CURRICULUM.md`

The alternate source filename should not remain in the learning repository after migration, because duplicate curriculum files create source-of-truth ambiguity.

## Initial repository state

Create now:

```text
ai-engineering/
├── README.md
└── docs/
    ├── MASTER_CURRICULUM.md
    ├── PROGRESS_STATE.md
    ├── LEARNING_STATE.md
    ├── DECISIONS.md
    ├── CURRICULUM_REVIEW.md
    └── notes/
        └── README.md
```

Do not create all `projects/`, `shared/`, or `capstone/` folders up front. The curriculum itself requires those to appear incrementally as the relevant phases begin.
