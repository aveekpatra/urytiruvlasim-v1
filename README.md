# U Blanickych rytiru (first version)

First version of the website for U Blanickych rytiru, the restaurant in Vlasim castle. This build is live at [modern-metro-restaurant-site.vercel.app](https://modern-metro-restaurant-site.vercel.app).

The current site is a separate Next.js project running at [www.urytiruvlasim.cz](https://www.urytiruvlasim.cz).

The site is in Czech with an English version under `/en`.

## Pages

- `/`: hero with opening hours, featured dishes, about, gallery, reviews, call to action, contact
- `/menu`: full menu with search and sort by price
- `/gallery`: photo gallery with image modal
- `/contact`: contact details and embedded Google Map

Each page also exists under `/en` (for example `/en/menu`).

## Stack

- React 19, TypeScript, Vite 6
- React Router 7
- i18next with react-i18next (Czech and English)
- Tailwind CSS 4, Motion, Lucide icons

## Getting started

```bash
bun install      # or npm install
bun run dev      # or npm run dev
```

Other scripts:

```bash
npm run build    # type-check and build to dist/
npm run preview
npm run lint
```

No environment variables are needed.

## Project structure

```
src/pages/          route pages: Home, Menu, Gallery, Contact
src/components/     sections, navigation, language switcher and router
src/i18n/locales/   cs.json and en.json with all site text
public/             restaurant photos and logo
```
