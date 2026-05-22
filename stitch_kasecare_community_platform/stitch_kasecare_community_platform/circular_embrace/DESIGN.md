---
name: Circular Embrace
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#404942'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#707972'
  outline-variant: '#bfc9c0'
  surface-tint: '#296a4a'
  primary: '#00452a'
  on-primary: '#ffffff'
  primary-container: '#1b5e3f'
  on-primary-container: '#93d5ae'
  inverse-primary: '#93d5ae'
  secondary: '#785900'
  on-secondary: '#ffffff'
  secondary-container: '#fdc003'
  on-secondary-container: '#6c5000'
  tertiary: '#3f3c2c'
  on-tertiary: '#ffffff'
  tertiary-container: '#575342'
  on-tertiary-container: '#cdc7b1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#aef1c8'
  primary-fixed-dim: '#93d5ae'
  on-primary-fixed: '#002112'
  on-primary-fixed-variant: '#085134'
  secondary-fixed: '#ffdf9e'
  secondary-fixed-dim: '#fabd00'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5b4300'
  tertiary-fixed: '#e9e2cc'
  tertiary-fixed-dim: '#ccc6b1'
  on-tertiary-fixed: '#1e1c0e'
  on-tertiary-fixed-variant: '#4a4737'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  headline-xl:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.25'
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
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
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding-mobile: 1.25rem
  container-padding-desktop: 2.5rem
  gutter: 1.5rem
  section-gap: 4rem
---

## Brand & Style
The design system is built upon the philosophy of "Human-Centered Modernism." It seeks to evoke a profound sense of safety, inclusion, and neighborhood warmth. The visual language is defined by the "Circular Embrace" theme—utilizing organic curves and soft geometries to symbolize protection and communal support.

The style blends **Minimalism** with **Tactile** warmth. By prioritizing generous whitespace and a cream-based palette over stark whites, the UI feels lived-in and approachable rather than clinical. It is professional enough to signal high-stakes trust (caregiving) while remaining soft enough to feel like a neighborly conversation.

## Colors
The palette is rooted in the "Forest and Sunlight" metaphor. 

- **Primary (Deep Forest Green):** Used for core actions, headers, and navigation to establish a foundation of stability and growth.
- **Secondary (Vibrant Gold):** An accent of hope and vitality, used sparingly for highlights, verification markers, and high-energy touchpoints.
- **Backgrounds:** The interface avoids pure white. Instead, it utilizes a "Cream" base for the main canvas and "Soft Gold" for container backgrounds to reduce eye strain and increase perceived warmth.
- **Text:** A soft "Dark Gray" is used instead of pure black to maintain a high-contrast but gentle reading experience.

## Typography
The typographic system pairs the geometric friendliness of **Sora** for headings with the high utility of **Inter** for body text. 

**Headlines** utilize a tighter letter-spacing and heavier weights to feel authoritative yet modern. 
**Body copy** is optimized for legibility with a generous line-height (1.6) to ensure accessibility for a wide demographic of users, including elderly participants and caregivers. 

For **Bangla text support**, ensure the rendering engine defaults to a humanist sans-serif (like Kalpurush) that maintains the vertical rhythm established by Inter.

## Layout & Spacing
This design system employs a **Fluid Grid** with a soft 8px base unit. 

- **Desktop:** 12-column grid with a 1200px max-width container. 
- **Mobile:** Single column with 20px (1.25rem) side margins.
- **Rhythm:** Spacing between elements should favor "grouping by embrace"—related items sit closer together (8px-16px), while distinct sections are separated by large gaps (64px+) to prevent the interface from feeling cluttered or stressful.

## Elevation & Depth
Depth is communicated through **Tonal Layers** rather than aggressive shadows. 

1.  **Level 0 (Base):** The Cream background (#F9F6F3).
2.  **Level 1 (Cards):** Soft Gold (#FFF8E1) or pure white surfaces with an extremely diffused ambient shadow (8% opacity, Forest Green tint). This creates a "lifted" effect that feels natural.
3.  **Level 2 (Modals/Overlays):** Stronger elevation with a backdrop blur (12px) to focus the user’s attention on the safe "embrace" of the foreground element.

Avoid sharp edges or high-contrast borders; use subtle 1px Forest Green strokes at 10% opacity for structural definition where necessary.

## Shapes
The "Circular Embrace" theme is manifest in a consistent 12px to 16px corner radius. 

- **Small Components (Buttons, Inputs):** 12px radius.
- **Medium Components (Cards, Modals):** 16px radius.
- **Large Sections:** 32px top-radius on mobile "drawer" sheets.
- **Circular Motifs:** Profile pictures and status icons are always perfectly circular. 

The goal is to eliminate "sharpness" from the user experience, replacing it with soft, rounded paths that feel safe to touch.

## Components

### Buttons
- **Primary:** Forest Green fill with White text. Bold, 12px rounded corners.
- **Accent:** Vibrant Gold fill with Forest Green text. Used for "Add Help" or "Join" actions to provide warmth.
- **Secondary/Outline:** Forest Green 1.5px border with transparent background.

### Cards
- **Caregiver Profile:** Cream background, 16px radius, soft ambient shadow. Features a subtle Forest Green accent bar on the left side to denote "Stability."
- **Verification Cards:** Deep Forest Green background with Gold icons. These should feel like a "Seal of Trust."

### Inputs & Fields
- **Search/Text Fields:** Subtle cream fill with a 1px Forest Green border.
- **Focus State:** The border transitions to a thicker Forest Green, accompanied by a Gold underline animation that "grows" from the center, symbolizing a spark of hope/interaction.

### Badges & Status
- **Verified:** A circular gold star badge. 
- **Urgency:** Use a soft terracotta red, but keep the Forest Green/Gold hierarchy dominant to prevent panic.

### Navigation
A bottom navigation bar on mobile should use "active" indicators that are circular pills, reinforcing the primary motif of protection and inclusion.