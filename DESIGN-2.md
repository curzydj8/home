---
name: Mars Geek Precision Portal
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#434655'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#4e565d'
  on-tertiary: '#ffffff'
  tertiary-container: '#676e76'
  on-tertiary-container: '#eaf1fa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#dce3ec'
  tertiary-fixed-dim: '#c0c7d0'
  on-tertiary-fixed: '#151c23'
  on-tertiary-fixed-variant: '#40484f'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  code-snippet:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system embodies the intellectual rigor, curiosity, and technological clarity of a high-end personal learning nexus. Targeted at forward-thinking engineers, researchers, and technical self-learners, it presents knowledge as an engineered artifact: structural, luminous, and noise-free. 

The aesthetic style is rooted in modern technological minimalism with a deliberate focus on airy readability and precise information density. It eschews decorative excess in favor of crisp delineation, high optical clarity, and microscopic details (such as micro-borders, subtle tinting, and keyboard accelerator hints). The visual atmosphere evokes the precision of an aerospace terminal paired with the quiet sanctuary of an architect's modern studio.

## Colors
The color architecture relies on a crisp white-to-slate continuum anchored by an authoritative precision blue. 

- **Primary (`#2563EB`)**: Precision Tech Blue serves as the directional beacon. It is reserved for key calls-to-action, active navigational states, focus rings, and high-priority interactive cues. Its hover state steps down to `#1D4ED8`.
- **Secondary (`#0F172A`)**: Deep Slate 900 acts as the ultimate structural anchor for headings, primary textual signals, and high-emphasis icons.
- **Tertiary (`#EFF6FF`)**: Crisp Azure Tint, used for badge backgrounds, active item fills, and contextual tags to convey status without introducing chromatic clutter.
- **Neutral Canvas (`#FFFFFF` & `#F8FAFC`)**: The ground layer. Pure White (`#FFFFFF`) commands high-focus surfaces and cards, while the ultra-light slate canvas (`#F8FAFC`) establishes structural contrast across screen regions. A secondary neutral boundary (`#F1F5F9`) renders sunken metadata panels or tertiary button fills.
- **Borders & Dividers**: Boundary definition uses `#E2E8F0` at 1px thickness, producing structural isolation between complex knowledge blocks without optical weight.
- **Text Tiers**:
  - Primary Content / Titles: `#0F172A`
  - Secondary Explanations / Subheaders: `#475569`
  - Metadata / Placeholders / Shortcut Legends: `#94A3B8`

## Typography
The typographic hierarchy is calibrated for bilingual harmony, pairing Latin glyphs with modern Chinese sans-serif system fallbacks (`-apple-system`, `PingFang SC`, `Microsoft YaHei`). 

- Maintain generous line-heights across body text (`lineHeight: 26px` on `fontSize: 16px`) to ensure effortless scanning of technical treatises, research notes, and code summaries.
- Large titles employ subtle negative tracking (`-0.01em` to `-0.02em`) to bind headline phrases into single visual units.
- Metadata and badges utilize `label-sm` with slight uppercase tracking (`0.04em`) to establish clear hierarchy above raw numeric values, tags, and timestamps.
- Technical notations and keyboard shortcuts defer to monospaced styling (`JetBrains Mono`) to maintain spatial rhythm across inline key commands (e.g., `⌘K`).

## Layout & Spacing
The layout adheres to a 12-column fluid grid system bounded by a maximum content container of 1280px to prevent excessive line length on ultra-wide displays.

- **Desktop (1024px+)**: 12 columns with 24px (`1.5rem`) gutters and 32px (`2rem`) outer canvas margins. Hub dashboards utilize a dynamic asymmetrical split: a 3-column sticky sidebar for navigation and indexing, accompanied by a 9-column fluid stream for cards and reading panes.
- **Tablet (768px - 1023px)**: 8 columns with 20px gutters. Navigation collapses into a top utility bar or drawer.
- **Mobile (< 768px)**: 4 columns with 16px (`1rem`) gutters and 16px (`1rem`) outer margins. Card clusters stack linearly, dropping secondary column spans into uniform vertical sequences.
- Spacing rhythm maintains vertical cadence via multiples of 4px and 8px: `space-xs` (4px) for micro badge padding, `space-sm` (8px) for icon-text inline pairings, `space-md` (16px) for inner card content spacing, and `space-xl` (40px) between major architectural modules.

## Elevation & Depth
Elevation in this design system is engineered through clean surface tiering, hairline perimeter borders, and ambient light physics rather than dense shadows.

- **Resting Layer (Surface 1 / Base Cards)**:
  - Background: `#FFFFFF`
  - Border: 1px solid `#E2E8F0`
  - Shadow: `0 1px 3px 0 rgba(0, 0, 0, 0.05)`
  - Feel: Grounded, planar, flush with the technical framework.
- **Interactive Hover Layer**:
  - Background: `#FFFFFF`
  - Border: 1px solid rgba(37, 99, 235, 0.3)
  - Shadow: `0 10px 25px -5px rgba(37, 99, 235, 0.08), 0 8px 10px -6px rgba(37, 99, 235, 0.04)`
  - Motion: 200ms cubic-bezier(0.16, 1, 0.3, 1) transform translateY(-2px).
  - Effect: Gives the impression of magnetic attraction, signaling active responsiveness through precision blue refraction.
- **Overlays & Command Palettes**:
  - Background: `#FFFFFF` with slight backdrop diffusion when over dynamic lists.
  - Border: 1px solid `#CBD5E1`
  - Shadow: `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`

## Shapes
The shape language uses `roundedness: 2`, aligning with modern technical software:

- **Base Components (Inputs, Buttons, Cards, Badges)**: Feature an 8px (`0.5rem`) corner radius. This softens the mathematical severity of the grid without sacrificing structural discipline.
- **Container Elements (Panels, Large Modular Blocks, Dialogs)**: Utilize `rounded-lg` (16px / `1rem`) to form distinct geometric envelopes.
- **Key Caps & KBD Shortcuts**: Set to 4px (`rounded-sm`) to emulate physical keyboard hardware.
- **Filter Tags & Micro-pills**: May opt for full pill radii (9999px) strictly when denoting dynamic status (e.g., "Active", "Reading") to differentiate state indicators from actionable modular tiles.

## Components

### Buttons
- **Primary**: Background `#2563EB`, text `#FFFFFF`, 8px radius, height 40px, horizontal padding `space-md`. Hover shifts to `#1D4ED8`. Active state scales to `0.98`. Focus-visible exhibits an offset ring of 2px (`#2563EB`) with a 2px white gap.
- **Secondary / Ghost**: Background `#FFFFFF`, 1px solid `#E2E8F0`, text `#0F172A`. Hover transitions background to `#F8FAFC` and border to `#CBD5E1`.
- **Tertiary Tint**: Background `#EFF6FF`, text `#2563EB`, no border. Used for inline navigational links and lightweight actions.

### Knowledge Cards & Modular Grids
- Constructed on `#FFFFFF` with 1px `#E2E8F0` border and 12px or 16px corner radius.
- Padding follows `space-lg` (24px).
- Internal layout: Top row hosts categorization badges and reading time; body showcases `headline-sm` with immediate clamp to 2 lines; bottom dock contains author avatars, publish dates (`#94A3B8`), and subtle arrow icons that slide 4px rightward on hover.

### Global Search & Command Bar
- Height: 44px. Background: `#FFFFFF` or `#F8FAFC`.
- Border: 1px solid `#E2E8F0`. Focus transitions to `#2563EB` with a subtle outer glow: `0 0 0 3px rgba(37, 99, 235, 0.15)`.
- Left: 18px line-art magnifying glass in `#94A3B8`.
- Right: Inline keyboard shortcut badge container displaying `⌘K` or `Ctrl K` on `#F1F5F9`, 1px `#E2E8F0` border, `#64748B` text, 4px border radius, font-size 11px.

### Chips & Badges
- Background `#EFF6FF`, text `#2563EB`, border 1px solid rgba(37, 99, 235, 0.2).
- Font size: `label-sm` (11px), uppercase or tracked, padding 2px 8px, radius 6px or 9999px.
- Subtle neutral variants use `#F1F5F9` background with `#475569` text.

### Form Inputs & Checkboxes
- **Inputs**: Background `#FFFFFF`, border 1px solid `#E2E8F0`, text `#0F172A`, placeholder `#94A3B8`. Height 40px, padding 0 12px.
- **Checkboxes**: 18x18px, 4px corner radius. Unchecked: `#FFFFFF` with 1.5px border `#CBD5E1`. Checked: `#2563EB` fill with crisp white vector checkmark.

### Quick-Filter & Navigation Tabs
- Clean segmented switch design or borderless horizontal tabs.
- Active tab features a solid `#0F172A` or `#2563EB` bottom bar indicator (2px height) or a pill-style solid background with white text, transitioning with swift 150ms opacity fades.