# Responsive Design Tokens & Mobile-First CSS Architecture

Standalone responsive dashboard implementation using modern CSS custom properties,
CSS Grid, Flexbox, glassmorphism, and mobile-first breakpoints.

## Files

- `index.html` — responsive demo
- `style.css` — complete design-token and responsive CSS

## Breakpoints

- Base: 320px+
- Tablet: 768px+
- Desktop: 1024px+
- Large desktop: 1440px+

## Design tokens

The `:root` block contains:

- Brand and semantic colors
- Light/dark theme variables
- Typography scale
- Spacing scale
- Border radii
- Shadows
- Glass blur
- Layout dimensions
- Transitions

## Responsive behavior

- Mobile: single-column layout
- Tablet: two-column layout
- Desktop: 12-column CSS Grid
- Large desktop: increased spacing
- `overflow-x: hidden` prevents accidental horizontal scrolling
- `min-width: 320px` supports narrow mobile viewport testing

## Run

Open `index.html` in a browser.

For GitHub Pages, upload both files to a repository and enable Pages from
the repository settings.

## Screenshot checklist

Capture the demo at:

1. 320 × 800
2. 768 × 1024
3. 1024 × 768
4. 1440 × 900

Also capture both light and dark themes if screenshots are required for
the project submission.
