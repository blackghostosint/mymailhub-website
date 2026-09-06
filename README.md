# MyMailhub Marketing Site (`mymailhub.app`)

The official marketing and sales website for **MyMailhub**, built with [Astro](https://astro.build) and deployed to [Netlify](https://netlify.com).

## Overview

MyMailhub is front-counter package and mail intake software built by independent pack-and-ship store operators for independent pack-and-ship counters.

- **Stack:** Astro 7, Tailwind CSS 4, DM Sans typography.
- **Brand System:** *Black and Gold Elegance* (`#000000` Black, `#14213D` Oxford Navy, `#FCA311` Marigold Gold, `#E5E5E5` Platinum Gray, `#FFFFFF` White).
- **Core Architecture:**
  - `mymailhub.app` (root) &rarr; Static marketing/sales site on Netlify.
  - `app.mymailhub.app` &rarr; Multi-tenant web application.

## Pages

1. **Home (`/`)** — Compressed StoryBrand (SB7) sales letter: owner pain, unbroken 3-step counter motion, assisted roster migration callout, legacy software comparison grid, and gated walkthrough video.
2. **Pricing (`/pricing`)** — Hormozi value-math breakdown for the $39/month flat all-in plan.
3. **How It Works (`/how-it-works`)** — Technical walkthrough of camera intake, automated SMS/email notifications, and digital signature release.
4. **FAQ (`/faq`)** — Straightforward answers on assisted migration, hardware compatibility, zero-install cloud security, and cancellation terms.

## Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build static output to dist/
npm run build

# Preview build locally
npm run preview
```
