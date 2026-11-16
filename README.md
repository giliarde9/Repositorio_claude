# Repositorio_claude

Claude Code skills configured for this repo (`.claude/skills/`):

| Skill | Source | What it does |
|---|---|---|
| `taste-skill` | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | Anti-"AI slop" frontend design taste: opinionated typography, color, layout and motion rules for landing pages, portfolios and redesigns. |
| `web-design-guidelines` | [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines) | Reviews UI code against Vercel's Web Interface Guidelines (interactions, accessibility, layout, forms, performance). |
| `awesome-design-md` | [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) | Library of `DESIGN.md` files reverse-engineered from real brands (Apple, Stripe, Airbnb, Anthropic, etc.) to match a UI to a known aesthetic. |
| `image-to-code-skill` | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill/tree/main/skills/image-to-code-skill) | Image-first workflow: generate/analyze a design reference image, then implement the website to match it. |
| `playwright-skill` | [lackeyjb/playwright-skill](https://github.com/lackeyjb/playwright-skill) | Browser automation with Playwright — screenshots, responsive checks, login flows, and general end-to-end testing. |
| `archify` | [tt-a1i/archify](https://github.com/tt-a1i/archify) | Generates validated, interactive standalone-HTML diagrams (architecture, workflow, sequence, data-flow, ERD, timeline, etc.) and one-page explainers. Installed via `npx skills add` into `.agents/skills/archify` (symlinked from `.claude/skills/`). |

All are third-party skills (MIT-licensed, except `archify`, which is Apache-2.0), vendored as-is with their original `LICENSE` files.