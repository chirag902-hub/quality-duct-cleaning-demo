---
name: Smiley's Empire Core
colors:
  surface: '#121413'
  surface-dim: '#121413'
  surface-bright: '#383a38'
  surface-container-lowest: '#0d0f0e'
  surface-container-low: '#1a1c1b'
  surface-container: '#1e201f'
  surface-container-high: '#282a29'
  surface-container-highest: '#333534'
  on-surface: '#e2e3e1'
  on-surface-variant: '#c2c6d4'
  inverse-surface: '#e2e3e1'
  inverse-on-surface: '#2f3130'
  outline: '#8c919d'
  outline-variant: '#424752'
  surface-tint: '#a9c7ff'
  primary: '#a9c7ff'
  on-primary: '#003063'
  primary-container: '#1565c0'
  on-primary-container: '#dae5ff'
  inverse-primary: '#005db7'
  secondary: '#bbc9d0'
  on-secondary: '#253238'
  secondary-container: '#3e4b51'
  on-secondary-container: '#adbbc2'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#676666'
  on-tertiary-container: '#e8e4e4'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#a9c7ff'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#00468c'
  secondary-fixed: '#d7e5ec'
  secondary-fixed-dim: '#bbc9d0'
  on-secondary-fixed: '#101d23'
  on-secondary-fixed-variant: '#3c494f'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#121413'
  on-background: '#e2e3e1'
  surface-variant: '#333534'
typography:
  display-xl:
    fontFamily: DM Sans
    fontSize: 80px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: DM Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: DM Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.1'
  headline-md:
    fontFamily: DM Sans
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
  cta-label:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  caption:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The visual identity of the design system is rooted in **Industrial Brutalism** mixed with high-octane **Modernism**. It captures the "street-credible" essence of an established Temecula tire shop while maintaining the professional precision expected in automotive care. The aesthetic is raw, gritty, and intentionally unrefined in its layout, yet polished in its execution.

The brand persona is "The Trusted Expert"—an authoritative figure who knows the asphalt better than anyone else. To evoke this, the UI utilizes heavy borders, high-contrast typography, and cinematic, high-grain imagery of tires and workshop environments. The emotional goal is to project reliability and mechanical expertise through a "no-nonsense" interface.

- **Minimalism & Brutalism:** Large whitespace to offset heavy, industrial elements.
- **Cinematic Atmosphere:** Photography uses deep shadows and high-contrast lighting.
- **Street Credibility:** Usage of monospaced-style labels and rigid structural grids to mimic technical automotive manuals.

## Colors

The palette is designed to look like a workshop floor: concrete, steel, and a singular pop of "Electric Cobalt" signaling high voltage and action.

- **Dark Anchor (#141414):** The core of the system. Used for headers, main surfaces, and deep card backgrounds to provide a "midnight" industrial feel.
- **Electric Cobalt (#1565C0):** Reserved exclusively for high-priority actions (CTAs), focus states, and critical information.
- **Smoked Steel (#B0BEC5):** Used for supporting text, borders, and secondary icons. It provides a metallic, industrial texture to the UI.
- **Off-White Concrete (#F2F2F0):** Used for sections that require high readability or as a high-contrast background to break up dark content.

**Strict Constraint:** No warm tones (amber/gold/yellow) or purple-tinted gradients. All gradients must be linear, moving from #141414 to #2A2A2A to preserve the gritty, monochromatic depth.

## Typography

Typography is the "heavy lifting" element of this design system. We use a high-contrast pairing that balances the thick, impactful weight of **DM Sans Bold** with the clinical, functional precision of **Inter**.

- **Headlines:** Set in DM Sans Bold. They should be massive, often overlapping or tightly packed with negative letter-spacing to create a "blocky," industrial feel. Sentence case is preferred for a modern, direct tone.
- **Body:** Inter Regular provides the necessary readability for service descriptions and technical specifications. Minimum size is strictly 16px.
- **Labels & Technicals:** JetBrains Mono (monospaced) is used for small metadata, such as SKU numbers, tire sizes, or technical specs, reinforcing the "mechanic's manual" aesthetic.
- **CTAs:** High contrast, uppercase, and bold to ensure they pop against the dark background.

## Layout & Spacing

The layout philosophy follows a **Dynamic Asymmetric Grid**. Rather than perfectly centered content, elements are often offset to create a sense of movement and energy, reminiscent of a busy shop floor.

- **Asymmetry:** Cards should vary in height or be staggered on a 12-column grid to prevent a "template" look.
- **Generous Whitespace:** Large gaps (120px+) between sections are used to isolate photography and headlines, giving the content "room to breathe" amidst the gritty textures.
- **Mobile-First:** On mobile, the grid collapses into a single column of high-impact cards. The asymmetric nature is maintained through varying padding levels on the left and right sides of different components.
- **Grid:** 12-column fluid grid for desktop with wide 64px margins. Use 16px margins for mobile to maximize real estate for tire photography.

## Elevation & Depth

Depth in this system is achieved through **Tonal Layering** and **Industrial Shadows** rather than traditional elevation.

- **Tonal Layers:** The base background is #141414. Cards use a slightly lighter #1F1F1F to appear "above" the surface.
- **Low-Contrast Outlines:** Instead of soft shadows, use 1px solid borders in #B0BEC5 (Smoked Steel) at 20% opacity to define boundaries. This creates a "blueprint" feel.
- **Hard Shadows:** Where depth is required for buttons, use a 0-blur, 4px-offset hard shadow in #000000 to mimic physical metal plates.
- **Image Overlays:** Photos must use a 40-60% black-to-transparent gradient overlay to ensure white headline text remains legible and the "cinematic" mood is maintained.

## Shapes

The shape language is strictly **Sharp (0px)**. To maintain the industrial, rugged vibe, there are no rounded corners in this design system. 

- **Buttons:** Sharp 90-degree corners.
- **Cards:** Sharp 90-degree corners with optional 1px "brushed steel" borders.
- **Inputs:** Sharp edges.
- **Images:** All photography is clipped to sharp rectangular containers.

This "hard edge" approach reinforces the professional, heavy-duty nature of the tire industry.

## Components

### Buttons
- **Primary:** Electric Cobalt (#1565C0) background, white text, sharp corners. On hover, background shifts to a darker navy, and a 2px Smoked Steel bottom border appears.
- **Secondary:** Transparent background, 2px Smoked Steel border, white text.
- **Tertiary:** Text-only with an underline that extends 100% width on hover.

### Cards
- **Asymmetric Cards:** Use varying widths (e.g., one card spans 5 columns, the next 7).
- **Backgrounds:** Always #141414 or a cinematic image with a dark overlay.
- **Border:** 1px solid #B0BEC5 at 10% opacity.

### Input Fields
- Underline-only style or solid #1F1F1F background with no border. 
- Focus state: A 2px Electric Cobalt bottom border.
- Label text: JetBrains Mono, 12px, uppercase.

### Lists & Specs
- Use the Smoked Steel color for list icons.
- Bullet points should be replaced with horizontal "dashes" or technical "plus" signs (+) to match the industrial theme.

### Additional Components
- **The "Tread" Divider:** A thin, repeating 45-degree pattern divider used to separate sections, mimicking tire tread marks.
- **Service Tags:** Small, monospaced chips in Smoked Steel with black text, used for categorizing tire types (e.g., "ALL-TERRAIN", "PERFORMANCE").