Glacial Landing Page Based on King LASIK Landing Page.

**Project Maintainer** - Anthony

**TRELLO** - https://trello.com/b/i9aKwuxB/landing-page-templating

# Generic Landing Page

## Project Goals
 - To create a sustainable, modular landing page system That can be used to create landing pages.
## Short term goals
  - Make markup generic, document build process.
## Gulp command options
  - gulp concat - concatenates all css files in src/css directory. outputs to dist/css
  - gulp concat-scripts - concatenates all js files in src/js directory. outputs to dist/js
  - gulp imagemin - runs/minifies all images in src/images directory. outputs to dist/images
  - gulp critical - minifies and puts critcal css into head of index.html. outputs to dist/index.html
  - [ ] TODO: Make gulp default run all these commands.
  - [ ] TODO: Make gulp watch run all these commands on file change.
  - [ ] TODO: implement gulp-sass

# Instructions
1. Using Gulp With this project.
  - a. install Node.js if not installed.
  - b. install node-sass globally through npm
  - c. install Gulp globally through npm.
  - d. download project files.
  - e. run gulp through the node.js command line. refer to gulp commands above.
2. Structure
  - css/ - base directory
  - css/partials - partials
