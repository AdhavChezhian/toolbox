# tinker.fun

A Neal.fun-style collection of small interactive web toys.

## Apps

- 📡 **Morse Code** — Type anything and hear it tap out in real morse code
- 🌍 **Right Now** *(coming soon)*
- 🗓 **Life in Weeks** *(coming soon)*

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `tinker-fun` or whatever you want the site to be called)
2. Push this folder's contents to the repo:
   ```bash
   git init
   git add .
   git commit -m "initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your repo
4. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`
5. Hit Save — your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Customizing

- **Site name**: Search and replace `tinker.fun` across both HTML files
- **Add a new app**: Duplicate `morse.html`, build your app, then add a card to `index.html`
- **Colors**: The CSS variable `--accent` controls the green accent color throughout
