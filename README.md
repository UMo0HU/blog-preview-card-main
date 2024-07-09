# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Solution](https://github.com/UMo0HU/blog-preview-card-main)
- Live Site URL: [Live Site](https://umo0hu.github.io/blog-preview-card-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


  ### What I learned

1 - I was happy learning about how to use an external font file using the @font-face.
```css
@font-face {
    font-family: "Figtree";
    src: url(assets/fonts/Figtree-VariableFont_wght.ttf);
}
```

2 - also I was happy learning about the :Seudo-class using MDN as a reference.
```css
.inner-container p:nth-child(3) {
    font-weight: 600;
    font-size: 12px;
    margin: 3px 0 13px;
}
```

3- and finally it was a good experience to learn how to use Combinators using w3schools as a reference.
```css
img + p {
    background-color: var(--Yellow);
    padding: 5px 7.5px;
    width: fit-content;
    display: inline-block;
    font-weight: 900;
    font-size: 13px;
    border-radius: 5px;
    margin: 0 0 10px;
}
```

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:first-child) - This helped me understanding Suedo-classes.
- [W3schools](https://www.w3schools.com/css/css_combinators.asp) - his helped me understanding Combinators.

## Author

- Frontend Mentor - [UMo0HU](https://www.frontendmentor.io/profile/UMo0HU)
