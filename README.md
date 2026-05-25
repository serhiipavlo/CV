# Serhii Pavlo — CV site

Single-page CV / landing page tailored for the **API Automation Engineer / QA Engineer** role at Halo lab.

- `index.html` — content (cover letter, transferable experience, stack, timeline, contact).
- `styles.css` — dark, responsive design. No framework, no build step.
- `.github/workflows/pages.yml` — auto-deploy to GitHub Pages on every push to `main`.

## Local preview

Just open `index.html` in a browser, or:

```bash
python -m http.server 8080
# then visit http://localhost:8080
```

## Deploy

Pushes to `main` are deployed automatically by GitHub Actions.

**One-time setup in the repo:**
Settings → Pages → *Source* → **GitHub Actions**.

After that, the workflow publishes to:

```
https://serhiipavlo.github.io/CV/
```
