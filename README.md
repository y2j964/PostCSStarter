# PostCSS Starter
A mimimal postcss starter pack.

## Table of contents
* [General info](#general-info)
* [Setup](#setup)

## General Info
This is a simple frontend boilerplate to compile postcss to css. It has one script, which is intended to be run in parallel with something like VSCode's Live Server extension. There is no css minification, as this is not intended to be used in real production environments. You might use this if you wanted a CodePen-esque setup but want to work in a code editor.

## Setup
Simply clone this repo, and run `npm install` to install all dependencies.

### Scripts
Here is our sole script:

#### `npm run css`
Sets up a file watch that compiles postcss into css.