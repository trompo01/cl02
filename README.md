# Bibliografía

Minimalistic bilingual template (ES/EN) for 6 books by Vanina Vergara and Pablo Mera.

## Features
- Dark background, white letters, high contrast
- True 3D tilt on mouse move + gentle float animation
- Neon accents, sparkling link effects
- Mobile responsive (2 columns desktop, stacks on phone)
- 7 pages in a single `index.htm` file
- Background music loops (`kelvin.aac`)

## Structure
- **Page 1**: Welcome grid (2×3) with 6 book covers + language buttons
- **Pages 2-5**: Spanish editions
- **Pages 6-7**: English editions
- Each page has its own background cover image

## How to publish on GitHub Pages
1. Create a new repository named `bibliografia` (or any name)
2. Upload these files to the root:
   - `index.htm`
   - `kelvin.aac` (add your audio file - not included)
   - All images: `vesp.jpg`, `pesp.jpg`, `lamp.jpg`, `crc.jpg`, `veng.jpg`, `peng.jpg`, `amazon.png`, `bam.png`, `bookshoporg.png`, `bookstw.png`, `mercadolibre.png`, `v1.png`, `saxo.jpg`, `ibs.png`, `feltri.png`
3. In repo Settings → Pages, set Source to `main` branch / root
4. Your site will be live at `https://<username>.github.io/bibliografia/`

## Notes
- All Amazon links were normalized from `swatch₀` to `swatch_0` for functionality
- IBS and Feltrinelli logos are provided as PNG (`ibs.png`, `feltri.png`) instead of SVG for compatibility
- Replace placeholder covers (`vesp.jpg`, `pesp.jpg`, `veng.jpg`, `peng.jpg`) with final artwork if needed
- Music autoplays on first click due to browser policies

© 2026 - Ready to publish
