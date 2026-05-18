---
name: Industrial Authority
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#44474c'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#75777d'
  outline-variant: '#c5c6cc'
  surface-tint: '#535f70'
  primary: '#05111f'
  on-primary: '#ffffff'
  primary-container: '#1a2635'
  on-primary-container: '#818da0'
  inverse-primary: '#bbc7db'
  secondary: '#b71410'
  on-secondary: '#ffffff'
  secondary-container: '#dc3227'
  on-secondary-container: '#fffbff'
  tertiary: '#10100d'
  on-tertiary: '#ffffff'
  tertiary-container: '#252522'
  on-tertiary-container: '#8d8c88'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e3f8'
  primary-fixed-dim: '#bbc7db'
  on-primary-fixed: '#101c2b'
  on-primary-fixed-variant: '#3c4858'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4a9'
  on-secondary-fixed: '#410001'
  on-secondary-fixed-variant: '#930004'
  tertiary-fixed: '#e5e2dd'
  tertiary-fixed-dim: '#c9c6c2'
  on-tertiary-fixed: '#1c1c19'
  on-tertiary-fixed-variant: '#474743'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  headline-xl:
    fontFamily: Barlow Condensed
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Barlow Condensed
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Barlow Condensed
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Barlow Condensed
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Barlow Condensed
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 48px
  section-padding: 80px
---

## Brand & Style

The design system is engineered to project the reliability and grit of a high-end automotive garage. It targets car owners who value technical expertise and transparency over flashy marketing. The aesthetic is "Industrial Premium"—a blend of clean, modern layouts and raw, authoritative elements that evoke the feeling of a well-organized, high-tech workshop.

The visual language emphasizes:
- **Authority:** Bold, condensed typography that feels like stenciled machinery or vintage shop signage.
- **Credibility:** A grounded color palette that balances deep navy and warm neutrals to avoid the clinical feel of a dealership.
- **Utility:** High-contrast interfaces with clear pathways to conversion (Book Service, Get Quote).
- **Precision:** Zero-gradient surfaces, sharp edges, and a strict adherence to a structural grid.

## Colors

The palette is rooted in automotive tradition but elevated for a premium digital experience.

- **Deep Navy Slate (#1A2635):** The primary anchor. Used for navigation, footers, and primary text to establish trust and stability.
- **Engine Red (#D93025):** The high-visibility accent. Reserved strictly for calls to action, urgent alerts, and active states. It mimics the "Check Engine" light but in a way that suggests action and resolution.
- **Warm Neutral (#F4F1EC):** The background canvas. This off-white provides a "lived-in" quality, making the UI feel more approachable and less sterile than pure white.
- **Near Black (#2C2C2C):** Used for "Dark Cards" and heavy secondary sections. It evokes the texture of asphalt and cast iron.
- **Pure White (#FFFFFF):** Used for interior card surfaces and high-contrast text on dark backgrounds.

## Typography

This design system utilizes a high-contrast typographic pairing to balance "Shop Energy" with "Professional Service."

- **Headlines (Barlow Condensed):** A bold, industrial sans-serif. Use for all major titles. Despite the condensed nature, it must remain in **sentence case** for readability and a modern feel, except for small labels where uppercase is permitted for utility.
- **Body (Work Sans):** A grounded, highly legible sans-serif. The minimum size is locked at 16px to ensure accessibility for customers who may be viewing the site in low-light conditions or on-the-go.
- **Line Heights:** Generous line heights are used for body text (1.6) to provide a premium, editorial feel, while headlines remain tight (1.1) to maintain their impactful, blocky silhouette.

## Layout & Spacing

The layout follows a strict **12-column fixed grid** on desktop, transitioning to a single-column fluid flow on mobile.

- **Rhythm:** All spacing is derived from an 8px base unit. 
- **Sectioning:** Large vertical gaps (80px+) are used between sections to allow the content to breathe, emphasizing a premium feel. 
- **Margins:** Desktop views use wide 48px margins to frame the content, while mobile uses 16px to maximize screen real estate.
- **Alignment:** Content should predominantly be left-aligned to reinforce the "straightforward" and "direct" personality of the brand.

## Elevation & Depth

This design system avoids traditional soft shadows and "fluff." Instead, depth is created through **Tonal Layering** and **High-Contrast Outlines.**

- **Stacked Surfaces:** Use the Neutral #F4F1EC for the base background, and Near Black #2C2C2C or White #FFFFFF for cards. 
- **Shadows:** If used, shadows must be "Hard Shadows"—low blur (4px or less), high opacity (20%+)—reminiscent of architectural blueprints or heavy objects sitting on a floor.
- **Borders:** A 1px or 2px solid border in the Primary Navy (#1A2635) is the preferred method for defining elements like input fields or card containers.

## Shapes

The shape language is rigid and structural.
- **Small Radii:** All interactive elements (buttons, inputs, cards) use a consistent 0.25rem (4px) corner radius. This is just enough to feel modern without losing the "sharp" industrial edge.
- **No Pills:** Under no circumstances should buttons or tags be fully rounded (pill-shaped). 
- **Dividers:** Use thick, solid 2px dividers rather than thin faint lines to separate major content blocks, mimicking the structural beams of a shop.

## Components

### Buttons
- **Primary:** Background #D93025 (Red), Text #FFFFFF, 4px radius. High-impact, used for "Book Appointment."
- **Secondary:** Outline 2px #1A2635, Text #1A2635, 4px radius. 
- **States:** On hover, primary buttons should shift to a slightly darker shade of red (#B7281F) with a hard-offset shadow.

### Input Fields
- Solid 1px #1A2635 border on #FFFFFF background.
- Labels are always Barlow Condensed (Label-md) in sentence case, positioned above the field.
- Error states use a thick 2px #D93025 left-side border.

### Cards
- **Dark Variant:** Background #2C2C2C, Text #FFFFFF. Used for "Service Highlights."
- **Light Variant:** Background #FFFFFF, Border 1px #1A2635. Used for "Customer Reviews" or "Pricing Tables."

### Status Chips
- Rectangular with 2px radius. 
- Background colors should be muted (e.g., a desaturated version of the status color) with high-contrast text to maintain the industrial look.

### Appointment Bar
- A persistent, high-contrast bar (Primary Navy background) at the top or bottom of the mobile screen featuring a single "Schedule Now" button in Engine Red.