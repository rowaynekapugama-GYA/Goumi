# goumi — website

Marketing website for goumi (hands-free, AI + voice cooking app). Plain HTML/CSS, no build step, everything in one folder. Domain: goumi.ai

## Files
- `index.html` — landing page
- `privacy.html`, `health-data-policy.html`, `terms.html`, `cookie-policy.html` — policy pages
- `goumi-logo.png` — brand logo
- `favicon.ico`, `favicon-16.png`, `favicon-32.png`, `apple-touch-icon.png`, `favicon-512.png` — site/app icons
- `og-image.jpg` — social-share preview (1200×630), used by SMS/iMessage/WhatsApp/social link previews
- `flatbread.jpg`, `tostadas.jpg`, `table-spread.jpg`, `wok.jpg` — food photos

## Deploy with GitHub Pages
1. Push these files to the **root** of a GitHub repo.
2. Repo → **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main / root**, Save.
3. Live in ~1–2 min. Point goumi.ai at it (add a `CNAME` file containing `goumi.ai` and set DNS).

`.nojekyll` is included so all files are served as-is.

## Seeing an old version? (cache)
Browsers and GitHub Pages cache aggressively. After you deploy/replace files, **hard-refresh** to see changes:
- Mac: **Cmd + Shift + R**   ·   Windows: **Ctrl + Shift + R**
If a layout still looks like an older build, it's almost always a cached copy — hard-refresh or open in a private window.

## Important: social-share image
The share preview tags use **absolute** `https://goumi.ai/...` URLs, so the link preview image only appears once the site is live at **goumi.ai**. If you test on a temporary GitHub Pages URL first, the preview image won't load until the goumi.ai domain points here.

## Before you go live
- **Fill the placeholders** in the policy pages (legal name, ABN, contact email, address, dates — shown as `[like this]`), get a lawyer's review, then remove the "draft for legal review" banner.
- **App Store links** — replace the placeholder `href="#"` on the "Get goumi" button and App Store badges with your real URL.
- **Image licensing** — the food photos are Shutterstock; confirm your licence covers website use.
