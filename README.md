# Isabel S. Sands — Academic Website

Personal academic website for Isabel S. Sands, MIT Kavli Institute.

## Files

| File | Page |
|---|---|
| `index.html` | About / Biography |
| `research.html` | Research areas and publications |
| `cv.html` | Curriculum vitae |
| `style.css` | Shared stylesheet |
| `cv.pdf` | CV PDF download *(add your own)* |

## Deployment on GitHub Pages

1. Create a repository named `yourusername.github.io` on GitHub.
2. Push all files in this folder to the `main` branch.
3. Go to **Settings → Pages**, set source to `main` branch, root directory.
4. Your site will be live at `https://yourusername.github.io` within a minute.

Or, for a project page under an existing account:

1. Create any public repository (e.g. `academic-site`).
2. Push all files to the `main` branch.
3. Enable Pages from **Settings → Pages** (source: `main`, root).
4. Site will be at `https://yourusername.github.io/academic-site`.

## Customising the content

All placeholder text is in brackets like `[doctoral institution]` or styled in grey.
Things to fill in before publishing:

- **`index.html`**: Email address, GitHub/arXiv links, doctoral institution and bio paragraph.
- **`research.html`**: Paper titles, author lists, arXiv IDs, journal names, and links.
- **`cv.html`**: Education, publications, talks, awards, teaching, service.
- **`cv.pdf`**: Add your CV PDF to this folder so the download button works.

## Adding a profile photo

In `index.html`, replace the `<div class="hero-visual">` SVG with:

```html
<div class="hero-visual">
  <img src="photo.jpg" alt="Isabel S. Sands" style="width:240px;height:240px;object-fit:cover;border-radius:50%;border:1px solid rgba(110,159,218,0.2);">
</div>
```

Then add `photo.jpg` to the site folder.
# isabel.s.sands.github.io
