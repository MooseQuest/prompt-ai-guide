# prompt-ai-guide

Reusable open-source starter kit for `prompt.ai` workflow + Cursor rules.

## What this gives you

- `prompt.ai` folder for development logs and release summaries
- `.cursor/rules` guidance for consistent AI-assisted workflows
- Starter `git_workflow.md` using Conventional Commits + SemVer
- Baseline open-source repo files (`LICENSE`, `CONTRIBUTING.md`)

## Quick start

1. Clone this repo or copy these files into your project.
2. Keep the `.cursor/rules` files in your project root.
3. Update `prompt.ai/development_log.md` as tasks are completed.
4. Follow `prompt.ai/git_workflow.md` when creating branches/commits/releases.

## Folder structure

```text
prompt-ai-guide/
  .cursor/
    rules/
      prompt-ai.mdc
      git-commit.mdc
  prompt.ai/
    development_log.md
    git_workflow.md
    release_summary_template.md
  CONTRIBUTING.md
  LICENSE
  README.md
```

## Using this in another repo

Copy `.cursor/rules/*` and `prompt.ai/*` into your target repository.

Then tailor:
- branch names in `prompt.ai/git_workflow.md`
- docs links in `CONTRIBUTING.md`
- release process details for your team

## License

MIT - see `LICENSE`.
