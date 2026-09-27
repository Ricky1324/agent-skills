# Agent Skills & Prompts

This is a personal collection of reusable, practice-tested workflows for Codex and other AI coding agents. It is intentionally small and will grow as workflows become stable enough to reuse.

## Structure

```text
agent-skills/
├── AGENTS.md
├── README.md
├── skills/
│   └── sync-project-context/  # Planned
└── prompts/
    └── create-agents-md.md
```

## Skills and prompts

- A **prompt** is a reusable task instruction. It is useful in repeated situations but does not yet need a full workflow wrapper.
- A **skill** is a stable workflow with clear trigger conditions, steps, constraints, and a way to verify its result.

Use a prompt by adapting its instructions to the repository and task at hand. Add a skill only after its workflow has been used and validated enough to be repeatable.

## Getting started

Read `AGENTS.md` for the repository context and task-based navigation. Use this README for the collection's purpose and content model.

## Current contents

- `AGENTS.md` provides repository context and points agents to the files relevant to their task.
- `prompts/create-agents-md.md` helps analyse an existing repository and create a concise, navigation-focused project-level `AGENTS.md`.
- `skills/sync-project-context/` is reserved for a future skill that reviews whether `AGENTS.md` and related project documentation still match significant repository changes.
