---
name: Industrial Clarity
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1b1b'
  on-surface-variant: '#42474e'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#72777f'
  outline-variant: '#c2c7cf'
  surface-tint: '#386188'
  primary: '#002743'
  on-primary: '#ffffff'
  primary-container: '#0a3d62'
  on-primary-container: '#80a8d3'
  inverse-primary: '#a2caf7'
  secondary: '#006877'
  on-secondary: '#ffffff'
  secondary-container: '#5fe6ff'
  on-secondary-container: '#006573'
  tertiary: '#27251f'
  on-tertiary: '#ffffff'
  tertiary-container: '#3d3a34'
  on-tertiary-container: '#a8a49c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#a2caf7'
  on-primary-fixed: '#001d34'
  on-primary-fixed-variant: '#1d496f'
  secondary-fixed: '#a2eeff'
  secondary-fixed-dim: '#4dd7f0'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#004e5a'
  tertiary-fixed: '#e7e2d9'
  tertiary-fixed-dim: '#cbc6bd'
  on-tertiary-fixed: '#1d1b16'
  on-tertiary-fixed-variant: '#494640'
  background: '#fcf9f8'
  on-background: '#1b1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
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
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
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
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is built on the intersection of mechanical reliability and tropical luxury. It evokes the "South Florida Pro" persona: intense, efficient, and impeccably clean. The aesthetic is a mix of **Minimalism** and **High-Contrast Bold**, stripping away unnecessary decorative elements to focus on utility and expertise.

The UI should feel like a high-end tool—sturdy, precise, and high-performance. Avoid any visual "fluff." Use whitespace not just for breathing room, but to simulate the stark, bright clarity of midday sun on concrete. Imagery must be razor-sharp, focusing on the chemistry of water and the precision of pool hardware.

**Emotional Response:**
- Reliability through high-contrast legibility.
- Confidence through bold, unapologetic layouts.
- Freshness through a bright, sun-bleached color palette.

## Colors

The palette is driven by functional contrast. **Deep Ocean Blue** serves as the foundation for authority and depth. **Bright Aqua Accent** is reserved exclusively for action and critical focus points, ensuring high visibility even in bright outdoor viewing conditions. 

**Warm Sand** acts as the primary background or "canvas" color to reduce the harshness of pure white while maintaining a "sun-bleached" Mediterranean feel. **Charcoal** is used for primary text to ensure maximum readability without the vibrating contrast of pure black.

No gradients are permitted. All colors must be applied as solid, hard-edged blocks to maintain the "no-nonsense" industrial vibe.

## Typography

This design system utilizes **Inter** exclusively to convey a systematic, modern, and trustworthy tone. 

**Headlines:** Use heavy weights (700-800) for all headings. Headlines should be punchy and direct. Avoid long sentences. Tighten letter spacing on larger sizes to create a "locked-in" technical appearance.
**Body:** Use regular weight (400) for all descriptive text. Maintain generous line heights (1.5+) to ensure readability in high-glare environments.
**Labels:** Use bold, uppercase labels for categories and small UI hints to mimic industrial labeling and equipment tags.

**Constraint:** Never use em dashes or decorative alternates. Keep all punctuation and formatting standard and utilitarian.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain a contained, professional appearance, transitioning to a **Fluid Grid** for mobile.

- **Desktop:** 12-column grid, 1200px max-width, 24px gutters.
- **Mobile:** 4-column grid, fluid width, 16px margins.

Spacing is based on an 8px rhythmic scale. Use larger vertical increments (lg/xl) between sections to simulate the vastness of a clean pool surface. Elements should be aligned to a strict vertical axis to reinforce the "one-man precision" brand narrative.

## Elevation & Depth

This design system rejects traditional shadows in favor of **Low-contrast outlines** and **Tonal layers**. Depth is created through the stacking of solid colors rather than blurs.

- **Surface Tiers:** Use White (#FFFFFF) for the highest priority foreground elements (cards, modals) against the Warm Sand (#F5EFE6) background.
- **Borders:** Use 1px solid borders in Charcoal (#1C1C1C) at 10% opacity for subtle definition, or 2px solid Deep Ocean Blue (#0A3D62) for high-emphasis containers.
- **Interactions:** Elements do not "lift" on hover; instead, they change fill color or stroke weight to indicate state changes, maintaining a flat, architectural feel.

## Shapes

The shape language is **Soft (0.25rem)**. This provides just enough curvature to feel approachable and modern without losing the "tool-kit" structural integrity. 

- **Buttons & Inputs:** Use the standard 4px (0.25rem) radius.
- **Cards:** Use 8px (0.5rem) for larger containers to create a distinct visual hierarchy between small components and large layout blocks.
- **Icons:** Use thick, 2px stroke icons with slightly rounded caps to match the typography weight.

## Components

**Buttons:**
- **Primary:** Bright Aqua (#00B4CC) background with White (#FFFFFF) bold text. High contrast is mandatory. 
- **Secondary:** Transparent background with 2px Deep Ocean Blue (#0A3D62) border and text.
- **State:** On hover, primary buttons should shift to a slightly darker aqua; no shadows.

**Input Fields:**
- Solid White (#FFFFFF) fill with a 1px Charcoal (#1C1C1C) border at 20% opacity. 
- Labels must be positioned above the field in `label-bold` style.

**Cards:**
- No shadows. Use 1px solid borders or a subtle fill change (Warm Sand vs White).
- Images within cards must be full-bleed at the top to emphasize the "crystal-clear" visual requirement.

**Service Chips:**
- Use Deep Ocean Blue (#0A3D62) with White text for status indicators (e.g., "Chemicals Balanced").

**Lists:**
- Use Aqua-colored checkmarks for service lists. Avoid bullet points. Every list item should feel like a completed task in a professional logbook.