# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- [Solution URL:](https://github.com/rlabuonora/frontend-mentor-grid-testimonials)
-  [Live Site URL:](https://frontend-mentor-grid-testimonials.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Used grid-template-areas for this one:

```css
   .container {
        display: grid;
        gap: 2em;
        grid-template-areas: 
                 "a a b e"
                 "c d d e";
        grid-template-columns: 1fr 1fr 1fr 1fr;

    }

     figure:nth-child(1) {
        grid-area: a;
    }

    figure:nth-child(2) {
        grid-area: b;
    }


```
## Author

- Website - [Rafael La Buonora](https://www.rlabuonora.com)
- Frontend Mentor - [@rlabuonora](https://www.frontendmentor.io/profile/rlabuonora)
- Twitter - [@rlabuonora](https://www.twitter.com/rlabuonora)
