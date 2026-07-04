# Personal website

Single-page portfolio site — plain HTML/CSS/JS, no build step.

## Files

- `index.html` — all the content. Search for `EDIT:` comments to find the spots
  that still need your input (bio wording, resume PDF, GitHub/LinkedIn links).
- `style.css` — all styling. Colors live in the `:root` variables at the top;
  the teal accent (`#2A8E96`) matches the hydromod figure palette.
- `main.js` — mobile nav toggle and footer year. Nothing else.
- `assets/` — put `resume.pdf` here (the nav Resume button points at it),
  plus any project screenshots you add later.

## Preview locally

Just open `index.html` in a browser — no server needed.

## Deploy free on GitHub Pages

1. Create a repo on GitHub (e.g. `tanner-site` — or name it
   `<username>.github.io` to get the root URL).
2. From this folder:
   ```
   git add .
   git commit -m "Initial site"
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source: Deploy from a branch → main / (root)**.
4. Site appears at `https://<username>.github.io/<repo>/` in a minute or two.

Every future `git push` republishes automatically.
