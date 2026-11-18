---
name: Gramin Arthsetu Interface
colors:
  surface: '#f9f9f8'
  surface-dim: '#dadad9'
  surface-bright: '#f9f9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f3'
  surface-container: '#eeeeed'
  surface-container-high: '#e8e8e7'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#404941'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1f0'
  outline: '#717970'
  outline-variant: '#c0c9be'
  surface-tint: '#2e6a41'
  primary: '#003b1b'
  on-primary: '#ffffff'
  primary-container: '#14532d'
  on-primary-container: '#87c695'
  inverse-primary: '#96d5a3'
  secondary: '#9b4500'
  on-secondary: '#ffffff'
  secondary-container: '#fd8a42'
  on-secondary-container: '#682c00'
  tertiary: '#283245'
  on-tertiary: '#ffffff'
  tertiary-container: '#3e495c'
  on-tertiary-container: '#adb8cf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b1f2be'
  primary-fixed-dim: '#96d5a3'
  on-primary-fixed: '#00210d'
  on-primary-fixed-variant: '#12512c'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb68e'
  on-secondary-fixed: '#331200'
  on-secondary-fixed-variant: '#763300'
  tertiary-fixed: '#d8e3fb'
  tertiary-fixed-dim: '#bcc7de'
  on-tertiary-fixed: '#111c2d'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f9f9f8'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Noto Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Noto Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Noto Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Noto Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Noto Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
  label-sm:
    fontFamily: Noto Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
  numeric-currency:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.5rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system establishes a civic-grade, high-trust digital interface tailored for rural micro-entrepreneurs, self-help groups, local village level entrepreneurs (VLEs), and field advisory officers across India. 

The visual style is **Civic Modern**: an intersection of institutional integrity, utilitarian clarity, and humane warmth. It avoids trendy gimmicks, excessive blurs, or fragile abstractions in favor of direct affordances, disciplined structural hierarchy, and high contrast. The emotional tone evokes institutional dependability, financial dignity, transparency, and accessible empowerment. Visual metaphors draw inspiration from physical ledger registers, official passbooks, and clear demarcation boards, reinterpreted as a refined, modern digital utility.

## Colors
The color architecture relies on high-contrast grounding:

- **Primary (`#14532d`)**: Deep Civic Forest Green. Represents economic stability, agriculture, prosperity, and state endorsement. Used for primary app bars, high-priority interactive buttons, authoritative confirmations, and core visual anchors.
- **Secondary (`#b45309`)**: Warm Earth / Mustard Amber. Represents capital, financial metrics, loan disbursement counters, warnings, and pending operational steps.
- **Tertiary (`#1e293b`)**: Deep Slate. Used for structural iconography, secondary actions, and high-emphasis analytical data points.
- **Neutral Canvas (`#fbfbfa`)**: Warm cream-tinted off-white reducing screen glare under direct sunlight in field environments, paired with `#f4f4f0` for secondary structural wells and `#ffffff` for elevated record cards.
- **Data Confidence States**:
  - *VERIFIED*: `#166534` text with `#dcfce7` tint background.
  - *OBSERVED*: `#0369a1` text with `#e0f2fe` tint background.
  - *ESTIMATED*: `#b45309` text with `#fef3c7` tint background.

## Typography
Typography is tuned for bilingual English and Devanagari (Hindi) legibility. 

- **Primary Body and Data Labels**: Set in **Noto Sans** to guarantee uniform x-height, clear conjunctive ligatures in Devanagari, and open counters that remain sharp on entry-level Android devices and high-glare field environments.
- **Headlines and Key Financial Totals**: Set in **Plus Jakarta Sans**, offering geometric clarity, distinct numeral shapes for currency figures (avoiding digit confusion between 0, 6, 8, and 9), and robust structural authority.
- Every typographic tier enforces minimum contrast ratios of 4.5:1 against surfaces (with body and critical labels exceeding 7:1 against card backgrounds using `#0f172a`).

## Layout & Spacing
The layout adheres to a fluid, vertical rhythm structured around a 4-column layout on mobile, 8 columns on tablet, and 12 columns on desktop kiosks and administrative terminals.

- **Mobile First Focus**: The primary interaction environment is handled within a single-hand thumb-zone framework. Key controls, actionable cards, and voice prompt activators remain pinned or docked within safe viewport boundaries.
- **Generous Touch Targets**: All actionable surface rows, selectors, and form elements enforce a strict minimum interactive dimension of 48x48 CSS pixels.
- **Vertical Rhythm**: Layout blocks use `space-md` (16px) internally and `space-lg` (24px) between independent contextual clusters to eliminate clutter without causing excessive scrolling.

## Elevation & Depth
Depth in this design system is established through **tonal separation and low-contrast borders**, rejecting heavy skeuomorphic drop shadows or ephemeral glass transparency:

- **Level 0 (Canvas Base)**: `#fbfbfa` warm neutral floor.
- **Level 1 (Card & Actionable Pods)**: Pure `#ffffff` surface, outlined with a 1px solid `#e2e8f0` border, resting with an ambient hairline drop (`0 1px 3px rgba(15, 23, 42, 0.05)`).
- **Level 2 (Active Sheets & Financial Summaries)**: `#ffffff` surface with a reinforced `1px solid #cbd5e1` edge and focused elevation shadow (`0 4px 12px -2px rgba(15, 23, 42, 0.08)`).
- **Level 3 (Modal Advisory Sheets & Overlays)**: Bounded by a high-clarity dim scrim (`rgba(15, 23, 42, 0.45)`), framed with high visual borders to retain edge perception under bright outdoor daylight.

## Shapes
A restrained roundedness level (`roundedness: 1`) provides a sturdy, utilitarian structure reminiscent of official documents, while softening touch targets just enough to indicate digital interactability:

- Interactive inputs, buttons, and system badges utilize `0.25rem` (4px) to `0.5rem` (8px) radii.
- Surface cards and bottom-docked sheets use a maximum corner radius of `0.75rem` (12px).
- Full pills (`9999px`) are exclusively reserved for atomic state tags (such as financial confidence chips and operational status labels) to separate metadata chips visually from standard card panels.

## Components

### Buttons & Interactive Controls
- **Primary Civic Action**: `#14532d` background, `#ffffff` bold text, minimum height 48px, minimum horizontal padding 20px. Focused states highlight with a 2px `#b45309` outer ring.
- **Secondary Action**: `#ffffff` background with 1.5px `#14532d` border and `#14532d` text.
- **Audio / Voice Assist Toggle**: Prominent 52px floating or embedded high-contrast pill with audio waveform icon, pairing `#b45309` background and white text for non-literate navigation.

### Financial Status Pills (Confidence Architecture)
- **VERIFIED**: Text `#166534`, background `#dcfce7`, border `1px solid #bbf7d0`. Used for Aadhaar-authenticated, GST, or bank-statement validated records.
- **OBSERVED**: Text `#0369a1`, background `#e0f2fe`, border `1px solid #bae6fd`. Used for field-officer geo-tagged inputs and self-reported bills.
- **ESTIMATED**: Text `#92400e`, background `#fef3c7`, border `1px solid #fde68a`. Used for AI cash-flow projections and algorithmic credit scoring.
- All pills feature uppercase `label-sm` typography with an optional prefixed status icon.

### Form Inputs & Selectors
- Minimum input target height of 52px with 16px horizontal internal padding.
- Base state: `#ffffff` surface, `#e2e8f0` border (1.5px), `#0f172a` body text.
- Focus state: `#14532d` border (2px), `#f0fdf4` subtle background highlight.
- Bilingual labels stacked systematically: Primary regional language above in `body-sm`, English counterpart inline in `label-sm` muted slate (`#64748b`).

### Advisory & Financial Metric Cards
- Grounded on `#ffffff` with a subtle left-edge status bar (4px thick): `#14532d` for working capital, `#b45309` for debt exposure, and `#0284c7` for scheme eligibility.
- Currency display prominently scales with `numeric-currency` styling, ensuring the rupee sign (`₹`) and values are unmistakably clear at arm's length.