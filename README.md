# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/joud-s/3-column-preview-card-component)
- Live Site URL: [Add live site URL here](https://joud-s.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I initially struggled to prevent the expansion behavior of the button when the hover effect occurs, and then looked it up at stack overflow and fix it.

To see how you can add code snippets, see below:

```html
<div class="box box-1">
  <div class="svg">
    <img src="./images/icon-sedans.svg" alt="sedan svg" />
  </div>
  <h1>Sedans</h1>
  <p>
    Choose a sedan for its affordability and excellent fuel economy. Ideal for
    cruising in the city or on your next road trip.
  </p>
  <button class="button-1">learn more</button>
</div>
```

```css
button {
  background: white;
  border: none;
  padding: 0.75rem 1.5rem;
  border-radius: 1.25rem;
  text-transform: capitalize;
  cursor: pointer;
}
button:hover,
button:focus {
  background: transparent;
  box-shadow: 0 0 0 1px #ffffff;
  color: white;
  overflow: hidden;
}
```

### Useful resources

- [stackoverflow](https://stackoverflow.com/questions/60391939/div-expand-its-size-on-hover-due-to-border) - This helped me for prevent the expanding behavior for the button when hover on.

## Author

- Frontend Mentor - [@joud-s](https://www.frontendmentor.io/profile/joud-s)
- Twitter - [@joudishaker](https://www.twitter.com/joudishaker)
