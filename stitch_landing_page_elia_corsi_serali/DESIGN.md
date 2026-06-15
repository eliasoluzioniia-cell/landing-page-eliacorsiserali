---
name: Institutional Excellence
colors:
  surface: '#faf9fd'
  surface-dim: '#dbd9dd'
  surface-bright: '#faf9fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f7'
  surface-container: '#efedf1'
  surface-container-high: '#e9e7eb'
  surface-container-highest: '#e3e2e6'
  on-surface: '#1a1b1e'
  on-surface-variant: '#414754'
  inverse-surface: '#2f3033'
  inverse-on-surface: '#f1f0f4'
  outline: '#727785'
  outline-variant: '#c1c6d6'
  surface-tint: '#005bc0'
  primary: '#005bbf'
  on-primary: '#ffffff'
  primary-container: '#1a73e8'
  on-primary-container: '#ffffff'
  inverse-primary: '#adc7ff'
  secondary: '#5c5f60'
  on-secondary: '#ffffff'
  secondary-container: '#dee0e1'
  on-secondary-container: '#606364'
  tertiary: '#9e4300'
  on-tertiary: '#ffffff'
  tertiary-container: '#c55500'
  on-tertiary-container: '#0e0200'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc7ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#e1e3e4'
  secondary-fixed-dim: '#c4c7c8'
  on-secondary-fixed: '#191c1d'
  on-secondary-fixed-variant: '#444748'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb691'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#783100'
  background: '#faf9fd'
  on-background: '#1a1b1e'
  surface-variant: '#e3e2e6'
  surface-alt: '#E9E9E9'
  white: '#FFFFFF'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 48px
  margin-mobile: 16px
---

## Brand & Style

The design system is engineered for "Elia Corsi Serali," an educational management platform that prioritizes clarity, reliability, and institutional trust. The target audience includes adult learners and administrators who require a tool that feels authoritative yet accessible during evening hours.

The chosen style is **Corporate / Modern**, characterized by a focus on functional efficiency and a native, system-integrated feel. It utilizes high-contrast typography and a structured grid to manage complex information without overwhelming the user. The aesthetic is "Invisible UI"—where the interface recedes to allow the educational content and administrative tasks to take center stage.

## Colors

The palette is anchored by **Institutional Blue** (`#1A73E8`), used strategically for primary actions, progress indicators, and interactive highlights to drive user focus. 

The background strategy utilizes a tiered white-to-gray system to establish hierarchy:
- **Base Surface:** Pure `#FFFFFF` for main content areas to maximize legibility.
- **App Background:** `#F1F3F4` to provide a soft contrast against white cards.
- **Structural Elements:** `#E9E9E9` for borders and secondary dividers.
- **Typography:** `#202124` (Near-Black) is used for all primary text to ensure WCAG AAA compliance and reduce eye strain.

## Typography

This design system utilizes **Inter** across all levels to achieve a "system-native" feel that is highly legible and technically precise. 

- **Headlines:** Use tighter letter spacing and heavier weights to create a strong visual anchor.
- **Body Text:** Uses standard weights with generous line heights (`1.5x`) to maintain readability during long reading sessions.
- **Labels:** Small caps or increased letter spacing should be used for metadata and category tags to differentiate them from body copy.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop and a **Fluid Grid** on mobile.

- **Grid:** A 12-column grid is used for desktop (1200px max-width), transitioning to a 4-column grid for mobile devices.
- **Rhythm:** All spacing is derived from an 8px base unit. 
- **Whitespace:** Generous padding (minimum 24px) is required between logical sections to prevent cognitive load. 
- **Alignment:** Content should be left-aligned to mimic traditional document structures, facilitating faster scanning.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Soft Shadows**. 

- **Surface Tiers:** Backgrounds are `#F1F3F4`, while active content "floats" on `#FFFFFF` cards.
- **Shadows:** Use a single, professional shadow style for elevated elements like cards or dropdowns. 
  - *Shadow Specification:* `0px 4px 12px rgba(0, 0, 0, 0.05)`. 
- **Borders:** Low-contrast outlines (`1px solid #E9E9E9`) are used for nested elements or input fields where elevation is not required.

## Shapes

The design system employs a **Rounded** shape language to soften the institutional feel and make the platform more approachable.

- **Standard Elements:** Buttons, input fields, and small components use a 0.5rem (8px) radius.
- **Containers:** Large cards and modals use a 1rem (16px) radius to clearly define content boundaries.
- **Interactive States:** Hover states should maintain the same corner radius while slightly intensifying the shadow or background tint.

## Components

- **Buttons:** Primary buttons use the Institutional Blue background with white text. Secondary buttons use a light gray (`#F1F3F4`) background or a simple outline.
- **Cards:** Cards are the primary container. They must have a white background, the standard soft shadow, and 16px rounded corners.
- **Input Fields:** Use a 1px border (`#E9E9E9`) and 8px rounded corners. On focus, the border color transitions to Institutional Blue with a subtle 2px glow.
- **Chips/Badges:** Used for status indicators (e.g., "Enrolled", "Pending"). Use high-clearance padding (8px horizontal) and 100px (pill) radius.
- **Lists:** Clean rows with 1px bottom dividers. Avoid zebra-striping; use hover highlights in `#F1F3F4` instead.
- **Progress Bars:** Thin, 4px height bars using Institutional Blue to show course completion or form progress.