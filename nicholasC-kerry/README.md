**Author**: Nicholas C and Kerry N.
**Previous Collaborations** Nicholas and Rob and Fred and Joel Nicholas C and Fred and Ariel and Joel and Kat and Nicholas and Ariel Joel and Kerry. Nicholas and Joel, Kerry and Joy, Kerry and Kat, Kerry and Joel, Kerry and Seth
**Version**: 1.7.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
We are building a blog site to the designer's specifications. We were to mirror a few images of the sample site provided by the customer.

## Getting Started
We were given starter code with the html file completed. You would have to layout a CSS structure in which to build the design.
1. Normalize the CSS in vendor styles folder
1. Add SMACCS style files like base.css, layout.css, modules.css
1. Link them all in the head of the html
1. Set the viewport metatag in html
1. Starting with a topdown approach create the styles for the mobile version of the site
1. Again with a topdown approach, create the styles for the full version of the site
## Day 2
1. Removed all articles from the Dom and used Nicholas and Rob's CSS to style the new page for Nicholas and Fred
1. Completed the `Article()` constructor and created instances by assigning all of the properties of each data object to properties of `this`
1. Completed the `toHtml()` method, which renders each article instance to the DOM
1. Articles are now sorted by date
1. Added the necessary script tag to include jQuery in the app
1. Utilized jQuery functionality to modify the display property of DOM elements
1. Utilized jQuery functionality to traverse the DOM and completed the HTML template for the articles
1. Refactored all `for` loops using the `.forEach()` method
## Day 3
1. Refactored all the concatenation into template literals
1. Created selector menus and functionality for those menus
1. Created tab selectors that hid and showed elements of the dom
## Day 4
1. Refactored the template into handlebar notation.
1. Refactored most of our functions into fat arrow notation.
## Day 6
1. Loaded raw data into localStorage.
1. Created function to write articles from localStorage into DOM.
1. Created header eTag to reference changes with local and "remote" data.
## Day 7
1. Included the Static resources to point express to the public content available to the client
1. Initialized project using npm, creating and populating package.json and package-lock.json
1. Required the expressjs package
1. Refactored a bunch of functions to arrow functions
1. Reviewed new code and commented on their function on their stack trace

## Architecture
We used CSS and modified an html file already given to us. We imported a normalized CSS file from https://github.com/necolas/normalize.css/ 
We use node  via an express library to initialize the server

## Change Log
1. We set up the directories
1. added CSS files
1. Mobile header hover content content content content
1. fixed header
1. Styled main-nav
1. Added style to main and footer
1. added README
### Day 2
### Day 3
1. Added articleView.js
###Day 7
1. Added server- many new files given by vendor/teacher
