[README.md](https://github.com/user-attachments/files/32178055/README.md)
# lawschoolalternatives.com

A comprehensive, independent guide for people asking: *Is law school actually worth it?*

Live at **[lawschoolalternatives.com](https://lawschoolalternatives.com)**

---

## What's on the site

- **13+ careers that don't require a JD** — compliance officer, paralegal, legal ops, policy analyst, mediator, contract manager, legal tech, and more — with salary ranges for each
- **Alternative degrees** — MLS (Master of Legal Studies), MPP, MPA, MBA, paralegal certificate — what they cost, who hires them, and when they make sense
- **Real stories** — people who left law school, never enrolled, or pivoted mid-career
- **Famous law school dropouts** — household names who skipped or left and did just fine
- **Honest resources** — books (including Amazon affiliate links), subreddits, podcasts, and organizations
- **FAQ** — common questions answered plainly, with schema.org structured data for AI/search visibility

---

## Tech

Single-file static site (`index.html`). No build step, no dependencies, no framework.

- Pure HTML, CSS, and vanilla JS in one file
- Notion-style layout: emoji rows, clean sans-serif typography (Inter via Google Fonts)
- Full light/dark theme support via CSS custom properties
- SEO: meta tags, Open Graph, Twitter Cards, canonical URL
- GEO (AI/LLM visibility): JSON-LD structured data (WebSite, FAQPage, ItemList schemas), schema.org microdata
- Responsive, mobile-friendly

---

## Deployment

Deployed via [Vercel](https://vercel.com) connected to this GitHub repo. Pushing to `main` auto-deploys to production.

No build command or output directory needed — Vercel serves `index.html` directly.

---

## Affiliate disclosure

Some book links use an Amazon Associates affiliate tag (`nk1900-20`). Clicking them and buying something earns a small commission at no cost to you. All recommendations are independent.

---

## Contributing

Spotted something outdated, a broken link, or a career path that's missing? Open an issue or a PR. Contributions welcome.
