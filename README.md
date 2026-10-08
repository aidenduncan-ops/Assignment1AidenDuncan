# Assignment1AidenDuncan

## Web and Script Programming Assignment

The main goal of the website is to give a brief introduction of myself while using my knowledge thus far of web and script programming to convey this online.

I used elements of both fluid and responsive design throughout the webpage, leveraging each feature to convey my true vision for the site.

## Navigation

For my navigation page, I chose to use a relatively unintrusive navigation bar in order to switch between each webpage. On each separate webpage I included the navigation bar with near identical formatting sitting on the left side of the page.

The navigation bar contains four sections: Main Page, Contact Me, Past Projects, and About Me. I used CSS to give the navigation buttons a consistent burgundy color and added a hover effect that changes their color when the user moves their mouse over them.

## Page Design and CSS

I chose a simple color scheme consisting mainly of white, burgundy, and dark red. I wanted the website to have a clean appearance while still having enough color to distinguish important elements such as headings, navigation buttons, and the footer.

Most of the general styling is contained in `style.css`, while `full.css`, `tablet.css`, and `smartphone.css` are used to adjust the layout for different screen sizes. The media queries in the HTML determine which stylesheet is used based on the width of the user's screen.

One of the more important layout choices was using floating elements for the navigation column and some of the images. The navigation column is floated to the left, allowing the main content to occupy the remaining space beside it. Images on the About Me and Projects pages are also floated so that text can wrap around them.

I also used `box-sizing: border-box` on several elements so that padding and borders are included in the defined width. This helps prevent the columns from becoming larger than intended.

The footer is positioned using `position: fixed`, meaning it remains at the bottom of the screen while the user navigates the page. I also used a gradient on the footer to make it visually separate from the rest of the page.

## Main Page

The main page acts as the introduction to my website. I included a brief welcome message introducing myself as a second year student at Ontario Tech University.

I wanted this page to function as a starting point for visitors, giving them a basic understanding of who I am and what the purpose of the website is.

## About Me

The About Me page gives visitors a more personal look into who I am outside of my schoolwork.

I included information about moving from Trinidad & Tobago to Canada to pursue university, as well as my current studies in Networking & IT Security. I also included information about my two dogs, Remy and Santos.

I included a picture of my dogs as well as a video to make the page more visually engaging instead of relying entirely on text.

## Past Projects

The Past Projects page showcases some of the work I have completed throughout my university courses.

The projects cover topics including networking, collaborative leadership, influencer marketing, and consumer behavior. I used images alongside the projects to help visually separate each section and make the page easier to read.

CSS is used to keep the project sections consistent, with the project images floated to the right and the text positioned beside them.

## Contact Me

The Contact Me page contains a simple contact form where visitors can enter their first name, last name, and email address.

I included submit and reset buttons and used CSS to give the form elements a consistent appearance. The form also demonstrates the use of different HTML input types, including text, email, and number inputs.

## Responsive Design

I created separate CSS files for full-sized screens, tablets, and smartphones. This allows the layout to change depending on the user's screen size.

The main stylesheet contains the general styling shared throughout the website, while the additional stylesheets make adjustments for different devices. This was important because elements such as the navigation column, images, and text need to be positioned differently on a smaller screen.

## Overall Goal

Overall, I wanted the website to function as a small personal portfolio that combines information about myself with examples of my academic work.

I tried to keep the website simple and easy to navigate while demonstrating the HTML and CSS concepts I have learned throughout the course. The different pages allow me to show both personal information and examples of my projects, while the responsive design allows the website to remain usable across different screen sizes.