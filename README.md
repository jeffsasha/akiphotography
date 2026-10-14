# Sasha 秋鸽 — Photography Portfolio

[![Live site](https://img.shields.io/badge/Live-GitHub_Pages-2563eb?style=flat-square)](https://jeffsasha.github.io/akiphotography/)

Portfolio site for Sasha Qiu, portrait photographer & director based in Moscow.

🌐 **[View the portfolio →](https://jeffsasha.github.io/akiphotography/)**

![Portfolio hero](images/hero_bg.jpg)

Pure static site: hand-written HTML + CSS, no frameworks, no build step.

## Structure

- `index.html` — hero, portfolio grid, about, contact
- `style.css` — all styling and animations
- `images/` — portfolio photos and hero background

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Notes for contributors

- Portfolio images are large originals committed directly to git. For a slimmer clone, consider compressing to web-sized WebP/JPEG or tracking `images/` with Git LFS.
- `.DS_Store` / `.idea` are git-ignored going forward; untrack any still in the index with `git rm -r --cached`.
