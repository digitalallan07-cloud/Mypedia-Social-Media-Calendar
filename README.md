# myPedia — Content Calendar

A static, Instagram-grid style social media content calendar for **myPedia**, a pediatric clinic. It lays out scheduled posts (Aug 10 – Oct 05, 2026, mostly 2 days apart) as a responsive card grid, one row per topic: **left = Static photo, middle = Carousel graphic, right = Reel**. Each row belongs to a content pillar (Dental or Pediatric).

Plain HTML + CSS, no framework, no build step, no dependencies.

## Files

- `index.html` — the full page markup and content
- `styles.css` — all styling
- Post thumbnails are hotlinked directly from Google Drive's image CDN (`lh3.googleusercontent.com`) — no binary assets are stored in this repo.

## Deploying on Vercel

1. Go to [vercel.com/new](https://vercel.com/new) and import this GitHub repository.
2. When prompted for a framework preset, choose **Other**.
3. Leave the **Build Command** empty (no build step required).
4. Set the **Output Directory** to `./`.
5. Click **Deploy**.

That's it — Vercel will serve `index.html` and `styles.css` as static files.
