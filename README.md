# Laura Pacin academic website

A simple Quarto academic website inspired by Louis Sirugue's site structure.

## Files

- `_quarto.yml`: global website configuration and navigation.
- `index.qmd`: home page.
- `research/index.qmd`: research page.
- `teaching/index.qmd`: teaching page.
- `styles.css`: small visual customizations.
- `profile.jpg`: add your profile picture under this exact name.
- `cv.pdf`: add your CV under this exact name.

## Preview locally

Install Quarto, open a terminal in this folder, and run:

```bash
quarto preview
```

## Publish with GitHub Pages

The website renders into the `docs/` folder because `_quarto.yml` contains:

```yaml
project:
  type: website
  output-dir: docs
```

After rendering, commit and push the repository. In GitHub, go to **Settings > Pages**, choose **Deploy from a branch**, select your main branch and the `/docs` folder.

If your repository is `laura-pacin.github.io`, the site will be available at `https://laura-pacin.github.io/`.
