# Architecture Decisions

This file stores durable architecture and engineering decisions made while progressing through the AI Engineering curriculum.

Do not record trivial code edits. Do not delete an old decision when it changes; mark it Superseded and create the replacement ADR.

## ADR Template

```markdown
## ADR-001 — <Decision Title>

Status: Proposed | Accepted | Rejected | Deprecated | Superseded
Date: YYYY-MM-DD

### Decision
...

### Why
...

### Alternatives
...

### Chosen Approach
...

### Trade-offs
...

### When We Would Revisit It
...

### Supersedes / Superseded By
...
```

## Recorded Decisions

## ADR-001 — Keep the Post-Curriculum Flagship in the Same Repository and Build It Sequentially

Status: Accepted
Date: 2026-09-24

### Decision

After Phase 24 and the existing Final Capstone are completed, build the new **AI Engineering Intelligence Platform** as a post-curriculum flagship inside this same repository under:

`flagship/engineering-intelligence-platform/`

The folder is created only when the Section 58 entry gate passes.

The flagship is built in the authoritative F0 → F17 milestone order defined in `docs/MASTER_CURRICULUM.md`. The mentor must not scaffold or implement later flagship milestones early.

The existing `docs/PROGRESS_STATE.md`, `docs/LEARNING_STATE.md`, and `docs/DECISIONS.md` continue to be the authoritative continuity files.

### Why

The repository already defines a single-repository, sequential learning model. Keeping the flagship in the same repository preserves the learning history, makes earlier reusable components available for deliberate reuse, and avoids creating a disconnected portfolio project.

Delaying creation of the flagship folder prevents empty future scaffolding and reinforces the curriculum's no-jumping rule.

### Alternatives

- create a separate Git repository for the flagship;
- replace the existing Phase 24 capstone with the new product;
- add the product as another numbered phase/project before the capstone;
- create all flagship folders and architecture files now.

### Chosen Approach

Keep every existing phase/project/capstone unchanged. Append Section 58 after the curriculum and begin the flagship only after all existing completion gates pass.

Reuse earlier code only after inspecting it and confirming that reuse is appropriate.

### Trade-offs

Advantages:

- one coherent engineering history;
- no duplicated curriculum state;
- earlier production components can be reused deliberately;
- the recruiter-facing product remains visibly connected to the engineering progression;
- no conflict with the existing Phase 0 → Phase 24 order.

Disadvantages:

- the repository becomes larger;
- public navigation must clearly separate learning projects, the Phase 24 capstone, and the later flagship;
- reusable code may require refactoring before it is suitable for the flagship.

### When We Would Revisit It

Revisit only if repository size, access control, deployment isolation, licensing, or portfolio presentation creates a concrete technical reason to extract the flagship later. Such extraction would be a deliberate migration, not a new learning roadmap.

### Supersedes / Superseded By

Supersedes: None.

Superseded by: None.

