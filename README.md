Frontend Mentor - Blog Preview Card Solution
https://preview.jpg

This is my solution to the Blog Preview Card challenge on Frontend Mentor.

Table of Contents
Overview

The Challenge

Screenshot

Links

My Process

Built With

What I Learned

Continued Development

Author

Overview
The Challenge
Users should be able to:

View the optimal layout depending on their device's screen size

See hover states for interactive elements

Screenshot
https://./screenshot.png

Links
Solution URL: GitHub Repository

Live Site URL: Live Demo

My Process
Built With
Semantic HTML5 markup

CSS custom properties

Flexbox

Mobile-first workflow

Google Fonts (Figtree)

What I Learned
During this project I reinforced important CSS concepts:

css
/* Centering with Flexbox */
body {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

/* Box-shadow effects for card styling */
.card {
    border: 1px solid hsl(0, 0%, 7%);
    box-shadow: 8px 8px 0px hsl(0, 0%, 7%);
    transition: box-shadow 0.3s ease;
}

.card:hover {
    box-shadow: 12px 12px 0px hsl(0, 0%, 7%);
}

/* Position fixed for footer */
.attribution {
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    width: 100%;
}

/* Responsive image handling */
img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
}
Continued Development
Areas I want to continue focusing on in future projects:

CSS Grid for more complex layouts

Advanced CSS animations and transitions

Accessibility improvements

Performance optimization techniques

Author
Frontend Mentor - @DiegoRuiz8

GitHub - DiegoRuiz8