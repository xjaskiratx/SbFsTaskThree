# FlipStuck — Course Explore Page (Task Three)

[![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Pure_Vanilla-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Pure CSS](https://img.shields.io/badge/JavaScript-Zero_Dependencies-lightgrey?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Vercel](https://img.shields.io/badge/Deployment-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://sandbyte-flipstuck-task-three.vercel.app)

A pixel-perfect, accessible, and responsive Course Explore and Catalog Page for FlipStuck, developed strictly with 100% semantic HTML5 and Vanilla CSS3 without JavaScript dependencies.

---

## Key Features

- **Pure HTML & CSS Architecture**:
  - Developed strictly with standard semantic HTML5 and Vanilla CSS3.
  - Zero JavaScript dependencies: responsive top-down mobile navigation and slide-in filter drawer powered by CSS `:target` and `:checked` states.
  - Native smooth scrolling (`scroll-behavior: smooth`) with sticky header offset compensation (`scroll-margin-top`).
- **Hero and Search Section**:
  - Breadcrumb navigation (`Home > Explore Courses`).
  - High-contrast typography with custom serif italic styling (`Instrument Serif` / `Playfair Display`).
  - Search input form with icon indicators and query action.
- **Filter Controls**:
  - **Categories**: Web Development, Graphic Design, Data Science, Computer Basics, Video Editing, Beauty & Lifestyle, Digital Marketing, Music.
  - **Level**: Beginner, Intermediate, Advanced.
  - **Price**: Free, Paid.
  - **Rating**: 4.5 & up, 4.0 & up.
  - Form reset button (`Clear All Filters`) to restore default catalog view.
- **Course Catalog Grid**:
  - 9 course cards with authentic cropped thumbnails, instructor avatars, star rating metrics, student review counts, and enrollment pricing (`₹299` to `₹799`).
  - Status badges (`Best Seller`, `Trending`, `Popular`).
  - Interactive CSS hover transitions with subtle elevation and shadow expansion.
- **Footer and Design Assets**:
  - Multi-column category navigation with brand indicator accents.
  - Direct contact links for email, phone, and social media platforms.
  - Panoramic footer artwork illustration (`Assets-2/footer-bg.jpg`).
  - Standard legal and copyright bar.
- **Responsive Viewport Support**:
  - Top-down mobile navigation drawer with backdrop blur.
  - Slide-in mobile filter drawer with full touch support.
  - Floating back-to-top button.

---

## Repository Structure

```text
.
├── Assets-2/                   # Optimized image assets, course thumbnails, avatars, favicons
├── TaskThree/                  # Task distribution package
│   ├── Assets-2/
│   ├── Course Explore Page.png
│   ├── Course Page UI.png
│   ├── HomePage UI (2).png
│   ├── index.html
│   └── style.css
├── favicon.ico                 # Multi-resolution favicon
├── favicon.png                 # Apple touch icon and PWA icon
├── index.html                  # Semantic HTML5 catalog markup
├── site.webmanifest            # Web application manifest
├── style.css                   # Vanilla CSS design system
├── vercel.json                 # Production routing and cache headers
└── README.md                   # Project documentation
```

---

## Local Development

To view the project locally, open `index.html` (or `TaskThree/index.html`) directly in any modern web browser. No compilation, bundling, or runtime servers are required.

```bash
# Optional local HTTP server:
python3 -m http.server 3000
```

---

## Deployment

This project is deployed to Vercel and can be accessed at:
https://sandbyte-flipstuck-task-three.vercel.app
