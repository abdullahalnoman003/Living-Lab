<div align="center">

# 🌿 Nature's Platter - Living Lab

### A modern, responsive grocery shopping landing page ✦ your everyday essentials, fresh & delivered.

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)]()
[![Tailwind](https://img.shields.io/badge/Tailwind%20CSS%204-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![DaisyUI](https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)](https://daisyui.com/)
[![Font Awesome](https://img.shields.io/badge/Icons-Font%20Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)](https://fontawesome.com/)
[![Status](https://img.shields.io/badge/Status-Active-2ea44f?style=for-the-badge)]()

---

[📜 Overview](#-overview) • [✨ Features](#-features) • [🛠 Technologies](#-technologies) • [📦 Getting Started](#-getting-started) • [🗂 Project Structure](#-project-structure) • [✏️ Customizing](#-customizing) • [🤝 Contributing](#-contributing) • [👨‍🎓 Author](#-author)

</div>

---

## 📜 Overview

**Nature's Platter** is a single-page **grocery & fresh-produce landing page** - a "Living Lab" for experimenting with modern front-end styling workflows. It showcases a complete retail experience: branded navigation, a bold hero banner, product showcases with ratings & pricing, service highlights, seasonal offers, an interactive FAQ accordion, and a newsletter signup - all wrapped in a polished, responsive layout.

The project experiments with the **Tailwind CSS + DaisyUI** pairing served **directly via CDN** - zero build step, zero configuration friction, open `index.html` and it just works.

---

## ✨ Features

| Section | What it does |
| --- | --- |
| 🏪 **Branded Header** | Logo, navigation menu, and user actions |
| 🎯 **Hero Banner** | Bold headline, tagline, and call-to-action built over a produce-themed visual |
| 🥦 **Product Showcase** | Popular items with images, pricing, and ratings |
| 🛵 **Service Highlights** | 24/7 availability, fast delivery, and healthy-product guarantees |
| 🏷️ **Special Offers** | Seasonal discounts & featured brand arrivals (e.g., Dawat, India Gate) |
| ❓ **Interactive FAQ** | Accordion-style answers to common customer questions |
| 📬 **Newsletter Footer** | Subscribe panel + full site footer |
| 🌓 **Theme Support** | Page boots with DaisyUI's `data-theme` system (light theme by default) |

---

## 🛠 Technologies

| Tool | Role |
| --- | --- |
| **HTML5** | Semantic page structure |
| **Tailwind CSS 4** | Utility-first responsive styling (via browser CDN) |
| **DaisyUI** | Component classes - cards, accordions, menus, buttons |
| **Font Awesome** | Scalable vector icons |
| **Google Fonts** | **Sora** (headings) + **Poppins** (body) typography |
| **Custom CSS** | Gradient backgrounds & design tokens in `<style>` blocks |

---

## 📦 Getting Started

### Option A - Just open it (easiest)

1. Clone or download the repository
2. Open `index.html` in any modern browser
3. You're done 🎉

### Option B - Local dev server (recommended for live reload)

```bash
# Using Python
python -m http.server 8000

# Using VS Code: right-click index.html → "Open with Live Server"
```

Then visit [http://localhost:8000](http://localhost:8000).

> 🌐 Because styles load from a CDN, an **internet connection is required** for fonts/icons/Tailwind to render.

---

## 🗂 Project Structure

```
Living-Lab/
├── index.html              # Entire landing page (single file)
├── tailwind.config.js      # Tailwind theme/customization reference
├── README.md               # You are here
└── c2-assets/              # Local images & brand assets
    ├── logo-header.png         ├── logo-footer.png
    ├── hero-vegetables.png     ├── vegetable-busket.png
    ├── vegetable-offer.png     ├── delivery.png
    ├── healthy.png             ├── service.png
    ├── onion.png               ├── potato.png
    ├── tomato.png              ├── dawat-logo.png
    ├── india-gate-logo.png     ├── dawat-mock-up.png
    └── india-gate-mock-up.png
```

---

## ✏️ Customizing

- **Branding** - swap the logos inside `c2-assets/` and update `titles`/`alt` text in `index.html`.
- **Colors & theme** - DaisyUI themes are applied via the `data-theme` attribute on `<html>`; change it to `dark`, `nord`, `cupcake`, etc.
- **Products & offers** - edit the product cards and offer blocks directly in `index.html`; images are referenced relative to `c2-assets/`.
- **Fonts** - the `sora` and `poppins` classes control typography; adjust the Google Fonts `<link>` tags to swap families.

---

## 🤝 Contributing

Ideas, section additions, and design polish are always welcome!

1. 🍴 Fork this repository
2. 🌿 Create a feature branch (`git checkout -b add/section-name`)
3. ✅ Make your changes in `index.html`
4. 🔀 Submit a Pull Request

---

## 📄 License

Built for **learning & experimentation**. Feel free to fork, remix, and reuse.

---

## 🧑‍💻 Developer

**👨‍🎓 Abdullah Al Noman**  
🔗 [LinkedIn](https://www.linkedin.com/in/abdullahalnoman003) •  
🔗 [Github](https://github.com/abdullahalnoman003) •  

⭐ Like this landing page? Star the repo to show some love!

---