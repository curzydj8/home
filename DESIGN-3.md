---
name: Mars Geek Space Deck
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#89ceff'
  on-secondary: '#00344d'
  secondary-container: '#00a2e6'
  on-secondary-container: '#00344e'
  tertiary: '#c5c9ff'
  on-tertiary: '#131e8c'
  tertiary-container: '#a3abff'
  on-tertiary-container: '#2c37a0'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#7bd0ff'
  on-primary-fixed: '#001e2c'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#89ceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004c6e'
  tertiary-fixed: '#e0e0ff'
  tertiary-fixed-dim: '#bdc2ff'
  on-tertiary-fixed: '#000767'
  on-tertiary-fixed-variant: '#2f3aa3'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  headline-xl:
    fontFamily: Inter, 'PingFang SC', 'Microsoft YaHei', sans-serif
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter, 'PingFang SC', 'Microsoft YaHei', sans-serif
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter, 'PingFang SC', 'Microsoft YaHei', sans-serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter, 'PingFang SC', 'Microsoft YaHei', sans-serif
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter, 'PingFang SC', 'Microsoft YaHei', sans-serif
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter, 'PingFang SC', 'Microsoft YaHei', sans-serif
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter, 'PingFang SC', 'Microsoft YaHei', sans-serif
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: '''JetBrains Mono'', monospace'
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: '''JetBrains Mono'', monospace'
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: '''JetBrains Mono'', monospace'
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system establishes a high-performance, futuristic personal telemetry hub for technologists, autodidacts, and engineering polymaths. It positions continuous learning as an orbital expedition: rigorous, high-precision, focused, and instrument-driven. 

The aesthetic blends **Modern Dark Terminal UI** with **Cybernetic Neon Minimalism**. It avoids chaotic cyberpunk clutter in favor of crisp mission-control dashboards, combining deep aerospace navy foundations with luminous cyan and sky-blue signal lines. The interface conveys total mastery, intellectual momentum, and technical depth. Interactions should feel frictionless, weighted with subtle luminous glows and ultra-responsive state shifts.

## Colors

The palette leverages a dark-field strategy engineered for prolonged nocturnal research and complex data parsing without cognitive strain:

- **Primary Canvas (`#0F172A`)**: The deep space void. Anchors the visual hierarchy with maximum contrast stability.
- **Card Surfaces (`#1E293B`)**: Raised structural planes for modular dashboard widgets.
- **Surface Borders (`#334155`)**: Subdued delineation defining spatial grid integrity.
- **Signal Primaries (`#38BDF8` & `#0EA5E9`)**: High-luminance cyan/sky blues used strictly for active states, key data trajectories, progression rings, and energetic interaction cues.
- **Secondary Accent (`#818CF8`)**: Deep periwinkle reserved for system metadata, algorithmic tags, and secondary skill branches.
- **Typography Neutrals**: `#F8FAFC` for high-impact operational text and numeric readouts; `#94A3B8` for supportive meta-labels and structural subheadings.

## Typography

Typography prioritizes bilingual clarity across Latin and Simplified Chinese glyphs. 

- **Primary Body and Headlines**: Fallbacks cascade through `Inter`, `PingFang SC`, and `Microsoft YaHei` to guarantee consistent optical balance between dense Chinese strokes and geometric Latin alphabets.
- **Technical Readouts**: `JetBrains Mono` handles metric feeds, status pills, code snippets, orbital coordinates, and time counters to preserve the utilitarian mission console tone.
- Text contrast must rigorously clear WCAG AAA on dark surfaces: never dip below `#94A3B8` for tertiary details.

## Layout & Spacing

The layout utilizes a structured 12-column modular grid built for customizable widgets, telemetry streams, and linear learning tracks.

- **Desktop (1280px+)**: 12-column layout with `2rem` margins and `1.5rem` gutters. Accommodates high-density side panels (learning progress, active syllabi) alongside central study terminals.
- **Tablet (768px - 1279px)**: 8-column layout with `1.5rem` margins and `1rem` gutters. Side panels collapse into tabbed auxiliary trays.
- **Mobile (< 768px)**: 4-column layout with `1rem` margins and `1rem` gutters. Widgets stack vertically into fluid cards with thumb-reachable interactive anchors.
- Component-level spacing follows an absolute 4px base multiplier, using `space-xs` through `space-xl` for disciplined interior rhythmic breathing.

## Elevation & Depth

Spatial depth relies on a combination of **tonal layering**, **structural surface borders**, and **luminous energy emission**:

1. **Base Layer (L0)**: `#0F172A` — The endless viewport background.
2. **Card Base (L1)**: `#1E293B` enclosed in a precise `1px solid #334155` border. No default box shadows; separation is achieved purely via surface luminance contrast.
3. **Elevated Overlays & Popovers (L2)**: `#1E293B` layered over a backdrop blur (`backdrop-filter: blur(12px)` with `rgba(15, 23, 42, 0.75)` alpha).
4. **Neon Hover States**: When components enter an active or hover state, the border shifts to `rgba(56, 189, 248, 0.5)` complemented by a soft, diffused cyan atmospheric glow (`box-shadow: 0 0 20px -3px rgba(56, 189, 248, 0.25)`). Focus rings use a sharp double halo (`0 0 0 2px #0F172A, 0 0 0 4px #38BDF8`).

## Shapes

The interface implements a refined curvature hierarchy that balances technical precision with modern ergonomics:

- **Dashboard Cards and Modules**: Standard `0.5rem` (8px) corner radius, preserving the modular grid's structural tension.
- **Badges, Status Chips, and Action Triggers**: Scaled into complete capsule/pill formations (`9999px` border-radius) to distinctively differentiate interactive chips from structural containers.
- **Nested Progress Tracks and Sliders**: Full pill rounding to maintain a fluid, hydraulic energy bar aesthetic.

## Components

### Buttons
- **Primary Cyber Action**: Filled with `#38BDF8`, labeled with `#0F172A` in bold font weights. On hover, shifts to `#0EA5E9` with an ambient glow (`box-shadow: 0 0 16px rgba(56, 189, 248, 0.4)`).
- **Secondary Ghost Terminal**: Background transparent, border `1px solid #334155`, text `#F8FAFC`. On hover, border transitions to `#38BDF8` with a subtle inner glow (`background: rgba(56, 189, 248, 0.05)`).
- **Radius**: Pill-shaped (`rounded-full`) for quick action buttons, `rounded-md` (8px) for modular toolbar triggers.

### Chips & Badges
- **Status Pills**: Height 24px, background `rgba(56, 189, 248, 0.1)`, border `1px solid rgba(56, 189, 248, 0.3)`, text `#38BDF8`. Uses `JetBrains Mono` in `label-sm`.
- **System Indicator**: Prepends a 6px circular neon dot with a pulsing ambient radial flare (`box-shadow: 0 0 8px #38BDF8`) to indicate live telemetry or active courses.

### Input Fields & Search Bars
- **Surface**: Solid `#1E293B` with border `1px solid #334155`, text `#F8FAFC`, placeholder `#64748B`.
- **Focus**: Border shifts immediately to `#38BDF8` with zero latency, paired with `box-shadow: 0 0 0 1px #38BDF8, 0 0 12px rgba(56, 189, 248, 0.2)`.

### Cards & Learning Modules
- **Container**: Background `#1E293B`, border `1px solid #334155`, corner radius `8px`.
- **Header**: High-contrast title (`#F8FAFC`) paired with a monospace progress indicator (`#94A3B8`).
- **Interactive State**: Elevates border to `rgba(56, 189, 248, 0.4)` on mouseover, creating an instant atmospheric highlight without physical displacement.

### Checkboxes & Radios
- **Frame**: 18px box or ring with `#334155` border and `#0F172A` background.
- **Checked**: Filled with `#38BDF8` displaying a deep charcoal `#0F172A` icon checkmark, surrounded by a 4px soft outer cyan luminescence.

### Data & Telemetry Widgets (Mars Geek Specials)
- **Progress Trackers**: Slimline 6px horizontal bars with background `#334155` and fill `#38BDF8`, terminating in a bright `#F8FAFC` energy leading edge.
- **Metric Readouts**: Large numeric displays set in `Inter` tabular figures, paired with micro-labels in uppercase `JetBrains Mono`.