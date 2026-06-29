# goumi — website

The marketing website for goumi (a hands-free, AI + voice cooking app). Plain HTML/CSS, no build step, all files in one folder.

## Files
- `index.html` — landing page
- `privacy.html`, `health-data-policy.html`, `terms.html`, `cookie-policy.html` — policy pages
- `goumi-logo.png` — brand logo
- `flatbread.jpg`, `tostadas.jpg`, `table-spread.jpg`, `wok.jpg` — food photos

## Deploy with GitHub Pages
1. Push these files to the **root** of a GitHub repository.
2. Repo → **Settings → Pages**.
3. **Source: Deploy from a branch**, **Branch: `main` / `root`**, then **Save**.
4. The site goes live at `https://<username>.github.io/<repo>/` within a minute or two.

`.nojekyll` is included so GitHub Pages serves every file as-is.

## Before you go live
- **Fill the placeholders** in the policy pages — legal name, ABN, contact email, address, dates (they show `[like this]`) — and get a lawyer's sign-off, then remove the "draft for legal review" banner.
- **App Store links** — replace the placeholder `href="#"` on the "Get goumi" button and the App Store badges with your real App Store URL.
- **Image licensing** — the food photos are Shutterstock; confirm your licence covers website use.
