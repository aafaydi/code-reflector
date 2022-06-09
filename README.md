# Code Refactor Starter Code
01_Code_Refactor_JGR
BootCamp Homework - 01 HTML CSS Git: Code Refactor

The Challenge
To refactor an existing webpage in order to make it accessible, so it is optimized for search engines.

Acceptance criteria for the webpage:

Meets accessibility standards
Applies semantic HTML elements
The elements follow a logical structure independent of styling and positioning
Includes accessible alt attributes in images
Heading attributes fall in sequential order
Includes a concise, descriptive title element
Additional requirements for long term sustainability:

Ensure all links are functioning correctly
Clean up the CSS selectors and properties to make it efficient
Consolidate CSS selectors and properties
Organize CSS selectors and properties to follow the semantic structure of the HTML elements
Include comments before each element or section of the page
The Process
In orther to accomplish the challege, the following steps were done:

Understand clearly the webpage purpose and content
Research sources to understand key concepts
What code refactoring is
Semantic HTML
Web accesibility standards
How to edit Markdown files
Proper use of a README.mb file
Apply above concepts in the revision and editing of the HTML and CSS files

The specific findings and modifications to the HTML file

Structure and descriptive comments were added

<!-- Header -->

<!-- Main content -->

<!-- Additional indirect content -->

<!-- Page footer -->


Changed title to "Business Digital Strategies"

Changed <div>  for <header> tag

Changed <div>  for <nav> tag in HTML, and .header nav CSS rules

Changed to meetingMainImage, and included into the header section.

Added some empty lines for making the HTML sections easier to identify


Added <main> tag to group the main content

Added <footer> tag at the bottom of the page

Changed content class name for mainContent both in the HTML and CSS files

The benefits <div> tag was changed to <aside> tag


Included alt properties with related description for each image

Changed the class search-engine-optimization to id search-engine-optimization

Changed the classes  benefit-lead, benefit-brand and benefit-cost to id benefit-lead, benefit-brand and benefit-cost

Removed the online-reputation-management class and rules in CSS updated to id

Removed the social-media-marketing class and rules in CSS updated to id

The </img> was removed

The specific findings and modifications to the CSS file

Structure and descriptive comments were added to the CSS file, and the css rules were clasified accordingly:

/* ================================= 
 Global rules and element rules
==================================== */


/* ================================= 
 Structural content style
==================================== */

/* ---------- The Header ---------- */

/* ---------- Main content ---------- */

/* ------- Additional content ------- */

/* --------- The Page Footer --------- */


The rules were ordered in terms of specificity to provide clearance in cascading rules application. Element rules first, then class selector rules and finally id selector sules.

I could not find CSS rules that could be deleted or simplified. The rules that were overwritten were mainly from user agen stylesheet and the * universal selector

Rules that were simplified into one rule:

The Output
With the research, application of concepts, and specific changes made to the files, we were able to ensure an accesible, efficient, and easy to read project.

Installation
The project was uploaded to GitHub at the following repository: https://github.com/jorguzman100/01_Code_Refactor_JGR

You can access the deployed application with the GitHup Pages link: https://jorguzman100.github.io/01_Code_Refactor_JGR/

References
Code refactoring

Semantic HTML

Web accessibility standards

Markdown and Visual Studio Code

Make a README

Interactive tutorial