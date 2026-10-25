# PixelWin Labs — company website

Plain static pages for GitHub Pages: `index.html` (about the company), `privacy.html` (Privacy Policy), `terms.html` (Terms of Service), `404.html`, `style.css`, `logo.png`, `.nojekyll`. No scripts, no cookies, no build step.

## Put it on GitHub Pages
1. On github.com create a new **public** repository, for example `pixelwinlabs` (Pages is free for public repositories).
2. Upload every file of this folder to the root of the repository (Add file › Upload files), including the empty `.nojekyll`.
3. Repository › **Settings › Pages** › Source: *Deploy from a branch*, Branch: `main`, folder `/ (root)` › Save.
4. After a minute or two the site is at `https://<your-github-name>.github.io/pixelwinlabs/`
   (name the repository `<your-github-name>.github.io` instead and it is at `https://<your-github-name>.github.io/`).
5. The links for the Play Console and the app: `…/privacy.html` and `…/terms.html`.

Own domain later: Settings › Pages › Custom domain, and a DNS record at the domain registrar (GitHub shows which).

## Before publishing — check these
- **Email**: `pixelwinlabs@gmail.com` (Aftab, 2026-10-24) is on every page. Check that mail to it is read.
- **Country** India is an assumption. **Minimum age 18** (Aftab, 2026-10-24) — set the Play Console target audience to 18+ to match.
- The privacy policy says the apps may use Google AdMob and Firebase (Crashlytics, Analytics) — the Play Store requires the policy to name them.
- These texts are a sensible starting point, not legal advice.

## Domain
`CNAME` holds `pixelwinlabs.com`. GitHub Pages reads it as the custom domain; the DNS records are set at the registrar.
