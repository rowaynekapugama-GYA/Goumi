# goumi — website

Marketing website for goumi (a hands-free, AI + voice cooking app). Plain HTML/CSS, no build step, all files in one folder. Domain: goumi.ai

## Files
- `index.html` — landing page
- `privacy.html`, `health-data-policy.html`, `terms.html`, `cookie-policy.html` — policy pages
- `goumi-logo.png` — brand logo
- `flatbread.jpg`, `tostadas.jpg`, `table-spread.jpg`, `wok.jpg` — food photos

## Deploy with GitHub Pages
1. Push these files to the **root** of a GitHub repository.
2. Repo → **Settings → Pages**.
3. **Source: Deploy from a branch**, **Branch: `main` / `root`**, then **Save**.
4. Live at `https://<username>.github.io/<repo>/` in a minute or two. (Point your goumi.ai domain at it via a CNAME when ready.)

`.nojekyll` is included so every file is served as-is.

## Before you go live
- **Fill the placeholders** in the policy pages — legal name, ABN, contact email, address, dates (shown as `[like this]`) — and get a lawyer's sign-off, then remove the "draft for legal review" banner.
- **App Store links** — replace the placeholder `href="#"` on the "Get goumi" button and App Store badges with your real App Store URL.
- **Image licensing** — the food photos are Shutterstock; confirm your licence covers website use.
