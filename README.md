# Frontend Mentor - Blog Preview Card Solution

This is my solution to the [Blog Preview Card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/DiegoRuiz8/blog-preview-card)
- Live Site URL: [Live Demo](https://diegoruiz8.github.io/blog-preview-card/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Google Fonts (Figtree)

### What I Learned

During this project I reinforced important CSS concepts:

```css
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
```
