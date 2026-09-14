# Design System

## Visual Theme

A late-night screening room: black velvet, oxidized metal, one narrow line of champagne light, and cool projector spill. The palette is dark and restrained, with oxidized teal as the brand anchor and champagne used sparingly for emphasis.

## Color Palette

- Background: `oklch(0.085 0 0)`
- Raised surface: `oklch(0.135 0.008 170)`
- Primary / oxidized teal: `oklch(0.55 0.086 170)`
- Accent / champagne: `oklch(0.82 0.105 83)`
- Ink: `oklch(0.94 0.008 83)`
- Muted ink: `oklch(0.72 0.014 83)`
- Rule: `oklch(0.30 0.018 170)`

## Typography

- Display: Bahnschrift Condensed with Arial Narrow and sans-serif fallbacks.
- Body: Aptos with Segoe UI and system sans-serif fallbacks.
- Headings use compact width and measured tracking; body copy remains sentence case and comfortably spaced.

## Layout

- Mobile-first, single-column reading flow.
- Maximum reading width of 72ch for policy text.
- Wider, asymmetric homepage composition above 860px.
- Spacing follows a deliberate 8px-based rhythm with larger cinematic intervals between major sections.

## Components

- Masthead: compact wordmark, persistent three-link navigation, visible current-page state.
- Frame mark: four corner strokes that evoke a camera frame without using an image asset.
- Statement: one dominant headline with restrained supporting copy.
- Integration boundary: concise explanation of what the public site does and does not do.
- Policy article: numbered sections, strong anchor targets, no card grid.
- Footer: studio name, TikTok handle, policy links, and contact placeholder where required.

## Motion

No continuous motion. A short first-load reveal may run only when motion is permitted; reduced-motion users receive an instant render.
