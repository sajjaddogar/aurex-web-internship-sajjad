# AUREX Full-Stack Engineering Internship — Week 2

**Intern Name:** Sajjad Ali  
**Domain:** Full-Stack Web Development  
**Week:** Week 2 — CSS3 Fundamentals + Modern Layouts (Flexbox & Grid) + Basic UI/UX + Responsive Web Design  

---

## 🌐 Live Deployment Link
- **Live URL:** [https://sajjaddogar.github.io/aurex-web-internship-sajjad](https://sajjaddogar.github.io/aurex-web-internship-sajjad) *(or Vercel deployment link)*

---

## 🎨 CSS Features & Layout Techniques Implemented

1. **CSS3 Core Fundamentals & Box Model:**
   - Universal box-sizing (`box-sizing: border-box`) for predictable spacing calculations.
   - CSS custom properties (variables) for consistent color palettes, typography, shadows, and border radii.
   - Clean visual hierarchy with styled cards, hover states, and smooth focus rings for interactive accessibility.

2. **Modern Layout Techniques:**
   - **Flexbox:**
     - Header / Hero component alignment.
     - Sticky navigation bar with centered, wrap-ready menu items.
     - Split layout for the About Me section (text and profile avatar).
     - Modern pill/tag layouts for skills lists.
     - Structured form and address item alignments.
   - **CSS Grid:**
     - Main layout vertical flow and section spacing.
     - Multi-column `skills-grid` for technical vs. soft skills.
     - Responsive two-column split in the Contact section (`form` + `address` info).

3. **Responsive Web Design & Media Queries:**
   - **Mobile-First Foundation:** Designed from single-column fluid mobile views up to large desktops.
   - **Breakpoints Implemented:**
     - **Mobile (< 768px):** Single-column stacked layouts, centered items, and touch-friendly controls.
     - **Tablet (≥ 768px):** 2-column grid for skills, side-by-side About section, and multi-column contact area.
     - **Desktop (≥ 1024px):** Enhanced padding, refined typography scaling (`clamp()`), and optimized image sizing.

---

## 💡 Key Learnings & Challenges Faced

### Key Learnings:
- Combining **CSS Grid** for macro-layouts (card grids, multi-column sections) with **Flexbox** for micro-layouts (navbars, pill badges, form controls).
- Structuring scalable CSS with variables and a consistent spacing system.
- Designing responsive layouts with mobile-first media queries to avoid code repetition and layout breaking.

### Challenges & Solutions:
- **Challenge:** Managing image scaling and circular profile clipping without distortion across screen widths.
  - **Solution:** Utilized `object-fit: cover` with explicit dimensions and fluid wrapper positioning.
- **Challenge:** Creating an aligned contact form next to address details that naturally stacks on mobile devices.
  - **Solution:** Used CSS Grid on `.contact-container` that shifts from `1fr` on small screens to `1.4fr 1fr` on tablets and desktops.

---

## 📸 Screenshots

| Desktop View | Tablet View | Mobile View |
| :---: | :---: | :---: |
| *(Add screenshot here)* | *(Add screenshot here)* | *(Add screenshot here)* |

---

## ✅ Completed Requirements Checklist

- [x] Transformed Week 1 HTML profile into a modern, professional portfolio using CSS3
- [x] Implemented Flexbox and CSS Grid layouts
- [x] Added responsive media queries for Desktop, Tablet, and Mobile
- [x] Maintained visual consistency, clear typography, and clean box-model spacing
- [x] Formatted repository according to standard structure (`index.html`, `style.css`, `README.md`)
- [ ] Published live on GitHub Pages or Vercel and updated the live link
- [ ] Added 3 screenshots (Desktop, Tablet, Mobile) before submission