# Stats preview card component

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (1440px and 375px)

### Screenshot

![Stats Preview Card Screenshot](/images/stats_preview_card_screenshot.jpg)

### Links

- [Live Site URL](https://thealexgonzo.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- Vanilla CSS
- Flexbox
- Mobile-first workflow

### What I learned

I really enjoyed workign on this project, although it only works with two screen sizes (1440px and 375px), I still had the opportunity to learn and practice some new CSS properties. I also think that my HTML was a lot more organised this time than with previous projects.

The new CSS property I discovered in this project was <code>background-blend-mode</code>, and combining it with <code>background-color</code> and <code>background-image</code>:

```css
.preview-card__image-container {
  background-color: var(--accent_color);
  background-image: url("images/image-header-mobile.jpg");
  background-blend-mode: multiply;
}
```

### Continued development

There are two things I would like to focus on my next projects. Firslty to make sure that my designs are repsonsive at different sizes between a max and a min instead of just matching two screen sizes like a did with this project. The other tech I will practice with my next project is to use a CSS pre-processor, probably Sass.

### Useful resources

- [Blend background images and colors with CSS](https://www.youtube.com/watch?v=HwDyNRkJZLQ) - This helped me learn how to create the <code>background-image</code> overaly effect.
- [background-image MDN documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image) - This helped me understand <code>background-image</code> a lot better.

## Author

Jesus Alejandro González Rodríguez
