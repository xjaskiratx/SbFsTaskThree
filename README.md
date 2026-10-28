# FlipStuck — Course Explore Page (Task Three)

[![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Pure_Vanilla-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Pure CSS](https://img.shields.io/badge/JavaScript-Zero_Dependencies-lightgrey?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Vercel](https://img.shields.io/badge/Deployment-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://vercel.com)

A pixel-perfect, accessible, and responsive **Course Explore & Catalog Page** for **FlipStuck**, replicating `Course Explore Page.png` strictly with **100% Pure Semantic HTML5 and Vanilla CSS3 (Zero JavaScript)**.

---

## 🌟 Key Features

* **100% Pure HTML & CSS Architecture**:
  * Built strictly with standard semantic HTML5 and Vanilla CSS3.
  * Completely JS-free: mobile navigation drawer and mobile filter drawer powered by pure CSS checkbox hacks (`:checked` selector).
  * Smooth native browser scrolling (`scroll-behavior: smooth`).
* **Hero & Search Bar**:
  * Clean breadcrumb navigation (`Home > Explore Courses`).
  * High-impact hero typography with custom serif italic accents (`Instrument Serif` / `Playfair Display`).
  * Pill search bar form with leading search icon and submit action.
* **Semantic Filter Sidebar**:
  * **Categories**: Web Development, Graphic Design, Data Science, Computer Basics, Video Editing, Beauty & Lifestyle, Digital Marketing, Music.
  * **Level**: Beginner, Intermediate, Advanced.
  * **Price**: Free, Paid.
  * **Rating**: 4.5 & up, 4.0 & up.
  * Native form reset button (`Clear All Filters`) to reset selections with pure HTML.
* **Course Catalog Grid**:
  * 9 authentic course cards with high-fidelity cropped thumbnails, instructor avatars, star ratings, review counts, and enrollment pricing (`₹299` to `₹799`).
  * Card badges (`Best Seller`, `Trending`, `Popular`).
  * CSS micro-animations: elevation lift and shadow expansion on hover.
* **Footer & Artwork**:
  * Multi-column category navigation with brand green dot indicators.
  * Contact info, email, phone, and social links.
  * Panoramic ink landscape illustration banner (`Assets-2/footer-bg.jpg`).
  * Comprehensive legal and copyright bar.
* **Mobile-First Responsiveness**:
  * Slide-out mobile navigation drawer with backdrop blur (Pure CSS).
  * Slide-out mobile filter drawer (Pure CSS).
  * Floating back-to-top button.

---

## 📁 Repository Structure

```text
.
├── Assets-2/                   # Optimized images, course thumbnails, avatars, favicons
├── TaskThree/                  # TaskThree distribution package
│   ├── Assets-2/
│   ├── Course Explore Page.png
│   ├── Course Page UI.png
│   ├── HomePage UI (2).png
│   ├── index.html
│   └── style.css
├── favicon.ico                 # Multi-resolution favicon
├── favicon.png                 # Apple touch icon & PWA icon
├── index.html                  # Pure HTML5 Explore Catalog markup
├── site.webmanifest            # PWA manifest
├── style.css                   # Complete Vanilla CSS design system
├── vercel.json                 # Caching and production deployment configuration
└── README.md                   # Project documentation
```

---

## 🚀 Local Development

To view the project locally, simply open `index.html` (or `TaskThree/index.html`) in any modern web browser. No build steps, bundlers, or servers required.

```bash
# Optional local HTTP server:
python3 -m http.server 3000
```
