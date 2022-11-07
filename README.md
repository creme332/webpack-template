# 🕸 webpack-project-template
[![Front‑End_Checklist followed](https://img.shields.io/badge/Front‑End_Checklist-followed-brightgreen.svg)](https://github.com/thedaviddias/Front-End-Checklist/)

A template to speed up setting up a project. For more customisations visit https://createapp.dev/webpack/no-library.

[▶ Live Preview](https://creme332.github.io/)

# 🚀Features
- eslint + prettier
- webpack
- babel

#  🛠 Installation

Clone project:
```sh
git clone git@github.com:creme332/webpack-template.git
```

In `package.json`, update project name and description.

Install dependencies:
```sh
npm install
```
To run project in development mode:
```sh
npm start
```

To create a production build:
```sh
npm run build-prod
```

To generate webpack stats:
```
npx webpack --profile --json=compilation-stats.json
```
Use [this website](https://chrisbateman.github.io/webpack-visualizer/) to visualise stats.

# To-do
- [ ] Follow Frontend checklist
- [ ] Use pageInsight to test website after deployment.