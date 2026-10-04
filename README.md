# ReproRehab Bootcamp: Pod 5 (Advanced)

Curriculum for the Advanced Pod of the [ReproRehab](https://www.reprorehab.usc.edu/) bootcamp, built as a [Quarto](https://quarto.org) website.

## View the site

Once published, the curriculum is available at:

`https://hooymana.github.io/reprorehab-pod5/`

## Build locally

1. Install Quarto: <https://quarto.org/docs/get-started/>
2. From the project folder, preview with live reload:
   ```bash
   quarto preview
   ```
3. Render the static site into `_site/`:
   ```bash
   quarto render
   ```

## Publish to GitHub Pages

```bash
quarto publish gh-pages
```

## Structure

- `_quarto.yml` — site configuration (title, navbar, theme)
- `index.qmd` — the curriculum
- `_site/` — rendered output (git-ignored)
