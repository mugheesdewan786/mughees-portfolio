# Design System

## Theme

Light, Bilal-matched. Off-white page, charcoal type, indigo/violet accent, green WhatsApp. Circular portrait with a gradient ring.

**Color strategy:** Full palette, matching Syed Bilal Fahim's portfolio: `#F9FAFB` ground, `#6366F1` indigo, `#8B5CF6` violet, `#15803D` green, `#F59E0B` gold on the ring.

## Colors

| Role | Token | Value |
|------|--------|--------|
| Primary ink | `--primary` | `#0D1B2A` |
| Body | `--text` | `#1A1A1A` |
| Muted | `--text-2` | `#666666` |
| Page | `--bg` / `--bg-2` | `#FFFFFF` / `#F9FAFB` |
| Indigo | `--indigo` | `#6366F1` |
| Violet | `--violet` | `#8B5CF6` |
| Green | `--green` | `#15803D` |

## Typography

Space Grotesk for headings, Inter for body. Same pairing as the reference site the owner asked to match.

## Imagery

Hero portrait is a 400px circle with an indigo–violet–amber ring and a slow float. Closing portrait is also circular. No full-bleed split panels.

## Colors (OKLCH)

| Role | Token | Value |
|------|--------|--------|
| Paper | `--paper` | `oklch(0.965 0.014 78)` |
| Surface | `--surface` | `oklch(0.94 0.016 78)` |
| Sunk | `--sunk` | `oklch(0.91 0.018 78)` |
| Ink | `--ink` | `oklch(0.23 0.035 265)` |
| Ink 2 | `--ink-2` | `oklch(0.42 0.03 265)` |
| Ink 3 | `--ink-3` | `oklch(0.55 0.025 265)` |
| Rule | `--rule` | `oklch(0.88 0.018 78)` |
| Lapis | `--lapis` | `oklch(0.36 0.12 262)` |
| Lapis bright | `--lapis-bright` | `oklch(0.92 0.03 262)` |
| On lapis | `--on-lapis` | `oklch(0.96 0.012 85)` |

Never pure black or white. Neutrals tint toward hue 262.

## Typography

- **Display / thesis:** Source Serif 4. Newspaper, gazette, institutional. Used for the name, case titles, and the closing line.
- **Body / UI:** Schibsted Grotesk. Weight contrast inside one family for nav, body, stamps.
- **Mark:** Noto Naskh Arabic, once, for مغیث دیوان in the nav.

Reflex-rejected: Inter, Instrument Serif, Playfair, Fraunces, IBM Plex, Space Grotesk, DM Sans.

Scale (perfect fourth, ~1.333): xs 0.75 / sm 0.875 / base 1.0625 / lg 1.333 / xl 1.777 / display `clamp(2.8rem, 8vw, 5.4rem)`. Body measure 62ch. Line-height 1.58.

## Layout

Full-bleed split hero: copy on paper, standing portrait on a lapis panel. Page measure ~72rem. Cases use a numbered rail, not cards. Experience is a timeline of rules, not a card grid. Spacing on a 4pt base with uneven rhythm (tight groups, generous section gaps).

## Elevation

Almost none. Grouping via space, rules, and the sunk decision band. No shadows, no glass.

## Motion

Page-load stagger on hero only (`opacity` + `translateY`, 500–700ms, `--ease-out-expo`). Link/button color at 150ms. No layout-property animation. `prefers-reduced-motion: reduce` disables entrance motion.

## Components

- **Primary CTA:** filled lapis, WhatsApp. Not WhatsApp green.
- **Secondary CTA:** ink outline on paper.
- **Decision band:** full sunk surface, not a left stripe.
- **Numbers:** tabular lining figures in Grotesk, lapis color, no card chrome.
- **Quotes:** rule-top, no quote cards.

## Imagery

Hero: navy-blazer standing portrait (fusion kurta + jacket), large, not circular. Casual denim cutout only in the close section. Diagrams are argument SVGs, not decoration.
