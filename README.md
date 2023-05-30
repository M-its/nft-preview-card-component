# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

This is an example of an NFT card component.

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover states for interactive elements

### Screenshot

![Desktop](./solution.png)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   Mobile-first workflow

### What I learned

In this project I have learned how to use css pseudo-elements

See below a code snippet that I'm proud of:

```css
.nft-preview-card-component-image {
    display: flex;
    flex-direction: column;
    position: relative;
}

.nft-preview-card-component-image::after {
    content: url(./images/icon-view.svg);
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    border-radius: 15px;
    background-color: var(--cyan-cover);
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
    transition: opacity 0.3s ease-in-out;
}
```

### Continued development

for the next projects I want to deepen my knowledge in pseudo-classes and accessibility

### Useful resources

-   [MDN Web Docs - ::after (:after)](https://developer.mozilla.org/pt-BR/docs/Web/CSS/::after) - This helped me to understand pseudo-elements.
-   [W3 Schools - CSS hsla() Function](https://www.w3schools.com/cssref/func_hsla.php) - This is an amazing article about how to add transparency to an opaque color.
-   [DEV - Técnica para você mudar de pixels(px) para rem!](https://dev.to/gabrlcj/tecnica-para-voce-mudar-de-pixels-px-para-rem-2626) - This article helped me to build the project with more responsive fonts.

## Author

-   GitHub - [@M-its](https://github.com/M-its)
-   Frontend Mentor - [@M-its](https://www.frontendmentor.io/profile/M-its)
-   Codepen - [@M-its](https://codepen.io/m-its)
