# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- Deploy to GitHub Pages Use these commands to manually push your dist folder to the gh-pages branch:

bash
Copy code
cd dist
git init
git add .
git commit -m "Deploy to GitHub Pages"
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git
git push -f origin main:gh-pages