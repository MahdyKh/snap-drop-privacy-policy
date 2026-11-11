# Snap & Drop — Privacy Policy

Official Privacy Policy for **Snap & Drop**, published by **Next Studio**.

| | |
|---|---|
| Publisher | Next Studio |
| Game | Snap & Drop |
| Android package name | `com.snapdrop.game` |
| Support email | [nextstudio2010@gmail.com](mailto:nextstudio2010@gmail.com) |
| Published policy | https://mahdykh.github.io/snap-drop-privacy-policy/ |

This repository exists only to host the privacy policy on GitHub Pages, so that it has a public HTTPS URL for
Google Play Console and for the in-game **Settings → Privacy policy** link.

## Files
- `index.html` — the published page (static HTML and CSS; no JavaScript, tracking or ads).
- `PrivacyPolicy.md` — the same policy text in Markdown. `index.html` is generated from this file, so the wording is identical.
- `.nojekyll` — tells GitHub Pages to serve the files as they are, without Jekyll processing.

## Updating the policy
1. Edit `PrivacyPolicy.md` in the Snap & Drop game project (`Marketing/GooglePlay/Privacy/site/`). Change the
   **Effective date** whenever the content changes.
2. Regenerate the page from the game project root: `node Tools/PrivacySite/build_privacy_site.mjs`
   (it refuses to build if a placeholder is left).
3. Copy `index.html`, `PrivacyPolicy.md` and `README.md` into this repository, commit and push to `main`.
   GitHub Pages redeploys automatically within a minute or two.
4. Keep the URL unchanged: it is registered in Google Play Console and inside the game.

## GitHub Pages configuration
- Repository visibility: **Public**
- Settings → Pages → Source: **Deploy from a branch**
- Branch: **`main`**, folder: **`/ (root)`**
