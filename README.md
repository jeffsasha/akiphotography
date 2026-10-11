# Sasha 秋鸽 — Photography Portfolio

Portfolio site for Sasha Qiu, portrait photographer & director based in
Moscow. Pure static site: hand-written HTML + CSS, no frameworks, no build
step.

## Structure

- `index.html` — hero, portfolio grid, about, contact
- `style.css` — all styling and animations
- `images/` — portfolio photos and hero background

## Notes

- Portfolio images are large originals committed directly to git. For a
  slimmer clone, consider compressing to web-sized WebP/JPEG or tracking
  `images/` with Git LFS.
- `.DS_Store` and `.idea/` files still present in git history are covered by
  `.gitignore` going forward; run
  `git rm -r --cached .DS_Store images/.DS_Store .idea` to stop tracking them.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
