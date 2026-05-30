---
name: coding-conventions
description: Language-agnostic coding conventions and best practices for this experimental repository
---

## Naming
- Functions/variables: `camelCase`
- Classes: `PascalCase`
- Constants: `UPPER_SNAKE_CASE`
- Files: `kebab-case` or `snake_case` (match existing)

## Structure
- One responsibility per module
- Group related files in directories
- Keep functions small and focused
- Prefer pure functions over side effects

## Error Handling
- Return errors, don't throw unless exceptional
- Handle all promise/async rejections
- Validate inputs at module boundaries
- Fail fast with clear messages
