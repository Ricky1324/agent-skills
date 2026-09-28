# Agent Skills & Prompts

This is a collection of reusable, practice-tested workflows for AI coding agents. It is intentionally small and will grow as workflows become stable enough to reuse.

## Structure

```text
agent-skills/
├── AGENTS.md
├── README.md
├── skills/
│   └── sync-project-context/  # Planned
└── prompts/
    ├── create-agents-md.md     # English
    └── create-agents-md-zh.md  # Chinese
```

## Skills and prompts

- A **prompt** is a reusable task instruction. It is useful in repeated situations but does not yet need a full workflow wrapper.
- A **skill** is a stable workflow with clear trigger conditions, steps, constraints, and a way to verify its result.

Use a prompt by adapting its instructions to the repository and task at hand. Add a skill only after its workflow has been used and validated enough to be repeatable.

## Getting started

Read `AGENTS.md` for the repository context and task-based navigation. Use this README for the collection's purpose and content model.

## Current contents

- `AGENTS.md` provides repository context and points agents to the files relevant to their task.
- `prompts/create-agents-md.md` is the English prompt for analysing an existing repository and creating a concise, navigation-focused project-level `AGENTS.md`.
- `prompts/create-agents-md-zh.md` is its Chinese counterpart for the same task.
- `skills/sync-project-context/` is reserved for a future skill that reviews whether `AGENTS.md` and related project documentation still match significant repository changes.
