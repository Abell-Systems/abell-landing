# Abell Systems Landing

The public web presence of **Abell Systems**, the team behind [**Abell Nexus**](https://github.com/Abell-Systems/nexus): a working prototype that connects real technology demands with Spanish patents and utility models, with every result linked to its public source.

- **Live URL:** [https://abell-systems.github.io/abell-landing/](https://abell-systems.github.io/abell-landing/)
- **Organization:** [https://github.com/Abell-Systems](https://github.com/Abell-Systems)

## Features
- **Zero-Dependency Delivery**: Ultra-lightweight, high-performance static HTML/CSS with dark tech aesthetics and typography.
- **Presents the current product**: Abell Nexus, with an unretouched real example, what the prototype does today and what is not claimed yet. Figures on the page come from the Nexus repository's README and must be updated when the corpus changes.
- **Mixed language by design**: the product section is in Spanish (`lang="es"`); brand, origin and team are in English.
- **Automated CI/CD**: Pushes to `main` automatically verify and deploy via GitHub Actions to GitHub Pages.
- **Governed by CIRCLE**: Evolution and operational decisions tracked under [.circle/](.circle/).

## Local Preview
Simply open `index.html` in any browser or run:
```bash
python3 -m http.server 8000
```
