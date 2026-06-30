# Environmental Enterprises USA — Homepage Mockup

A modern, responsive homepage redesign concept for **Environmental Enterprises USA, Inc.**, a NELAP-accredited environmental testing laboratory in Slidell, Louisiana.

This is a static front-end mockup (single `index.html` with an embedded stylesheet and a small vanilla-JS script — no build step).

## Preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 4173
# then visit http://localhost:4173
```

## Highlights

- **Full-bleed video hero** (offshore rig at sunset) with a brand-tinted overlay and poster fallback
- **Transparent header** over the hero that transitions to a solid white bar on scroll
- **Mobile nav drawer** with overlay, focus on accessibility (Esc to close, scroll lock)
- Sections: Testing & Analysis, Sampling Logistics (chain of custody, pickup routes, holiday updates), Client Data Portal, Accreditations (real NELAP/TCEQ/LDEQ certs), and a direct-email contact form
- Palette: light blue · light green · white

## Structure

```
index.html          # The full page (markup + styles + script)
assets/
  img/              # Logo, accreditation certificates, lab photos, hero poster
  video/            # Web-optimized hero background (MP4)
```

## Notes

- The contact form, portal login, and hamburger drawer are front-end only — the form and portal need a backend (email service / auth) to go live.
- Imagery and accreditation certificates were sourced from the company's existing materials for mockup purposes.
