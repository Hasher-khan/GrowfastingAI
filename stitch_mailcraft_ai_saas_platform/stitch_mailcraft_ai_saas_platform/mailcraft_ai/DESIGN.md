---
name: MailCraft AI
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
  secondary: '#006591'
  on-secondary: '#ffffff'
  secondary-container: '#39b8fd'
  on-secondary-container: '#004666'
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
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#89ceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004c6e'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7d2d00'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
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
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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

This design system establishes a modern, premium SaaS aesthetic tailored for an intelligent AI email generator and grammar checker. The brand personality is trustworthy, intelligent, and approachable—balancing sophisticated automation with human-centric clarity. 

We employ a refined Modern SaaS style characterized by clean surfaces, generous whitespace, subtle gradients, and soft, ambient shadows. The visual language conveys reliability and precision without feeling clinical or intimidating.

## Colors

The color palette is built on a foundation of crisp whites and soft grays (#F8FAFC), anchored by deep navy typography (#0F172A) for maximum legibility and authority. 

Primary actions and focal points utilize a confident royal blue (#2563EB), complemented by a vibrant sky blue accent (#0EA5E9) for interactive states, gradients, and secondary highlights. Subtle neutral borders (#E2E8F0) structure the interface without creating visual clutter.

## Typography

Typography pairs the welcoming, geometric forms of Plus Jakarta Sans for headlines with the neutral, highly legible utility of Inter for body text and labels. 

Headlines utilize tighter letter-spacing to project modern authority, while body sizes maintain generous line heights to optimize readability across dense, content-heavy AI generation workflows. Headings exceeding 32px adapt responsively for mobile viewports to prevent wrapping anomalies.

## Layout & Spacing

The layout is governed by a 12-column fluid grid system optimized for desktop SaaS workspaces, collapsing gracefully into single-column layouts on mobile devices. 

We prioritize generous whitespace, utilizing 2rem outer canvas margins and 1.5rem gutters to let complex AI tools and email previews breathe. Element spacing adheres to a strict 4px/8px baseline grid, ensuring consistent vertical rhythm across panels, sidebars, and card layouts.

## Elevation & Depth

Visual hierarchy is achieved through a combination of tonal layering and soft, ambient shadows. 

Surfaces are elevated using subtle shadow diffusion (`box-shadow: 0 4px 6px -1px rgba(15, 23, 42, 0.05)`) paired with thin, crisp borders (#E2E8F0) to define structural boundaries without heavy contrast. Interactive elements lift slightly on hover, reinforcing tactile responsiveness in high-frequency editing environments.

## Shapes

The shape language is consistently rounded and approachable, utilizing a base border-radius of 0.5rem (8px) for inputs and small controls, and scaling up to 1rem (16px) or 1.25rem (20px) for primary containers, cards, and modal dialogs. 

This friendly geometry softens the technical precision of the AI engine, making complex configuration panels feel welcoming and easy to navigate.

## Components

### Buttons
Primary buttons feature solid primary or gradient backgrounds with rounded corners (8px–12px), subtle hover states, and clear focus rings. Secondary and ghost variants utilize clean borders or transparent fills with navy text.

### Input Fields & Textareas
Designed for heavy text generation and editing. Featuring a clean white background, thin neutral borders (#E2E8F0), and focused states highlighted by the primary blue ring. Include subtle helper text and inline AI generation triggers.

### Cards
Built with generous internal padding, 12px–16px border-radius, soft background fills, and delicate outlines. Used extensively for email previews, tone-selection modules, and analytics summaries.

### Chips & Badges
Pill-shaped or softly rounded micro-elements used for tone tags (e.g., "Professional", "Casual"), grammar suggestion counters, and status indicators.

### Checkboxes & Radio Buttons
Clean, systematic controls with precise square/circular geometry, utilizing primary accent fills when selected.

### Additional Components
- **AI Prompt Bars:** Floating input bars with integrated action pills for tone adjustment and length constraints.
- **Diff Viewers:** Side-by-side or inline comparison components for grammar corrections with clear accept/reject micro-actions.