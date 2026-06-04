---
name: Luminous Professionalism
colors:
  surface: '#faf8ff'
  surface-dim: '#d9d9e5'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3fe'
  surface-container: '#ededf9'
  surface-container-high: '#e7e7f3'
  surface-container-highest: '#e1e2ed'
  on-surface: '#191b23'
  on-surface-variant: '#434655'
  inverse-surface: '#2e3039'
  inverse-on-surface: '#f0f0fb'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#943700'
  on-tertiary: '#ffffff'
  tertiary-container: '#bc4800'
  on-tertiary-container: '#ffede6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7d2d00'
  background: '#faf8ff'
  on-background: '#191b23'
  surface-variant: '#e1e2ed'
typography:
  display-lg:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Outfit
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
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
    letterSpacing: 0.01em
  code:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  2xl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style
The design system is built for a B2B SaaS environment where clarity and trust are paramount. The brand personality is **Professional, Reliable, and Efficient**, manifesting in a "Luminous" visual style. This style prioritizes extreme legibility and a sense of "airiness" through generous whitespace and subtle translucent layers.

The aesthetic leans into **Modern Corporate Minimalism** with a focus on high-quality typography and a refined color application. The goal is to reduce cognitive load for users managing complex certification data, making the interface feel responsive and intelligent rather than cluttered or overwhelming.

## Colors
The palette is anchored by **Electric Blue**, a high-energy primary color that signals action and modern technology. 

- **Primary (#2563EB):** Used for primary actions, active states, and brand highlights.
- **Neutrals:** A sophisticated range of Slate grays provides hierarchy. Backgrounds utilize the neutral base for a clean, off-white canvas that reduces eye strain.
- **Semantic Palette:**
    - **Emerald Green:** For "Active" or "Verified" statuses.
    - **Amber Orange:** For "Expiring Soon" or "Pending" warnings.
    - **Rose Red:** For "Expired" or "Critical Action Required" states.
    
Semantic colors should be used in two weights: a saturated version for text/icons and a low-opacity (10-15%) version for background "soft badges."

## Typography
This design system employs a dual-font strategy to balance character with utility. 

**Outfit** is used for headings to provide a modern, slightly geometric "tech" feel that aligns with the luminous brand personality. **Inter** is used for all functional UI elements, body text, and data tables to ensure maximum readability at small sizes.

Large displays and headlines use tighter letter spacing to maintain a cohesive visual block, while labels use slightly increased tracking to assist in quick scanning.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a 12-column structure for desktop. 

- **Desktop (1440px+):** 12 columns, 24px gutters, 32px side margins.
- **Tablet (768px - 1439px):** 8 columns, 16px gutters, 24px side margins.
- **Mobile (Up to 767px):** 4 columns, 16px gutters, 16px side margins.

Vertical rhythm is strictly maintained using a **4px base unit**. Component padding typically follows a 16px (md) or 24px (lg) increment to ensure a spacious, "luminous" feel.

## Elevation & Depth
Depth is created using **Ambient Shadows** and **Tonal Layers** rather than heavy borders.

- **Level 0 (Background):** Neutral base (#F8FAFC).
- **Level 1 (Cards/Surface):** Pure White (#FFFFFF) with a 1px border in a very light neutral (#E2E8F0).
- **Level 2 (Dropdowns/Modals):** Pure White with a soft, diffused shadow: `0 10px 15px -3px rgba(0, 0, 0, 0.05), 0 4px 6px -2px rgba(0, 0, 0, 0.02)`.

To achieve the "luminous" effect, use subtle blue-tinted shadows for primary elements and avoid pure black in any shadow calculations.

## Shapes
The shape language is friendly yet professional, utilizing **Rounded** corners to soften the industrial nature of B2B data.

- **Default (Inputs, Small Buttons):** 8px (0.5rem).
- **Large (Cards, Modals):** 16px (1rem).
- **Extra Large (Hero Sections, Containers):** 24px (1.5rem).

Interactive elements like Checkboxes use a 4px radius, while Status Badges use a full "pill" radius (999px) for a distinct visual separation from actionable buttons.

## Components

### Buttons
- **Primary:** Solid Electric Blue with white text. 12px vertical / 24px horizontal padding.
- **Secondary:** Ghost style with an Electric Blue border and text.
- **Tertiary:** Text-only with a subtle background hover state.

### Status Badges
Badges use the semantic palette. They feature a low-opacity background (e.g., 10% Emerald Green) with high-contrast text (100% Emerald Green). This "soft badge" style ensures they are visible without competing with primary action buttons.

### Cards
Cards are the primary container for certification data. They feature a white background, 16px corner radius, and a 1px soft border. Internal padding should be a minimum of 24px to maintain the luminous whitespace.

### Tables
Modern tables remove vertical dividers. Use horizontal dividers only in a light Slate (#F1F5F9). The header row uses a light gray background with uppercase `label-md` typography for clarity.

### Input Fields
Inputs use a 1px border (#CBD5E1) that transitions to Electric Blue on focus, accompanied by a subtle blue outer glow (3px spread, 15% opacity). Labels sit clearly above the field in `label-md`.