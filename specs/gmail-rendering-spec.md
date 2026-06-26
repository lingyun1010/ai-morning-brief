# Gmail Rendering Spec

The Gmail version is the main user-facing output. It should read like a polished editorial briefing and render cleanly on mobile.

## Layout

- Warm off-white page background
- Centred max-width container around 720px
- Single-column layout
- Clear spacing between modules
- Rounded cards
- Source buttons or clear links
- Separate LinkedIn and X cards
- Hero H1 around 32px
- Section h2 headings around 24-26px
- Card headings around 18-19px

## CSS

- Inline CSS only
- No external stylesheets
- No web fonts
- No JavaScript
- Avoid complex layout techniques that Gmail may strip

## Required Modules

- Preheader
- Hero
- Sections 1-10
- Market Note as a small card immediately after Executive Summary
- Sources
- Footer/status note

## Gmail Sending

- Send using `html_body` or `content_type='text/html'`.
- Never send raw HTML through a normal Markdown body.
- Include a short plain text fallback in `body`.

## Visual Elements

Include 3-5 visual elements, such as:

- Hero image placeholder
- News visual placeholder
- Builder gallery visual placeholder
- Action visual placeholder
- Small source/link button row

Visuals may be placeholders if no image assets are available.

## HTML Quality Bar

Before sending:

- No Markdown syntax remains in the HTML body.
- Headings are real HTML headings.
- Lists are HTML lists or clean paragraph blocks.
- Links are real `<a>` tags.
- Section numbers appear exactly once.
- Mobile layout remains single column.
