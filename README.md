# Bootstrap 4 boilerplate with sass and gulp 4
A Bootstrap 4.3.1 boilerplate with font-awesome, sass, gulp 4 tasks, browserSync (with hot-reloading). You can override bootstrap sass variables by placing those variables in `bootstrap-4-sass-gulp-4-starter/assets/scss/_bootstrap_variable_overrides.scss`

## Pre-requisite
- [Node.js](https://nodejs.org/en/download/ "Node Js")
-  NPM (Comes with Node.js)
- [Gulp 4](https://gulpjs.com/ "Gulp")

Install Gulp cli

     $ npm install --global gulp-cli
     

## Installing:

1. Clone repository:
`git clone https://github.com/jschibelli/bootstrap-4-sass-gulp-4-starter.git`

2. Change directory:
`cd bootstrap-4-sass-gulp-4-starter`
    
3. `cd` into the starter boilerplate folder and run `npm install` in your terminal -  this command installs packages listed in the package.json file and any packages that it depends on. Packages are installed in the "node_modules" directory. a. Please do not modifiy anything in the "node_modules" directory Note: the "node_modules" directory is not kept in source control.

4.	To start your project, make sure you are in the Pattern Library folder and run ` gulp `  to start the “default” gulp task and bring up the local BrowserSync server. This step will also create the dist folder for you, run the Gulp tasks specified in the gulpfile.js file, and watch for file changes. When changes are ready to be comiited, stop the default gulp task, and commit to source control. 

5.	Your finished static mini site will be created in a folder called dist, viewable at this URL:
http://localhost:3000 

## Gulp Tasks:
  - `gulp`      - To compile scss to css, minify css and js and build ready for production files in **dist** folder.

  - `gulp dev`  - Starts a local server with browserSync and hot reloading on changes to files (HTML, SCSS, JS).

  - `gulp build` - Creates a compressed, production-ready assets. This will delete everything in the dist folder and recreate all of your complied files. Never make updates directly into the dist folder as these files get overridden each time. Note: The dist folder is not kept in source control.
