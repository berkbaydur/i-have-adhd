# Mindworks website (draft)

A single self-contained static page (`index.html`): no build step, so it can be hosted anywhere (Netlify, Cloudflare Pages, GitHub Pages, or your current host).

## Design system
- **Type:** Schibsted Grotesk (display/body) + IBM Plex Mono (technical labels, data).
- **Colour:** warm paper `#F1EEE7`, ink `#15140F`, one signal accent `#E8480C` (international orange). Automatic dark mode.
- **Motif:** engineering datasheet: numbered sections (§01…), figure captions, hairline rules, square corners.
- **Motion:** one staged hero load, a live device→edge→cloud simulation, a signal pulse along the IoT stack, timesheet bars filling on scroll. Everything respects `prefers-reduced-motion`.

## Before going live: fill every orange-highlighted placeholder
- [ ] Legal company name, Companies House number, registered office, VAT number (footer)
- [ ] Year Mindworks was founded, sectors/clients sentence (Company)
- [ ] Founder line: years of experience, education or previous employers, photo (Leadership)
- [ ] 3–4 real case studies: sector, year, role, stack, one verifiable outcome. Anonymise clients if NDAs require it
- [ ] Higher-resolution logo (SVG ideally; the current PNG is 300px wide and softens on retina screens)
- [ ] Company and personal LinkedIn URLs; confirm the contact email address
- [ ] Confirm London as your base (it drives the clock and coordinates in the hero)
- [ ] Trim the IoT stack list to technologies you have actually shipped with
- [ ] Confirm process claims (free 30-minute call, reply within one working day)
- [ ] Privacy notice page (required under UK GDPR if you collect any personal data)
