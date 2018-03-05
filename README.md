# Static Shell

This repository contains a static website shell that utlizes Gulp for a task runner. All tasks have been updated to Gulp 4 syntax.

## Default Gulp Task

+ Browser sync reloads the page automatically when a change is saved
+ HTML files are minifed on save
+ Sass files are linted on save, checking for best practices and errors
+ Sass files are compiled to a single minified CSS file after passing the linter task
+ Sass source maps are written and updated on save
+ Vendor prefixes are automatically added on save
+ JavaScript files are minified and concatenated on save to a single JavaScript file

## Required Installs

+ [Ruby](https://www.ruby-lang.org/en/)
+ [Sass](http://sass-lang.com/)
+ [Gulp 4](http://gulpjs.com/)
+ [Node](https://nodejs.org/en/)

# How to Use

Clone the git repository or download the zip file and then run **npm install** in the **gulp** directory to install the required dependencies for Gulp.

## Clone Project

    git clone https://github.com/jacobproffer/static-shell.git

## Install

Run the following command in the project root directory:

    npm install

## Run the default Gulp task

    gulp
