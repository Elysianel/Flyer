# Flyer — agency blog

Static blog for **Flyer** (*Ideas that land.*). Plain HTML/CSS, no build step.

- `index.html` — home and post list
- `posts/hello-we-are-flyer.html` — agency identity: name, logo, tagline, claim
- `posts/the-pigs-stole-christmas.html` — the Albert pitch slides
- `presentation/` — put the exported deck here as `flyer-albert-christmas-2026.pdf`; the slides post embeds it automatically

## Publishing (GitHub Pages)

Settings → Pages → Source: *Deploy from a branch* → `main`, `/ (root)` → Save.
Live at https://elysianel.github.io/flyer/ a minute or two later.

## Adding the presentation

Export the deck to PDF. On GitHub open `presentation/` → **Add file → Upload files**,
name it `flyer-albert-christmas-2026.pdf`, commit.
