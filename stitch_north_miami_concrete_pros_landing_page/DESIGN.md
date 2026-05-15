---
name: Structural Craft
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#eae8e5'
  surface-container-highest: '#e4e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#444748'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ed'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#040505'
  on-primary: '#ffffff'
  primary-container: '#1e1e1e'
  on-primary-container: '#878585'
  inverse-primary: '#c8c6c5'
  secondary: '#9f4120'
  on-secondary: '#ffffff'
  secondary-container: '#fe8861'
  on-secondary-container: '#732102'
  tertiary: '#040405'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1e1e'
  on-tertiary-container: '#868686'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1b1b1c'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59e'
  on-secondary-fixed: '#3a0b00'
  on-secondary-fixed-variant: '#802a0a'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
typography:
  headline-xl:
    fontFamily: Barlow Condensed
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Barlow Condensed
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.1'
  headline-md:
    fontFamily: Barlow Condensed
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
---

## Brand & Style

This design system is built for a premier residential concrete contractor, prioritizing the "craftsman" narrative. The visual language is masculine, confident, and unapologetically direct, reflecting the permanence and strength of concrete. 

The design style is **Modern Industrial Minimalism**. It utilizes heavy whitespace to convey premium positioning, while drawing from **Brutalism** through the use of strong borders and impactful, condensed typography. The goal is to evoke a sense of structural integrity and professional reliability without corporate fluff. Digital surfaces should feel as intentional as a hand-poured slab.

## Colors

The palette is rooted in the raw materials of the trade. 

- **Structural Charcoal (#1E1E1E):** Used for primary navigation, high-contrast sections, and all primary headings on light backgrounds. It represents the strength of the finished product.
- **Terracotta (#C65D3A):** The sole accent color. Reserved strictly for calls to action, active states, and step-indicators in process sections.
- **Pale Sand (#F6F4F1):** The primary background for content-heavy sections to ensure readability and a "clean site" feel.
- **Concrete Gray (#7A7A7A):** Used for secondary text, borders, and UI iconography.
- **Off White (#F0EDE8):** Specifically utilized for body text sitting on Structural Charcoal backgrounds to reduce harsh optical vibration.

## Typography

The typography employs a "heavy-weight" hierarchy. 

**Headlines** utilize **Barlow Condensed Bold**. The condensed nature allows for massive, impactful type that mirrors the verticality of structural forms. Use uppercase for all primary and secondary headings to maintain a commanding presence.

**Body text** uses **Inter**. It provides a functional, neutral counterpoint to the aggressive headings, ensuring that technical specifications and project descriptions remain highly legible.

**Labels and Meta-data** use Inter Bold with increased letter spacing and uppercase styling to denote "Utility" information, similar to architectural blueprints.

## Layout & Spacing

The layout follows a **Rigid Grid** philosophy. We use a 12-column grid for desktop and a 4-column grid for mobile.

- **Vertical Rhythm:** Large vertical gaps (120px+) between sections create a sense of scale and premium quality.
- **Alignment:** Elements should feel "locked" into place. Use hard-edge alignment; avoid centering text for long-form content. Left-alignment is the default to maintain a structured, blueprint-like feel.
- **Mobile-First:** On mobile, padding is reduced to 16px to maximize the impact of high-resolution imagery of concrete textures and finished work.

## Elevation & Depth

This design system avoids traditional drop shadows to maintain its "Solid" persona. Depth is created through **Tonal Layering** and **Hard Borders**:

- **No Shadows:** We do not use soft ambient shadows. Surfaces are either flat or separated by 1px solid borders (#7A7A7A at 20% opacity).
- **Textural Depth:** Dark sections (#1E1E1E) should feature a subtle, low-opacity noise or grain overlay (Concrete Grain) to give the digital surface a tactile, physical quality.
- **High Contrast:** Depth is achieved by placing light Sand elements directly against dark Charcoal backgrounds, creating a clear foreground/background relationship without the need for blur or elevation.

## Shapes

The shape language is **Strictly Geometric**. 

To reflect the precision of masonry and formwork, all UI elements—including buttons, input fields, and image containers—use a **0px border radius (Sharp)**. The only exception is for circular icons where functionality dictates. This "sharp" aesthetic reinforces the themes of precision, accuracy, and strength.

## Components

### Buttons
- **Primary:** Structural Charcoal background with Off White text. Sharp corners. 1px border of Charcoal to maintain shape on Sand backgrounds.
- **CTA (Action):** Terracotta background with Off White text. Reserved for "Request a Quote" or "Call Now."
- **Hover State:** Terracotta buttons shift to a slightly darker shade; Charcoal buttons shift to Terracotta.

### Cards
- Cards utilize a 1px border (#7A7A7A) with no fill on light backgrounds. On dark backgrounds, use a slightly lighter charcoal fill (#2A2A2A) to differentiate from the base.

### Input Fields
- Underline-only or 1px bordered boxes. No rounded corners. Labels should use the `label-bold` typographic style above the field.

### Process Steps
- Use Terracotta for step numbers (e.g., 01, 02, 03) in a large Barlow Condensed Bold font to guide the user through the "Craftsman's Process."

### Image Treatments
- All project photography should be framed in sharp-edged containers. Use a subtle grayscale filter on hover to reveal full-color imagery, emphasizing the "raw to finished" transformation.