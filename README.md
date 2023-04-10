# Frontend Mentor - Space tourism website solution

This challenge is my solution to the Space Tourism website challenge from Frontend Mentor in collaboration with Scrimba and Kevin Powell.  [Space tourism website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/space-tourism-multipage-website-gRWj1URZ3). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
- [Log](#log)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for each of the website's pages depending on their device's screen size
- See hover states for all interactive elements on the page
- View each page and be able to toggle between the tabs to see new information

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- Crested all the base styles first, using Sass variables and utility classes;
- Styled all the components individually (buttons, navs, layouts, etc) before coding the html structure;

### Built with

- Semantic HTML5 markup
- CSS utility classes
- Sass nesting and variables
- Mobile-first workflow

### What I learned

```CSS

    /* Creating .sr-only class in reset to define classes available for only for screen readers */
    .sr-only {
    position: absolute; 
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px; 
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap; /* added line */
    border: 0;
  }

   /* Using clamp to define font-sizes */
   font-size: clamp(5rem, 10vw, 9.25rem);

   /* The shorthand place-items to center items on the grid vertically and horizontally */
   place-items: center;

   /* Using padding-inline to set the spaces on the left and right of a inline element */
   padding-inline: 2rem;

   /* Using backdrop-filter property to create a blurred effect in the mobile menu */
   backdrop-filter: blur(2rem);

```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- MSDN documentation about backdrop-filters (https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter#browser_compatibility)

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

## Log