# Nipun Garg — Portfolio

Personal portfolio website for **Nipun Garg**, Data Engineer & Data Analyst.

🔗 **Live:** https://ngarg2k2.github.io/

## Overview

A modern, responsive single-page portfolio built with plain HTML, CSS and vanilla JavaScript (no framework, no build step). Deployed via **GitHub Pages**.

### Sections
- Hero with animated role typing
- About + highlight stats
- Experience timeline (MAQ Software: SE2 / SE1 / ASE, Samsung PRISM)
- Skills (Languages & Databases, Tools & Platforms, Concepts & Methodologies)
- Projects
- Certifications (Snowflake, Microsoft Fabric / Azure AI, GitHub Copilot)
- Education
- Contact (email, WhatsApp, phone + working contact form)

### Features
- Dark / light theme toggle (persisted in `localStorage`)
- Active-section nav highlighting
- Scroll-progress bar
- Scroll-reveal animations (respects `prefers-reduced-motion`)
- SEO: Open Graph + Twitter cards, `robots.txt`, `sitemap.xml`
- Accessible focus states

## Tech stack
- HTML5 / CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (IntersectionObserver)
- [Font Awesome](https://fontawesome.com/) icons, [Google Fonts](https://fonts.google.com/) (Sora + Inter)
- [Web3Forms](https://web3forms.com/) for the contact form

## Project structure
```
.
├── index.html
├── robots.txt
├── sitemap.xml
└── assets/
    ├── css/style.css
    └── img/            # profile, favicon, project screenshots
```

## Local development
Serve the folder over HTTP (absolute `/assets/...` paths need a server, not `file://`):
```bash
python -m http.server 8765
# then open http://localhost:8765/
```

## Configuration to complete
- **Contact form:** get a free access key at [web3forms.com](https://web3forms.com/) and replace `YOUR_WEB3FORMS_ACCESS_KEY` in `index.html`.
- **Analytics (optional):** uncomment the GA4 snippet in `<head>` and add your `G-XXXXXXXXXX` Measurement ID.
- **Resume:** the Resume button links to a Google Drive PDF — update the link when the resume changes.

## Deployment
Push to `main` — GitHub Pages rebuilds automatically.
```bash
git add -A
git commit -m "Update portfolio"
git push origin main
```

## Contact
- Email: garg2002nipun@gmail.com
- LinkedIn: https://linkedin.com/in/ngarg2k2
- GitHub: https://github.com/ngarg2k2
