# OS Educational Site

Educational site about Hackintosh, Bootable USB, Ventoy, and Linux Distros.

## Structure
- `index.html`: Hackintosh/OSx86
- `index2.html`: Bootable USB Drive
- `index3.html`: Ventoy Installation Guide
- `index4.html`: Ventoy Overview & Guide
- `index5.html`: Top Linux Distros 2025

## Local Preview

```zsh
npm install
npm start
```

## Deploy to GitHub Pages

1. Initialize git and commit all files:
   ```zsh
   git init
   git add .
   git commit -m "Initial commit"
   ```
2. Create a new repository on GitHub (e.g. `os-educational-site`).
3. Add remote and push:
   ```zsh
   git remote add origin https://github.com/<your-username>/os-educational-site.git
   git branch -M main
   git push -u origin main
   ```
4. Deploy:
   ```zsh
   npm run deploy
   ```

The site will be available at `https://<your-username>.github.io/os-educational-site/`.
