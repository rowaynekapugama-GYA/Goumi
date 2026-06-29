# goumi — website

Marketing site for goumi (hands-free, AI + voice cooking app). Plain HTML/CSS, no build step, one folder. Domain: goumi.ai

## Files
- `index.html` — landing page
- `privacy.html`, `health-data-policy.html`, `terms.html`, `cookie-policy.html` — policy pages
- `goumi-logo.png` · favicons (`favicon.ico`, `favicon-16/32/512.png`, `apple-touch-icon.png`) · `og-image.jpg` (social share)
- `flatbread.jpg`, `tostadas.jpg`, `table-spread.jpg`, `wok.jpg` — food photos

## Deploy (GitHub Pages)
1. Push everything to the **root** of a repo.
2. Settings → Pages → Deploy from a branch → **main / root**.
3. Add a `CNAME` file containing `goumi.ai` and point DNS. `.nojekyll` is included.

## ⚠️ Seeing an OLD layout? Read this — it's almost always cache.
If cards look like two columns on desktop, or text wraps into a skinny left strip, you are viewing a **cached copy**, not these files. The current files render every card as a single stacked block (heading on top, full-width description). To force the newest version:

1. **Re-upload these files** to your host (don't assume the old deploy updated itself).
2. Then load the page with a cache-buster — the most reliable options:
   - Open in a **private / incognito window**, OR
   - Add `?v=2` to the URL, e.g. `https://goumi.ai/?v=2` (any number works; change it each time), OR
   - Hard refresh: **Cmd+Shift+R** (Mac) / **Ctrl+Shift+R** (Windows).
3. GitHub Pages also has a CDN that caches ~10 min — if a hard refresh isn't enough, wait a few minutes and try the `?v=` trick.

**Verify which build you have:** open the page, View Source, and look near the top for `<!-- goumi build ... -->`. If the timestamp is old, you're still on a cached copy.

These pages send `Cache-Control: no-cache` to reduce this going forward. (For production you can remove that meta tag once things are stable.)

## Cookie banner
A consent banner ("Accept" / "Decline" + Cookie Policy link) appears on first visit and remembers the choice in `localStorage` (`goumi_cookie_consent`). It works on the deployed site. To re-test it, clear the key or use a private window.

## Before launch
- Fill the `[bracketed]` placeholders in the policy pages (legal name, ABN, contact, dates), get a lawyer's review, remove the "draft for legal review" banner.
- Replace the placeholder `href="#"` on the "Get goumi" / App Store buttons with your real store URL.
- The social-share image uses absolute `goumi.ai` URLs, so the preview only resolves once live at goumi.ai.
- Food photos are Shutterstock — confirm your licence covers website use.
