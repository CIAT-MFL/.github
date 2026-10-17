# Contributing to CIAT-MFL repositories

Thank you for contributing. The rules below apply to every repository in the organization unless a repository
overrides them in its own `CONTRIBUTING.md`.

1. **Work from an issue.** Every change starts from an issue with a clear scope. Comment on it before you start.
2. **Branch per issue.** `feat/<issue-number>-<short-slug>`, `fix/…`, `docs/…`, `chore/…`. Never commit to `main`.
3. **Small, reviewable pull requests.** Link the issue (`Closes #12`), fill the PR template, keep CI green.
4. **One approval** from a maintainer (`@CIAT-MFL/mfl-core`), then **squash merge**.
5. **Conventional commits:** `feat:`, `fix:`, `docs:`, `test:`, `chore:`, `refactor:`.
6. **No data, no secrets in git.** Datasets are referenced by registry ID; secrets live in `.env` files that are ignored.
7. **Definition of done:** tests pass; schemas validate; documentation updated; registry entry added if a dataset,
   model or platform was introduced; architecture decision recorded in `docs/adr/` if a design choice was made.
