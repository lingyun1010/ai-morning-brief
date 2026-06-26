# Future Agent Architecture

The future Lingyun AI Morning Brief agent should convert this documentation-first workflow into a scheduled, verifiable automation.

## Pipeline

```text
scheduler
  -> research collectors
  -> LLM brief generator
  -> HTML renderer
  -> verifier
  -> Gmail sender
  -> Notion writer
  -> Slack sender
```

## Components

### Scheduler

Runs the workflow daily at the chosen morning time. It should support local development and hosted deployment.

### Research Collectors

Collect candidate sources from:

- AI company announcements
- News feeds
- GitHub repositories and releases
- Product Hunt and Hacker News
- Builder posts and demos
- Job-market and company sources

Collectors should preserve original URLs, titles, timestamps, and source type.

### LLM Brief Generator

Uses the production prompt and collected sources to generate the structured brief.

The generator should output:

- Structured content object
- Source list
- Gmail-ready content blocks
- Notion-ready content blocks
- Slack summary

### HTML Renderer

Takes structured content and renders it into the Gmail HTML template.

The renderer should avoid Markdown and keep CSS inline.

### Verifier

Checks the generated output against the pre-send checklist.

The verifier should block sending if required modules, sections, sources, or rendering rules fail.

### Gmail Sender

Sends the verified HTML email using a Gmail API or approved mail provider.

### Notion Writer

Creates the daily Notion archive page with the full brief, sources, and tags.

### Slack Sender

Sends a concise daily digest to the target Slack channel.

## Design Principle

Start with simple, inspectable components. The first real agent should prioritise reliability, source traceability, and clear failure states over complex orchestration.
