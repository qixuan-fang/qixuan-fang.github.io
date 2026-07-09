# Qixuan Fang — Jekyll academic homepage

This is a Jekyll/GitHub Pages academic homepage.

## Important

Do **not** include a `.nojekyll` file in the repository. Jekyll needs to run in order to process layouts, includes, and the automatic footer date.

## How to use on GitHub Pages

1. Delete the old files in your `<username>.github.io` repository, especially `.nojekyll` if it exists.
2. Upload all files from this folder to the root of the repository.
3. Go to `Settings → Pages`.
4. Use `Deploy from a branch`, branch `main`, folder `/root`.
5. Wait a few minutes.

## Local preview

If Ruby and Bundler are installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open:

```text
http://127.0.0.1:4000
```

## Editing

- Main site settings: `_config.yml`
- Navigation: `_data/navigation.yml`
- Shared layout: `_layouts/default.html`
- Header: `_includes/header.html`
- Footer: `_includes/footer.html`
- Style: `assets/css/style.css`
- Pages: `index.md`, `research.md`, `teaching.md`, `seminars.md`, `life.md`, `contact.md`
