# prompt-ai-guide

Reusable open-source starter kit for `prompt.ai` workflow + Cursor rules.

![Typing demo](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&pause=900&width=1000&lines=You%3A+Fetch+and+analyze+prompt-ai-guide;AI%3A+Creating+prompt.ai%2Fdevelopment_log.md;AI%3A+Creating+prompt.ai%2Fgit_workflow.md;AI%3A+Creating+.cursor%2Frules%2Fprompt-ai.mdc;AI%3A+Updating+README.md+and+CONTRIBUTING.md;Done%3A+Workflow+installed)

If animation does not render in your client, use the static transcript below.

## Demo: Prompt -> Agent Response

The snippet below shows the intended experience: you paste one instruction, and
the agent scaffolds the workflow files.

```text
You: "Fetch and analyze https://github.com/MooseQuest/prompt-ai-guide.
Then implement the same prompt.ai workflow in this project."

AI Agent:
> Reading repository structure...
> Creating prompt.ai/development_log.md
> Creating prompt.ai/git_workflow.md
> Creating .cursor/rules/prompt-ai.mdc
> Creating .cursor/rules/git-commit.mdc
> Creating prompt.ai/research/README.md
> Updating README.md and CONTRIBUTING.md references
> Logging all changes in prompt.ai/development_log.md
Done. Workflow installed.
```

### Assistant style examples (tab-like)

GitHub README does not support real tabs, so this uses collapsible sections to
emulate ChatGPT/Claude variants.

<details open>
  <summary><strong>ChatGPT-style prompt</strong></summary>

```text
Fetch and analyze this repository first:
https://github.com/MooseQuest/prompt-ai-guide

Then implement the same prompt.ai workflow in my project.

Requirements:
- Create prompt.ai/development_log.md and prompt.ai/git_workflow.md
- Create .cursor/rules/prompt-ai.mdc and .cursor/rules/git-commit.mdc
- Add prompt.ai/research/README.md for LLM-generated guidance artifacts
- Update README.md and CONTRIBUTING.md to reference these files
- Log all changes in prompt.ai/development_log.md
```
</details>

<details>
  <summary><strong>Claude-style prompt</strong></summary>

```text
Please review and apply the prompt-ai-guide pattern from:
https://github.com/MooseQuest/prompt-ai-guide

Set up the same structure in this repository:
1) prompt.ai/development_log.md
2) prompt.ai/git_workflow.md
3) .cursor/rules/prompt-ai.mdc
4) .cursor/rules/git-commit.mdc
5) prompt.ai/research/README.md

Also update README/CONTRIBUTING references and record the setup in
prompt.ai/development_log.md.
```
</details>

## What this gives you

- `prompt.ai` folder for development logs and release summaries
- `prompt.ai/research` for LLM-generated guidance and analysis artifacts
- `.cursor/rules` guidance for consistent AI-assisted workflows
- Starter `git_workflow.md` using Conventional Commits + SemVer
- Baseline open-source repo files (`LICENSE`, `CONTRIBUTING.md`)
- Community governance files (`CODE_OF_CONDUCT.md`, `SECURITY.md`)

## Quick start

1. Clone this repo or copy these files into your project.
2. Keep the `.cursor/rules` files in your project root.
3. Update `prompt.ai/development_log.md` as tasks are completed.
4. Follow `prompt.ai/git_workflow.md` when creating branches/commits/releases.
5. Tell your AI agent: "Read this repository and implement the `prompt.ai` workflow in this project."

### Copy-paste starter prompt

```text
Fetch and analyze this GitHub repository first:
https://github.com/MooseQuest/prompt-ai-guide

If this repo was forked, use the current fork URL instead of the original.

Then implement the same `prompt.ai` workflow in my project.

Requirements:
- Create `prompt.ai/development_log.md` and `prompt.ai/git_workflow.md`
- Create `.cursor/rules/prompt-ai.mdc` and `.cursor/rules/git-commit.mdc`
- Add `prompt.ai/research/README.md` for LLM-generated guidance artifacts
- Update `README.md` and `CONTRIBUTING.md` to reference these workflow files
- Log your changes in `prompt.ai/development_log.md`
```

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
    research/
      README.md
  CONTRIBUTING.md
  CODE_OF_CONDUCT.md
  LICENSE
  SECURITY.md
  README.md
```

## Using this in another repo

Copy `.cursor/rules/*` and `prompt.ai/*` into your target repository.

Then tailor:
- branch names in `prompt.ai/git_workflow.md`
- docs links in `CONTRIBUTING.md`
- release process details for your team
- research conventions in `prompt.ai/research/README.md`

## Research artifacts

Store LLM-generated guidance for agents in `prompt.ai/research/`.

Use this when you need to capture:
- prompt experiments and outputs
- strategy notes for agent execution
- technical trade-offs from model-assisted research

## Community and security

- Community standards: see `CODE_OF_CONDUCT.md`
- Vulnerability reporting process: see `SECURITY.md`

## License

MIT - see `LICENSE`.
