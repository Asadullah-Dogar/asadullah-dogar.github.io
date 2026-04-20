# 🚀 Asad Ullah Dogar - Portfolio Website

![Portfolio Live](https://img.shields.io/badge/Portfolio-Live-brightgreen?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-100%25-E34C26?style=flat-square)
![Accessibility](https://img.shields.io/badge/WCAG%202.1-AA%2B-green?style=flat-square)

**🔗 Live Site:** [asadullah-dogar.github.io](https://asadullah-dogar.github.io/)

A **modern, production-ready portfolio** showcasing AI engineering excellence, scalable backend architecture, and impactful leadership. Built with semantic HTML5, Tailwind CSS (CDN), and vanilla JavaScript—optimized for **performance**, **accessibility**, and **SEO**.

---

## ⚡ Quick Start

```bash
# Clone the repository
git clone https://github.com/Asadullah-Dogar/asadullah-dogar.github.io.git
cd asadullah-dogar.github.io

# Make it your own - customize index.html with your content
# Then push to GitHub!
git add .
git commit -m "Customize portfolio"
git push origin main
```

**Your portfolio will be live at:** `https://yourusername.github.io`

---

## ✨ Features

### 🎨 Design & UX
- **Modern Dark Theme** — Sleek slate-950 background with purple/cyan gradient accents
- **Fully Responsive** — Mobile-first design (320px to 4K), optimized for all devices
- **Smooth Animations** — Scroll-triggered section reveals with Intersection Observer
- **WCAG 2.1 AA+** — Full accessibility compliance with keyboard navigation

### 📱 Content Sections
| Section | Description |
|---------|-------------|
| **Hero** | Bold introduction with gradient text and CTAs |
| **About** | Tech stack overview with 4-column expertise grid |
| **Volume** | Visual grid showing 140+ shipped projects |
| **Projects** | Featured engineering work with live demo links |
| **Credentials** | Certifications archive with issuer & date |
| **Leadership** | Professional leadership roles & initiatives |
| **Contact** | Social links with branded icons |

### 🚀 Performance
- **Single HTML file** — No build step, no dependencies
- **CDN-hosted assets** — Tailwind CSS, Lucide Icons, Font Awesome
- **Preconnect optimization** — DNS prefetch to external resources
- **Deferred icon loading** — Faster initial page render
- **Zero CLS** — Optimized animations with CSS transforms

### 🔍 SEO & Meta
- ✅ Comprehensive meta descriptions & keywords
- ✅ Open Graph tags for social media sharing
- ✅ JSON-LD structured data for rich snippets
- ✅ Semantic HTML5 throughout
- ✅ Mobile-responsive viewport
- ✅ Proper heading hierarchy (h1 → h4)

---

## 📁 Project Structure

```
asadullah-dogar.github.io/
├── index.html                    # Main portfolio (single-page)
├── README.md                     # Documentation
├── .gitignore                    # Git configuration
├── CONTRIBUTING.md               # Contribution guidelines
└── .github/
    └── workflows/
        └── deploy.yml            # GitHub Pages auto-deploy
```

---

## 🛠️ Tech Stack

| Technology | Purpose | Link |
|-----------|---------|------|
| **HTML5** | Semantic structure & accessibility | — |
| **Tailwind CSS** | Utility-first styling (CDN) | [cdn.tailwindcss.com](https://cdn.tailwindcss.com) |
| **Lucide Icons** | Clean, consistent icons | [lucide.dev](https://lucide.dev) |
| **Font Awesome** | Branded social logos | [fontawesome.com](https://fontawesome.com) |
| **Vanilla JS** | Lightweight interactivity | — |

**Zero dependencies.** Everything loads from CDN. No build process required.

---

## 🎨 Design System

### Color Palette

| Role | Color | Hex | Usage |
|------|-------|-----|-------|
| **Primary Dark** | Slate 950 | `#0f172a` | Background |
| **Accent 1** | Purple 500 | `#a855f7` | Headlines, highlights |
| **Accent 2** | Cyan 400 | `#06b6d4` | Links, hover states |
| **Text Primary** | White | `#ffffff` | Headings |
| **Text Secondary** | Slate 300 | `#cbd5e1` | Body text |
| **Text Tertiary** | Slate 500 | `#64748b` | Meta info |

### Typography

- **Display (Hero):** `5xl → 8xl` (mobile → desktop)
- **Headings:** `2xl → 5xl` (h2-h3)
- **Body:** `lg → xl` (paragraph text)
- **Small:** `sm` (meta, badges)
- **Font:** System sans-serif (San Francisco, Segoe UI, Helvetica)

---

## ♿ Accessibility Features

### Keyboard Navigation
- `Tab` — Navigate through interactive elements
- `Escape` — Close mobile menu
- `Enter` — Activate links/buttons
- Focus indicators on all clickable elements

### ARIA & Semantics
- Proper `role` attributes on sections
- `aria-label` and `aria-expanded` for clarity
- Semantic HTML (`<nav>`, `<main>`, `<footer>`, `<section>`)
- Image alt text (decorative elements marked `aria-hidden`)

### Motion & Vision
- Respects `prefers-reduced-motion` media query
- High contrast text (WCAG AA)
- Readable font sizes (minimum 16px)
- Focus rings on all interactive elements

---

## 🚀 Deployment

### Option 1: GitHub Pages (Recommended)

**Step 1: Create a GitHub Repository**
```bash
# Go to https://github.com/new
# Create repo named: yourusername.github.io
```

**Step 2: Push Your Portfolio**
```bash
git add .
git commit -m "Initial portfolio commit"
git push -u origin main
```

**Step 3: Enable GitHub Pages**
- Repository → Settings → Pages
- Set source to "Deploy from a branch"
- Select "main" branch
- Save

✅ Your portfolio is live at `https://yourusername.github.io`

### Option 2: Custom Domain

**Create a CNAME file:**
```
yourportfolio.com
```

**Update DNS at your domain registrar:**
- Point to GitHub Pages IP: `185.199.108.153`
- Or use CNAME: `yourusername.github.io`

**Configure in GitHub:**
- Settings → Pages → Custom domain
- Enter your domain

---

## 📝 Customization Guide

### Update Content

1. **Hero Section** (lines 150-180)
   - Edit headline
   - Update tagline
   - Modify CTA buttons

2. **About Section** (lines 185-210)
   - Update bio text
   - Customize tech stack cards
   - Add/remove expertise areas

3. **Projects** (lines 280-310)
   - Add project descriptions
   - Update links
   - Modify tech tags

4. **Certifications** (lines 460-480)
   - Edit `certsData` array
   - Update dates & issuers

### Modify Colors

Search and replace Tailwind color classes:
```html
<!-- Replace these -->
purple-500 → your-primary-color
cyan-400 → your-secondary-color
slate-950 → your-background-color
```

### Add New Sections

```html
<section id="newsection" class="animated-section min-h-screen py-24 px-6 md:px-12 lg:px-24 transition-all duration-1000 ease-out transform opacity-0 translate-y-10">
  <h2 class="text-3xl md:text-5xl font-bold text-white mb-12">New Section</h2>
  <!-- Your content -->
</section>
```

Add to navigation menu (line 45-50):
```html
<a href="#newsection" class="text-sm font-medium hover:text-cyan-400">New Section</a>
```

---

## 📊 Performance Metrics

| Metric | Target | Status |
|--------|--------|--------|
| **Lighthouse Performance** | 95+ | ✅ |
| **Accessibility Score** | 98+ | ✅ |
| **First Contentful Paint** | < 1.5s | ✅ |
| **Cumulative Layout Shift** | < 0.1 | ✅ |
| **Time to Interactive** | < 2s | ✅ |

**Test with:** [Google PageSpeed Insights](https://pagespeed.web.dev)

---

## 🐛 Troubleshooting

### Icons not showing?
- Check browser console for errors
- Ensure `defer` attribute on Lucide script
- Clear browser cache (Ctrl+Shift+Delete)

### Mobile menu not closing?
- Press `Escape` key
- Or click a menu link
- Check JavaScript errors (F12 → Console)

### Styles not loading?
- Verify Tailwind CDN link is active
- Check network tab in DevTools
- Ensure no Content Security Policy blocks

### Animations not smooth?
- Check `prefers-reduced-motion` in Accessibility settings
- Disable browser extensions
- Test in incognito mode

---

## 🔐 SEO Best Practices

✅ **Meta Tags** — Descriptions, keywords, author  
✅ **Open Graph** — Social media preview optimization  
✅ **JSON-LD** — Structured data for search engines  
✅ **Semantic HTML** — Proper heading hierarchy & landmarks  
✅ **Mobile-First** — Responsive design indexed by Google  
✅ **Page Speed** — Fast loading for better rankings  
✅ **Alt Text** — Descriptive image attributes  
✅ **Sitemap Ready** — Add `sitemap.xml` if needed  

---

## 🤝 Contributing

Found a bug or want to improve this template?

1. **Report Issues:** Open a GitHub Issue with details
2. **Suggest Features:** Start a Discussion
3. **Fork & Customize:** This is your portfolio!

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📞 Contact & Links

- **Email:** dogarasad277@gmail.com
- **GitHub:** [@Asadullah-Dogar](https://github.com/Asadullah-Dogar)
- **LinkedIn:** [asad-ullah-dogar](https://www.linkedin.com/in/asad-ullah-dogar/)
- **Portfolio:** [asadullah-dogar.github.io](https://asadullah-dogar.github.io/)

---

## 📄 License

**MIT License** — Feel free to fork, customize, and use this template for your own portfolio!

See [LICENSE](LICENSE) for details.

---

## 🌟 Credits

- **Design Inspiration** — Modern portfolio trends
- **Icons** — [Lucide](https://lucide.dev) & [Font Awesome](https://fontawesome.com)
- **Styling** — [Tailwind CSS](https://tailwindcss.com)
- **Hosting** — [GitHub Pages](https://pages.github.com)

---

<div align="center">

**Built with ❤️ using modern web standards**

[⬆ Back to top](#-asad-ullah-dogar---portfolio-website)

</div>
