# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1. Creating format with html
2. defining styles in moble view
3. desktop view with media queries

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

The main thing i learned was how to use grid-template-area. I think this is the easiest approach to using grid in your projects

```css
@media (min-width: 1200px) {
  .cards {
    max-width: 1400px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: 2;
    grid-template-areas:
      "d d jw k"
      "j p p k";
  }

  .card-1 {
    grid-area: d;
  }
  .card-2 {
    grid-area: jw;
  }

  .card-3 {
    grid-area: j;
  }

  .card-4 {
    grid-area: p;
  }

  .card-5 {
    grid-area: k;
  }
}
```

### Useful resources

- [Grid Area Explanation](https://youtu.be/83iQbQoEmHM?si=N0IZmVyYj5XDmV8s) -This gave a straighforward rundown of grid-template-areas

## Author

- Website - [Durand](https://www.github.com/daebecodin)
- Frontend Mentor - [@daebecodin](https://www.frontendmentor.io/profile/daebecodin)

## Acknowledgments

- Ma Boi - [Josia](https://github.com/jlucas10)
