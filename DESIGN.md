---
name: Kinetic Developer Portfolio
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#bac9cc'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#849396'
  outline-variant: '#3b494c'
  surface-tint: '#00daf3'
  primary: '#c3f5ff'
  on-primary: '#00363d'
  primary-container: '#00e5ff'
  on-primary-container: '#00626e'
  inverse-primary: '#006875'
  secondary: '#bcc7de'
  on-secondary: '#263143'
  secondary-container: '#3e495d'
  on-secondary-container: '#aeb9d0'
  tertiary: '#e4edff'
  on-tertiary: '#213145'
  tertiary-container: '#c1d2ec'
  on-tertiary-container: '#4a5a70'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#9cf0ff'
  primary-fixed-dim: '#00daf3'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004f58'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 128px
---

## Brand & Style
The brand personality is **Precise, Technical, and Forward-Thinking**. It targets high-end tech recruiters and engineering managers who value both technical rigor and modern aesthetics. 

The design style is a blend of **Corporate Modern** and **Minimalism**, with subtle hints of **Glassmorphism** for depth. The interface utilizes a "Developer-First" aesthetic—clean lines, structured data, and high-quality typography—evoking the feeling of a high-performance code editor or a premium SaaS dashboard. The atmosphere is quiet and professional, allowing the work to be the primary focus while using vibrant electric accents to signal activity and innovation.

## Colors
The palette is rooted in a "Deep Space" theme. 
- **Primary (Electric Cyan):** Used sparingly for calls to action, active states, and critical highlights. It provides the "tech" energy.
- **Secondary (Slate Blue):** Used for card backgrounds and secondary UI elements to provide subtle contrast against the background.
- **Neutral (Midnight):** The primary background color. It reduces eye strain and provides a premium, "IDE-like" backdrop.
- **Success/Warning/Error:** Standard utility colors should be desaturated to match the dark theme, using emerald, amber, and rose tones respectively.

## Typography
The typography system uses a tri-font approach to define hierarchy:
- **Hanken Grotesk** handles the heavy lifting for displays and headers, offering a sharp, contemporary feel.
- **Inter** provides maximum readability for long-form project descriptions and experience details.
- **JetBrains Mono** is used for metadata, tags, and technical labels to reinforce the developer identity.

For mobile, scale down display sizes significantly to maintain readability without excessive scrolling. Use optical sizing where available to keep the "Inter" body text crisp.

## Layout & Spacing
The system employs a **Fluid Grid** model with a strictly enforced 8px base unit. 
- **Desktop:** 12-column grid with 24px gutters. Content is centered with a max-width of 1200px.
- **Tablet:** 8-column grid with 20px gutters.
- **Mobile:** 4-column grid with 16px gutters and 16px side margins.

Spacing between major sections should be generous (128px) to allow the technical content to "breathe" and create a sense of premium intentionality. Use consistent internal padding for cards (24px or 32px) to maintain a structured, mathematical rhythm.

## Elevation & Depth
Depth is achieved through **Tonal Layers** and **Subtle Outlines** rather than heavy shadows.
- **Level 0 (Background):** Midnight (#0F172A).
- **Level 1 (Cards/Surface):** Slate Blue (#1E293B) with a 1px solid border (#334155).
- **Level 2 (Hover/Active):** Slightly lighter slate with a Primary (Cyan) glow effect.

Use a 10% opacity white inner-stroke on primary cards to simulate a glass-like edge. Backdrop blurs (12px to 20px) should be applied to sticky navigation bars to maintain context of the underlying content.

## Shapes
The shape language is **Soft (0.25rem)**. This provides a professional, "architectural" feel that isn't as aggressive as sharp corners but remains more serious than fully rounded/pill shapes. 
- Standard buttons and input fields use 4px (0.25rem).
- Project cards and large containers use 8px (0.5rem).
- Status indicators and "Skill Tags" may use pill-shaping (100px) to distinguish them from interactive buttons.

## Components
- **Buttons:** Primary buttons use a solid Electric Cyan fill with black text for maximum contrast. Secondary buttons use a ghost style (outline) with cyan text.
- **Project Cards:** Feature a top-aligned image, followed by JetBrains Mono tags for technology stacks, and an Hanken Grotesk title. On hover, the border color shifts to the primary accent.
- **Chips/Tags:** Small, low-contrast capsules (Secondary color background) used for languages (C++, Python). Use mono fonts for these.
- **Inputs:** Dark backgrounds with a 1px border that illuminates in Electric Cyan upon focus.
- **Timeline:** A vertical line component for Education and Experience, using a Primary Cyan dot for the current/most recent item and Grey for historical items.
- **Code Snippets:** Syntax-highlighted blocks using a "One Dark" or "Night Owl" inspired theme to match the system's palette.