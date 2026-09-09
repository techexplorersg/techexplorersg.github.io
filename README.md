# Satwik Gudapati — AI/ML Portfolio

A zero-cost, responsive static portfolio website based on the supplied resume and cover letter.

## Free hosting: GitHub Pages

GitHub Pages is available on GitHub Free for public repositories. A personal site uses a repository named `<your-username>.github.io` and is served from that GitHub Pages URL.

### Fastest setup

1. Create a **public** GitHub repository named `YOUR_GITHUB_USERNAME.github.io`.
2. Upload every file in this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under the build/deployment settings, choose **GitHub Actions** and deploy the provided workflow.
5. Your site will appear at `https://YOUR_GITHUB_USERNAME.github.io/`.

The workflow in `.github/workflows/pages.yml` publishes the static files directly; no framework or paid hosting is needed.

## Resume file

The website currently includes `Satwik-Gudapati-Resume.docx` as the downloadable resume. Replace it with a PDF later if you prefer, using the same filename (or update the link in `index.html`).

## Editing

The website is intentionally framework-free:
- `index.html` = content/structure
- `styles.css` = design
- `script.js` = mobile navigation
- `.github/workflows/pages.yml` = deployment

No build tool, npm install, database, API key, or paid service is required.
