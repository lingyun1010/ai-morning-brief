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

## CSS

- Inline CSS only
- No external stylesheets
- No web fonts
- No JavaScript
- Avoid complex layout techniques that Gmail may strip

## Required Modules

- Preheader
- Hero
- Market Note
- Sections 1-10
- Sources
- Footer/status note

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
