# Git Workflow

## Branch strategy
- `main`: production-ready code
- `release`: integration and release prep
- `feature/<name>`: feature and fix work

## Commit convention
Use [Conventional Commits](https://www.conventionalcommits.org/):

```text
<type>[optional scope]: <description>
```

Examples:
- `feat(api): add historical cache endpoint`
- `fix(backtest): correct drawdown calculation`
- `docs(readme): improve setup guidance`

## Workflow process
1. Create a feature branch from `main`
2. Make small, atomic commits
3. Open a PR into `release` (or `main`, based on team flow)
4. Validate tests and docs updates
5. Merge and tag a release when needed

## Versioning
Use [Semantic Versioning](https://semver.org/):
- MAJOR for incompatible API changes
- MINOR for backward-compatible features
- PATCH for backward-compatible fixes

## Release notes
For each release include:
- version and date
- summary of changes
- features and fixes
- breaking changes (if any)
- contributors
