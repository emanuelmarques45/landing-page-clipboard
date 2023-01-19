# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshots

#### Desktop Layout

![Desktop](https://github.com/emanuelm45/portfolio-images/blob/main/landing-page-clipboard/desktop.png)

#### Mobile Layout

<p align="center">
  <img src="https://github.com/emanuelm45/portfolio-images/blob/main/landing-page-clipboard/mobile.png">
</p>

### Links

- Solution URL: https://www.frontendmentor.io/solutions/responsive-landing-page-made-with-html-and-sass-03Fg4X5ql8
- Live Site URL: https://emanuelm45.github.io/clipboard-landing-page-master/
## My process

### Built with

- Semantic HTML5 markup
- SASS functions
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow
- [AOS](https://michalsnik.github.io/aos/) - JS library for scroll animation

### What I learned

I first used the SASS functions, just to know a little bit about. It is very interesting. I also used the library Animation On Scroll (AOS) to use the animations

```html
<li data-aos="fade-up" data-aos-anchor-placement="top-center" data-aos-easing="ease" data-aos-duration="1000">
  <h3>Create blacklists</h3>
  <p>Ensure sensitive information never makes its way to your clipboard by excluding certain sources.</p>
</li>
```
```css
@mixin hover-background($color) {
    background-color: $color;

    &:hover {
        background-color: lighten($color: $color, $amount: 65);
    }
}

@mixin hover-image($image, $image-hover) {
    background-image: $image;
    background-size: cover;

    &:hover {
        background-image: $image-hover;
    }
}
```

### Continued development

I intend to continue studying SASS and using its functionalities the best way possible.

## Author

- Frontend Mentor - [@emanuelm45](https://www.frontendmentor.io/profile/emanuelm45)
- LinkedIn - [Emanuel Marques](https://www.linkedin.com/in/emanuel-marques-541617215/)
