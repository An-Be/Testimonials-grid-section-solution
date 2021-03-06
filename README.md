# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/images/Screenshot-large.png)
![](/images/screenshot-small.png)

<!-- ### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com) -->

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned the very basics of CSS Grid. How to make different sections different sizes and how to change their positions according to their line numbers. I also learned how to use grid and media queries to make cards stack vertically.


```css
.proud-of-this-css {
  @media(max-width: 1050px){
    .container{ 
       grid-template-columns: 1fr;
       width: 100%
    }
    #daniel{
        grid-column: 1;
    }
    #patrick{
        grid-column: 1;
        grid-row: 4;
    }
    #kira{        
        grid-column: 1;
        grid-row: 5;
    }
  }
}
```

### Useful resources

- [Example resource 1](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me better understand the units of measurements used in grid box and also the basics of how to get started.

## Author

- Website - [Andrea Berrocal](https://andreacodes-alpha.vercel.app/)
