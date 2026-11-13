# CAFAM website design proposals

A preapproved visual reference of the current CAFAM design, followed by seven interactive static alternatives for review. The landing page provides access to every concept and a desktop/mobile preview. The seventh proposal combines the first and third directions.

## Browse

Visit **https://nicolasgomez2093.github.io/cafam-propuestas-web/** to browse the current design and all seven alternatives without downloading files or signing in. You can also open `index.html` locally in a browser. All links and assets use relative paths, so the site works under a GitHub Pages project URL.

## Contents

- `index.html`: proposal gallery and responsive preview.
- `actual/index.html`: public rendered snapshots of the current design and its main public views. These are static HTML/CSS/images, with standalone preview interactions; no private application source or backend is included.
- `propuesta-1.html` through `propuesta-7.html`: interactive concepts.
- `styles.css`, `app.js`, `assets/`: styles, interactions, bundled fonts and images.
- `presentacion-cafam.pdf`: complementary static presentation.

The prototypes include scroll reveals, a brand carousel, hover interactions, sample content dialogs, and reduced-motion support. They are independent of CAFAM's application backend and administrator. Editorial text is illustrative; photography is reused from the existing CAFAM review materials. There are no credentials, environment files, database exports, or application APIs in this repository.

## GitHub Pages

Publish the `main` branch from the repository root. `.nojekyll` enables direct static-file publishing; no package installation or build is required.

The current-design reference is a visual snapshot, not a deployment of the private application. Sending enquiries, private administration, live data updates and server-backed operations remain disconnected. Public images and fonts are bundled locally. The comparison page contains no recommendation block.
