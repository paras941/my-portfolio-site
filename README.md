Personal Portfolio Website

This is the complete source code for a responsive, one-page personal portfolio website. It is built with clean HTML, modern CSS, and a touch of JavaScript for a dynamic "typed" effect.

This portfolio is designed to be easily customized and deployed as a static site.

View Live Demo <-- Add your live deployment link here

Features

Fully Responsive: Looks great on all devices, from mobile phones to desktops.

Sticky Navigation: Easy-to-use header that sticks to the top for simple navigation.

Smooth Scrolling: Clicking navigation links scrolls smoothly to the corresponding section.

Dynamic Hero Section: Uses typed.js to animate your job titles or skills.

Multiple Sections: Includes all the essential portfolio sections:

Home: A hero section to introduce yourself.

Projects: A grid of cards to showcase your best work.

Work Experience: A card-based section to detail your skills.

Contact: A functional-looking HTML form for potential employers or clients.

Modern Design: A sleek, dark-mode theme with clean cards and hover effects.

Technologies Used

HTML5: For the core structure and content (semantic tags).

CSS3: For all styling, layout (Flexbox/Grid), and responsiveness (media queries).

CSS Variables: Easily themeable and maintainable (all colors are in :root).

JavaScript (ES6+): Powers the typed.js animation in the hero section.

Typed.js: A popular library for the typing animation.

How to Customize

This portfolio is designed to be a template. You can easily make it your own by following these steps:

Fork this repository.

Clone your forked repository to your local machine.

Open index.html and edit the content directly.

Key Areas to Edit in index.html:

Navigation (Line 13):

Update the links in the <nav> to match your sections.

Hero Section (Line 24):

Change the <h1> and <p> text to your name and bio.

Hero Animation (Line 158):

In the <script> tag at the bottom, change the strings in the strings: [...] array to your desired job titles (e.g., "Full-Stack Engineer", "UI/UX Designer", "Student").

Projects Section (Line 42):

Replace the src attribute for each <img class="project-image" ...> with a path to your own project screenshot (e.g., images/my-project.png).

Update the .project-title, .project-desc, and the href attributes for the "Live Demo" and "GitHub" buttons.

Work Experience Section (Line 80):

Change the .dev-head and .dev-desc text for each "vertical" card to reflect your skills.

Replace the src for <img class="dev-image" ...> with icons for your skills (e.g., images/react-icon.png).

Contact Form (Line 118):

This is a static form. To make it functional, you can use a service like Formspree or Netlify Forms.

How to Change Colors/Theme:

All colors are in one place! Open style.css and edit the variables inside the :root block at the top of the file.

:root {
    --primary-color: rgb(200, 150, 248); /* Accent color */
    --dark-bg: rgb(0, 0, 45);         /* Main background */
    --medium-bg: rgb(3, 3, 104);      /* Navbar background */
    --card-bg: rgb(5, 5, 65);         /* Card background */
    /* ...and so on */
}


License

This project is open-source and available under the MIT License.
