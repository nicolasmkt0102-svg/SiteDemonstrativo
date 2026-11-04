---
name: Smile Odontologia Care System
colors:
  surface: '#f5faff'
  surface-dim: '#d2dbe2'
  surface-bright: '#f5faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#ecf5fc'
  surface-container: '#e6eff6'
  surface-container-high: '#e0e9f0'
  surface-container-highest: '#dbe4eb'
  on-surface: '#141d22'
  on-surface-variant: '#41474f'
  inverse-surface: '#293237'
  inverse-on-surface: '#e9f2f9'
  outline: '#717880'
  outline-variant: '#c1c7d0'
  surface-tint: '#1c6395'
  primary: '#005282'
  on-primary: '#ffffff'
  primary-container: '#286b9e'
  on-primary-container: '#d4e8ff'
  inverse-primary: '#97cbff'
  secondary: '#406181'
  on-secondary: '#ffffff'
  secondary-container: '#b6d8fd'
  on-secondary-container: '#3d5e7e'
  tertiary: '#195376'
  on-tertiary: '#ffffff'
  tertiary-container: '#376b90'
  on-tertiary-container: '#d0e8ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cee5ff'
  primary-fixed-dim: '#97cbff'
  on-primary-fixed: '#001d33'
  on-primary-fixed-variant: '#004a76'
  secondary-fixed: '#cfe5ff'
  secondary-fixed-dim: '#a8caee'
  on-secondary-fixed: '#001d33'
  on-secondary-fixed-variant: '#274968'
  tertiary-fixed: '#cbe6ff'
  tertiary-fixed-dim: '#9accf6'
  on-tertiary-fixed: '#001e30'
  on-tertiary-fixed-variant: '#0c4b6e'
  background: '#f5faff'
  on-background: '#141d22'
  surface-variant: '#dbe4eb'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
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
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
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
  label-sm:
    fontFamily: Plus Jakarta Sans
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
  space-2xl: 4rem
---

## Brand & Style

This design system establishes a clinical yet deeply welcoming atmosphere, balancing state-of-the-art dental technology with empathetic patient care. Designed for the clinical practice of Dr. Kenny, the interface bridges professional medical rigor with warm, approachable hospitality.

The design movement combines **Contemporary Health Minimalism** with subtle **Tactile Precision**:
- Surfaces remain pristine, clear, and breathable, invoking sterility, hygiene, and calm.
- Micro-interactions prioritize reassurance and clarity to minimize medical anxiety and friction in scheduling appointments.
- Visual elements eliminate aggressive harshness through tempered rounded corners, luminous blue-hued depths, and legible editorial typographic hierarchy.

## Colors

The palette is engineered around light and calming clinical tones:

- **Primary (`#286B9E`)**: Used for pivotal calls-to-action (e.g., booking consults, WhatsApp direct triggers), active navigational states, and high-priority feedback.
- **Secondary (`#173B59`)**: Grounded deep navy applied to prominent headlines, high-contrast typography, and structured navigational containers to convey stability, trust, and clinical authority.
- **Tertiary (`#77A9D1`)**: Soft oceanic accent for borders, supportive tags, secondary iconography, progress indicators, and hover feedback.
- **Neutral Surface / Ice Blue (`#EAF3FA`)**: Subtle background tinting used to layer sub-sections, specialty procedure cards, and soft informational banners away from the pure white canvas without visual weight.
- **Background Pure (`#FFFFFF`)**: Foundation color, maximizing clean white-space and optical brightness.

## Typography

The design system utilizes **Plus Jakarta Sans** across all roles to achieve a warm geometric presence that remains contemporary and clinical. The rounded apertures and clean terminal shapes soften medical messaging, while tight tracking on larger scales injects authority and professionalism.

- Display headers use semibold and bold weights paired with negative tracking for an editorial clinic presence.
- Body copy relies on strict standard line-heights (1.5x) to maintain legibility for patients of all ages reviewing clinical treatments or instructions.
- Micro-labels and tags use uppercase or semi-bold variants with subtle positive tracking to distinguish administrative metadata from clinical prose.

## Layout & Spacing

A 12-column responsive fluid grid governs desktop displays (max-width `1280px`), adapting to 8 columns on tablet viewports and 4 columns on mobile devices:

- **Desktop (1024px+)**: `3rem` margins and `1.5rem` gutters. Wide content breathing room to reflect high-end clinic environments.
- **Tablet (768px - 1023px)**: `2rem` margins, collapsing multi-card grids into 2-column modules.
- **Mobile (320px - 767px)**: `1.25rem` margins and `1rem` gutters. Elements stack vertically, preserving rapid touch access to emergency or appointment booking actions.
- Layout flow incorporates generous vertical spacing (`space-2xl`) between thematic blocks (treatments, credentials, testimonials, clinic facilities) to avoid visual density.

## Elevation & Depth

Depth is established via diffused ambient illumination rather than harsh shadows, simulating daylight filtering through clean dental treatment suites:

- **Level 0 (Flat)**: Pure `#FFFFFF` and tint `#EAF3FA` surfaces used for static page sections and nested content dividers.
- **Level 1 (Subtle Lift)**: Used for service cards and patient guidance tiles. Supported by a 1px border of `#77A9D1` at 20% opacity and an ambient drop shadow: `0px 4px 20px rgba(23, 59, 89, 0.04)`.
- **Level 2 (Interactive Floating)**: Hovered cards, navigation headers, and floating appointment triggers. Utilizes `0px 10px 30px rgba(23, 59, 89, 0.08)`.
- **Level 3 (Modal / Dialog)**: Booking overlays, doctor profile views, and diagnostic details. Uses `0px 20px 48px rgba(23, 59, 89, 0.14)` combined with backdrop blur `backdrop-filter: blur(8px)`.

## Shapes

The roundedness level is configured to **Rounded (2)**. 

- Interactive elements (buttons, inputs, dropdown selectors) employ `0.5rem` (8px) radius to maintain an approachable, friendly touchpoint.
- Content containers, treatment cards, and modal sheets scale to `1rem` (16px) or `1.5rem` (24px) for organic framing.
- Category tags, status pills, and doctor qualification badges adopt full capsule/pill styling (`9999px`) to emphasize humanized warmth.

## Components

### Buttons
- **Primary Action (Agendar Consulta / WhatsApp)**: Filled `#286B9E` with pure `#FFFFFF` text. Height of 48px, horizontal padding `space-lg`, border-radius `0.5rem`. On hover: `#173B59` background transition with subtle elevation.
- **Secondary Action**: Bordered button with 1.5px stroke of `#77A9D1`, transparent background, and `#173B59` typography. Hover applies `#EAF3FA` background fill.
- **Ghost/Tertiary Action**: Text-only button in `#286B9E` with underline or rightward arrow transition on hover.

### Cards
- **Procedure & Service Cards**: Background `#FFFFFF`, border `1px solid rgba(119, 169, 209, 0.25)`, padding `space-lg`, border-radius `1rem`. Houses high-contrast icons styled in `#286B9E` sitting inside an `#EAF3FA` rounded badge.
- **Testimonial & Social Proof Cards**: Background `#EAF3FA`, borderless, padding `space-lg`, border-radius `1rem`.

### Input Fields & Selectors
- Standard height of 48px with base background `#FFFFFF`, border `1.5px solid rgba(119, 169, 209, 0.4)`, font size `16px`.
- Active/Focus state uses `#286B9E` border with a 3px soft outer ring of `rgba(40, 107, 158, 0.15)`.

### Chips & Badges
- Pill-shaped tags for specializations (e.g., "Implantodontia", "Ortodontia Invisível", "Clareamento a Laser").
- Tinted background in `#EAF3FA`, text in `#173B59`, bordered with a fine `1px solid rgba(119, 169, 209, 0.3)`.

### Checkboxes & Radios
- Size 20x20px with `0.25rem` radius (checkboxes) or full circle (radios).
- Inactive stroke `#77A9D1`; active fill `#286B9E` featuring a crisp `#FFFFFF` checkmark or interior dot.

### Specialized Clinic Components
- **Dentist Credential Bar**: Clean horizontal band combining Dr. Kenny's CRO registry, specialty badges, and academic credentials in subdued `#173B59` with `#77A9D1` dividers.
- **Before & After Visualizer**: Border-radius `1rem`, dual-state image frame with interactive drag slider tinted in `#286B9E`.
- **Direct Care Floating Bar**: Persistent bottom mobile anchor providing direct one-tap access to WhatsApp triage and clinic phone lines.