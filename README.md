# Dr José Shina — Dental Profile

A single-page personal profile site listing practice locations and contact details.

## Structure
- `index.html` — all page content (one page, anchor navigation only)
- `style.css` — styles
- `dr-jose-shina.jpg` — profile photo (kept at the repo root, no subfolder, so nothing can get flattened or lost on upload)

## Deploying with Netlify (from GitHub)
1. Push this folder to a new GitHub repository.
2. In Netlify: **Add new site → Import an existing project → GitHub**, then select the repo.
3. Build settings: no build command needed, leave it blank.
4. **Publish directory:** `/` (the repo root, since this is a static site with no build step).
5. Deploy. Netlify will give you a live URL immediately; you can add a custom domain afterwards in **Site settings → Domain management**.

No dependencies, frameworks, or build tools are used — it's plain HTML/CSS, so it will deploy as-is.
