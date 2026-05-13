---
name: Pro-Grade Reliability
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
  on-surface-variant: '#434751'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#737782'
  outline-variant: '#c3c6d3'
  surface-tint: '#2d5da7'
  primary: '#08468f'
  on-primary: '#ffffff'
  primary-container: '#2e5ea8'
  on-primary-container: '#c9daff'
  inverse-primary: '#abc7ff'
  secondary: '#515e7e'
  on-secondary: '#ffffff'
  secondary-container: '#cdd9ff'
  on-secondary-container: '#525f7f'
  tertiary: '#8f140c'
  on-tertiary: '#ffffff'
  tertiary-container: '#b12e22'
  on-tertiary-container: '#ffcec7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#abc7ff'
  on-primary-fixed: '#001b3f'
  on-primary-fixed-variant: '#06458e'
  secondary-fixed: '#d9e2ff'
  secondary-fixed-dim: '#b9c6eb'
  on-secondary-fixed: '#0d1b37'
  on-secondary-fixed-variant: '#3a4665'
  tertiary-fixed: '#ffdad5'
  tertiary-fixed-dim: '#ffb4a9'
  on-tertiary-fixed: '#410000'
  on-tertiary-fixed-variant: '#8e130c'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  button-text:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-padding-desktop: 80px
  section-padding-mobile: 48px
  grid-gutter: 24px
  container-max-width: 1200px
---

## Brand & Style

This design system establishes a visual language of absolute authority and local expertise. The brand personality is straight-talking, dependable, and physically grounded, reflecting the blue-collar precision of high-end plumbing and HVAC work. 

The aesthetic is **High-Contrast / Bold** mixed with **Corporate / Modern** sensibilities. It avoids all decorative fluff like gradients or soft blurs in favor of structural integrity and clear hierarchy. Visuals should feel "heavy" and "bolted down," using substantial blocks of color and thick-weighted typography to evoke the feeling of industrial reliability and institutional trust.

## Colors

The palette is anchored by a sophisticated Deep Navy (#1A2744) which serves as the primary "Authority" color, used for headers, footers, and hero sections to establish immediate trust. Steel Blue (#2E5EA8) is the functional "Action" color, reserved for primary interactions and navigational cues.

Emergency Red (#C0392B) is used sparingly but with high intensity for 24/7 service alerts, critical warnings, and urgent contact triggers. The background strategy utilizes an Off-White (#F7F8FA) for the main content areas to maintain high legibility and a clean, professional finish, contrasted against a dark Neutral (#2A2A2A) for body text to ensure maximum WCAG accessibility.

## Typography

The typography system prioritizes impact and clarity. **Montserrat** is utilized for all headlines and display text; its geometric construction conveys a modern, urban strength. Heavy weights (700-800) are the default for headings to emphasize the "straight-talking" nature of the brand.

**Inter** is the workhorse for body copy and UI labels. It provides a neutral, utilitarian balance to the bold headings, ensuring that technical information and service descriptions are highly readable. Large headlines should use tighter letter spacing to feel more cohesive, while small labels use increased letter spacing and uppercase styling to provide a "blueprint" or "industrial label" aesthetic.

## Layout & Spacing

This design system uses a **fixed grid** layout for desktop (12 columns) and a fluid 4-column grid for mobile. The layout philosophy is centered on "contained power"—information is organized into clearly defined sections with generous vertical padding to allow the bold typography room to breathe.

A strict 8px spacing scale governs all internal component margins. On desktop, content is centered within a 1200px container to maintain an authoritative, organized appearance. Gutters are kept at a standard 24px to ensure a dense, sturdy feel without appearing cluttered. Section transitions should use sharp horizontal dividers in #D5D5D5 or direct color-block shifts between Off-White and Deep Navy.

## Elevation & Depth

To maintain the "straight-talking" and "no-nonsense" brand promise, elevation is communicated through **Tonal Layers** and **Low-contrast outlines** rather than soft shadows. 

Depth is achieved by stacking elements on the Off-White content background using subtle 1px borders (#D5D5D5). When a surface needs to stand out (like a service card), use a slight background color shift to pure White (#FFFFFF) rather than a shadow. If shadows must be used for critical floating elements (like a mobile "Call Now" button), they should be crisp, low-blur, and high-opacity to maintain the industrial, tactile feel of the system.

## Shapes

The shape language is **Soft (0.25rem)**. While a completely sharp (0px) corner can feel overly aggressive, the 4px radius provides just enough professional polish while maintaining a "square" and reliable silhouette. 

This subtle rounding should be applied consistently to buttons, input fields, and card containers. Avoid large radii or pill-shaped buttons as they detract from the authoritative, industrial tone. Icons should follow this logic, utilizing thick strokes and minimal rounding on terminal points.

## Components

- **Buttons**: The Primary button uses Steel Blue (#2E5EA8) with White text, featuring a bold weight and uppercase Montserrat. The Emergency button is the exception, utilizing Red (#C0392B) with a slight "pulse" or high-contrast border to draw immediate attention.
- **Inputs**: Field backgrounds should be pure white with a 1px border (#D5D5D5). Focused states utilize the Steel Blue for the border with a 2px thickness. Labels sit strictly above the field in bold Inter.
- **Service Cards**: Use a white background on the off-white page. They feature a top-border accent in Steel Blue to denote professional categories.
- **Emergency Banner**: A persistent, full-width Deep Navy bar at the top of the viewport, featuring the Emergency Red for the contact number and "Call Now" trigger.
- **Trust Badges**: Monochromatic (Deep Navy) versions of certification logos or "Since 2004" seals to maintain a clean, high-end appearance.
- **Lists**: Bullet points should be replaced with custom "check" icons in Steel Blue to reinforce the concept of "job done right."