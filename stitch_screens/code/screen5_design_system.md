---
name: Obsidian Edge
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
  on-surface-variant: '#bcc9c6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#879390'
  outline-variant: '#3d4947'
  surface-tint: '#6fd8c8'
  primary: '#6fd8c8'
  on-primary: '#003731'
  primary-container: '#30a193'
  on-primary-container: '#00302a'
  inverse-primary: '#006a60'
  secondary: '#abcbdb'
  on-secondary: '#123441'
  secondary-container: '#2b4b58'
  on-secondary-container: '#99baca'
  tertiary: '#ffb59e'
  on-tertiary: '#5a1c06'
  tertiary-container: '#d3795b'
  on-tertiary-container: '#501502'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#8cf5e4'
  primary-fixed-dim: '#6fd8c8'
  on-primary-fixed: '#00201c'
  on-primary-fixed-variant: '#005048'
  secondary-fixed: '#c6e8f8'
  secondary-fixed-dim: '#abcbdb'
  on-secondary-fixed: '#001f29'
  on-secondary-fixed-variant: '#2b4b58'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59e'
  on-tertiary-fixed: '#390b00'
  on-tertiary-fixed-variant: '#77321a'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-lg:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
The design system embodies a high-performance, technical aesthetic tailored for developer tools and sophisticated SaaS environments. The brand personality is precise, focused, and quietly powerful. It targets power users who value efficiency and deep focus over decorative flair.

The visual style is a fusion of **Minimalism** and **Geist-inspired Technicality**. It leverages a deep monochromatic foundation punctuated by a single, vibrant turquoise accent. The interface feels "engineered" rather than "decorated," utilizing rigorous grid alignment and deliberate whitespace to manage cognitive load. The emotional response is one of calm control and professional-grade reliability.

## Colors
The palette is rooted in an "Obsidian" dark theme, utilizing a layered approach to blacks and grays to create environmental depth without relying on heavy shadows.

- **Primary (#2a9d8f):** A focused turquoise blue used exclusively for primary actions, active states, and critical information highlights.
- **Secondary (#264653):** A muted navy-teal used for subtle background fills on secondary interactive elements.
- **Surface & Neutral:** The background is a true-black (#121212) to maximize OLED efficiency and contrast. Surface containers use a slightly elevated charcoal (#1e1e1e).
- **Accents:** Use success (emerald), warning (amber), and error (crimson) minimally, ensuring they are desaturated to maintain the dark-mode harmony.

## Typography
Typography is the core structural element. **Geist** provides a clean, neutral sans-serif foundation for most interface elements, ensuring readability and a modern technical feel. 

**JetBrains Mono** is utilized for labels, metadata, and code snippets to reinforce the developer-centric aesthetic. All typography should maintain high contrast against the dark background. Use "Body-md" for general reading and "Label-sm" for all caps metadata.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop and a fluid single-column approach for mobile. 

- **Navigation:** The system moves away from bottom bars and complex sidebars in favor of a clean, single-page flow or a top-aligned "minimalist utility bar." 
- **Structure:** Use a 12-column grid on desktop (max-width 1200px) and a single-column layout on mobile. 
- **Rhythm:** All spacing is based on a 4px baseline unit. Prefer generous padding within cards (24px) to ensure the dark theme feels airy rather than cramped. Elements should be grouped logically using "proximity over borders."

## Elevation & Depth
In this design system, depth is communicated through **Tonal Layering** and **Low-Contrast Outlines** rather than physical shadows.

- **Level 0 (Background):** #121212 (The void).
- **Level 1 (Cards/Sections):** #1e1e1e with a 1px border of #333333.
- **Level 2 (Modals/Popovers):** #252525 with a slightly brighter border (#444444).
- **Interactions:** Use subtle inner-glows (0.5px white at 10% opacity) on primary buttons to suggest a slight tactile lift without breaking the minimalist plane.

## Shapes
The shape language is "Soft-Technical." Elements use a subtle **0.25rem (4px)** corner radius. This creates a precision-engineered look that feels modern but avoids the aggressive sharpness of pure brutalism.

- **Small elements (Buttons/Inputs):** 4px (Soft).
- **Large elements (Cards/Containers):** 8px (Rounded-lg).
- **Interactive States:** Maintain consistent radii across all states (hover, active, focus).

## Components
- **Buttons:** Primary buttons use a solid turquoise (#2a9d8f) background with black text for maximum legibility. Secondary buttons are outlined with #333333.
- **Inputs:** Fields are dark (#1e1e1e) with a subtle bottom border or 1px perimeter border. Focus states must glow with a 2px turquoise outer stroke.
- **Cards:** No shadows. Use tonal separation and a fine 1px border. Content inside cards should follow the 24px internal padding rule.
- **Chips/Badges:** Use JetBrains Mono for text. Backgrounds should be low-opacity versions of the primary color (e.g., turquoise at 15% opacity).
- **Navigation:** A single-page header containing only essential actions. Use a "Breadcrumb + Action" pattern to keep the UI clean and focused on the current task.
- **Data Visualization:** Use turquoise as the primary data point color, supported by neutral grays for secondary data sets.
