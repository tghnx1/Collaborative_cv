# Collaborative CV – Junior Freelance Web Developer Resume

A clean, one-page, ATS-friendly resume template built as a static HTML/CSS webpage. Designed to target **junior freelance web developer** roles at digital services companies working on e-commerce, SaaS platforms, and business tools.

## 📄 Files

| File | Purpose |
|------|---------|
| `index.html` | Resume markup – all content lives here |
| `styles.css` | Visual styles – layout, colours, typography, print rules |

## 🚀 Usage

Open `index.html` directly in any modern browser – no build step required.

```bash
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

### Print / Export to PDF

1. Open `index.html` in Chrome or Firefox.
2. Press `Ctrl + P` (or `Cmd + P` on macOS).
3. Set **Destination → Save as PDF** and **Margins → None**.
4. Ensure **Background graphics** is checked to preserve colours.

## ✏️ Customisation

All personal content is in `index.html`. Replace the placeholder values with your own:

- **Name, title, and contact details** – `<header>` block
- **Summary** – `<section class="section summary">` block
- **Skills** – `<div class="skills-grid">` block
- **Projects** – each `<div class="entry">` inside the Projects section
- **Experience** – each `<div class="entry">` inside the Experience section
- **Education** – `<div class="edu-grid">` block

Colour accent (`--accent: #2563eb`) and font can be changed via CSS custom properties at the top of `styles.css`.

## 🎯 Role Alignment

The template demonstrates the following competencies required for junior freelance web developer roles:

- ✅ HTML, CSS, JavaScript (Vanilla & Vue.js)
- ✅ Basic backend (PHP / Python Flask)
- ✅ Git / GitHub workflow
- ✅ Feature development, bug fixing, CSS adjustments, testing
- ✅ Remote work, autonomy, and clear communication
