# Qixuan Fang — Haider-style academic homepage

This is a static GitHub Pages website. It uses plain HTML and CSS only. No Jekyll, no npm, no build step.

## Files

- `index.html`: About page / homepage.
- `research.html`: Research page.
- `teaching.html`: Teaching page.
- `seminars.html`: Seminars page.
- `life.html`: Other / non-academic interests.
- `contact.html`: Contact page.
- `style.css`: All fonts, colors, layout, navigation, responsive behavior.
- `.nojekyll`: Tells GitHub Pages not to process the site with Jekyll.
- `404.html`: Custom not-found page.

## How to preview locally

Double-click `index.html`, or run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How to publish on GitHub Pages

1. Create a repository named `<your-github-username>.github.io`.
2. Upload all files in this folder to the root of the repository.
3. Go to Settings → Pages.
4. Choose Deploy from a branch → main → /root.
5. Save.

Your site will appear at:

```text
https://<your-github-username>.github.io
```

## Where to edit style

In `style.css`, the Touseef-inspired constants are near the top:

```css
--text: #393939;
--muted: #727272;
--link: #267CB9;
--nav-blue: #1479a9;
--nav-hover: #CCD9E2;
```

The font is:

```css
font: 14px/1.5 "Poppins", "Helvetica Neue", Helvetica, Arial, sans-serif;
```
