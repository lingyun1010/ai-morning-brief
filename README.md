# Lingyun AI Morning Brief

This repository is the source-of-truth specification for Lingyun Zhao's daily **Lingyun AI Morning Brief** automation.

The brief is designed for a software engineer / big data engineer transitioning into an AI Engineer role. It turns daily AI news, builder activity, open-source projects, job-market signals, and practical learning opportunities into a structured morning briefing that can be delivered through Gmail, Notion, and Slack.

## Why This Exists

ChatGPT Tasks can run the daily workflow, but they currently cannot directly import prompt files or specifications from GitHub. This repository therefore exists for:

- Version control of the production prompt
- Clear documentation of the brief structure and delivery rules
- Manual copy/paste into the ChatGPT Task prompt
- Future migration into a real scheduled AI Morning Brief agent
- Portfolio evidence of practical AI product and automation design

## Current Workflow

1. Edit the prompt, specs, template, or examples in this repository.
2. Review the pre-send verification checklist.
3. Copy the latest production prompt from [`prompts/morning-brief-v2-production.md`](prompts/morning-brief-v2-production.md).
4. Paste it into the ChatGPT Task configuration.
5. Use the task output to send the daily Gmail, Notion update, and Slack summary.

## Future Workflow

The future version will be a real scheduled agent:

`scheduler -> research collectors -> LLM brief generator -> HTML renderer -> verifier -> Gmail sender -> Notion writer -> Slack sender`

The future implementation plan lives in [`future-agent/implementation-roadmap.md`](future-agent/implementation-roadmap.md).

## Delivery Channels

- **Gmail:** Rich mobile-friendly HTML newsletter
- **Notion:** Structured archive and searchable daily knowledge base
- **Slack:** Concise daily digest for quick scanning

## Main Brief Sections

1. Executive Summary
2. Top AI News
3. Builder Spotlight
4. Daily AI Builder Gallery
5. Open Source Radar
6. AI Engineering Insight
7. AI Job Market Signals
8. Opportunities for Lingyun
9. Content Ideas
10. Today's 1-Hour Action

The Hero and Market Note modules sit above the numbered sections.

## Repository Structure

```text
ai-morning-brief/
├── README.md
├── prompts/
├── templates/
├── specs/
├── examples/
└── future-agent/
```

## Practical Principle

Keep the repository useful now, not only theoretically complete. The prompt should be copy/paste friendly, the specs should explain the intended behaviour, and the future-agent notes should be detailed enough to support implementation without over-engineering.
