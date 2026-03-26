# 🌐 Maneesha M — Personal Portfolio

> **AI / ML Engineer · Data Scientist**  
> A modern, single-page portfolio built with pure HTML, CSS & JavaScript — no frameworks, no dependencies.

[![Live Site](https://img.shields.io/badge/Live%20Site-maneesha1618.github.io-00d4ff?style=for-the-badge&logo=github)](https://maneesha1618.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-maneesha1618-0066ff?style=for-the-badge&logo=github)](https://github.com/maneesha1618)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Maneesha%20M-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/maneesha-m-402641225)

---

## ✨ Features

- **Bold Gradient Mesh Theme** — animated floating orbs, electric blue/cyan accent system
- **Transparent Navbar** — starts fully transparent, transitions to frosted glass on scroll
- **Scroll Progress Bar** — thin gradient line at the top tracks reading progress
- **Rich Animations**
  - Staggered hero reveal on page load
  - Scroll-triggered fade-in, slide-from-sides, and scale-in effects
  - Skill tags animate in one by one on section enter
  - Project icon bounce on card hover
  - Contact link shimmer sweep on hover
- **Fully Responsive** — mobile-friendly layout
- **Zero Dependencies** — pure HTML/CSS/JS, no npm, no build step
- **Fast** — single file, embeds logo as base64, loads instantly

---

## 📁 Project Structure

```
maneesha1618.github.io/
│
├── index.html          # Entire portfolio (single file)
└── README.md           # This file
```

---

## 🗂️ Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | **Hero** | Name, title, experience badge, seeking statement, key stats |
| 02 | **Skills** | 8 skill groups — ML, NLP, Cloud, Web, Data, Databases, and Currently Learning |
| 03 | **Experience** | 2 roles with quantified impact bullets |
| 04 | **Projects** | 4 featured AI/ML projects with impact stats and GitHub links |
| 05 | **Education** | MSc Statistics + BSc Mathematics with CGPA |
| 06 | **Certifications** | 5 certifications + Currently Exploring section |
| 07 | **Contact** | Email, phone, LinkedIn, GitHub |

---

## 🚀 Deployment (GitHub Pages)

### First-time setup

1. Create a repository named exactly `maneesha1618.github.io`
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. Wait ~2 minutes — your site is live at `https://maneesha1618.github.io`

### Updating the site

Just re-upload `index.html` to the repo — GitHub Pages will auto-deploy within a minute.

---

## 🎨 Design System

| Token | Value | Usage |
|-------|-------|-------|
| `--bg` | `#04050f` | Page background |
| `--c1` | `#00d4ff` | Primary cyan accent |
| `--c2` | `#0066ff` | Blue accent |
| `--c3` | `#00ffcc` | Teal-green accent |
| `--c4` | `#7b2fff` | Violet accent |
| `--text` | `#f0f2ff` | Body text |
| `--muted` | `#7a80a0` | Secondary text |

**Fonts:** [Outfit](https://fonts.google.com/specimen/Outfit) (headings & body) · [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (italic descriptions)

---

## 🛠️ Customisation

To update content, open `index.html` and edit the relevant HTML section:

```html
<!-- Update your name -->
<span class="gradient-text">Maneesha M</span>

<!-- Update hero description -->
<p class="hero-desc">Your description here...</p>

<!-- Add a new project card -->
<div class="project-card scale-in">
  <div class="project-number">Project 05</div>
  <span class="project-icon">🧠</span>
  <div class="project-title">Your Project Title</div>
  ...
</div>
```

To change the accent color, update the CSS variables in `:root`:

```css
:root {
  --c1: #00d4ff;  /* Change to your preferred accent */
  --c2: #0066ff;
  --c3: #00ffcc;
}
```

---

## 📬 Contact

| Platform | Link |
|----------|------|
| 📧 Email | [maneeshaclement46@gmail.com](mailto:maneeshaclement46@gmail.com) |
| 📞 Phone | +91 7994270124 |
| 💼 LinkedIn | [linkedin.com/in/maneesha-m-402641225](https://linkedin.com/in/maneesha-m-402641225) |
| 🐙 GitHub | [github.com/maneesha1618](https://github.com/maneesha1618) |
| 📍 Location | Ernakulam, India · Open to Remote |

---

<p align="center">Designed & built by <strong>Maneesha M</strong> · 2025</p>
