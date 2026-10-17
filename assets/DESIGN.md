---
name: Lumen Precision Detailing
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
  on-surface-variant: '#e6bdba'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ac8886'
  outline-variant: '#5c3f3e'
  surface-tint: '#ffb3af'
  primary: '#ffb3af'
  on-primary: '#68000e'
  primary-container: '#e32636'
  on-primary-container: '#fffeff'
  inverse-primary: '#bf0023'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#c7c6c6'
  on-tertiary: '#303031'
  tertiary-container: '#767676'
  on-tertiary-container: '#ffffff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3af'
  on-primary-fixed: '#410005'
  on-primary-fixed-variant: '#930018'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Space Grotesk
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 46px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 30px
    fontWeight: '500'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
    letterSpacing: -0.015em
  title-md:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Geist
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.12em
  label-code:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  margin-tablet: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system embodies high-precision Finnish craftsmanship combined with high-performance German automotive engineering aesthetics. Inspired directly by the instrumentation, optical lenses, and architectural cockpits of brands like Porsche and BMW M, the aesthetic prioritizes technical clarity, surgical focus, and quiet authority.

The UI targets discerning automotive collectors, luxury vehicle owners, and performance purists who view vehicle care as precision optical restoration rather than cosmetic maintenance. The visual tone evokes trust, optical brilliance, and methodical mastery.

The visual style blends **Technical Minimalism** with **Precision Instrument UI**:
- Surfaces are dark, quiet, and matte, allowing high-luminescence imagery, laser-guided focal elements, and crisp technical text to stand forward.
- High contrast, mechanical micro-details, and subtle hairline dividers evoke precision-machined aluminum and lens collimators.
- Accents are restrained: vibrant racing red is deployed with deliberate intent solely to signal precision, active performance states, and technical verification.

## Colors

The palette operates on a calibrated dynamic contrast system reflecting optical clarity:

- **Deep Charcoal Canvas (`#171717`):** The primary dark mode foundation. Provides a deep, non-reflective backdrop that mimics an inspection darkroom or cleanroom detailing bay.
- **Racing Red Accent (`#E32636`):** The singular focal chromatic accent. Used for status indicators, micro-callouts, key CTAs, and performance calibration metrics. It must never overwhelm large surface areas; it acts as an optical beam.
- **Secondary Cleanroom White (`#FFFFFF`):** High-efficiency neutral for luminous headlines, inverted stark content modules, and stark foreground elements.
- **Soft Technical Gray (`#F5F5F5`):** Reserved for high-contrast light inspection sections, comparison modules, and printed certification documents.
- **Graphite Gray (`#202020`):** Secondary container fill on dark canvas, providing quiet contrast without elevating brightness.
- **Muted Instrumentation Gray (`#777777`):** Technical labels, telemetry metadata, dimensional markers, and secondary descriptive copy.
- **Hairline Borders (`#282828` on dark, `#E5E5E5` on light):** Structural delineators calibrated to 1px thickness for razor-sharp spatial grouping.

## Typography

The type system is balanced between geometric structural mechanics (**Space Grotesk**) and clinical utilitarian readability (**Geist**).

- **Headlines & Technical Callouts (Space Grotesk):** Engineered glyph forms and slight square terminals evoke optical lens branding and bespoke instrument gauges. Display and headline levels feature tight tracking to maintain visual density.
- **Body & Data Displays (Geist):** Clean, neutral, high-legibility sans-serif optimized for specs, service walkthroughs, and micro-metrics.
- **Labels & Micro-indicators:** Rendered predominantly uppercase in `label-caps` with wide tracking (`0.12em`), reinforcing diagnostic instruments and calibration dials.
- All numerical data (optical lux levels, micrometers, coating cure times) should enforce tabular figures where applicable to align across multi-column grids.

## Layout & Spacing

The layout philosophy is strictly aligned to a 12-column mathematical grid, emphasizing deliberate spatial rhythm, generous perimeter breathing room, and razor-sharp vertical axis alignment.

- **Desktop (1200px+):** 12 columns with `1.5rem` gutters and a maximum canvas width of `1440px`. Exterior margins expand symmetrically up to `3rem` to mirror the expansive balance of modern Nordic design.
- **Tablet (768px - 1199px):** 8 columns with `1.25rem` gutters and `2rem` margins. Complex diagnostic comparisons fold into dual-column cards.
- **Mobile (< 768px):** 4 columns with `1rem` gutters and `1.25rem` canvas margins. Asymmetrical data layouts stack strictly into sequential vertical stages.
- **Rhythm & Whitespace:** Spacing between disparate technical sections uses large vertical intervals (`space-2xl` to `space-3xl`) to establish an elite showroom presentation, while internal component spacing remains compact and precise (`space-xs` to `space-md`).

## Elevation & Depth

To sustain the engineering and technical ethos, this design system avoids heavy drop shadows, blurred ambient lighting, or skeuomorphic bevels. Instead, elevation is communicated through **structural tonal layering** and **hairline edge definition**:

1. **Surface 0 (Base Canvas):** `#171717` — Deep matte background absorbing ambient visual clutter.
2. **Surface 1 (Card & Module Foundation):** `#202020` — Low-contrast lift with a continuous `1px` border of `#282828`.
3. **Surface 2 (Interactive Floating & Flyout Layers):** `#252525` — Outlined by `#333333` with an ultra-subtle zero-offset rim shadow: `0 4px 20px rgba(0, 0, 0, 0.45)`.
4. **Light Section Surface Tier:** Full-bleed `#F5F5F5` panels framed against dark canvas with stark structural transitions; nested cards within light sections utilize pure `#FFFFFF` surfaces with `#E5E5E5` hairline borders.
5. **Optical Focus State:** Elements in active state or hover receive a sharp, low-spread glow accentuating optical precision: `0 0 0 1px #E32636`.

## Shapes

The shape system is strictly **Sharp (`0`)**, with `0px` border-radius across all core interactive elements, cards, and technical containers.

- Geometric 90-degree corners communicate absolute rigidity, structural accuracy, and engineering tolerance down to the millimeter.
- Tags, badges, and status chips retain rectangular geometry with clean, disciplined inner padding.
- Optical focal points (such as lens crosshairs, slider handles, and technical indicator dots) maintain true geometric circles only where mathematically representative of optical apertures or lasers.

## Components

### Buttons
- **Primary Technical Action:** Deep charcoal `#171717` or pure white text on `#E32636` red background. 0px corner radius, uppercase `label-caps` typography, `1rem` vertical and `1.75rem` horizontal padding. Subtle hover state transitions background to `#C71F2E`.
- **Secondary / Outline Action:** Transparent background with `1px` border in `#FFFFFF` (on dark) or `#202020` (on light). Sharp typography, active state fills with primary text color in reverse.
- **Diagnostic / Ghost Action:** Text-only with an accompanying right-aligned hair arrow (`→`) and bottom underline offset by `4px`.

### Cards & Modular Containers
- Framed in `#282828` hairline boundaries on `#202020` fill.
- Internal padding calibrated uniformly to `space-xl` (`2.5rem`) on desktop and `space-lg` (`1.5rem`) on mobile.
- Headers within cards should feature a dual-row header: micro-label category in `label-caps` (`#777777`) followed immediately by the item title.

### Headlight Before / After Optical Comparison Slider
- A full-bleed interactive dual-image module divided by a 1px vertical hairline in `#E32636`.
- The central handle consists of a machined 32px circular reticle with internal directional chevrons (`‹ ›`), moving smoothly along the horizontal axis.
- Visual readout tags for "DEGRADED UV LAYER [BEFORE]" and "RESTORED OPTICAL CLARITY [AFTER]" positioned in `label-caps` at top corners.

### Technical Spec Chips & Badges
- Strict rectangular containers (`0px` radius).
- Background `#202020` with `#282828` border, or `#FFFFFF` with `#E5E5E5` border on light themes.
- Preceded by a `4px` solid square status marker in `#E32636` for high-importance metrics (e.g., `99.4% LUX RETENTION`, `CERAMIC QUARTZ 9H`).

### Input Fields & Selectors
- Background: `#1C1C1C`. Hairline border in `#2E2E2E`.
- Text typed in `Geist` body font (`#FFFFFF`). Placeholder text rendered in muted `#777777`.
- Focus state: Border transitions instantly to pure white (`#FFFFFF`) or racing red (`#E32636`) with zero corner rounding and no blurred outer ring.

### Checkboxes & Segmented Toggles
- Custom square selectors (`16px × 16px`) with 1px border. Checked state fills with `#E32636` and features a stark geometric micro-tick in white.
- Segmented multi-step package pickers operate like vehicle configuration dials: flush rectangular buttons connected in a unified horizontal bar with active segment inverted to pure white background and charcoal text.