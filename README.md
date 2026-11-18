# snakeco-legal

Public website of the SnakeCo Android game by DGM Technology OÜ: landing pages (EN `/`, ES `/es/`), press kit
(`/press/`), Privacy Policy and Terms of Use in English and Spanish. Served with GitHub Pages at
<https://snakeco.flashylearning.app/>. Plain HTML/CSS, no cookies, no trackers, no build step.

| Page | URL |
|---|---|
| Privacy Policy (EN) — used in Google Play Console | https://snakeco.flashylearning.app/en/privacy.html |
| Terms of Use (EN) | https://snakeco.flashylearning.app/en/terms.html |
| Landing (EN, x-default) / Landing (ES) | https://snakeco.flashylearning.app/ · https://snakeco.flashylearning.app/es/ |
| Press kit | https://snakeco.flashylearning.app/press/ |
| Política de privacidad (ES) | https://snakeco.flashylearning.app/es/privacy.html |
| Condiciones de uso (ES) | https://snakeco.flashylearning.app/es/terms.html |

The source of these files lives in the private SnakeCo repository under `docs/legal-site/`. Edit them there, then copy
them here. The app links to these exact URLs (string resources `about_privacy_url` / `about_terms_url`), so never
rename or move the files. Keep the `CNAME` file (`snakeco.flashylearning.app`): without it GitHub Pages drops the custom
domain. The old `dfgonzalez88.github.io/snakeco-legal/` URLs redirect here (301).

When SnakeCo switches to free with ads, section 12 of the privacy policy becomes active: remove the "not active"
box, update the effective date and the permissions table, and add an `app-ads.txt` if AdMob asks for one.

Landing pages: `index.html`, `es/index.html`, `landing.css`, `img/` (built from approved art by
`tools/build_landing_assets.py` in the private repo), `sitemap.xml`, `robots.txt`; `en/index.html` only redirects
to `/`. Play links carry an install `referrer` per channel (list in the private repo,
`docs/marketing/visibility/LINKS.md`).

**On 6 January 2027** remove the Christmas section: delete everything between `<!-- XMAS-2026 START` and
`<!-- XMAS-2026 END -->` in `index.html` and `es/index.html`, the "Christmas 2026" block in `landing.css` and
`img/xmas-banner.webp`. (Until then a tiny inline script hides the section from that date anyway.)
