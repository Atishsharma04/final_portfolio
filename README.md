# Atish Sharma — Portfolio

A single-page portfolio built as one self-contained `index.html` (no build step, no dependencies).

## Deploy on Vercel

**Option 1 — Vercel dashboard**
1. Push this folder to a GitHub repo (or drag-and-drop the folder into [vercel.com/new](https://vercel.com/new)).
2. Import the repo in Vercel → Framework Preset: **Other** → leave build command empty → Deploy.

**Option 2 — Vercel CLI**
```bash
npm i -g vercel
cd atish-portfolio
vercel
```
Follow the prompts (any defaults are fine since there's no build step) and Vercel will give you a live URL.

## Editing
Everything — HTML, CSS, and the inline SVG illustration — lives in `index.html`. Open it in any editor and edit directly; no build tools required.
