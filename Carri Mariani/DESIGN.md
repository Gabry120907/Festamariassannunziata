---
name: Annunziata 413
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#43474f'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#737780'
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40'
  on-primary: '#ffffff'
  primary-container: '#003366'
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#221e0d'
  on-tertiary: '#ffffff'
  tertiary-container: '#383321'
  on-tertiary-container: '#a29b83'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#ebe2c8'
  tertiary-fixed-dim: '#cec6ad'
  on-tertiary-fixed: '#1f1c0b'
  on-tertiary-fixed-variant: '#4c4733'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  grid-margin: 24px
  grid-gutter: 24px
---

## Brand & Style[cite: 12]

The design system is anchored in the intersection of historical solemnity and contemporary accessibility. It serves the 413th iteration of a sacred tradition, requiring a visual language that feels both ancient and vital[cite: 12].

The aesthetic direction is **Sophisticated Editorial**[cite: 12]. It utilizes high-contrast serif typography and a restricted, regal color palette to evoke a sense of "sacred prestige."[cite: 12] The UI draws from classical Italian archival layouts—generous white space, meticulous alignment, and gold accents—while maintaining the functional clarity of modern web standards[cite: 12]. The emotional response should be one of reverence, community pride, and historical continuity[cite: 12].

## Colors[cite: 12]

The palette is rooted in Marian iconography and liturgical tradition[cite: 12].

*   **Primary (Blu Mariano - #003366):** Used for primary navigation, headings, and key brand moments[cite: 12]. It represents the mantle of the Virgin and provides a deep, authoritative contrast[cite: 12].
*   **Secondary (Oro - #C5A059):** A muted, satin gold used for accents, borders, and interactive states[cite: 12]. It should be used sparingly to maintain its perceived value[cite: 12].
*   **Backgrounds:**[cite: 12]
    *   **Avorio (#FDFBF7):** The default background for standard content pages to reduce eye strain[cite: 12].
    *   **Pergamena (#F4EBD0):** Reserved for historical sections, timelines, and "archival" components to provide a tactile, paper-like feel[cite: 12].
    *   **White (#FFFFFF):** Used for dynamic utility sections, forms, and high-density data[cite: 12].

## Typography[cite: 12]

This design system uses a high-contrast typographic pairing to bridge the gap between 1611 and the present day[cite: 12].

**Headlines (Playfair Display):** Should be set with tight letter-spacing[cite: 12]. For the "413th" designation and major titles, use the Display-LG weight to create a focal point[cite: 12]. Use italic styles for quotes or specific liturgical Latin phrases[cite: 12].

**Body (Inter):** Chosen for its exceptional legibility on mobile devices[cite: 12]. Use the Medium weight (500) for introductory paragraphs and Regular (400) for long-form historical text[cite: 12].

**Label-Caps:** Use for "Overlines" (small text above headings) to categorize content (e.g., "TRADITION", "LITURGY")[cite: 12].

## Layout & Spacing[cite: 12]

The layout follows a **Fixed Grid** philosophy on desktop (12 columns, 1200px max-width) to mimic the structured nature of an illuminated manuscript or a formal program[cite: 12].

*   **Rhythm:** Use an 8px base unit[cite: 12]. All margins and paddings should be multiples of 8[cite: 12].
*   **Negative Space:** Use aggressive vertical spacing (120px+) between major sections to allow the imagery and typography to "breathe," emphasizing the solemnity of the content[cite: 12].
*   **Mobile Adaptivity:** On mobile, margins reduce to 24px and the grid collapses to a single column[cite: 12]. Horizontal scrolling is permitted for historical timelines and gallery previews[cite: 12].

## Elevation & Depth[cite: 12]

Depth is communicated through **Tonal Layering** and **Subtle Outlines** rather than heavy shadows[cite: 12].

*   **Surfaces:** Use the Pergamena (#F4EBD0) color to indicate "elevated" content sections against the Avorio (#FDFBF7) background[cite: 12].
*   **Borders:** Employ thin (1px) borders in Oro (#C5A059) or low-opacity Blu Mariano (10%) to define containers[cite: 12].
*   **Shadows:** When necessary for interactivity (e.g., hovering over a card), use a very soft, "Ambient" shadow: `0px 12px 32px rgba(0, 51, 102, 0.05)`[cite: 12]. This creates a subtle lift without feeling "tech-heavy."[cite: 12]
*   **Glassmorphism:** Use a light blur (8px) with a semi-transparent White (80%) for fixed navigation bars to maintain context of the underlying imagery[cite: 12].

## Shapes[cite: 12]

The shape language is conservative and architectural[cite: 12]. 

*   **Corners:** UI elements use "Soft" (4px) corners[cite: 12]. This avoids the harshness of pure sharp edges while remaining more formal and structured than fully rounded shapes[cite: 12].
*   **Interactive Elements:** Buttons and Input fields maintain this 4px radius[cite: 12]. 
*   **Decorative Elements:** Vertical lines (dividers) should be used to separate content, capped with a 4px Gold square at the start or end to simulate traditional typesetting ornaments[cite: 12].

## Components[cite: 12]

*   **Hero Banners:** Use full-bleed high-resolution photography of the "Simulacro" or the Pedara Basilica[cite: 12]. Apply a gradient overlay (Blu Mariano to Transparent) to ensure Playfair Display headings remain legible[cite: 12].
*   **Buttons:**[cite: 12]
    *   *Primary:* Solid Blu Mariano background, White Inter text (Caps), 4px radius[cite: 12]. 
    *   *Secondary:* Transparent background, 1px Oro border, Oro text[cite: 12]. 
    *   *Hover state:* Swap Oro for Blu Mariano; add subtle 2px vertical offset[cite: 12].
*   **Historical Cards:** Avorio background with a 1px Oro bottom border[cite: 12]. These should use "Headline-SM" for titles[cite: 12].
*   **Vertical Timelines:** A 2px Oro central axis[cite: 12]. Historical milestones are marked with Blu Mariano circles[cite: 12]. Use the Pergamena background for this entire component to signal a transition into the past[cite: 12].
*   **Inputs:** Minimalist style[cite: 12]. No background (transparent), 1px Blu Mariano bottom-border only, with Label-Caps floating above[cite: 12].
*   **Liturgical Lists:** Use small Gold icons (crosses or stylized petals) as bullet points instead of standard discs[cite: 12].