---
name: Royal Estate & Commercial Investment
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#44474d'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#74777d'
  outline-variant: '#c4c6cd'
  surface-tint: '#4d6079'
  primary: '#000917'
  on-primary: '#ffffff'
  primary-container: '#0d2137'
  on-primary-container: '#7689a4'
  inverse-primary: '#b5c8e5'
  secondary: '#725b38'
  on-secondary: '#ffffff'
  secondary-container: '#fedeb2'
  on-secondary-container: '#78603e'
  tertiary: '#000b05'
  on-tertiary: '#ffffff'
  tertiary-container: '#002617'
  on-tertiary-container: '#009b6b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#b5c8e5'
  on-primary-fixed: '#081c32'
  on-primary-fixed-variant: '#364860'
  secondary-fixed: '#fedeb2'
  secondary-fixed-dim: '#e0c298'
  on-secondary-fixed: '#281800'
  on-secondary-fixed-variant: '#584323'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  headline-xl:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 44px
  headline-xl-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 34px
  headline-lg-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: IBM Plex Sans
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system positions itself as an authoritative, prestigious institutional portal for high-net-worth individuals, institutional investors, and premier real estate developers across the Gulf and broader MENA region. The visual ethos merges classical luxury with rigorous financial precision, balancing high-end architectural grandeur with the analytic utility of a private wealth management terminal.

The aesthetic follows an understated "Warm Executive Minimalist" movement enriched by subtle tactile cues:
- High contrast, pristine white cards suspended against serene, neutral pale canvas grounds.
- Meticulous architectural framing, micro-borders with brushed metallic accents, and calculated golden section proportions.
- An unmistakable RTL-first visual orientation engineered specifically for the rhythmic baseline, optical weights, and fluid ligatures of contemporary Arabic typography.
- An emotional resonance of uncompromising financial discretion, structural permanence, and elite investment exclusivity.

## Colors
The palette evokes institutional solidity paired with curated luxury:

- **Primary (`#0D2137` / `#0A192F`):** Deep Royal Navy anchor tone. Used for critical navigational structures, key surface headers, primary calls to action, and authoritative typography.
- **Secondary (`#C5A880` / `#D4AF37`):** Warm Gold / Champagne. Deployed deliberately for premier status indicators, luxury property tiers, bespoke key metrics, active tab indications, and refined outline highlights.
- **Tertiary (`#10B981`):** Emerald Yield Green. Dedicated exclusively to financial performance metrics, projected internal rate of return (IRR), annualized ROI, net capital appreciation indicators, and verified validation badges.
- **Neutral Core (`#1E293B` & `#64748B`):** Slate Slate tones providing nuanced textual contrast tiers across Arabic letterforms, maintaining clear legibility across diverse device display profiles.
- **Background & Canvas (`#F8FAFC` & `#FFFFFF`):** High-grade luminous backdrop preventing the dense navy elements from overwhelming the spatial flow, accented with subtle borders (`#E2E8F0`).

## Typography
IBM Plex Sans (supporting Arabic script alongside Latin numerals) provides the geometric discipline and clarity required for high-density transactional screens. Arabic typography necessitates increased line-height allowances (1.5x - 1.6x the font size) to accommodate ascenders, descenders, and tashkeel marks without collision.

Letter spacing is uniformly locked to `0` or slightly loose for labels; negative tracking is strictly avoided in Arabic scripts to preserve authentic ligature connectivity. Financial figures and percentages default to tabular figures to ensure precise vertical alignment across yield comparisons and portfolio valuations.

## Layout & Spacing
The layout adheres strictly to right-to-left (RTL) reading geometry: primary focal points, property titles, and navigation starting points align to the right edge, while secondary progressive disclosures, chevron arrows, and financial metrics anchor to the left.

The spatial system follows an 8-point base grid:
- **Mobile Handsets (&lt;640px):** 4-column layout with 16px outer margins, 12px interior gutters, and tight vertical rhythm to keep multi-asset metrics visible above the fold.
- **Large Handsets & Small Tablets (640px–1024px):** 8-column layout with 24px margins, allowing side-by-side presentation of floor plans alongside investment breakdown sheets.
- Horizontal scroll carousels for high-yield property showcases bleed edge-to-edge with right-hand margin indentations to maintain uninterrupted RTL finger flow.

## Elevation & Depth
Elevation conveys institutional stability and tangible luxury without relying on synthetic skeuomorphism. Depth is achieved through a triad of warm ambient shadows, fine hairline borders, and layered luminous containers:

- **Level 0 (Floor Canvas):** Flat `#F8FAFC`, non-elevated background surface.
- **Level 1 (Property & Asset Cards):** Pure `#FFFFFF` background bound by a 1px border of `#E2E8F0`, layered over a dual ambient drop: `0px 2px 4px rgba(13, 33, 55, 0.03), 0px 8px 24px rgba(13, 33, 55, 0.06)`. This deep-navy tinted shadow eliminates dirty gray blurs and introduces an atmospheric spatial richness.
- **Level 2 (Interactive Floating Actions & Yield Calculators):** Bordered with `#E2E8F0` and elevated with `0px 12px 32px rgba(13, 33, 55, 0.12)`.
- **Level 3 (Modal Sheets & Portfolio Overlays):** Deep navy translucent backdrops (`rgba(10, 25, 47, 0.48)`) matched with high-specular glass-frosted filters (`backdrop-filter: blur(12px)`), casting crisp focus onto the foreground container.

## Shapes
A disciplined "Soft" curvature standard (`roundedness: 1`) reflects structural architectural permanence:
- Base cards, image viewports, and structural containers utilize clean 4px to 8px corner radii (`0.25rem` - `0.5rem`), echoing polished marble slabs and architectural blueprints.
- Yield pills, verification chips, and investment badges use pill-shaped micro-radii to distinguish data indicators from spatial structural containers.
- Inputs and action triggers carry crisp, low-radius contours to retain their executive, non-frivolous character.

## Components

### Buttons & Financial CTAs
- **Primary CTA:** Deep Royal Navy (`#0D2137`) fill, crisp white typography, 8px radius. Active state produces a subtle gold inner border highlight (`#C5A880`).
- **Luxury Secondary Action:** Luminous white container with a 1px solid Champagne Gold border (`#C5A880`) and navy text.
- **Icon Alignment:** Action directional icons (such as left-pointing back arrows or progressive disclosure chevrons) must be flipped 180 degrees to preserve native RTL semantics.

### Cards (Asset & Investment)
- Composed of 8px corner radii, razor-thin `#E2E8F0` borders, and high-aspect-ratio architectural photography.
- The top-right corner is reserved for status badges (e.g., "تحت الإنشاء" / "Under Construction" or "جاهز للاستلام" / "Ready to Move"), while the top-left features the Emerald ROI capsule badge.
- Bottom card segments host verified broker micro-avatars paired with clear license badges.

### Investment Chips & Badges
- **Yield & ROI Chips:** Soft translucent emerald background (`rgba(16, 185, 129, 0.10)`) paired with bold `#10B981` text, indicating expected annual return (e.g., `8.4% عائد استثماري`).
- **Verified Agent Badges:** Navy background (`#0D2137`) with a miniature micro-check icon in Champagne Gold (`#C5A880`).

### Input Fields & Search Bars
- Background set to pure `#FFFFFF` surrounded by a 1px border of `#E2E8F0`, transitioning into `#0D2137` on focus with a 2px outer gold aura (`rgba(197, 168, 128, 0.25)`).
- Input labels remain anchored to the right; currency symbols (e.g., ر.س / د.إ) sit firmly on the left boundary as visual bookends.

### Specialized Component: Bilingual Investment Calculator Slider
- Dual slider tracking commercial real estate down payments against mortgage amortization periods.
- Features continuous gold rail highlights (`#C5A880`) over deep-navy grab thumbs, outputting live financial yields formatted with clear RTL numerals and currency nomenclature.