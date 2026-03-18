# social.plus Brand Messaging — Router

This file is the entry point for all social.plus brand-aligned content tasks. It tells you which files to fetch based on what the user needs.

All files are hosted at:
`https://github.com/socialplus-tools/claude-skills/blob/main/core-messaging/`

## How to use this file

1. You fetched this file first. Good.
2. Read the user's request.
3. Match it against the routing table below.
4. Fetch the listed files using WebFetch on the GitHub blob URLs above.
5. Apply everything you fetch. Terminology and tone are non-negotiable.

## Routing table

### Any content task (always fetch these)
- `terminology.md` — Approved and forbidden terms. This is law.
- `tone.md` — Tone of voice and writing style rules.

### Short-form content (social posts, email subject lines, ad copy, taglines, product descriptions)
- `boilerplates.md` — Standardized descriptions and elevator pitches as starting points.

### Long-form content (blog posts, landing pages, thought leadership, whitepapers, case studies, press releases)
- `narrative.md` — Messaging hierarchy and 5-step narrative structure.
- `value-story.md` — Core problems we solve, value creation model, differentiation framework.

### Positioning or identity questions (what is social.plus, who do we serve, what are our pillars)
- `positioning.md` — Company overview, vision, mission, ecosystem position, product pillars.

### Content review or audit (checking existing copy against brand guidelines)
- Fetch ALL files. Compare the content under review against every guideline.

## Rules

- **Terminology is law.** Always use approved terms. Never use forbidden terms. No exceptions.
- **Tone comes from the documents, not from your defaults.** Override your natural writing style with what the tone file specifies.
- **Never invent.** Do not fabricate statistics, customer names, quotes, features, or performance claims. If it's not in the fetched documents, don't state it.
- **Messaging hierarchy matters.** For content longer than a paragraph: establish the market shift → define infrastructure → engagement → intelligence → revenue → long-term advantage.
- **Boilerplates are starting points.** Adapt to context but preserve meaning and claims.
- **If a fetch fails**, tell the user the GitHub content is unavailable and you cannot guarantee brand alignment. Do not proceed with stale or memorized content.

## Available files

| File | Sections | Contains |
|---|---|---|
| `positioning.md` | 1–7 | Company overview, vision, mission, ecosystem position, what we are/aren't, product pillars |
| `value-story.md` | 8–10 | Core problems, value creation model, differentiation framework |
| `terminology.md` | 14–15 | Approved terms, forbidden terms |
| `tone.md` | 16–17 | Tone of voice, writing style rules |
| `narrative.md` | 19–20 | Messaging hierarchy, standard narrative structure |
| `boilerplates.md` | 21–22 | Boilerplates, elevator pitches |
