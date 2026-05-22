# Changelog

All notable changes to **Moe Kyaw Aung Portfolio** are documented here.

Format: [Semantic Versioning](https://semver.org) · Date: YYYY-MM-DD

---

## [V13] — 2026-05-21 · 🚀 Current Release

### ✨ Added
- Complete 17-section single-file portfolio
- Animated particle canvas hero with connecting-line mesh
- Custom cursor — dot + magnetic ring effect
- Dark / Light mode toggle with CSS custom property transitions
- Parallax depth scrolling on hero section
- Masonry grid for Projects, Skills, Certificates, GitHub Accounts
- Scroll-triggered counter animation (12 yrs · 60+ apps · 43 profiles)
- Skill progress bars with IntersectionObserver trigger
- Testimonial carousel — auto-play every 5.5s with dot navigation
- Image lightbox gallery — 12 photos with keyboard (Esc) close
- Contact form — full client-side validation, success state
- FAQ accordion with ARIA `aria-expanded` support
- Newsletter subscription form with confirmation
- Back-to-top button (appears at 400px scroll)
- Sticky CTA "Hire Me" button
- Google Maps embed (Tachileik, Myanmar)
- GitHub Pages CI/CD workflow (`.github/workflows/deploy.yml`)
- 43 GitHub profile links rendered dynamically
- 33 Lovable PWA links section
- 20 professional email addresses collection
- Full social media accounts grid
- Organizations & memberships section
- Pricing table — Starter / Professional / Enterprise
- Responsive hamburger mobile menu (≤ 768px)
- WCAG-compliant ARIA labels throughout
- SEO meta tags + Open Graph tags

### 🎨 Design
- Colour palette: `#222831` · `#393E46` · `#948979` · `#DFD0B8` · `#c8a97e`
- Fonts: Bebas Neue (display) · DM Sans (body) · JetBrains Mono (code/labels)
- All icons: inline SVG — zero external CDN dependency
- All images: Cloudinary CDN with WebP support

### 🛠 Technical
- Zero npm / zero build tools — pure HTML + CSS + JS
- Preloader removed from layout during load (`overflow:hidden`)
- `IntersectionObserver` for all scroll animations
- Canvas particle system — 120 particles, connecting lines at < 120px
- Inline SVG icon library replacing Lucide CDN (fixes `is not defined` error)

---

## [V12] — 2026-04-15

### Changed
- Migrated icons from Font Awesome CDN to inline SVG
- Improved mobile sidebar animation timing
- Fixed carousel touch-swipe on Android WebView

---

## [V11] — 2026-03-02

### Added
- Thailand Resources Hub community section
- Myanmar character Matrix rain easter egg (Konami code)

### Fixed
- Skill bars not triggering on slow connections

---

## [V10] — 2026-01-20

### Added
- CI/CD GitHub Actions — 5-workflow Android pipeline reference section
- Acode plugin showcase (v2.0.42)

---

## [V9] — 2025-12-01

### Added
- MoekyawTranslator app feature card (Claude API, 8 languages)
- TFLite / AI section in Skills card

---

## [V8] — 2025-10-15

### Changed
- Full palette refresh to current charcoal/sand scheme
- Hero profile ring animation (dual concentric, counter-rotate)

---

## [V7] — 2025-08-30

### Added
- Testimonials carousel
- FAQ accordion section
- Pricing table

---

## [V6] — 2025-07-01

### Added
- Lightbox gallery
- Back-to-top button
- Custom cursor

---

## [V5] — 2025-05-10

### Added
- Dark/Light mode
- Animated counters

---

## [V1–V4] — 2024

- Initial builds exploring Three.js, Cosmic, Neon Cyberpunk, Synthwave, Luxury Gold themes
- Foundation GitHub profile README system (200+ component template)
