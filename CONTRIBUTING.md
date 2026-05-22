# Contributing to Moe Kyaw Aung Portfolio V13

Thank you for your interest in contributing! 🙏

## 🛠 How to Contribute

### 1. Fork & Clone
```bash
git clone https://github.com/Dev-moe-kyawaung/Moe-Kyaw-Aung-Portfolio-V13.git
cd Moe-Kyaw-Aung-Portfolio-V13
```

### 2. Create a Branch
```bash
# Bug fix
git checkout -b fix/your-fix-description

# New feature
git checkout -b feat/your-feature-description
```

### 3. Make Changes
- Keep all code in `index.html` (single-file architecture)
- Follow existing naming conventions (BEM-like CSS, camelCase JS)
- Test on Chrome, Firefox, Safari, and mobile
- Ensure no console errors

### 4. Commit with Conventional Commits
```bash
git commit -m "fix: correct mobile nav z-index on iOS Safari"
git commit -m "feat: add language switcher for Burmese/English"
git commit -m "docs: update README with new live demo links"
git commit -m "style: adjust particle canvas opacity on light mode"
```

### 5. Open a Pull Request
- Fill in the PR template
- Link any related issues
- Describe what changed and why

---

## 📋 Code Style Guidelines

### HTML
- Use semantic elements (`<section>`, `<nav>`, `<main>`, `<footer>`)
- Include `aria-label` / `aria-hidden` / `role` attributes
- Indent with 2 spaces

### CSS
- Use CSS custom properties (`var(--name)`) for all colours and spacing
- Group rules: layout → typography → colours → transitions
- Mobile-first media queries

### JavaScript
- ES6+ syntax (const/let, arrow functions, template literals)
- Comment complex logic blocks
- No external libraries — keep it dependency-free

---

## 🐛 Reporting Bugs

Use the **Bug Report** issue template. Include:
- Browser + version
- Device type (desktop/tablet/mobile)
- Steps to reproduce
- Expected vs actual behaviour
- Console error messages (if any)

---

## 💡 Suggesting Features

Use the **Feature Request** issue template. Describe:
- The problem you're solving
- Your proposed solution
- Any design/UX considerations

---

## 🤝 Code of Conduct

Please read [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) before contributing.

---

*Questions? Email: moekyawaung@engineer.com*
