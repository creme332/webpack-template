# 🎭 webpack-template
[![Front‑End_Checklist followed](https://img.shields.io/badge/Front‑End_Checklist-followed-brightgreen.svg)](https://github.com/thedaviddias/Front-End-Checklist/)
![HTML5 shield](https://img.shields.io/badge/-HTML5-blue)
![JavaScript shield](https://img.shields.io/badge/-JavaScript-yellow)
![CSS3 shield](https://img.shields.io/badge/-CSS3-orange)

A webpack template for your vanilla JavaScript projects with automatic deployments on Github Pages.

[▶ Live Preview](https://creme332.github.io/webpack-project-template)

## Features
- ESLint
- Axist minimal CSS library 
- Prettier
- Webpack
- Babel
- Automatic website deployment on Github Pages

## Installation
There are two ways to use this template. In either ways, you must edit the project name and description in `package.json`. 

### Method 1
Click on the `Use this template` option at the top right corner of the Github page.
### Method 2
Clone project:
```sh
git clone git@github.com:creme332/webpack-template.git
```
> 🔴 **Note**: If you are placing this project in another project already having a `.git` folder, delete the `.git` folder in this project to prevent interference.

Install dependencies:
```sh
npm install
```

## Usage

### Local
To run project in development mode:
```sh
npm start
```
Open http://localhost:8080/ in your browser. If everything is working fine, you should see a spinning box.

To create a production build:
```sh
npx webpack
```

To generate webpack stats:
```
npx webpack --profile --json=compilation-stats.json
```
> 🟢 Tip: Use [this website](https://chrisbateman.github.io/webpack-visualizer/) to visualize your webpack statistics.

> 🟢 Note: For more webpack customizations visit https://createapp.dev/webpack/no-library.

### Github pages
Enable Github pages in your repository settings and deploy from the `gh-pages` branch. The site will be live at `https://<username>.github.io/<reponame>/` (ex: `https://creme332.github.io/webpack-template/`);

## To-do
- [ ] Follow Frontend checklist
- [ ] Use pageInsight to test website after deployment.

## Attributions
| Resource                  | Source                                  |
| ------------------------- | --------------------------------------- |
| Drop-in Axist CSS library | https://github.com/ruanmartinelli/axist |