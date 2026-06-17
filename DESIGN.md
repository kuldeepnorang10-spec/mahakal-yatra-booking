---
name: Sacred Kinetic
colors:
  surface: '#041329'
  surface-dim: '#041329'
  surface-bright: '#2c3951'
  surface-container-lowest: '#010e24'
  surface-container-low: '#0d1c32'
  surface-container: '#112036'
  surface-container-high: '#1c2a41'
  surface-container-highest: '#27354c'
  on-surface: '#d6e3ff'
  on-surface-variant: '#e0c0b1'
  inverse-surface: '#d6e3ff'
  inverse-on-surface: '#233148'
  outline: '#a78b7e'
  outline-variant: '#584237'
  surface-tint: '#ffb692'
  primary: '#ffb692'
  on-primary: '#552000'
  primary-container: '#ff7722'
  on-primary-container: '#5e2400'
  inverse-primary: '#9f4200'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#ebc245'
  on-tertiary: '#3d2f00'
  tertiary-container: '#c09b1e'
  on-tertiary-container: '#443400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcb'
  primary-fixed-dim: '#ffb692'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#793100'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffe08c'
  tertiary-fixed-dim: '#ebc245'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#584400'
  background: '#041329'
  on-background: '#d6e3ff'
  surface-variant: '#27354c'
  saffron-vibrant: '#FF7722'
  antique-gold: '#D4AF37'
  deep-navy: '#0A192F'
  sticker-white: '#FFFFFF'
  ink-black: '#000000'
typography:
  display-lg:
    fontFamily: Cinzel
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: 0.02em
  display-lg-mobile:
    fontFamily: Cinzel
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Cinzel
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Cinzel
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is built on a "Spiritual Pop-Art Fusion" philosophy, bridging the ancient reverence of temple pilgrimage with the vibrant, high-energy aesthetics of modern digital culture. It targets a new generation of spiritual seekers who value both tradition and technological seamlessness.

The visual style is characterized by **Immersive Cinematic Realism** layered with **Pop-Art Graphic Overlays**. This is achieved through:
- **Cinematic Depth:** Using heavy layering, ambient blurs, and deep perspective to create a sense of vastness.
- **Graphic Contrast:** Utilizing halftone dot patterns and sticker-style UI elements (heavy white borders, hard shadows) to inject a youthful, energetic "Pop" vibe into the sacred context.
- **Glassmorphism:** Employing frosted glass surfaces to maintain high-end sophistication while allowing vibrant background colors to bleed through.

## Colors

The palette is anchored in **Deep Navy Blue**, providing a celestial, night-sky backdrop that allows chromatic accents to glow. 

- **Primary Saffron:** Used for call-to-action elements, primary buttons, and critical spiritual focus points. It represents the fire of transformation.
- **Antique Gold:** Reserved for secondary accents, icons, and decorative trim. It adds the "Premium" layer, suggesting timeless value and divinity.
- **Neutral Navy:** The foundation of all backgrounds. Avoid pure black; use the deep navy to maintain depth and color harmony.
- **Functional Accents:** Pure white is used exclusively for the "Sticker" effects and high-readability body text on dark backgrounds.

## Typography

This system employs a high-contrast typographic pairing:

1.  **Cinzel (Headers):** Used for all titles and hero sections. Its classical Roman proportions evoke stone inscriptions and traditional authority. Use "Bold" for display levels to ensure the "Pop-Art" impact.
2.  **Lexend (Body):** Selected for its hyper-readability and modern, geometric structure. It balances the ornate nature of Cinzel with a clean, functional feel.
3.  **Inter (UI Labels):** Utilized for small metadata, button labels, and system status. Often set in uppercase with increased letter spacing to provide a technical, "cutting-edge" contrast to the organic spiritual themes.

## Layout & Spacing

The layout follows a **Fluid Cinematic Grid** designed to showcase high-quality imagery.

- **Grid Model:** A 12-column system for desktop with generous 24px gutters to allow elements "room to breathe." On mobile, a 4-column grid is used.
- **Safe Zones:** Content is heavily centered or asymmetrical to create a dynamic, editorial feel. 
- **Halftone Patterns:** Subtle dot patterns should be used in the margins or as "texture leaks" behind cards to break the perfection of the digital grid, reinforcing the Pop-Art aesthetic.
- **Rhythm:** Spacing follows an 8px base unit. Larger vertical gaps (80px - 120px) are encouraged between sections to create a sense of "pilgrimage" as the user scrolls.

## Elevation & Depth

Hierarchy is established through extreme depth layering rather than simple shadows:

1.  **Background Layer:** Deep Navy (#0A192F) with subtle radial gradients and halftone textures.
2.  **Mid-Ground Layer:** Glassmorphic cards with a 16px backdrop blur, 10% white opacity fill, and a 1px Antique Gold (#D4AF37) border.
3.  **Foreground Layer:** "Sticker" elements (Mascots/Chips) with 0px blur hard-drop shadows (offset 4px, 4px) and 3px solid white borders.
4.  **Glow Layer:** Interactive elements like primary buttons should emit a soft Saffron (#FF7722) outer glow to simulate a sacred aura.

## Shapes

The design system uses a **Mixed-Geometry** approach:
- **UI Containers:** Use "Rounded" (0.5rem) corners to maintain a sophisticated, modern SaaS feel.
- **Sticker Elements:** Use "Irregular" or highly rounded paths. The mascot avatar must have a thick, irregular white offset path (reminiscent of a hand-cut sticker).
- **Icons:** Should be thin-stroke (Antique Gold) to contrast against the bold, heavy shapes of the buttons.

## Components

- **Buttons:** Primary buttons are Solid Saffron (#FF7722) with a subtle "inner-glow" and 1px Gold border. On hover, they should scale slightly (1.05x). Secondary buttons use the Glassmorphism style with Gold text.
- **Sticker Mascot:** The digital avatar always appears with a `3px solid #FFFFFF` border and a `4px 4px 0px #000000` (ink-black) drop shadow. It should appear "thrown" onto the interface at slight angles (-3 to +3 degrees).
- **Glass Cards:** Used for trip details and content blocks. Feature a `backdrop-filter: blur(16px)` and a thin Gold border (`0.5px`).
- **Input Fields:** Deep Navy fills with Gold bottom-borders only, creating a "Temple-Gate" minimalist look. Focus state brings up a Saffron glow.
- **Chips:** Highly rounded (Pill-shaped) with Saffron background and Black text for high-impact Pop-Art readability.
- **Progress Indicators:** Use a "Mandala" spinning loader or a linear bar that fills with a Saffron-to-Gold gradient.