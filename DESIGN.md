---
name: Cyber Kawaii Home
colors:
  surface: '#1f0e13'
  surface-dim: '#1f0e13'
  surface-bright: '#493338'
  surface-container-lowest: '#19090e'
  surface-container-low: '#28161b'
  surface-container: '#2d1a1f'
  surface-container-high: '#382529'
  surface-container-highest: '#442f34'
  on-surface: '#fbdae1'
  on-surface-variant: '#e5bcc5'
  inverse-surface: '#fbdae1'
  inverse-on-surface: '#3f2b30'
  outline: '#ac878f'
  outline-variant: '#5c3f46'
  surface-tint: '#ffb1c4'
  primary: '#ffb1c4'
  on-primary: '#65002e'
  primary-container: '#ff4a8d'
  on-primary-container: '#590028'
  inverse-primary: '#ba005b'
  secondary: '#dcfdff'
  on-secondary: '#00373a'
  secondary-container: '#00f1fd'
  on-secondary-container: '#006a6f'
  tertiary: '#abd600'
  on-tertiary: '#283500'
  tertiary-container: '#7c9c00'
  on-tertiary-container: '#222e00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd9e1'
  primary-fixed-dim: '#ffb1c4'
  on-primary-fixed: '#3f001a'
  on-primary-fixed-variant: '#8f0044'
  secondary-fixed: '#6ff6ff'
  secondary-fixed-dim: '#00dce6'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f53'
  tertiary-fixed: '#c3f400'
  tertiary-fixed-dim: '#abd600'
  on-tertiary-fixed: '#161e00'
  on-tertiary-fixed-variant: '#3c4d00'
  background: '#1f0e13'
  on-background: '#fbdae1'
  surface-variant: '#442f34'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.5'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  data-label:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  data-value:
    fontFamily: JetBrains Mono
    fontSize: 20px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  container-max-width: 1440px
---

## Brand & Style
The design system is a high-energy fusion of late-90s futurism and contemporary "Kawaii" aesthetics. It reimagines the smart home dashboard not as a utility, but as a digital sanctuary that is vibrant, kitsch, and unapologetically expressive. Target users are tech-savvy trendsetters who value personality over corporate minimalism.

The visual language is a "Cyber-Glow" mix of **Glassmorphism** and **Skeuomorphism**. Interfaces should feel tactile, like jelly-coated hardware or sticker-bombed acrylic. Emotional responses should range from nostalgia to hyper-active joy. Key motifs include 8-bit pixel art accents, four-pointed sparkles (✦), and chrome-like gradients that evoke a Y2K handheld gaming vibe.

## Colors
The palette utilizes high-saturation neon primaries against a deep, glossy foundation. 

- **Neon Pink (#ff007f):** Used for primary actions and "active" states (e.g., lights ON).
- **Bright Cyan (#00f3ff):** Used for secondary info, cooling systems, and interactive strokes.
- **Lime Green (#ccff00):** Used for energy metrics, battery levels, and success states.
- **Lavender (#b19cd9):** Used for background accents, soft shadows, and non-critical status icons.

The background should utilize a dark glass effect with a `backdrop-filter: blur(20px)` to allow background "aura" glows of pink and cyan to bleed through, creating a sense of depth and luminosity.

## Typography
Typography balances "bubbly" expressive headlines with technical precision for data. 

- **Headlines:** Use *Bricolage Grotesque* for its quirky, rounded terminal ends that mimic the "Bubblegum Sans" aesthetic while remaining modern. Headlines should often feature a 2px text-stroke or a soft glow in the primary color.
- **Body:** *Be Vietnam Pro* provides a clean, contemporary sans-serif feel that ensures readability amidst the visual noise.
- **Data & Labels:** *JetBrains Mono* is used for all smart home metrics (temperature, humidity, voltage). This creates a "hacker-kawaii" contrast, making the data feel like it’s part of a retro console BIOS.

## Layout & Spacing
The layout follows a fluid-to-fixed grid hybrid. Surfaces should feel like "floating modules" rather than a rigid structural grid.

- **Grid:** A 12-column system on desktop with wide 24px gutters to allow for decorative border glows to breathe.
- **Padding:** Internal card padding is generous (24px - 32px) to accommodate "sticker" accents that may overlap the content areas.
- **Responsibility:** On mobile, the grid collapses to a single column, but maintaining a "stacked sticker" look where cards have slight rotations (1-2 degrees) to mimic a physical dashboard aesthetic.

## Elevation & Depth
Depth is created through luminosity and "jelly" textures rather than traditional gray shadows.

- **Inner Glows:** Every primary card must have a 1px inner border with a `linear-gradient` (Cyan to Pink) and a soft 10px inner box-shadow of the same colors.
- **Outer Glows:** Instead of black shadows, use "Neon Dropshadows." Use the primary color at 30% opacity with a large blur (20px) to make elements appear as if they are sitting on a light table.
- **The Gloss Factor:** Top-level interactive elements should feature a "specular highlight"—a semi-transparent white gradient overlay at the top 50% of the element to simulate a curved, plastic surface.

## Shapes
The shape language is dominated by exaggerated "squircle" forms and "pill" shapes. 

- **Base Radius:** 16px (rounded-lg) for standard cards. 
- **Interactive Radius:** Buttons should be full-pill (rounded-xl) to look like jellybeans.
- **Sticker Motifs:** Use star-shaped clipping masks or SVG "bursts" for notifications and special status badges.
- **Pixel Borders:** For the "Console Terminal," use a stepped, pixelated border style (2px width) to distinguish technical areas from lifestyle areas.

## Components
- **Jelly Buttons:** High-gloss, 3D-effect buttons. They use a thick 4px bottom border (darker shade of the button color) to simulate physical depth. On press, the border disappears and the element shifts 2px down.
- **Smart Cards:** Featured with "Holographic" gradient borders. Use a `conic-gradient` of the primary palette for the border stroke.
- **Sticker Chips:** Status indicators that look like physical stickers, featuring a white 2px "die-cut" border and a slight drop shadow.
- **Console Terminal:** A dedicated section for logs/automation scripts with a dark green background, *JetBrains Mono* text, and a bezel that resembles a 90s handheld game screen (complete with fake "Power" and "Battery" LEDs).
- **Sparkle Accents:** Randomly placed `✦` (star) icons in corners of containers, using `animate-pulse` to create a shimmering effect.
- **Input Fields:** Thick cyan borders with pink focus states. The cursor should be a blinking block character (█) to maintain the retro-tech vibe.
