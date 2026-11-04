# Aravali Ventures

Website for [aravali.ventures](https://aravali.ventures), built with [Astro](https://astro.build) and deployed on Vercel.

## Develop

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # outputs to dist/
```

## Edit content

All page copy (tagline, focus areas, principles, contact email) lives at the top of `src/pages/index.astro`.
Colors and fonts are in `src/layouts/Base.astro`.

## Deploy

Vercel builds every push to `main` automatically (framework preset: Astro, output: `dist`).
