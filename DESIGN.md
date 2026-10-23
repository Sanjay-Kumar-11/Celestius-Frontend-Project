---
name: Luminescent Kinetic Modernism
colors:
  surface: '#10131a'
  surface-dim: '#10131a'
  surface-bright: '#363941'
  surface-container-lowest: '#0b0e15'
  surface-container-low: '#191b23'
  surface-container: '#1d1f27'
  surface-container-high: '#272a32'
  surface-container-highest: '#32353d'
  on-surface: '#e1e2ec'
  on-surface-variant: '#cbc3d7'
  inverse-surface: '#e1e2ec'
  inverse-on-surface: '#2d3038'
  outline: '#958ea0'
  outline-variant: '#494454'
  surface-tint: '#d0bcff'
  primary: '#d0bcff'
  on-primary: '#3c0091'
  primary-container: '#a078ff'
  on-primary-container: '#340080'
  inverse-primary: '#6d3bd7'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#adc6ff'
  on-tertiary: '#002e6a'
  tertiary-container: '#4d8eff'
  on-tertiary-container: '#00285d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#10131a'
  on-background: '#e1e2ec'
  surface-variant: '#32353d'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system projects an atmospheric, electric, and forward-leaning aesthetic tailored for live experiences, nightlife, tech conferences, and underground culture discovery. It marries the depth of dark-mode UI with the energetic, emotive pull of live events.

### Brand Personality & Audience
- **Target Audience:** Digital natives, urban event-goers, tech conference attendees, creators, and night-owls seeking seamless discovery, ticket checkout, and calendar integration.
- **Tone:** Electric, refined, nocturnal, and tactile. It feels like an illuminated venue pass inside a dark club or an immersive festival HUD.
- **Emotional Response:** Anticipation, clarity, velocity, and exclusivity.

### Design Aesthetic
The system relies on **Luminescent Glassmorphism** layered over deep obsidian and slate foundations. High-contrast typography sits atop frosted glass surfaces, punctuated by vivid violet-to-cyan directional gradients, ambient backlight flares, and subtle luminescent border strokes.

## Colors

The palette is engineered specifically for dark environments, relying on chromatic luminance rather than full-spectrum fill to guide attention.

### Palette Architecture
- **Base Canvas (`#0A0D14`):** True obsidian void, ground-floor level for all main page views.
- **Surface Elevation 1 (`#121824`):** Deep slate used for navigation panels, persistent sidebars, and inactive container fills.
- **Surface Elevation 2 (`#1E2638`):** Elevated card base, popovers, and interactive modules.
- **Primary Accent (`#8B5CF6` - Neon Violet):** Core interactive focus, primary actions, and brand identity badges.
- **Secondary Accent (`#06B6D4` - Cyber Cyan):** Live status indicators, verified artist tags, and secondary action hooks.
- **Tertiary Accent (`#3B82F6` - Electric Azure):** Mid-range gradient interpolation, links, and active state highlights.
- **Text & Contrasts:**
  - High-Contrast Primary: `#F8FAFC` (Pure/Off-White 98%)
  - Secondary Text: `#94A3B8` (Cool Muted Slate)
  - Tertiary/Muted: `#64748B` (Subtle metadata, disabled states)
- **Glass Accents & Borders:** `rgba(255, 255, 255, 0.08)` for structural strokes; `rgba(139, 92, 246, 0.25)` for focused or glowing state rings.

## Typography

The type system blends the geometric authority of **Plus Jakarta Sans** for high-impact headlines and event branding with the functional, legible clarity of **Inter** for data grids, body copy, and transaction forms.

- **Display & Headings:** Always track tightly (`-0.01em` to `-0.03em`) to mimic poster design and festival line-up graphics.
- **Body Text:** Maintain a neutral, open tracking structure to preserve optical legibility over dark obsidian backgrounds.
- **Caps & Micro-Tags:** Set in all-caps using `label-caps` with wide letter-spacing (`0.08em`) to demarcate metadata categories such as genre, live status, and seat tiers.

## Layout & Spacing

The layout is built upon an adaptive 12-column fluid grid system on desktop, reflowing into an 8-column layout on tablet and a 4-column column on mobile devices.

### Layout Rhythm
- **Desktop (1024px+):** Max layout container capped at 1280px or 1440px wide for wide-screen displays; uses 24px (`1.5rem`) gutters and minimum 32px (`2rem`) edge margins.
- **Tablet (768px - 1023px):** Fluid grid reflows to 8 columns with 16px (`1rem`) gutters and 24px (`1.5rem`) margins. Multi-column event discovery lists collapse into 2-column card decks.
- **Mobile (< 768px):** 4-column single-stack arrangement with 16px (`1rem`) lateral margins. Sticky bottom sheets house ticket actions and registration triggers.

Horizontal spacing between interactive tokens adheres directly to the `space-*` scale:
- `space-xs` (4px): Micro gaps between icons and counter badges.
- `space-sm` (8px): Spacing inside compact tags, buttons, and form input headers.
- `space-md` (16px): Standard internal card padding and stack gaps.
- `space-lg` (24px): Structural division between sub-components within an event summary card.
- `space-xl` (40px): Section breaks, headline-to-content buffers, and major flow steps.

## Elevation & Depth

This design system avoids traditional drop shadows, relying instead on **frosted translucency**, **luminescent border strokes**, and **chromatic ambient backlighting**.

### Elevation Stack
1. **Canvas Level (0dp):** Deep `#0A0D14`. Ground zero for viewports.
2. **Layer 1 - Recessed Surfaces:** `#121824` with 0px blur and no border. Used for filter bars and empty list wells.
3. **Layer 2 - Glass Cards (Default):**
   - Background: `rgba(18, 24, 36, 0.72)`
   - Backdrop Filter: `blur(16px)`
   - Border: `1px solid rgba(255, 255, 255, 0.08)`
   - Shadow: `0 8px 32px 0 rgba(0, 0, 0, 0.45)`
4. **Layer 3 - Hover & Elevated Modules:**
   - Background: `rgba(30, 38, 56, 0.85)`
   - Backdrop Filter: `blur(20px)`
   - Border: `1px solid rgba(255, 255, 255, 0.16)`
   - Ambient Glow: `0 12px 40px -10px rgba(139, 92, 246, 0.25)`
5. **Layer 4 - Overlays & Modals:**
   - Background: `rgba(10, 13, 20, 0.88)`
   - Backdrop Filter: `blur(24px)`
   - Border: `1px solid rgba(255, 255, 255, 0.12)`
   - Shadow: `0 24px 64px 0 rgba(0, 0, 0, 0.75)`

## Shapes

The design system employs a **Rounded** aesthetic (Scale `2`), striking a balance between cybernetic precision and approachable tactile ergonomics.

- **Base Radii (`rounded` - 8px / 0.5rem):** Form inputs, buttons, filter chips, dropdowns, and status badges.
- **Intermediate Radii (`rounded-lg` - 16px / 1rem):** Event cards, artist panels, media previews, and modal sheets.
- **Macro Radii (`rounded-xl` - 24px / 1.5rem):** Large hero display banners and checkout summary modules.
- **Pill Exception (`rounded-full`):** Reserved exclusively for live indicators, category pills, avatar clusters, and circular floating action buttons (FABs).

## Components

### Buttons
- **Primary Glowing Action Button:** Background is a vibrant directional gradient (`linear-gradient(135deg, #8B5CF6 0%, #3B82F6 100%)`). Text is `#FFFFFF` with `label-lg`. Padding: `12px 24px`. Border: none. Shadow: `0 0 20px rgba(139, 92, 246, 0.45)`. On hover, the glow expands to `0 0 28px rgba(6, 182, 212, 0.6)` with a slight upward translate (`-1px`).
- **Secondary Ghost Button:** Translucent fill (`rgba(255, 255, 255, 0.04)`), frosted border (`1px solid rgba(255, 255, 255, 0.12)`), text `#F8FAFC`. On hover, background shifts to `rgba(255, 255, 255, 0.08)` and border brightens to `rgba(255, 255, 255, 0.25)`.
- **Destructive / Alert Action:** Translucent red base (`rgba(239, 68, 68, 0.12)`), border (`rgba(239, 68, 68, 0.3)`), text `#EF4444`.

### Glass Cards (Event & Discovery)
- Constructed with a `16px` border-radius and `backdrop-filter: blur(16px)`.
- Base background: `rgba(18, 24, 36, 0.65)`.
- Border: `1px solid rgba(255, 255, 255, 0.08)`.
- Features an image wrapper with a top-to-bottom dark gradient overlay (`rgba(10, 13, 20, 0) 50%` to `rgba(10, 13, 20, 0.9) 100%`) ensuring text contrast over arbitrary event imagery.

### Chips & Filter Tags
- Fully rounded (`pill-shaped`) or `rounded-md` (8px).
- Inactive: Background `#121824`, border `rgba(255, 255, 255, 0.08)`, text `#94A3B8`.
- Active/Selected: Background `rgba(139, 92, 246, 0.15)`, border `1px solid #8B5CF6`, text `#F8FAFC` with a subtle inner luminescent shadow.

### Form Inputs & Search Fields
- Base fill: `#121824` with `1px solid rgba(255, 255, 255, 0.1)`. Height: `44px`.
- Padding: `0 16px`. Font: `body-md` in `#F8FAFC`. Placeholder: `#64748B`.
- Focused state: Border snaps to `#8B5CF6` with a soft outer ring: `0 0 0 3px rgba(139, 92, 246, 0.25)`.

### Checkboxes & Radio Controls
- Base: 20x20px container in `#121824` with `1px solid rgba(255, 255, 255, 0.2)`.
- Selected: Filled with `#8B5CF6` and checked with an inset `#FFFFFF` stroke icon; radiates a localized `0 0 10px rgba(139, 92, 246, 0.5)` glow.

### Lists & Row Items
- Divided using hair-thin horizontal dividers: `1px solid rgba(255, 255, 255, 0.06)`.
- Row items transition seamlessly on hover to `rgba(255, 255, 255, 0.03)` with no shift in layout.

### Domain-Specific Components
- **Live Ticket Availability Bar:** A progress indicator with an electric gradient track (`#8B5CF6` to `#06B6D4`) over a dark `#1E2638` channel, indicating low-stock tickets with an animated pulsing dot.
- **VIP / Tier Badge:** A micro tag featuring a metallic/holographic gradient stroke (`linear-gradient(90deg, #8B5CF6, #06B6D4)`) and `label-caps` typography.