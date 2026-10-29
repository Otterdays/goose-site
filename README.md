# Goose site

Static site for the Goose game prototype. Plain HTML, no build step.

Source of truth lives in the game repo under `site/`; this repo is a deploy mirror.

## Deploy on Vercel

Import the repo in Vercel. Framework preset: **Other**. No build command, output directory `.` (set in `vercel.json`).

## Local preview

```bash
npx serve .
```
