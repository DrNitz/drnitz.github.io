# Dr.N — Portfolio & Clinical Tech Site

<p align="center">
  <img src="https://drnitz.com/medical-animation.svg" width="100%" alt="3D Medical Animation" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=28&duration=3000&pause=800&color=66FCF1&center=true&vCenter=true&width=700&lines=Cure.+Code.+Create.;Full-time+Medical+Doctor;Residency+%26+AHIMA+CCS+Aspirant;Tech+Enthusiast+%26+AI+Explorer" alt="Typing Animation" />
</p>

<p align="center">
  <a href="https://drnitz.com" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/🌐_drnitz.com-66FCF1?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=111010" alt="Website" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=drnitz&label=👁️%20Profile%20Views&color=45A29E&style=for-the-badge" alt="Profile Views" />
</p>

A static, dependency-free GitHub Pages site for **Dr.N** — a general practitioner who builds tools at the intersection of medicine and technology. Live at **https://drnitz.com/**.

---

## About this repository

There is no build step, package manager or server code. Every page is hand-authored HTML with inline styles plus two shared stylesheets in `assets/`. The custom domain is configured via `CNAME`; `.nojekyll` ensures assets are served verbatim.

### Preview locally

```bash
git clone https://github.com/DrNitz/drnitz.github.io.git
cd drnitz.github.io
python3 -m http.server 8000
# open http://localhost:8000
```

Relative links work locally; canonical and social URLs point at the production domain.

### Pages

| File | What it is |
|---|---|
| `index.html` | Portfolio landing page — bio, project cards, contact |
| `anraksha.html` | Anraksha by Dr.Nitz — health notes and early signs (in development) |
| `mededu.html` | Redirect to `anraksha.html` (keeps old links working) |
| `nnotes.html` | Nnotes Android app showcase |
| `nnotes-privacy.html` | Nnotes app privacy policy and terms (linked from Google Play) |
| `privacy.html` | Privacy policy for this website |

### Layout

- `assets/` — shared CSS (base reset/reduced-motion and the clay dock navigation)
- `About/` — Nnotes user manual, Play Store listing copy and folder overview
- `medical-animation.svg`, `image/`, `*.jpg`, `anatomy_bg.png` — site assets
- `sitemap.xml`, `robots.txt`, `CNAME`, `.nojekyll`, `ads.txt`, `app-ads.txt` — crawler/domain/monetization config

### Deployment

Pushes to `main` publish automatically through GitHub Pages. When adding or renaming a page, update `sitemap.xml`, the navigation/footer links, and the page's title, description, canonical and OG/Twitter tags. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full checklist and [CHANGELOG.md](CHANGELOG.md) for recent changes.

### Documentation & policies

- [Nnotes documentation index](About/README.md)
- [User manual](About/USER_MANUAL.md)
- [Play Store listing copy](About/PLAYSTORE_LISTING.md)
- [App privacy & terms](nnotes-privacy.html) · [Site privacy](privacy.html)

Licensed under the [MIT License](LICENSE) for original site content; third-party attributions are listed there. Contributions are welcome under the [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 🩺 About Dr.N

> *"Medicine is my full-time vocation, while coding is my fun sandbox. I'm definitely not a master developer — I'm a passionate enthusiast who learns by building real tools, experimenting with AI, and relying heavily on brilliant co-developers like Lead Developer Harshita to make things actually work reliably!"*

```yaml
👤 name: Dr.N
🎓 profession: Full-time Medical Doctor (GP)
📖 goals: Preparing for Medical Residency & AHIMA CCS Certification
💻 tech_profile: Enthusiast Coder & Part-time AI Explorer
🌍 location: Earth
🌐 website: https://drnitz.com
🎯 motto: "Cure. Code. Create."
🔭 flagship_projects:
  - Anraksha (Health Notes & Early Signs 📚)
  - Nnotes (Lead Dev: Harshita | Co-Dev: Dr.N 🚀)
  - p2pcompanion.com (Live Terminal ⚡)
  - Med Reminder (In Development 💊)
```

---

## 🚀 Live Projects & Collaborations

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📚 Anraksha</h3>
      <p align="center">
        <a href="https://drnitz.com/anraksha.html">
          <img src="https://img.shields.io/badge/🩺%20Anraksha-66FCF1?style=for-the-badge&logo=google-chrome&logoColor=white" />
        </a>
      </p>
      <p align="center"><i>by Dr.Nitz — Primum non nocere, "First, do no harm." Plain-language health notes and early-warning guidance for patients, with clinical detail for doctors.</i></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🌐 p2pcompanion.com</h3>
      <p align="center">
        <a href="https://p2pcompanion.com">
          <img src="https://img.shields.io/badge/🚀%20LIVE-66FCF1?style=for-the-badge&logo=rocket&logoColor=white" />
        </a>
      </p>
      <p align="center"><i>P2P Companion Terminal — Real-time P2P crypto rates and arbitrage spreads across 6 exchanges and 80+ fiat currencies, with a free tier and a paid API.</i></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📝 Nnotes</h3>
      <p align="center">
        <a href="https://drnitz.com/nnotes.html">
          <img src="https://img.shields.io/badge/✨%20Showcase-66FCF1?style=for-the-badge&logo=appstore&logoColor=white" />
        </a>
        <a href="https://drnitz.com/nnotes-privacy.html">
          <img src="https://img.shields.io/badge/🛡️%20Privacy-45A29E?style=for-the-badge&logo=shield&logoColor=white" />
        </a>
      </p>
      <p align="center"><i>Ad-supported Android handwriting app: infinite canvas, on-device recognition, PDF annotation, vector export and 7 animated companions. Notes stay on your device. Lead Dev: <b>Harshita</b> | Co-Dev: <b>Dr.N</b>.</i></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">💊 Med Reminder</h3>
      <p align="center">
        <a href="https://github.com/drnitz/Med">
          <img src="https://img.shields.io/badge/📁%20Prototype-181717?style=for-the-badge&logo=github&logoColor=white" />
        </a>
      </p>
      <p align="center"><i>A practical medication tracking and dosage reminder app prototype designed from a physician's perspective for daily regimen adherence.</i></p>
    </td>
  </tr>
</table>

---

## 🌐 Connect

<p align="center">
  <a href="https://drnitz.com" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/🌐_drnitz.com-66FCF1?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=111010" />
  </a>
  <a href="https://github.com/drnitz" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:111010,50:45A29E,100:66FCF1&height=140&section=footer&text=Cure.%20Code.%20Create.&fontSize=24&fontColor=ffffff&animation=twinkling" alt="Footer Wave" />
</p>
