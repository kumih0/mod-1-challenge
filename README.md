# Module 1 Challenge

# Refactoring Website for Horiseon 

# User Story


    AS A marketing agency
    I WANT a codebase that follows accessibility standards
    SO THAT our own site is optimized for search engines


# Acceptance Criteria

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


# Refactoring Code

    I removed div tags and replaced with appropriate HTML semantic tags to improve accessibility functions of the website.  
    The CSS styles in the stylesheet have updated selectors to match their respective HTML tag while retaining the legacy code style.  
    Superfluous class and id tags were deleted from the HTML file and class properties in CSS file have been simplified and consolidated. 
    Necessary images have alt descriptions to improve accessibility for screen readers.
    Further consolidation and trimming of redundant code following DRY coding practices.

# Screenshot
![Screenshot of Mock-Up Website] (assets/images/01-html-css-git-homework-demo.png)

# Live Link
https://kumih0.github.io/mod-1-refactoring-website/
