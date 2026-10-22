# Contributing

## Branches
`feat/<short-name>`, `fix/<short-name>`, `chore/<short-name>`. Never commit straight to `main`.

## Commits
[Conventional commits](https://www.conventionalcommits.org): `feat: add login`, `fix: crash on empty save`.

## Pull requests
Fill in the template, keep PRs small, squash merge.

## Open by default
Any Bodring repo may become public at any time, with its full history. So:
- Never commit keys, tokens, passwords or `.env` files. Use GitHub Secrets or a local `.env` that git ignores.
- No customer or personal data in repos, issues or screenshots.
- Business documents (finance, contracts, strategy) live in the private `hq` repo only.
- Every repo runs a secret scan on each push. If it flags a real key, rotate the key first, then remove it.
