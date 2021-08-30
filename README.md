# Adventours Landing Page

## This website is on working progress, if you have any doubts or suggestions, reach me on my socials.

## Steps

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
Files:
Variables
Mixins
Functions

### Components: Building blocks
Components are our reusable building blocks that make our website/app. They can be completly independent.
So, we create 1 file for each of our components.

### Layout: Layout holds these components
The components are held together by the layout of the page, so we need a layout folder for each piece of the global layout of the entire project.
Inside, we're going to have a global footer, header, etc.
These layout elements should work everywhere and on all pages. 

### Pages: Specific style for specific page
Specific style for specific page (example: home) goes into a file in the pages folder.

### Themes: For storing different themes
In case that we are doing a web app with different themes.

### Vendors: Third party css
This folder is for third party css. For example: css file of a bootstrap. Or an icon, an animation etc