# hahezzang.github.io

Personal introduction page served by GitHub Pages at https://hahezzang.github.io

## Files

- `index.html` — page content. Replace every `[...]` placeholder.
- `style.css` — styles (Google Fonts: Playfair Display, EB Garamond, Caveat, Inter).
- `assets/` — images used by the page (missing images fall back to pink placeholders):
  - `profile.jpg` — ID photo (portrait, about 3:4)
  - `research-1.jpg`, `research-2.jpg`, `research-3.jpg` — research card thumbnails
  - PDFs for the Publications list (update the `href="#"` links in `index.html`)

## Before publishing

- Email: in `index.html`, replace `your-email@example.com` (2 places: the mail icon and the "Contact me" button).
- Photo: upload your ID photo as `assets/profile.jpg` (portrait, about 3:4). Until then a pink placeholder is shown.

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

1. Create a **public** repository named exactly `hahezzang.github.io` on GitHub.
2. Push these files to the `main` branch.
3. Repository → Settings → Pages → Source: "Deploy from a branch", Branch: `main` / `(root)`.
4. After 1–2 minutes the site is live at https://hahezzang.github.io
