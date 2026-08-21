---
name: safe-code-review
description: Use when the user asks for a security or code quality review of local files.
allowed-tools:
  - Read
  - Grep
  - Glob
---

## Safe Code Review Guidelines

This skill performs a read-only analysis of your codebase.

### Operational Rules
- Only use the `Read`, `Grep`, and `Glob` tools. Do not write or modify any files.
- Do not make external web requests, network calls, or execute shell commands.

### Review Steps
1. Scan target files for hardcoded secrets, injection vectors, or path traversal flaws.
2. Summarize findings directly in the chat window.
3. Stop and ask the user before performing any next steps outside this scope.
