# myPedia — Content Calendar

A static, Instagram-grid style social media content calendar for **myPedia**, a pediatric clinic. It lays out 9 scheduled Instagram carousel posts (Aug 10 – Sep 3, 2026) as a responsive card grid, using the first slide of each carousel as the feed thumbnail — matching how Instagram displays carousels in-grid.

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
