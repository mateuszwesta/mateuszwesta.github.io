# mateuszwesta.github.io

Personal website, served with GitHub Pages at <https://mateuszwesta.github.io>.

## Structure

- `index.html` — the whole site, one page
- `styles.css` — styling, with light and dark themes via `prefers-color-scheme`

No build step, no dependencies. Open `index.html` in a browser to preview locally.

## Editing

Content lives directly in `index.html`. Sections are marked with `id` attributes
(`about`, `experience`, `education`, `skills`, `publications`, `contact`) and the
header navigation links to them.

## Deploying

Any push to `main` is published automatically.

```
git add -A
git commit -m "Describe the change"
git push
```
