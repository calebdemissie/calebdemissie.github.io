# calebdemissie.github.io

Engineering portfolio of Caleb Demissie. Live at https://calebdemissie.github.io

Plain HTML/CSS, no build step. Open `index.html` in a browser to preview.

## Images and video

All media lives in `assets/img/`, extracted from the Google Doc export. The two animations were converted from GIF to MP4 (about 45 MB down to 0.7 MB) and play like GIFs: autoplay, loop, muted.

To swap an image, replace the file with one of the same name.

## Publishing (GitHub Pages)

1. On GitHub, create a **public** repo named exactly `calebdemissie.github.io` (no README).
2. In this folder:
   ```
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/calebdemissie/calebdemissie.github.io.git
   git push -u origin main
   ```
3. Repo → Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute or two the site is live at https://calebdemissie.github.io
