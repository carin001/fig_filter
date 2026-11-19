---
name: Warm Artisanal Gastronomy
colors:
  surface: '#fff8f8'
  surface-dim: '#e1d8d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf1f2'
  surface-container: '#f5eced'
  surface-container-high: '#efe6e7'
  surface-container-highest: '#e9e0e1'
  on-surface: '#1e1b1c'
  on-surface-variant: '#4d444b'
  inverse-surface: '#342f30'
  inverse-on-surface: '#f8eeef'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#755377'
  primary: '#331736'
  on-primary: '#ffffff'
  primary-container: '#4a2c4d'
  on-primary-container: '#ba94bb'
  inverse-primary: '#e3b9e3'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#ffc55f'
  on-secondary-container: '#755100'
  tertiary: '#1b2500'
  on-tertiary: '#ffffff'
  tertiary-container: '#303b0f'
  on-tertiary-container: '#98a66f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fe'
  primary-fixed-dim: '#e3b9e3'
  on-primary-fixed: '#2c1030'
  on-primary-fixed-variant: '#5b3c5e'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f5bd58'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#dbe9ac'
  tertiary-fixed-dim: '#bfcd92'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#404b1e'
  background: '#fff8f8'
  on-background: '#1e1b1c'
  surface-variant: '#e9e0e1'
  bg-canvas: '#FAF6F0'
  surface-card: '#FFFFFF'
  surface-subtle: '#F3ECE1'
  border-subtle: '#E5DCD0'
  border-strong: '#4A2C4D'
  amber-subtle: '#FBF3E3'
  text-muted: '#6E6365'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 3.25rem
    fontWeight: '600'
    lineHeight: 3.75rem
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.75rem
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.75rem
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: 0em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: 2rem
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 1.25rem
    fontWeight: '500'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.6rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.4rem
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '700'
    lineHeight: 1rem
    letterSpacing: 0.06em
  price-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: 1.5rem
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

The design system establishes a warm, tactile, and grounded aesthetic tailored for an artisanal neighbourhood café. The brand speaks with honest clarity: plainspoken, warm, and subtly dry-humoured. The interface feels organic and considered, prioritizing physical craft—fresh baking, small-batch roasting, and courtyard greenery—over digital ornamentation.

The visual direction leans into modern editorial craft. It balances rich, botanical depth with expansive, warm paper-toned surfaces. The tactile sensibility mirrors a well-printed café menu or tactile signage: quiet borders, generous whitespace, confident serif headers, and purposeful, earthy accents. Interfaces must immediately resolve physical real-world questions (hours, location, menu prices) without digital friction or unnecessary animations.

## Colors

The palette is rooted in physical craft and natural botanicals:
- **Primary (`#4A2C4D`)**: Deep fig purple. Used for principal branding, hero typography, primary action buttons, strong outlines, and focal navigational cues.
- **Secondary / Accent (`#D9A441`)**: Warm amber. Strictly reserved for accents, status pills, dietary badges, rating highlights, and subtle atmospheric strokes. Never used for standard body copy or long paragraphs.
- **Neutral (`#221E1F`)**: Deep near-black charcoal. Delivers high-contrast readability for running copy, prices, and structural tabular data without the harsh sterility of `#000000`.
- **Canvas & Surface (`#FAF6F0`)**: An unbleached, warm parchment off-white, providing organic warmth rather than clinical digital brightness.

Every screen uses light mode to reflect daylight café dining. Text on `#4A2C4D` surfaces must strictly render in `#FAF6F0` or `#FFFFFF` to ensure high accessibility.

## Typography

The type system blends the characterful elegance of `Playfair Display` with the friendly, open legibility of `Plus Jakarta Sans`.

- **Headings (`Playfair Display`)**: Conveys human tradition, warmth, and artisanal care. Titles and section labels use standard sentence capitalization or title case, keeping the voice approachable and avoiding aggressive all-caps treatments.
- **Body & Data (`Plus Jakarta Sans`)**: Clean, highly readable sans-serif optimized for mobile screens. Delivers friction-free scanning for ingredient descriptions, transit routes, and opening schedules.
- **Microcopy & Price Points**: Menu prices sit comfortably inline using `price-md`, maintaining clear optical alignment with item titles. Dietary labels (V, VG, GF) leverage `label-sm` with slight uppercase tracking for rapid parsing.

## Layout & Spacing

The layout is built mobile-first, ensuring every critical action and piece of practical information functions seamlessly in a single vertical column.

- **Mobile Viewport (<768px)**: Strict single-column stack. Page margins use `margin: 1rem`. Critical operational data (operating hours, address, transit notes) sits above the fold on relevant landing views.
- **Desktop Viewport (≥768px)**: Fluid max-width container capped at `1040px` centered with auto margins. Menus expand to a maximum of two columns to preserve rapid optical scanning. Catering packages transition from a vertical card stack to an intuitive three-column side-by-side comparison.
- **Rhythm**: Component interiors scale along an 8px grid (`space-sm`, `space-md`, `space-lg`). Content sections breathe with generous top and bottom separation (`space-xl` on mobile, `space-2xl` on desktop), establishing a calm, unhurried pace.

## Elevation & Depth

Visual hierarchy relies on quiet editorial layering, tactile material distinctions, and crisp borders rather than heavy drop shadows:

- **Flat Tonal Layering**: Depth is achieved by placing pure white (`#FFFFFF`) or pale sand (`#F3ECE1`) containers against the warm parchment canvas (`#FAF6F0`).
- **Low-Contrast Outlines**: Cards, dietary badges, and table rows use a subtle, hairline border (`1px solid #E5DCD0`). 
- **Active & Interactive Elevation**: Interactive cards (such as catering package tiers) lift slightly using a soft, warm ambient shadow (`0 8px 24px -4px rgba(74, 44, 77, 0.08)`), pairing the fig tint with elevation to signal state changes organically.
- **Floating Modals & Sheets**: Mobile navigation overlays and contextual popovers utilize an opaque `#FAF6F0` surface with a delicate top edge border and deep, muted ambient diffusion (`0 16px 36px rgba(34, 30, 31, 0.12)`).

## Shapes

The design system adopts a soft, architectural shape language (`roundedness: 1`):
- **Base Components (Inputs, Buttons, Cards)**: `0.25rem` (4px) to `0.5rem` (8px). This subtle softening reflects crafted paper stationery and timber cafe fixtures without descending into bubbly, overly-digital geometry.
- **Dietary Badges & Dietary Tags**: `rounded-full` pills (`9999px`) to create an immediate structural distinction between informational metadata and actionable interactive cards.
- **Imagery**: Photography of the roastery, daily pastries, and founders maintains `0.5rem` corners with occasional subtle border overlays (`1px solid rgba(74, 44, 77, 0.08)`) to nestle them comfortably into the layout.

## Components

### Buttons & Calls to Action
- **Primary CTA**: Strict rule of exactly one primary CTA per view ("Find us", "Order catering"). Solid Deep Fig background (`#4A2C4D`), warm off-white text (`#FAF6F0`), font weight 600, padding `0.875rem 1.75rem`, border radius `0.375rem`. Hover state introduces a gentle darkening tone with no layout shifts.
- **Secondary Actions & Links**: Visually understated. Text links styled in `#4A2C4D` with a delicate bottom border (`1px solid #4A2C4D`), transitioning to warm amber (`#D9A441`) on hover. Never compete visually with the single primary CTA.

### Menu List Items
- Structured as single-column horizontal pairs on mobile and dual-column lists on desktop.
- Dish/drink name styled with `headline-sm`, followed by a leader or direct gap to `price-md`.
- Brief, plainspoken ingredient description in `body-sm` (`#6E6365`).
- Dietary badges displayed alongside titles: compact, uppercase pills with subtle border (`border-subtle`) and amber-toned highlight background (`#FBF3E3`).

### Catering Cards
- Defined containers with `surface-card` background and `1px solid #E5DCD0`.
- Interior padding set to `space-lg`.
- Top section highlights package name, per-person pricing, and minimum headcounts.
- Bulleted contents feature subtle warm-amber dot markers.
- Prominent package tier receives an accent outline in `#4A2C4D` and a modest amber tag ("Most Popular").

### Hours & Location Table
- Designed for rapid glanceability on mobile devices.
- Days and times arranged in a balanced two-column tabular layout with alternating row backgrounds (`#FAF6F0` and `#FFFFFF`) or hairline dividers (`#E5DCD0`).
- The current operating day is highlighted with a soft warm amber left-accent bar.
- Immediate plain text address and contact links sit directly adjacent, fully visible above the mobile scroll fold.

### Form Inputs & Enquiry Fields
- Clean input containers with `surface-card` fill and `1px solid #E5DCD0`.
- Focus state activates a distinct `1px solid #4A2C4D` boundary and a faint purple halo tint.
- Labels rendered in `label-md` using `#221E1F`, positioned directly above the input with `space-xs` spacing.