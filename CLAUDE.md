# CLAUDE.md

Guidance for Claude Code (and any AI assistant) working in the **prompt-ai-guide**
repository.

## What this repo is

`prompt-ai-guide` is an AI-agnostic template for lightweight prompt + context
management — the `prompt.ai/` workflow. This is the **template source**: keep
tracked files clean and reusable so downstream projects can adopt them directly.

## Working conventions

- **Keep the template files clean.** Don't append project- or session-specific
  history to tracked files.
  - Put guidance and findings in `prompt.ai/research/`.
  - Local, throwaway notes go in `prompt.ai/session_notes.local.md` (gitignored) —
    never commit them.
  - Do **not** add session history to `prompt.ai/development_log.md` in this
    template repo. Downstream project repos enable that (see
    `prompt.ai/git_workflow.md`).
  - For releases, create `prompt.ai/vX.Y.Z_release_summary.md` from
    `release_summary_template.md`.
- **Update docs alongside changes.** When you change behavior, update the related
  documentation in the same change.

## Git & commits

Follow the process in `prompt.ai/git_workflow.md`. Commits use
**Conventional Commits**:

```text
<type>[optional scope]: <description>
```

Types: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`, `ci`, `build`,
`perf`, `style`.

- Keep commits atomic and focused — no unrelated changes in one commit.
- Write clear, intentional commit messages.
- **Never add AI-authorship attribution.** No `Co-Authored-By:` trailers, no
  "Generated with …" or "🤖" lines — in any commit message, PR body, issue, or
  comment. Commits are authored solely by the human committer. This rule is
  standing and non-negotiable.

## Secrets

Never commit secrets. This repo's `.vault.toml` holds only key *names* — values
resolve at runtime via the vault and never touch disk. Never put secret values,
tokens, or passwords in tracked files.
