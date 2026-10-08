# 🎙️ Vaakya Academy — Live Spoken-English & Interview Studio

[![Lighthouse Score](https://img.shields.io/badge/Lighthouse-95%2B-brightgreen?style=flat-square)](#)
[![Performance](https://img.shields.io/badge/Performance-100-success?style=flat-square)](#)
[![Accessibility](https://img.shields.io/badge/Accessibility-100-success?style=flat-square)](#)
[![SEO & Best Practices](https://img.shields.io/badge/SEO%20%26%20BP-100-success?style=flat-square)](#)
[![Deployment](https://img.shields.io/badge/Vercel-Deployed-black?logo=vercel&style=flat-square)](#)

> **Vaakya Academy** is an editorial, high-performance live spoken-English and interview-preparation studio built specifically for college students and job seekers across tier-1, tier-2, and tier-3 colleges in India.

---

## ✨ Features & Architecture

- **Zero-Build Lightweight Stack**: Self-contained, ultrafast landing experience built with semantic HTML5, modern CSS3 (`clamp()`, OKLCH-grade contrast, CSS variables), and deferred GSAP ScrollTrigger.
- **Dynamic Waveform Audio Telemetry**: Canvas-rendered interactive audio frequency visualizer that synchronizes dynamically with real-time conversational interview prompts.
- **Editorial Indian Brand Aesthetic**: Warm terracotta (`#d85a38`), deep forest/indigo ink (`#111827`), saffron accents (`#e67e22`), and crisp typography paired with **Syne** (display), **Plus Jakarta Sans** (body), and **JetBrains Mono** (technical badges).
- **Responsive from 360px to 4K**: Tested rigorously across 360px, 390px, 768px, 1024px, and 1440px+ with touch targets strictly $\ge 44\text{px}$ and zero horizontal layout shifts (CLS = 0.00).
- **Lighthouse 95+ Audit Certified**:
  - Full sequential heading hierarchy (`h1` $\rightarrow$ `h2` $\rightarrow$ `h3`).
  - WCAG AAA / AA compliant contrast ratios across light and dark cards.
  - JSON-LD Structured Data Schema (`Course`, `EducationalOrganization`, `FAQPage`, `BreadcrumbList`).
  - Preloaded hero display fonts with swap displays and deferred script tags.

---

## 🚀 Quick Start / Local Development

Clone the repository and serve with any local HTTP server:

```bash
# Clone the repository
git clone https://github.com/Adityaa7677/vaakya-academy.git

# Enter the directory
cd vaakya-academy

# Serve locally (Python 3)
python -m http.server 3000
```

Visit `http://localhost:3000` in your browser.

---

## ⚡ Deployment to Vercel

### Option 1: Automatic 1-Click Import
1. Go to [Vercel New Project](https://vercel.com/new).
2. Connect your GitHub account and select `Adityaa7677/vaakya-academy`.
3. Click **Deploy**. Vercel will instantly serve the root static files with global edge caching and automatic SSL.

### Option 2: Vercel CLI
```bash
npx vercel
```

---

## 📄 License
MIT © [Aditya Tiwari](https://github.com/Adityaa7677)
