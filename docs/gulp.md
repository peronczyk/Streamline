# Gulp

## Installation

Instal required npm packages:
```bash
$ npm install
```

Than you can generate dist files by entering:
```bash
$ gulp
```
or any other gulp command from "Gulp commands" section.

## Commands

* `gulp clean-dist` - Removes all content from 'dist' directory.
* `gulp css` - Compiles all SASS files from 'assets' and moves results to 'dist'.
* `gulp js` - Uglifies and concatenates all JS files from 'assets' and moves results to 'dist'.
* `gulp images` - Copies all images from 'assets' to 'dist'.
* `gulp fonts` - Copies all fonts from 'assets' to 'dist'.
* `gulp watch` - Enters watch mode. Monitors changes in JS, CSS, Images and Fonts assets.
* `gulp serve` - Enters watch mode and starts simple server that serves same browser experience on different browsers through generated URL.
* `gulp default` - Runs tasks: clean-dist, js, css, images, fonts.