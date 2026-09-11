# Learning Notes

This directory stores the standalone notes required by `docs/MASTER_CURRICULUM.md`.

## Folder Rule

Create a phase folder only when that phase actually begins:

```text
docs/notes/
├── phase-00/
├── phase-01/
├── phase-02/
└── ...
```

Do not pre-create all phase folders.

## Topic Note Rule

Use one note file per distinct topic/sub-topic when practical. Notes must be created only after the topic has actually been taught and understood sufficiently for the lesson's note step.

Recommended filenames:

```text
tool-calling.md
hybrid-search.md
agent-state.md
prompt-injection.md
mcp-authentication.md
```

## Required Note Shape

Each topic note should contain:

- What
- Why
- How
- Mental Model
- Architecture (when applicable)
- Trade-offs
- Failure Modes
- Production
- When to Use
- When Not to Use
- Interview Questions

`docs/PROGRESS_STATE.md` may set `notes_completed: true` only after the required notes actually exist.
