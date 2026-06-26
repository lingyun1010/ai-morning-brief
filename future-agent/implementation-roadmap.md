# Implementation Roadmap

## Phase 0: Documentation Source Of Truth

Status: current phase.

Goals:

- Maintain production prompt in version control.
- Document section rules, source strategy, rendering requirements, and delivery channels.
- Keep examples and checklist copy/paste friendly.

## Phase 1: Static HTML Renderer

Build a small script that takes structured sample content and renders `templates/gmail-html-template.html`.

Outputs:

- Rendered HTML file
- Local preview file
- Basic placeholder substitution

## Phase 2: Source Collector

Add source collection from a small number of reliable inputs.

Initial sources:

- RSS feeds or official blogs
- GitHub repository search/releases
- Product Hunt or Hacker News
- Manual source list file

Outputs:

- Normalised source JSON
- Source type labels
- Deduped URL list

## Phase 3: Verification Script

Implement automated checks for the pre-send checklist.

Checks:

- Required modules exist
- Sections 1-10 exist exactly once
- Section 4 has exactly 5 project entries
- Source diversity minimums are met
- HTML contains no Markdown syntax
- Inline CSS only

## Phase 4: Gmail Sender

Add Gmail delivery after verification passes.

Requirements:

- Send only verified HTML
- Support dry-run mode
- Store send status
- Never send if verification fails

## Phase 5: Notion/Slack Integration

Add secondary delivery channels.

Notion:

- Create one page per brief
- Store sources and tags
- Link back to generated HTML or source data

Slack:

- Send headline, summary, top links, and 1-hour action
- Include Notion link when available

## Phase 6: Scheduler/Deployment

Deploy as a scheduled workflow.

Options:

- GitHub Actions
- Local cron
- Cloud scheduler
- Lightweight serverless function

Requirements:

- Clear logs
- Failure notifications
- Manual rerun path

## Phase 7: Portfolio Polish

Turn the project into a presentable AI Engineer portfolio project.

Add:

- Architecture diagram
- Example rendered brief
- Verification screenshots or logs
- Clear README demo flow
- Notes on trade-offs, safety, and reliability
