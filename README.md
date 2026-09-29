# Pipeline Gurus Design Language v1

A sharp, high-contrast design system for Pipeline Gurus social content, sales education, and digital experiences.

This repository turns the source social-media workbook into an agent-readable design language. Attach or clone it when building Pipeline Gurus work so designers and coding agents use the same typography, color, composition, logo, and content rules.

## Read in this order

1. `AGENTS.md` or `CLAUDE.md` — hard implementation rules
2. `DESIGN.md` — the complete system and rationale
3. `tokens/tokens.css` or `tokens/tokens.json` — exact values
4. `assets/pipeline-gurus-logo.jpg` — official logo extracted from the source workbook
5. `preview/index.html` — live brand specimen

## System at a glance

| Layer | Rule |
| --- | --- |
| Display | Bebas Neue, uppercase |
| Body | Poppins |
| Core palette | Black `#000000`, white `#FFFFFF`, action red `#F6283F` |
| Color balance | Approximately 70% ground, 20% text, 10% red |
| Grid | 12 columns; 90px columns on a 1080px square canvas |
| Geometry | Rectangles and angled lines; no circles or soft curves |
| Space | Keep 40–50% of each social frame empty |
| Motion | Left to right or bottom to top, 0.5–1 second |
| Voice | Confident, assertive, data-driven |

## Local preview

Open `preview/index.html` directly in a browser. There is no build step. The page loads Bebas Neue and Poppins from Google Fonts when online and uses explicit local fallbacks when offline.

## Source

The canonical brand rules were transcribed from `PG Social Media Guidelines.xlsx`. The logo in `assets/` was extracted from that workbook without redrawing or modification.

## Version

`v1.0.0` — initial repository lock of the Pipeline Gurus social design language.
