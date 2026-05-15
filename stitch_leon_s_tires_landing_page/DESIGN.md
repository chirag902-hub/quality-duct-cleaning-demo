---
name: Rugged Industrial
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#59413f'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#8d706e'
  outline-variant: '#e1bfbc'
  surface-tint: '#b02c2d'
  primary: '#96181d'
  on-primary: '#ffffff'
  primary-container: '#b83232'
  on-primary-container: '#ffd9d5'
  inverse-primary: '#ffb3ad'
  secondary: '#2b6197'
  on-secondary: '#ffffff'
  secondary-container: '#90c2fe'
  on-secondary-container: '#104f84'
  tertiary: '#484c52'
  on-tertiary: '#ffffff'
  tertiary-container: '#60646a'
  on-tertiary-container: '#dee1e8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3ad'
  on-primary-fixed: '#410004'
  on-primary-fixed-variant: '#8e1119'
  secondary-fixed: '#d2e4ff'
  secondary-fixed-dim: '#9fcaff'
  on-secondary-fixed: '#001c37'
  on-secondary-fixed-variant: '#02497e'
  tertiary-fixed: '#e0e2e9'
  tertiary-fixed-dim: '#c3c6cd'
  on-tertiary-fixed: '#181c21'
  on-tertiary-fixed-variant: '#43474d'
  background: '#faf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e3e2df'
typography:
  display:
    fontFamily: Barlow Condensed
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.0'
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
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
    fontSize: 20px
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
  stats-num:
    fontFamily: Barlow Condensed
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.0'
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  max-width: 1280px
---

## Brand & Style

This design system is built for the "neighborhood shop"—a grounded, mechanical, and highly functional aesthetic that prioritizes utility over corporate polish. It captures the atmosphere of a working garage: the smell of rubber, the texture of concrete, and the precision of steel tools.

The visual style leans into **Brutalism** and **Modern Industrialism**. It utilizes raw textures, heavy borders, and sharp geometric shapes to evoke strength and reliability. The interface should feel like a piece of high-quality workshop equipment: durable, straightforward, and no-nonsense. Whitespace is used not for "luxury," but for "clarity," ensuring the user can find the services they need quickly while they are on the go.

## Colors

The palette is derived from the workshop environment. 
- **Burnt Iron Red (#B83232):** Used exclusively for primary calls to action (CTAs), urgent alerts, and price highlights. It demands attention against the industrial background.
- **Deep Slate Black (#1A1E23):** Used for the "Hero" section, headers, and footer backgrounds. It provides a heavy, grounded foundation.
- **Steel Blue (#3A6EA5):** Acts as a trust indicator. Use this for badges, verified reviews, and secondary links.
- **Off-white Concrete (#F3F2EF):** The default background for main content sections. It feels cleaner than pure white while maintaining the industrial vibe.
- **Warm White (#F0EDE8):** Specifically for typography sitting on dark backgrounds to reduce eye strain and improve legibility.

## Typography

The typography strategy uses a high-contrast pairing to differentiate between "Instruction" and "Action."

**Barlow Condensed** is used for all headlines and display text. Its tall, narrow profile mimics industrial signage and technical manuals. All headlines should be set in Uppercase to project authority and strength.

**Inter** provides a clean, neutral balance for body text. It ensures that technical details, tire specs, and service descriptions are easily readable on any device. 

Scale is aggressive. Don't be afraid to let a headline dominate a section to create a clear visual hierarchy.

## Layout & Spacing

The design system utilizes a **Fixed Grid** model for desktop to maintain a structured, "blueprint" feel, while transitioning to a fluid model for mobile.

- **Grid:** A 12-column grid for desktop with wide 24px gutters. Content should feel like it is "locked" into place.
- **Rhythm:** An 8px base unit drives all padding and margins. 
- **Section Breaks:** Use heavy 4px or 8px Slate Black borders as horizontal dividers between major site sections instead of subtle gray lines.
- **Reflow:** On mobile, margins shrink to 16px. Cards and tire listings stack vertically, but maintain their rigid, squared-off proportions.

## Elevation & Depth

This system avoids soft ambient shadows. Instead, it uses **Bold Borders** and **Tonal Layers** to create hierarchy.

1.  **Primary Depth:** Created by stacking blocks of color. For example, a Red CTA button might have a 4px offset "hard shadow" in Slate Black to make it look like a physical switch.
2.  **Outlines:** Use 2px solid Slate Black borders for cards and input fields. This mimics the structural framing found in workshop racking.
3.  **Active States:** When an element is pressed, it should appear to "flush" into the surface—remove the hard shadow and move the element 2px down/right.

## Shapes

The shape language is strictly **Sharp (0)**. 

To maintain the rugged, mechanical feel, avoid all corner radii. Every button, input, card, and image container must have 90-degree corners. This reinforces the "steel and concrete" metaphor and distinguishes the shop from "soft" corporate tire retailers. 

The only exception is the tire itself in photography; the UI around it must remain rigid to provide a frame.

## Components

### Buttons
- **Primary:** Burnt Iron Red background, Warm White text, heavy 700 weight, all caps. No rounded corners. 4px hard black shadow.
- **Secondary:** Transparent background, 2px Slate Black border, Slate Black text.

### Input Fields
- Heavy 2px Slate Black border.
- Off-white Concrete background.
- Labels sit above the field in **Inter Bold**, Uppercase.

### Cards (Tire Listings)
- 2px Slate Black border.
- No shadow.
- Use Steel Blue for "In Stock" or "Best Seller" badges—badges should be rectangular with sharp corners.

### Lists & Specs
- Use a "Technical Spec" style: Label on the left in Steel Blue, Value on the right in Bold Slate Black.
- Separate items with a 1px solid Slate Black divider.

### Shop Indicators
- **Open/Closed Status:** Use a high-contrast block. A Red block for "Closed," a Steel Blue block for "Open." These should look like physical signage hanging in the window.