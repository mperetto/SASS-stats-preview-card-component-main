# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size

### Screenshot

Desktop version
![desktop version](./design/screen-shot-desktop.png)

Mobile Version
![mobile version](./design/screen-shot-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- SASS - SCSS
- Flexbox
- Mobile-first workflow

### What I learned

I never used img scrset attribute before.
```html
<img 
          srcset="./images/image-header-desktop.jpg 1440w, ./images/image-header-mobile.jpg 375w"
          sizes="(max-width: 375px) 375w, 1440w"
          class="img-fluid"
          alt="office image">
```

I have improve my skill with CSS FlexBox
```css
.stats {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
```

### Continued development

Id like to improve my skill with CSS grid / flexbox system and SASS / SCSS.

### Useful resources

- [Complete guide to CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me for CSS flex box property.

## Author

- Linkedin - [Marco Peretto](https://www.linkedin.com/in/marco-peretto/)
- Frontend Mentor - [@mperetto](https://www.frontendmentor.io/profile/mperetto)

