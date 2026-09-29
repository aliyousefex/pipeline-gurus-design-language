---
version: "1.0.0"
name: Pipeline Gurus Design Language
description: Sharp, high-contrast sales design system using Bebas Neue, Poppins, black, white, and action red.
colors:
  black: "#000000"
  white: "#FFFFFF"
  action-red: "#F6283F"
  soft-white: "#F5F5F3"
  muted: "#A7A7A7"
  text-dark: "#333333"
  line-dark: "#303030"
  line-light: "#D7D7D7"
  text-light: "#D0D0D0"
typography:
  display: '"Bebas Neue", "Arial Narrow", sans-serif'
  body: 'Poppins, Arial, sans-serif'
grid:
  columns: 12
  square-canvas: 1080px
  column-width: 90px
shape:
  radius: 0px
  cta-radius: 10px
---

# Pipeline Gurus Design Language

## Overview

Pipeline Gurus is built from speed, precision, and authority. The system behaves like a sales argument: one decisive headline, one supporting visual, one action, and nothing competing for attention.

The default frame uses approximately 70% ground color, 20% type, and 10% red accent. Red is energy, not decoration. Use it once per frame as a button, keyword, number, underline, divider, or full background. Never set body copy in red.

The source workbook describes the target character as “elite, minimal, fast, and powerful” and “Ferrari meets Wall Street.” Translate that into exact alignment, large negative space, hard contrast, flat geometry, and an assertive editorial voice. Do not translate it into automotive imagery or financial claims unless the content calls for them.

## Logo

The official supplied asset is `assets/pipeline-gurus-logo.jpg`, extracted directly from the source workbook. It contains the white PG shield and white PIPELINE GURUS wordmark on black.

- Use one logo per frame.
- Keep the full asset intact. Do not redraw, trace, stretch, rotate, recolor, or add effects.
- Maintain clear space equal to at least 1.5 times the logo mark height.
- For new transparent or color variants, request approved source artwork. Do not manufacture them from the JPG.

The workbook mentions horizontal, vertical, and icon-only variants in white, black, and red. Only the white-on-black horizontal lockup was embedded in the provided file; the other variants remain documented requirements, not available assets.

## Color

| Token | Hex | Role |
| --- | --- | --- |
| Black | `#000000` | Authority, dark covers, body text on white |
| White | `#FFFFFF` | Clarity, copy on black/red, clean inner slides |
| Action Red | `#F6283F` | Energy, action, the single accent |
| Soft White | `#F5F5F3` | Optional preview/documentation ground |
| Muted | `#A7A7A7` | Metadata on black; not primary copy |
| Text Dark | `#333333` | Long-form supporting copy on white |
| Line Dark | `#303030` | Hairlines on black |
| Line Light | `#D7D7D7` | Hairlines on white |
| Text Light | `#D0D0D0` | Supporting copy on black |

Approved high-contrast pairs:

- White on black
- Black on white
- White on red
- Red on white for short accents

Avoid red body copy. Avoid red on black and black on red except for small, tested button treatments. Do not introduce gradients, neon glows, or extra brand colors.

## Typography

Use two families only.

- **Bebas Neue:** headlines, hero numbers, short CTA display lines. Uppercase and dominant.
- **Poppins:** body, labels, UI, metadata, URLs, and supporting evidence.

Headline size is the primary hierarchy. Body copy should be no more than 40% of the headline size. Use no more than two type sizes in one social frame. Headlines are left aligned by default; centered alignment is reserved for story covers and deliberate question frames. Never right-align headlines.

Recommended web scale:

| Role | Size / line height | Notes |
| --- | --- | --- |
| Display XL | `clamp(72px, 12vw, 180px) / 0.86` | One short statement |
| Display | `clamp(52px, 8vw, 112px) / 0.9` | Section conclusions |
| H2 | `48px / 0.95` | Compact headlines |
| Body large | `20px / 1.55` | Lead copy |
| Body | `16px / 1.6` | Supporting copy |
| Label | `12px / 1.3` | Uppercase, tracked |

## Layout and composition

Use a 12-column grid. On a 1080px square social canvas, each column is 90px. Keep primary text aligned to a stable vertical edge, typically column 3 on a left-weighted composition or column 10 for an opposing element.

- Preserve 40–50% empty space.
- Prefer a Z-pattern: logo top-left, headline mid-left, CTA bottom-right.
- Choose one visual hero: headline, number, or image.
- Use one logo and one CTA maximum.
- Keep offsets consistent across a carousel. If a headline starts 120px from the left on slide one, retain that start line.
- Carousels begin with black or red, use white for inner slides, and close on black or red with a CTA.
- Stories use larger headlines, more centered cover compositions, and stronger color dominance.

## Geometry, depth, and movement

Use rectangles, thin dividers, angled lines, arrows, and cropped elements that point into the frame. Avoid circles, soft curves, pill controls, and rounded card systems. The default radius is zero. The source allows a 10px radius on CTA buttons only.

Keep surfaces flat. No shadows behind text or logos. A CTA may use one soft shadow at most: `0 8px 24px rgba(0,0,0,.25)`.

If animated, move left to right or bottom to top. Use 0.5–1 second transitions. Avoid random movement and repeated entrance effects.

## Photography and icons

- Use black-and-white team or product photography.
- Keep imagery to 40% or less of the frame; text owns at least 60%.
- Add a 20–30% black overlay where needed for copy contrast.
- Avoid generic stock photography and staged smiles-at-camera sales imagery.
- Use thin geometric outline icons at 2px stroke or less, in red or white.
- Do not use emoji as icons.

## Voice

Pipeline Gurus sounds confident, assertive, specific, and data-driven. State the sales insight or action directly. Do not use casual motivation, vague hype, or emojis.

Good:

- `YOUR PIPELINE ISN'T STUCK. YOUR NEXT STEP IS.`
- `3 SIGNALS YOUR DEAL WILL SLIP`
- `BOOK YOUR FREE CONSULTATION`

Avoid:

- `Unlock your limitless potential!`
- `Let’s crush those goals 🚀`
- Claims, metrics, or customer proof that have not been supplied.

## Components

### CTA

Red rectangle, white uppercase Poppins text, 10px radius, placed bottom-center or bottom-right. Use one per frame. Supported source copy includes `LEARN MORE`, `VISIT WEBSITE`, `READ MORE`, `VOTE NOW`, `SWIPE UP`, and `BOOK YOUR FREE CONSULTATION`.

### Accent

Choose one per frame: a red underline, keyword, large number, thin divider, arrow, outline, button, or background. Never stack several red accents.

### Data point

Set the number in Bebas Neue and red or black. Keep charts flat, minimal, and subordinate to the number. Use no 3D effects.

### Quote

Use a black background, white Bebas Neue statement, and one or two red keywords. A monochrome headshot is optional. Red quotation marks may be the single accent.

## Social templates

| Format | Pattern |
| --- | --- |
| Carousel cover | Black ground, white headline, one red underline or keyword, horizontal white logo top-left |
| Carousel inner | White ground, black text, one red callout, icon-only red logo bottom-right when approved asset exists |
| Carousel close | Black ground, white headline, red CTA near bottom, small website below |
| Clean editorial | White ground, black headline, red underline, generous 100px padding |
| Quote | Black ground, white statement, one or two red words, optional monochrome portrait |
| Tip | White ground, black headline, thick red underline, logo bottom-left |
| Promo | Red ground, white type and logo, CTA near lower edge |
| Story question | Red ground, white centered question, white icon-only logo when approved asset exists |
| Story steps | Black ground, white copy, large red numbers, bottom CTA |
| Data / stat | White ground, large red percentage, black supporting copy, optional simple bar chart |

## Accessibility

Black/white and white/red provide strong contrast. Small red text on white may not meet WCAG contrast requirements; reserve that combination for large display text or non-text decoration. Always provide visible keyboard focus in interactive work and honor `prefers-reduced-motion`.

## Do / do not

Do use one hero, exact alignment, decisive whitespace, high contrast, monochrome imagery, and one red action cue.

Do not use gradients, glass, 3D icons, multiple focal points, red body copy, soft rounded cards, centered-everything layouts, or invented brand assets.
