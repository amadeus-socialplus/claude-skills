# social.plus Marketing Plugin

Shared plugin for the social.plus marketing team. Ensures all content Claude produces aligns with the latest brand messaging.

## How it works

This plugin contains a lightweight skill that fetches brand messaging guidelines live from GitHub every time it triggers. The actual content lives at:

https://github.com/socialplus-tools/claude-skills/tree/main/core-messaging

When you ask Claude to write or review any social.plus content, the skill automatically fetches the latest messaging files and applies them.

## Installation

Install the `.plugin` file in Claude Cowork. The plugin works in Cowork and Claude Code (any environment with WebFetch or bash access).

## Updating content

Edit the markdown files in the `core-messaging/` folder on GitHub. Changes are live immediately for all team members — no plugin reinstall needed.

## Files on GitHub

| File | Contains |
|---|---|
| `positioning.md` | Company overview, vision, mission, ecosystem position, product pillars |
| `value-story.md` | Core problems, value creation, differentiation |
| `terminology.md` | Approved and forbidden terms |
| `tone.md` | Tone of voice and writing style rules |
| `narrative.md` | Messaging hierarchy and narrative structure |
| `boilerplates.md` | Standardized descriptions and elevator pitches |
