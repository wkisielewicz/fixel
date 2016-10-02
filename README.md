# fixel
---
A css library.

# Get started

# Building

Fixel uses Grunt for the build process which you need to have installed on your system.
Also there are four additional Grunt tasks:
* grunt-contrib-cssmin
* grunt-sass
* grunt-contrib-concat
* grunt-contrib-watch

To install the dependencies, run `npm install`.

Run `grunt` from the project directory. This will run the default grunt task which compiles the SCSS files into fixel.css file.
Though this should be sufficient for building the library for testing.
If you want to build the minified version as well you can run the `grunt deploy` command instead.
