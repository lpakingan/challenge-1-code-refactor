# Bootcamp Challenge #1: Code Refractor

## Summary of the Challenge

In this week's challenge, we were given the HTML and CSS file for a website of a marketing agency. The main tasks were:
1. To make the website more accessible
2. To organize the semantic elements of the HTML file
3. To consolidate the CSS file to make it more efficient 
4. To debug any lingering issues

## Acceptance Criteria
```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Strategy

#### HTML

In order to make the website more accessible, the **alt** attribute was used in order to add an alternate description for the images on the website. This allows for the alternate description to be shown in the event that the image cannot be shown, and assists with accesibility by being able to be read using a screen reader. 

The initial code lacked the semantic elements of **header**, **nav**, **section**, and **footer**. These were all added to increase the organization of the structure of the file. 

It was noticed that one of the links in the nav bar (Search Engine Optimization) was not redirecting to the respective section on the webpage. This was due to the respective id not being included. Upon adding the id to the content section, the link worked.

#### CSS

The CSS file was reorganized to follow the logical order of elements in the HTML file. There were also a lot of redundant selectors pertaining to elements with the same stylistic parameters. This was fixed by consolidating the redundant selectors into one main selector (i.e the consolidation of all 3 img parameters into 1 by using the class as the main selector instead of each unique element). 

The CSS file was commented on to explain which parts of the webpage each selector was influencing.

## Deployed Application
The final deployed webpage can be found [here](https://lpakingan.github.io/challenge-1-code-refractor/).
