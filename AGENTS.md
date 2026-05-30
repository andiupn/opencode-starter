# Project Rules

This is a general-purpose experimental repository that may contain code in any language or framework.

## Core Rules

1. **Security**: Never commit secrets, keys, tokens, or credentials.
2. **Code Quality**: Follow existing code style. Do not add unnecessary comments.
3. **Testing**: New features must include tests. Follow existing test patterns.
4. **Conventions**: Read surrounding files before creating new ones. Match patterns.
5. **Brevity**: Answer directly without unnecessary explanations.

## External File Loading

When you encounter a file reference (e.g., `@rules/general.md`), use Read to load it on a need-to-know basis. Do NOT preemptively load all references. When loaded, treat content as mandatory instructions.

## Agents

- `@code` — Primary agent for all coding tasks
- `@research` — Explore and understand the codebase
- `@debug` — Diagnose and fix errors
- `@refactor` — Clean up and optimize code
- `@document` — Write documentation (read-only)

### Invocation Workflow

1. `@research` first to understand unknown areas
2. `@code` for implementation
3. `@debug` when tests fail or errors appear
4. `@refactor` after features stabilize
5. `@document` last, after code is final

## Commands

- `/analyze` — Analyze project structure
- `/fix` — Find and fix issues
- `/explain` — Explain code or concepts

## Permissions Model

| Agent | Edit | Bash | Read | Notes |
|-------|------|------|------|-------|
| code | allow | allow | allow | Full access |
| research | deny | git/grep/find/ls | allow | Exploration only |
| debug | deny | git/npm/pip/cargo | allow | Diagnostics only |
| refactor | allow | git diff/status | allow | Code changes only |
| document | deny | deny | allow | Read-only |
