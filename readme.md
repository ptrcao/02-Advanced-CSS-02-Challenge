# Read Me

> URL: <a href="https://ptrcao.github.io/02-Advanced-CSS-02-Challenge/">https://ptrcao.github.io/02-Advanced-CSS-02-Challenge/</a>

The single-page website displays a job candidate's portfoilo in card grid format along with relevant navigational features, information, and links - in order for a prospective employer to evaluate.  The website uses a desktop-first design, but has built-in responsive features which activate at a breakpoint of 793px.  CSS media queries with a `max-width` were used to manage the responsive aspects.  The HTML code was run through an online validator, which cleared it of all validation errors.

## Screenshot (>793px wide)
<img src="assets/Desktop screenshot from 793px.png">

## Screenshot (=<793px wide)
<img src="assets/Small device screenshot up to 793px.png">

## Acceptance Criteria
> GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them

&#9745; Developer's name

&#9745; Recent photo or avatar

&#9745; Links to sections about the applicant, their work, and how to contact them


> WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section

&#9745; Anchor jumps have been implemented, which target the IDs of the sections.

> WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications

&#9745; "Work" link scrolls to a section with titled images of the developer's applications.

> WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others

&#9745; the first of the cards is CSS grid-configured to be more prominent in size, relative to the 4 smaller cards that follow.

> WHEN I click on the images of the applications
THEN I am taken to that deployed application

&#9745; Since I do not currently have completed projects, I have linked to Google, or `#`, as a placeholder.  These will be updated as the course progresses, and beyond.

> WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport

&#9745; Responsive layout has been implemented at breakpoint of 793px.  Primilarly, the navigation links at the top and the bottom are implicated here, as they become transposed on smaller screens.  The grid of cards is responsive by default.