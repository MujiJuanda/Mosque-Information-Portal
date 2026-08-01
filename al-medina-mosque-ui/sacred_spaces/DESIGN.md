---
name: Sacred Spaces
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#404944'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#707974'
  outline-variant: '#bfc9c3'
  surface-tint: '#2b6954'
  primary: '#003527'
  on-primary: '#ffffff'
  primary-container: '#064e3b'
  on-primary-container: '#80bea6'
  inverse-primary: '#95d3ba'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#003623'
  on-tertiary: '#ffffff'
  tertiary-container: '#004f34'
  on-tertiary-container: '#31c98f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b0f0d6'
  primary-fixed-dim: '#95d3ba'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#0b513d'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  headline-xl:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Libre Caslon Text
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
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 24px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is built for a contemporary Islamic context, focusing on serenity, reverence, and clarity. The brand personality is "Modern Spiritual"—combining the weight of tradition with the efficiency of modern technology. 

The aesthetic is **Minimalist** with a **Tactile** edge. It avoids visual clutter to keep the user focused on prayer times and community news. It utilizes subtle geometric patterns inspired by Islamic tiling (Girih) as background textures or divider elements. The emotional response should be one of peace (Sakinah) and focused attention, achieved through generous whitespace and a sophisticated, limited color palette.

## Colors

The palette is rooted in a deep Emerald Green, representing life and the Islamic tradition. Gold is used sparingly for accents, active states, and high-value indicators (like current prayer time).

- **Primary (Deep Emerald):** Used for headers, primary buttons, and critical branding elements.
- **Secondary (Gold):** Used for icons, decorative borders, and highlighting special events.
- **Surface (Soft Cream):** The main background color to reduce eye strain and provide a warmer feel than pure white.
- **Accent (Mint):** A lighter green used for success states and secondary call-to-actions.

## Typography

This design system uses a high-contrast pairing to bridge the gap between historical manuscripts and digital utility. 

**Libre Caslon Text** is used for all headlines. Its literary, refined character provides the necessary "authoritative" feel for religious content. **Plus Jakarta Sans** is used for all body text and UI labels; its soft, rounded terminals complement the organic nature of the emerald and gold palette while ensuring maximum legibility on mobile devices.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop (12 columns) and a **Fluid Grid** on mobile (4 columns). 

A strict 8px spacing rhythm is maintained. The layout philosophy emphasizes "Breathable Sanctity"—meaning internal margins within cards and containers are larger than standard utility apps to evoke a sense of calm. 

- **Mobile:** 24px side margins to create a "frame" around content.
- **Desktop:** Max content width of 1140px, centered.
- **Section Dividers:** Use thin 1px lines in 10% Emerald Green or subtle geometric pattern strips.

## Elevation & Depth

To maintain a clean and modern feel, the design system utilizes **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Surface Level:** The Soft Cream background.
- **Elevated Level (Cards):** Pure white background with a very soft, 1px border in Emerald-100.
- **Active State:** A subtle inner glow in Gold (#D4AF37) at 10% opacity can be used to signify selection.
- **Shadows:** Only used for floating action buttons or primary modals, using a highly diffused Emerald-tinted shadow (0px 10px 30px rgba(6, 78, 59, 0.08)).

## Shapes

The shape language is **Rounded**, reflecting the domes and arches found in sacred architecture. 

- **Standard Elements:** 0.5rem (8px) corner radius for input fields and small cards.
- **Large Containers:** 1rem (16px) for main content cards.
- **Interactive Elements:** Buttons use a fully rounded (Pill) shape to distinguish them from informational cards.
- **Iconography:** Contained within circular or "eight-pointed star" (Khatim) containers.

## Components

### Buttons
- **Primary:** Pill-shaped, Emerald Green background, White text.
- **Secondary:** Pill-shaped, Gold border, Gold text.
- **Tertiary:** Text-only in Emerald Green with a small Gold icon.

### Prayer Time Cards
Cards representing prayer times should use a white background. The "Active" prayer should feature a Gold left-border (4px width) and a subtle cream-to-white gradient to highlight the current time.

### Chips & Tags
Used for categories like "Hadith," "Community," or "Announcement." These should have a background of Emerald Green at 10% opacity with Emerald Green text.

### Inputs
Text fields are rectangular with 8px rounding, using the Soft Cream color for the fill to blend with the background, and a 1px Emerald-200 border that turns Gold on focus.

### Additional Components
- **Qibla Compass:** A circular component using Gold for the needle and Emerald for the cardinal points.
- **Pattern Dividers:** A component that renders a 40px tall repeating geometric pattern at 5% opacity to separate major sections.