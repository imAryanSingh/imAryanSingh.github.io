# Aryan Singh

My portfolio site built with plain HTML, CSS, and vanilla JavaScript. Showcases my research, internships, projects, and achievements in AI/ML.

**Live site:** https://imAryanSingh.github.io

![theme](https://img.shields.io/badge/theme-dark%20%2F%20light-7c6ff7)
![no-build](https://img.shields.io/badge/build-none%20required-4ade80)
![license](https://img.shields.io/badge/license-MIT-blue)

---

## Features

- **Dark / light theme toggle** — persists across visits via `localStorage`, defaults to the visitor's system preference on first load
- **Fully responsive** — desktop nav, mobile-friendly stacked layout
- **Scroll-triggered fade-in animations** using `IntersectionObserver`
- **Sections:** About, Education, Experience, Projects, Skills, Recognition, Contact
- Zero dependencies — a single `index.html` file, no `npm install`, no build tooling

## Tech stack

| Layer | Tech |
|---|---|
| Markup | Semantic HTML5 |
| Styling | CSS3 (custom properties / CSS variables for theming) |
| Interactivity | Vanilla JavaScript |
| Hosting | Any static host (GitHub Pages, Vercel, Netlify) |

## Project structure

```
.
├── index.html      # entire site — markup, styles, and script in one file
└── README.md
```

## Running locally

No build step required. Just open the file directly:

```bash
git clone https://github.com/imAryanSingh/<your-repo-name>.git
cd <your-repo-name>
open index.html    # macOS
# or
start index.html   # Windows
# or
xdg-open index.html # Linux
```

Or serve it with any static server, e.g.:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

This is a static file, so it deploys anywhere with zero configuration:

- **GitHub Pages:** Settings → Pages → Deploy from branch → select `main` / root, and `index.html` will be served automatically.
- **Vercel / Netlify:** Import the repo — no build command or output directory needed.

## Customizing

- **Theme colors** — edit the CSS custom properties in `:root` and `[data-theme="light"]` at the top of `index.html`.
- **Content** — each section is clearly commented (`<!-- HERO -->`, `<!-- EXPERIENCE -->`, `<!-- PROJECTS -->`, etc.) for easy editing.
- **Contact links** — update the email, LinkedIn, GitHub, and resume links in the `#contact` section.

## License

Free to use and adapt for your own portfolio.
