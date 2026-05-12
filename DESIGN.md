---
name: Industrial Maritime Identity
colors:
  surface: '#f7f9ff'
  surface-dim: '#d7dadf'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f9'
  surface-container: '#ebeef3'
  surface-container-high: '#e5e8ee'
  surface-container-highest: '#e0e3e8'
  on-surface: '#181c20'
  on-surface-variant: '#44474e'
  inverse-surface: '#2d3135'
  inverse-on-surface: '#eef1f6'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#465f88'
  primary: '#000a1e'
  on-primary: '#ffffff'
  primary-container: '#002147'
  on-primary-container: '#708ab5'
  inverse-primary: '#aec7f6'
  secondary: '#115cb9'
  on-secondary: '#ffffff'
  secondary-container: '#659dfe'
  on-secondary-container: '#003370'
  tertiary: '#090b0c'
  on-tertiary: '#ffffff'
  tertiary-container: '#1f2223'
  on-tertiary-container: '#87898a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#aec7f6'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#d7e2ff'
  secondary-fixed-dim: '#acc7ff'
  on-secondary-fixed: '#001a40'
  on-secondary-fixed-variant: '#004491'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#f7f9ff'
  on-background: '#181c20'
  surface-variant: '#e0e3e8'
typography:
  display:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  headline-sm:
    fontFamily: Montserrat
    fontSize: 20px
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
    lineHeight: '1.2'
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.3'
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
  margin-desktop: 64px
  margin-mobile: 16px
---

## Brand & Style

The visual identity of this design system is rooted in the principles of structural integrity and high-seas reliability. Drawing inspiration from the heritage established in 2002, the aesthetic is **Corporate / Modern** with a lean toward **Minimalism**. It aims to evoke the feeling of a precision-engineered vessel: stable, functional, and authoritative. 

The user experience focuses on clarity and trust, utilizing a high-contrast environment that minimizes decorative elements in favor of information density and operational efficiency. Every interface element is designed to feel "bolted down"—grounded and intentional—to resonate with a professional industrial audience.

## Colors

The palette is anchored by **Deep Navy (#002147)**, representing the depth and stability of the maritime industry. This is used for primary navigation, headers, and core brand elements. **Maritime Blue (#0056b3)** serves as the functional accent, applied to interactive elements like buttons, links, and active states to provide a clear visual path for the user.

Backgrounds utilize a pristine **White** and a very light grey (**Tertiary**) to maintain a clean, high-contrast environment that ensures legibility in various lighting conditions typical of industrial settings. Text is primarily set in a deep charcoal to maintain a softer read than pure black while preserving high accessibility.

## Typography

This design system exclusively employs **Montserrat** to achieve an industrial, geometric, and professional tone. The typeface’s open apertures and wide character set provide excellent legibility on both desktop displays and mobile hardware. 

Headlines utilize bold weights and tighter letter spacing to command authority, while body text uses a generous line height (1.6) to facilitate scanning of technical specifications and service logs. Labels and navigational items often utilize an uppercase transformation with a semi-bold weight to mimic the utilitarian markings found in maritime environments.

## Layout & Spacing

A **Fixed Grid** model is used to ensure structural stability across large-format monitors. The layout is centered with a 12-column structure on desktop, transitioning to a 4-column structure on mobile. 

The spacing rhythm is based on an **8px linear scale**, ensuring mathematical harmony between components and containers. Generous external margins are used to frame content, preventing the UI from feeling cramped. Content reflow is handled by standard breakpoints (600px for mobile-to-tablet, 1024px for tablet-to-desktop), where the gutter width remains constant at 24px to maintain a rigid vertical rhythm even as the column widths flex.

## Elevation & Depth

To maintain a "high-reliability" and grounded feel, this design system avoids excessive shadows or floating elements. Depth is primarily communicated through **Tonal Layers** and **Low-Contrast Outlines**.

Surface hierarchies are created by layering white containers over light grey backgrounds. When elevation is necessary—such as for dropdown menus or critical modals—a very soft, diffused ambient shadow is used (0px 4px 12px) with a hint of navy tinting to maintain color harmony. Interactive cards use a 1px border in a neutral mid-tone rather than a shadow, reinforcing the industrial, "blueprint" nature of the design.

## Shapes

The shape language reflects the durability of maritime hardware. A **Soft (0.25rem)** roundedness is applied to standard UI elements like buttons, input fields, and tags. This slight radius softens the industrial edges just enough to feel modern and accessible while maintaining a rigid, professional silhouette. 

Large containers and cards utilize a `rounded-lg` (0.5rem) setting to provide a distinct visual boundary for content modules without appearing overly "playful" or consumer-grade.

## Components

### Buttons
Primary buttons use the Maritime Blue background with white Montserrat text in a semi-bold weight. Secondary buttons use a Deep Navy outline with a transparent background. All buttons feature an uppercase label for increased prominence.

### Input Fields
Inputs are defined by a 1px solid border in a neutral grey, which shifts to Maritime Blue upon focus. Labels are placed above the field in a small, bold, uppercase format to mimic industrial forms.

### Cards
Cards are white containers with a subtle 1px border. They do not use shadows by default. When cards contain service information or ship specifications, they use a "header-strip" of Deep Navy at the top to categorize content.

### Lists & Data Grids
Given the industrial context, data grids are high-density. Rows use alternating tonal backgrounds (White and Tertiary) to improve horizontal scanability. 

### Status Indicators
Status chips use high-saturation colors (Success Green, Warning Amber, Error Red) but always include an accompanying icon for accessibility, ensuring reliability in high-stakes operational environments.