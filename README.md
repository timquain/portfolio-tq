# JayTees Professional Portfolio — Web Version

This is a single-page web portfolio that mirrors the Professional Portfolio Artifact template.

## Edit the HTML
1. Open `index.html` in your editor (VS Code, Sublime, etc.).
2. Update text in the **Hero**, **Snapshot Grid**, **Timeline**, and **Artifacts** sections to reflect your work.
3. Replace image references in `assets/` (e.g., `assets/hero.jpg`). Keep file names or update the `src` attributes in the `<img>` tags.
4. Save the file and refresh your browser to see the changes.

## Local Preview
Use a lightweight static server so relative assets load correctly:
```bash
python3 -m http.server 8000
# visit http://localhost:8000 in your browser
```

## Deploy to GitHub Pages
1. Create a repo (e.g., `jaytees-professional-portfolio`).
2. Commit and push `index.html`, `assets/`, and supporting files to `main`.
3. In GitHub → **Settings** → **Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`.
4. Wait for the build to finish; your site appears at `https://<username>.github.io/<repo-name>/`.

## Deploy to Netlify
- Drag the folder to https://app.netlify.com/drop, or connect the repo and set **Build command** to `none` and **Publish directory** to `/` (root). Deploys happen automatically on git push.

## Screenshots
Put images into `assets/` and reference from `index.html`:
```html
<img src="assets/docs-screenshot.png" alt="API docs">
```
