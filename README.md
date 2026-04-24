# burgern.github.io

Personal site for Nicola Burger.

## Setup

1. Create a new GitHub repo named exactly `burgern.github.io` (public).
2. From this directory:
   ```bash
   git init
   git add .
   git commit -m "initial site"
   git branch -M main
   git remote add origin git@github.com:burgern/burgern.github.io.git
   git push -u origin main
   ```
3. Drop your thesis PDF at `assets/burger_nicola_msc_thesis.pdf`.
4. GitHub Pages activates automatically on user/org sites — visit
   `https://burgern.github.io` within a minute or two.

## Structure

- `index.html` — single-page site, no build step, no framework.
- `assets/` — PDFs and static files.

## Updating

Edit `index.html`, commit, push. Done.
