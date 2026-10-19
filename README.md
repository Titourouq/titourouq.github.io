# Personal academic website — Titouan Rouquayrol

Built with Quarto, hosted on GitHub Pages.

## Before the first render

1. Replace `USERNAME` with your GitHub username in `_quarto.yml` and `index.qmd`.
2. Add your photo as `profile.jpg` (square, at least 400x400 px) at the root.
3. Create a `files/` folder and put your CV in it as `files/CV_Rouquayrol.pdf`.

## Workflow

```bash
quarto preview   # local preview, refreshes on save
quarto render    # builds the site into docs/
git add .
git commit -m "Update site"
git push
```

## GitHub Pages setup (once)

Repository named `USERNAME.github.io` → Settings → Pages →
Source: "Deploy from a branch" → Branch: `main`, folder: `/docs`.
