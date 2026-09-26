# Shurui Li — personal website

A single-page static website for GitHub Pages. No build step is required.

## Publish

1. Create a public GitHub repository named `<your-username>.github.io`.
2. Copy `index.html`, `styles.css`, and the `assets/` directory into the repository root.
3. Push to the `main` branch. In the repository's **Settings → Pages**, choose deployment from the `main` branch and the repository root.
4. Open `https://<your-username>.github.io` after GitHub finishes publishing.

## Before publishing

- Review the text and public contact email. No personal photo is included.
- The publications section lists verified public records as preprints, journal articles, and conference and workshop contributions. Check each record's publication status before changing a preprint to an accepted venue.
- The VSS 2025 oral slides and poster PDFs are bundled in `assets/`. The VSS 2026 entry links only to the public abstract.
- The CSD project includes its public ScienceDB dataset, paper, and code links. AVID is marked as coming soon with a ScienceDB preview link.
- The site uses system fonts and has no build dependencies. The ScienceDB statistics widget loads the [official widget script](https://www.scidb.cn/help?p=widgets_component) from jsDelivr; the dataset link remains available if the script cannot load.

Edit the copy in `index.html` and the colors/layout in `styles.css`.
