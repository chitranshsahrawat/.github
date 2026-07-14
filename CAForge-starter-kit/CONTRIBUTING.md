# Contributing

Thanks for contributing! Please follow this workflow to keep things consistent.

## Branching

- `main` — always stable, deployable
- `feature/<short-name>` — new features (e.g. `feature/auth`)
- `fix/<short-name>` — bug fixes (e.g. `fix/login-crash`)

Never commit directly to `main`.

## Workflow

1. Create a branch off `main`
2. Make your changes, with clear commit messages (see below)
3. Push your branch and open a Pull Request
4. Fill out the PR template — link the related issue
5. Wait for at least one review/approval before merging
6. Squash-merge into `main` once approved

## Commit Message Style

Use short, present-tense messages, ideally following [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: add JWT-based authentication
fix: correct off-by-one error in pagination
docs: update setup instructions in README
refactor: simplify distance estimation logic
```

## Versioning

Once a project reaches a working milestone, tag a release using [semantic versioning](https://semver.org/):

- `v1.0.0` — first stable/working version
- `v1.1.0` — new backwards-compatible feature added
- `v1.0.1` — bug fix, no new features

## Code Review

- Be respectful and specific in review comments
- Suggest changes rather than just pointing out problems
- It's fine to ask questions instead of assuming intent
