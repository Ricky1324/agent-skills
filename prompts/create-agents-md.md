# Create a Project-Level AGENTS.md

Create a project-level `AGENTS.md` for the current repository.

Its purpose is to provide stable, long-lived project context for future Agent conversations. A new agent should be able to read it, understand the project quickly, and determine which repository files to read next for its specific task.

## Investigate before writing

Do not infer the project from a small number of files. Inspect the repository thoroughly enough to ground every statement in evidence. Start with the README and other root-level documentation, project structure, configuration, and recent history. Then inspect the relevant core source code, tests, implementation plans, and other documents as needed to understand the project.

Prioritise canonical sources over summaries. Do not assume a feature, file, command, dependency, architecture, metric, experiment result, or project status that the repository does not support.

## What AGENTS.md should provide

Keep `AGENTS.md` concise and navigation-focused rather than turning it into a project report. Where detailed information already exists, direct future agents to the canonical file instead of duplicating it.

Include only repository-supported information that helps future agents understand:

- what the project is and the problem it addresses;
- the high-level architecture, main modules, and important directories or files and their responsibilities;
- core data flows or pipelines, where applicable;
- primary technologies and dependencies;
- established design decisions and constraints;
- testing and evaluation approaches;
- development conventions and workflows that agents should follow when making changes; and
- which files to read next for development, testing, debugging, documentation, project-summary, or resume-related tasks.

Separate stable project context from temporary development progress. Include current status only when it is stable enough to remain useful; otherwise point to the appropriate source of truth.

If important context is available only in the conversation and cannot be verified from the repository, report it separately. Do not write it into `AGENTS.md` as fact.

## Required review before editing

Before creating or modifying `AGENTS.md`, first provide:

1. a concise summary of your repository-backed understanding of the project;
2. the proposed `AGENTS.md` outline;
3. important documentation gaps you found;
4. a recommendation on whether additional documents such as `PROJECT_CONTEXT.md`, `ARCHITECTURE.md`, `PROGRESS.md`, or `EVALUATION.md` are genuinely needed.

Do not create additional documentation merely for completeness. Prefer improving navigation to existing canonical sources. Wait for explicit approval of the proposed structure before editing `AGENTS.md`.
