# bootstrap3-sass-theme-dev
Easy Bootstrap 3 (Sass) theme development

### Pre-requisites
1. Install latest version of [Node.js](https://nodejs.org).
2. Upgrade to latest version of npm: `npm upgrade -g npm`
### Install instructions
Note: For file paths, use '\\' on Windows, '/' otherwise. 
1. `git clone` or download this repository and unzip
2. Install gulp globally with command `npm install -g gulp`.
3. `cd` to the directory and issue command `npm install` to install modules listed in `package.json`.
4. Please note that this installs `bootstrap-sass`, `jQuery` and `modernizr` in `node_modules` directory.
### Usage Instructions
1. `cd` to `bootstrap4-sass-theme-dev` and issue command `gulp -s src -f bootstrap.scss -c dist`. This will start a file watcher on Scss directory (`-s`), compile base Scss file (`-f`), and generate the CSS file with the same as Scss file in destination directory (`-c`).
2. Visit `index.html` to see updated results.