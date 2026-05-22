# Design System Inspired by Care.com
## 1. Visual Theme & Atmosphere
Care.com's design system embodies warmth, trust, and accessibility for families seeking care solutions. The visual language combines approachable humanity with professional reliability, using soft natural tones and vibrant accent colors that feel inviting rather than clinical. The design prioritizes clarity and ease of navigation, reflecting the platform's commitment to simplifying the care-finding process. Generous whitespace and rounded corners create a friendly, non-threatening aesthetic that resonates with diverse age groups and care scenarios—from young parents seeking childcare to adult children finding senior care.
**Key Characteristics**
- Warm, accessible, and family-oriented visual identity
- Generous whitespace and breathing room between elements
- Rounded, soft corners for approachability
- Clear typographic hierarchy with readable, modern typefaces
- Nature-inspired color palette with vibrant accents
- Trust-building visual consistency across all care categories
- Playful yet professional tone through color and illustration
## 2. Color Palette & Roles
### Primary
- **Teal Primary** (`#377A69`): Core brand color for primary interactive elements, buttons, and key UI components; establishes trust and calm
- **Deep Teal** (`#025747`): Secondary primary shade for hover states, emphasis, and footer elements; adds depth and weight
### Accent Colors
- **Sage Green Light** (`#D0F5A3`): Soft, optimistic accent for success states and highlighted calls-to-action
- **Sage Green Pale** (`#E4FFB8`): Lightest accent for backgrounds and subtle UI accents; creates visual breathing room
- **Lime Accent** (`#ACCE`): Supporting accent for badges and tertiary interactive states
### Interactive
- **Link Blue** (`#0000EE`): Standard hyperlink color for text links and navigation
- **Button Green** (`#D0F5A3`): Primary CTA button background with `#025747` text overlay
### Neutral Scale
- **Charcoal Dark** (`#1E1E1E`): Primary text color for body copy and headings; dominant throughout interface
- **White** (`#FFFFFF`): Primary surface and background color
- **Black** (`#000000`): High-contrast text for critical information
- **Gray Medium** (`#707070`): Secondary text and disabled states
- **Gray Light** (`#DDDDDD`): Borders and subtle dividers
- **Cream Beige** (`#F6F3EE`): Warm neutral background alternative
- **Cream Off-White** (`#F7F5F0`): Subtle background tint for content sections
### Status & Semantic
- **Warning Gold** (`#F6BE36`): Primary warning state indicator; high visibility for cautions
- **Warning Amber** (`#FAAF00`): Secondary warning shade for consistency and emphasis
## 3. Typography Rules
### Font Family
**Primary Font:** Oceanic Text (Semibold)
- Fallback: `system-ui, -apple-system, sans-serif`
- Used for display and primary headings
**Secondary Font:** Oceanic Grotesk (Regular, Medium, Semibold)
- Fallback: `system-ui, -apple-system, sans-serif`
- Used for body, labels, and component text
**Display Font:** NaN Druid Sans (Bold)
- Fallback: `Georgia, serif`
- Used for hero display text
**Monospace Font:** Arial
- Fallback: `monospace`
- Used for buttons and utility text
### Hierarchy
| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|---|---|
| Display/Hero | NaN Druid Sans | 64px | 550 | 72px | 0px | Reserved for main page headlines; impactful and bold |
| Heading 1 | Oceanic Text | 32px | 450 | 48px | 0px | Primary section headers and page titles |
| Heading 2 | Oceanic Text | 24px | 450 | 40px | 0px | Secondary section headers; strong visual weight |
| Heading 3 | Oceanic Grotesk | 18px | 500 | 24px | 0px | Subsection headers and card titles |
| Heading 4 | Oceanic Grotesk | 16px | 500 | 20px | 0px | Component labels and tertiary headers |
| Heading 5 | Oceanic Grotesk | 14px | 500 | 16px | 0px | Small labels and metadata |
| Body/Paragraph | Oceanic Grotesk | 18px | 400 | 28px | 0px | Primary reading text and descriptions |
| Body Small | Oceanic Grotesk | 16px | 400 | 22px | 0px | Input labels, captions, and secondary text |
| Button/CTA | Arial | 13.3333px | 400 | normal | 0px | Interactive button text; clear and accessible |
### Principles
- Use **Oceanic Grotesk** as the workhorse font for all body and component text; it provides clarity and modern sensibility
- Reserve **Oceanic Text Semibold** for headings to establish visual hierarchy and create distinct sections
- Use **NaN Druid Sans** exclusively for hero/display areas to create memorable entry points
- Maintain minimum `16px` for body text to ensure readability across all devices
- Respect the generous line heights (`28px` for body) to improve scanning and reduce cognitive load
- Never reduce line height below `1.4x` the font size; trust and readability depend on breathing room
- Use weight `500` (Medium) as the visual threshold for interactive and actionable text
## 4. Component Stylings
### Buttons
#### Primary Button
- **Background:** `#D0F5A3`
- **Text Color:** `#025747`
- **Font:** Oceanic Grotesk, `16px`, Weight `500`
- **Padding:** `8px 24px`
- **Border Radius:** `20px`
- **Border:** `1px solid #D0F5A3`
- **Height:** `40px`
- **Line Height:** `18px`
- **Hover State:** Background `#ACCE`, text `#025747`
- **Active State:** Background `#377A69`, text `#FFFFFF`
- **Disabled State:** Background `#DDDDDD`, text `#707070`, cursor `not-allowed`
#### Secondary Button (Teal)
- **Background:** `#377A69`
- **Text Color:** `#FFFFFF`
- **Font:** Oceanic Grotesk, `16px`, Weight `500`
- **Padding:** `8px 24px`
- **Border Radius:** `20px`
- **Border:** `1px solid #377A69`
- **Height:** `40px`
- **Line Height:** `18px`
- **Hover State:** Background `#025747`, text `#FFFFFF`
- **Active State:** Background `#1E1E1E`, text `#FFFFFF`
#### Ghost Button
- **Background:** `transparent`
- **Text Color:** `#377A69`
- **Font:** Oceanic Grotesk, `16px`, Weight `400`
- **Padding:** `8px 24px`
- **Border Radius:** `20px`
- **Border:** `2px solid #377A69`
- **Height:** `40px`
- **Hover State:** Background `#F6F3EE`, text `#025747`
- **Active State:** Background `#D0F5A3`, text `#025747`
### Cards & Containers
#### Standard Card
- **Background:** `#FFFFFF`
- **Text Color:** `#1E1E1E`
- **Font:** Oceanic Grotesk, `18px`, Weight `400`
- **Padding:** `24px`
- **Border Radius:** `32px`
- **Border:** `1px solid #DDDDDD`
- **Box Shadow:** `0px 2px 8px rgba(0, 0, 0, 0.08)`
- **Line Height:** `28px`
- **Hover State:** Box Shadow `0px 4px 16px rgba(0, 0, 0, 0.12)`
#### Category Card (with Image Overlay)
- **Background:** `linear-gradient(135deg, rgba(2, 87, 71, 0.85) 0%, rgba(55, 122, 105, 0.85) 100%)`
- **Text Color:** `#FFFFFF`
- **Font:** Oceanic Grotesk, `18px`, Weight `500`
- **Padding:** `20px`
- **Border Radius:** `32px`
- **Border:** `none`
- **Box Shadow:** `0px 4px 12px rgba(0, 0, 0, 0.15)`
- **Background Image:** Yes (full cover)
- **Hover State:** Opacity `0.95`, scale `1.02`
#### Testimonial/Profile Card
- **Background:** `#FFFFFF`
- **Text Color:** `#1E1E1E`
- **Font:** Oceanic Grotesk, `16px`, Weight `400`
- **Padding:** `16px`
- **Border Radius:** `32px`
- **Border:** `none`
- **Box Shadow:** `0px 2px 8px rgba(0, 0, 0, 0.1)`
- **Line Height:** `22px`
#### Pink Highlight Card (Services List)
- **Background:** `#F2B6E1` (soft pink)
- **Text Color:** `#1E1E1E`
- **Font:** Oceanic Grotesk, `16px`, Weight `400`
- **Padding:** `24px`
- **Border Radius:** `24px`
- **Border:** `none`
- **Box Shadow:** `none`
- **Line Height:** `24px`
### Inputs & Forms
#### Text Input (ZIP Code Style)
- **Background:** `#FFFFFF`
- **Text Color:** `#1E1E1E`
- **Font:** Oceanic Grotesk, `18px`, Weight `400`
- **Padding:** `12px 16px`
- **Border Radius:** `8px`
- **Border:** `1px solid #DDDDDD`
- **Height:** `48px`
- **Line Height:** `24px`
- **Placeholder Color:** `#707070`
- **Focus State:** Border `2px solid #377A69`, Box Shadow `0px 0px 0px 3px rgba(55, 122, 105, 0.1)`
#### Rounded Search Input
- **Background:** `#FFFFFF`
- **Text Color:** `#1E1E1E`
- **Font:** Oceanic Grotesk, `12.8px`, Weight `400`
- **Padding:** `6px 15px 6px 35px`
- **Border Radius:** `50px`
- **Border:** `1px solid #707070`
- **Height:** `31px`
- **Line Height:** `normal`
- **Placeholder Color:** `#707070`
- **Focus State:** Border `1px solid #377A69`, outline `none`
#### Label
- **Font:** Oceanic Grotesk, `16px`, Weight `400`
- **Color:** `#1E1E1E`
- **Line Height:** `22px`
- **Margin Bottom:** `8px`
- **Display:** `block`
### Navigation
#### Main Navigation (Horizontal)
- **Background:** transparent or `#FFFFFF`
- **Text Color:** `#1E1E1E`
- **Font:** Oceanic Grotesk, `18px`, Weight `400`
- **Padding:** `16px 24px`
- **Line Height:** `28px`
- **Link Spacing:** `24px` horizontal gap
- **Hover State:** Text color `#377A69`, underline `2px solid #D0F5A3`
- **Active State:** Text color `#025747`, underline `2px solid #025747`
#### Dropdown Menu
- **Background:** `#FFFFFF`
- **Text Color:** `#1E1E1E`
- **Font:** Oceanic Grotesk, `16px`, Weight `400`
- **Padding:** `12px 16px`
- **Border:** `1px solid #DDDDDD`
- **Border Radius:** `8px`
- **Box Shadow:** `0px 4px 12px rgba(0, 0, 0, 0.15)`
- **Item Height:** `40px`
- **Item Hover:** Background `#F6F3EE`, text `#377A69`
### Badges & Tags
#### Success Badge
- **Background:** `#D0F5A3`
- **Text Color:** `#025747`
- **Font:** Oceanic Grotesk, `14px`, Weight `500`
- **Padding:** `4px 12px`
- **Border Radius:** `4px`
- **Border:** `1px solid #ACCE`
#### Warning Badge
- **Background:** `#F6BE36`
- **Text Color:** `#1E1E1E`
- **Font:** Oceanic Grotesk, `14px`, Weight `500`
- **Padding:** `4px 12px`
- **Border Radius:** `4px`
- **Border:** `1px solid #FAAF00`
#### Neutral Badge
- **Background:** `#F6F3EE`
- **Text Color:** `#1E1E1E`
- **Font:** Oceanic Grotesk, `14px`, Weight `400`
- **Padding:** `4px 12px`
- **Border Radius:** `4px`
- **Border:** `1px solid #DDDDDD`
## 5. Layout Principles
### Spacing System
**Base Unit:** `4px`
**Scale:**
- `4px` — Micro spacing (tight component interiors)
- `8px` — XS spacing (component padding, tight lists)
- `16px` — S spacing (standard padding, narrow gaps)
- `20px` — M spacing (comfortable padding)
- `24px` — L spacing (component padding, moderate gaps)
- `28px` — XL spacing (generous padding)
- `32px` — 2XL spacing (section padding)
- `36px` — 3XL spacing (large gaps)
- `40px` — 4XL spacing (hero spacing)
- `48px` — 5XL spacing (between major sections)
- `64px` — 6XL spacing (section separation)
- `80px` — 7XL spacing (page margin)
**Usage Context:**
- Button padding: `8px 24px`
- Card padding: `24px`
- Section padding: `32px` to `48px`
- Page margins: `40px` to `80px` at desktop
- Component gaps (flex/grid): `16px` to `24px`
### Grid & Container
- **Max Width:** `1200px` for main content container
- **Column Strategy:** 6-column flexible grid at desktop; 2-column at tablet; 1-column mobile
- **Gutter:** `24px` between columns
- **Section Pattern:** Full-width background with `1200px` max-width centered content
- **Container Padding:** `40px` horizontal at desktop; `24px` at tablet; `16px` at mobile
### Whitespace Philosophy
Care.com embraces generous whitespace as a fundamental trust-building tool. Every section breathes; cards have clear breathing room; typography has generous line heights. This approach reduces cognitive load and creates a calm, welcoming experience—particularly important for users seeking care solutions during stressful life transitions. White space is not wasted space; it is intentional design that communicates stability and clarity.
### Border Radius Scale
- `4px` — Badges, small utility elements, inputs
- `8px` — Form inputs, small cards, secondary buttons
- `20px` — Primary buttons, rounded accents
- `24px` — Medium cards, containers
- `28px` — Large interactive elements
- `32px` — Category cards, major cards
- `50px` — Search inputs, fully rounded pills
## 6. Depth & Elevation
| Level | Treatment | Use |
|-------|-----------|-----|
| 0 (Flat) | No shadow | Flat backgrounds, text-only areas, disabled states |
| 1 (Subtle) | `0px 2px 8px rgba(0, 0, 0, 0.08)` | Standard cards, light elevation buttons |
| 2 (Raised) | `0px 4px 12px rgba(0, 0, 0, 0.12)` | Hovered cards, moderate elevation modals |
| 3 (Floating) | `0px 8px 16px rgba(0, 0, 0, 0.15)` | Dropdowns, tooltips, active modals |
| 4 (Overlay) | `0px 12px 24px rgba(0, 0, 0, 0.18)` | High-priority modals, floating action buttons |
**Shadow Philosophy:**
Care.com uses subtle, directional shadows to create gentle depth without visual heaviness. Shadows support hierarchy and usability by distinguishing interactive surfaces from static backgrounds. All shadows use soft, natural falloff (`rgba(0, 0, 0, 0.08)` to `0.18)`) and avoid pure black or harsh contrast. Shadows increase on hover and active states to provide feedback without overwhelming the interface. This measured approach maintains the warm, approachable aesthetic while preserving clarity and focus.
## 7. Do's and Don'ts
### Do
- Use `#377A69` (Teal Primary) as the default interactive color for primary CTAs, links, and key UI elements
- Apply `#D0F5A3` (Sage Green Light) to primary action buttons with `#025747` text for maximum contrast and warmth
- Maintain minimum `28px` line height for body text to ensure readability and scanning efficiency
- Use `#1E1E1E` (Charcoal Dark) as the primary text color; it's tested and dominant throughout the interface
- Implement generous whitespace (`24px` to `48px` gaps) between major sections and components
- Round corners to `32px` on all category and major cards for consistency and brand recognition
- Use **Oceanic Grotesk** for all body and component text; it's the workhorse font
- Apply subtle shadows (`0px 2px 8px rgba(0, 0, 0, 0.08)`) to cards to add gentle depth without weight
- Use `#F6BE36` and `#FAAF00` (Warning Gold/Amber) for cautions and alerts; these colors stand out
- Test inputs with `50px` border radius for search fields to create pill-shaped, approachable inputs
- Ensure button heights are `40px` minimum for easy touch targets across all devices
- Use pink/warm accent colors for secondary call-to-action areas to add personality
### Don't
- Don't use pure black (`#000000`) for body text; it's reserved for high-contrast emphasis only
- Don't apply colors outside the defined palette; brand consistency depends on restraint
- Don't reduce font sizes below `16px` for interactive or label text; accessibility requires minimum readability
- Don't use `#FFFFFF` text on pale green backgrounds; insufficient contrast
- Don't round corners below `8px` except on badges; the brand uses generous, soft corners
- Don't crowd components with tight spacing; maintain at least `16px` gaps between cards
- Don't apply shadows heavier than `0px 12px 24px rgba(0, 0, 0, 0.18)`; overuse diminishes effect
- Don't mix font families within a single heading or body text block; maintain consistent hierarchy
- Don't use link blue (`#0000EE`) for non-linked text; it creates confusion and false affordance
- Don't apply gradients beyond the teal primary overlay on category cards; keep design flat and clear
- Don't disable primary buttons with gray; use reduced opacity or remove from DOM
- Don't use uppercase text for body copy; the brand favors sentence case for approachability
## 8. Responsive Behavior
### Breakpoints
| Breakpoint Name | Width | Key Changes |
|---|---|---|
| Mobile | `0px` – `640px` | 1-column grid, `16px` padding, stacked components, `24px` spacing |
| Tablet | `641px` – `1024px` | 2-column grid, `24px` padding, `24px` gaps, reduced hero text |
| Desktop | `1025px` – `1440px` | 6-column grid, `40px` padding, `24px` gaps, full typography |
| Large Desktop | `1441px`+ | Max width `1200px` container, center-aligned, `80px` margins |
### Touch Targets
- **Minimum Button Height:** `40px`
- **Minimum Button Width:** `48px`
- **Minimum Link/Tap Area:** `44px × 44px`
- **Spacing Between Tappable Elements:** `8px` minimum
- **Search Input Height:** `40px` to `48px` on mobile
- **Card Touch Height:** `120px` minimum for category cards
### Collapsing Strategy
- **Hero Section:** Full-width background image at desktop; reduce `font-size` from `64px` to `40px` at tablet; `32px` at mobile. Reduce vertical padding from `80px` to `40px` at tablet; `24px` at mobile.
- **Navigation:** Horizontal at desktop; collapse to hamburger menu at tablet and mobile; drawer overlay with `24px` padding.
- **Cards Grid:** 3-column at desktop; 2-column at tablet; 1-column at mobile with full width minus `16px` margins.
- **Buttons:** Full width at mobile (except in tight groups); maintain `40px` height; use `16px` padding at mobile.
- **Inputs:** Full width at mobile with `24px` margin-bottom; side-by-side layout at desktop (e.g., zip + search).
- **Typography:** Reduce all font sizes by `2px` to `4px` at mobile to maintain readability with smaller screens; maintain line height ratios.
- **Padding:** Reduce section padding from `48px` to `24px` at tablet; `16px` at mobile for efficient space use.
## 9. Agent Prompt Guide
### Quick Color Reference
- **Primary CTA:** Sage Green Light (`#D0F5A3`) with Teal text (`#025747`)
- **Secondary CTA:** Teal Primary (`#377A69`) with White text
- **Background:** White (`#FFFFFF`)
- **Body Text:** Charcoal Dark (`#1E1E1E`)
- **Heading Text:** Charcoal Dark (`#1E1E1E`)
- **Link Color:** Link Blue (`#0000EE`) for inline links; Teal Primary (`#377A69`) for navigation
- **Accent Accents:** Sage Green Light (`#D0F5A3`), Lime (`#ACCE`)
- **Warning/Alert:** Warning Gold (`#F6BE36`) or Warning Amber (`#FAAF00`)
- **Borders:** Gray Light (`#DDDDDD`)
- **Disabled/Secondary:** Gray Medium (`#707070`)
- **Card Background:** White (`#FFFFFF`)
- **Overlay/Gradient:** Deep Teal (`#025747`) with 85% opacity over images
### Iteration Guide
1. **Always use `#D0F5A3` primary buttons** with `#025747` text, `16px` Oceanic Grotesk, `8px 24px` padding, `20px` border-radius, `40px` height.
2. **Set body text to `#1E1E1E`, `18px`, Oceanic Grotesk `400`, line-height `28px`** for all paragraph content.
3. **Apply `32px` border-radius to all major cards**; use `8px` for inputs and badges.
4. **Maintain whitespace:** minimum `24px` gaps between cards, `48px` between sections, `80px` page margins at desktop.
5. **Use Oceanic Text Semibold for headings** at `32px` (h1), `24px` (h2); Oceanic Grotesk `18px` for h3 and body.
6. **Headings are always `#1E1E1E`**; links are `#0000EE` inline or `#377A69` in navigation.
7. **Buttons must be `40px` tall** with `50px` border-radius for pill-shaped; `20px` for standard buttons.
8. **Apply subtle box-shadow `0px 2px 8px rgba(0, 0, 0, 0.08)`** to all cards; increase to `0px 4px 12px rgba(0, 0, 0, 0.12)` on hover.
9. **Inputs use `#FFFFFF` background, `#1E1E1E` text, `1px solid #DDDDDD` border, `50px` radius for search, `8px` for standard.**
10. **Mobile breakpoint at `640px`:** stack grids to 1 column, reduce padding to `16px`, font-size to `40px` hero, maintain `40px` button heights for touch.