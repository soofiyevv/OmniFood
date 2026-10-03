# Omnifood

A responsive landing page for Omnifood, a fictional AI-powered food subscription service that delivers healthy meals every day. Built with plain HTML, CSS and a small amount of vanilla JavaScript.

## Features

- Fully responsive layout with five breakpoints (from large desktops down to phones)
- Sticky navigation that appears after scrolling past the hero section
- Mobile navigation with an animated full-screen menu
- Smooth scrolling between sections
- Sections: hero, "featured in" logos, how it works, meals, testimonials with a photo gallery, pricing, sign-up form, footer
- Hero image served as WebP with a PNG fallback
- Footer year updated automatically

## Built with

- HTML5
- CSS3 (Flexbox, CSS Grid, media queries, `rem`-based sizing)
- Vanilla JavaScript (Intersection Observer API for the sticky header)
- [Ionicons](https://ionic.io/ionicons) for icons
- [Rubik](https://fonts.google.com/specimen/Rubik) from Google Fonts

## Project structure

```
Omnifood/
├── index.html
├── manifest.webmanifest
├── css/
│   ├── general.css    # reset, typography, reusable components (grid, buttons, lists)
│   ├── style.css      # section styles
│   └── queries.css    # media queries
├── js/
│   └── script.js      # mobile nav, smooth scrolling, sticky header
└── img/               # logos, meals, customers, gallery, app screens
```

## Running locally

No build step or dependencies are needed.

```bash
git clone https://github.com/<your-username>/omnifood.git
cd omnifood
```

Then open `index.html` in a browser, or serve the folder with any static server, for example:

```bash
python -m http.server 8000
```

and visit `http://localhost:8000`.

## Notes

- The sign-up form uses the `netlify` attribute, so submissions are only collected when the site is deployed on Netlify. On other hosts (such as GitHub Pages) the form is display-only.
- Omnifood is not a real company. All content, prices and testimonials are placeholders.

## Author

Kanan Sofiyev
