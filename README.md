# Dongmin Kim

Personal academic website built with [al-folio](https://github.com/alshedivat/al-folio).

Site URL after deployment: https://kmin2426.github.io

## Local preview

```bash
docker compose up
```

Open http://localhost:8080. Content edits reload automatically; restart the service after changing `_config.yml`.
Stop with `Ctrl+C`, or `docker compose down` when running in the background.
The Docker image is pinned by digest for reproducible dependencies.

## Editing

- `_pages/about.md`: biography
- `_projects/*.md`: individual research projects
- `_data/socials.yml`: email, GitHub, LinkedIn, and CV link
- `_config.yml`: name, site URL, and feature settings

No sample publications, stock portrait, blog entries, or third-party biographies are included.

## GitHub Pages

The included workflow builds pull requests and deploys pushes to `main` or `master` to the `gh-pages` branch.
After the first successful deployment, choose **Settings → Pages → Deploy from a branch → gh-pages → /(root)**.
The workflow requires GitHub Actions to be enabled and permission to write repository contents.

## Template provenance

Based on upstream al-folio commit `e0a684cfe16147bf4f3e0ef1ab94a5e2187efabf`.
The upstream MIT license is retained in `LICENSE`. No local overrides of theme layouts or runtime code are used.
