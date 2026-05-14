---
name: Elite Authority Service
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
  on-surface-variant: '#414844'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#a14000'
  on-secondary: '#ffffff'
  secondary-container: '#ff8342'
  on-secondary-container: '#682700'
  tertiary: '#282621'
  on-tertiary: '#ffffff'
  tertiary-container: '#3e3c37'
  on-tertiary-container: '#aaa69f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#ffdbcc'
  secondary-fixed-dim: '#ffb694'
  on-secondary-fixed: '#351000'
  on-secondary-fixed-variant: '#7a2f00'
  tertiary-fixed: '#e7e2da'
  tertiary-fixed-dim: '#cac6be'
  on-tertiary-fixed: '#1d1c17'
  on-tertiary-fixed-variant: '#494741'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Montserrat
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
    lineHeight: '1.2'
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
  container-max: 1200px
---

## Brand & Style

The design system is engineered for **Termicure Pest Control**, targeting homeowners who value immediate results, local expertise, and absolute accountability. The personality is "The Elite Guardian"—professional, uncompromising on quality, yet accessible and neighborly.

The aesthetic follows a **High-Contrast / Modern** movement tailored for the blue-collar sector. It utilizes heavy-weight typography to project strength and authority, paired with a clean, grid-based layout that prioritizes information density and conversion triggers. Every visual element—from shield icons to high-impact call-to-actions—is designed to reduce friction and build instant psychological trust in a high-stakes home service environment.

## Colors

The palette is built on a foundation of "Trust and Action."

*   **Primary (Forest Green):** Used for headers, trust badges, and primary branding to evoke stability, growth, and safety.
*   **Secondary (Burnt Orange):** Reserved exclusively for conversion-critical elements (CTAs, phone numbers, lead forms). It provides an aggressive contrast against the green to guide the eye toward action.
*   **Neutral (Charcoal):** Used for body text and deep backgrounds to ensure maximum readability and a grounded feel.
*   **Surface (Warm Off-White):** Used for section backgrounds to break up the "starkness" of pure white, providing a premium, editorial feel that differentiates the brand from low-cost competitors.

## Typography

This design system uses a dual-sans-serif approach to balance impact with utility. 

**Montserrat** is used for all headlines. It is set with tight letter-spacing and heavy weights (700-800) to project an aggressive, "local authority" voice. All-caps should be used sparingly for labels and small eyebrows to maintain the accountability-forward feel.

**Inter** is used for body copy and UI elements. Its high x-height and neutral character ensure that technical details and contract terms are crystal clear and easy to scan.

## Layout & Spacing

The layout utilizes a **Fixed Grid** model (12 columns) to create a structured, professional appearance. 

*   **Vertical Rhythm:** Generous whitespace (120px) between major sections is mandatory to prevent the "cluttered" look common in low-tier pest control sites. This breathing room signals premium service.
*   **Direct Response Hierarchy:** Content follows a strict Z-pattern or F-pattern. Key selling points are housed in 3-column grids (on desktop) or stacked vertically (on mobile).
*   **Sticky Conversion:** A persistent header or bottom-mobile bar must contain the primary Burnt Orange CTA and "Call Now" link at all times.

## Elevation & Depth

This design system avoids excessive depth to maintain a "grounded" and "reliable" feel. 

*   **Low-Contrast Outlines:** Use 1px borders in Forest Green (at 10-20% opacity) for cards and containers rather than heavy shadows.
*   **Flat Layering:** Depth is primarily communicated through color blocking (switching between White and Warm Off-White backgrounds).
*   **Strategic Shadows:** Reserve subtle, tight shadows (0px 4px 12px rgba(0,0,0,0.08)) only for the primary conversion form and sticky navigation to pull them slightly forward from the content.

## Shapes

The shape language is **Soft (0.25rem)**. 

While the brand is aggressive, sharp 90-degree corners can feel "hostile" or "unrefined." A subtle radius provides a modern, professional polish. 

*   **Buttons:** Standard buttons use a 0.25rem radius. 
*   **Feature Cards:** Use 0.5rem (rounded-lg) for larger containers to create a distinct frame for testimonials and service descriptions.
*   **Shield Elements:** Icons and trust badges should incorporate shield-like geometries to reinforce the "protection" and "accountability" narrative.

## Components

*   **Primary CTA Buttons:** Burnt Orange (#C85A1A) background with White text. Bold Montserrat, uppercase. Use a subtle hover state that darkens the orange slightly. No gradients.
*   **Secondary Buttons:** Forest Green (#1B4332) outline with Forest Green text. Used for "Learn More" or less critical actions.
*   **Input Fields:** Large, 56px height for accessibility. Solid 1px border (#1A1A1A at 20% opacity). Labels are always visible above the field in Label-Bold typography.
*   **Trust Badges:** 48px - 64px tall, monochromatic (Forest Green). Grouped in a horizontal row below the primary Hero CTA.
*   **Service Cards:** White background, 1px border, 0.5rem corner radius. Includes a high-quality "Texas-suburb" lifestyle image at the top, followed by a bold headline and a short bulleted list.
*   **Guarantees / Shields:** A dedicated "Accountability Block" using the Forest Green background with White/Burnt Orange text to highlight the 100% satisfaction guarantee.