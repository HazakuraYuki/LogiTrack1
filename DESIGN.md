---
name: LogiTrack Design System
colors:
  surface: '#0c1324'
  surface-dim: '#0c1324'
  surface-bright: '#33394c'
  surface-container-lowest: '#070d1f'
  surface-container-low: '#151b2d'
  surface-container: '#191f31'
  surface-container-high: '#23293c'
  surface-container-highest: '#2e3447'
  on-surface: '#dce1fb'
  on-surface-variant: '#bbcac6'
  inverse-surface: '#dce1fb'
  inverse-on-surface: '#2a3043'
  outline: '#859490'
  outline-variant: '#3c4947'
  surface-tint: '#4fdbc8'
  primary: '#4fdbc8'
  on-primary: '#003731'
  primary-container: '#14b8a6'
  on-primary-container: '#00423b'
  inverse-primary: '#006b5f'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  tertiary: '#ffb95f'
  on-tertiary: '#472a00'
  tertiary-container: '#e49200'
  on-tertiary-container: '#543300'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#71f8e4'
  primary-fixed-dim: '#4fdbc8'
  on-primary-fixed: '#00201c'
  on-primary-fixed-variant: '#005048'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#0c1324'
  on-background: '#dce1fb'
  surface-variant: '#2e3447'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  title-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
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
  label-code:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.12em
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
  space-xl: 2rem
---

## Brand & Style

The design system establishes a high-performance, dark-mode-first logistics orchestration platform tailored specifically for Indonesian overland freight and supply chain operations. The visual atmosphere balances industrial rigor with software precision, projecting reliability, speed, and real-time operational clarity across vast transit networks.

The design movement blends **Modern Dark SaaS** with **Tactile Precision Logistics**. Deep, noise-free slate backdrops reduce eye strain in 24/7 fleet control rooms and high-density mobile dispatch environments. Luminous teal accents serve as high-visibility operational status anchors, cutting through the dark hierarchy to guide critical handoffs, route verifications, and cargo status tracking. High-contrast typography and subtle structural outlines deliver an interface that feels utilitarian, authoritative, and frictionless.

## Colors

The palette is engineered for WCAG AAA/AA legibility in low-light environments, leveraging an oceanic-to-slate contrast spectrum:

- **Canvas & Base Surface (`#020617` / Slate 950):** The primary deep ground for all viewports, eliminating visual fatigue during prolonged dispatch monitoring.
- **Card Surface (`#0f172a` / Slate 900):** Elevated surfaces for waybills, shipment clusters, and fleet analytics widgets.
- **Structural Outlines (`#1e293b` / Slate 800):** Subtle borders providing crisp geometry without overpowering data density.
- **Primary Accent (`#14b8a6` / Teal 500):** High-energy signifier for interactive primary actions, route progress lines, and verified shipment milestones. Transitions to `#0d9488` (Teal 600) on active/hover states.
- **Interactive Inversion:** Primary CTA buttons render with solid `#14b8a6` fill and ultra-dark slate text (`#020617`) to guarantee immediate visual priority and contrast ratios exceeding 9:1.
- **Data & Text Contrast:** Text primary is locked to `#f1f5f9` (Slate 100), with secondary metadata, timestamps, and fleet subtexts styled in `#94a3b8` (Slate 400). Muted guidelines and micro-captions leverage `#64748b` (Slate 500).
- **Functional Semantics:** Accent blue (`#38bdf8`) signifies transit telematics and route updates; Amber (`#f59e0b`) highlights checkpoint delays and awaiting signatures; Emerald (`#10b981`) flags successful chain-of-custody delivery.

## Typography

The typography leverages **Plus Jakarta Sans** across all levels, infusing contemporary precision with warm legibility suited for rapid on-screen parsing.

- **Tabular & Code Integrity:** The dedicated `label-code` style is calibrated with expanded letter spacing (`0.12em`) and uppercase transformation for the 10-character verification confirmation codes (e.g., `TRK-8924-JKT`), ensuring zero ambiguity between characters like `0` vs `O` or `1` vs `I`.
- **Hierarchical Discipline:** Numbers, tonnages, and transit timestamps within overview tables default to `title-md` or `label-md` to preserve clean tabular alignment.
- **Editorial Legibility:** Body copy maintains loose leading (1.5x–1.6x) to facilitate scanning across multi-leg transit itineraries and consignment manifests.

## Layout & Spacing

The layout model uses a **fluid-responsive grid architecture** anchored by an 8px base rhythm:

- **Desktop (1200px+):** 12-column grid with 24px (`1.5rem`) gutters and 32px (`2rem`) margins. Content containers max out at 1440px for wide fleet control consoles.
- **Tablet (768px – 1199px):** 8-column layout with 20px gutters and 24px page margins.
- **Mobile (<768px):** 4-column layout with 16px (`1rem`) gutters and 16px margins, ensuring one-handed operation for warehouse staff and drivers.

Components adhere to strict vertical flow: metadata chips use `space-xs` to `space-sm` gaps, nested form blocks use `space-md`, and independent waybill sections separate with `space-lg` to `space-xl`.

## Elevation & Depth

Depth in this system avoids distracting, artificial drop shadows in favor of **structural illumination and layered tonal tiers**:

1. **Level 0 (Canvas Base):** Solid `#020617`. Anchors navigation headers, sidebars, and structural backgrounds.
2. **Level 1 (Cards & Data Surfaces):** Solid `#0f172a` wrapped in a 1px continuous border of `#1e293b`.
3. **Level 2 (Dropdowns, Overlays & Modals):** `#0f172a` with a refined ambient diffusion: `0px 12px 32px -4px rgba(2, 6, 23, 0.8)`, paired with a brightened hairline perimeter of `rgba(20, 184, 166, 0.2)` on active focus.
4. **Interactive Glows:** Focused input fields and high-priority transit nodes receive an ambient, diffuse teal bloom (`box-shadow: 0 0 0 1px #14b8a6, 0 0 16px -2px rgba(20, 184, 166, 0.25)`).

## Shapes

The geometric framework balances technical rigor with modern ergonomics:

- Standard interactive controls, form fields, and operational chips utilize `0.5rem` (8px) to `0.75rem` (12px) corners.
- Primary card enclosures, modal dialogues, and shipment status cards conform to `1rem` (16px) curvature (`rounded-lg` / `rounded-xl`).
- Micro-elements such as live GPS telemetry pings and verification indicator pills utilize full pill geometry (`9999px`).

## Components

### Buttons
- **Primary Action (CTA):** Solid teal `#14b8a6` background with dark slate text `#020617` (Font: `label-lg`, weight 600). Hover triggers `#0d9488`. Active state tightens slightly (`transform: scale(0.99)`). Border-radius: 12px.
- **Secondary Action:** Transparent fill with 1px border of `#1e293b`, primary text `#f1f5f9`. Hover fills to `#1e293b`.
- **Ghost Action:** `#0f172a` background with `#94a3b8` text for low-priority table filters and export tools.

### Input Fields
- Dark canvas fill (`#020617`) framed by 1px `#1e293b` border, 12px corner radius.
- Placeholder text in `#64748b`; entered text in `#f1f5f9`.
- Focused state transitions border to `#14b8a6` with ambient teal outer focus ring. Includes embedded leading icons (Lucide-style line icons, 18px stroke 1.75).

### Logistics Feature Badge: "Serah Terima Terverifikasi"
- Specialized chain-of-custody verification component.
- Visual container: Compact pill or 12px rounded block with deep teal tint (`rgba(20, 184, 166, 0.1)`) and border (`1px solid rgba(20, 184, 166, 0.3)`).
- Left accessory: Verified check shield icon in `#14b8a6`.
- Typography: Label reads *"Serah Terima Terverifikasi"* (`label-md`, `#f1f5f9`).
- Verification Code Display: Embedded sub-badge in `#020617` with high-contrast monospace/expanded font (`label-code`) rendering the 10-character confirmation string: `KODE: 4A89-91X-JK`.

### Shipment Cards
- Built on `#0f172a` with 16px corner radius and 1px `#1e293b` perimeter.
- Header showcases vehicle registration (e.g., `B 9841 TXZ`), current leg (e.g., `Jakarta → Surabaya`), and live state chip.
- Interior body embeds a vertical transit step-line with 2px teal route tracks and timestamp breadcrumbs.

### Chips & Status Indicators
- **In Transit (Dalam Perjalanan):** Background `rgba(56, 189, 248, 0.1)`, text `#38bdf8`, dot pulse indicator.
- **Checkpoint Delayed (Tertunda):** Background `rgba(245, 158, 11, 0.1)`, text `#f59e0b`.
- **Delivered (Terkirim):** Background `rgba(16, 185, 129, 0.1)`, text `#10b981`.

### Checkboxes & Radios
- 20px structural square/circle with `#020617` interior and 1.5px `#1e293b` frame.
- Checked state transitions to `#14b8a6` solid fill with `#020617` checkmark/indicator icon.