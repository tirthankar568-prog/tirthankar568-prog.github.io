---
name: Joyful Academy
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3dae9'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff3ff'
  surface-container: '#e7eefd'
  surface-container-high: '#e2e8f8'
  surface-container-highest: '#dce3f2'
  on-surface: '#151c27'
  on-surface-variant: '#424753'
  inverse-surface: '#2a313c'
  inverse-on-surface: '#ebf1ff'
  outline: '#727785'
  outline-variant: '#c2c6d5'
  surface-tint: '#005ac3'
  primary: '#0058be'
  on-primary: '#ffffff'
  primary-container: '#2b71de'
  on-primary-container: '#fefcff'
  inverse-primary: '#aec6ff'
  secondary: '#b81c34'
  on-secondary: '#ffffff'
  secondary-container: '#fe5361'
  on-secondary-container: '#5b0011'
  tertiary: '#7b5400'
  on-tertiary: '#ffffff'
  tertiary-container: '#9b6b00'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#aec6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#ffdad9'
  secondary-fixed-dim: '#ffb3b3'
  on-secondary-fixed: '#400009'
  on-secondary-fixed-variant: '#920021'
  tertiary-fixed: '#ffdead'
  tertiary-fixed-dim: '#ffba3b'
  on-tertiary-fixed: '#281900'
  on-tertiary-fixed-variant: '#604100'
  background: '#f9f9ff'
  on-background: '#151c27'
  surface-variant: '#dce3f2'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.25rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system serves early childhood educators, daycare administrators, and preschool caretakers. It strikes an intentional balance: visually radiant, warm, and playful enough to evoke the wonder of early childhood education, yet clean, highly structured, and reliable to handle daily operations, attendance check-ins, medical notes, and milestone checklists.

The design style blends **Tactile Soft UI** with **Modern Clean Functionalism**. Elements celebrate soft pillowy volumes, rounded container geometry (16px to 24px), friendly multi-colored category coding directly inspired by the Gurukul block logo, and tactile interactive affordances. Touch interactions should feel reassuring, crisp, and effortless for teachers on the move holding a tablet or mobile device.

## Colors

The palette directly honors the primary block colors from the brandmark, anchored onto warm neutral surfaces:

- **Primary (`#3578E5`)**: A bright, dependable sky cobalt used for primary buttons, active navigation, student records, and scanner target indicators.
- **Secondary (`#F44B5A`)**: A warm, cheerful strawberry coral used for urgent alerts, check-out statuses, attendance highlights, and primary promotional banners.
- **Tertiary (`#FDB528`)**: A sunny marigold/amber tone utilized for afternoon logs, pending tasks, snack/nap schedules, and achievement badges.
- **Support Mint Green (`#38C172`)**: Check-in verified, healthy health status, and affirmative milestone completion.
- **Support Royal Purple (`#8C38F7`)**: Creative activities, art curriculum, and administrative master logs.
- **Neutral Base (`#1E2530`)**: Deep ink slate ensuring high-contrast, WCAG AAA readability on warm neutral backdrops (`#F9F9FB` canvas and `#FFFFFF` cards).

## Typography

**Plus Jakarta Sans** is employed across all typographic roles. Its geometric roundness, wide apertures, and balanced x-height convey youthful friendliness without sacrificing administrative precision. 

- Large titles adopt bolder weights (`700` and `800`) to evoke the iconic rounded letterforms of educational toy blocks.
- Body and label copy are optimized for glanceability during high-paced classroom transitions, with deliberate line heights avoiding accidental misreads of allergy warnings or guardian pickup authorizations.

## Layout & Spacing

A flexible 4-column layout model is used for standard mobile viewports, expanding to 8 columns on tablet devices.

- **Mobile Viewports (<600px)**: 16px screen margins ensure edge-to-edge breathing room while maximizing card surface area. Components strictly abide by a 48px minimum touch target.
- **Tablet / Split View (600px–1024px)**: 24px margins with dual-pane master-detail views (e.g., class roster on the left, daily check-in checklist on the right).
- Spacing is rhythmic and built on an 8pt base grid, with micro 4px increments for tightly-associated items like avatar tags and status pills.

## Elevation & Depth

Visual hierarchy relies on **tactile tonal layering** and **warm ambient drop shadows** rather than harsh outlines:

- **Surface Layer 0 (Canvas)**: Warm off-white (`#F8F9FD`).
- **Surface Layer 1 (Cards, Modules)**: Pure white (`#FFFFFF`) backed by a diffused, warm multi-layered shadow: `0 4px 16px -2px rgba(30, 37, 48, 0.06), 0 2px 4px -1px rgba(30, 37, 48, 0.03)`.
- **Surface Layer 2 (Floating Action Bars, Modal Sheets)**: `0 12px 32px -4px rgba(30, 37, 48, 0.12)`.
- **Interactive State Depth**: Primary action buttons feature a subtle 2px bottom lip shadow (e.g., darker shade tint) that simulates a physical, squishy pushbutton when tapped.

## Shapes

The design system embraces generous, friendly curvature directly echoing the toy-block silhouette:
- Standard interactive elements (input fields, checklist tiles, quick-filter chips) utilize `rounded-md` (8px) to `rounded-lg` (16px).
- Prominent educational cards, scanner viewports, and modal sheets embrace extra roundedness (`rounded-xl` at 20px–24px).
- Avatars, badge counters, and active status indicators are fully rounded pills or circles (`9999px`).

## Components

### Buttons
- **Primary CTA**: Filled cobalt blue (`#3578E5`) with bold white text, 52px height, 16px border-radius, accompanied by a subtle physical depth shadow. Active state compresses by 1px downward.
- **Secondary Action**: Warm tinted surface (e.g., `#EBF2FD` background with `#3578E5` typography) for low-friction actions like "Log Snack" or "Add Note".
- **Destructive/Emergency**: Strawberry coral (`#F44B5A`) for critical allergy alerts or sign-out confirmations.

### Chips & Tags
- Used for room assignment ("Toddlers A", "Pre-K"), allergy warnings, and filter bars.
- Rendered with light pastel fills paired with high-contrast saturated text (e.g., soft mint background `#E8F8F0` with `#238249` label).

### Scanner Check-in Module
- A dedicated QR / Barcode card framing an active camera viewport with 20px rounded edges, framed with animated cobalt alignment corners.
- Instant feedback status banner: Fresh Green bar for "Checked In", Coral Red for "Guardian Verification Required".

### Student Checklist Items
- 64px minimum row height containing a round 40px avatar on the left, child's full name, attendance state pill, and a tactile checkbox/toggle on the right.
- Tapping triggers a warm micro-bounce animation with haptic feedback.

### Form Inputs
- 48px height with 12px rounded borders, subtle warm grey border (`#E2E8F0`), and filled background (`#FFFFFF`). Focus state transitions smoothly to a 2px cobalt ring with a soft ambient glow.