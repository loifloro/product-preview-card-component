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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./dist/assets/design/screenshot.jpg)


### Links

- Solution URL: [Github](https://github.com/loifloro/product-preview-card-component)
- Live Site URL: [Github Pages](https://loifloro.github.io/product-preview-card-component/dist/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- BEM Methodology


### What I learned

In this project I used vanilla CSS and created this custom properties. I also applied using the picture tag on the transition of images to mobile and desktop sizes. 

To see how you can add code snippets, see below:
PICTURE TAG

```html
<picture>
        <source media="(min-width: 768px)"
                srcset="./assets/images/image-product-desktop.jpg">
        <img src="./assets/images/image-product-mobile.jpg" 
              alt="Gabrielle CHANEL"
              class="card__img">
</picture>
```
```css
:root {
    /* Colors */
    --dark-cyan: hsl(158, 36%, 37%);
    --cream: hsl(30, 38%, 92%);

    /* Neutral Colors */
    --very-dark-blue: hsl(212, 21%, 14%);
    --dark-grayish-blue: hsl(228, 12%, 48%);
    --white: hsl(0, 0%, 100%);
}
```

### Continued development

On to my next project Im gonna try to really personalize my solution just like what hall of famers do in this community. 


### Useful resources

- [CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - This is the reference I used on applying this custom properties as my color palette
- [How to use picture element](https://www.youtube.com/watch?v=Rik3gHT24AM) - As you all know Kevin Powell's videos are really a great help especially if you are visual learner.


## Author

- Github - [loifloro](https://github.com/loifloro/)
- Frontend Mentor - [@loifloro](https://www.frontendmentor.io/profile/loifloro)
- Twitter - [@loisfloro](https://www.twitter.com/loisfloro)
- LinkedIn - [@jlfloro](https://www.linkedin.com/in/jlfloro/)


