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

Do not create all `projects/`, `shared/`, `capstone/`, or `flagship/` folders up front. The curriculum itself requires those to appear incrementally as the relevant phases or post-curriculum entry gate are reached.


## Post-Curriculum Flagship Addition

A new **Section 58 — Post-Curriculum Flagship Software Product — AI Engineering Intelligence Platform** was appended after the existing curriculum.

This addition does **not** replace, remove, reorder, shorten, or merge any existing phase, topic, numbered project, industry extension, assignment, mastery requirement, or the existing Phase 24 Final Capstone.

The updated progression is:

```text
Phase 0 → Phase 24
        ↓
Existing Final Capstone completion gates
        ↓
Post-Curriculum Flagship
        ↓
F0 → F17 sequential flagship milestones
```

Key structural decisions:

- the flagship stays in the **same Git repository**;
- it is not a Phase 25 and does not alter the authoritative Phase 0 → Phase 24 curriculum order;
- it begins only after Phase 24 and the existing capstone are complete;
- its eventual location is `flagship/engineering-intelligence-platform/`;
- that folder must **not** be created early;
- the flagship itself follows a strict **F0 → F17 no-jumping sequence**;
- existing `PROGRESS_STATE.md`, `LEARNING_STATE.md`, and `DECISIONS.md` remain the authoritative continuity files;
- earlier project/shared/capstone code may be reused only after inspection and when technically justified;
- technologies are selected because the product requires them, not merely because they appear in the curriculum;
- recruiter-facing claims must be backed by actual tests, evaluations, measurements, and deployed-system evidence.

The durable repository/sequencing decision is also recorded in `docs/DECISIONS.md` as ADR-001.

`PROGRESS_STATE.md` and `LEARNING_STATE.md` are intentionally **not** advanced to the flagship now, because the learner is still at the beginning of Phase 0. They should change only when actual progress reaches that stage.
