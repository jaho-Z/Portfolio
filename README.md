# Gate Of Time Portfolio Website

This repository contains the GitHub Pages deployment output for **Gate Of Time**, a cultural experience project about Suzhou Changmen.

The live page is built from the latest React/Vite portfolio source project and copied here as static files so GitHub Pages can serve it directly from the repository root.

## Repository Structure

```text
.
|-- assets/        Built JavaScript and CSS bundles
|-- images/        Static image assets used by the page
|-- index.html     GitHub Pages entry point
|-- README.md      Repository notes
`-- 文字稿.md      Original project manuscript / content draft
```

## Deployment Notes

This repository is intended to stay as a static deployment repository. To update the page:

```bash
cd ../CPT208_GroupA1-4_ProjectName_Portfolio
npm install
npm run build
```

Then copy the generated `dist/` output into this repository root, commit the changes, and push to GitHub.
