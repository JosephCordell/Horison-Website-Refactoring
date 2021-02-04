# HORISEON Digital Marketing Website Refactoring
This respository contains a project 
Refactoring an existing website to improve the **accessibility**. The tech lead has given a small list of specific criterias to satisfy the project.

## User Story
```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```
## Scope of Work
```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the image elements
THEN I find accessible alt attributes

WHEN I view the heading attributes
THEN they fall in sequential order

WHEN I view the title element
THEN I find a concise, descriptive title
```
## Submission Links

Repository URL: [https://github.com/melissa-tan/Horison-Website_Refactoring](https://github.com/melissa-tan/Horison-Website_Refactoring)

Website URL: [https://melissa-tan.github.io/Horison-Website_Refactoring/](https://melissa-tan.github.io/Horison-Website-Refactoring/)

## Screenshot
The below image shows the website after refactoring.
![Screenshot of website after refactoring](./assets/images/refactored-site-screenshot.png)

## Changes Made
### HTML
Changed the title to Horiseon Digital Marketing
Changed element tags to be semantic 
Changed div tags to header, nav, img, main, section,aside, footer
Removed class for elements with duplicate id and class names 
Added comments to differentiate sections

### CSS
Updated tags to match index.html
Updated the ordering of the selectors to match the sequential order of index.html
Consolidated repeating CSS Rules and CSS Values to a single class selector of the same name
Updated and combined class selectors to id selectors based on updates in index.html
Added comments to differentiate sections