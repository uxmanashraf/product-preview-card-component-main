# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Product preview card component challenge screenshot](./screenshot.png)

### Links

- Live Site URL: [https://tiny-cocada-d996ad.netlify.app/](https://tiny-cocada-d996ad.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

Well, I learned a lot of things by implementing this challange.

Implemented the solution using mobile-first approach and then wrote media query for desktop design.

Wrote code of non-visual accessability and hidden over visual devices. Snippet given below:

```html
<div class="flex-group">
  <p class="product__price">
    <span class="visually-hidden">Current price:</span>
    $149.99
  </p>
  <p class="product__original-price">
    <span class="visually-hidden">Original price:</span>
    <s>$169.99</s>
  </p>
</div>
```

### Continued development

In future, I want to focus more and more on semantic html and equal accessibilty based solutions.

## Author

- LinkedIn - [Usman Ashraf](https://www.linkedin.com/in/uxmanashraf/)


## Acknowledgments

I've been following [Kevin Powell](https://www.youtube.com/@KevinPowell) since some time and its really helping me sharpen my skills in HTML & CSS.

