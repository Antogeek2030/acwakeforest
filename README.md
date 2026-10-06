# AC Repair Wake Forest NC — Astro Site

Static Astro site for **acrepairinwakeforestnc.com**, optimized for Cloudflare Pages.

## Features
- Responsive, mobile-first design
- Cool blue + cyan color theme
- OpenStreetMap embed for 105 E Young St, Rolesville, NC 27571
- SEO: meta tags, canonical, JSON-LD HVACBusiness schema, sitemap, robots.txt
- Fast static build for Google indexing
- Cloudflare Pages ready (static output, no adapter needed)

## Phone number
Placeholder: **(919) 555-0199** — replace across files (search for `9195550199` and `555-0199`).

## Location
105 E Young St, Rolesville, NC 27571, USA

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub/GitLab repo.
2. In Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Build settings:
   - **Framework preset:** Astro
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Add custom domain `acrepairinwakeforestnc.com`.
5. Submit `https://acrepairinwakeforestnc.com/sitemap-index.xml` in Google Search Console.

## Local development
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```
Output is in `dist/`.

## Notes
- Site is fully static (`output: 'static'` by default) — ideal for Pages and SEO.
- `@astrojs/sitemap` generates `/sitemap-index.xml` at build time.
- `public/robots.txt` points crawlers to the sitemap.
