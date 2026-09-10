# André Chadú — Academic Website

Static academic website prepared for GitHub Pages.

## Publish on GitHub Pages

1. Create a repository named exactly `YOUR-USERNAME.github.io`.
2. Upload all files from this folder to the repository root.
3. Commit/push to the `main` branch.
4. In GitHub: **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch** and choose `main` / `(root)`.
6. The website will be available at `https://YOUR-USERNAME.github.io/` after GitHub finishes deployment.

## Replace the profile placeholder

Put a portrait at `assets/profile.jpg`, then replace this block in `index.html`:

```html
<div class="profile-art" aria-label="Profile placeholder"><span>AC</span></div>
```

with:

```html
<img class="profile-art" src="assets/profile.jpg" alt="Portrait of André Chadú">
```

## CV

The CV button in `cv.html` currently points to the public Google Drive version of the CV. If you later prefer to host the PDF directly in the repository, place it at `files/cv-andre-chadu.pdf` and update the button link accordingly.

## Files

- `index.html` — Home
- `research.html` — Research
- `teaching.html` — Teaching
- `cv.html` — CV
- `style.css` — visual style and responsive layout
- `assets/favicon.svg` — browser icon
