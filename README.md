# Sopaan Practice Series — Brain & Mind Academy

Interactive practice sheets. Plain HTML: no build step, no server.

## Structure
- `index.html`: home page listing every sheet
- `sheets/*.html`: one self-contained file per sheet

## Publish on GitHub Pages
1. Push this folder to a repository (the files go at the repository root).
2. Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save.
3. The site appears at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Add a new sheet
1. Put the new file in `sheets/` (e.g. `sheets/polynomials.html`).
2. Add a card for it in `index.html` (copy an existing `<a class="card">` block).

## Student sign-in and progress
Accounts and progress are saved in the student's own browser (localStorage), so they carry over only on the same device and browser. Every sheet on the same GitHub Pages site shares one sign-in. Clearing browser data erases progress.

## Content credit
`sheets/multi-variable.html` uses problems © Paul Dawkins, Paul's Online Math Notes, Lamar University (tutorial.math.lamar.edu). Their terms require the author's written consent before the content is placed on another website, so get that permission before making this repository public.
