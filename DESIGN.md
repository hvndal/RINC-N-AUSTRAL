---
name: Alpina Wilderness System
colors:
  surface: '#fcf8f7'
  surface-dim: '#ddd9d8'
  surface-bright: '#fcf8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3f1'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e6'
  surface-container-highest: '#e5e2e0'
  on-surface: '#1c1b1b'
  on-surface-variant: '#464742'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#777871'
  outline-variant: '#c7c7bf'
  surface-tint: '#5e5e5b'
  primary: '#5e5e5b'
  on-primary: '#ffffff'
  primary-container: '#f9f7f2'
  on-primary-container: '#71716d'
  inverse-primary: '#c8c6c2'
  secondary: '#5c5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dee0e0'
  on-secondary-container: '#606363'
  tertiary: '#546256'
  on-tertiary: '#ffffff'
  tertiary-container: '#ecfbec'
  on-tertiary-container: '#667469'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e2dd'
  primary-fixed-dim: '#c8c6c2'
  on-primary-fixed: '#1b1c19'
  on-primary-fixed-variant: '#474744'
  secondary-fixed: '#e1e3e3'
  secondary-fixed-dim: '#c4c7c7'
  on-secondary-fixed: '#191c1c'
  on-secondary-fixed-variant: '#444747'
  tertiary-fixed: '#d7e6d8'
  tertiary-fixed-dim: '#bbcabc'
  on-tertiary-fixed: '#121e15'
  on-tertiary-fixed-variant: '#3d4a3f'
  background: '#fcf8f7'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e0'
typography:
  display-xl:
    fontFamily: Playfair Display
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 90px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 54px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: DM Sans
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 24px
  section-gap: 160px
---

## Brand & Style
The design system embodies "Quiet Luxury" set against the raw, majestic backdrop of Argentine Patagonia. It prioritizes a cinematic and editorial experience that feels like a high-end travel monograph rather than a standard booking engine.

The aesthetic is **Minimalist Luxury** with a focus on **Serenity and Expansiveness**. It draws inspiration from the architectural restraint of Aman and the tactile storytelling of Kinfolk. The UI acts as a silent gallery frame for breathtaking wilderness photography, using vast white space (Warm Ivory) to create a sense of psychological breathing room. Every interaction should feel intentional, slow, and refined, evoking an emotional response of awe and profound calm.

## Colors
The palette is rooted in the Patagonian landscape. **Warm Ivory** serves as the primary canvas, replacing harsh whites to provide a softer, more organic feel. **Patagonian Stone** and **Deep Forest Green** provide grounding structural elements and primary typography colors.

**Lake Turquoise** is used sparingly as a high-end accent for specific call-outs or status indicators, mirroring the glacial lakes of the region. Neutrals like **Weathered Oak** and **Burnt Copper** are reserved for secondary UI elements, iconography, and decorative dividers to maintain a warm, tactile connection to natural materials like wood and earth.

## Typography
The typography system relies on a high-contrast pairing: **Playfair Display** for an authoritative, editorial serif presence and **DM Sans** for a modern, functional, and airy sans-serif body.

- **Headlines:** Use wide tracking for Display styles to emphasize luxury. Playfair Display should always be used for storytelling elements and section headers.
- **Body:** DM Sans provides a clean, neutral counterpoint. Maintain generous line heights (1.6x+) to ensure readability and a sense of lightness.
- **Labels:** Small labels use uppercase DM Sans with increased letter spacing to mimic high-end fashion branding.

## Layout & Spacing
The layout follows an **asymmetric editorial grid** rather than a rigid functional one. Use a 12-column grid for desktop, but intentionally leave columns empty to create "white space pockets."

- **Margins:** Extremely wide side margins (80px+) on desktop focus the user's eye on the center content.
- **Section Gaps:** Vertical spacing between major sections is aggressive (160px+) to ensure each concept or image feels isolated and important.
- **Mobile:** Transition to a single-column fluid layout with 24px side margins. Use vertical scrolling as a narrative device, utilizing large-scale imagery that spans the full width of the viewport.

## Elevation & Depth
Elevation is achieved through **Tonal Layers** and **Subtle Glassmorphism** rather than traditional drop shadows.

- **Surfaces:** Use the secondary neutral (Natural Limestone) for subtle container backgrounds to differentiate from the Warm Ivory base.
- **Glassmorphism:** For overlays, navigation bars, and mobile menus, use a high-refinement backdrop blur (20px-30px) with a 60% opacity Warm Ivory tint.
- **Outlines:** Instead of shadows, use "Ghost Borders"—1px solid lines in **Weathered Oak** or **Natural Limestone** at low opacity (20-40%) to define boundaries without adding visual weight.

## Shapes
This design system utilizes **Sharp (0px)** corners for all structural elements including buttons, image containers, and input fields. The lack of roundedness communicates architectural precision and a sophisticated, contemporary edge.

Circular elements are only permitted for specific functional icons (like a play button or a directional arrow) to create a clear distinction between "content containers" and "interactive triggers."

## Components
- **Buttons:** Primary buttons are sharp-edged, using a Deep Forest Green background with Warm Ivory text. Hover states should involve a subtle shift to Lake Turquoise or a thin 1px outline expansion. Text is always uppercase with 0.1em tracking.
- **Imagery Containers:** Images are the hero. Use large aspect ratios (16:9 or 4:3). Implement a slow "ken burns" scale effect on scroll or hover to add a cinematic quality.
- **Lists:** Use thin horizontal dividers in Natural Limestone. List items should have significant vertical padding (24px+) to maintain the airy feel.
- **Input Fields:** Bottom-border only (1px Weathered Oak). Labels float above in uppercase DM Sans. This creates a minimalist, "registration desk" aesthetic.
- **Chips/Labels:** Small, sharp-edged boxes with a 1px Patagonian Stone border and centered text.
- **Cards:** Cards should not have shadows. Use a subtle background color shift (Natural Limestone) and sharp corners to define the card area. Text within cards should be center-aligned for an editorial look.
- **Navigation:** A sticky top bar using the glassmorphism treatment. The logo is centered, with navigation links split to the left and right to maintain balance.