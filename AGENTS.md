# Project Context for Agents

## Purpose

This repository is a personal collection of reusable, practice-tested workflows for Codex and other AI coding agents. It intentionally remains small and grows when a workflow has become stable enough to reuse.

## Content Model

- `prompts/` contains reusable task instructions that are useful in repeated situations but do not yet need a complete workflow wrapper.
- `skills/` contains stable workflows with clear trigger conditions, steps, constraints, and a way to verify their result.

Do not promote a prompt to a Skill, or create a new Skill, until its workflow is sufficiently designed and validated to be repeatable.

## Repository Map

- `README.md` explains the repository purpose, directory structure, and the distinction between prompts and Skills.
- `prompts/` contains reusable prompts. Read the target prompt before revising it or using its conventions as a pattern.
- `skills/` is reserved for stable Skills. `sync-project-context/` is planned but does not yet contain an implemented `SKILL.md`.
- `LICENSE` contains the repository license.

## Working in This Repository

- Base documentation and repository claims on files that are present and verifiable. Do not invent tools, commands, dependencies, architecture, test results, or project status.
- Keep the repository minimal. Do not add scripts, templates, configuration, reference material, or new documentation merely to fill out a structure.
- Prefer updating the canonical document for a topic instead of duplicating its content elsewhere.
- Keep long-lived repository context separate from short-lived working-tree status. Check Git history and status when current progress matters.

## Task-Based Reading Guide

| Task | Read first | Then inspect as needed |
| --- | --- | --- |
| Orienting to the repository | `README.md`, this file | The relevant `prompts/` or `skills/` directory |
| Creating or revising a prompt | `README.md`, the target file in `prompts/` | Related prompts for established patterns |
| Designing or revising a Skill | `README.md`, the target directory in `skills/` | Existing `SKILL.md` files and any repository-backed workflow evidence |
| Updating project context or documentation | This file, `README.md` | The specific artifact being described and Git history/status when progress matters |
| Testing or debugging | The relevant artifact and the current repository tree | Configuration or test files if they exist; do not assume commands or a test framework |
| Preparing a project summary or resume material | `README.md`, completed prompts and Skills | Git history and the relevant artifact content; distinguish verified repository facts from working notes |

There is currently no repository-documented application code, execution pipeline, dependency manifest, test suite, or evaluation framework. If such material is added, update this file and `README.md` when their navigation guidance or content model changes.
