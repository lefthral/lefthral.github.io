# Aryan Shinde Portfolio

Static portfolio site prepared for GitHub Pages.

## Local preview

Open `index.html` directly in a browser, or run a temporary local server:

```bash
python3 -m http.server 8080
```

## Publish to GitHub Pages

This folder is set up for the personal GitHub Pages repository:

```bash
cd ~/lefthral.github.io
git init
git add .
git commit -m "Create portfolio site"
gh auth login -h github.com
gh repo create lefthral.github.io --public --source=. --remote=origin --push
```

After the push, the site should be available at:

```text
https://lefthral.github.io
```

If the repository already exists, use:

```bash
git remote add origin https://github.com/lefthral/lefthral.github.io.git
git branch -M main
git push -u origin main
```
