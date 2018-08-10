# JS13K Starter

This repository allow you to quick start your JS13K project to develop, compile, minify and zip you JS13K project.

Uses adfab-gulp-boilerplate to compile sass or less, concat you JS, minify your assets...with additional tasks to zip and improve minification

## Installing

Run `npm install` in the project directory to install all needed packages.

## Gulp commands

`gulp` to compile your files

`gulp watch` to compile your files and watch for file updates to compile again

`gulp serve` will host the game on your vhost set in gulp-config.json

`gulp --production` builds the production version of the project (minified, no sourcemap...).

`gulp zip` creates the zip file for competition and concatenates css/js in a single html file to add more optimisation

## Generate you final game

run `gulp --production && gulp zip`

Your game.zip file will be generated in `/dist` folder.

## Update path and config

You can update path and other config in `gulp-config.json` file.