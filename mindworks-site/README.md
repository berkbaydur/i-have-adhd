# Mindworks website (draft)

A single self-contained static page (`index.html`): no build step, so it can be hosted anywhere (Netlify, Cloudflare Pages, GitHub Pages, or your current host).

## Design system
- **Type:** Schibsted Grotesk (display/body) + IBM Plex Mono (technical labels, data).
- **Colour:** warm paper `#F1EEE7`, ink `#15140F`, one signal accent `#E8480C` (international orange). Automatic dark mode.
- **Motif:** engineering datasheet: numbered sections (§01…), figure captions, hairline rules, square corners.
- **Motion:** one staged hero load, a live device→edge→cloud simulation, a signal pulse along the IoT stack, timesheet bars filling on scroll. Everything respects `prefers-reduced-motion`.

## Files
- `index.html`: the site
- `logo.svg`, `logo-dark.svg`: vector logo (light and dark backgrounds), redrawn in Marcellus from the original PNG
- `favicon.svg`: browser tab icon
- `fonts/`: self-hosted, Latin-subset web fonts, so the site makes no third-party requests and sets no cookies

## Still to confirm before going live
- [ ] Companies House company number (footer, highlighted in orange)
- [ ] Contact email `hello@mindworkss.co.uk` exists and is monitored
- [ ] Year(s) of the Encore Networks engagement, if you want a date on the case study
- [ ] Optional: founder photo to replace the "BB" monogram in Leadership
