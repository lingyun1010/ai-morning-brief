# Pre-Send Verification Checklist

Run this checklist before Gmail, Notion, and Slack delivery.

If any check fails: **DO NOT SEND; regenerate the failed part first.**

## Naming

- [ ] Title, email subject, and Notion page title use exactly `🧠 Lingyun AI Morning Brief — YYYY-MM-DD`.
- [ ] No suffixes are added unless explicitly requested for a test resend.

## Gmail Transport

- [ ] Gmail uses `html_body` or `content_type='text/html'`.
- [ ] Raw HTML is never sent through a normal Markdown body.
- [ ] A short plain text fallback exists in `body`.
- [ ] HTML contains no Markdown syntax.

## Required Modules

- [ ] Hero exists.
- [ ] Dynamic daily headline exists.
- [ ] Executive Summary exists.
- [ ] Market Note exists.
- [ ] Market Note appears as a small card after Executive Summary.
- [ ] Market Note includes GBP → AUD and GBP → CNY exchange rates.
- [ ] Market Note includes as-of time if available.
- [ ] Market Note includes "Indicative only".
- [ ] Sections 1-10 exist exactly once.

## Content Rules

- [ ] Gmail Executive Summary is 120-180 words.
- [ ] Executive Summary includes today's strongest AI industry signal.
- [ ] Executive Summary explains why the signal matters for AI Engineer / Applied AI Engineer roles.
- [ ] Executive Summary includes one practical takeaway for Lingyun.
- [ ] LinkedIn and X ideas are separate cards.
- [ ] Builder Spotlight contains external builders/products.
- [ ] Section 4 contains exactly 5 real published projects with original source links.
- [ ] Section 4 does not include "Inspiration for Lingyun".
- [ ] Section 4 does not include "Portfolio lesson".
- [ ] Section 4 does not force relevance to Lingyun.
- [ ] Opportunities for Lingyun contains exactly 3 visual cards: Feature to build, Improvement to an existing project, and Portfolio/GitHub/LinkedIn idea.
- [ ] Each Opportunities card includes signal observed today, opportunity, suggested action, and why it helps the job transition.
- [ ] At least 2 authoritative AI/news sources are present.
- [ ] At least 2 builder/product sources are present.
- [ ] At least 2 GitHub/open-source sources are present.
- [ ] At least 1 AI job-market/company source is present.

## Rendering Rules

- [ ] 3-5 visual elements exist.
- [ ] Mobile single-column layout is used.
- [ ] Inline CSS only.

## Final Gate

- [ ] Final manual self-check passed before sending.

If any check fails: **DO NOT SEND; regenerate the failed part first.**
