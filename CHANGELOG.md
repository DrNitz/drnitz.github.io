# Changelog

## Unreleased — 20 Nov 2026

### Fixed / reworked
- **Privacy & legal:** rewrote the Nnotes policy to be truthful about ad-supported data processing; added Play Data Safety categories, children/COPPA section, retention/deletion/opt-out and a compliant upstream MIT notice with Stanford/Lane CC BY-SA 4.0 credit. Removed literal Markdown artifacts from the live policy.
- **Canonicalization:** moved all canonical, OG/Twitter, sitemap and robots URLs from `drnitz.github.io` to the live custom domain `https://drnitz.com/`; added the previously missing site policy page to the sitemap.
- **Product copy:** reconciled the Nnotes and MedEdu descriptions with the shipped Play app and the "in development" status of MedEdu; refreshed P2P Companion stats; fixed mislabeled GitHub links.
- **Tooling:** removed five one-off Python scripts that destroyed OG tags, duplicated canonicals or reversed image processing on re-run; removed the unrelated 3D contribution workflow and junk `help.md`.

### Added
- `LICENSE` with MIT terms for this repo plus third-party attributions.
- `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `.gitignore` and this changelog.
- Page-specific social metadata, `og:image` on Nnotes, and a second privacy-policy cross-link in the footer.

### Improved
- Accessibility: `<main>` landmarks, labelled navigation and icon links, keyboard-accessible Nnotes demo, real `<h3>` feature headings, ARIA tabs, reduced-motion support, decorative images hidden from assistive tech.
- Contrast: all text colours on light pages now pass WCAG AA (lowest ratio 4.75:1).
- Robustness: pinned `vanta@0.5.24` and removed `@latest`; SRI hashes on all CDN scripts; guarded GSAP/Vanta calls; removed inline `onerror` handlers; off-screen dock links leave the tab order.
- Documentation: site README now covers setup and deployment; Play listing doc aligned with the live app.

### Notes
- Changes are uncommitted at the time of writing. Deployment requires a commit/push.
- HTTPS enforcement on the custom domain and Search Console verification remain manual GitHub/Google settings.
