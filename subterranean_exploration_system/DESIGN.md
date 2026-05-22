---
name: Subterranean Exploration System
colors:
  surface: '#fcf9f5'
  surface-dim: '#dcdad6'
  surface-bright: '#fcf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ef'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e4'
  surface-container-highest: '#e5e2de'
  on-surface: '#1c1c19'
  on-surface-variant: '#414844'
  inverse-surface: '#31302e'
  inverse-on-surface: '#f3f0ec'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#7c5640'
  on-secondary: '#ffffff'
  secondary-container: '#ffcdb1'
  on-secondary-container: '#7a553f'
  tertiary: '#252626'
  on-tertiary: '#ffffff'
  tertiary-container: '#3b3c3c'
  on-tertiary-container: '#a7a6a6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#ffdbc9'
  secondary-fixed-dim: '#edbca1'
  on-secondary-fixed: '#2f1504'
  on-secondary-fixed-variant: '#613f2a'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#fcf9f5'
  on-background: '#1c1c19'
  surface-variant: '#e5e2de'
typography:
  display-lg:
    fontFamily: Chivo
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Chivo
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Chivo
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Chivo
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The brand personality is **Rugged Professionalism**. It balances the raw, tactile adventure of cave exploration with the reliability and safety expected from a premier tourist destination. The goal is to evoke a sense of awe and discovery while maintaining high accessibility standards for users who may be viewing the interface in varying outdoor lighting conditions.

The design style is a hybrid of **Modern Minimalism** and **Tactile Ruggedness**. We utilize generous whitespace and clean layouts to ensure information density remains low and readable, but we ground the interface with textures and edge treatments that mimic the organic, sharp, and layered nature of geological formations. The interface should feel like a high-end field guide: functional, durable, and authoritative.

## Colors

The palette is derived directly from the Okbot Cave environment. 
- **Primary (Forest Green):** Represents the lush entrance and the life surrounding the cave. Used for primary actions and brand presence.
- **Secondary (Earthy Brown):** Represents the trail and the earth. Used for accent elements, wayfinding, and secondary buttons.
- **Tertiary (Cave Grey):** A deep, cool grey used for text and structural elements, providing high contrast against light backgrounds.
- **Neutral (Sandstone):** A warm, off-white used for backgrounds to reduce eye strain compared to pure white, especially in outdoor settings.

Accessibility is paramount; all color pairings for text must meet WCAG AA standards at minimum, specifically focusing on contrast ratios for users in high-glare environments.

## Typography

This design system prioritizes legibility above all else. 
- **Chivo** is used for headlines. Its sharp, confident terminals evoke a modern and professional feel, echoing the precision required in caving.
- **Atkinson Hyperlegible Next** is used for all body and UI text. It was specifically designed to increase character recognition, making it the ideal choice for tourists reading information on mobile devices in bright sunlight or low-light cave entrances.

Scale the typography conservatively on mobile to ensure line lengths remain comfortable and headlines do not break awkwardly. Use uppercase labels for metadata and small captions to provide clear visual hierarchy.

## Layout & Spacing

The layout follows a **fluid grid** model with a maximum content width of 1280px for desktop. 
- **Desktop:** 12-column grid with 24px gutters.
- **Tablet:** 8-column grid with 24px gutters.
- **Mobile:** 4-column grid with 16px gutters.

Spacing follows an 8px rhythmic scale. Use `lg` and `xl` spacing for vertical section separation to allow the "nature" of the imagery to breathe. Elements should feel intentionally placed, avoiding clutter to reflect the vastness of the cave environment. Padding within components (like cards and buttons) should be generous to ensure easy touch targets for users who may be active or wearing light gear.

## Elevation & Depth

To maintain a "modern yet rugged" feel, the design system avoids soft, floating shadows. Instead, it uses **tonal layers** and **low-contrast outlines**.

1.  **Surface Tiers:** Use subtle shifts in background color (e.g., Sandstone to a slightly darker Earthy Tint) to define hierarchy.
2.  **Hard Edges:** Shadows, when used, are "crisp" and low-offset, mimicking the sharp shadows cast by rock under a headlamp.
3.  **Outlines:** Use 1px borders in Cave Grey at 15% opacity to define card boundaries and input fields, ensuring structure without adding digital "bulk."
4.  **Scrims:** When text overlays imagery, use a 40% Cave Grey linear gradient at the base to ensure high contrast and legibility.

## Shapes

The shape language is **Soft (0.25rem)**. This choice reflects the intersection of man-made precision and natural erosion. 
- **Buttons and Inputs:** Use a 4px corner radius to feel sturdy and structural.
- **Cards and Modals:** Use `rounded-lg` (8px) to soften the large surface areas, making the professional interface feel approachable.
- **Icons:** Should use a consistent 2px stroke weight with slightly rounded joins to match the typography's character.

## Components

- **Buttons:** Primary buttons are solid Forest Green with White text. Secondary buttons use an Earthy Brown outline with a matching label. Both must have a minimum height of 48px for outdoor accessibility.
- **Chips:** Used for "Difficulty Levels" or "Tour Types." Use high-contrast background colors (e.g., a "Hard" tour uses a dark Grey chip with white text).
- **Lists:** Use Cave Grey dividers (1px, 10% opacity) between list items. Icons in lists should be earth-toned to guide the eye.
- **Inputs:** Text fields feature a 1px border. On focus, the border thickens to 2px in Forest Green. Labels are always visible (never placeholder-only) to maintain accessibility.
- **Cards:** Features a thin border and no shadow. Content is padded by 24px (`md` spacing). Use for "Tour Packages" or "Safety Tips."
- **Status Indicators:** Use vibrant Forest Green for "Open/Available" and a deep burnt orange for "Closed/Limited Access" to ensure visibility against the neutral background.
- **Weather/Condition Widget:** A unique component for this system, using monochromatic icons to show cave temperature and moisture levels, styled with the same rugged outline as other cards.