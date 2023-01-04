# 🕸 webpack-project-template
[![Front‑End_Checklist followed](https://img.shields.io/badge/Front‑End_Checklist-followed-brightgreen.svg)](https://github.com/thedaviddias/Front-End-Checklist/)

A template to speed up setting up a web project. For more customisations visit https://createapp.dev/webpack/no-library.

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
>⚠ If you are placing this project in another project already having a `.git` folder, delete the `.git` folder in this project to prevent interference.

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

# Usage
Once everything is installed, you should see a spinning box after typing `npm start`.

# To-do
- [ ] Follow Frontend checklist
- [ ] jest
- [ ] Use pageInsight to test website after deployment.