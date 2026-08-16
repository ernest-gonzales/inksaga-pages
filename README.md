# InkSaga Pages

Public GitHub Pages deployment repository for InkSaga.

The website is built from the private sibling `inksaga-web` repository and published locally with:

```bash
npm run publish:pages
```

That command verifies and builds `inksaga-web` with the `/inksaga-pages` base path, replaces the generated files in this repository, commits them, and pushes `main`. A push to `main` triggers `.github/workflows/pages.yml`, which deploys the checked-in static site to GitHub Pages.

No EPUB source text, private chapter evidence, or provenance payloads are published here.
