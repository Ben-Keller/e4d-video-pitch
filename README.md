# Light Through Concrete

Storyboard pitch and voiceover script for a 2-minute projection-mapped film on UNDP's
Sustainable Energy for Development offer, narrated by Riad Meddeb.

Static site — `index.html` plus the eight storyboard frames in `frames/`. No build step.

## Publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `e4d-video-pitch`), public or private
   (private repos need GitHub Pro/Team for Pages).
2. Push this folder:

   ```sh
   git remote add origin git@github.com:Ben-Keller/e4d-video-pitch.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   branch `main`, folder `/ (root)`. Save.
4. The site goes live in about a minute at
   `https://Ben-Keller.github.io/e4d-video-pitch/`.

To update, edit `index.html` (or replace a frame in `frames/`) and push.
