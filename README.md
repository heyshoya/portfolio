# Yash Nemane - Portfolio

Personal portfolio of Yash Nemane, a third-year Electrical Engineering student (SSGMCE).
Built with React and Vite: an animated landing page, an About section, projects, internships,
certificates, skills and a contact form, with an intro video and background music.

Live: https://heyshoya.github.io/portfolio/

## Run locally

```bash
npm install
npm run dev
```

The dev server opens at http://localhost:3000.

## Build

```bash
npm run build
```

The production site is generated in `dist/`. Asset paths are relative (`base: './'`),
so the build works at the root of a domain and under a GitHub Pages project URL.

## Deploy

The `main` branch holds the source. The built site lives on the `gh-pages` branch, which
GitHub Pages serves. To publish a change, run `npm run build` and push the contents of
`dist/` (plus an empty `.nojekyll` file) to `gh-pages`.

## Project layout

- `index.html` - page markup, styles and scripts
- `src/` - React components (certificates cards)
- `public/` - videos, audio, fonts, icons, certificate and project images, CV
