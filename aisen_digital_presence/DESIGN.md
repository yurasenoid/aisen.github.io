---
name: Aisen Digital Presence
colors:
  surface: '#fdf7ff'
  surface-dim: '#ded8e0'
  surface-bright: '#fdf7ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f2fa'
  surface-container: '#f2ecf4'
  surface-container-high: '#ece6ee'
  surface-container-highest: '#e6e0e9'
  on-surface: '#1d1b20'
  on-surface-variant: '#494551'
  inverse-surface: '#322f35'
  inverse-on-surface: '#f5eff7'
  outline: '#7a7582'
  outline-variant: '#cbc4d2'
  surface-tint: '#6750a4'
  primary: '#4f378a'
  on-primary: '#ffffff'
  primary-container: '#6750a4'
  on-primary-container: '#e0d2ff'
  inverse-primary: '#cfbcff'
  secondary: '#63597c'
  on-secondary: '#ffffff'
  secondary-container: '#e1d4fd'
  on-secondary-container: '#645a7d'
  tertiary: '#765b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c9a74d'
  on-tertiary-container: '#503d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#cfbcff'
  on-primary-fixed: '#22005d'
  on-primary-fixed-variant: '#4f378a'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#cdc0e9'
  on-secondary-fixed: '#1f1635'
  on-secondary-fixed-variant: '#4b4263'
  tertiary-fixed: '#ffdf93'
  tertiary-fixed-dim: '#e7c365'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#594400'
  background: '#fdf7ff'
  on-background: '#1d1b20'
  surface-variant: '#e6e0e9'
typography:
  h1:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  h3:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Manrope
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
  container-max: 1140px
  gutter: 24px
  margin-page: 40px
  section-gap: 120px
---

## Brand & Style

This design system blends the soulful nostalgia of vintage editorial design with the functional clarity of modern minimalism. It is designed for a personal brand that values craft, intentionality, and quiet sophistication. The visual language avoids the loud trends of the current web, opting instead for a "digital heirloom" aesthetic.

The style is primarily **Minimalist**, leaning on heavy whitespace and high-quality typography to communicate value. It incorporates elements of **Corporate Modern** for structural reliability, but softens the edges with organic tones and tactile, low-contrast borders. The goal is to evoke a sense of calm and permanence, making the user feel as though they are browsing a beautifully curated physical portfolio or a modern literary journal.

## Colors

The palette is rooted in warm, organic neutrals to avoid the clinical feel of pure white. 

- **Primary Background:** A soft, warm cream (#FDFBF7) that mimics premium unbleached paper.
- **Primary Text:** A deep espresso (#2D2926) instead of pure black, providing high contrast that is easier on the eyes and feels more "ink-like."
- **Accent Color:** A muted Sage Green (#8A9A5B). This color should be used sparingly for calls to action, active states, and subtle decorative elements to maintain the vintage botanical feel.
- **Secondary Neutral:** A slightly darker beige used for dividers, borders, and subtle backgrounds to create depth without introducing new hues.

## Typography

This design system uses a high-contrast typographic pairing to bridge the gap between vintage and modern.

**Newsreader** is the primary serif for all headings. It brings a literary, authoritative, and slightly weathered feel to the design. For large displays (H1), use a tighter letter-spacing to create a bespoke editorial look.

**Manrope** serves as the functional workhorse for body text and labels. Its geometric yet warm construction ensures legibility across all devices. Use the "Label-Caps" style for navigation items, tags, and small sub-headers to provide a clean, modern counter-balance to the serif headlines.

## Layout & Spacing

The layout follows a **Fixed Grid** model centered on the page, utilizing a 12-column system. To reinforce the minimalist aesthetic, the design system relies on "generous breathing room"—using large section gaps (120px+) to separate distinct thoughts or portfolio pieces.

Spacing is based on an 8px rhythmic scale. Elements should be aligned with intent; use asymmetrical layouts for portfolio showcases to create a more dynamic, gallery-like experience, while keeping text-heavy sections strictly aligned to a central, readable column.

## Elevation & Depth

This system avoids heavy shadows and floating effects to maintain its flat, paper-like quality. Depth is achieved through **Low-contrast outlines** and **Tonal layers**.

- **Borders:** Use 1px solid strokes in the "Secondary Neutral" color to define cards and input fields.
- **Tonal Shifts:** Instead of lifting an object with a shadow, use a subtle background color shift (e.g., moving from the primary cream to a slightly cooler beige) to indicate a nested container.
- **Interactions:** On hover, a "lift" can be simulated by changing the border color to the Sage Green accent or by a very slight, sharp 2px offset "hard shadow" to mimic vintage print layering.

## Shapes

The shape language is **Soft**. While sharp corners feel too aggressive and fully rounded "pill" shapes feel too tech-focused, a subtle radius (4px to 8px) provides a hand-trimmed, organic feel. 

Buttons and input fields should utilize the base `rounded` (4px) setting. Larger containers like portfolio cards may use `rounded-lg` (8px) to feel more substantial and approachable.

## Components

### Sticky Navigation
The navigation bar should be a "glass" or solid cream strip at the top of the viewport. Use a blur effect if translucent, but keep the border bottom subtle. Links use the `label-caps` typography style.

### Portfolio Cards
Cards should be minimal, consisting of a full-bleed image with a 1px border. The project title (Serif) and category (Sans-serif caps) should sit below the image rather than overlaying it, maintaining an editorial layout.

### Buttons
- **Primary:** Solid Sage Green background with Espresso or White text.
- **Secondary:** Outlined with a 1px stroke of the text color.
- Use a slight transition on hover that shifts the background color or underlines the text link.

### Forms
Input fields are simple underlines or 1px stroke boxes. Labels should always be visible (not just placeholders) using the `label-caps` style for maximum clarity.

### Lists
Use custom bullets for lists—small Sage Green squares or subtle "en-dashes" to maintain the vintage typewriter or architectural drawing aesthetic.