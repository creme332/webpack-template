# 🕸 webpack-project-template
[![Front‑End_Checklist followed](https://img.shields.io/badge/Front‑End_Checklist-followed-brightgreen.svg)](https://github.com/thedaviddias/Front-End-Checklist/)

A template to speed up setting up a project.

[▶ Live Preview](https://creme332.github.io/)

# 🚀Features
- eslint + prettier
- webpack
- babel

#  🛠 Installation
Set project name and description in `package.json`.

Install dependencies:
```
npm install
```
Run project in development mode:
```
npm start
```

# Before deploying to production
Set `mode: 'production'` in `webpack.config.js`.

Generate final version of code:
```
npx webpack --watch
```

Generate webpack stats:
```
npx webpack --profile --json=compilation-stats.json
```
Use [this website](https://chrisbateman.github.io/webpack-visualizer/) to visualise stats.
# To-do
