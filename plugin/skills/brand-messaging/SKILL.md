---
name: brand-messaging
description: >
  Enforces social.plus brand messaging consistency across all content Claude produces.
  Use this skill whenever writing marketing copy, social media posts, ad copy, email campaigns,
  landing page text, blog posts, press releases, pitch materials, sales enablement content,
  website copy, product descriptions, investor communications, or any content representing
  the social.plus brand. Also trigger when reviewing or auditing existing content against
  brand guidelines, when someone asks about brand voice, tone, approved terminology,
  messaging frameworks, value propositions, competitive positioning, boilerplates, or
  elevator pitches. Trigger even for short tasks like writing a subject line or tagline.
  If the output will carry the social.plus name, use this skill.
---

# social.plus Brand Messaging

This skill ensures all social.plus content aligns with official brand messaging. The source of truth lives on GitHub and must be fetched fresh every time.

## What to do

1. Fetch the router file using WebFetch:

```
https://github.com/socialplus-tools/claude-skills/blob/main/core-messaging/brain.md
```

2. Follow its instructions. It tells you which additional files to fetch based on the user's task.

That's it. Everything else — routing logic, rules, file references — lives in `brain.md` on GitHub so it can be updated without redistributing this plugin.
