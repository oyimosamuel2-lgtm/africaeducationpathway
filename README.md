# AED African Education Pathway — Website

Static website (HTML, CSS, JavaScript — no build step needed).

## Structure
```
index.html        ← the page
css/style.css     ← styles & animations
js/main.js        ← menu, scroll animations, contact form
assets/img/       ← logo and photos
.nojekyll         ← tells GitHub Pages to serve files as-is
```

## Publish on GitHub Pages
1. Create a new repository on GitHub (e.g. `aed-website`), set to **Public**.
2. Upload all the files in this folder (keep the folder structure) — "Add file → Upload files", drag everything in, then **Commit**.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/aed-website/`.

To use a custom domain (e.g. aedpathway.com), add it under Settings → Pages → Custom domain and point your DNS to GitHub.

## Editing
- Text: edit `index.html`.
- Colours: change the variables at the top of `css/style.css` (`--yellow`, `--green`, …).
- Contact form: opens the visitor's email app addressed to aedafricaneducationpathway@gmail.com. For a form that sends without an email app, sign up at formspree.io and point the form at your Formspree endpoint.
