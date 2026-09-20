---
name: awesome-design-md
description: Curated library of DESIGN.md files reverse-engineered from real, well-known websites (Apple, Airbnb, Stripe, Anthropic, etc). Use when the user wants a page or UI to look like a specific known brand/product, or asks to "build me a page that looks like X".
metadata:
  author: VoltAgent
  version: "1.0.0"
  source: https://github.com/VoltAgent/awesome-design-md
---

# Awesome DESIGN.md

A DESIGN.md is a plain-text design system document (tokens, layout rules,
typography, motion) that an AI coding agent reads to generate UI consistent
with a specific visual language, the same way AGENTS.md/CLAUDE.md describes
how to build a project.

This skill bundles ready-made DESIGN.md files extracted from real websites,
under `design-md/<brand>/DESIGN.md`. See `design-md/` for the full list of
available brands (Apple, Airbnb, Stripe, Anthropic/Claude, Notion, Uber,
ElevenLabs, and more — see `README.md` for the complete index).

## How to use

1. Ask the user which brand/aesthetic they want to match, or infer it from
   their request (e.g. "make it look like Stripe").
2. Read the matching `design-md/<brand>/DESIGN.md` file.
3. Apply its tokens and rules when generating or reviewing UI code, instead
   of defaulting to generic styling.
4. If no matching brand exists in `design-md/`, say so rather than
   fabricating one, and fall back to the `taste-skill`/`web-design-guidelines`
   skills for general design quality.
