---
name: Sleek Tech Professional
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#434655'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#5c5f60'
  on-secondary: '#ffffff'
  secondary-container: '#dee0e2'
  on-secondary-container: '#606365'
  tertiary: '#525558'
  on-tertiary: '#ffffff'
  tertiary-container: '#6a6d71'
  on-tertiary-container: '#eef0f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#e1e2e4'
  secondary-fixed-dim: '#c5c6c8'
  on-secondary-fixed: '#191c1e'
  on-secondary-fixed-variant: '#444749'
  tertiary-fixed: '#e0e2e6'
  tertiary-fixed-dim: '#c4c7ca'
  on-tertiary-fixed: '#191c1f'
  on-tertiary-fixed-variant: '#44474a'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  headline-display:
    fontFamily: Noto Sans KR
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Sans KR
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Noto Sans KR
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Sans KR
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Noto Sans KR
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Noto Sans KR
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Noto Sans KR
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 900px
  section-padding: 80px
  gutter: 24px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system focuses on a **Sleek Tech Professional** aesthetic, tailored for an AI-driven educational environment. The target audience includes students and professionals who value precision, efficiency, and modern technology. 

The visual style is a blend of **Corporate Modern** and **Minimalism**. It utilizes expansive white space, a strictly organized 900px centered layout, and photorealistic imagery to establish high credibility. The interface should feel authoritative yet accessible, using technical light grays to provide subtle depth without cluttering the user experience. The emotional goal is to evoke a sense of confidence, clarity, and "future-proof" innovation.

## Colors
The palette is rooted in technical precision. 
- **Primary Blue (#2563eb):** Used for primary actions, progress indicators, and key branding elements.
- **Dark Ink (#111827):** Reserved for headings and body text to ensure maximum legibility and a premium feel.
- **Technical Grays:** The background shifts between **White (#ffffff)** and **Light Gray (#f3f4f6)** to delineate sections. 
- **Accents:** Secondary grays are used for borders, dividers, and disabled states to maintain a low-noise environment.

## Typography
The system uses **Noto Sans KR** exclusively to maintain consistency with the product's technical identity. 

Headlines are "Giant" and "Impactful," utilizing heavy weights and tight letter-spacing to command attention on the landing page. Body text prioritizes high contrast against the light background, using generous line heights (1.6) to ensure long-form content, such as feature descriptions or roadmaps, remains readable. Labels use uppercase styling and increased letter spacing to create a distinct technical "data-tag" appearance.

## Layout & Spacing
This design system employs a **Fixed Grid** philosophy. The core content container is strictly limited to **900px** and centered on the viewport. This constraint creates an editorial, high-end feel that prevents information density from becoming overwhelming.

- **Vertical Rhythm:** Sections are separated by a consistent 80px padding to allow the layout to breathe.
- **Mobile Adaptation:** At breakpoints below 900px, the layout transitions to a fluid model with 20px side margins, maintaining the same vertical rhythm and stacking components vertically.

## Elevation & Depth
To maintain a "Sleek Tech" look, this design system avoids heavy drop shadows. Instead, it uses:
- **Tonal Layers:** Using the light gray background (#f3f4f6) to separate cards or section blocks from the white background.
- **Low-Contrast Outlines:** Components like cards or input fields use a subtle 1px border (#e5e7eb).
- **Subtle Ambient Shadows:** Only for high-conversion floating elements (like the primary CTA button or sticky nav), using a very soft, diffused shadow (0px 4px 20px) with 5% opacity of the neutral ink color.

## Shapes
The shape language is **Soft (0.25rem)**. This subtle rounding provides a modern, friendly touch without sacrificing the professional, organized grid feel. Larger components like cards or hero images may use **rounded-lg (0.5rem)** to emphasize their containment, while buttons remain sharp enough to feel "technical."

## Components
- **Primary Buttons:** Large, high-conversion blocks using the primary tech blue. Typography should be bold and centered. Use 0.5rem (rounded-lg) for these to make them feel "clickable" and prominent.
- **Accordions (FAQ):** Minimalist style with a 1px bottom border only. Use a simple plus/minus or chevron icon in primary blue to indicate state.
- **Timelines (Roadmap):** A vertical 2px gray line with primary blue nodes. Each node should be accompanied by a date/title in the label-sm style and description in body-md.
- **Cards:** White background on the light gray section background. Subtle borders (no shadows) and consistent 32px internal padding.
- **Inputs:** Clean fields with light gray fills that turn white on focus, highlighted by a 2px primary blue border.