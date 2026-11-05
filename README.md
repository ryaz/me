# dmytro.scrumlaunch.com

One-page personal site of Dmytro Riazanov. Plain static HTML: no build step, no dependencies.

## Edit

Everything is in `index.html`. Placeholders are marked with HTML comments:

- **Photo**: put a square photo (~544×544, JPG or WebP) in the repo root as `photo.jpg`, then replace
  `<div class="photo" ...>DR</div>` with
  `<img class="photo" src="photo.jpg" alt="Dmytro Riazanov" width="272" height="272">`.
- **Case studies**: section "Selected work". Copy a `<a class="card">` block per case study.
- **Email**: `dmytro@scrumlaunch.com` appears in the hero button and the Contact section.

## Hosting

GitHub Pages from `main` (root). Custom domain is set by the `CNAME` file.
DNS (scrumlaunch.com zone): `CNAME  dmytro  ->  ryaz.github.io`
