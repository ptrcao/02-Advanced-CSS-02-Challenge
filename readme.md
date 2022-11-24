# Read me

The single-page website displays a job candidate's portfoilo in linked card format along with relevant navigational features, information and links, in order for a prospective employer evaluate.  The website uses a desktop-first design, but has built-in responsive features which activate at a breakpoint of 793px.  CSS media queries with a max-width were used to manage the responsive aspects.  The HTML code was run through an online validator, which cleared it of all validation errors.

## Screenshot (=<793px wide)
<img src="assets/Small device screenshot up to 793px.png">

## Screenshot (>793px wide)
<img src="assets/Desktop screenshot from 793px.png">

## Acceptance Criteria
> GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them

&#9745; Developer's name

&#9745; Recent photo or avatar

&#9745; Links to sections about the applicant, their work, and how to contact them


> WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section

Anchor jumps have been implemented, which relate to IDs.

> WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications

> WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others

> WHEN I click on the images of the applications
THEN I am taken to that deployed application

> WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport