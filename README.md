# Portfolio - Hosting Instructions

This repository contains a static portfolio site (HTML/CSS/JS). Below are quick, safe ways to host it.

Options

- **GitHub Pages (recommended if you use GitHub)**: automatic with GitHub Actions.
- **Netlify / Vercel**: easy drag-and-drop or connect your GitHub repo.

Quick steps (GitHub Pages)

1. Initialize a git repo locally (if you haven't):

```powershell
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

2. Push to GitHub. The included GitHub Actions workflow will build and publish your site to GitHub Pages automatically on push to `main`.

3. After the workflow runs (Actions → your workflow), your site will be available at `https://<your-username>.github.io/<repo>/`.

If you prefer Netlify

- Drag-and-drop the project folder at https://app.netlify.com/drop
- Or connect the repository and set the build directory to `/` (no build command for static sites).

If you prefer Vercel

- Import the GitHub repo at https://vercel.com/new and deploy (no build step required for static sites).

Notes

- Replace `https://github.com/<your-username>/<repo>.git` with your actual repo URL.
- If your site uses a build step (e.g., bundler), update the workflow to run the build and publish the output folder (usually `dist` or `build`).

If you want, I can:

- Initialize a local git repo and create an initial commit for you.
- Create the remote GitHub repo (I cannot do this without your credentials).
- Add a custom domain guide and HTTPS setup.

Tell me which option you want (GitHub Pages / Netlify / Vercel) and I will continue.
