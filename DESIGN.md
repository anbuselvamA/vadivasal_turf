---
name: Eco-Sports Identity
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#bfcaba'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8a9485'
  outline-variant: '#40493d'
  surface-tint: '#88d982'
  primary: '#88d982'
  on-primary: '#003909'
  primary-container: '#2e7d32'
  on-primary-container: '#cbffc2'
  inverse-primary: '#1b6d24'
  secondary: '#7dffa2'
  on-secondary: '#003918'
  secondary-container: '#05e777'
  on-secondary-container: '#00622e'
  tertiary: '#91d78a'
  on-tertiary: '#003909'
  tertiary-container: '#3a7b39'
  on-tertiary-container: '#c8ffbf'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#a3f69c'
  primary-fixed-dim: '#88d982'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005312'
  secondary-fixed: '#62ff96'
  secondary-fixed-dim: '#00e475'
  on-secondary-fixed: '#00210b'
  on-secondary-fixed-variant: '#005226'
  tertiary-fixed: '#acf4a4'
  tertiary-fixed-dim: '#91d78a'
  on-tertiary-fixed: '#002203'
  on-tertiary-fixed-variant: '#0c5216'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Lexend
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Lexend
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Lexend
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

The design system is built for the high-performance intersection of sustainability and competitive athletics. The brand personality is aggressive yet conscious, combining the adrenaline of professional sports with the precision of environmental science. It targets an audience of "eco-warriors" and high-performance athletes who value technical excellence and ecological responsibility.

The visual style is **High-Contrast / Bold** with a **Minimalist** technical edge. By utilizing a deep charcoal base, the primary green acts as a high-visibility signal, akin to stadium lighting or performance neon gear. The interface focuses on speed, clarity, and impactful data visualization, evoking an emotional response of motivation, power, and discipline.

## Colors

This design system utilizes a high-contrast dark palette to ensure maximum readability and impact. The **Primary Color (#2E7D32)** serves as the core brand anchor, while a brighter **Secondary Green (#00E676)** is reserved for high-action call-to-outs, success states, and critical performance metrics. 

The background is a strict **Deep Charcoal (#121212)** to minimize light bleed and maximize the vibrancy of the greens. Text hierarchies are strictly enforced with pure white for headlines and a muted grey for supporting information to maintain the "sleek sports" aesthetic without overwhelming the user's eye.

## Typography

Lexend is the exclusive typeface for this design system, chosen for its athletic clarity and exceptional readability in high-stress or high-motion environments. 

Headlines use heavy weights (700-800) with slight negative letter-spacing to create a "locked-in" and aggressive look typical of sports broadcasting. Body text remains light but legible, while labels utilize uppercase styling and increased tracking to emulate technical gear markings and performance statistics.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** model with a standard 12-column structure for desktop and a single column for mobile. The system uses an 8px rhythmic scale to ensure mathematical consistency between elements.

Padding and margins are generous on the outer containers to provide a "premium" feel, but tighten significantly within data-heavy components to maintain a technical, dashboard-like density. This contrast in spacing reinforces the professional athlete's focus on precision within the larger environment.

## Elevation & Depth

Visual hierarchy in this design system is achieved through **Tonal Layers** rather than traditional shadows. Surfaces are stacked using varying shades of charcoal to define depth:
- **Level 0 (Background):** #121212
- **Level 1 (Cards/Sections):** #1E1E1E
- **Level 2 (Modals/Popovers):** #2C2C2C

To enhance the modern feel, a **1px Low-contrast Outline** (#333333) is used on card elements to provide definition without breaking the sleek, flat aesthetic. High-action elements like primary buttons may use a subtle, diffused glow of the primary green color to simulate an "active energy" or bioluminescence.

## Shapes

The shape language is **Soft (0.25rem)**, leaning toward a more technical and geometric look. This sharp-but-not-brutal approach reflects the precision of carbon-fiber sports equipment and high-tech sustainable materials.

Buttons and active interactive elements utilize the base 4px (0.25rem) radius, while larger containers like cards may scale up to 8px (0.5rem) to maintain visual balance. Pill shapes are reserved exclusively for "Status" indicators and performance tags to differentiate them from functional buttons.

## Components

### Buttons
Primary buttons are solid #2E7D32 with white Lexend Bold text. Secondary buttons use a ghost style with a #2E7D32 border. Interaction states (hover) should shift the primary color to the more vibrant #00E676.

### Cards
Cards are built on #1E1E1E with a 1px #333333 border. They should avoid heavy drop shadows, relying on the tonal contrast against the #121212 background to stand out.

### Inputs & Selection
Input fields feature a dark fill (#252525) with a bottom-border-only focus state in primary green. Checkboxes and radio buttons use the primary green for "active" states, creating a sharp visual "on" signal.

### Specialized Components
- **Performance Gauges:** Circular or linear progress bars using #00E676 against a #333333 track.
- **Metric Chips:** Small, uppercase labels with a #1B5E20 background and #00E676 text to highlight specific eco-metrics or athlete stats.
- **Data Tables:** High-density rows with alternating tonal backgrounds and no vertical borders to maintain a streamlined, horizontal flow.