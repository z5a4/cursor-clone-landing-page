Hey — quick README for this small landing page project.

What this is
- A simple static landing page prototype (no build tools).
- Files: `landingpage.html` (markup) and `styles.css` (all page styles).
- Images live in the `images/` folder (hero-image.png and various assets).

How to preview
1. Open `landingpage.html` in your browser (double-click or `Open With -> Browser`).
2. No server required — just static HTML/CSS.

Quick notes / where things live
- Header: markup at the top of `landingpage.html` inside the `<header>` tag. If you want to change links or the logo, edit that block.
- Hero: in `landingpage.html` under the `.hero` section — swap `./images/hero-image.png` for a different image or change the text/button.
- Sections: the page is split into sections (trusted logos, features, testimonials, frontier, about/join, highlights, CTA, footer). Each section has a comment above it in `landingpage.html` so you can find it easily.
- Styling: everything is in `styles.css`. Tweak paddings, colors, and fonts there. Media queries are near the bottom of the file (`@media (max-width: 992px)` and `@media (max-width: 640px)`).
- Images: add or replace images in the `images/` folder and update the `src` paths in `landingpage.html`.

Class names
- The code intentionally uses straightforward class names (e.g. `.feature-card`, `.hero`, `.footer`) so it's easy to read and edit — feel free to rename, but update both HTML and CSS together.

Accessibility & performance tips
- Add `alt` text to all images (some already have it). Good for a11y and SEO.
- Consider optimizing images (resize/compress) for faster load times.

If you want next
- I can extract repeated color values into CSS variables for easier theming.
- I can add a small live-reload dev server (`npx serve` or similar) if you want to preview edits quickly.
- I can split CSS into smaller files or switch to SCSS if you plan a larger site.

Want anything changed right now? Tell me which part to tweak and I’ll update it.
