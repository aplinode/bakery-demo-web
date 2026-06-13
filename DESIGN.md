---
name: Heritage Hearth
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
  on-surface-variant: '#4f453f'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#81756e'
  outline-variant: '#d2c4bc'
  surface-tint: '#705a4c'
  primary: '#26170c'
  on-primary: '#ffffff'
  primary-container: '#3d2b1f'
  on-primary-container: '#ac9181'
  inverse-primary: '#dec1af'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#20190e'
  on-tertiary: '#ffffff'
  tertiary-container: '#362e21'
  on-tertiary-container: '#a19584'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fbddca'
  primary-fixed-dim: '#dec1af'
  on-primary-fixed: '#28180d'
  on-primary-fixed-variant: '#574335'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#efe0cd'
  tertiary-fixed-dim: '#d2c4b2'
  on-tertiary-fixed: '#221a0f'
  on-tertiary-fixed-variant: '#4f4538'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style
The design system is anchored in the concept of "Artisanal Heritage"—fusing the warmth of a traditional Pakistani kitchen with the sophisticated precision of modern luxury patisserie. It targets a high-discerning clientele in urban Pakistan, evoking an emotional response of trust, comfort, and indulgence.

The visual style is **Minimalist / Corporate Modern** with **Tactile** accents. It prioritizes high-quality whitespace to allow commercial photography of the products to serve as the primary visual driver. The interface feels established and professional while maintaining a "family-friendly" warmth through soft color transitions and elegant serif flourishes. 

Adhering to strict cultural guidelines:
- Visual storytelling focuses exclusively on ingredients, the baking process, and the final product.
- Avoid any imagery containing human figures, tobacco, or restricted substances.
- Emphasize "Halal Excellence" through clean, transparent layouts and authoritative typography.

## Colors
The palette is inspired by the raw ingredients of high-end baking:
- **Primary (Chocolate Brown):** Used for primary text, deep-contrast backgrounds, and core branding elements to provide weight and authority.
- **Secondary (Soft Gold):** Reserved for "moments of luxury"—buttons, active states, call-to-action borders, and premium iconography.
- **Tertiary (Warm Beige):** Used for container backgrounds, card fills, and secondary sections to soften the transition between white and dark tones.
- **Neutral (Cream White):** The foundational canvas color, providing a clean, "flour-dusted" aesthetic that feels lighter and more premium than pure white.

## Typography
The typographic pairing reflects the "Heritage Hearth" philosophy. **Playfair Display** provides an editorial, high-end feel for titles and storytelling, while **Montserrat** ensures high readability for product descriptions, navigation, and the admin dashboard.

**Usage Rules:**
- **Serif (Playfair):** Use for all headings, product names, and "The Baker's Note" sections.
- **Sans-Serif (Montserrat):** Use for body copy, buttons, and data-heavy dashboard tables.
- **Letter Spacing:** Apply a slight positive tracking (+0.05em) to uppercase labels to enhance the premium feel.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to maintain an editorial, magazine-like structure. Elements are aligned to a 12-column grid with generous outer margins to emphasize the "Luxury" positioning.

- **Desktop:** 12-column grid, 24px gutters, 64px page margins.
- **Mobile:** Single column flow, 20px margins, with specific emphasis on vertical stacking for product cards.
- **Spacing Rhythm:** Use a base 8px unit. Major sections should be separated by `stack-lg` (64px) to ensure the layout never feels cluttered.

## Elevation & Depth
This design system avoids heavy drop shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**. 

Depth is achieved by:
1. **Layering:** Placing Cream White (#FDFBF7) cards on a Warm Beige (#F5E6D3) background.
2. **Gold Accents:** Using thin 1px Soft Gold (#C5A059) borders for active states or "Featured" items.
3. **Soft Ambient Shadows:** For floating elements like the WhatsApp button or Sticky Nav, use a very diffused shadow: `0 8px 30px rgba(61, 43, 31, 0.08)`. This adds lift without breaking the clean, minimalist aesthetic.

## Shapes
The shape language is **Soft (0.25rem - 0.75rem)**. This provides a gentle, welcoming feel suitable for a family-oriented brand while maintaining a professional, "sharper" edge compared to playful consumer brands.

- **Standard Buttons & Inputs:** 0.25rem (4px) corner radius.
- **Product Cards:** 0.5rem (8px) corner radius.
- **Dashboard Widgets:** 0.75rem (12px) corner radius for a more modern, organized look.

## Components
- **Product Cards:** Use a Cream White background with a subtle Warm Beige bottom-border. Images should be full-bleed at the top with a 1:1 aspect ratio. Text is centered with the price in Soft Gold.
- **Floating WhatsApp Button:** A circular button with a Soft Gold background and Primary Brown icon, positioned at the bottom right with a subtle ambient shadow.
- **Sticky Navigation:** A semi-transparent Cream White bar with a 1px bottom border in Warm Beige. Logo is centered; navigation links use `label-lg` typography.
- **Luxury Gallery Grid:** An asymmetrical grid alternating between large 2-column feature images and 1-column detail shots. No gutters between images to create a "tapestry" effect.
- **Admin Dashboard:** High-contrast white backgrounds, 1px Primary Brown borders for input fields, and Soft Gold for primary action buttons (e.g., "Add New Product").
- **Buttons:**
    - *Primary:* Solid Chocolate Brown with Cream White text.
    - *Secondary:* Ghost style with Soft Gold 1px border and Soft Gold text.