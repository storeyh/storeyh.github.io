# storeyh.github.io

Personal portfolio site — aerospace engineering / rocket propulsion projects.

Live at: https://storeyh.github.io

## Structure

- `index.html` — the whole site (single page)
- `assets/` — images and the downloadable resume PDF

## Updating

Edit `index.html` directly (or ask Claude to), then commit and push (or re-upload
through the GitHub web UI). Changes usually go live within a minute or two.

### Adding photos to a project card

1. Add the image file to `assets/` (e.g. `assets/igniter-1.jpg`).
2. In `index.html`, inside the relevant `<div class="project">`, add a
   `<div class="gallery">` (see the Fuel Flowmeter Flanges card for the pattern)
   containing one `<figure>` per photo:
   ```html
   <div class="gallery">
     <figure>
       <img src="assets/igniter-1.jpg" alt="Describe the photo here">
       <figcaption>Short caption</figcaption>
     </figure>
   </div>
   ```
