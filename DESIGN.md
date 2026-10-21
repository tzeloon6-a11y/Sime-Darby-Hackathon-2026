---
name: Circularity Living
colors:
  surface: '#ecffe6'
  surface-dim: '#cddfc7'
  surface-bright: '#ecffe6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#e7f9e0'
  surface-container: '#e1f3db'
  surface-container-high: '#dbedd5'
  surface-container-highest: '#d6e8d0'
  on-surface: '#111f10'
  on-surface-variant: '#414940'
  inverse-surface: '#253424'
  inverse-on-surface: '#e4f6dd'
  outline: '#72796f'
  outline-variant: '#c1c9bd'
  surface-tint: '#3a693e'
  primary: '#204f27'
  on-primary: '#ffffff'
  primary-container: '#38673d'
  on-primary-container: '#afe3af'
  inverse-primary: '#9fd3a0'
  secondary: '#376936'
  on-secondary: '#ffffff'
  secondary-container: '#b8f1b0'
  on-secondary-container: '#3d6f3c'
  tertiary: '#03511e'
  on-tertiary: '#ffffff'
  tertiary-container: '#256a34'
  on-tertiary-container: '#9fe8a4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bbf0ba'
  primary-fixed-dim: '#9fd3a0'
  on-primary-fixed: '#002107'
  on-primary-fixed-variant: '#215029'
  secondary-fixed: '#b8f1b0'
  secondary-fixed-dim: '#9dd496'
  on-secondary-fixed: '#002204'
  on-secondary-fixed-variant: '#1f5121'
  tertiary-fixed: '#abf4af'
  tertiary-fixed-dim: '#90d795'
  on-tertiary-fixed: '#002108'
  on-tertiary-fixed-variant: '#05521f'
  background: '#ecffe6'
  on-background: '#111f10'
  surface-variant: '#d6e8d0'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
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
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

### Personality & Emotional Response
The design system channels an ethos of grounded stewardship, institutional trust, and modern ecological progress. It pairs the architectural authority and heritage of a tier-one property developer with the active optimism of everyday environmental stewardship. The interface must feel clean, dependable, and dignified—never preachy, overly playful, or gritty. It reassures residents that their individual household contributions matter while giving administrative operators the clarity and speed expected of an enterprise utility system.

### Design Movement & Aesthetic Direction
A modern, warm corporate-sustainability aesthetic built on refined architectural structure. It merges crisp structural layouts with soft, organic surfaces:
- Generous alabaster backdrops counterpointed by deep forest green structural anchors.
- Clean white card modules floating subtly above warm organic canvases.
- Restrained amber accents that reference repurposed cooking oil and clean biofuel energy transitions without visually competing with ecological greens.
- Deliberate balance between civic utility and premium residential lifestyle.

## Colors

### Color Strategy
The palette balances environmental resonance with high operational legibility:
- **Primary (`#38673D`)**: Used for core structural boundaries, high-priority actions, key navigation items, and authoritative headings. It brings institutional weight and stability.
- **Secondary (`#4F824C`)**: Acts as the active catalyst—used for milestone celebrations, positive delta indicators, progress rings, and environmental metrics.
- **Tertiary (`#67AC6E`)**: Applied strictly to signify lifecycle oil volumes, feedstock weigh-ins, pending transaction flags, and renewable energy conversion indicators.
- **Neutral (`#D1E3CB`)**: Delivers contrast against light surfaces without the stark harshness of pure black.

### Surface System
- `surface-canvas`: `#F4F6F4` (Warm alabaster tint that grounds cards and reduces glare).
- `surface-card`: `#FFFFFF` (Pure crisp white to elevate primary touchpoints).
- `surface-subtle`: `#EDF1EE` (Secondary containers, table zebra stripes, and segmented controls).
- `surface-elevated`: `#FFFFFF` with warm olive/slate ambient drop.

## Typography

### Architectural Hierarchy
- **Headlines (Plus Jakarta Sans)**: Carries balanced warmth through softened geometric curves, reflecting approachable hospitality without sacrificing structural authority. Headlines must prioritize tight line height to retain solid visual block formation.
- **Body & Labels (Inter)**: Built for metric rendering, high-density collection rosters, dashboard telemetry, and status indicators. Provides neutral, undistorted clarity across variable lighting conditions on residential handhelds and tablet devices.
- **Numerics & Measurements**: For volume units (e.g., `Liters`, `kg CO2e`, `RM credits`), set numeric values in `Plus Jakarta Sans` semi-bold while retaining adjoining metric abbreviations in `Inter` medium to ensure distinct tabular cadence.

## Layout & Spacing

### Layout Model
The layout adopts a unified 12-column grid system for desktop and administration monitors, transitioning into an 8-column layout on tablet consoles, and a flexible 4-column flow on field-officer mobile viewports. 

### Breakpoint Structure
- **Mobile (`< 768px`)**: Single column stack for collection workflows, `margin-mobile` (20px), cards fill edge-to-edge minus exterior margin.
- **Tablet (`768px - 1024px`)**: Dual-card metric splits, sticky bottom action bars for logistics updates, `margin` (32px), `gutter` (20px).
- **Desktop (`> 1024px`)**: Asymmetric dashboard layout featuring persistent structural sidebars, 2-to-3 column analytical card groupings, and a maximum content constraint of `1440px`.

### Spacing Cadence
Component internals scale strictly off an 8pt modular interval:
- Sub-element spacing (icon-to-label, badge margins): `space-xs` (4px) to `space-sm` (8px).
- Field inputs, inner card content blocks: `space-md` (16px).
- Major container boundaries, table row headers: `space-lg` (24px).
- Section divides, dashboard widget gutters: `space-xl` (40px).

## Elevation & Depth

### Depth Paradigm
Depth is defined by physical layering on top of the organic `#F4F6F4` alabaster plane. Instead of harsh grey drop shadows, the system deploys ambient environmental shadows infused with a minute degree of forest green/slate undertone (`rgba(56, 103, 61, 0.04)` to `rgba(209, 227, 203, 0.08)`).

### Elevation Hierarchy
- **Level 0 (Flat)**: Sub-panels, inactive tabs, segmented input bases. Rendered cleanly using tone shifts against the canvas (`#EDF1EE`) with no drop shadow.
- **Level 1 (Card Baseline)**: Primary collection cards, metric summaries, and data tables. Pure `#FFFFFF` surfaces surrounded by a subtle 1px border (`rgba(56, 103, 61, 0.08)`) and a warm ambient blur: `0 4px 20px -2px rgba(56, 103, 61, 0.05)`.
- **Level 2 (Hover & Active Focus)**: Triggered card interactions and dropdown menus. Elevated via `0 12px 28px -4px rgba(56, 103, 61, 0.09)`.
- **Level 3 (Overlays & Operational Modals)**: Weigh-in verification dialogs, QR dispatch panels, and side drawers. Elevated via `0 24px 48px -8px rgba(209, 227, 203, 0.16)`.

## Shapes

### Form Geometry
The shape system uses a balanced rounded geometry to create a modern residential feel:
- **Standard Surfaces (`rounded-lg` / 16px)**: Applied across metric cards, form containers, data modules, and summary panels to soften architectural rigidity while preserving layout structure.
- **Interactive Controls (8px to 12px)**: Input fields, collection status selects, and data filters use an 8px radius to keep inputs structurally stable and compact.
- **Pills & Badges (`rounded-full`)**: Assigned exclusively to circularity status badges, categorical tags, profile counters, and micro-metric chips.

## Components

### Buttons
- **Primary**: Solid Forest Green (`#38673D`) background, crisp white text (`#FFFFFF`), subtle hover transition brightening to `#457A4B`. 8px corner radius. Padding: `12px 24px` for medium buttons.
- **Secondary / Ghost**: Alabaster border (`1px solid #38673D`), Forest Green text, hovering shifts background to `rgba(56, 103, 61, 0.06)`.
- **Accent (Energy / Trade)**: Golden-Amber (`#67AC6E`) background, white text, reserved for direct trade-in, credit disbursement, or urgent operational dispatches.

### Input Fields & Controls
- **Text & Number Inputs**: White fill, 1px border in `#D1D5DB`, 8px corner radius. Focus states shift border directly to `#457A4B` with a soft outer ring: `0 0 0 3px rgba(79, 130, 76, 0.15)`.
- **Checkboxes & Radios**: 20px base target, unchecked border `#9CA3AF`, checked state switches to solid `#38673D` with white checkmark glyphs. Smooth scaling transition.

### Status Badges & Chips
- **Completed / Recycled**: Soft green background (`rgba(79, 130, 76, 0.15)`), Fresh Leaf text (`#457A4B`).
- **Oil Intake / In Progress**: Amber tint (`rgba(103, 172, 110, 0.12)`), Golden-Amber text (`#3F7845`).
- **Administrative / Scheduled**: Slate tint (`rgba(209, 227, 203, 0.08)`), Charcoal text (`#374151`).
- All badges are rendered with `rounded-full`, paired with a 6px status dot positioned directly adjacent to text.

### Metric & Circularity Cards
- Structured on `#FFFFFF` with a 16px corner radius (`rounded-lg`), bounded by a subtle border (`rgba(56, 103, 61, 0.08)`).
- Card layouts display the metric icon top-left (encased in a soft circular tint), the large numeric metric centered or stacked, followed by clean baseline progress indicators or historical delta markers (`+12.4% this month`).

### Data Tables & Roster Lists
- Alternating rows utilizing `#FFFFFF` and `#F8F9FA`. Dividers use low-contrast borders (`#E5E7EB`).
- Header cells styled with `label-md` typography in charcoal slate (`#4B5563`), uppercase with slight letter spacing.
- Real-time timestamp columns and liter weights right-aligned with fixed-width numerals.