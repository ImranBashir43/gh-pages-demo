# gh-pages-demo



This project demonstrates how to automatically deploy a static website to **GitHub Pages** using **GitHub Actions**.


Every time you push to the `main` branch, a GitHub Actions workflow is triggered. It copies your static files from the `src/` folder, moves them into a `public/` folder, and deploys the contents to the `gh-pages` branch using the [peaceiris/actions-gh-pages](https://github.com/peaceiris/actions-gh-pages) action.



## 🚀 Live Demo

👉 [View Deployed Site](https://ImranBashir43.github.io/gh-pages-demo/)




## 📦 Workflow Features

- Triggers on push to `main`
- Can also be run manually
- Automatically deploys to `gh-pages` branch
- Uses GitHub Actions and `GITHUB_TOKEN` for secure deployment
