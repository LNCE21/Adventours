# Steps

## Install NPM Node SASS to compile the scss file into css

## On vscode:
. install live sass compiler
. install live server

## On the terminal:

. Run the script  of the package.json file: "compile:sass"

. You can do it like this:
npm run compile:sass

. Now, open the extension Live Sass Compiler 

. Finally, open the extension Live Server

## About the architecture:
. CSS architcture of 7-1 pattern where we create 7 folders and one main SASS file to import all the files in these folders.
Is made to handle large multi-page websites or web apps.

. All these files will be inside the SASS folder
Folders:

### Base: 
Base file: For low level basics (such as resets, styles for the html and body element selectors).
This file should be a partial, so we can import it into the main SASS file.
Partial files start with an underscore

Animations file:
Typography file:
Utilities file:

### Abstracts:
Code that's not going to output any css (variables, mixins etc)