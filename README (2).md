# CHIMERA — Cyborg Augmentation Landing Page

A responsive, single-file landing page for a fictional cybernetic augmentation lab.
Built around one concept: **the seam** — the exact line where flesh meets machine.

**Live concept:** warm copper (organic) vs. cold cyan-steel (synthetic), meeting at a draggable "seam" reveal.

## Highlights
- **Signature interaction:** drag (or arrow-key) the seam divider to reveal the synthetic layer under the organic one.
- Animated HUD "sync core" reticle and an ECG→square-wave pulse strip (organic pulse morphing into a digital signal).
- Hover-to-expand augmentation spec cards with a cursor-tracking glow.
- Scroll-reveal animations, fixed nav with live status, telemetry marquee, client-side access form.
- Fully responsive (desktop → mobile), keyboard focus states, and `prefers-reduced-motion` respected.

## Tech
Plain HTML + CSS + vanilla JS. **No build step, no dependencies.** Google Fonts (Chakra Petch / Inter / Space Mono) loaded via CDN.

## Run locally
Just open `index.html` in a browser. That's it.

## Deploy on GitHub Pages
1. Push this repo to GitHub.
2. Settings → Pages → Source: `main` branch, `/root`.
3. Your live URL appears in a minute or two.

## Files
- `index.html` — the entire site (markup, styles, and scripts inline).
