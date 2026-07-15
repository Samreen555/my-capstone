# CLAUDE.md

Guidance for Claude Code (or any AI assistant) working in this repository.

## Project Overview
[1-2 sentences: what this capstone project is and who it's for.]

## Stack
- Language:
- Framework:
- Package manager:
- Testing:
- Deployment target:

## Conventions
- **Commits:** Follow [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/)
  (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`, etc.)
- **Branching:** `main` is always deployable; feature work happens on `feat/*` branches.
- **Code style:** [linter/formatter, e.g. ESLint + Prettier, or Black]
- **File structure:** [describe key folders once they exist]

## How to Run
```bash
# install
# dev server
# tests
```

## What the AI Assistant Should Do
- Prefer small, focused commits over large ones.
- Explain non-obvious changes in the commit body, not just the subject line.
- Ask before adding new dependencies.
- Never commit secrets, `.env` files, or credentials.

## What the AI Assistant Should Avoid
- Don't rewrite existing history on `main`.
- Don't introduce new frameworks without discussion.
