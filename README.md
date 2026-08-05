# Abhishek Ranjan — personal academic website

A static, classic/scholarly site (four pages: Home, Research & Consulting, Teaching, Leisure).
No build step, no dependencies — just HTML + CSS. Fonts load from Google Fonts.

## Files
- `index.html` — Home / bio / appointments
- `research.html` — publications, projects, consulting, seminars
- `teaching.html` — courses + documents
- `leisure.html` — running / marathons
- `style.css` — shared stylesheet

## Publish it on GitHub Pages (free)

**Option A — user site at `yourusername.github.io`**
1. Create a repository named exactly `yourusername.github.io` (use your own GitHub username), set to **Public**.
2. Upload all the files in this folder (Add file → Upload files → drag them in → Commit).
3. Wait ~1 minute, then visit `https://yourusername.github.io`.

**Option B — project site (keeps your username free for something else)**
1. Create any public repo, e.g. `website`.
2. Upload these files and commit.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, branch `main`, folder `/root`, Save.
4. Your site appears at `https://yourusername.github.io/website`.

## Swapping the "AR" monogram for a photo
On the Home page (`index.html`) replace this block:

```html
<div class="avatar" aria-hidden="true">AR</div>
```
with:
```html
<img class="avatar" src="photo.jpg" alt="Abhishek Ranjan" style="object-fit:cover;">
```
and upload a square `photo.jpg` alongside the other files.

## Editing tips
- Change the accent colour once in `style.css` — edit `--accent` near the top.
- All content is plain text inside the `.html` files; edit directly, no tools needed.
