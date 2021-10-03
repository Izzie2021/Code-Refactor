# CodeRefactor
This project mimicks a real life user story for a marketing agency.  The goal of this project is to take an existing marketing web page and make sure it meets accessbility standards and uses best practices for css and html. 

## User Story
> AS A marketing agency\
> I WANT a codebase that follows accessibility standards\
> SO THAT our own site is optimized for search engines\

## Acceptance Criteria
> GIVEN a webpage meets accessibility standards\
> WHEN I view the source code\
> THEN I find semantic HTML elements\
> WHEN I view the structure of the HTML elements\
> THEN I find that the elements follow a logical structure independent of styling and positioning\
> WHEN I view the image elements\
> THEN I find accessible alt attributes\
> WHEN I view the heading attributes\
> THEN they fall in sequential order\
> WHEN I view the title element\
> THEN I find a concise, descriptive title

---

To meet the acceptance criteria, I changed the following:
-  Replace div tags with semantic tags
-  Added id to fix navigation link
-  Added alt attributes to images
-  Replaced h2 tag in footer with h4 to maintain proper header structure
-  Replaced div with semantic nav tag
-  Refactored & consalidated css
-  Made sure that overall it had a logical structure independent of styling and positioning

[Link to deployed application](https://izzie2021.github.io/Code-Refactor/)