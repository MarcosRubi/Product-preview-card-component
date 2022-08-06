# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./result/screenshot.png)

### Links

- Solution URL: [GitHub](https://github.com/MarcosRubi/Product-preview-card-component)
- Live Site URL: [GitHub Pages](https://marcosrubi.github.io/Product-preview-card-component/)

## My process

### Built with

- Pug
- SCSS
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I learned how to use the picture tag to be able to change the image to display depending on the size of the screen.
[Documentation](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)


```html
<picture>
    <source srcset="images/image-product-desktop.jpg" media="(min-width:768px)">
    <img src="images/image-product-mobile.jpg" alt="Imagen del producto">
</picture>
```

## Author

- Website - [Marcos Rubí](https://mrubi.vercel.app/)
- Frontend Mentor - [@MarcosRubi](https://www.frontendmentor.io/profile/MarcosRubi)
