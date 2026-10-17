# otonielrm.github.io

Source for https://otonielrm.github.io, a Quarto website. Every push to `main` is rendered
and deployed by GitHub Actions (`.github/workflows/publish.yml`).

## Local preview (WSL)

```bash
quarto preview      # live-reloading preview in the browser
```

## Adding content

- **Paper summary:** copy `_templates/paper-summary.qmd` → `ledger/YYYY-MM-DD-short-name.qmd`.
- **Blog post:** create `blog/YYYY-MM-DD-slug/index.qmd` (images go in the same folder).
- **Project:** add a row to `projects.qmd`.
