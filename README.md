# grunt-sass-bootstrap
Theming Bootstrap using SASS with Grunt and Yarn.



## Installation

1. Clone the repo
2. <i>cd</i> to the folder
3. Run the <i>yarn install</i> command to install the packages (Bootstrap, Bootstrap Sass, Font Awesome, jQuery and Popper.js, grunt packages)
4. Run the <i>grunt copy</i> task to copy Bootstrap and jQuery files to the <i>public/assets/javascript</i>
5. Run grunt to start watching for changes in your files.

## Using

The Sass files are exported in <i>public/assets/stylesheets</i>. If you want to minify the final CSS file run the "grunt cssmin" task.

This Grunt project doesn't minified Javascript you must add an uglify task for that.

You have to copy eventual fonts manually in <i>public/assets/fonts</i> and your custom JS file in <i>public/assets/javascript</i>.

You can copy the Bootstrap and jQuery files in the <i>public/assets/javascript</i> folder running the <i>grunt copy</i> task.
