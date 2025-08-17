# Contributing

I appreciate your interest in contributing. This document lays out practical guidance I use for getting started, reporting issues, proposing improvements, and submitting pull requests.

## Quick start

- If you're an external contributor, fork the repository; if you're on the team, branch from `main`.
- Follow the instructions in `README.md` to install dependencies and configure your environment.
- Please use a focused branch for each task, for example `feat/auth` or `fix/login-bug`.

## Reporting bugs

When filing a bug with me, please include:

- A concise, descriptive title.
- Reproduction steps.
- The expected behavior and what actually happened.
- Environment details (OS, browser, versions) and any relevant logs or error messages.

> [!TIP]
> Check existing issues before creating a new one — the bug may already be reported.

## Suggesting changes or new features

Open an issue that explains:

- The problem you're trying to solve.
- The approach you'd like to take and alternatives you considered.
- Who benefits from the change.

If I ask you to implement the change, please work on a dedicated branch and keep the work scoped to that issue.

## Pull request guidelines

- Reference the related issue in the PR description (for example: "Fixes #123").
- Use a clear title and explain why the change is needed.
- Keep PRs focused and small when possible; split larger work into multiple PRs as appropriate.
- Run tests and linters locally before opening the PR.
- Address any review feedback and update the branch (rebase or merge `main` to stay current).

## Code style & quality

- Follow the repository's existing style. If linters or formatters are configured, run them before committing.
- Favor readable, self-documenting code and add or update tests when introducing new behavior.

### Commit messages

I follow the [Conventional Commits](https://www.conventionalcommits.org/) convention. Please format commits like:

```
type(scope): short description
```

Common types I use: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.

---

_If you need help with setup, consult `README.md`._
