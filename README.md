# YURIY G. / fijimlk — Portfolio v3

A single-page Web3 Community & Ecosystem portfolio. Includes an interactive Three.js sculpture, experience, selected technical projects, contact links, and a downloadable one-page public CV (no surname).

## Run locally

1. Install Node.js 20+.
2. In this folder run `npm install` then `npm run dev`.
3. Open `http://localhost:5173/`.

## Publish without GitHub

Run `npm run build`. Upload the generated `dist` folder to Cloudflare Pages using Direct Upload (Cloudflare Dashboard → Workers & Pages → Create → Pages → Upload assets). The CV is in `public/` and Vite copies it to `dist/` during build.

## Notes

The browser extension is linked to its Chrome Web Store listing. Ritual Market Signal Engine is accurately labeled as a historical prototype. No GitHub account is required. No private email or surname appears in public-facing content. Before sharing, test navigation, CV download and mobile layout.


## v4 avatar hero
Replaced chrome Three.js sculpture with original uploaded avatar. Circular portrait gently moves, orbit rings rotate, and desktop pointer controls a subtle 3D tilt. Motion respects reduced-motion settings. No new dependencies.


## v6
Hero redesigned around the public identity YURIY G. / @fijimlk. The slogan is secondary, role is prominent, and portrait/other sections are preserved.
