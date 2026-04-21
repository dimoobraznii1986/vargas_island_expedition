# vargas_island_expedition

Static companion site for the June 2026 **Vargas Island Expedition** (Norm Hann Expeditions). Host on GitHub Pages or any static host.

## Publish on GitHub Pages

1. Create a new repository named `vargas_island_expedition` on GitHub (empty, no README if you will push this folder).
2. From this directory:

```bash
git remote add origin https://github.com/YOUR_USERNAME/vargas_island_expedition.git
git branch -M main
git add .
git commit -m "Add Vargas Island expedition companion site"
git push -u origin main
```

3. In the repo on GitHub: **Settings → Pages → Build and deployment → Source**: **Deploy from a branch**, branch **main**, folder **/ (root)**.
4. After a minute, the site will be at `https://YOUR_USERNAME.github.io/vargas_island_expedition/`.

This project uses only relative URLs (`styles.css`, `trip-details.html`), so it works at that subpath without extra configuration.

## Contents

- `index.html` — trip overview and external resources  
- `trip-details.html` — meeting point, food notes, packing list  
- `route.html` — Leaflet map (illustrative, not for navigation)

Always confirm dates, fees, and safety with Norm Hann Expeditions.
