---
name: Serene Dental
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#42474e'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#73777f'
  outline-variant: '#c2c7cf'
  surface-tint: '#3c6186'
  primary: '#00243f'
  on-primary: '#ffffff'
  primary-container: '#0e3a5d'
  on-primary-container: '#80a4cd'
  inverse-primary: '#a5caf4'
  secondary: '#006684'
  on-secondary: '#ffffff'
  secondary-container: '#68d3ff'
  on-secondary-container: '#005a74'
  tertiary: '#002725'
  on-tertiary: '#ffffff'
  tertiary-container: '#003f3b'
  on-tertiary-container: '#3ab2a9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e4ff'
  primary-fixed-dim: '#a5caf4'
  on-primary-fixed: '#001d34'
  on-primary-fixed-variant: '#22496d'
  secondary-fixed: '#bde9ff'
  secondary-fixed-dim: '#68d3ff'
  on-secondary-fixed: '#001f2a'
  on-secondary-fixed-variant: '#004d64'
  tertiary-fixed: '#85f5eb'
  tertiary-fixed-dim: '#67d8cf'
  on-tertiary-fixed: '#00201e'
  on-tertiary-fixed-variant: '#00504b'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  section-padding: 80px
---

## Brand & Style
The design system is built for a premium healthcare environment that prioritizes patient tranquility and clinical excellence. The brand personality is "Ultra-Modern Scandinavian," combining the precision of medical science with the warmth of a luxury wellness retreat.

The visual style is a fusion of **Minimalism** and **Glassmorphism**. It utilizes heavy whitespace to evoke a sense of hygiene and mental clarity, while employing soft, translucent layers to create a "fear-free" digital environment. Every interaction should feel intentional, frictionless, and premium, mirroring the high-end physical experience of the clinic.

## Colors
The palette is anchored by **Deep Navy Blue**, providing an authoritative and trustworthy foundation. **Dental Blue** and **Soft Mint** are used as clinical accents to signify freshness and oral health. 

- **Primary (Deep Navy):** Use for hero headings, primary buttons, and critical UI state.
- **Secondary (Dental Blue):** Use for interactive elements and brand markers.
- **Accent (Soft Mint):** Use sparingly for highlights and subtle background washes.
- **Surface:** Pure White is the primary canvas to ensure a "clinical-clean" aesthetic. 
- **Sectioning:** Use the off-white tint (#F8FAFC) to differentiate content blocks without using heavy borders.

## Typography
The typographic system creates a hierarchy of "Confident Precision." **Manrope** is used for all headings to provide a modern, geometric, yet friendly personality. **Inter** is used for body text to maintain maximum legibility and a systematic, clean feel.

Large display headings should use tighter letter-spacing to emphasize the premium editorial look. Body text defaults to a "Medium" (500) weight to ensure readability against light backgrounds, avoiding the "thinness" that can sometimes feel unapproachable in healthcare settings.

## Layout & Spacing
The layout follows a **Fluid Grid** philosophy with generous breathing room. 
- **Desktop:** 12-column grid with 24px gutters. Content should be centered within a 1200px container.
- **Mobile:** 4-column grid with 20px side margins. 
- **Rhythm:** Spacing follows an 8px base unit. Use significant vertical padding (80px+) between sections to allow the Scandinavian minimalist aesthetic to breathe. High-priority information should be isolated to prevent visual clutter.

## Elevation & Depth
This design system uses **Ambient Shadows** and **Glassmorphism** to create a sense of lightness and layering. 

- **Navigation:** The top bar should use a high-saturation background blur (20px+) with a semi-transparent white fill (70-80% opacity). 
- **Elevation Levels:** Shadows should be extremely diffused and low-opacity (5-8%), using the Primary Navy color as the shadow tint rather than pure black to maintain a softer, more premium look.
- **Layering:** Use subtle inner shadows on input fields to create a "recessed" feel, while buttons and cards "float" slightly above the surface.

## Shapes
The shape language is defined by "Organic Precision." While the base roundedness is set to `2` (0.5rem), the system utilizes `rounded-2xl` (1.5rem) and `rounded-3xl` (2rem) for primary containers and cards to mimic high-end hardware and Apple-inspired aesthetics.

Buttons and selection chips should use a **Full Pill** (rounded-full) radius to evoke comfort and safety, removing any sharp angles that could subconsciously trigger dental anxiety.

## Components
- **Buttons:** Primary buttons use a solid Deep Navy fill with white text. Secondary buttons use a transparent background with a thin 1px border in Dental Blue. All buttons should have a high horizontal padding (24-32px).
- **Cards:** White background with a `rounded-3xl` radius and a very soft ambient shadow. No borders.
- **Input Fields:** Soft grey background (#F8FAFC) with a `rounded-xl` radius. On focus, the border transitions to Soft Mint.
- **Chips/Badges:** Use Soft Mint with a 10% opacity background and solid Soft Mint text for a "fresh" and "clean" status indicator.
- **Iconography:** Use 1.5pt line icons with rounded caps. Icons should be monochrome (Primary Navy) or use the Dental Blue for active states.
- **Patient Progress Bar:** A custom, thin linear progress bar using the Soft Mint accent to track appointment booking or treatment stages.