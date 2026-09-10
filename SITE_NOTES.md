# Website redesign notes

This version keeps the site deliberately restrained: it presents the research clearly without trying to read like a lab or startup landing page.

## Content changes

- Homepage language is more direct and academic, with a smaller research-focused hero and less promotional phrasing.
- Current position is stated as **PhD candidate at MPI-SWS and Saarland University**, advised by Mariya Toneva and Isabel Valera.
- The former CV page is now **Background** and focuses on current position and education. GPAs have been removed.
- Publications and teaching stay on their own pages instead of being duplicated on the Background page.
- `/cv/` and `/resume` redirect to `/background/` so existing links continue to work.
- Research-page language has been tightened and the Feynman quote / manifesto-like framing removed.

## GitHub Pages compatibility

- `Gemfile` is pinned to `github-pages ~> 232`, the current GitHub Pages dependency bundle checked in September 2026.
- This corresponds to Jekyll 3.10.0 on GitHub Pages.
- Only GitHub Pages-supported Jekyll plugins are enabled (`jekyll-paginate`, `jekyll-sitemap`, `jekyll-gist`, `jekyll-feed`, `jekyll-redirect-from`).
- The unsupported/unnecessary `hawkins` dependency has been removed.
- `webrick` remains only as a local development dependency for `jekyll serve`; it is not registered as a Jekyll plugin.

## Deployment

The repository is intended to work with GitHub Pages' normal Jekyll build from the repository root. The custom domain remains configured through `CNAME`.

A production build was run successfully against the vendored `github-pages` 232 / Jekyll 3.10.0 dependency set on 2026-09-10. The generated homepage, Background page, research/publication/teaching pages, and `/cv/` / `/resume` redirects were checked after the build.
