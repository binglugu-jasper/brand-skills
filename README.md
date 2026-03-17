# Brand Skills

A collection of [Agent Skills](https://agentskills.io) that capture the brand identity of companies for creating on-brand ad content, variations, and net-new campaigns.

Each skill encodes a brand's visual system, typography, color palette, copy voice, and layout patterns — so AI agents can produce content that looks and feels authentically on-brand.

## Available Skills

| Brand | Folder | Description |
|-------|--------|-------------|
| Kohler | [skills/kohler-brand](skills/kohler-brand/) | Premium bath and kitchen fixtures — bold, cinematic, design-led luxury |
| Infineon | [skills/infineon-brand](skills/infineon-brand/) | Global semiconductor manufacturer — precise, technical, teal-dominant B2B |
| Mattress Firm | [skills/mattressfirm-brand](skills/mattressfirm-brand/) | Largest US mattress retailer — promotional, red/navy, sleep-aspiration driven |

## Install

```bash
npx skills add <path-to-this-repo>
```

## Adding a New Brand

1. Create a new folder under `skills/` named `[brand]-brand/`
2. Add a `SKILL.md` following the pattern in an existing skill
3. Core sections: Brand Overview, Colors, Typography, Copy Voice, Visual Style, Logo Rules, Hard Rules

## What Goes Into a Brand Skill

Minimum inputs needed to write a new brand skill:
- **Logo** (PNG or SVG)
- **3–5 ad examples** (screenshots)
- **Brand website URL** (to extract actual font and color tokens from CSS)
