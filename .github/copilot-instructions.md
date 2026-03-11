# copilot instructions — Thyanri/Thyanri

This repository exists solely to power a premium GitHub profile README.

## design language

- **minimalist premium** — inspired by Monkeytype's visual style
- dark neutral palette with a single warm accent (#e2b714)
- generous whitespace, strong spacing, no clutter
- every visual element must earn its place

## guidelines

### assets
- prefer local SVG files in `/assets` over third-party badge services
- all SVGs follow the palette defined in `assets/palette.md`
- do not introduce random badges, emoji decorations, or gradient fills
- generated files (metrics, snake) live at repository root or on the `output` branch

### readme
- keep sections concise — product-style copy, not blog prose
- use lowercase section labels where it fits the style
- maintain breathing room between sections
- use collapsible `<details>` blocks for secondary content
- do not add trophy widgets, typing animations, or public stat cards
- preserve relative asset paths (`./assets/...`, `./github-metrics.svg`)

### workflows
- keep permissions minimal and explicit at both workflow and job level
- do not hardcode tokens — use repository secrets
- add brief comments explaining purpose and schedule

### tone
- calm, sharp, confident, technical
- avoid hype, buzzwords, and "passionate developer" language
- write like a product interface, not a personal blog
