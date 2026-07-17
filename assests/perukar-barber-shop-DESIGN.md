---
version: alpha
name: "Perukar Dark Masculine"
description: "Perukar is a dark, masculine barber shop template built on full-bleed photography with a warm earth-tone color system anchored by deep brown (#14100c), warm taupe (#625c56), and gold-bronze (#91765a). Typography is exclusively Outfit with heavy uppercase tracking for labels and bold weight for headings, creating a sharp, editorial barbershop identity. The layout uses generous vertical padding (120–160px sections), zero border-radius throughout, and a flat shadow strategy. Navigation links are rendered in the brand gold (#91765a) against a transparent dark overlay, reinforcing the premium masculine aesthetic."
colors:
  deep-espresso: "#14100c"
  ivory-white: "#fdfbf8"
  light-gray: "#f4f4f4"
  warm-cream: "#f5eee7"
  dark-charcoal: "#212529"
  gold-bronze: "#91765a"
  muted-stone: "#aba59f"
  pure-white: "#ffffff"
  warm-taupe: "#625c56"
typography:
  hero-headline:
    fontFamily: "Outfit"
    fontSize: "48px"
    fontWeight: "800"
    lineHeight: "57.6px"
  section-heading-large:
    fontFamily: "Outfit"
    fontSize: "27px"
    fontWeight: "800"
    lineHeight: "33.75px"
  section-heading-medium:
    fontFamily: "Outfit"
    fontSize: "24px"
    fontWeight: "800"
    lineHeight: "30px"
  card-heading:
    fontFamily: "Outfit"
    fontSize: "18px"
    fontWeight: "800"
    lineHeight: "22.5px"
  small-heading:
    fontFamily: "Outfit"
    fontSize: "17px"
    fontWeight: "800"
    lineHeight: "35px"
  uppercase-label:
    fontFamily: "Outfit"
    fontSize: "12px"
    fontWeight: "800"
    lineHeight: "26.25px"
    letterSpacing: "2px"
  nav-label:
    fontFamily: "Outfit"
    fontSize: "12px"
    fontWeight: "800"
    lineHeight: "20px"
    letterSpacing: "1px"
  body-text:
    fontFamily: "Outfit"
    fontSize: "15px"
    fontWeight: "300"
    lineHeight: "26.25px"
  body-regular:
    fontFamily: "Outfit"
    fontSize: "15px"
    fontWeight: "400"
    lineHeight: "26.25px"
  small-body:
    fontFamily: "Outfit"
    fontSize: "16px"
    fontWeight: "300"
    lineHeight: "26.25px"
rounded:
  sharp: "0px"
  subtle: "1px"
  small: "5px"
  pill: "50px"
spacing:
  xs: "5px"
  sm: "10px"
  md-sm: "12px"
  md: "15px"
  md-lg: "20px"
  lg: "25px"
  xl: "30px"
  2xl: "40px"
  3xl: "50px"
  4xl: "70px"
  5xl: "90px"
  section: "120px"
  hero: "160px"
---

## Overview

Perukar is a dark, masculine barber shop template built on full-bleed photography with a warm earth-tone color system anchored by deep brown (#14100c), warm taupe (#625c56), and gold-bronze (#91765a). Typography is exclusively Outfit with heavy uppercase tracking for labels and bold weight for headings, creating a sharp, editorial barbershop identity. The layout uses generous vertical padding (120–160px sections), zero border-radius throughout, and a flat shadow strategy. Navigation links are rendered in the brand gold (#91765a) against a transparent dark overlay, reinforcing the premium masculine aesthetic.

**Signature traits:**
- Single-family weight hierarchy: Builds hierarchy from Outfit across 3 weights rather than multiple families.
- Soft, rounded geometry: Generous corner rounding up to 50px.
- Layered elevation: Depth comes from 2 validated shadow tokens.

## Colors

The palette uses 9 validated color tokens across 1 theme profile. Semantic roles stay attached to observed usage so generation agents can choose accents without inventing new color meaning.

**Semantic naming:**
- **surface-background** maps to `deep-espresso`: Role "background" is grounded by usage context "Primary dark background for navbar dropdown, footer, and dark section overlays".
- **content-text** maps to `warm-taupe`: Role "text" is grounded by usage context "Default body text, navbar base color, hero section text color".
- **action-text** maps to `gold-bronze`: Role "text" is grounded by usage context "Navigation link color, CTA accent, brand highlight color on interactive elements".

### Text Scale
- **Dark Charcoal** (#212529): Dropdown menu text, body color fallback. Role: text. {authored: rgb(33, 37, 41), space: rgb}
- **Gold Bronze** (#91765a): Navigation link color, CTA accent, brand highlight color on interactive elements. Role: text. {authored: rgb(145, 118, 90), space: rgb}
- **Muted Stone** (#aba59f): Placeholder text, secondary muted labels, form input text. Role: text. {authored: rgb(171, 165, 159), space: rgb}
- **Pure White** (#ffffff): Hero headings, dropdown link text, footer text on dark backgrounds. Role: text. {authored: rgb(255, 255, 255), space: rgb, alpha: 0.2}
- **Warm Taupe** (#625c56): Default body text, navbar base color, hero section text color. Role: text. {authored: rgb(98, 92, 86), space: rgb}

### Surface & Shadows
- **Deep Espresso** (#14100c): Primary dark background for navbar dropdown, footer, and dark section overlays. Role: background. {authored: rgb(20, 16, 12), space: rgb}
- **Ivory White** (#fdfbf8): Footer localized surface, subtle warm white background. Role: background. {authored: rgb(253, 251, 248), space: rgb}
- **Light Gray** (#f4f4f4): Alternate section backgrounds, card surfaces. Role: background. {authored: rgb(244, 244, 244), space: rgb}
- **Warm Cream** (#f5eee7): Light section backgrounds, warm off-white surface areas. Role: background. {authored: rgb(245, 238, 231), space: rgb}

## Typography

Typography uses Outfit across extracted hierarchy roles. Keep hierarchy mapped to these token rows before adding decorative type styles.

Uses Outfit throughout for a uniform feel. Weight range spans bold, light, regular. Sizes range from 12px to 48px.

### Font Roles
- **Headline Font**: Outfit
- **Body Font**: Outfit

### Type Scale Evidence
| Role | Font | Size | Weight | Line Height | Letter Spacing | Stack / Features | Notes |
|------|------|------|--------|-------------|----------------|------------------|-------|
| Primary hero heading — large bold display text over photography | Outfit | 48px | 800 | 57.6px | normal | Outfit, sans-serif | Extracted token |
| Section-level headings and card titles | Outfit | 27px | 800 | 33.75px | normal | Outfit, sans-serif | Extracted token |
| Sub-section headings and feature titles | Outfit | 24px | 800 | 30px | normal | Outfit, sans-serif | Extracted token |
| Card and widget headings | Outfit | 18px | 800 | 22.5px | normal | Outfit, sans-serif | Extracted token |
| Minor headings and list item titles | Outfit | 17px | 800 | 35px | normal | Outfit, sans-serif | Extracted token |
| Section eyebrow labels, category tags, navigation items — tracked uppercase | Outfit | 12px | 800 | 26.25px | 2px | Outfit, sans-serif | Extracted token |
| Navigation link labels with letter-spacing | Outfit | 12px | 800 | 20px | 1px | Outfit, sans-serif | Extracted token |
| Primary body copy, descriptions, paragraph text | Outfit | 15px | 300 | 26.25px | normal | Outfit, sans-serif | Extracted token |
| Secondary body text, link text, list items | Outfit | 15px | 400 | 26.25px | normal | Outfit, sans-serif | Extracted token |
| Slightly larger body variant for introductory paragraphs | Outfit | 16px | 300 | 26.25px | normal | Outfit, sans-serif | Extracted token |

## Layout

Responsive system uses 3 breakpoint tier(s): mobile, tablet, desktop.

This system uses a 5px base grid with scale values 5, 10, 12, 15, 20, 25, 30, 40, 50, 70, 90, 120, 160.

### Responsive Strategy
- **mobile (<= 1259.98px)**: Constrain layout for small viewports and prioritize vertical stacking.
- **tablet (>= 992px)**: Increase spacing and column structure for medium-width viewports.
- **desktop (>= 1200px)**: Expand layout density and horizontal composition for wide viewports.

### Spacing System
| Token | Value | Px | Notes |
|------|-------|----|-------|
| xs | 5px | 5 | Extracted spacing token |
| sm | 10px | 10 | Extracted spacing token |
| md-sm | 12px | 12 | Extracted spacing token |
| md | 15px | 15 | Extracted spacing token |
| md-lg | 20px | 20 | Extracted spacing token |
| lg | 25px | 25 | Extracted spacing token |
| xl | 30px | 30 | Extracted spacing token |
| 2xl | 40px | 40 | Extracted spacing token |
| 3xl | 50px | 50 | Extracted spacing token |
| 4xl | 70px | 70 | Extracted spacing token |
| 5xl | 90px | 90 | Extracted spacing token |
| section | 120px | 120 | Extracted spacing token |
| hero | 160px | 160 | Extracted spacing token |

## Elevation & Depth

Keep depth flat unless validated shadow or interaction evidence appears in the extraction payload. Do not invent shadows beyond this evidence boundary.

### Shadow Evidence
| Shadow Token | Layers | Details |
|--------------|--------|---------|
| inset-subtle | 1 | inset 0px 0px 0px 0px rgba(217, 214, 209, 0.5) |
| top-border-glow | 1 | 0px -1px 0px 0px rgba(255, 255, 255, 0.04) |

### Interaction Signals
| Theme | Signal | Evidence |
|-------|--------|----------|
| Light | outline-color | rgb(98, 92, 86) ; rgb(255, 255, 255) ; rgb(145, 118, 90) |
| Light | outline-width | 3px ; 0px |
| Light | outline-offset | 0px |
| Light | transform | matrix(1, 0, 0, 1, 0, 0) ; matrix(1, 0, 0, 1, 0, -152.5) ; matrix(1, 0, 0, 1, 0, 20) |

## Shapes

Shape language maps directly to rounded tokens. Keep component corners consistent with the role mapping below before introducing bespoke geometry.

### Radius Roles
| Token | Value | Px | Role Mapping |
|------|-------|----|--------------|
| sharp | 0px | 0 | Hairline corner |
| subtle | 1px | 1 | Hairline corner |
| small | 5px | 5 | Subtle corner |
| pill | 50px | 50 | Large surface corner |

### Geometry Evidence
| Radius Token | Shape | Units |
|--------------|-------|-------|
| sharp | 0 | px |
| subtle | 1px | px |
| small | 5px | px |
| pill | 50px | px |

## Components

(none detected)

## Do's and Don'ts

Guardrails protect Single-family weight hierarchy, Soft, rounded geometry, Layered elevation without adding unsupported visual claims.

| Do | Don't |
|----|---------|
| Do maintain consistent spacing using the base grid | Don't make unsupported claims about absent visual features |
| Do maintain WCAG AA contrast ratios (4.5:1 for normal text) | Don't mix rounded and sharp corners in the same view |
| Do use the primary color only for the single most important action per screen |  |
| Do verify evidence before writing new design-system guidance |  |

## Responsive Evidence

### Breakpoints
| Name | Width | Key Changes |
|------|-------|-------------|
| Mobile | <= 480px | screen and (max-width: 480px) |
| Mobile | <= 767px | (max-width: 767px) |
| Breakpoint 3 | <= 767.98px | (max-width: 767.98px) |
| Breakpoint 4 | <= 768px | screen and (max-width: 768px) |
| Breakpoint 5 | <= 991px | screen and (max-width: 991px) |
| Breakpoint 6 | <= 991.98px | (max-width: 991.98px) |
| Breakpoint 7 | <= 1199px | (max-width: 1199px) |
| Breakpoint 8 | <= 1259.98px | (max-width: 1259.98px) |
| Tablet | >= 992px | screen and (min-width: 992px) |
| Desktop | >= 1200px | (min-width: 1200px) |

## Agent Prompt Guide

### Example Component Prompts
- Create button component using validated primary color role and spacing tokens.
- Create card component with mapped radius role and evidence-backed elevation.
- Create form input component using inferred typography hierarchy and border roles.

### Iteration Guide
1. Start with extracted palette and typography roles only.
2. Map spacing and radius directly from token tables before visual polish.
3. Apply component patterns one section at a time and compare against source intent.
4. Keep elevation claims tied to explicit evidence in output.
5. Iterate with smallest diffs and re-check section hierarchy after each change.
