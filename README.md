# build4paws.ro

Site-ul oficial al Asociației **Build 4 Paws** — tech NGO care construiește infrastructura software pentru bunăstarea animalelor în România.

## Stack

- **[Astro](https://astro.build/)** — generator static (HTML pur, zero JS by default)
- **[Tailwind CSS v4](https://tailwindcss.com/)** — design tokens CSS-first
- **Google Fonts** — Funnel Display (headings) + Rethink Sans (body)
- **[Lucide](https://lucide.dev/)** — iconset
- **[Cloudflare Pages](https://pages.cloudflare.com/)** — hosting (gratuit, CDN global, SSL)

## Comenzi

```sh
npm install       # instalează dependențele
npm run dev       # pornește dev server pe http://localhost:4321
npm run build     # build static în ./dist
npm run preview   # preview local după build
```

## Structura

```
src/
├── components/   # Button, Card, Container, Section, Header, Footer
├── layouts/      # BaseLayout (meta, fonts, shell)
├── pages/        # rute (index, despre, proiecte, contact)
└── styles/       # global.css cu brand tokens (Tailwind v4 @theme)
public/
├── logo/         # variante logo (horizontal, vertical, white)
└── favicon.svg   # symbol navy
```

## Design tokens

Brand Book v1.0 (martie 2026) de [Tea Tomescu](https://teatomescu.ro).

**Culori primare:** Navy `#041A49` · Orange `#F95905` · Light Grey `#F2F1F0`
**Tipografie:** H1=64px · H2=48px · H3=36px · H4=24px · P=16px

## Deploy

Cloudflare Pages — build command `npm run build`, output directory `dist`.

## Licență

Cod: MIT. Brand assets (logo, identitate vizuală): © Build 4 Paws.
