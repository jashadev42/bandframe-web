# BandFrame Website

Marketing site + legal pages for BandFrame, served at [bandframe.app](https://bandframe.app) via Vercel.

- `/` — landing page
- `/privacy/` — privacy policy
- `/terms/` — terms of use
- `/support/` — support & contact

Plain static HTML/CSS, no build step. Styles mirror the app's design tokens (`src/theme/tokens.ts` in the app repo).

To swap in real screenshots: drop images in `/assets/` and replace the `.phone-screen` placeholder contents in `index.html` with `<img src="/assets/shot-1.png" alt="..." />`.
