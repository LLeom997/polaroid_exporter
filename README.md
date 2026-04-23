# Polaroid Print Studio

A browser-based tool to arrange photos in polaroid or plain grid layouts, ready to print on A4 or A3 paper.

## Features
- Upload multiple images (JPG, PNG, WebP)
- Polaroid frame or plain (no border) mode
- A4 / A3 · Portrait / Landscape
- Adjustable image size, gap, margin via sliders
- Custom frame color + optional shadow
- Caption text on polaroids
- **Download as PNG** (all pages stacked)
- **Download as PDF** (one page per PDF page, print-ready)
- Multi-page support — auto-calculates grid to fit max images

## Deploy to Vercel (30 seconds)

### Option A — Vercel CLI
```bash
npm i -g vercel
vercel
```
Follow prompts. Done.

### Option B — Vercel Dashboard
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import the repo → Deploy
4. No build command needed — it's a static site

### Option C — Drag & Drop
1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag the `polaroid-studio` folder into the deploy area

## Local dev
```bash
npx serve public
# → open http://localhost:3000
```

## Print tips
- **PDF**: Open in any PDF viewer → Print → scale 100% (actual size) for accurate mm dimensions
- **PNG**: Print via browser or image viewer → set paper size to match A4/A3, disable scaling
- For best results use 200 DPI (the app renders at 200 PPI internally)
