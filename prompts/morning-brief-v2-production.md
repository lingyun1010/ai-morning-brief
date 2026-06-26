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

Use exactly this title, subject, and page title format:

**🧠 Lingyun AI Morning Brief — YYYY-MM-DD**

Do not add suffixes unless explicitly requested for a test resend.

The Gmail and Notion versions must include the Hero module, exactly these 10 numbered sections, and a small Market Note card immediately after the Executive Summary. Each numbered section must appear once.

### Hero Module

Include:

- A dynamic daily headline
- Date
- Short editorial deck
- 1 visual placeholder or relevant image slot
- Clear positioning as Lingyun's AI Morning Brief

### 1. Executive Summary

For the Gmail version, write this as a 120-180 word editorial summary.

It must include:

- Today's strongest AI industry signal
- Why that signal matters for AI Engineer / Applied AI Engineer roles
- One practical takeaway for Lingyun

Prioritise decisions, launches, technical shifts, builder trends, and job-market signals. Keep it concise and specific.

### Market Note Module

Place this as a small card immediately after the Executive Summary.

It must include:

- GBP → AUD exchange rate
- GBP → CNY exchange rate
- As-of time if available
- The phrase "Indicative only"

Do not replace this with a generic market/product note. The Market Note is for exchange-rate context, not AI industry commentary.

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

Include exactly 3 visual cards:

1. Feature to build
2. Improvement to an existing project
3. Portfolio/GitHub/LinkedIn idea

Each card must include:

- Signal observed today
- Opportunity
- Suggested action
- Why it helps the job transition

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

Gmail MUST be sent using `html_body` or `content_type='text/html'`. Never send raw HTML through a normal Markdown body. Include a short plain text fallback in `body`.

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
- Title using exactly `🧠 Lingyun AI Morning Brief — YYYY-MM-DD`
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

Before Gmail, Notion, and Slack delivery, verify:

- Gmail uses `html_body` or `content_type='text/html'`.
- Raw HTML is never sent through a normal Markdown body.
- A short plain text fallback exists in `body`.
- HTML contains no Markdown syntax.
- Title, email subject, and Notion page title use exactly `🧠 Lingyun AI Morning Brief — YYYY-MM-DD`.
- Hero exists.
- Dynamic daily headline exists.
- Executive Summary exists.
- Gmail Executive Summary is 120-180 words and includes today's strongest AI industry signal, why it matters for AI Engineer / Applied AI Engineer roles, and one practical takeaway for Lingyun.
- Market Note exists as a small card after Executive Summary.
- Market Note includes GBP → AUD, GBP → CNY, as-of time if available, and "Indicative only".
- Sections 1-10 exist exactly once.
- LinkedIn and X ideas are separate cards.
- Builder Spotlight contains external builders/products.
- Section 4 contains exactly 5 real published projects with original source links.
- Opportunities for Lingyun contains exactly 3 visual cards: Feature to build, Improvement to an existing project, and Portfolio/GitHub/LinkedIn idea.
- Each Opportunities card includes signal observed today, opportunity, suggested action, and why it helps the job transition.
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
