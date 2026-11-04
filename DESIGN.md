---
name: Sofisticação Acolhedora
colors:
  surface: '#fff8f5'
  surface-dim: '#e3d8d2'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fdf1eb'
  surface-container: '#f7ece5'
  surface-container-high: '#f1e6e0'
  surface-container-highest: '#ebe0da'
  on-surface: '#201b17'
  on-surface-variant: '#52443e'
  inverse-surface: '#352f2b'
  inverse-on-surface: '#faefe8'
  outline: '#84746d'
  outline-variant: '#d7c2bb'
  surface-tint: '#865139'
  primary: '#834f37'
  on-primary: '#ffffff'
  primary-container: '#9f674d'
  on-primary-container: '#fffbff'
  inverse-primary: '#fcb799'
  secondary: '#4f6357'
  on-secondary: '#ffffff'
  secondary-container: '#cfe5d6'
  on-secondary-container: '#53675b'
  tertiary: '#685a4a'
  on-tertiary: '#ffffff'
  tertiary-container: '#817261'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcd'
  primary-fixed-dim: '#fcb799'
  on-primary-fixed: '#341001'
  on-primary-fixed-variant: '#6a3a24'
  secondary-fixed: '#d2e8d9'
  secondary-fixed-dim: '#b6ccbd'
  on-secondary-fixed: '#0c1f16'
  on-secondary-fixed-variant: '#384b40'
  tertiary-fixed: '#f3dfcb'
  tertiary-fixed-dim: '#d6c3b0'
  on-tertiary-fixed: '#241a0d'
  on-tertiary-fixed-variant: '#514536'
  background: '#fff8f5'
  on-background: '#201b17'
  surface-variant: '#ebe0da'
typography:
  display-xl:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-desktop: 5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system expresses *Sofisticação Acolhedora*—an editorial healthcare narrative designed for an elevated dental practice. The visual approach deliberately strips away sterile clinical tropes (pure blues, harsh whites, cold aluminum surfaces) in favor of tactile serenity, architectural warmth, and human-centric precision. 

The aesthetic fuses **Warm Editorial Minimalism** with **Organic Tactility**. It balances high-end boutique hospitality with medical rigor: generous negative space, deliberate typographic tension between an expressive serif and a contemporary sans-serif, layered earth-toned card surfaces, and subtle, luminous borders. 

The emotional response must convey quiet confidence, unhurried care, and deep restorative tranquility. Patients should perceive the experience not as an intimidating medical procedure, but as an intimate, bespoke wellness consultation.

## Colors

The palette draws its grounding warmth from natural minerals and biophilic accents:

- **Marfim / Ivory Canvas (`#F6F0E8`):** The primary environment tone. A soft, luminous non-clinical canvas replacing stark `#FFFFFF` to mitigate screen glare and medical anxiety.
- **Terracota / Terracotta (`#A96F55`):** The primary focal anchor. Used exclusively for high-intent interactive elements, direct conversion actions (booking, priority contact), and refined emphasis.
- **Verde Sálvia / Sage Green (`#52665A`):** The secondary clinical reassurance color. Applied to clinical specializations, health verification indicators, delicate accents, and organic badges.
- **Areia / Sand (`#DCC9B5`):** The tertiary architectural structural tone. Utilized for subtle tonal surface containers, structural dividers, and translucent borders (`rgba(220, 201, 181, 0.4)`).
- **Grafite Quente / Warm Graphite (`#39332F`):** The neutral text foundation. Replaces harsh blacks to deliver editorial contrast with softened transitions.

### Functional Roles & Contrast
- `surface-default`: `#F6F0E8` (dominant background)
- `surface-subtle`: `#EFE7DC` (elevated surface tier)
- `surface-card`: `#FFFFFF` with 70% opacity over ivory or solid `#FBF8F4`
- `text-primary`: `#39332F` (contrast ratio exceeds 9:1 against ivory)
- `text-muted`: `rgba(57, 51, 47, 0.70)`
- `interactive-primary`: `#A96F55` with interactive hover state `#925E47`
- `accent-organic`: `#52665A` with light pill container `rgba(82, 102, 90, 0.12)`

## Typography

The typography leverages an editorial pairing strategy:

- **Playfair Display** establishes bespoke medical artistry, authority, and classical elegance. It is applied to primary display banners, doctor signatures, and section headings. It should maintain natural typographic casing (sentence case) to avoid visual harshness; all-caps serif is strictly avoided.
- **Plus Jakarta Sans** provides a warm, modern grotesque counterpart. Its open counters and geometric humanism ensure clear legibility for clinical schedules, procedure breakdowns, pricing structures, and long-form consultation context.

Use `label-sm` with uppercase transformation and `0.08em` tracking exclusively for medical badge categories, sub-headers, and step indicators.

## Layout & Spacing

The layout philosophy follows an **asymmetric, spacious rhythm** reminiscent of luxury editorial print. Layouts must avoid dense, stacked utility dashboards.

### Responsive Breakpoints & Grid
- **Mobile (< 768px):** 4-column fluid layout with `1.25rem` canvas margins and `1rem` column gutters. Components stack linearly into single-column cards with generous vertical breathing space (`2.5rem` between sections).
- **Tablet (768px - 1024px):** 8-column layout with `2.5rem` outer margins. Cards can split into 4-column side-by-side modules.
- **Desktop (> 1024px):** 12-column layout with a maximum container boundary of `1280px` and `5rem` lateral margin. Features asymmetric spans: a 5-column editorial text block paired with a 7-column clinical showcase imagery block.

Vertical rhythm relies on generous structural white space: sections are separated by `5rem` to `7.5rem` on desktop to convey calm confidence rather than urgent crowding.

## Elevation & Depth

Visual hierarchy does not rely on heavy drop shadows or dramatic blurs. Depth is achieved via **tonal layering**, **micro-translucency**, and **warm ambient halos**:

- **Borders over Shadows:** Surfaces utilize a delicate structural edge (`1px solid rgba(220, 201, 181, 0.45)`) that defines geometry without harsh separation.
- **Tonal Layering:** 
  - `Base`: Marfim canvas (`#F6F0E8`).
  - `Surface 1 (Cards)`: Tinted ivory-white (`rgba(255, 255, 255, 0.85)`) supported by a warm diffuse halo: `0 12px 36px -8px rgba(57, 51, 47, 0.05)`.
  - `Surface 2 (Overlays / Modals)`: Solid `#FBF8F4` with refined boundary `0 24px 48px -12px rgba(57, 51, 47, 0.08)`.
- **Floating Conversion Anchor:** The sticky WhatsApp consultation element uses an ambient terracotta-tinted glow: `0 10px 25px -5px rgba(169, 111, 85, 0.25)`.

## Shapes

The shape system expresses biological gentleness and organic curvature. Sharp edges are replaced with generous radiuses that ease tension:

- **Standard Elements (Buttons, Inputs, Badges):** Full pill curvature (`rounded-full`) or substantial soft radii (`1rem`).
- **Cards & Content Modules:** Large corner treatment using `rounded-2xl` (`1.5rem` / `24px`) on compact devices, advancing to `rounded-3xl` (`2rem` / `32px`) on desktop showcases.
- **Asymmetric Image Containers:** Specialized editorial masks combining unequal radii (e.g., `top-left: 6rem; top-right: 1.5rem; bottom-right: 6rem; bottom-left: 1.5rem`) for clinical and spatial photography, conveying custom architectural intentionality.

## Components

### Buttons
- **Primary CTA (Direct Scheduling / Conversion):** Terracotta background (`#A96F55`), text in Marfim (`#F6F0E8`), pill-shaped (`border-radius: 9999px`), padding `0.875rem 2rem`. Text set in `Plus Jakarta Sans` 600. Hover: background `#925E47` with a soft lift `translate-y-[-1px]`.
- **Secondary (Inquiry / Procedure Details):** Transparent background, `1.5px` border in `#A96F55`, text in `#A96F55`. Hover: background fills with `rgba(169, 111, 85, 0.06)`.
- **Ghost / Tertiary:** No border, text in `#52665A`, underline accent with `0.25rem` offset on hover.

### Badges & Micro-Pills
- Pill-shaped (`border-radius: 9999px`), `padding: 0.35rem 0.85rem`.
- **Clinical Badge:** Background `rgba(82, 102, 90, 0.10)`, text `#52665A`, 1px border `rgba(82, 102, 90, 0.25)`. Font: `label-sm`.
- **Prestige Badge:** Background `rgba(169, 111, 85, 0.10)`, text `#A96F55`, paired with a micro dot indicator (`4px` solid circle).

### Cards
- Fills: `rgba(255, 255, 255, 0.75)` with `backdrop-filter: blur(8px)`.
- Border: `1px solid rgba(220, 201, 181, 0.5)`.
- Radius: `24px` (`rounded-2xl`) or `32px` (`rounded-3xl`).
- Padding: `2rem` internal spacing.
- Sub-cards (procedure breakdowns) use solid `#F1E9DE` without drop shadows.

### Input Fields & Selectors
- Background: `#FBF8F4`.
- Border: `1px solid #DCC9B5`.
- Text: `#39332F`, placeholder in `rgba(57, 51, 47, 0.40)`.
- Radius: `14px`. Height: `52px` to accommodate effortless touch targeting.
- Focus: Border shifts to `#A96F55` with no aggressive outer glow—instead, a delicate outline `2px solid rgba(169, 111, 85, 0.15)`.

### Checkboxes & Radios
- Size: `20px x 20px`. Radius: `6px` for checkboxes, `50%` for radios.
- Unchecked: 1.5px border `#DCC9B5`, background transparent.
- Checked: Background `#A96F55`, border `#A96F55`, white checkmark or inner dot.

### Specialized Consultation Elements
- **WhatsApp Concierge Bubble:** Fixed bottom corner element. Surface: `#52665A` (Sage reassurance) or custom muted emerald with Terracotta notification badge. Includes refined text: *"Agendamento Exclusivo"*.
- **Doctor Credential Signature Module:** Combination of Playfair Display italic quote, CRO license badge in `label-sm`, and warm sand divider rule (`1px solid #DCC9B5`).