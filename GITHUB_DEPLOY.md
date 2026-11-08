# Publish to GitHub Pages

1. Create a GitHub account at https://github.com/signup (if needed).
2. Create a **public** repository named `yuriy-portfolio` (do not initialize it with README).
3. Upload the **contents of this folder**, including `.github/workflows/deploy.yml`, to the repository root. The easiest way to preserve the hidden `.github` folder is to use Git or VS Code Source Control rather than the web upload dialog.
4. In repository **Settings → Pages → Build and deployment**, choose **GitHub Actions**.
5. Open **Actions**, wait for **Deploy portfolio to GitHub Pages** to finish successfully.
6. Visit `https://YOUR_USERNAME.github.io/yuriy-portfolio/`.

If using terminal instead of web upload, from this folder:

```bash
git init
git add .
git commit -m "Launch portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/yuriy-portfolio.git
git push -u origin main
```

The project uses `base: './'` and asset paths that work on GitHub Pages project URLs. Do not upload `node_modules` or `dist`.
