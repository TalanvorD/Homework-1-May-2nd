User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

Acceptance Criteria
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

This is a refactoring code project, taking an existing index.html and style.css and altering it to meet specific criteria. 

Steps taken:
Added alt text and titles to all images
Modified the title to be more relevant
Removed all div tags and renamed into semantic containers i.e. header, nav, main, figure, section, aside, article, footer
Removed nearly all classes from objects
Collapsed css into fewer instructions, mostly moved into element selectors instead of class selectors
Added comments to style.css
