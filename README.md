# UoP
Browser extension script for grading pages adjustment
This Readme offers guidance on the use of the two available scripts
1. Discussion Grading
2. Assignment Grading


# Discussion Grading Panel Adjuster

A Stylus user style that modifies the University of the People Moodle grading interface to provide wider grading panels.

## Features

- Expands the right panel (grading details) from default 450px to 600px
- Expands the left panel (PDF annotation) from default 450px to 600px

## Installation

1. Install the Stylus extension for your browser:
   - Chrome: https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne
   - Firefox: https://addons.mozilla.org/en-US/firefox/addon/stylus/

2. After installing Stylus:
   - Click the Stylus icon in your browser toolbar
   - Select "Manage Styles"
   - Click the "Write new style" button
   - Copy and paste the contents of the Stylus file available here on github
   - Save the style

## Usage

The style will automatically activate when you visit any UoPeople discussion grading page (URLs matching `https://my.uopeople.edu/mod/forum/view.php?*`).

## Customization

To adjust the panel widths:
1. Open the style in Stylus
2. Modify the pixel values in the CSS (currently set to 600px)
3. Save your changes
