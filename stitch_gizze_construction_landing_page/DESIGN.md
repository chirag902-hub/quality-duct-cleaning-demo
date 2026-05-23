---
name: Industrial Integrity
colors:
  surface: '#fef9f1'
  surface-dim: '#ded9d3'
  surface-bright: '#fef9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3ec'
  surface-container: '#f2ede6'
  surface-container-high: '#ece7e1'
  surface-container-highest: '#e7e2db'
  on-surface: '#1d1b17'
  on-surface-variant: '#444748'
  inverse-surface: '#32302c'
  inverse-on-surface: '#f5f0e9'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#040505'
  on-primary: '#ffffff'
  primary-container: '#1e1e1e'
  on-primary-container: '#878585'
  inverse-primary: '#c8c6c5'
  secondary: '#516169'
  on-secondary: '#ffffff'
  secondary-container: '#d2e2ec'
  on-secondary-container: '#55656e'
  tertiary: '#120100'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f0c00'
  on-tertiary-container: '#ee4f18'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1b1b1c'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#d5e5ef'
  secondary-fixed-dim: '#b9c9d3'
  on-secondary-fixed: '#0e1d25'
  on-secondary-fixed-variant: '#3a4951'
  tertiary-fixed: '#ffdbd1'
  tertiary-fixed-dim: '#ffb59f'
  on-tertiary-fixed: '#3a0a00'
  on-tertiary-fixed-variant: '#852300'
  background: '#fef9f1'
  on-background: '#1d1b17'
  surface-variant: '#e7e2db'
  gunmetal: '#1E1E1E'
  steel-gray: '#2B3A42'
  safety-orange: '#E84B13'
  concrete: '#F2EDE6'
  pure-white: '#FFFFFF'
  caution-yellow: '#F9C80E'
typography:
  display-lg:
    fontFamily: Archivo Narrow
    fontSize: 84px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Archivo Narrow
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Archivo Narrow
    fontSize: 60px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Archivo Narrow
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Archivo Narrow
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Archivo Narrow
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system is forged for **Gizze Construction Inc.**, embodying the raw power and multi-generational reliability of heavy industry. The brand personality is unapologetic, honest, and high-impact—built on a foundation of "no fluff" credibility. 

The aesthetic draws from **Industrial Brutalism**, utilizing a high-contrast palette, heavy-weight typography, and hard-edged geometry. It mimics the physical world of construction: the weight of steel beams, the texture of poured concrete, and the high-visibility urgency of safety equipment. The UI avoids all decorative softness (gradients, blurs, or rounded corners) in favor of a structural, grid-locked layout that conveys stability and precision.

## Colors

The palette is rooted in the materials of the job site. **Gunmetal (#1E1E1E)** serves as the primary structural color, used for backgrounds, heavy type, and grounding elements. **Steel Gray (#2B3A42)** provides a professional, cool-toned secondary layer for interactive states and metadata.

**Safety Orange (#E84B13)** is the exclusive call-to-action color, designed to pop against dark backgrounds like a safety vest in a work zone. The primary surface color is **Concrete (#F2EDE6)**, a warm neutral that provides better readability and a more premium, "fourth-generation" feel than sterile white. Use **Pure White (#FFFFFF)** only for high-contrast text on dark backgrounds or specific content cards to create depth.

## Typography

Typography is used as a structural element. Headlines utilize **Archivo Narrow** set to Bold or Heavy weights with tight letter-spacing to create a "wall of text" effect that feels massive and immovable. All primary headlines must be set in **uppercase** to reinforce the confident, "no fluff" brand voice.

**Public Sans** is the workhorse for body copy. It provides an institutional, trustworthy feel that is highly legible for technical specifications and project descriptions. For desktop, the default body size is 18px to ensure presence and accessibility. Labels and utility text return to **Archivo Narrow** in uppercase with slightly increased letter-spacing to ensure clarity at small scales.

## Layout & Spacing

The layout follows a **Fixed-Fluid Hybrid** model. Content is housed within a strict 12-column grid with a maximum width of 1280px for desktop to maintain optimal line lengths. Large section gaps (120px+) are used to create "breathing room" between heavy blocks of content, preventing the UI from feeling cluttered despite its "heavy" style.

Spacing is strictly linear and based on an **8px base unit**. Gutters are generous (24px) to emphasize the separation of structural components. On mobile, margins tighten to 20px, and the grid collapses to a single column, but the heavy vertical rhythm is maintained to preserve the brand's "weight."

## Elevation & Depth

This design system rejects traditional shadows and soft blurs. Depth is achieved through **Tonal Layering** and **High-Contrast Outlines**.

1.  **Structural Stacking:** Elements do not "float"; they are "built." Backgrounds use **Concrete**, while foreground cards use **Pure White** with a sharp 2px **Gunmetal** border.
2.  **Hard Shadows:** If depth is absolutely required for interaction (e.g., a pressed button), use a 100% opaque, non-blurred offset shadow (4px x 4px) in **Gunmetal**.
3.  **Z-Index Logic:** Components at higher elevations are indicated by thicker borders or high-visibility **Safety Orange** accents rather than light-based shadows.

## Shapes

The shape language is strictly **Sharp (0px radius)**. Every element—buttons, input fields, cards, and image containers—must have hard 90-degree angles. This reinforces the "construction-grade" metaphor, echoing the cut of steel and the edge of a brick. Avoid any circular elements, including profile avatars (use squares) or icons (choose angular, geometric sets).

## Components

### Buttons
Primary buttons are styled like "Safety Vests": a solid **Safety Orange** fill with **Gunmetal** uppercase text. They feature a 2px Gunmetal border. Hover states should invert the colors or apply a hard 4px offset shadow.

### Input Fields
Inputs use a **Pure White** background with a 2px **Gunmetal** border. Labels sit strictly above the field in **label-bold** typography. Focus states change the border color to **Safety Orange** or increase the border thickness to 3px.

### Cards
Cards are the primary container for project highlights. They feature a 2px **Gunmetal** border with no shadow. Headlines inside cards should be flushed to the top-left to emphasize the grid.

### Chips & Tags
Used for project status (e.g., "COMPLETED," "IN PROGRESS"). Use **Gunmetal** backgrounds with **Pure White** text or **Steel Gray** for secondary tags. They are always rectangular with zero corner radius.

### List Items
Lists are separated by 2px **Gunmetal** horizontal rules. Bullet points are replaced with small, solid **Safety Orange** squares to maintain the geometric theme.

### Additional Components
- **The "Steel Beam" Divider:** A heavy 8px-16px horizontal rule used to separate major page sections, typically in **Gunmetal**.
- **The "Blueprint" Grid:** An optional subtle background pattern of 8px squares in a light-opacity **Steel Gray** used for hero sections.