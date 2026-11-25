---
name: "Mehro nisa Malik Clinical Nutrition"
description: "A calm, trustworthy, medical-grade yet warm design system for Mehro nisa Malik's clinical dietetics practice, built on sage green, deep forest green, warm off-white, and soft coral accents."
---

## Overview

This design system shapes the personal professional website and clinical booking experience for **Mehro nisa Malik, Clinical Dietician**. It balances medical-grade credibility with the warmth and approachability of whole-food, evidence-based nutrition care.

- **Brand Personality:** Calm, reassuring, knowledgeable, and grounded.
- **Target Audience:** Patients seeking trustworthy, personalised clinical nutrition guidance for diabetes, PCOS, weight management, renal and cardiac health, and family nutrition—primarily browsing on mobile and desktop.
- **Design Style:** Warm Editorial Minimalism — generous warm off-white breathing room, soft sage tonal surfaces, rounded botanical geometry, and high-legibility typography pairing an editorial serif for headings with a clean geometric sans-serif for clinical copy.

## Colors

The palette anchors on **Warm Off-White** (`#FAF8F4`) for calm, paper-like backgrounds, **Deep Forest Green** (`#2F4F3E`) for authoritative headings and primary actions, **Sage Green** (`#7FA68A`) for botanical brand accents and soft dividers, and **Soft Coral** (`#E07A5F` / `#B95C43` accessible action tone) for inviting consultation calls-to-action.

- **Primary & Headings:** Deep Forest Green (`#2F4F3E`) provides crisp contrast on light surfaces and anchors primary navigation and clinical credibility.
- **Sage Brand Accent:** Sage Green (`#7FA68A`) is used for decorative botanical accents, trust-strip icons, and soft tinted borders.
- **Warm Coral CTA:** Soft Coral (`#E07A5F`) and its accessible button tone (`#B95C43`) draw gentle, encouraging attention to consultation booking actions.
- **Surfaces:** Warm Off-White (`#FAF8F4`) pairs with pure white (`#FFFFFF`) and soft sage-tinted containers (`#ECF3EA`) to create quiet visual hierarchy without harsh borders.

```yaml
colors:
  sage-green: "#7FA68A"
  deep-forest-green: "#2F4F3E"
  warm-off-white: "#FAF8F4"
  soft-coral: "#E07A5F"
  primary: "#2F4F3E"
  on-primary: "#FFFFFF"
  primary-container: "#C3ECCD"
  on-primary-container: "#123722"
  secondary: "#42664E"
  on-secondary: "#FFFFFF"
  secondary-container: "#D1FBDB"
  on-secondary-container: "#123722"
  accent: "#B95C43"
  on-accent: "#060606"
  accent-container: "#FFDBD2"
  on-accent-container: "#3C0800"
  surface: "#FAF8F4"
  on-surface: "#1B1C1A"
  surface-container-lowest: "#FFFFFF"
  surface-container-low: "#F2F0ED"
  surface-container: "#ECF3EA"
  surface-container-high: "#DDE4DC"
  on-surface-variant: "#424842"
  outline: "#727972"
  outline-variant: "#C1C8C0"
  error: "#BA1A1A"
  on-error: "#FFFFFF"
```

## Typography

Typography pairs **Playfair** for editorial, trustworthy headings with **Poppins** for friendly, highly legible clinical body copy and UI controls. **Spline Sans Mono** handles tabular metrics and consultation durations.

```yaml
typography:
  display-lg:
    fontFamily: "Playfair"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 56px
    letterSpacing: -0.5px
  display-lg-mobile:
    fontFamily: "Playfair"
    fontSize: 32px
    fontWeight: 700
    lineHeight: 38px
    letterSpacing: -0.25px
  headline-lg:
    fontFamily: "Playfair"
    fontSize: 36px
    fontWeight: 600
    lineHeight: 44px
    letterSpacing: -0.25px
  headline-lg-mobile:
    fontFamily: "Playfair"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 34px
    letterSpacing: -0.15px
  headline-md:
    fontFamily: "Playfair"
    fontSize: 26px
    fontWeight: 600
    lineHeight: 34px
    letterSpacing: 0px
  title-lg:
    fontFamily: "Poppins"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 28px
    letterSpacing: 0px
  title-md:
    fontFamily: "Poppins"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 24px
    letterSpacing: 0.1px
  body-lg:
    fontFamily: "Poppins"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 28px
    letterSpacing: 0px
  body-md:
    fontFamily: "Poppins"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0.1px
  body-sm:
    fontFamily: "Poppins"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0.15px
  label-lg:
    fontFamily: "Poppins"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 20px
    letterSpacing: 0.25px
  label-sm:
    fontFamily: "Poppins"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 16px
    letterSpacing: 0.3px
  mono-md:
    fontFamily: "Spline Sans Mono"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 20px
    letterSpacing: 0px
```

## Layout & Spacing

The layout uses a **Fluid Grid** on mobile viewports (`< 768px`) with 20px–24px side margins, expanding to a **Fixed-Max-Width 12-Column Grid** (`max-w-7xl` / `1200px` content container) on desktop with generous vertical section rhythm (`64px`–`96px`). All spacing tokens follow an 8px base rhythm with a 4px half-step for tight UI alignment.

```yaml
spacing:
  gutter-xs: 4px
  gutter-sm: 8px
  gutter-md: 16px
  gutter-lg: 24px
  gutter-xl: 32px
  section: 64px
  page-margin: 24px
```

## Elevation & Depth

Visual hierarchy relies primarily on **tonal surface layering** (`#FAF8F4` base, `#FFFFFF` elevated cards, `#ECF3EA` soft sage containers) paired with **extra-diffused ambient shadows** tinted subtly toward deep forest green (`rgba(47, 79, 62, 0.06)`). Avoid heavy drop shadows or crisp dark borders; use soft `1px` `outline-variant` borders only where cards sit on matching surfaces.

## Shapes

Every interactive element and content container uses generous, approachable rounded corners. Primary buttons and pill badges use `full` (`9999px`) or `lg` (`16px`), cards use `xl` (`24px`), and form inputs use `md` (`12px`).

```yaml
rounded:
  sm: 6px
  DEFAULT: 12px
  md: 12px
  lg: 16px
  xl: 24px
  full: 9999px
```

## Motion & Micro-interaction

Motion is gentle, unhurried, and reassuring—mirroring a calm clinical consultation. Interactive button and card hovers respond smoothly without jarring snaps, and scroll-reveal transitions decelerate softly. Honour `prefers-reduced-motion` and animate only `transform`, `opacity`, and color.

```yaml
motion:
  state-change:
    duration: 180ms
    delay: 0ms
    timingFunction: ease-out
  surface-enter:
    duration: 320ms
    delay: 0ms
    timingFunction: cubic-bezier(0.2, 0, 0, 1)
  surface-exit:
    duration: 200ms
    delay: 0ms
    timingFunction: cubic-bezier(0.3, 0, 1, 1)
```

## Voice & Content Strategy

- **Tone of Voice:** Professional, reassuring, and encouraging. Speak clearly in plain, non-medical language so patients feel supported rather than overwhelmed. Never make extreme "quick fix" or miracle weight-loss claims.
- **Capitalisation:** Sentence case for body copy, form labels, and secondary descriptions; Title Case for navigation links, section headings, and primary consultation buttons.
- **Terminology:** Use "Consultation" (not "Session" or "Meeting"), "Personalised Nutrition Plan" (not "Diet Hack"), and "Clinical Dietician" consistently.
- **Action Labels:** Use clear, outcome-focused verbs such as `Book a Consultation`, `Explore Services`, and `Read Article`.
- **Medical Disclaimer:** Always include the clear footer note: *"Information on this website does not replace personalised medical advice."*

## Components

Component implementations live as individual HTML sticker sheet files in
`components/`. Each file contains the canonical, styled HTML components with
`<!-- COMPONENT: name -->` comment markers. Read each file before use.

- **Badge** → `@components/badge.html` — `badge-numeric`, `badge-dot`
- **Button** → `@components/button.html` — `button-primary`, `button-icon`, `button-with-icon`
- **Card** → `@components/card.html` — `card-elevated`, `card-action`, `card-interactive`, `card-interactive-2`
- **Typography** → `@components/typography.html` — `typography-display`, `typography-body`, `typography-label`
