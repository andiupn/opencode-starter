---
name: testing-patterns
description: Testing patterns and requirements for experimental features in this repository
---

## Discovery
- Check test config files: jest.config.*, vitest.config.*, pytest.ini, Cargo.toml
- Check package.json for test scripts
- Follow existing test framework and patterns

## Requirements
- New features must include tests
- Cover critical paths and error cases
- One assertion concept per test
- Use descriptive test names

## Running
- Find correct command (npm test, pytest, cargo test, go test, etc.)
- Run related tests before and after changes
- Debug failures with @debug agent
