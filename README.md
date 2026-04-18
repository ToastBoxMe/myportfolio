# Glenn Marten — Portfolio

Personal portfolio site for **Glenn Marten (鍾岷錥)** — Computer Science graduate, n8n automation developer, Mandarin-certified (TOCFL B1, NTNU). Based in Jakarta.

> Single-file HTML. All assets (photo + screenshots) embedded as base64. No build step.

---

## Deploy to GitHub Pages (free hosting)

1. **Create a new GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it `glenn-marten.github.io` (if you want it at your root URL) **or** any repo name (it'll live at `username.github.io/reponame/`)
   - Set it to **Public**
   - Do not initialize with a README (we already have one)

2. **Upload the files**
   - On the empty repo page, click **"uploading an existing file"**
   - Drag `index.html`, `README.md`, and `.gitignore` in
   - Commit directly to `main`

3. **Enable GitHub Pages**
   - Go to repo **Settings → Pages**
   - Under "Build and deployment", set Source to **Deploy from a branch**
   - Branch: `main` · Folder: `/ (root)` · Save
   - Wait 1–2 minutes for first deploy

4. **Visit your site**
   - `https://<username>.github.io/` (if repo is `<username>.github.io`)
   - `https://<username>.github.io/<reponame>/` (any other repo name)

## Alternative deploys (also free)

| Host        | How                                                        | URL pattern                |
|-------------|------------------------------------------------------------|----------------------------|
| Netlify     | Drag the folder to [app.netlify.com/drop](https://app.netlify.com/drop) | `xxx.netlify.app`          |
| Vercel      | `npx vercel` inside the folder                             | `xxx.vercel.app`           |
| Cloudflare  | Connect the GitHub repo at [pages.cloudflare.com](https://pages.cloudflare.com) | `xxx.pages.dev`            |

---

## Local preview

Just double-click `index.html` to open in a browser. Or serve it:

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

---

## Editing

All content and styles live in a single `index.html` file. Sections are clearly commented:

- `<!-- HERO -->`
- `<!-- ABOUT -->`
- `<!-- PROJECTS -->` — contains Monita, Trixie, and Invoice Automation
- `<!-- SKILLS -->`
- `<!-- EXPERIENCE -->`
- `<!-- LANGUAGES -->`
- `<!-- CONTACT -->`

Images are embedded as `data:image/jpeg;base64,...` inline. To replace an image, encode the new file and swap the base64 string.

---

## Contact

- Email · martenglenn@gmail.com
- LinkedIn · [linkedin.com/in/glenn-marten](https://linkedin.com/in/glenn-marten)
- Phone · +62 813-1657-9309
