# Sandesh Tiwari Portfolio

Files:
- index.html
- about.html
- experience.html
- projects.html
- skills.html
- education.html
- contact.html
- style.css
- script.js

## Version 3 design

A redesign built around the vernacular of an engineering drawing sheet,
instead of a generic dark SaaS theme:

- **Sheet-meta strip** at the top of every inner page (drawn by / sheet
  number / scale) replaces the old breadcrumb and pill-badge eyebrow.
- **Revision table** (Rev A / B / C) presents the career timeline the way
  a drawing revision block would.
- **Legend-style skills page** — each skill category has its own swatch
  colour, echoing a one-line diagram legend.
- **Hand-drawn SVG hero diagram** on the homepage: a distribution pole
  with sagging conductors (drawn once on load) and a small current-flow
  pulse animation, plus a span dimension callout — literal to the pole
  loading / sag-tension work described in Experience.
- Typeface: IBM Plex Sans + IBM Plex Mono (the mono face is used only for
  drawing-style labels, not body text).
- Palette: near-black ink background, warm brass/copper accent, muted
  teal secondary, paper-toned light sections — no purple/pink gradient
  glow effects.
- Motion is deliberately limited to the one hero sequence and small
  hover/focus states; `prefers-reduced-motion` is respected throughout.

## Before publishing

1. Add a headshot if you want one — the design currently has no photo
   placeholder; add an `<img>` where you'd like it (e.g. the About page
   sidebar) and reference `images/profile.jpg`.
2. Add your latest resume at `resume/Sandesh_Tiwari_Resume.pdf`.
3. Replace `YOUR_EMAIL_HERE`, `YOUR_LINKEDIN_URL_HERE` and
   `YOUR_GITHUB_URL_HERE` in `contact.html`.
4. Review dates, the diploma title/year on `education.html`, and project
   wording against your latest CV.
5. Upload all files to the root of your GitHub repository or Cloudflare
   Pages project (sandeshtiwari.com.np).
