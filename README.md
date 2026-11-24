# Mathematics Learning Hub (MLH)

A bilingual (Vietnamese / English) mathematics learning library with a scientific visual identity. The project is designed to be both a personal study workspace and an open resource for a wider learning community.

## Version 0.1.0 — Foundation

Included in this first build:
- Responsive homepage for desktop, tablet and mobile.
- Vietnamese / English language switch.
- Eight mathematics subject domains.
- Subject search and level filters.
- Learning-path overview.
- Formula showcase rendered with MathJax.
- Initial workspace and community roadmap sections.
- Accessible navigation basics and reduced-motion support.

Not included yet: member accounts, cloud sync, user submissions, database, server-side symbolic computation, or a fully functional graphing/calculator engine. These require a backend or additional client-side modules and will be planned in later phases.

## Project structure

```text
mathematics-learning-hub/
├── index.html          # Main landing page
├── css/
│   └── styles.css      # Design system and responsive layout
├── js/
│   └── app.js          # Bilingual UI, subject catalog, search and filters
├── assets/
│   └── favicon.svg
├── data/               # Reserved for structured subject and exercise data
├── subjects/           # Reserved for individual subject modules
├── templates/          # Reserved for reusable lesson / exercise templates
└── README.md
```

## Run locally

1. Extract the project ZIP.
2. Open the folder in Visual Studio Code.
3. Start a local static server (for example, the **Live Server** extension), or use any simple HTTP server.
4. Open the local URL shown by the server.

The page loads MathJax and web fonts from public CDNs, so an internet connection is needed for those external resources. The rest of the site is static HTML, CSS and JavaScript.

## Publish with GitHub Pages

1. Create a public GitHub repository, for example `mathematics-learning-hub`.
2. Upload the contents of this project folder to the repository root (the `index.html` file must be at the root).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. After GitHub Pages finishes publishing, open the URL shown in the Pages settings.

## Contribution direction

Planned content contributions should include:
- A clear topic title in Vietnamese and English.
- Learning objectives and prerequisites.
- Definitions, theorems and properly formatted equations.
- A worked example with complete reasoning.
- Exercises with solutions or answer keys.
- References for non-original material.

## License

No license has been selected yet. Add a license before inviting public contributions or reusing third-party learning content.
