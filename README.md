# Bibliografía — Static Site (9 pages)

This repository contains a small static 9-page site titled "Bibliografía" optimized for mobile (Android & iPhone) with a dark metallic theme, high-contrast white typography, animated headings, 3D buttons with sparkle effects, and looping background audio.

Files:
- index.html — Page #1 (welcome grid with 8 square 3D image-buttons + language buttons + main CTA)
- page2.html — #2 (CUANDO LA FAMILIA SE ROMPE EN SILENCIO)
- page3.html — #3 (MANUAL DEL INADAPTADO LÚCIDO)
- page4.html — #4 (EL JARDÍN DE LOS QUE VOLVIERON)
- page5.html — #5 (EL JARDÍN DE LUMA)
- page6.html — #6 (CARACOL – Menú de Autor)
- page7.html — #7 (CARACOL Author's Menu)
- page8.html — #8 (WHEN FAMILIES FRACTURE IN SILENCE)
- page9.html — #9 (THE LUCID MISFIT’S HANDBOOK)
- drake.aac — (background audio file; place original file here)
- All referenced images (vesp.jpg, pesp.jpg, lamp.jpg, EJDL.jpg, crc.jpg, CRCENG.png, veng.jpg, peng.jpg, py.jpg, amazon.png, mercadolibre.png, etc.)

Usage:
1. Put all HTML files and the listed media files in the same directory.
2. Open `index.html` in a browser to preview locally.
3. To publish, push the folder to a GitHub repository and enable GitHub Pages (use the repository's `gh-pages` branch or the `main` branch depending on your repo settings).

Notes and accessibility considerations:
- Background audio is set to autoplay + loop. Modern mobile browsers may block audible autoplay. The site attempts a play() on load and will resume playback on first user interaction (tap/click) if blocked.
- All external links open in a new tab (target="_blank" rel="noopener") and internal navigation uses simple page links (page2.html … page9.html).
- Headline split-animation values:
  - Stagger between characters: ~0.04 s
  - Duration per character: ~700 ms
  - Easing: cubic-bezier(.2,.85,.25,1)
  These values create a subtle organic reveal without harming readability.
- Buttons are designed with clear contrast, large touch targets, and a 3D effect (box-shadow + transform).
- Pages #2..#9 include the requested footer text:
  [*eurobooks.sk y eslite.com solo se acceden usando VPN]

Mobile optimization:
- Uses responsive CSS grid and aspect-ratio to ensure the 2x4 grid on index.html displays all 8 square tiles on common phone widths.
- Touch targets follow recommended sizes (approx 44px+ height).
- The site uses simple, performant CSS and no heavy JS frameworks.

If you'd like, I can:
- Package everything into a ZIP download.
- Create the GitHub repo and push these files (I will need the repo owner/name and permission to write).
- Inline all assets as base64 (not recommended for large images).
- Add a simple service-worker for offline caching.

Tell me which next step you want and I will do it (I can create the repo and push files if you provide repository details).