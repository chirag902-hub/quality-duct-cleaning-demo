---
name: Luke Heating Cooling & Plumbing Design System
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#43474e'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#73777f'
  outline-variant: '#c3c6cf'
  surface-tint: '#436084'
  primary: '#002444'
  on-primary: '#ffffff'
  primary-container: '#1b3a5c'
  on-primary-container: '#87a4cc'
  inverse-primary: '#abc9f2'
  secondary: '#b02d21'
  on-secondary: '#ffffff'
  secondary-container: '#fc6451'
  on-secondary-container: '#650001'
  tertiary: '#331f00'
  on-tertiary: '#ffffff'
  tertiary-container: '#4f3300'
  on-tertiary-container: '#c49b5f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#abc9f2'
  on-primary-fixed: '#001c38'
  on-primary-fixed-variant: '#2b486b'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4a9'
  on-secondary-fixed: '#410000'
  on-secondary-fixed-variant: '#8e130c'
  tertiary-fixed: '#ffddb1'
  tertiary-fixed-dim: '#ecbf80'
  on-tertiary-fixed: '#291800'
  on-tertiary-fixed-variant: '#5f410c'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.4'
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
  base: 8px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
  gutter: 24px
  container-max-width: 1200px
---

## Brand & Style

The design system is engineered for high-conversion PPC performance, balancing the rugged reliability of skilled trades with the approachable warmth of a local family business. The aesthetic is **Corporate / Modern** with a slight industrial edge—prioritizing trust, urgency, and technical competence.

The visual language avoids "fluff" or decorative trends like gradients and glassmorphism. Instead, it relies on high-contrast color blocking, massive typography, and razor-sharp execution to communicate authority. The interface should feel like a well-organized toolbox: functional, durable, and ready for immediate use.

**Key Visual Principles:**
- **Authority through Scale:** Use oversized headlines to communicate service offerings instantly.
- **Precision:** Perfect alignment and consistent borders to reflect mechanical expertise.
- **Local Trust:** Use authentic photography of the Sioux Falls landscape and actual team members to differentiate from national franchises.

## Colors

The palette is rooted in the "Steel and Forge" concept. **Deep Steel Blue** acts as the foundation, evoking professional reliability and the cooling side of the business. **Forge Red** is reserved strictly for conversion-critical elements (CTAs, phone numbers, and emergency alerts), creating an aggressive visual "pop" against the calmer blue and white surfaces.

**Usage Rules:**
- **Primary (#1B3A5C):** Used for navigation backgrounds, footers, and primary headings.
- **Secondary (#C0392B):** Limited to "Book Now" buttons, "24/7 Emergency" tags, and iconography accents.
- **Neutral/Background (#F4F5F6 & #FFFFFF):** The light gray background provides a clean canvas, while pure white is used for service cards to create subtle depth.
- **Text (#1A1A1A):** Used for all body copy to ensure maximum AAA-grade accessibility and readability.

## Typography

This design system utilizes **Inter** exclusively to maintain a modern, systematic, and highly legible appearance. The hierarchy is intentionally aggressive, using "Extra Bold" and "Black" weights for headlines to grab attention immediately in a PPC environment.

**Implementation Details:**
- **Urgency:** Use `display-hero` for the main value proposition (e.g., "AC Out? We're on our way.").
- **Readability:** Body copy utilizes a generous 1.6 line-height to ensure that even dense service descriptions remain approachable.
- **Utility:** Small labels and tags should use `label-bold` with slight letter spacing to ensure clarity when used on buttons or status indicators.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop to maintain a premium, editorial feel, transitioning to a fluid model for mobile devices.

**Grid System:**
- **Desktop:** 12-column grid with 24px gutters. Content is centered within a 1200px container.
- **Mobile:** Single column with 20px side margins. 
- **Rhythm:** All spacing (margins, padding) must be multiples of 8px. Use large vertical gaps (120px+) between major sections to let the high-impact typography breathe.

**PPC Optimization:**
Place the primary Lead Form above the fold on desktop (right-aligned) and immediately following the hero headline on mobile.

## Elevation & Depth

This design system avoids heavy, "mushy" shadows in favor of **Low-contrast outlines** and **Tonal layering**. Depth is used to distinguish interactive elements from the background without compromising the flat, professional aesthetic.

**Depth Indicators:**
- **Cards:** Use a 1px solid border (#DDE1E6) instead of a shadow.
- **Active State:** Only the primary CTA buttons receive a subtle, crisp shadow (4px blur, 10% opacity black) to suggest "pressability."
- **Layering:** Lead forms should be placed on a pure white surface (#FFFFFF) to stand out against the light gray (#F4F5F6) background, creating a natural focal point for the user.

## Shapes

The shape language is **Soft (0.25rem)**. This provides a subtle nod to modern UI standards while maintaining the masculine, structured feel required for a service brand.

- **Buttons & Inputs:** Use the standard 4px radius.
- **Service Cards:** Use `rounded-lg` (8px) to distinguish them as larger content containers.
- **Strictness:** Do not use pills or circles for any primary UI elements; reserve 100% rounding only for small notification badges or numerical step indicators.

## Components

### Buttons
- **Primary CTA:** Forge Red (#C0392B) with White text. Bold weight. Use for the main "Schedule Now" or "Call Now" actions.
- **Secondary:** Deep Steel Blue (#1B3A5C) with White text. Use for less urgent service browsing.

### Lead Capture Form
- **Input Fields:** Large 56px height for touch-friendliness on mobile. 1px stroke (#DDE1E6), turning Steel Blue on focus.
- **Labels:** Floating labels or high-contrast top-aligned labels using `label-bold`.

### Service Cards
- White background, 1px border. 
- Large, simple icons in Deep Steel Blue.
- Short, punchy headlines followed by 2-3 bullet points of value.

### Trust Bar (Unique Component)
- A horizontal strip below the hero section featuring: 
  - Google Review Rating (Star icons in Forge Red).
  - "Family Owned & Operated" badge.
  - "Licensed & Insured" checkmark.

### Lists
- Use custom checkmark icons in Forge Red for "What's Included" or "Our Guarantees" to reinforce the brand color in the body of the page.