# Peter Kimeli — Portfolio

Personal portfolio site for Peter Kimeli, Senior DevSecOps & AI Platform Engineer. Static HTML/CSS/JS, no build step — ready for GitHub Pages.

## Structure

```
index.html      Page markup
css/style.css   Styles (dark theme, responsive)
js/script.js    Nav toggle, scroll reveal, active-link highlighting
cv.pdf          Downloadable CV (linked from the "Download CV" buttons)
```

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a GitHub repository (e.g. `peterkimeli.github.io` for a user site, or any name for a project site).
2. Push this directory's contents to the `main` branch.
3. In the repo, go to **Settings → Pages**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — GitHub will publish the site at `https://<username>.github.io/` (user site) or `https://<username>.github.io/<repo>/` (project site) within a minute or two.

If using a project repo name, no code changes are needed since all asset links in `index.html` are relative.

## Updating content

Edit the CV facts directly in `index.html` (sections are labeled `<!-- HERO -->`, `<!-- ABOUT -->`, `<!-- SKILLS -->`, `<!-- PROJECTS -->`, `<!-- EXPERIENCE -->`, `<!-- EDUCATION -->`, `<!-- CONTACT -->`). Replace `cv.pdf` with an updated file of the same name to keep the download links working.
