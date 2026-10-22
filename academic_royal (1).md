---
name: Academic Royal
colors:
  surface: '#f8f9fd'
  surface-dim: '#d9dade'
  surface-bright: '#f8f9fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3f7'
  surface-container: '#edeef2'
  surface-container-high: '#e7e8ec'
  surface-container-highest: '#e1e2e6'
  on-surface: '#191c1f'
  on-surface-variant: '#43474e'
  inverse-surface: '#2e3134'
  inverse-on-surface: '#eff1f5'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#455f88'
  primary: '#002045'
  on-primary: '#ffffff'
  primary-container: '#1a365d'
  on-primary-container: '#86a0cd'
  inverse-primary: '#adc7f7'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#420f00'
  on-tertiary: '#ffffff'
  tertiary-container: '#661c00'
  on-tertiary-container: '#ff7545'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#adc7f7'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59d'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#832600'
  background: '#f8f9fd'
  on-background: '#191c1f'
  surface-variant: '#e1e2e6'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Montserrat
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Montserrat
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
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

The visual identity embodies an institutional yet deeply welcoming educational foundation. Rooted in traditional academic dignity and future-forward pedagogical clarity, the aesthetic balances the disciplined gravitas of deep royal navy with the vibrant optimism of sacred saffron. It serves a multigenerational audience—primary students, discerning parents, and dedicated faculty—requiring an atmosphere that feels scholarly, secure, and warmly accessible.

The design movement blends **Corporate / Modern** clarity with **Humanist Educational Tactility**. Structural surfaces remain clean and distraction-free, prioritizing immediate comprehension and high contrast. Rounded forms, ambient navy-tinted shadows, and clear bilingual script accommodations ensure digital touchpoints feel friendly rather than bureaucratic, instilling pride, character, and scholastic focus.

## Colors

The palette establishes an immediate academic hierarchy through deep, trusted foundations illuminated by warm, aspirational accents:

- **Primary (`#1A365D`):** Classic deep royal navy. Used for core brand elements, primary actions, critical navigation, and authoritative headlines. Communicates institutional heritage, discipline, and stability.
- **Secondary (`#D97706`):** Radiant warm saffron. Employed for secondary emphasis, active state highlights, achievement indicators, and key student badges.
- **Tertiary (`#C2410C`):** Deep terracotta maroon-orange. Applied sparingly for urgency indicators, high-priority notifications, and grounded cultural motifs.
- **Neutral Foundation (`#F3F4F8`):** An ultra-soft, cool-tinted lavender-slate canvas that softens glare compared to raw white, reducing eye fatigue during sustained reading sessions.

### Semantic & Surface Rules
- **Canvas Base:** `#F3F4F8` provides page-level grounding.
- **Surface Level 1 (Cards, Sections):** Crisp pure white (`#FFFFFF`) to produce clean physical separation against the tinted canvas.
- **Text Primary:** Deep slate navy (`#0F1E36`) ensuring a minimum 7:1 contrast ratio against white containers.
- **Text Muted:** Balanced neutral blue-grey (`#475569`) strictly calibrated for secondary metadata and bilingual subtexts.

## Typography

The type scale combines the geometric confidence of Montserrat for titles, structural navigation, and badges with the humanist warmth and legibility of Open Sans for body prose, tabular school reports, and bilingual scripts.

### Typographic Hierarchy & Application
- **Display & Section Titles (`headline-xl`, `headline-lg`):** Executed in Montserrat with tight tracking. Provides modern gravitas for portal headers, school announcements, and module titles.
- **Content Blocks (`body-lg`, `body-md`):** Open Sans provides open counters and sturdy verticals, rendering English and Devanagari numerals with equal clarity across desktop and mobile viewports.
- **Bilingual Stacking Rules:** When Hindi (Devanagari) transliterations or translations appear alongside English, pair primary English labels in Montserrat with secondary sub-labels rendered in Open Sans at `body-sm` (400 weight), allowing a 1.25x line height increase to prevent vowel-mark clipping.

## Layout & Spacing

The system implements a structured 12-column responsive fluid grid on desktop viewports, transitioning to an 8-column layout on tablets, and a compact 4-column layout on mobile devices.

### Layout Philosophy & Rhythms
- **Canvas Centering & Max Width:** Academic dashboard and portal layouts constrain to a max container width of `1280px` to maintain optimal line reading lengths.
- **Desktop Grid:** 12 columns with `gutter: 1.5rem` and outer canvas margins of `margin: 2rem`. Content blocks group in spans of 3, 4, 6, or 12.
- **Mobile Grid:** 4 columns with `gutter-mobile: 1rem` and edge margins of `margin-mobile: 1rem`. Cards and data tables collapse into unified vertical stacks.
- **Vertical Spacing Scale:** Layout flow strictly honors the 8pt rhythm using defined component gap tokens: compact list gaps use `space-xs` and `space-sm`, interactive container padding scales with `space-md` to `space-lg`, and primary distinct page modules separate via `space-xl`.

## Elevation & Depth

Visual hierarchy is maintained via gentle, light-diffused ambient elevations tinted with the deep royal navy hue, eliminating harsh, clinical grays.

### Elevation Levels
- **Level 0 (Flat / Canvas):** Surface color `#F3F4F8`. No drop shadow. Used for page backgrounds, dividers, and inactive state panels.
- **Level 1 (Card & Module Resting):** Pure white container `#FFFFFF` with a soft ambient shadow: `0 4px 16px -2px rgba(26, 54, 93, 0.06), 0 2px 6px -1px rgba(26, 54, 93, 0.04)`. Outlined with a fine 1px hairline border in `rgba(26, 54, 93, 0.08)` to prevent edge bleed on low-contrast screens.
- **Level 2 (Interactive Hover & Modals):** `0 12px 28px -4px rgba(26, 54, 93, 0.12), 0 4px 10px -2px rgba(26, 54, 93, 0.06)`. Used for interactive card states, elevated floating action buttons, dropdown menus, and school alerts.
- **Level 3 (Overlays & Dialogs):** `0 24px 48px -8px rgba(15, 30, 54, 0.20)`. Backed by an institutional navy backdrop veil (`rgba(15, 37, 82, 0.40)`) with a light 4px blur.

## Shapes

The interface embraces a friendly, rounded shape language (`roundedness: 2`) that softens academic formality while retaining institutional discipline.

### Geometric Application
- **Base Geometry (`0.5rem` / 8px):** Applied to form input fields, table action cells, and standard UI controls.
- **Card & Container Radius (`rounded-lg: 1rem` to `rounded-xl: 1.5rem` / 16px–24px):** Applied to student information cards, academic modules, and portal dashboard containers. The curvature produces an approachable, safe tactile feel.
- **Pill Radius (`9999px`):** Reserved exclusively for status indicators, student badges, bilingual chips, and small pill buttons.

## Components

### Buttons
- **Primary Action:** Solid `#1A365D` navy fill with white text (`label-md`). Fully rounded edges (`rounded-lg` or pill), 48px minimum touch height, padded horizontally with `space-lg`. Hover brings a 4% brightness lift and Level 2 elevation.
- **Secondary / Accent Action:** Solid `#D97706` saffron fill with white text for admissions, student rewards, and critical highlights.
- **Subtle / Ghost:** Pure white background with a 1.5px border in `#1A365D` and navy text.

### Badges & Student Awards
- **Structure:** Pill-shaped elements featuring an icon, bold text, and a soft tinted background.
- **House / Achievement Badges:** Gold/Saffron (`#FEF3C7` background, `#D97706` border, `#92400E` text), Navy Merit (`#E0E7FF` background, `#1A365D` border and text).
- **Sizing:** Fixed height of 28px, padded `space-sm` horizontally with `label-sm` typography.

### Bilingual Chips
- **Layout:** Inline horizontal or dual-line vertical elements designed for dual English/Hindi language tags (e.g., "Mathematics / गणित").
- **Styling:** Soft background (`#FFFFFF`), subtle border (`rgba(26, 54, 93, 0.12)`), radius of `rounded-lg` (16px). Secondary native script renders at `body-sm` in `#475569`.

### Cards & Panels
- **Student Profile & Course Cards:** Crisp white surface (`#FFFFFF`), rounded-xl (20px) corners, Level 1 elevation, and interior padding using `space-lg`. Features an optional top accent stripe (4px) in saffron or navy to indicate academic categories.

### Form Inputs & Checkboxes
- **Input Fields:** 48px height, rounded corners (`rounded: 0.5rem`), `#FFFFFF` surface, hairline border in `rgba(26, 54, 93, 0.20)`. On focus, transitions to a 2px solid `#1A365D` border with a subtle 3px ring in `rgba(26, 54, 93, 0.12)`.
- **Checkboxes & Radios:** 20px touch target housed within a 44px accessible hit box. Selected states fill with `#1A365D` displaying a crisp white indicator.

### Lists
- **Academic Lists:** Borderless items separated by `space-sm` gaps, each styled as a micro-card with Level 0 or hairline border, containing leading student avatar or subject badge, clear dual-line title/subtitle, and trailing performance or date metrics.