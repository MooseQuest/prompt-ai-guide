# Contributing

Thanks for contributing.

## Workflow files

This template uses:
- `prompt.ai/development_log.md` as template baseline content
- `prompt.ai/git_workflow.md` for branching, commit, and release process
- `prompt.ai/research/README.md` for LLM-guided research artifacts
- `prompt.ai/session_notes.template.md` as local scratchpad template
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
- If using LLM research/guidance, add or update a file in `prompt.ai/research/`
- Keep session scratch notes in `prompt.ai/session_notes.local.md` (untracked)

## Template mode for this repo

- Keep `prompt.ai/development_log.md` template-clean
- Do not commit `prompt.ai/session_notes.local.md`
- Move lasting insights into `prompt.ai/research/`
- In downstream project repos, remove `prompt.ai/TEMPLATE_MODE` to re-enable project-mode log updates
