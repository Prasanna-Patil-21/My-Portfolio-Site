PRASANNA PATIL — INTERACTIVE 3D PORTFOLIO
=========================================

HOW TO VIEW
-----------
Just double-click  index.html  — it opens in your browser.
(An internet connection is needed the first time, because the 3D engine,
animation library and fonts load from a CDN.)

IMPORTANT
---------
Keep the  assets/  folder in the SAME place as index.html.
It holds your video and photos:
  assets/hero-bg.jpg / .webp  ... the suit/ocean shot — full-bleed hero background
  assets/hero.mp4 / hero.webm ... the Norway fjord clip (seamless loop) — shown in "About"
  assets/hero-poster.jpg      ... first-frame fallback for the fjord video
  assets/detail.jpg / .webp   ... the watch close-up — cinematic quote interlude
  assets/work.jpg / .webp     ... the "how I work" photo
  assets/about.jpg / .webp    ... spare casual photo (not currently shown)

If you move index.html, move the assets/ folder with it.

WHAT'S INSIDE / INTERACTIONS
----------------------------
- Live WebGL "constellation" background that reacts to your mouse (Three.js)
- Custom cursor + magnetic buttons + smooth scrolling
- Hero title reveal, scroll-reveals and parallax (GSAP)
- A drag-to-spin 3D sphere of your skills (Skills section)
- A live "document -> validated JSON" demo for PRANCER (Work section)
- Animated stat counters, depth timeline, credential grid
- Fully responsive (desktop / tablet / mobile) and respects
  "reduce motion" accessibility settings

EDITING TEXT
------------
All content lives directly in index.html — search for the wording you want
to change and edit it. Styling is in the <style> block at the top; behaviour
is in the <script> block at the bottom.

HOSTING IT ONLINE (optional)
----------------------------
Upload the whole folder (index.html + assets/) to any static host:
GitHub Pages, Netlify (drag-and-drop), Cloudflare Pages, or Vercel.
No build step required.

Built 2026.
