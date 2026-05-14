---
name: Tarrant Professional Pest
colors:
  surface: '#14130f'
  surface-dim: '#14130f'
  surface-bright: '#3b3934'
  surface-container-lowest: '#0f0e0a'
  surface-container-low: '#1d1c17'
  surface-container: '#21201b'
  surface-container-high: '#2b2a25'
  surface-container-highest: '#36352f'
  on-surface: '#e7e2da'
  on-surface-variant: '#c4c6cc'
  inverse-surface: '#e7e2da'
  inverse-on-surface: '#32302b'
  outline: '#8e9196'
  outline-variant: '#44474c'
  surface-tint: '#bac8dc'
  primary: '#bac8dc'
  on-primary: '#243141'
  primary-container: '#0d1b2a'
  on-primary-container: '#768497'
  inverse-primary: '#525f71'
  secondary: '#ffb691'
  on-secondary: '#552100'
  secondary-container: '#a64600'
  on-secondary-container: '#ffd8c6'
  tertiary: '#bcc7dd'
  on-tertiary: '#263142'
  tertiary-container: '#0f1a2b'
  on-tertiary-container: '#788398'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d6e4f9'
  primary-fixed-dim: '#bac8dc'
  on-primary-fixed: '#0f1c2c'
  on-primary-fixed-variant: '#3a4859'
  secondary-fixed: '#ffdbcb'
  secondary-fixed-dim: '#ffb691'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#783100'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#14130f'
  on-background: '#e7e2da'
  surface-variant: '#36352f'
typography:
  display-lg:
    fontFamily: Chivo
    fontSize: 72px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Chivo
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Chivo
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Chivo
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Public Sans
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
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
  margin-desktop: 80px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style
This design system is built for an authoritative, "blue-collar premium" aesthetic. It targets homeowners and business owners in North Texas who value reliability, grit, and precision over flashy gimmicks. The visual language is inspired by heavy-duty engineering and modern industrial design—evoking the feeling of a custom-built tool rather than a generic service.

The style is **High-Contrast & Utilitarian**. It utilizes heavy typographic weights, architectural alignment, and a "no-nonsense" approach to layout. By stripping away decorative gradients and soft shadows, the UI emphasizes speed, transparency, and competence. It feels established and permanent.

## Colors
The palette is rooted in a deep, nocturnal Navy (#0D1B2A) which provides an immediate sense of authority and professional scale. Burnt Orange (#C45C1A) is used exclusively for Actionable items (CTAs), ensuring that "Call to Action" is never missed and feels distinctly Texan.

- **Primary/Background:** Used for hero sections, footers, and heavy-contrast blocks.
- **CTA/Accents:** Reserved for buttons, critical notifications, and high-priority lead-gen elements.
- **Body Backgrounds:** The Off-White (#F5F0E8) creates a sophisticated, "paper-like" contrast against the navy, preventing the design from feeling like a standard tech site.
- **Typography:** Warm White is used on dark backgrounds; Steel Gray is used for secondary metadata on light backgrounds to maintain legibility without the harshness of pure black.

## Typography
The typography is the primary driver of the "authority" narrative. **Chivo** is used for headlines; its heavy weights and sharp terminals feel mechanical and confident. **Public Sans** provides a neutral, highly readable body face that feels institutional and trustworthy.

**IBM Plex Sans** is used for utility labels and navigation. This monospaced-influenced sans-serif reinforces the industrial, systematic nature of the business. Use uppercase for labels and sub-headers to create a clear "blue-collar" visual hierarchy.

## Layout & Spacing
This design system utilizes a **12-column fixed-width grid** for desktop and a **fluid 4-column grid** for mobile. The layout philosophy is "Spacious and Structural." 

- **Section Gaps:** Large vertical spacing (120px+) between major sections forces the user to focus on one value proposition at a time, common in high-conversion landing pages.
- **In-Section Spacing:** Adhere strictly to an 8px grid. Use 24px for component gutters and 48px for grouping related content blocks.
- **Mobile Reflow:** On mobile, margins should shrink to 20px, and all display typography should scale down to ensure no horizontal overflow while maintaining the bold "heavyweight" feel.

## Elevation & Depth
In keeping with the "no-nonsense" requirement, this design system avoids traditional drop shadows and blurs. Depth is achieved through **Tonal Blocking** and **Stark Outlines**.

- **Stacked Tones:** Use color blocks (Navy vs. Off-White) to define hierarchy. 
- **The "Heavy Border":** Instead of shadows, use 1px or 2px solid borders (in Steel Gray or Navy) to define card boundaries.
- **Z-Index:** Interactive elements (like cards on hover) do not "float" higher; instead, they change border weight or background color (e.g., shifting from Off-White to Warm White).

## Shapes
The shape language is strictly professional. Elements use a "Soft" (0.25rem/4px) corner radius. This is enough to prevent the UI from feeling aggressive or dated (sharp 0px), but keeps it firm and structured. 

- **Buttons:** 4px radius.
- **Input Fields:** 4px radius with a heavy 2px stroke.
- **Cards:** 8px radius (rounded-lg) for large layout containers to subtly differentiate from smaller components.

## Components

### Buttons
- **Primary:** Burnt Orange background, Warm White text, 14px IBM Plex Sans (Bold/Caps). No gradient.
- **Secondary:** Dark Navy background, Warm White text, or Off-White background with Navy border.
- **Hover State:** Shift background color 10% darker; no "lift" effects.

### Input Fields
- **Default:** Off-White background with 2px Steel Gray border.
- **Focus:** 2px Burnt Orange border. This signifies "Action" and "Attention."
- **Labels:** Positioned above the field in 12px IBM Plex Sans Bold (Caps).

### Cards
- Use Off-White backgrounds on Dark Navy sections.
- Use a 1px Steel Gray border for cards sitting on Off-White backgrounds.
- Avoid all box-shadows.

### Chips/Badges
- Small, rectangular tags with 2px radius. Use for "Emergency Service" or "Certified" markers.
- Navy background with White text for high-contrast visibility.

### Lists
- Use custom checkmarks in Burnt Orange.
- High-contrast list items with 16px vertical padding to ensure touch-friendly interaction on mobile.