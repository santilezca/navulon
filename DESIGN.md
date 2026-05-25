---
name: Navulon Core
colors:
  surface: '#111318'
  surface-dim: '#111318'
  surface-bright: '#37393e'
  surface-container-lowest: '#0c0e12'
  surface-container-low: '#1a1c20'
  surface-container: '#1e2024'
  surface-container-high: '#282a2e'
  surface-container-highest: '#333539'
  on-surface: '#e2e2e8'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#e2e2e8'
  inverse-on-surface: '#2f3035'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#b0c6ff'
  on-secondary: '#002c6f'
  secondary-container: '#0153c2'
  on-secondary-container: '#c0d0ff'
  tertiary: '#bac3ff'
  on-tertiary: '#00208f'
  tertiary-container: '#7187fe'
  on-tertiary-container: '#001b7e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#d9e2ff'
  secondary-fixed-dim: '#b0c6ff'
  on-secondary-fixed: '#001945'
  on-secondary-fixed-variant: '#00419c'
  tertiary-fixed: '#dee0ff'
  tertiary-fixed-dim: '#bac3ff'
  on-tertiary-fixed: '#00115a'
  on-tertiary-fixed-variant: '#1f38af'
  background: '#111318'
  on-background: '#e2e2e8'
  surface-variant: '#333539'
  deep-navy: '#0F172A'
  surface-stroke: rgba(255, 255, 255, 0.1)
  electric-glow: rgba(59, 130, 246, 0.5)
  trust-green: '#10B981'
typography:
  headline-xl:
    fontFamily: Sora
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Sora
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
  button-text:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base-unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The design system is engineered for a high-performance, premium technology environment. The brand personality is authoritative yet innovative, catering to a sophisticated audience that values speed, security, and precision.

The visual direction follows a **Modern High-Tech** aesthetic, blending elements of **Glassmorphism** with **Minimalist** precision. This is achieved through the use of deep, atmospheric backgrounds punctuated by vibrant "electric" accents. The emotional response should be one of "future-ready reliability"—a interface that feels both powerful and effortless. Key visual drivers include subtle inner glows, high-contrast typography, and a "depth-first" layering strategy that mimics high-end hardware interfaces.

## Colors

This design system utilizes a "Deep Space" palette. The foundation is a near-black neutral (`#0A0C10`), providing maximum contrast for the electric blue primary accent.

- **Primary Electric Blue:** Reserved for high-priority actions (CTAs) and active states. It should often be accompanied by a subtle outer glow to simulate a light-emitting source.
- **Deep Navy & Surface:** Used to create hierarchical layers. Surfaces sitting "closer" to the user should use slightly lighter navy tones (`#0F172A`) or semi-transparent glass layers.
- **Accents:** White is used strictly for high-readability text and crisp iconography. Tertiary blues are used for supporting data visualization or secondary interactive elements.

## Typography

Typography in the design system is built on a "Tech-Humanist" hybrid approach.

- **Sora (Headlines):** Chosen for its geometric precision and modern "tech" feel. It should be set with tight letter spacing for a compact, high-impact look in marketing sections.
- **Plus Jakarta Sans (Body):** Provides exceptional readability and a welcoming touch to balance the coldness of the dark theme.
- **JetBrains Mono (Technical Labels):** Used for "Trust Badges," metadata, and small captions to evoke a sense of technical engineering and accuracy.

All typography should maintain a high contrast ratio against the dark background, utilizing pure white for primary content and a 60% opacity white for secondary information.

## Layout & Spacing

The design system employs a **12-column fixed grid** for desktop, centered within a maximum container width of 1280px. 

### Rhythm
The spacing system is strictly linear based on an 8px scale. 
- **Internal Padding:** Use 16px or 24px for component internals.
- **Layout Spacing:** Use large, airy gaps (80px to 120px) between sections to allow the high-tech elements room to "breathe" and prevent the dark theme from feeling cramped.

### Responsive Strategy
- **Desktop:** 12 columns, 64px side margins.
- **Tablet:** 8 columns, 32px side margins.
- **Mobile:** 4 columns, 20px side margins. Elements that are horizontally oriented on desktop should stack vertically, maintaining the 8px unit consistency.

## Elevation & Depth

Elevation is conveyed through **Light Scarcity** and **Glassmorphism** rather than traditional heavy shadows.

1.  **Level 0 (Base):** The core background color (`#0A0C10`).
2.  **Level 1 (Sub-surface):** Slightly lighter navy with a 1px border of `surface-stroke` to define edges.
3.  **Level 2 (Active/Floating):** Semi-transparent surfaces with a 12px background blur (backdrop-filter) and a subtle 1px top-light border (white at 15% opacity).
4.  **Accent Elevation:** Primary CTAs use a soft, 20px electric blue outer glow (`electric-glow`) to appear as if they are self-illuminated.

Avoid using black shadows; instead, use darker indigo-tinted shadows to maintain the atmospheric "Deep Navy" feel.

## Shapes

The shape language is "Soft-Tech." Elements are neither strictly sharp nor overly bubbly. 

- **Standard UI Elements:** (Buttons, Input Fields) use a 0.5rem (8px) radius to feel modern and accessible.
- **Large Containers:** (Cards, Modals) use a 1rem (16px) radius to emphasize the "Glassmorphism" effect.
- **Technical Badges:** Use a pill-shape (full radius) to distinguish them from functional interactive elements.
- **Borders:** All borders should be 1px wide. Use "inner borders" (box-shadow inset) to give buttons a high-quality "machined" look.

## Components

### Buttons
- **Primary:** Solid Electric Blue background, white text, 8px radius. Include a subtle `electric-glow` on hover.
- **Secondary:** Transparent background with a 1px `surface-stroke` and white text.
- **Tertiary:** Text-only with an underline effect on hover, using `primary_color_hex`.

### Input Fields
- Darker than the surface background to create a "recessed" feel. 
- 1px border that turns `primary_color_hex` on focus with a tiny blue outer glow.

### Cards
- Background: `rgba(15, 23, 42, 0.6)`.
- Backdrop blur: 12px.
- Border: 1px solid `rgba(255, 255, 255, 0.1)`.
- Apply a slight gradient from top-left to bottom-right to simulate light hitting the corner.

### Trust Badges & Chips
- Use `label-caps` typography.
- Small, pill-shaped containers.
- For "Trust" signals, use `trust-green` for icons/accents to evoke safety.

### Lists
- Use horizontal dividers with a linear gradient (Transparent -> `surface-stroke` -> Transparent) for a sleek, modern separation.