---
name: Apex Quant Terminal
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#ffb3ad'
  on-secondary: '#68000a'
  secondary-container: '#a40217'
  on-secondary-container: '#ffaea8'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#00b2d0'
  on-tertiary-container: '#003f4b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#ffdad7'
  secondary-fixed-dim: '#ffb3ad'
  on-secondary-fixed: '#410004'
  on-secondary-fixed-variant: '#930013'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0em
  body-lg:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0em
  body-md:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
    letterSpacing: 0.01em
  data-display:
    fontFamily: JetBrains Mono
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.03em
  data-mono-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: -0.01em
  data-mono-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0em
  data-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 0.5rem
  margin: 0.75rem
  space-xs: 0.125rem
  space-sm: 0.25rem
  space-md: 0.5rem
  space-lg: 0.75rem
  space-xl: 1rem
---

## Brand & Style

The design system establishes a high-performance, institutional-grade analytics environment engineered for professional derivatives traders and quantitative researchers tracking NSE Nifty 50 intraday dynamics. 

### Philosophy & Visual Tone
The visual narrative rejects consumer-grade softness in favor of dense, precision-focused terminal aesthetics inspired by Bloomberg Terminal, TradingView Pro, and advanced algorithmic execution engines. The interface evokes calculated authority, absolute speed, and zero latency. The environment is structured to prevent cognitive fatigue during multi-hour market sessions while enabling instant, high-contrast pattern recognition across volatile order books, option chains, open interest (OI) shifts, and Greeks.

### Aesthetics & Stylistic Direction
- **Data-Dense Modern Minimalist & Technical Utilitarian:** Minimal decorative chrome, maximized viewport real estate for continuous visual telemetry, compact vertical metric stacks, and structural separation via hair-thin borders rather than spatial voids.
- **Controlled Luminescence:** Deep matte obsidian-slate backgrounds anchor the canvas, while selective, saturated phosphors (emerald, crimson, cyan, amber) deliver high-impact signals without color bleed.
- **Instrument Precision:** Geometry is tight, crisp, and predictable. Typography enforces strict tabular number alignment to ensure numbers never shift horizontal positions under rapid streaming updates.

## Colors

The color architecture is built around a non-negotiable functional hierarchy designed specifically for derivatives market structures.

### Functional Palette Mapping
- **Primary (`#10B981` / Emerald 500):** Bullish sentiment, Call Open Interest accumulation, positive Greek exposures (+Delta, +Gamma), long additions, bid dominance. Soft positive accent: `#22C55E`.
- **Secondary (`#EF4444` / Crimson 500):** Bearish sentiment, Put Open Interest dominance, negative Greek exposures (-Delta), short additions, ask/offer pressure. Soft negative accent: `#F43F5E`.
- **Tertiary (`#06B6D4` / Cyan 500):** At-the-Money (ATM) indicators, spot price equilibrium markers, implied volatility (IV) curves, and real-time execution tracers. Accent amber (`#F59E0B`) acts as a secondary spotlight for high-volatility spikes, PCR thresholds, and strike straddle midpoints.
- **Neutral (`#0B0F19` Base Canvas):** Multi-tiered slate-obsidian framework preventing eye strain:
  - Surface Void (Canvas): `#070A10`
  - Surface Base (Panels, Grid Cells): `#0B0F19`
  - Surface Elevated (Cards, Modal Drawers): `#111827`
  - Surface Highlight (Hover rows, Active Toggles): `#1F2937`
  - Subtle Border / Hairlines: `#1E293B`
  - High-Contrast Border: `#334155`

### Signal-to-Noise Ratio Rules
1. **Never use color for decoration:** Green and red are strictly semantic indicators of market direction or delta change.
2. **Desaturated Text Scales:** Text uses clean, non-glare off-white (`#F8FAFC`) for primary prices, muted slate (`#94A3B8`) for table column headers, and dimmed iron (`#64748B`) for static metadata/units.
3. **Heatmap & OI Shading:** Use low-opacity alpha fills (`rgba(16, 185, 129, 0.12)` for Call OI builds, `rgba(239, 68, 68, 0.12)` for Put OI builds) with saturated solid borders to preserve legibility of embedded numerical values.

## Typography

The typographic hierarchy separates contextual structure from raw data parsing through a dual-grotesque and monospace pairing.

### Type System Roles
- **Headlines (`Space Grotesk`):** Provides a sharp, tech-forward, institutional feel for board titles, major index tags (NIFTY 50, BANKNIFTY), modal titles, and summary KPIs.
- **UI & Structural Copy (`Geist`):** Delivers neutral, clean readability for table controls, tooltips, parameter labels, filters, and notifications.
- **Real-Time Data & Ticker Telemetry (`JetBrains Mono`):** Dedicated exclusively to strike prices, Greeks (Delta, Gamma, Vega, Theta), bids/asks, order volumes, and financial metrics. Monospace characters guarantee fixed-width tabular alignment (`font-variant-numeric: tabular-nums`), eliminating jitters when WebSocket price ticks stream in.

### Editorial Rules
- All table column headers use `label-caps` in uppercase with a muted color (`#64748B`) to anchor dense vertical columns.
- Positive and negative signs (`+`, `-`) must be permanently rendered in the data string to prevent layout shifting between directional turns.

## Layout & Spacing

The terminal uses an ultra-compact fluid docking layout optimized for maximum screen efficiency across dual-monitor desktop setups down to mobile trading views.

### Layout Mechanics
- **Grid Architecture:** Multi-pane fluid dashboard model with 12 structural columns. Each analytics viewport (e.g., Option Chain, PCR Gauge, Max Pain Chart, Multi-Strike IV) sits in a modular widget container.
- **Rhythm & Gaps:** Spacing conforms to an ultra-dense scale where `space-sm` (4px) and `space-md` (8px) govern the majority of component internal layouts. The outer canvas maintains a tight `0.75rem` margin to maximize analytical data space.

### Responsive Breakpoints & Adaptations
- **Desktop Pro (`>= 1440px`):** 3-pane split view (Left: Market Depth & PCR/Greeks Heatmap; Center: Full Depth Option Chain with Straddle Stacks; Right: Live Order Flow & Order Entry). Zero full-page scroll; each panel has isolated virtualization.
- **Laptop / Tablet (`768px - 1439px`):** Center option chain remains primary with collapsible left/right sidebars accessible via high-density micro tabs.
- **Mobile (`< 768px`):** Single-column stacked stream. Option chain switches from dual-wing layout (Calls on left, Puts on right) to a unified vertical strike card format with horizontal strike sliders.

## Elevation & Depth

Visual hierarchy avoids atmospheric drop shadows, which obscure dense financial data, in favor of a low-contrast structural outline model paired with distinct tonal surface layers.

### Surface Hierarchy
- **Level 0 (Canvas Backing):** Deep Obsidian (`#070A10`). Visible only between widget splitters and frame margins.
- **Level 1 (Docked Containers & Tables):** Surface Dark (`#0B0F19`) surrounded by a 1px ghost border (`#1E293B`).
- **Level 2 (Active Toolbars, Strike Highlight Banners):** Surface Slate (`#111827`) with inner hair-line highlights (`rgba(255, 255, 255, 0.05)`).
- **Level 3 (Modals, Context Menus, Float Tooltips):** Surface Overlay (`#1A2234`) with a high-contrast boundary (`#334155`) and an ambient, compact drop shadow (`0 4px 16px rgba(0, 0, 0, 0.6)`).

### ATM Spot Highlight & Glow Rules
- The current Spot Price row in the option chain acts as the physical horizon. It breaks table layering with a luminous edge: a 1px border of Cyan 500 (`#06B6D4`) with a restricted ambient glow (`box-shadow: 0 0 10px rgba(6, 182, 212, 0.2)`).

## Shapes

The design system enforces a precise, soft-edge geometry (`0.25rem` / `4px`) to preserve a professional, instrument-grade appearance while eliminating visual harshness.

### Corner Radius System
- **Base Shape (`roundedness: 1` / 4px):** Applied systematically to buttons, input fields, interactive chips, table row indicators, and dropdown menus.
- **Panels & Dashboard Cards (`rounded-lg` / 8px):** Structural viewport containers, modal windows, and flyout menus.
- **Pill Geometry (Restricted):** Exclusively allocated to live connection pulses (`Websocket Active`), ATM strike tags, and bullish/bearish net market regime chips.

## Components

### 1. Option Chain Data Table
- **Layout:** Bilateral matrix split down the center. Call data (LTP, Change, OI, Chg in OI, Volume, IV, Delta) on the left; Strike Ladder pinned in the center; Put data mirrored on the right.
- **Row Styling:** Tabular lines use 1px borders (`#1E293B`). Table rows have a default height of 32px to guarantee maximum strike visibility per viewport.
- **Heatmap Cell Bars:** Inline horizontal bar indicators within the `OI` and `OI Change` columns. Green bars anchor right-to-left for Calls; red bars anchor left-to-right for Puts, calculated relative to the session's max strike OI.
- **Hover State:** Entire horizontal strike crosshair (Calls + Strike + Puts) highlights with background `#161F30`.

### 2. Interactive Toggle Chips
- **Purpose:** Segment switches (e.g., Expiry dates: `06 MAR`, `13 MAR`, `27 MAR`; Metrics: `OI`, `Greeks`, `Volume`).
- **Style:** Compact height (24px), font `data-mono-sm`. Idle state: `#111827` background, `#94A3B8` text, `#1E293B` border. Active state: `#1E293B` background, `#F8FAFC` bold text, with a 1.5px bottom indicator border in `#06B6D4` (Cyan).

### 3. Action Buttons
- **Buy / Long / Call:** Solid emerald fill (`#10B981`), black bold text (`#022C22`), instant active feedback, micro border radius (4px).
- **Sell / Short / Put:** Solid crimson fill (`#EF4444`), white bold text (`#FFFFFF`), micro border radius (4px).
- **Terminal Control / Utility:** Transparent fill, ghost border (`#334155`), muted icon/text, shifts to `#1F2937` on hover.

### 4. Input Fields & Spinners
- **Numeric Strike & Lot Inputs:** Monospace font (`JetBrains Mono`), dense padding (`4px 8px`), dark slate fill (`#0B0F19`), sharp focus state featuring a 1px `#06B6D4` outline.
- **Micro Incrementers:** Pinned stepper buttons (`+`, `-`) built directly into the field edge for zero-keyboard quantity adjustments.

### 5. Sentiment Gauges & Market Meters
- **PCR (Put-Call Ratio) Meter:** Horizontal bi-directional gradient bar with a floating pointer diamond. Ratios > 1.2 lean Emerald; < 0.8 lean Crimson; 0.8 to 1.2 remain Neutral Slate with Cyan markers.
- **Max Pain & Strike Distribution:** Compact bar charts rendered with crisp 1px borders, matching the system's emerald/crimson rules, overlaid with a dotted vertical line marking current spot price.