# Aravali Ventures

Website for [aravali.ventures](https://aravali.ventures): the Udaipur Investor Summit by Aravali Ventures, built with [Astro](https://astro.build) and deployed on Vercel.

## Develop

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # outputs to dist/
```

## Edit content

Home page (Aravali Ventures) is `src/pages/index.astro`. The Udaipur Investor Summit page is `src/pages/udaipur-investor-summit.astro`, with its markup in `src/content/summit.html` (exported from the summit design in Claude). Images are in `public/images/`.
Global styles, phone-width overrides and SEO tags are in `src/layouts/Base.astro`; the Founders/Investors/Partners toggle and the invitation form (opens an email to contact@aravali.ventures) are scripted in `src/pages/index.astro`.

## Deploy

Vercel builds every push to `main` automatically (framework preset: Astro, output: `dist`).
