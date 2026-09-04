# Memoona Amir — Content Writing & Copywriting Portfolio

A single-page portfolio site. Open `index.html` in a browser to preview it.

## Push this to GitHub and go live (GitHub Pages)

1. Create a new repository on GitHub (e.g. `memoona-portfolio`) — don't add a README when prompted, since one is included here.
2. On your computer, unzip this folder, then open a terminal inside it and run:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/memoona-portfolio.git
   git push -u origin main
   ```
3. On GitHub, go to your repo → **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. Wait a minute, then your site will be live at:
   `https://YOUR-USERNAME.github.io/memoona-portfolio/`

## Editing later
- All text and links live in `index.html`.
- Your photo is `assets/memoona-portrait.png` — swap in a new file with the same name to replace it.
- Colors are set once at the top of the `<style>` block under `:root` — change `--ember` or `--champagne` there to restyle the whole site.
