---
name: Rugged Utility
colors:
  surface: '#131411'
  surface-dim: '#131411'
  surface-bright: '#3a3936'
  surface-container-lowest: '#0e0e0c'
  surface-container-low: '#1c1c19'
  surface-container: '#20201d'
  surface-container-high: '#2a2a27'
  surface-container-highest: '#353532'
  on-surface: '#e5e2dd'
  on-surface-variant: '#e1bfb7'
  inverse-surface: '#e5e2dd'
  inverse-on-surface: '#31302d'
  outline: '#a88a82'
  outline-variant: '#59413b'
  surface-tint: '#ffb4a2'
  primary: '#ffb4a2'
  on-primary: '#611200'
  primary-container: '#f3623c'
  on-primary-container: '#550f00'
  inverse-primary: '#ae310e'
  secondary: '#bcc7da'
  on-secondary: '#263140'
  secondary-container: '#3f4a59'
  on-secondary-container: '#aeb9cc'
  tertiary: '#b9c8d8'
  on-tertiary: '#24323f'
  tertiary-container: '#8492a2'
  on-tertiary-container: '#1d2b38'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbd2'
  primary-fixed-dim: '#ffb4a2'
  on-primary-fixed: '#3c0800'
  on-primary-fixed-variant: '#891e00'
  secondary-fixed: '#d8e3f6'
  secondary-fixed-dim: '#bcc7da'
  on-secondary-fixed: '#111c2a'
  on-secondary-fixed-variant: '#3d4857'
  tertiary-fixed: '#d5e4f5'
  tertiary-fixed-dim: '#b9c8d8'
  on-tertiary-fixed: '#0e1d29'
  on-tertiary-fixed-variant: '#3a4856'
  background: '#131411'
  on-background: '#e5e2dd'
  surface-variant: '#353532'
typography:
  headline-xl:
    fontFamily: Barlow Condensed
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: 0.05em
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.03em
  headline-md:
    fontFamily: Barlow Condensed
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Barlow Condensed
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.08em
  headline-xl-mobile:
    fontFamily: Barlow Condensed
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.1'
spacing:
  unit: 8px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  container-max: 1200px
---

## Brand & Style

This design system is built on the foundation of "Blue-Collar Professionalism." It evokes the atmosphere of a clean, well-organized auto shop: authoritative, honest, and hardworking. The visual language rejects the ephemeral trends of software-as-a-service (SaaS) in favor of a grounded, industrial aesthetic that prioritizes clarity and functional reliability.

The style is characterized by a "Modern Industrial" approach—utilizing sharp corners, heavy typography, and high-contrast surfaces. There are no decorative flourishes, glows, or unnecessary animations. It is designed to feel like a handshake: firm, direct, and dependable. The goal is to instill immediate trust in the user, signaling that their vehicle is in the hands of experts who value precision over polish.

## Colors

The palette is rooted in industrial heritage. The primary anchor is a deep Navy Slate, providing a stable, low-glare environment typical of professional workshops. The Burnt Brick Red serves as the high-visibility accent, used exclusively for primary calls to action and critical status indicators.

- **Anchor / Background:** Used for the primary canvas of the application.
- **CTA / Accent:** Reserved for moments requiring user action or immediate attention.
- **Warm Neutral:** Utilized for high-contrast informational sections or printed-style surfaces to break up the dark interface.
- **Body / Card Backgrounds:** A mid-tier slate that provides tonal separation without the need for shadows.

Contrast ratios must strictly adhere to AA standards to ensure legibility in high-glare environments, such as a garage floor or outdoor sunlight.

## Typography

The typography system uses a pairing of high-impact industrial sans-serifs.

**Headlines** utilize a bold, condensed sans-serif with wide tracking. This mimics the lettering found on vintage workshop signage and modern industrial equipment. While the variable tokens allow for sentence case as requested, the tracking remains wide to maintain an authoritative presence.

**Body copy** is set in a neutral, utilitarian sans-serif designed for maximum legibility. The 16px base ensures that text is readable on mobile devices or tablets held at a distance. All labels and secondary data points should use the condensed font family to maintain the mechanical character of the design system.

## Layout & Spacing

This design system employs a **Fixed Grid** model. The layout is structured around an 8px base unit, ensuring all elements align to a predictable, sturdy rhythm.

- **Desktop:** A 12-column grid with a 1200px maximum width. Gutters are kept tight (16px) to maximize information density.
- **Mobile:** A single-column layout with 16px side margins. 
- **Reflow:** Components should stack vertically on mobile, with heavy borders separating distinct sections rather than soft padding.

Spacing should be used to create clear, logical groupings of information. Elements like service lists or pricing tables should feel compact and efficient, reflecting the "no-nonsense" philosophy.

## Elevation & Depth

Depth in this design system is achieved through **Tonal Layering** rather than shadows or light effects. Surfaces are stacked to create hierarchy:

1.  **Level 0 (Base):** Deep Navy Slate (#1A2533) for the primary background.
2.  **Level 1 (Cards/Containers):** Mid Slate (#2C3A47) used to define interactive areas or content blocks.
3.  **Level 2 (Inlays/Modals):** High-contrast Off-white (#F4F1EC) used for critical information or heavy-text documents (like invoices or service reports).

Instead of shadows, use **1px solid borders** in a lighter shade of the background color (or the Accent color for focus states) to define edges. This creates a flat, mechanical look that feels engineered rather than rendered.

## Shapes

The shape language is strictly **Sharp**. All UI elements—including buttons, cards, input fields, and alerts—utilize a 0px corner radius. 

Sharp corners reinforce the brand’s focus on precision, strength, and directness. It avoids the "friendly" softness of consumer apps, leaning instead into an aesthetic of hardware and heavy-duty tools. This choice makes every element on the screen feel intentional and unyielding.

## Components

**Buttons**
Buttons are rectangular with zero roundedness. Primary CTA buttons use the Burnt Brick Red background with white text. Secondary buttons use a transparent background with a 2px solid white border. No gradients or shadows are permitted.

**Input Fields**
Inputs feature a Mid Slate background with a 1px border. On focus, the border changes to Burnt Brick Red. Labels are placed above the field in the condensed font, set in all-caps for a technical, labeled-drawer feel.

**Cards**
Cards use the Mid Slate background to sit slightly above the Base background. They should not have shadows. Grouping within cards is achieved through 1px horizontal dividers in the base Navy Slate color.

**Chips / Status Badges**
Used for vehicle status (e.g., "In Progress," "Completed"). These are small, sharp-edged rectangles. Use the Burnt Brick Red for urgent alerts and the Warm Neutral for general status.

**Lists & Tables**
Data-heavy lists should use alternating row colors (zebra striping) between the Mid Slate and the Base background to ensure readability when looking at complex service histories or parts lists.