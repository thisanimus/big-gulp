
# Big Gulp

A task runner for building websites.

[Gulp](https://gulpjs.com/) is a flexible task-runner that is good at watching files and doing things with them when they change.

## Installation
Install the gulp cli

    $ npm i -g gulp-cli

Install the project dependencies

    $ npm i 

## Configuration
Project config is in `/gulp-config.json`. This is where you define where your source files (SCSS, ESM JS, HTML/PHP templates, etc) are, and where you want the processed production-ready files to go.  If you're using a local LAMP environment, you can specify the local server url here to get live-reloading whenever you make a change. 

## Scripts

    $ npm run build

This builds the production-ready files from your source files.

    $ npm run watch

This watches all the files specified in `/gulp-config.json`, and runs the appropriate tasks when changes are detected.  This also opens a browsersync session that live-reloads your site when required to reflect changes you've made to your source files. 