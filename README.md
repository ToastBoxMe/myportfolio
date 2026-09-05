# Personal Portfolio Site

A lightweight, single-page portfolio built with HTML, CSS, and JavaScript. The site has no build step and can be deployed directly to a static hosting provider.

> Single-file HTML with local portfolio media.

---

## Deploy to GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html`, `README.md`, `.gitignore`, and the `media/` folder.
3. Open **Settings → Pages**.
4. Set the source to **Deploy from a branch**, select `main`, and choose `/ (root)`.
5. Open the GitHub Pages URL after deployment finishes.

## Local preview

Open `index.html` directly in a browser, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## Editing

The content and styles live in `index.html`. Main sections are clearly commented:

- `<!-- HERO -->`
- `<!-- ABOUT -->`
- `<!-- PROJECTS -->`
- `<!-- SKILLS -->`
- `<!-- EXPERIENCE -->`
- `<!-- LANGUAGES -->`
- `<!-- CONTACT -->`

Local project visuals are stored in `media/`. Update the image `src` paths and descriptive `alt` text when replacing them. Remove account handles, private links, and other identifying information before publishing screenshots.

Before deployment, replace the sample identity, project descriptions, links, and contact details in `index.html` with the site owner's information.

## Optional hosting

The same files can also be deployed through Netlify, Vercel, or Cloudflare Pages.
