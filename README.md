# ASSAM TEA — Steeped in Silence

A premium tea ritual web experience.

## Products

- **DAWN** — Morning Clarity Blend (₹ 890)
- **DUSK** — Evening Unwind Blend (₹ 950) — Bestseller
- **NIGHT** — Deep Rest Blend (₹ 1,050)

## Run locally

```bash
npm install
npm start
```

Then open http://localhost:3000

## Deploy

This is a static site that can be deployed to:

- **Vercel** (recommended) — just import this repo at https://vercel.com/new
- **GitHub Pages** — auto-deploys from the `gh-pages` branch
- **Netlify** — drag-and-drop the `public/` folder

## Structure

```
.
├── public/
│   ├── index.html              # Main page
│   ├── dawn-product.png        # Morning blend image
│   ├── dusk-product.png        # Evening blend image
│   ├── night-product.png       # Night blend image
│   └── tea-story-final.mp4     # Scroll-scrub video
├── package.json
└── vercel.json
```

## Tech

- Vanilla HTML/CSS/JS (no build step)
- GSAP + ScrollTrigger for animations
- Canvas-based video frame scrubbing
- Mobile responsive

---

Made with care.
