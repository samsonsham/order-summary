# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](https://ik.imagekit.io/c5xc1x6srka/screenshot/screen-order-summary-card_qimVWYIva.png)

### Links

- Solution URL: [https://github.com/samsonsham/order-summary](https://github.com/samsonsham/order-summary)
- Live Site URL: [https://samsonsham.github.io/order-summary/](https://samsonsham.github.io/order-summary/)

## My process

- Set up SCSS file structure. Define all the styles given by style guide, including colours and font into SCSS files.
- Define components and setup corresponding DOM elements in HTML file.
- Build each elements by with colours, alignment, and adjusting size.
- Add interactive effects onto buttons and hyperlink.

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- Mobile-first workflow

### What I learned

I spotted there are difference spacing between desktop and mobile so I do a mobile first workflow then add media query to handle desktop spacing. One thing to notice is the background image. I was using `no-repeat` but after I make my browser wide enough and I fixed it to `repeat-x`.

```css
main {
  /* some other style*/
  background: url(../images/pattern-background-desktop.svg);
  background-repeat: repeat-x;
}
```

## Author

- Website - [Samson Sham](https://samson-sham-portfolio.vercel.app)
- Frontend Mentor - [@samsonsham](https://www.frontendmentor.io/profile/samsonsham)
- Twitter - [@samson_sham](https://www.twitter.com/samson_sham)
