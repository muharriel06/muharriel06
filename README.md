<div align="center">

# MUHARRIEL — Creative Digital Experience

**Designing digital worlds at the intersection of design, technology and immersive experiences.**

`MUHE` · Creative Developer based in Indonesia

[![React](https://img.shields.io/badge/React-18-101C2C?style=flat-square&logo=react&logoColor=A8957D)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-6-101C2C?style=flat-square&logo=vite&logoColor=A8957D)](https://vite.dev)
[![Pure CSS](https://img.shields.io/badge/CSS-3-101C2C?style=flat-square&logo=css3&logoColor=A8957D)](https://developer.mozilla.org/docs/Web/CSS)
[![No Animation Libraries](https://img.shields.io/badge/motion-hand--crafted-A8957D?style=flat-square)](.)

</div>

---

> "Exploring the intersection between design, technology and immersive digital experiences. Every project is an opportunity to push creative boundaries and build something extraordinary."

A cinematic single-page portfolio built around a warm bronze and deep navy art direction. Not a template — every interaction is hand-crafted: a counting loader, a cursor with a personality, pointer-driven 3D tilts, parallax typography, and scroll-triggered reveals.

## `01` — The Experience

| Moment | What happens |
| --- | --- |
| **Loader** | The letters `M U H E` rise into frame while a line sweeps across, then the curtain lifts. |
| **Hero** | Headline lines stagger in one by one, a museum-scale `MUHE` watermark drifts with parallax, and the portrait tilts in 3D under the pointer. |
| **Cursor** | A custom cursor morphs between `hover`, `view` and `nav` states depending on what it touches. |
| **Navigation** | A floating nav that inverts its palette whenever it crosses into a dark section. |
| **Space** | Floating rings, spheres and glass shards orbit a second 3D portrait — the "vision" chapter. |
| **Reveal** | Sections fade and rise via `IntersectionObserver`, with staggering delays for rhythm. |

## `02` — Chapter Map

```
01  Hero          CREATIVE DIGITAL EXPERIENCE.
02  About         Hi, I'm Muharriel. Most people call me MUHE.
03  Portfolio     Selected work — brand, product, 3D and visual experiments.
04  Services      UI/UX, Web Development, 3D Web, Brand Identity, Creative Direction, Motion.
05  Journey       The timeline from design intern to independent creative developer.
06  Vision        Designing digital worlds.
07  Connect       Let's create something.
```

## `03` — Design Language

**Palette**

| Token | Hex | Role |
| --- | --- | --- |
| `--navy-dark` | `#101C2C` | Deep space background |
| `--navy-mid` | `#16263A` | Elevated dark surface |
| `--navy-light` | `#1D3045` | Dark section edge |
| `--coksu-primary` | `#A8957D` | Bronze accent, the signature |
| `--coksu-light` | `#B7A58C` | Muted bronze |
| `--white-broken` | `#F3F0E8` | Bone light background |
| `--white-warm` | `#E8E4DA` | Warm paper |
| `--black` | `#0A0A0A` | Ink |

**Type**

- **Space Grotesk** — display, headlines, oversized statements.
- **Inter** — body, navigation and interface copy.

The system is token-first: color, spacing, radius, easing and z-index all live in `:root` inside `src/index.css`, so the whole identity can shift from one place.

## `04` — Built With

- **React 18** — component-driven sections
- **Vite 6** — instant dev server and optimized production builds
- **Vanilla CSS** — a full design system, no Tailwind, no UI kit
- **CSS 3D + requestAnimationFrame** — tilt effects without WebGL
- **IntersectionObserver** — lightweight scroll reveals
- **Google Fonts** — Inter & Space Grotesk

## `05` — Getting Started

```bash
# install
npm install

# develop
npm run dev

# ship
npm run build
npm run preview
```

## `06` — Project Structure

```
.
├── index.html
├── public/
│   └── assets/
│       └── muhe-nobg.png        # Portrait cut-out used across sections
└── src/
    ├── main.jsx
    ├── App.jsx                  # Chapter composition
    ├── index.css                # Design tokens + full visual system
    ├── components/
    │   ├── Loader.jsx           # Cinematic intro
    │   ├── Cursor.jsx           # Custom cursor
    │   ├── Nav.jsx              # Adaptive navigation
    │   ├── Hero.jsx             # 3D tilt + parallax hero
    │   ├── About.jsx
    │   ├── Work.jsx             # Selected projects
    │   ├── Expertise.jsx        # Services
    │   ├── Experience.jsx       # Timeline
    │   ├── Space3D.jsx          # Floating objects / vision
    │   ├── Contact.jsx
    │   └── Footer.jsx
    └── hooks/
        ├── useCursor.js
        └── useReveal.js
```

## `07` — Details That Matter

- **Responsive** — breakpoints at `1024px` and `768px`, including a dedicated mobile menu.
- **Accessible motion** — `prefers-reduced-motion` is respected.
- **Performance** — a single lightweight portrait asset, no 3D engine, no animation dependency.
- **Consistent craft** — one easing family, one spacing scale, one palette.

---

<div align="center">

**Have an idea, project or collaboration in mind?**

[hello@muhe.dev](mailto:hello@muhe.dev) · [GitHub](https://github.com/muharriel06)

© 2026 MUHARRIEL — **BUILT WITH CURIOSITY.**

</div>
