# 🎵 Soundwave — Static Website Project

A fully responsive, multi-page music streaming landing page inspired by Spotify.
Built with semantic HTML5, modular CSS, and vanilla JavaScript.

---

## 📁 Project Structure

```
spotify-clone/
│
├── index.html              # Home page (hero, features, trending, plans, CTA)
│
├── pages/
│   ├── premium.html        # Premium subscription comparison page
│   ├── support.html        # Help center with FAQ accordion
│   └── download.html       # App download page for all platforms
│
├── css/
│   ├── reset.css           # Browser normalize / box-sizing reset
│   ├── variables.css       # CSS custom properties (design tokens)
│   ├── layout.css          # Global structure, containers, grid layouts
│   ├── components.css      # Buttons, cards, navbar, player, tracks, etc.
│   ├── animations.css      # Keyframes & scroll-triggered reveals
│   └── responsive.css      # Media queries (1024px, 900px, 768px, 480px)
│
├── js/
│   ├── navbar.js           # Scroll-sticky navbar + hamburger toggle
│   └── animations.js       # IntersectionObserver for fade-in-on-scroll
│
└── README.md               # This file
```

---

## 🚀 Features

- **Responsive Design** — Works on mobile, tablet, and desktop
- **Semantic HTML5** — `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- **Modular CSS** — Separated into reset, variables, layout, components, animations, responsive
- **CSS Custom Properties** — Consistent design tokens throughout
- **Scroll Animations** — IntersectionObserver-based fade-up reveals
- **Sticky Navbar** — Adds background on scroll + mobile hamburger menu
- **Accessible** — ARIA labels, roles, focus management
- **Multiple Pages** — Home, Premium, Support (FAQ accordion), Download
- **Transitions & Micro-interactions** — Hover effects, card lifts, badge floats

---

## 🎨 Design Decisions

| Token         | Value                |
|---------------|----------------------|
| Primary color | `#1DB954` (green)    |
| Background    | `#121212`            |
| Surface       | `#1e1e1e` / `#282828`|
| Font display  | Montserrat (900 weight) |
| Font body     | Inter                |

---


Built for Sprint Internship — Web Development Project 1
