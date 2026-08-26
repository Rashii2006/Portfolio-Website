# Rashmika Silva — Portfolio Site

Everything needed to deploy this site is in this folder:

```
index.html            → the site itself (self-contained: all CSS/JS is inline)
site.webmanifest       → home-screen / PWA icon metadata
icons/                 → favicon set (all sizes, referenced by index.html)
```

## Deploy to GitHub Pages (Rashii2006.github.io)

1. Create a new repository on GitHub named exactly **Rashii2006.github.io**
   (must match your username, all lowercase is fine too — GitHub is
   case-insensitive here). Leave it public, and don't add a README when
   creating it.
2. On the empty repo page, click **"uploading an existing file"**.
3. Drag in **all the contents of this folder** — `index.html`,
   `site.webmanifest`, and the whole `icons/` folder — keeping the same
   folder structure (the `icons` folder must stay named `icons` and sit
   next to `index.html`, not inside it differently).
4. Scroll down, leave "Commit directly to the master branch" selected,
   and click **Commit changes**.
5. Wait 1–2 minutes for GitHub Pages to build (you can watch progress
   under the repo's **Actions** tab).
6. Visit **https://rashii2006.github.io** — that's it, no settings to
   toggle, since `username.github.io` repos publish automatically.

To update the site later, just re-upload `index.html` (or any changed
file) the same way — GitHub will ask if you want to replace the
existing version.
