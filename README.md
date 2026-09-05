# Wayfinder Therapeutic — Website

A warm, welcoming, and inclusive marketing website for **Cliff Stornel, MACP** and his
practice, **Wayfinder Therapeutic**. Built as a lightweight static site (plain
HTML, CSS, and a little JavaScript) — no build step, hosts anywhere.

## Pages

| File | Page |
|------|------|
| `index.html` | Home — hero, inclusive statement, "what therapy is like", services preview, narrative-therapy intro, steps, CTA |
| `about.html` | About — Cliff's bio, philosophy, education & credentials |
| `services.html` | Services — individual / couples / group therapy, modalities, formats, fees |
| `faq.html` | FAQ — expandable common questions |
| `contact.html` | Contact — Jane booking button, email, Instagram, and availability details |

Shared assets: `css/styles.css`, `js/main.js`.

## ✅ Before you go live: fill in the placeholders

Everything that needs your real information is wrapped in **`[SQUARE BRACKETS]`**
so it's easy to find. Search the project for `[` (or use the list below) and
replace each one.

| Placeholder | Where | Replace with |
|-------------|-------|--------------|
| `wayfinder@wayfindertherapeutic.com` | footer (all pages), contact | Service email address |
| Confidentiality details | `faq.html` | Confirm the legal and ethical wording for the applicable jurisdiction |
| Therapy modalities | `services.html` | Confirm that the listed approaches match Cliff&rsquo;s actual practice |

### Contact
The contact page directs visitors to email Wayfinder Therapeutic or schedule through Jane.

## Running locally
It's static — just open `index.html` in a browser. Or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying
Works on any static host: **GitHub Pages**, **Netlify**, **Cloudflare Pages**,
**Vercel**, or a traditional web host. For GitHub Pages, enable Pages on this
repo and point it at the branch root.

## Design notes
- **Palette:** Forest & Gold — deep forest green + warm gold/sand on a warm cream
  background. Defined as CSS variables at the top of `css/styles.css`.
- **Fonts:** Fraunces (serif headings) + Nunito Sans (body), via Google Fonts.
- **Tone:** warm, upbeat, welcoming — "wayfinding / finding your path" language,
  strongly inclusive of all genders, relationship styles, and 2SLGBTQIA+ clients.
- Fully responsive with a mobile menu, an accessible FAQ accordion, and a Treaty 1
  land acknowledgement in the footer.
