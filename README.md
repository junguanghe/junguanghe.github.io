# Jason (Junguang) He

A minimal, responsive personal website, published at **https://junguanghe.github.io/**.

## Content

- `index.html` — introduction, experience, education, and contact links.
- `styles.css` — responsive layout and styling; no framework or build step.
- `assets/jason-he-cv.pdf` — downloadable general CV.

The initial content and PDF come from [jhe_cv](https://github.com/junguanghe/jhe_cv), using `markdown/jhe_cv.md` and `markdown/output/pdf/jhe_cv.pdf`. Website copy is curated separately; resume changes are not synced automatically. When updating the CV, replace the PDF here as well.

## Preview locally

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. The site works without JavaScript or third-party services.

## Publish

In **Settings → Pages**, select **Deploy from a branch**, **main**, and **/(root)**. Every push to `main` then updates the site. `.nojekyll` makes GitHub Pages serve the files directly.
