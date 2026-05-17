---
name: Institutional Editorial System
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#43474e'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#455f88'
  primary: '#002045'
  on-primary: '#ffffff'
  primary-container: '#1a365d'
  on-primary-container: '#86a0cd'
  inverse-primary: '#adc7f7'
  secondary: '#1960a3'
  on-secondary: '#ffffff'
  secondary-container: '#7db6ff'
  on-secondary-container: '#00477f'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cba72f'
  on-tertiary-container: '#4e3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#adc7f7'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#d3e4ff'
  secondary-fixed-dim: '#a2c9ff'
  on-secondary-fixed: '#001c38'
  on-secondary-fixed-variant: '#004881'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  subhead-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  column-gap: 24px
---

## Brand & Style
The design system is engineered to bridge the gap between academic prestige and youthful energy for a modern school magazine. The aesthetic is **Corporate / Modern** with a strong **Editorial** influence, prioritizing clarity, authority, and readability. 

The brand personality is "The Distinguished Academic Explorer"—combining the structured reliability of a municipal institution with the vibrant, forward-looking perspective of its students. The UI should evoke a sense of trust and pride among authorities while remaining accessible and engaging for the student body. This is achieved through generous whitespace, high-contrast typography, and a disciplined color application that mirrors a high-end professional newspaper.

## Colors
The palette is rooted in institutional stability. **Primary Dark Blue** serves as the anchor for headers and structural elements, symbolizing discipline and heritage. **Secondary Medium Blue** provides depth and is used for interactive elements and sub-sections. 

The **Accent Gold** is used sparingly for highlights, awards, and "Editor's Picks," adding an elegant, premium touch. The background strategy relies on **White** and **Light Gray** to create a clean, "breathable" canvas that allows photography and long-form text to take center stage without visual fatigue.

## Typography
Typography is the cornerstone of this design system. We use **Montserrat** for primary headlines to convey strength and modernity. For subheadings and navigational elements, **Plus Jakarta Sans** provides a softer, more welcoming geometric touch that aids in scannability.

**Open Sans** is the workhorse for all body content, chosen for its exceptional legibility in both digital and print-like layouts. For the A5 format, we maintain a strict hierarchy where font sizes are slightly larger than standard web specs to accommodate a "reading-first" experience. Tracking (letter spacing) is tightened for large headlines and slightly opened for small labels to ensure maximum clarity.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy optimized for the A5 magazine aspect ratio. We utilize a 12-column grid system for maximum flexibility, though most article content should be constrained to an 8-column center block or a 2-column "asymmetric" layout (66% content, 33% sidebar).

Spacing is governed by an 8px rhythmic scale. Margins are generous to simulate the feel of a printed journal. On mobile devices, the grid collapses to a single column with 16px side margins, while desktop views utilize the full 12-column span with 32px external margins to maintain the "Modern Editorial" look. Whitespace should be used intentionally between sections to signal a transition in topic or tone.

## Elevation & Depth
In keeping with an elegant and professional aesthetic, the design system avoids heavy shadows. Depth is primarily communicated through **Tonal Layers** and **Low-contrast Outlines**. 

- **Level 0 (Base):** White or Light Gray background.
- **Level 1 (Cards/Sections):** White surfaces with a 1px border in a slightly darker gray or a very subtle, highly diffused ambient shadow (Blur 10px, Opacity 4%).
- **Level 2 (Modals/Pop-overs):** Soft shadows with a Primary Blue tint to maintain brand cohesion.

This "Flat-Plus" approach ensures that the magazine feels modern and tactile without the "heaviness" of traditional skeuomorphism.

## Shapes
The shape language is **Soft**. We use a 0.25rem (4px) corner radius for most UI components (buttons, input fields, small cards). This subtle rounding takes the edge off the institutional rigidity without becoming overly playful or "bubbly."

Larger containers or featured images may use `rounded-lg` (8px) to draw the eye. Interactive elements should maintain consistent corner radii to reinforce the professional and structured nature of the publication.

## Components
### Buttons
Buttons use a solid **Primary Blue** fill with white **Plus Jakarta Sans** text for high-priority actions. Secondary buttons use a transparent background with a 1px Primary Blue border.

### Cards
Article cards are the primary vessel for content. They feature a top-aligned image, followed by a **Label-sm** category (in Secondary Blue or Gold), a **Headline-md**, and a short excerpt. The card should have a 1px light gray border and no shadow by default, gaining a subtle shadow on hover.

### Inputs
Search and form fields use a Light Gray fill with a bottom-border only or a subtle 1px outline, emphasizing the "academic" and "minimalist" aesthetic.

### Masthead & Headers
The main magazine header should feature the institution's name in **Montserrat Bold** with high contrast. Use a vertical divider and the **Gold accent** to separate the magazine title from the current issue/date.

### Pull Quotes
A signature magazine component. Pull quotes should be styled in **Montserrat**, centered, with a larger font size and a Gold-colored border-left (4px width) to differentiate them from standard body text.