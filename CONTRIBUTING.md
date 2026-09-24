# Contributing to StepFi

Thanks for your interest in contributing. This is the **organization-wide** guide for every
[StepFi-app](https://github.com/StepFi-app) repository. Individual repositories may add their own
`CONTRIBUTING` guide and a **required pull request template** — when they do, those take precedence
and you must follow them exactly.

## Repositories

| Repo | Stack | Scope |
|------|-------|-------|
| [StepFi-Contracts](https://github.com/StepFi-app/StepFi-Contracts) | Soroban / Rust | On-chain smart contracts only |
| [StepFi-API](https://github.com/StepFi-app/StepFi-API) | NestJS / Supabase | Backend API and services |
| [StepFi-Web](https://github.com/StepFi-app/StepFi-Web) | React / Vite | Web frontend |
| [StepFi-App](https://github.com/StepFi-app/StepFi-App) | Expo / React Native | Mobile app |
| [StepFi-Docs](https://github.com/StepFi-app/StepFi-Docs) | Docs | Product & developer documentation |

**Put changes in the right repo.** A PR that adds frontend code to the contracts repo (or vice versa)
will be closed. Check the target repository's PR template if you are unsure.

## Workflow

1. **Find or open an issue.** Discuss non-trivial changes before writing code. Comment on the issue to get it assigned before you start, so work is not duplicated.
2. **Branch** from the default branch using a descriptive name: `feat/…`, `fix/…`, `chore/…`, `docs/…`, `refactor/…`.
3. **Make focused commits.** One logical change per commit. Use [Conventional Commits](https://www.conventionalcommits.org/): `type(scope): description`.
4. **Test.** Add or update tests for every behavior change or bug fix. Do not lower existing coverage.
5. **Run the checks locally.** Build, test, lint, and format must all pass before you open a PR.
6. **Open a pull request** against the default branch. Fill out the repository's PR template completely and link the issue with `Closes #<number>`.

## Pull request expectations

- Keep PRs small and reviewable. Split large work into stages.
- CI must be green. **PRs with failing checks will be closed without review.**
- Do not merge your own PR without an approving review.
- Resolve review threads rather than deleting them.

## Code quality

- Handle errors explicitly; never silently swallow them.
- Validate all external input at the boundary.
- No hardcoded secrets — use environment variables or a secret manager.
- Prefer small, focused files and functions.
- Match the style and conventions of the surrounding code.

## Reporting security issues

Never open a public issue for a vulnerability. Follow the [Security Policy](./SECURITY.md).

## Code of Conduct

By participating, you agree to uphold our [Code of Conduct](./CODE_OF_CONDUCT.md).
