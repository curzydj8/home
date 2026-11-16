---
name: Mars Geek Cyber Portal
colors:
  surface: '#0e1322'
  surface-dim: '#0e1322'
  surface-bright: '#343949'
  surface-container-lowest: '#090e1c'
  surface-container-low: '#161b2b'
  surface-container: '#1a1f2f'
  surface-container-high: '#25293a'
  surface-container-highest: '#2f3445'
  on-surface: '#dee1f7'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#dee1f7'
  inverse-on-surface: '#2b3040'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#5de6ff'
  on-secondary: '#00363e'
  secondary-container: '#00cbe6'
  on-secondary-container: '#00515d'
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
  secondary-fixed: '#a2eeff'
  secondary-fixed-dim: '#2fd9f4'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#004e5a'
  tertiary-fixed: '#e0e0ff'
  tertiary-fixed-dim: '#bdc2ff'
  on-tertiary-fixed: '#000767'
  on-tertiary-fixed-variant: '#2f3aa3'
  background: '#0e1322'
  on-background: '#dee1f7'
  surface-variant: '#2f3445'
typography:
  display:
    fontFamily: Inter, PingFang SC, sans-serif
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: 4rem
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Inter, PingFang SC, sans-serif
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter, PingFang SC, sans-serif
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter, PingFang SC, sans-serif
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter, PingFang SC, sans-serif
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter, PingFang SC, sans-serif
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Inter, PingFang SC, sans-serif
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Inter, PingFang SC, sans-serif
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Inter, PingFang SC, sans-serif
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-code:
    fontFamily: JetBrains Mono, monospace
    fontSize: 0.8125rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Inter, PingFang SC, sans-serif
    fontSize: 0.75rem
    fontWeight: '700'
    lineHeight: 1rem
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system establishes a futuristic, high-focus developer aesthetic tailored for "火星极客" (Mars Geek). It balances deep space darkness with luminous cyan-tinted instrumentation, evoking the precision of an interplanetary control terminal and the ergonomic clarity of a high-performance developer workspace.

The emotional signature is focused, state-of-the-art, and intellectually empowering. Rather than chaotic cyberpunk neon, the interface channels disciplined cyber-minimalism: dark, layered, high-contrast surfaces punctuated by precision-tuned cyan glowing edges, laser-sharp typography, and translucent glass overlays.

## Colors
The palette relies on a hierarchy of dark navy voids and vivid ion-thruster accents:

- **Background Canvas (`#0A0F1E`)**: Deep space near-black navy providing absolute contrast and immersion without pure black eye fatigue.
- **Card & Base Surfaces (`#111827`, `#1E293B`)**: Stratified tiers of muted slate navy that ground components and delineate modular learning hubs.
- **Brand Glow & Focus (`#38BDF8`, `#22D3EE`)**: Primary and secondary luminescent cyans reserved for telemetry badges, active states, progress indicators, and ethereal edge highlights.
- **Tertiary Accent (`#818CF8`)**: Soft deep-violet for multi-discipline tagging, advanced module markers, and subtle secondary gradients.
- **Content Contrast**: High-clarity primary typography in Ice White (`#F8FAFC`) with auxiliary metadata, terminal prompts, and inactive labels in Cool Slate (`#94A3B8`).

## Typography
The system unifies Latin geometric clarity with CJK ideographic precision through `Inter` paired with system-level `PingFang SC`. Monospaced developer tags, telemetry telemetry, and progress statistics strictly leverage `JetBrains Mono`.

- **Headlines**: Tight negative tracking (-0.02em to -0.03em) on display sizes ensures headlines feel solid, dense, and architectural.
- **Bilingual Balance**: Line-heights for Chinese glyphs remain at an ergonomic minimum of 1.4x to 1.6x to prevent dense character collision in complex technical terminologies.
- **Code & Metadata**: `label-code` and `label-caps` inject technical authority into section headers, completion counters, and course code markers.

## Layout & Spacing
The layout follows a 12-column responsive fluid grid pinned to a maximum canvas width of 1440px to retain terminal-like containment.

- **Desktop (1024px+)**: 12 columns with 24px (`1.5rem`) gutters and 32px (`2rem`) outer canvas margins. Elements align in functional modular blocks (e.g., 8-column main study track + 4-column telemetry sidebar).
- **Tablet (768px - 1023px)**: 8 columns with 16px gutters and 24px margins. Side panels collapse into stacked tab sections.
- **Mobile (&lt;768px)**: 4 columns with 12px gutters and 16px outer margin. Layout flows vertically with horizontal card snapping for learning milestones and course decks.

## Elevation & Depth
Depth is created through ambient backlights, glass diffusion, and semi-transparent structural borders rather than conventional muddy drop shadows:

- **Surface Tier 0 (Canvas)**: Solid `#0A0F1E` punctuated by deep radial gradient backdrops (`rgba(56, 189, 248, 0.05)` at 800px blur radius).
- **Surface Tier 1 (Containers)**: `#111827` rendered at 80% opacity with `backdrop-filter: blur(16px)` and a hairline border of `1px solid rgba(255, 255, 255, 0.06)`.
- **Surface Tier 2 (Hover & Active Cards)**: `#1E293B` highlighted with an outer glow: `box-shadow: 0 0 24px -4px rgba(56, 189, 248, 0.25), inset 0 1px 0 0 rgba(34, 211, 238, 0.4)`.
- **Luminescent Overlays**: Primary actions and interactive nodes use directional edge borders created via linear gradients running from `#38BDF8` to `#22D3EE` at 0.4 to 0.8 alpha.

## Shapes
The portal embraces `roundedness: 2` (base 0.5rem / `rounded-2xl` reaching 1rem to 1.5rem) to soften the aggressive sci-fi geometry into an inviting, premium dashboard feel.

- **Main Cards & Panels**: Default to `1rem` (16px) or `1.5rem` (24px) border radius, giving them a sleek glass-slate appearance.
- **Buttons & Tags**: Retain a compact `0.5rem` (8px) radius for crisp visual tension against large, expansive card boundaries.
- **Avatars & Radar Nodes**: Fully circular (`rounded-full`) to contrast against the modular structural grid.

## Components

### Buttons
- **Primary Cyber Action**: Gradient background (`linear-gradient(135deg, #38BDF8, #22D3EE)`) with black bold text (`#0A0F1E`), 0.5rem radius, and a permanent soft cyan flare (`0 0 16px rgba(34, 211, 238, 0.35)`). Active transform `scale(0.98)`.
- **Secondary Ghost Action**: Transparent glass surface with `1px solid rgba(56, 189, 248, 0.3)`, text in `#F8FAFC`. On hover, border illuminates to `#38BDF8` with a deep navy surface fill (`#1E293B`).

### Learning Track Cards
- Encased in `rounded-2xl` surfaces (`#111827` at 85% opacity with 12px blur).
- Hairline stroke in `rgba(56, 189, 248, 0.15)` on idle, transitioning to an edge gradient of `#38BDF8` to `#22D3EE` with a 20px cyan halo on hover.
- Includes progress bars featuring neon glowing tips and `JetBrains Mono` percentage metrics.

### Chips & Badges
- Pill or 6px-radius markers with background `rgba(56, 189, 248, 0.1)` and border `1px solid rgba(56, 189, 248, 0.25)`.
- Text styled in `label-code` using `#38BDF8` for course levels (e.g., `L4_KERNEL_DEV`) and `#818CF8` for advanced electives.

### Input Fields & Terminal Prompts
- Dark inset backgrounds (`#0A0F1E`) with `1px solid rgba(148, 163, 184, 0.2)`.
- Focus shifts border to `#22D3EE` accompanied by a localized inner glow (`inset 0 0 8px rgba(34, 211, 238, 0.2)`).
- Caret is styled with vibrant `#38BDF8` pulse.

### Progress & Telemetry Nodes
- Hexagonal or circular mini-dials representing study streaks, XP, and topic mastery.
- Subtle SVG progress rings illuminated with linear cyan-blue gradients and monospace readouts.