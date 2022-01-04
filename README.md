# BUILD-TOOLS-BUCHELI-COURSE-WEBPACK-PACKING-MULTIPLE-JAVASCRIPT-FILES

## In order to pack multiple JavaScript files, follow the next steps:

* npm install --save-dev webpack webpack-cli
* npm run build

* Take the following information into consideration:

Take a look at the file structure of our project on the right by clicking on the folder icon. Our src directory has three JavaScript files. greetUser.js and myUser.js provide utility data and functionality to index.js. In a typical static web project, we would have to put all three scripts into our HTML page and include them in the right order. Managing and importing these scripts gets harder as our projects get more complex. Build tools like Webpack help make including resources easier.

Webpack will allow us to use import and export statements on all our front-end files, not just JavaScript. If you need a review of ES6 module syntax, check out the Implementing Modules Using Es6 Syntax article. When we build Webpack stitches all our files together as if we wrote them as one.
