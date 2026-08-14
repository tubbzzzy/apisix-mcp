Contributing to apisix-mcp

Thanks for your interest in contributing. This document explains how to get started, coding standards, testing, and PR etiquette.

Getting started

1. Fork the repository and clone your fork.
2. Create a feature branch: git checkout -b myfeature
3. Keep changes small and focused. One logical change per PR.

Development

- Use Node 18 and pnpm 8. Install deps: pnpm install
- Build: pnpm build
- Lint: pnpm lint
- Run tests: pnpm test (if present)

Testing & CI

- The repo has CI workflows for Node build and optional email integration. Ensure tests pass locally before opening a PR.

Commit messages & PRs

- Use clear, imperative commit messages e.g., "Add Node CI workflow".
- Include a short description of the why and the what in the PR body.

Code style

- Use the project's ESLint rules. Run pnpm lint to auto-fix where possible.

Reporting issues & security

- Create an issue describing the problem and steps to reproduce.
- For security issues, see SECURITY.md.
