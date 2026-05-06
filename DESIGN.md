---
name: Atelier Noir
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
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#ffe2ab'
  on-secondary: '#402d00'
  secondary-container: '#ffbf00'
  on-secondary-container: '#6d5000'
  tertiary: '#d0cdcd'
  on-tertiary: '#313030'
  tertiary-container: '#b4b2b2'
  on-tertiary-container: '#454544'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffdfa0'
  secondary-fixed-dim: '#fbbc00'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  h1:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The design system is rooted in the concept of "Culinary Noir"—a blend of high-end opulence and minimalist precision. It targets a discerning audience that values exclusivity, craftsmanship, and a sensory-first experience. The aesthetic is unapologetically premium, utilizing deep shadows and metallic highlights to create a digital environment that mirrors the atmosphere of a dimly lit, five-star dining room.

The chosen style is a hybrid of **Minimalism** and **Glassmorphism**. By stripping away unnecessary UI clutter, the design system allows high-contrast food photography to act as the primary visual driver. Translucent layers and subtle gold-tinted glows provide a sense of physical depth, making the interface feel tactile and expensive.

## Colors

This design system utilizes a high-contrast dark palette to evoke a sense of nighttime luxury. The foundation is built on **Deep Charcoal (#121212)** for primary backgrounds, while **Rich Black (#000000)** is reserved for depth transitions and image overlays.

**Luxurious Gold (#D4AF37)** serves as the primary brand anchor, used for iconography, thin borders, and decorative elements. **Warm Amber** is the functional accent, specifically reserved for Call to Action (CTA) buttons and critical highlights to ensure high visibility against the dark base. Text colors are strictly off-white or muted grey to maintain readability without breaking the dark-room aesthetic.

## Typography

The typographic strategy relies on a classic "Serif/Sans" pairing to communicate both heritage and modernity. **Noto Serif** is the voice of the brand, used for headlines and editorial pull-quotes. Its elegant, tapered strokes provide the "boutique" feel essential to a high-end establishment.

**Inter** provides the functional balance. Its neutral, geometric construction ensures that menu descriptions, pricing, and administrative labels remain legible even at small sizes on mobile devices. To maintain the premium feel, generous tracking (letter spacing) is applied to uppercase labels, creating a rhythmic, organized look common in luxury fashion and dining.

## Layout & Spacing

The design system follows a **Fixed Grid** model on desktop and a fluid model on mobile. Content is centered within a 1200px container to ensure focus and prevent visual fatigue. A 12-column grid is used for desktop layouts, while a 4-column grid is used for mobile.

Spacing is intentionally generous. The "Visual Silence" mentioned in the brand section is achieved through large vertical gaps (section-gap) between menu categories and featured items. This prevents the dark theme from feeling cramped or "heavy," allowing the user to focus on one dish or experience at a time.

## Elevation & Depth

In the design system, depth is not created with traditional dropshadows but through **Tonal Layering** and **Luminous Accents**. 

1.  **Base Layer:** The deepest level (#121212), used for the main page canvas.
2.  **Surface Layer:** Slightly lighter (#1A1A1A), used for cards and navigation bars.
3.  **Luminous Depth:** Cards and interactive containers feature a 1px inner border in muted gold or a semi-transparent white (0.1 opacity). 
4.  **Soft Glows:** Focused elements (like a selected menu item) may emit a very soft, diffused amber glow (blur radius 20px+, opacity 10-15%) to simulate the warm lighting of a restaurant booth.

## Shapes

The design system utilizes **Soft** roundedness. A radius of 0.25rem (4px) is applied to most UI components, including buttons and input fields. This subtle rounding removes the clinical edge of sharp corners while maintaining a structured, architectural look. 

For high-contrast photography containers, a slightly larger radius (0.5rem) is used to soften the impact of the images against the dark background. The intent is to avoid the "bubbly" look of consumer apps, favoring a more refined, tailored silhouette.

## Components

### Buttons
*   **Primary CTA:** Solid Amber background with Black text. This is the only high-saturation element to ensure users know exactly how to "Book a Table" or "Order."
*   **Secondary:** Outlined in Gold with Gold text. Used for "View Menu" or secondary explorations.

### Cards
Cards are the centerpiece of the design system. They feature a #1A1A1A background, a 1px subtle gold border, and a slight backdrop blur when hovering over images. Images within cards should use high-contrast photography with deep blacks to blend seamlessly into the UI.

### Navigation
A minimalist top-bar navigation. It should remain fixed and semi-transparent (Glassmorphic) with a backdrop blur to keep the focus on the content while providing a constant anchor.

### Photography Containers
Containers for food imagery should always be high-contrast. Use a subtle inner-shadow on images to create an "inset" look, making the food appear as if it is sitting within the interface rather than on top of it.

### Inputs & Selectors
Minimalist fields with only a bottom border in Gold or a full outline in #2A2A2A. Focus states should trigger a soft amber glow to guide the user's attention.