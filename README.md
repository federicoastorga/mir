# mir — portfolio

Simple static portfolio site. No build step, no dependencies.

## Files

- [index.html](index.html) — page content (text, projects, links)
- [styles.css](styles.css) — colors, fonts, layout
- [images/](images/) — project images

## How to edit

1. Open `index.html` in any text editor.
2. Look for lines marked `<!-- EDIT: ... -->` — those are the parts meant to be changed.
3. To add a project, copy one `<article class="project">` block inside the `<div class="projects">` and update the image, title, and description.
4. Save the file and refresh the browser.

## How to preview locally

Double-click `index.html` to open it in a browser. That's it.

## How to publish

Easiest option: drag this folder onto [netlify.com/drop](https://app.netlify.com/drop) — gives you a free URL instantly.
Other free options: GitHub Pages, Cloudflare Pages, Vercel.
