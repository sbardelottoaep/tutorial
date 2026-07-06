[README.md](https://github.com/user-attachments/files/29723220/README.md)
# Sbardelotto — Portfolio

Static site. No build step, no framework, no dependencies.

## Files
- `index.html` — the whole site
- `bg.jpg` — hero background image
- `vercel.json` — tells Vercel this is a plain static site

## Deploy on Vercel
1. Put `index.html`, `bg.jpg`, and `vercel.json` in the same folder (repo root).
2. Import the repo on Vercel.
3. When it asks for a framework preset, choose **Other** (or leave default).
4. Leave Build Command empty and Output Directory as `.` (or just root).
5. Deploy.

No `npm install`, no build script needed — it's just static HTML/CSS/JS.
