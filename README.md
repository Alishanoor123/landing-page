# TalentFlow — Landing Page

## Oasis Infobyte Internship

**Web Development & Designing**
Level 1 – Task 1

---

## Project Overview

TalentFlow is a fictional AI-powered hiring platform landing page. The site presents TalentFlow as a recruitment product that helps companies find top talent through intelligent candidate matching, verified credentials, and team collaboration tools.

The landing page is designed to look and feel like a real product website — complete with a hero section, feature cards, a how-it-works walkthrough, an about section, client testimonials, a contact section, and a professional footer.

---

## Objective

This project was created as a **static landing page** using **HTML5** and **CSS3** only, as part of the Oasis Infobyte Web Development & Designing internship (Level 1, Task 1).

The goal is to demonstrate foundational web design and layout skills including semantic HTML structure, CSS Flexbox and Grid layouts, responsive design with media queries, CSS variables, hover states, and clean visual hierarchy — without relying on any JavaScript or CSS frameworks.

---

## Technologies Used

- HTML5
- CSS3

---

## Features

- **Sticky navigation bar** — fixed to the top, stays visible while scrolling
- **5 navigation links** — Home, Features, How It Works, About, Contact
- **Hero section** — headline, subheadline, two CTA buttons, stats bar, and a CSS-drawn visual card with floating info cards
- **Features section** — 6 feature cards in a CSS Grid layout with hover effects
- **How It Works section** — 3-step process with numbered indicators
- **About section** — two-column layout with a quote card, stats panel, and brand story text
- **Testimonials section** — 3 client testimonial cards with one accent-variant card
- **Contact section** — contact details (email, phone, location), social links, and a static visual form
- **Footer** — brand column, 3 navigation columns, social icons, and copyright bar
- **Responsive design** — fully adapts across desktop, tablet, and mobile breakpoints
- **CSS-only hover effects** — on nav links, buttons, cards, and social links
- **CSS variables** — entire color palette managed through `:root` variables for easy customization
- **Smooth scroll** — `scroll-behavior: smooth` applied via CSS
- **Accessible markup** — semantic HTML5 elements, heading hierarchy, `aria-label`, `alt` attributes, and visible focus states
- **Mobile-friendly layout** — stacks columns, adjusts typography and spacing at small screen sizes
- **No JavaScript** — 100% static HTML and CSS

---

## Color Palette

Update the values below after selecting your final colors. To apply them to the project, edit the `:root` block at the top of `style.css`.

| Role              | Variable                | Current Value | Your Value |
|-------------------|-------------------------|---------------|------------|
| Primary           | `--primary-color`       | `#F1CF54`     |            |
| Primary Dark      | `--primary-dark`        | `#D9B29C`     |            |
| Accent            | `--accent-color`        | `#E54C44`     |            |
| Background        | `--bg-color`            | `#FFFCEF`     |            |
| Dark Background   | `--bg-dark`             | `#000000`     |            |
| Card Background   | `--bg-card`             | `#FFFFFF`     |            |
| Body Text         | `--text-color`          | `#111111`     |            |
| Muted Text        | `--text-muted`          | `#555555`     |            |
| Light Text        | `--text-light`          | `#888888`     |            |
| Text on Dark      | `--text-on-dark`        | `#FFFCEF`     |            |
| Border            | `--border-color`        | `#E8E2C8`     |            |

---

## Project Structure

```
WebDev-L1-LandingPage/
│
├── index.html          ← Main HTML file (all page sections)
├── style.css           ← All styles (variables, layout, responsive)
├── README.md           ← Project documentation (this file)
│
└── screenshots/        ← Add project screenshots here before submission
```

---

## How to Run

This is a fully static project — no build tools, no server, and no dependencies required.

1. Open the project folder
2. Double-click `index.html`  
   **or** right-click → *Open with* → your browser of choice
3. The page will load instantly in your browser

Tested and compatible with:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

---

## Page Sections

| Section        | ID               | Description                                      |
|----------------|------------------|--------------------------------------------------|
| Navigation     | `#home`          | Sticky navbar with logo and 5 anchor links       |
| Hero           | `#hero`          | Headline, subheadline, CTA buttons, stats, card  |
| Features       | `#features`      | 6 feature cards in a 3-column CSS Grid           |
| How It Works   | `#how`           | 3-step numbered process on yellow background     |
| About          | `#about`         | Two-column layout on dark background             |
| Testimonials   | `#testimonials`  | 3 client quotes with one accent card             |
| Contact        | `#contact`       | Contact info, social links, static form          |
| Footer         | *(footer)*       | Brand, nav columns, social icons, copyright      |

---

## Responsive Breakpoints

| Breakpoint | Target               |
|------------|----------------------|
| 1200px     | Large desktop        |
| 1024px     | Laptop               |
| 768px      | Tablet               |
| 600px      | Large mobile         |
| 480px      | Small mobile         |
| 390px      | Very small phones    |

---

## Requirements Checklist

- [x] HTML5
- [x] CSS3
- [x] No JavaScript
- [x] No frameworks or libraries
- [x] Fixed / sticky navigation
- [x] At least 3 navigation links (5 implemented)
- [x] Hero headline
- [x] Hero subheadline
- [x] CTA button
- [x] At least 2 distinct content sections (6 implemented)
- [x] Footer
- [x] Contact placeholders (email, phone, location)
- [x] Social placeholders (LinkedIn, GitHub, Instagram, Twitter)
- [x] Consistent color palette via CSS variables
- [x] Responsive layout (CSS media queries)
- [x] CSS Flexbox used
- [x] CSS Grid used
- [x] No element overlap
- [x] No horizontal scrolling
- [x] Intentional padding and margins throughout
- [x] Clean readable typography
- [x] Clear heading hierarchy (H1 → H2 → H3)
- [x] At least two font sizes
- [x] Hover states on nav, buttons, cards, and links
- [x] Semantic HTML5 elements (header, nav, main, section, footer, article, blockquote)
- [x] Scroll-behavior: smooth
- [x] Accessible focus states
- [x] Meta charset and viewport set
- [x] Meaningful page title and meta description
- [x] `box-sizing: border-box` applied globally
- [x] Centered container system with max-width
- [x] Static form (no backend, no data submission)

---

## Internship Details

| Field         | Value                            |
|---------------|----------------------------------|
| Organization  | Oasis Infobyte                   |
| Track         | Web Development & Designing      |
| Level         | Level 1                          |
| Task          | Task 1 – Landing Page            |
| Stack         | HTML5, CSS3                      |

---

*© 2026 TalentFlow. Built for the Oasis Infobyte Internship — Level 1, Task 1.*
