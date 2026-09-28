---
name: Origen Noble
colors:
  surface: '#fff8f6'
  surface-dim: '#e8d6d0'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ec'
  surface-container: '#fdeae3'
  surface-container-high: '#f7e4de'
  surface-container-highest: '#f1dfd8'
  on-surface: '#231916'
  on-surface-variant: '#54433a'
  inverse-surface: '#392e2a'
  inverse-on-surface: '#ffede7'
  outline: '#877369'
  outline-variant: '#dac2b6'
  surface-tint: '#934b19'
  primary: '#6c2f00'
  on-primary: '#ffffff'
  primary-container: '#8b4513'
  on-primary-container: '#ffc29f'
  inverse-primary: '#ffb68c'
  secondary: '#3b6934'
  on-secondary: '#ffffff'
  secondary-container: '#b9eeab'
  on-secondary-container: '#3f6d38'
  tertiary: '#344537'
  on-tertiary: '#ffffff'
  tertiary-container: '#4b5c4e'
  on-tertiary-container: '#c1d4c1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbc9'
  primary-fixed-dim: '#ffb68c'
  on-primary-fixed: '#321200'
  on-primary-fixed-variant: '#753401'
  secondary-fixed: '#bcf0ae'
  secondary-fixed-dim: '#a1d494'
  on-secondary-fixed: '#002201'
  on-secondary-fixed-variant: '#23501e'
  tertiary-fixed: '#d5e7d5'
  tertiary-fixed-dim: '#b9cbb9'
  on-tertiary-fixed: '#101f13'
  on-tertiary-fixed-variant: '#3a4b3d'
  background: '#fff8f6'
  on-background: '#231916'
  surface-variant: '#f1dfd8'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 26px
    fontWeight: '500'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
  numeric-data:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system embodies an agrarian-editorial aesthetic, uniting the artisanal rigor of specialty coffee grading with the institutional security of ethical microfinance. Built for specialty producers, green coffee buyers, Q-graders, and agricultural lenders, the interface evokes trust, craftsmanship, and grounded luxury.

Visual decisions draw from tactile editorial design paired with contemporary fintech precision:
- **Agrarian Tactility:** Natural textures, warm parchment foundations, and grounded organic tones replace sterile high-tech motifs.
- **Editorial Legibility:** Prominent, high-contrast serif headlines evoke origin journals and auction catalogs, while balanced grotesque sans-serifs anchor technical and transactional density.
- **Financial Gravity:** Critical metrics—SCA cupping scores, harvest altitudes, loan APRs, and auction increments—are rendered with sharp structural discipline, avoiding playful consumer tropes.

## Colors

The palette is derived from the life cycle of specialty coffee: raw green beans, volcanic soils, toasted parchment, and dense canopy shade.

- **Primary (`#8B4513` - Terracota Tostado):** Represents roasted beans and rich volcanic soil. Reserved for principal calls to action, active loan selections, primary auction bids, and key metric emphasis.
- **Secondary (`#2D5A27` - Verde Bosque):** Evokes fertile canopy microclimates and healthy farm yields. Employed for verification badges, positive financial yields, funded micro-loans, and organic certifications.
- **Tertiary (`#5A6B5C` - Café Verde):** A muted green-gray drawn from raw, unroasted export lots. Used for secondary status pills, supporting icons, sensory radar charts, and subtle interactive states.
- **Neutral (`#2C221E` - Madera Nogal):** A deep, saturated walnut brown used in place of synthetic true black. Delivers deep contrast with natural warmth across headings, typography, borders, and high-emphasis data displays.
- **Surface Canvas (`#F9F6F0` - Crema Cálido):** Warm raw parchment tone used as the foundational canvas, eliminating harsh digital white glare while maintaining AAA accessibility contrast.

## Typography

The typographic pairing reflects dual intent: the editorial authority of high-end culinary publications and the clean efficiency of financial tools.

- **Headlines & Editorial Titles:** Set in `Playfair Display`. It provides distinct character for lot origin narratives, auction titles, producer names, and hero loan overviews.
- **User Interface, Forms & Tables:** Set in `Plus Jakarta Sans`. Its open apertures and structured geometry ensure clear legibility across complex multi-column auction sheets, cupping scorecards, and credit amortization tables.
- **Numerical Data Display:** Dedicated style with tabular lining figures enabled (`font-variant-numeric: tabular-nums`) to ensure zero-jitter visual alignment during live micro-auction price increments and loan slider adjustments.

## Layout & Spacing

The layout follows an asymmetrical fixed-fluid hybrid structure:

- **Desktop (1200px+):** 12-column grid, 1.5rem gutters, and 3rem side margins. Financial simulators utilize structured 7:5 split layouts, pairing live calculation controls with immediate amortization projections.
- **Tablet (768px - 1199px):** 8-column grid with 1.25rem gutters and 2rem side margins. Metric panels collapse from multi-tier matrices into condensed 2x2 grids.
- **Mobile (Below 768px):** 4-column grid with 1rem gutters and 1.25rem screen margins. Auction tables transform into stacked feed cards; the credit simulator shifts from side-by-side to a vertical step flow with a persistent sticky calculation tray at the bottom viewport.

## Elevation & Depth

This system avoids plastic blurs or synthetic dropshadows, relying instead on warm physical depth and tonal layering inspired by natural surfaces and paper stationery:

- **Base Canvas:** Finished in flat `Crema Cálido` (`#F9F6F0`).
- **Surface Layer 1 (Cards, Ledger Sheets):** `#FFFFFF` with a crisp, low-contrast ghost outline (`1px solid rgba(44, 34, 30, 0.08)`).
- **Surface Layer 2 (Raised Modals, Auction Drawers):** `#FFFFFF` bordered with `rgba(44, 34, 30, 0.12)` complemented by an ambient, warm soil shadow: `0 12px 32px -4px rgba(44, 34, 30, 0.08)`.
- **Surface Layer 3 (Toast Notifications, Sticky Menus):** Warm high-contrast ground (`#2C221E` with `#FFFFFF` text), elevated through `0 16px 40px -8px rgba(44, 34, 30, 0.22)`.

## Shapes

The shape scale is restrained to a soft border radius (`4px` base / `8px` cards / `12px` modals) to preserve an editorial structure reminiscent of vintage bond certificates, cupping ledgers, and burlap export stamps.

- Small items (inputs, table headers, buttons): `4px`
- Interactive blocks (lot cards, credit simulator modules, alert banners): `8px`
- High-level containers (dialogs, auction side-sheets): `12px`
- Specialized Pills (SCA score tags, altitude chips): `100px` (full circular ends) to create sharp geometric contrast against structural rectangular cards.

## Components

### Buttons
- **Primary Action (Make Offer / Submit Credit Application):** Terracotta (`#8B4513`) background, `#FFFFFF` text, `4px` border radius, high-density padding (`12px 24px`). Hover transitions to darkened roast tone (`#72370E`).
- **Secondary Action (View Cupping Sheet / Farm Traceability):** Clear background, `1px solid #8B4513`, text in `#8B4513`. Hover sets a translucent terracotta tint (`rgba(139, 69, 19, 0.06)`).
- **Institutional/Tertiary Action:** Borderless, walnut (`#2C221E`) text, underline on hover with `4px` offset.

### SCA Specialty Coffee Cards
- Dedicated card containers for micro-lots featuring a prominent top-right circular SCA badge (`#2D5A27` background, white text) highlighting cupping scores (e.g., "88.5 PTS").
- **Metadata Ribbon:** Horizontal list of chips displaying Altitude ("1,850 msnm"), Processing ("Lavado Fermentación Lenta", "Natural Anaeróbico"), and Botanical Variety ("Geisha", "Bourbon Rosado").
- **Footer Section:** Direct micro-loan status indicator or current auction ask price with remaining lot quantity (e.g., "12 sacos disponibles").

### Badges & Chips
- **Altitude Badge:** `#F0ECE1` background, `#2C221E` text, accompanied by an upward elevation glyph.
- **Process Badge:** `#EBF2EB` background with `#2D5A27` text to signify organic wet/dry mill processing.
- **Micro-loan Risk Grade Badge:** Monospace-leaning letter tier (`A1`, `B2`) housed in a structured border box.

### Agricultural Credit Simulator
- **Interactive Range Sliders:** Custom track using `rgba(44, 34, 30, 0.1)` with active track fill in `#8B4513`. Thumb is a solid `#8B4513` square with `4px` radius and white indicator pip.
- **Live Output Ledger:** Real-time updates detailing total interest, loan tenure, harvest-aligned seasonal repayment milestones, and projected crop collateral margins.

### Auction Live Desk & Administrative Table
- Dense layout displaying lot ID, farm origin, Q-grader notes, base bid, current bid, and dynamic countdown timer.
- Live bids flash with a brief background tint of `#EBF2EB` (secondary light) before returning to white.
- Administrative controls allow manual lot pausing, minimum tick increases, and instant farmer payout settlements.

### Notifications & Toasts
- **Style:** Compact floating bars anchored to bottom-right or top-center.
- **Alert Types:**
  - *Loan Approval / Bid Superior:* Secondary green accent line on the left (`#2D5A27`), parchment background, walnut text.
  - *Outbid Warning / Payment Milestone:* Terracotta accent line (`#8B4513`), clear action link to counter-bid immediately.