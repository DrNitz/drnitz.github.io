# Contributing

This is a static GitHub Pages site — there is no build step, package manager, or test suite.

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Because a custom domain is configured in `CNAME`, relative links work locally but canonical/OG URLs point to `https://drnitz.com/`.

## Where things live

| Path | Purpose |
|---|---|
| `index.html` | Portfolio landing page |
| `anraksha/index.html` | Anraksha by Dr.Nitz — served at `/anraksha/` (in development) |
| `nnotes/index.html` | Nnotes app showcase — `/nnotes/` |
| `nnotes/privacy/index.html` | Nnotes policy/terms — `/nnotes/privacy/` |
| `privacy/index.html` | Website privacy policy — `/privacy/` |
| `assets/` | Shared CSS used by multiple pages |
| `About/` | Nnotes documentation, user manual and Play listing copy |
| `sitemap.xml`, `robots.txt` | Crawler metadata |

## Ground rules

1. **No build tooling.** Keep pages self-contained apart from the shared files in `assets/`.
2. **SEO metadata is hand-authored.** Do not reintroduce bulk HTML-injector scripts — earlier versions stripped Open Graph tags and duplicated canonicals on re-run. Edit the `<head>` blocks directly.
3. **Adding a page** means adding it to `sitemap.xml`, the footer/dock navigation where relevant, and giving it a unique title, description, canonical and OG/Twitter tags.
4. **Privacy copy must match reality.** The Nnotes policy describes an ad-supported app; keep it consistent with the Play Store Data Safety declaration and avoid absolute "zero telemetry" wording. Changes to the app require a review of `nnotes/privacy/index.html`, `About/PLAYSTORE_LISTING.md`, `About/USER_MANUAL.md` and `About/README.md`.
5. **Third-party scripts** must be version-pinned and carry SRI hashes. Do not use `@latest` CDNs.
6. **Accessibility:** keep one `<main>` per page, label icon-only navigation, include `alt=""` on decorative images, and preserve the reduced-motion rules in `assets/base.css`.

Changes go directly to `main` via pull request when practical. There are no automated checks yet — please open the page in a browser and confirm layout and links before merging.
