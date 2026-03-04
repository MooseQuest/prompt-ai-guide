# Contributing

Thanks for contributing.

## Workflow files

This template uses:
- `prompt.ai/development_log.md` for ongoing work logs
- `prompt.ai/git_workflow.md` for branching, commit, and release process
- `prompt.ai/research/README.md` for LLM-guided research artifacts
- `.cursor/rules/*.mdc` to guide AI-assisted coding behavior

## Commit format

Use Conventional Commits:

```text
<type>[optional scope]: <description>
```

Examples:
- `feat(api): add cache controls endpoint`
- `fix(ui): handle empty chart payload`
- `docs(readme): clarify setup steps`

## Pull requests

- Keep PRs focused and scoped
- Include test evidence (if applicable)
- Update docs for behavior changes
- Add an entry to `prompt.ai/development_log.md`
- If using LLM research/guidance, add or update a file in `prompt.ai/research/`

## Template hygiene for this repo

- For PRs into `main`, keep `prompt.ai/development_log.md` template-clean
- `prompt.ai/development_log.md` must match `prompt.ai/development_log.template.md`
- CI enforces this rule in `.github/workflows/template-hygiene.yml`
