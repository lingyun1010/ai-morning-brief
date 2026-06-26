# Lingyun AI Morning Brief - Production Prompt v2

## Mission

Create and deliver today's **Lingyun AI Morning Brief**: a practical, source-backed daily AI briefing for Lingyun Zhao, a software engineer / big data engineer transitioning into an AI Engineer role.

The brief must help Lingyun:

- Understand the most important AI news and product movement.
- Discover what builders are actually shipping.
- Track open-source AI engineering tools.
- Notice job-market and company hiring signals.
- Identify useful learning, portfolio, and content opportunities.
- Take one concrete 1-hour action today.

## Audience Context

Write for Lingyun Zhao:

- Based in Australia with an international AI career focus.
- Transitioning from software engineering and big data engineering into AI engineering.
- Interested in AI agents, RAG, evaluation, LLM apps, automation, prompt engineering, data pipelines, and practical AI products.
- Building a public portfolio and content presence across LinkedIn and X.

Use British/Australian English. Keep the tone editorial, useful, concise, and practical. Avoid hype unless there is clear evidence.

## Research Requirements

Research today's AI ecosystem before writing. Prioritise recent and primary sources.

Use sources across:

- Official AI company blogs and release notes
- Model provider announcements
- GitHub repositories and release pages
- Hacker News, Product Hunt, X/Twitter, YouTube demos, personal blogs, and official demo pages
- Reputable technology and AI news publications
- AI engineering blogs and technical write-ups
- Job boards, company career pages, funding announcements, and hiring posts

Prefer items published, released, or actively discussed in the last 7 days. If an older item is included, explain why it matters today.

## Notion Project-Context Requirements

If Notion context is available, check Lingyun's relevant project notes before finalising the brief. Look for:

- Current AI portfolio projects
- Active learning goals
- Content plans
- Job-search priorities
- Recently captured ideas or tasks

Use this context only where it genuinely improves relevance. Do not force every item to connect to Lingyun's work.

If Notion is unavailable, continue with the brief and state in the final status that Notion context was not available.

## Source Diversity Rules

The final brief must include:

- At least 2 authoritative AI/news sources
- At least 2 builder/product sources
- At least 2 GitHub or open-source sources
- At least 1 AI job-market, hiring, funding, or company source
- Original source links wherever possible
- Clear source buttons or links in the Gmail HTML

Do not rely on a single publication, platform, or social feed.

## Exact Content Structure

The Gmail and Notion versions must include the Hero and Market Note modules, then exactly these 10 numbered sections, each appearing once:

### Hero Module

Include:

- A dynamic daily headline
- Date
- Short editorial deck
- 1 visual placeholder or relevant image slot
- Clear positioning as Lingyun's AI Morning Brief

### Market Note Module

Include:

- A short "what changed overnight" market/product note
- 2-4 signals from research
- Why the signal matters to AI builders or job seekers

### 1. Executive Summary

Summarise the day in 4-6 bullets. Prioritise decisions, launches, technical shifts, builder trends, and job-market signals.

### 2. Top AI News

Include 3-5 important AI news items. Each item must include:

- Headline
- 2-3 sentence summary
- Why it matters
- Source link

### 3. Builder Spotlight

Feature external builders, teams, or products. This section must not become a personal productivity note. Include:

- Who built it
- What they shipped
- Link to demo, post, product, or repo
- Why it is interesting for AI builders

### 4. Daily AI Builder Gallery

Also acceptable title: **Cool AI Projects / Fun AI Apps**.

Include exactly 5 real, already-published external AI apps, projects, demos, workflows, agents, tools, or experiments.

Rules:

- Prioritise projects released or actively discussed in the last 7 days.
- Include original release/demo links such as X/Twitter, GitHub, YouTube, Product Hunt, Hacker News, personal blog, or official site.
- Include optional secondary discussion links only if relevant.
- Include stack/framework if publicly known.
- Explain why people are talking about it.
- Do not include "Inspiration for Lingyun".
- Do not include "Portfolio lesson".
- Do not force relevance to Lingyun's projects.
- This section is for discovering what people are actually building with AI.

Each of the 5 entries must include:

- Project name
- What it does
- Original source/demo link
- Optional discussion link
- Stack/framework if known
- Why people are talking about it

### 5. Open Source Radar

Include 3-5 open-source AI engineering repositories, releases, libraries, or examples. Each item must include:

- Repo/project name
- What changed or why it is notable
- GitHub/source link
- Practical use case

### 6. AI Engineering Insight

Give one practical technical insight for AI engineers. It may cover:

- RAG design
- Agent architecture
- Eval patterns
- Observability
- Prompt/system design
- Data pipelines
- Model routing
- Cost, latency, or reliability trade-offs

Include concrete implementation guidance, not abstract commentary.

### 7. AI Job Market Signals

Include 3-5 signals from AI hiring, company movement, role requirements, or funding. Focus on what an aspiring AI Engineer should notice.

Include at least one source from a company page, job post, funding announcement, or credible labour-market report.

### 8. Opportunities for Lingyun

Include 3-5 practical opportunities for Lingyun, grounded in the day's research where possible:

- Portfolio feature to build
- GitHub repo to study
- Job-search angle
- Networking opportunity
- Skill to practise

Do not over-personalise every news item. Keep this section useful and selective.

### 9. Content Ideas

Create separate cards for:

- LinkedIn ideas
- X ideas

LinkedIn ideas should be thoughtful, career-positioning, and suitable for an AI Engineer transition narrative.

X ideas should be concise, sharper, and more immediately postable.

### 10. Today's 1-Hour Action

Give one concrete 1-hour action with:

- Objective
- Why it matters
- 60-minute breakdown
- Output to produce
- Suggested follow-up

## Gmail HTML Rendering Requirements

Render the Gmail version as complete HTML suitable for sending with `html_body` or `content_type='text/html'`.

Requirements:

- Inline CSS only
- No external CSS
- No Markdown syntax in the HTML body
- Mobile-friendly single-column layout
- Warm off-white background
- Centred container around 720px
- Every.to-inspired editorial style
- Hero section
- Market Note card
- Clean rounded cards
- Source buttons or clear links
- Separate LinkedIn and X cards
- 3-5 visual elements or placeholders
- Clear hierarchy and readable spacing

Before sending, inspect the HTML for stray Markdown such as `#`, `**`, `- [ ]`, or fenced code blocks.

## Notion Delivery Requirements

Create or update a Notion entry for today's brief if Notion is available.

The Notion version should include:

- Date
- Title
- Executive Summary
- All 10 sections
- Source links
- Today's 1-Hour Action
- Tags such as `AI Morning Brief`, `AI Engineering`, `Job Market`, `Builder Gallery`

If Notion delivery fails, continue with Gmail and Slack only, then report the Notion failure in final status.

## Slack Delivery Requirements

Send a concise Slack version if Slack is available.

The Slack version should include:

- Daily headline
- 4-6 bullet executive summary
- Top 3 links
- Today's 1-Hour Action
- Link to Notion page if available

If Slack delivery fails, report it in final status.

## Mandatory Pre-Send Verification Checklist

Before Gmail delivery, verify:

- Gmail uses `html_body` or `content_type='text/html'`.
- HTML contains no Markdown syntax.
- Hero exists.
- Dynamic daily headline exists.
- Executive Summary exists.
- Market Note exists.
- Sections 1-10 exist exactly once.
- LinkedIn and X ideas are separate cards.
- Builder Spotlight contains external builders/products.
- Section 4 contains exactly 5 real published projects with original source links.
- At least 2 authoritative AI/news sources are present.
- At least 2 builder/product sources are present.
- At least 2 GitHub/open-source sources are present.
- At least 1 AI job-market/company source is present.
- 3-5 visual elements exist.
- Mobile single-column layout is used.
- Inline CSS only.
- Final manual self-check passed before sending.

If any check fails: **DO NOT SEND**. Regenerate the failed part first, then run the checklist again.

## Final Status Requirements

After completing the task, report:

- Gmail sent or not sent
- Notion written or skipped/failed
- Slack sent or skipped/failed
- Number of sources used
- Whether Section 4 had exactly 5 projects
- Whether the pre-send checklist passed
- Any missing context or delivery limitations
