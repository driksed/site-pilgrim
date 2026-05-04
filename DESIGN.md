---
name: Artisanal Sanctuary
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#43474a'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#74787a'
  outline-variant: '#c4c7c9'
  surface-tint: '#576064'
  primary: '#192125'
  on-primary: '#ffffff'
  primary-container: '#2e363a'
  on-primary-container: '#969fa3'
  inverse-primary: '#bfc8cd'
  secondary: '#1c58c4'
  on-secondary: '#ffffff'
  secondary-container: '#5f8ffd'
  on-secondary-container: '#002868'
  tertiary: '#3c1200'
  on-tertiary: '#ffffff'
  tertiary-container: '#5d2202'
  on-tertiary-container: '#de875f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce4e9'
  primary-fixed-dim: '#bfc8cd'
  on-primary-fixed: '#151d20'
  on-primary-fixed-variant: '#40484c'
  secondary-fixed: '#dae2ff'
  secondary-fixed-dim: '#b1c5ff'
  on-secondary-fixed: '#001946'
  on-secondary-fixed-variant: '#00419f'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#753413'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  headline-xl:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Epilogue
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Epilogue
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Epilogue
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin: 32px
---

## Brand & Style

The design system is rooted in the "Slow Life" philosophy, capturing the essence of a sun-drenched French alleyway where community and craft intersect. It targets an audience that values authenticity, sustainability, and the tactile nature of physical goods. The emotional response is one of calm, warmth, and discovery—akin to stepping off a cobblestone street into a quiet, botanical-filled sanctuary.

The visual style is **Tactile / Artisanal**. It rejects the sterile perfection of modern digital interfaces in favor of subtle imperfections and physical metaphors. It balances the "rustic" (unrefined textures, hand-drawn flourishes) with the "refined" (structured typography, deliberate whitespace) to ensure the experience feels premium yet approachable.

## Colors

The palette is derived directly from the physical storefront and its surroundings. The base of the experience relies on a warm, paper-like neutral to evoke an organic, non-digital feel.

- **Primary (Deep Charcoal):** Inspired by the shop front and chalkboards. Used for high-contrast typography and structural elements.
- **Secondary (Vibrant Blue):** Drawn from the iconic cafe chairs. This is the "soul" of the brand, used for primary actions and highlights to create a sense of energy.
- **Tertiary (Terracotta):** Representing wood tones and ceramic pots. Used for secondary accents and to bring warmth to the UI.
- **Botanical Green:** A supporting color used for success states and organic flourishes, reflecting the plant life within the concept store.

## Typography

This design system employs a sophisticated contrast between editorial tradition and modern geometry. 

**Newsreader** serves as the "voice" of the store, mimicking the fluid, organic lines of hand-lettered chalkboards. It should be used for all storytelling elements and major headings. **Epilogue** provides the functional structure, offering a clean, contemporary sans-serif that ensures legibility for menus, product descriptions, and navigational elements. 

To maintain the artisanal feel, use italicized Newsreader for subheaders to mimic the personality of a handwritten note.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model on desktop to mimic the structured yet cozy arrangement of a cafe. Content is centered with generous outer margins to focus the eye, while mobile layouts use fluid containers with a minimum of 20px side padding.

Spacing is intentionally "breathable" (8px base unit). Rather than cramming information, the system favors large gutters and section breaks to encourage a "Slow Life" browsing pace. Use asymmetrical spacing in image galleries to replicate the eclectic, curated feel of the concept store's shelves.

## Elevation & Depth

Visual hierarchy is established through **Tonal Layers** and **Ambient Shadows**. The design system avoids harsh, "floating" elevations in favor of a grounded, physical feel.

- **Base Layer:** The Neutral color (#F9F7F2), often given a subtle paper-grain texture.
- **Surface Layer:** White or slightly tinted cards that appear to sit just above the base.
- **Shadows:** Use extra-diffused, low-opacity shadows (Opacity: 4-8%) with a slight tint of the Primary color. This mimics the soft, ambient light found in a stone-walled shop.
- **Interactive Depth:** When hovered, elements should not significantly lift; instead, use a subtle shift in background tone or a thin, hand-drawn-style border to indicate focus.

## Shapes

The shape language is **Rounded**, reflecting the soft edges of handmade ceramics and weathered wooden furniture.

Standard UI containers use a 0.5rem radius, while larger cards or feature sections use 1rem or 1.5rem to feel more inviting. Botanical illustrations should be used as "breakout" elements—clipping through borders or sitting behind text—to disrupt the rigid grid with organic forms. Avoid sharp corners entirely to maintain the approachable, community-oriented personality.

## Components

- **Buttons:** Primary buttons use the Vibrant Blue with white text. Secondary buttons utilize the Deep Charcoal with a "slate" feel. Use a slightly larger horizontal padding to give them a sturdy, physical presence.
- **Cards:** Cards should feel like heavy cardstock. Apply a very subtle paper texture overlay and a 1px border in a slightly darker neutral tone.
- **Chips/Tags:** Used for "Vegan," "Local," or "Handmade" labels. These should have a hand-drawn border style or a solid Terracotta background with Newsreader typography.
- **Inputs:** Text fields should resemble the lines on a notepad. Use a bottom-only border in Deep Charcoal for a minimalist, non-intrusive look.
- **Botanical Icons:** Use thin-stroke line art for icons (leaf, coffee bean, sun, ceramic pot). These icons should look hand-etched rather than digitally perfect.
- **Menu Lists:** Replicate the chalkboard menu layout for food items—Price and Item name separated by a dotted leader line, using Epilogue for the price and Newsreader for the title.