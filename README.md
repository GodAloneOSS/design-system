# design-system

Shared visual identity for the GodAlone ecosystem - godalone.in, kadavulmattum.org, ekkhuda.org, and the Quran Web App.

## What's here

- **tokens.css** - the canonical CSS custom properties (colors, gradients, shadows, radii, fonts), lifted directly from godalone-theme/style.css. Import this file, or copy the :root block, to reuse the palette in a new site or app.
- **tokens.json** - the same tokens as structured JSON, for tooling (Figma plugins, style-dictionary, design QA scripts, etc.) that can't consume CSS directly.

## Palette at a glance

The system has two modes:

- **Night (default)** - deep green background (#064E3B) with a bright green/gold accent (#22C55E, #4ADE80).
- **Day** (html.theme-day) - elevated ivory/white background (#F8FFF5) with the same green accent family, deepened for light-background contrast.

Both modes share the same accent hues so the two feel like one brand, not two.

## Typography

| Role | Stack |
|---|---|
| Display (headings) | 'Marcellus', Georgia, 'Times New Roman', serif |
| Body | 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif |
| Arabic | 'Scheherazade New', 'Amiri', 'Traditional Arabic', serif |
| Tamil | 'Noto Sans Tamil', body stack |

## Layout

- Max content width: 1180px
- Corner radius: 20px (default), 28px (large)

## Source of truth

These tokens are extracted from the live godalone-theme WordPress theme (style.css, "GodAlone Premium" v2.0) - the theme remains the canonical source; this repo exists so the palette can be reused outside WordPress (the Quran Web App, future tools, print/brand assets) without re-deriving it by eye each time.
