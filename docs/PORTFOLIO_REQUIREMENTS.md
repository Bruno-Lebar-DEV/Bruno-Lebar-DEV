# Portfolio Website - Implementation Checklist

---

## 0. Visual Identity & Branding
- [x] Define main color palette: **Purple** and **Blue** (tech-oriented, minimal, professional)
- [x] Choose minimalist and modern style
- [x] Use repository name **Bruno-Lebar-DEV** as site title (logo to be added in the future)
- [x] Select main and accent fonts: **Sans-serif** for body, **Montserrat** for headings

### Color Palette (Modern & Vibrant)
- **Primary (Purple):** #7C3AED (violet-600)
- **Secondary (Blue):** #2563EB (blue-600)
- **Background Light:** #F9FAFB (gray-50)
- **Background Dark:** #21252B (One Dark Theme blueish dark)
- **Text Light:** #18181B
- **Text Dark:** #F9FAFB
- **Accent:** #A21CAF (fuchsia-700) or #38BDF8 (sky-400)

---

## 1. Project Setup
- [ ] Install Node.js and npm (if not already installed)
- [ ] Create project folder and initialize with Vite (React template)
- [ ] Install Tailwind CSS and configure tailwind.config.js
    - [ ] Add custom colors to Tailwind config
    - [ ] Enable dark mode
- [ ] Install React Router and set up basic routes
- [ ] Install i18next and create translation files (pt, en)
- [ ] Install Headless UI or Radix UI for modals
- [ ] Add Montserrat font via Google Fonts or npm

---

## 2. Structure & Pages
- [ ] Create layout component (header, footer, main content)
- [ ] Implement global theme toggle (dark/light)
- [ ] Implement global language switcher (Portuguese/English)
- [ ] Create Home page (intro, highlights)
- [ ] Create dedicated page for each project category:
    - [ ] Enterprise Solutions (ADVPL/TOTVS Protheus)
    - [ ] Mobile Development
    - [ ] Web Development
    - [ ] Backend & API Development
    - [ ] Game Development
    - [ ] DevOps & Infrastructure
    - [ ] Learning & Documentation

---

## 3. Project Cards & Popups
- [ ] List projects as cards/components in each category page
- [ ] Implement modal/popup for each project with detailed info
- [ ] Add subtle and modern animations (transitions, hover, card reveal)
- [ ] Ensure accessibility for all modals/popups

---

## 4. Content & Features
- [ ] About Me section
- [ ] Achievements & Certifications section
- [ ] Pinned/Featured Projects section
- [ ] Testimonials section (optionally carousel)
- [ ] Tech Stack visual overview
- [ ] Blog & Articles section (links only)
- [ ] Languages spoken section
- [ ] Contact callout section
- [ ] [Future] Functional contact form (with validation/feedback)
- [ ] [Future] Project filtering/search by technology
- [ ] [Future] Animated background or particles
- [ ] [Future] Downloadable CV/resume

---

## 5. Responsiveness, Accessibility & Performance
### 5.1 Responsiveness
- [ ] Make the site fully responsive (mobile-first)
- [ ] Optimize images and assets
- [ ] Implement lazy loading for project details and images

### 5.2 Accessibility
- [ ] All images have descriptive alt text
- [ ] All interactive elements are keyboard accessible
- [ ] Sufficient color contrast for text and UI
- [ ] Modals can be closed via keyboard (ESC)
- [ ] Test navigation with screen reader

### 5.3 SEO
- [ ] Add meta tags (title, description, og:image)
- [ ] Set unique title/description for each page
- [ ] Add favicon
- [ ] Generate sitemap.xml
- [ ] Add robots.txt

### 5.4 Performance
- [ ] Test with Lighthouse (Google Chrome)
- [ ] Optimize and compress images
- [ ] Remove unused dependencies
- [ ] Minimize bundle size
- [ ] Enable code splitting (React.lazy/Suspense)

---

## 6. Deployment & Hosting
- [ ] Test build locally before deploy
- [ ] Configure GitHub Pages for static site
- [ ] Add README with deploy instructions
- [x] Initial hosting on GitHub Pages
- [ ] [Future] Configure custom domain and HTTPS
- [ ] [Future] Option to migrate to Vercel, Netlify, etc.

---

## 7. Bugs & Pending Tasks
- [ ] (Anote aqui qualquer bug ou ajuste identificado durante o desenvolvimento)

---

## 8. References & Inspirations
- [ ] [One Dark Theme](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)
- [ ] [Tailwind UI](https://tailwindui.com/)
- [ ] [Awwwards Portfolios](https://www.awwwards.com/websites/portfolio/)
- [ ] [Vercel Templates](https://vercel.com/templates/next.js)

---

*Check off each item as you implement your portfolio site. This checklist will help ensure all requirements and best practices are covered.*
