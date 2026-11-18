# Majecki Ele – portfolio

Horizontal-scroll portfolio (desktop) / vertical layout (mobile). Plain HTML/CSS/JS, no build step.

## Deploy on GitHub Pages
1. Push `index.html` + the `images/` folder to a repo (root).
2. Repo → Settings → Pages → Branch `main`, folder `/ (root)` → Save.
3. Custom domain (Namecheap): add your domain under Settings → Pages → Custom domain.

## Images
- `bg-01.jpg … bg-13.jpg`  = the PDF's background layers (colours, gradients, blurred photos, with their transparency). Replace a tile with the same name to change a background.
- `concert-N, fete-N, portrait-N, poster-N, talk-N, personal-N` = the photos (these open in the enlarged viewer).
- `menu.png` = the menu design (6 clickable thumbnails).
- `logo-N` = logos (clickable, see below). `contact-illustration` = last-page illustration.
Overwrite a file keeping the same name/extension and aspect ratio.

## Logo links
Each logo is an `<a class="ph lg" href="…">` in `index.html`. Red Bull Music and Botanique are drawn inside the background layer, so their links are invisible `<a class="lgov">` boxes (search `lgov`).
`logo-9` (R symbol) and `logo-10` (SIVIAS) have no link yet.

## Captions / text
Plain text in `index.html` (`<figcaption>` for captions).

## Handy edits
- Menu background colour: `--c:#b8d4b2` on the `<div class="bandc">` near the top of `<div id="canvas">` (the colour inside `menu.png` was recoloured to match, so change both together or ask for a regenerate).
- Bottom navigation bar height: `--bar:54px` in the CSS.
- Credit link: search `oumaima.online` in `index.html`.
