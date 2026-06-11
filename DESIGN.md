---
name: GLOIN
colors:
  surface: '#f6fafa'
  surface-dim: '#d6dbdb'
  surface-bright: '#f6fafa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f4f4'
  surface-container: '#eaefee'
  surface-container-high: '#e5e9e9'
  surface-container-highest: '#dfe3e3'
  on-surface: '#171c1d'
  on-surface-variant: '#3e4949'
  inverse-surface: '#2c3131'
  inverse-on-surface: '#edf2f1'
  outline: '#6e7979'
  outline-variant: '#bdc9c9'
  surface-tint: '#00696d'
  primary: '#00676a'
  on-primary: '#ffffff'
  primary-container: '#148185'
  on-primary-container: '#f2ffff'
  inverse-primary: '#7ad5d9'
  secondary: '#436465'
  on-secondary: '#ffffff'
  secondary-container: '#c3e6e7'
  on-secondary-container: '#486869'
  tertiary: '#8e4d27'
  on-tertiary: '#ffffff'
  tertiary-container: '#cb7e54'
  on-tertiary-container: '#4a1c00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#97f1f5'
  primary-fixed-dim: '#7ad5d9'
  on-primary-fixed: '#002021'
  on-primary-fixed-variant: '#004f52'
  secondary-fixed: '#c6e9ea'
  secondary-fixed-dim: '#aacdce'
  on-secondary-fixed: '#002021'
  on-secondary-fixed-variant: '#2b4c4d'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb690'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#713612'
  background: '#f6fafa'
  on-background: '#171c1d'
  surface-variant: '#dfe3e3'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
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
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.15em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 120px
---

# Design System & Aesthetics: GLOIN

This document defines the design tokens, aesthetic guidelines, and styling rules for the **GLOIN** landing page, aligned with its premium, high-tech, and precise industrial brand identity.

---

## 1. Aesthetic Concept & Mood
- **Brand Essence**: Industrial precision, architectural technology, high-end design, and large-scale capability.
- **Visual Style**: Minimalist, technical, clean, and highly premium. Glassmorphic overlays, clean typography, and smooth transitions are key.
- **Key Elements**: Subtle grid systems, thin borders, metallic/glass textures, and sharp geometry reflecting PVC profiles and double glazing (DVH).

---

## 2. Color Palette

### Background Gradients & Base Colors
- **Metallic Slate (Base/Neutral)**: `#737878` (Neutral tone for technical precision)
- **Technical Light Surface**: `#F5FAFB` (Bright, airy background surface)
- **Card Background (Glassmorphism)**: `rgba(255, 255, 255, 0.6)` with backdrop-filter blur for a frosted glass effect.

### Accents & Typography
- **Primary Text**: `#171D1D` (Deep charcoal/slate for high readability on light backgrounds)
- **Primary Teal (Actions & Highlights)**: `#1A8488` (Refined, professional teal)
- **Tertiary Copper (Hardware Accents)**: `#CB7E54` (Warm industrial metal contrast)
- **Secondary Text / Muted**: `#3F4949` (On-surface variant)
- **Border/Divider**: `rgba(26, 132, 136, 0.1)` (Primary teal with high transparency for technical subtlety)

---

## 3. Typography
- **Headers & Titles**: Clean, wide, geometric sans-serif (**Space Grotesk**).
- **Body & Technical Info**: Crisp, readable sans-serif (**Inter**).
- **Letter Spacing**: Generous letter-spacing for uppercase text to emphasize scale and modernity.

---

## 4. UI Elements & Layout Details
- **Fondo Degradado (Gradient Background)**: A subtle linear gradient running diagonally (`135deg`) using light surface-tinted tones.
- **Card Design**: Semi-transparent light panels with thin technical border colors (`rgba(26, 132, 136, 0.15)`), rounded corners (`16px`), and high backdrop-filter blur (`16px`).
- **Buttons / Calls to Action**:
  - *Primary*: Solid `#1A8488` with white text, micro-animations on hover (scale, subtle glow).
  - *Secondary*: Transparent with a border of `#5C7D7E`, text in `#171D1D`, shifting to a light tinted background on hover.
  - *Tertiary Accents*: Use `#CB7E54` for specialized labels or subtle metallic highlights.
- **Icons**: Clean, monolinear vector icons in `#1A8488` or `#171D1D`.