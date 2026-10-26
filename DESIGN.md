---
name: Tawazun Financial
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#40000d'
  on-tertiary-container: '#f23d5c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdadb'
  tertiary-fixed-dim: '#ffb2b7'
  on-tertiary-fixed: '#40000d'
  on-tertiary-fixed-variant: '#92002a'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 30px
  headline-sm:
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
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: IBM Plex Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
  metric-display:
    fontFamily: IBM Plex Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1rem
  margin-tablet: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system targets small-to-medium enterprise owners, regional merchants, and independent entrepreneurs across Arabic-speaking markets. The tone is authoritative, precise, and reassuring, communicating institutional-grade reliability without enterprise friction.

The visual direction follows **Modern Corporate Tactility** rooted in RTL-first principles:
- **Atmosphere**: Confident, luminous, and structured. Clean off-white canvases allow rich dark navy foundations and vibrant fiscal indicators (emerald for surplus, rose for outflow) to establish instant financial clarity.
- **Micro-metaphors**: Financial records feel crisp, ledger-accurate, and tangible through precise borders, subtle structural elevation, and disciplined tabular data alignment.
- **RTL-Native Ergonomics**: Visual weight flows naturally from right to left, with numerical amounts, trend arrows, currency marks, and status iconography aligned to regional reading habits and financial conventions.

## Colors

The palette balances structural authority with intuitive fiscal polarity:

- **Primary (`#0F172A` - Deep Slate Navy)**: Acts as the primary anchor for dominant structural elements, headers, high-emphasis text, and core navigation cards.
- **Secondary (`#10B981` - Rich Emerald)**: Reserved for positive revenue, net gain, successful reconciliations, and primary action affirmations.
- **Tertiary (`#F43F5E` - Precision Coral/Rose)**: Represents operational costs, unpaid invoices, deficit balances, and tax liabilities. Avoids aggressive alarmist reds in favor of an elegant, ledger-grade rose tone.
- **Neutral (`#64748B` - Slate Grey)**: Supplies balanced secondary information, ledger subtexts, table headers, and inactive states.

### Surface and Border Specifications
- **Canvas (`#F8FAFC`)**: A clinical, cool off-white that prevents screen glare during prolonged bookkeeping tasks.
- **Surface Elevation (`#FFFFFF`)**: Pure white card surfaces providing crisp contrast against the base canvas.
- **Structural Outlines (`#E2E8F0`)**: Hairline borders defining cards, metric cells, and divider ribbons without visual clutter.

## Typography

Typography relies on **IBM Plex Sans** (encompassing IBM Plex Sans Arabic for native Arabic scripts and Western glyph sets). Its engineered, geometric curves reinforce structured financial accounting.

### Typographic Principles
- **Numeral Rendering**: Financial figures must use tabular lining figures (`font-variant-numeric: tabular-nums`) to guarantee column-by-column vertical alignment across ledgers and invoices.
- **RTL Baseline Alignment**: Latin currency codes (e.g., `SAR`, `AED`, `USD`) and Arabic denominations (e.g., `ر.س`) must sit aligned to the Arabic text baseline without vertical clipping or irregular leading.
- **Weight Pairing**: Headers employ bold weights (`700`) to anchor scanning eyes, while secondary values and metadata use medium (`500`) and regular (`400`) weights for clear informational hierarchy.

## Layout & Spacing

Layouts follow a structured **fluid grid** calibrated for modern smartphone viewports (360px to 430px wide) with seamless scaling up to merchant point-of-sale tablets:

- **Mobile Rhythm**: Base screen margins are fixed at `1rem` (16px), allowing maximum horizontal canvas for multi-column accounting tables and data summaries.
- **Internal Ledger Rhythm**: Spacing scales strictly in multiples of 4px. Metric cards, transactional line items, and list rows maintain compact vertical padding (`space-md` / 12px) to optimize content density on handheld displays.
- **Table Adaptability**: Financial ledgers employ sticky right-hand title columns for item descriptions, with horizontal scroll ribbons accommodating SKU, Tax, Unit Price, and Balance values.

## Elevation & Depth

This design system avoids heavy drop shadows, relying instead on **low-contrast borders combined with subtle ambient depth** to represent physical accounting sheets:

- **Surface Base**: Default background at `#F8FAFC`.
- **Card Tier (Level 1)**: Primary containers rest on pure `#FFFFFF` bounded by a 1px border of `#E2E8F0`. Elevation is accented by an ambient shadow: `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`.
- **Floating Controls (Level 2)**: Sticky navigation bars, floating quick-invoice actions, and modal action sheets leverage heightened depth: `box-shadow: 0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.03)` with a hairline boundary of `#E2E8F0`.
- **State Overlays**: Selected table rows or active fiscal periods receive a tinted background of `#0F172A` at 3% opacity (`rgba(15, 23, 42, 0.03)`) with zero blur alteration.

## Shapes

A medium roundedness level (`2`) balances professional ledger stability with modern, touch-friendly mobile ergonomics:

- **Standard Containers (`0.5rem` / 8px)**: Inputs, operational list items, table container envelopes, and primary action buttons.
- **Cards & Summary Surfaces (`1rem` / 16px)**: High-level metric panels, balance overview cards, and modal dialogs.
- **Badges & Pill Identifiers (`9999px`)**: Status flags (e.g., Paid, Overdue, Draft) and category filter chips maintain pill contours to clearly distinguish metadata from clickable rectangular cards.

## Components

### 1. Primary & Secondary Buttons
- **Primary Action (Create Invoice, Reconcile)**: Background `#0F172A`, text `#FFFFFF`, border-radius `0.5rem`, height `48px`. Pressed state scales to `0.98` with background `#1E293B`.
- **Success Action (Approve Payment, Settle)**: Background `#10B981`, text `#FFFFFF`.
- **Secondary / Ghost**: Background transparent, 1px solid border `#E2E8F0`, text `#0F172A`.

### 2. Financial Metric & Balance Cards
- **Structure**: Surface `#FFFFFF`, border `1px solid #E2E8F0`, corner radius `1rem`, padding `space-lg`.
- **KPI Metrics**: Arabic descriptor aligned right in `label-md` (`#64748B`), followed by the monetary total in `metric-display` (`#0F172A`) using tabular numerals.
- **Trend Indicators**: Tagged with contextual pill badges. Positive delta uses `#10B981` (10% tint background, solid text, right-facing green arrow). Outflows use `#F43F5E` (10% tint background, solid text, left-facing rose arrow).

### 3. Financial Status Chips & Badges
- **Paid / مكتمل**: Background `#ECFDF5`, text `#059669`, border `1px solid #A7F3D0`.
- **Pending / معلق**: Background `#FFFBEB`, text `#D97706`, border `1px solid #FDE68A`.
- **Overdue / متأخر**: Background `#FFF1F2`, text `#E11D48`, border `1px solid #FECDD3`.
- **Draft / مسودة**: Background `#F1F5F9`, text `#475569`, border `1px solid #CBD5E1`.

### 4. Accounting Tables & Ledger Rows
- **List Rows**: Minimal alternating shading; separated by a 1px solid `#F1F5F9` bottom divider.
- **Header Cells**: Label font `label-sm`, text `#64748B`, background `#F8FAFC`, right-aligned text alignment.
- **Amounts**: Numeric values right-aligned relative to currency abbreviations. Negative entries display `-1,250.00 ر.س` in `#F43F5E`; positive entries display `+4,800.00 ر.س` in `#10B981`.

### 5. Form Fields & Monetary Inputs
- **Base Style**: Height `48px`, border `1px solid #CBD5E1`, background `#FFFFFF`, text `#0F172A`, radius `0.5rem`.
- **Focus State**: Border color `#0F172A`, 2px outer outline with `#0F172A` at 10% opacity.
- **Currency Affix**: Arabic currency symbol (`ر.س`) permanently docked on the visual left (for RTL forms) inside a shaded container `#F1F5F9` to eliminate input ambiguity.

### 6. Interactive Checkboxes & Radio Selectors
- **Selection Box**: 20px by 20px square, 4px border radius. Unchecked state uses `#CBD5E1` border. Checked state uses solid `#0F172A` fill with a white checkmark.