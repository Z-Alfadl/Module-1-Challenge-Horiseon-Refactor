# Module 1 Challenge: Code Refactor

The Module 1 challenge is to refactor the provided starter code for a webpage to make it more accessible.

## Overview
The following changes were made in the refactoring process:
### HTML
* Descriptive title added to `<head>`.
* Header:
    1. Changed outer `<div>` to `<header>` as it contains the company name and nav links
    2. Changed inner `<div>` to `<nav>` to properly represent that child elements were navigation links.
* Main:
   1. Changed outermost `<div>` to ``<main>``, as that is the part of the page holding the primary content of the page.
   2. Added descriptive alt texts for images.
   3. Corrected an incorrect class/id assignation in the "Search Engine Optimization" `<div>`.
   4. Consolidated the three `<div>` under one class name as the relevant CSS is identical.
   5. Changed the benefits `<div>` to `<aside>` because it, while relevant information, is of secondary importance.
* Footer:
    1. Changed `<div>` to `<footer>` as it is a footer.

### CSS
* Reorganized CSS file to follow a more logical structure (general styling and font selectors first, then header, main and footer as they are structured in the HTML.)
* Added clear labels to beginning and end of each section.
* Removed or replaced redundant selectors.