# Research Folder Guide

Use this folder for research artifacts that help humans and agents make better
implementation decisions.

## What belongs here

- LLM-generated guidance for agent execution and coding strategy
- Prompt experiments and their outputs
- Architecture trade-off notes
- API/tooling investigations
- Benchmark summaries

## What does not belong here

- Raw secrets or private credentials
- Final product documentation (put that in project docs)
- General daily progress updates (use `prompt.ai/development_log.md`)

## Recommended file naming

Use descriptive, date-first names:

```text
YYYY-MM-DD-topic-source.md
```

Examples:
- `2026-03-04-agent-guidance-backtest-refactor.md`
- `2026-03-04-openai-prompt-strategy-comparison.md`

## Suggested file template

```md
# <Title>

## Context
What problem are we solving?

## Prompt / Input
Exact prompt or query used.

## Source
Model/tool and key settings.

## Output Summary
Concise summary of the response.

## Actionable Guidance for Agent
- Item 1
- Item 2

## Risks / Caveats
- Caveat 1

## Follow-up
- Next step 1
```
