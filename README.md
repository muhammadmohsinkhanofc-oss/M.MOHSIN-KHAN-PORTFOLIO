# MOHSIN KHAN® × MAD DESIGNS™ — Portfolio

Single-file portfolio site (`index.html`). Images and videos are embedded, so there is nothing else to upload.
Only external requests: Three.js (cdnjs) and Google Fonts.

## Publish on GitHub Pages
1. Create a new **public** repo on github.com (e.g. `mohsinkhan-portfolio`).
2. Upload everything in this folder (`index.html`, `README.md`, `.gitignore`, `.nojekyll`) with **Add file → Upload files**, then **Commit**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)**, then **Save**.
4. After about a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

Command line instead:
```bash
git init && git add . && git commit -m "Launch portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Edit content
Open `index.html` and search for `CONFIG` near the bottom: email, Instagram and WhatsApp links live there.
Page text (about, captions, toolkit) is plain HTML higher up. Search for the words you want to change.

## Notes
- WhatsApp number is published in the contact section (remove the WhatsApp line in `CONFIG` + `#soc` to hide it).
- Instagram link is `instagram.com/maddesigns.studio` — correct it in `CONFIG` if wrong.
- Custom domain: Settings → Pages → Custom domain.
