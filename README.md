# Novel Bot + Loophole Robot (standalone)

Self-contained static app - no build step. Just serve `index.html`.

## Run locally

```bash
npm run preview
```

## Deploy to GitHub Pages

1. Push this folder to a GitHub repo.
2. Settings -> Pages -> Source: GitHub Actions (workflow in `.github/workflows/pages.yml` already does this).
3. Open the Pages URL, fill **AI Settings** (any OpenAI-compatible base URL + key + model).

Your API key stays in the browser (localStorage) - never committed.
