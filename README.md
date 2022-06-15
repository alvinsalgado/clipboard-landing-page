# Frontend Mentor - Clipboard landing page solution

![Design preview for the Clipboard landing page coding challenge](./design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Frontend Mentor-solution](https://www.frontendmentor.io/solutions/responsive-landing-page-zIBcmAZ_q0)
- Live Site URL: [Live Demo](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I used svg format for the icons. It lets you change the properties of the svg with CSS.

```html
<a href="#"
  ><svg width="24" height="20" xmlns="http://www.w3.org/2000/svg">
    <path
      class="icon"
      d="M24 2.557a9.83 9.83 0 01-2.828.775A4.932 4.932 0 0023.337.608a9.864 9.864 0 01-3.127 1.195A4.916 4.916 0 0016.616.248c-3.179 0-5.515 2.966-4.797 6.045A13.978 13.978 0 011.671 1.149a4.93 4.93 0 001.523 6.574 4.903 4.903 0 01-2.229-.616c-.054 2.281 1.581 4.415 3.949 4.89a4.935 4.935 0 01-2.224.084 4.928 4.928 0 004.6 3.419A9.9 9.9 0 010 17.54a13.94 13.94 0 007.548 2.212c9.142 0 14.307-7.721 13.995-14.646A10.025 10.025 0 0024 2.557z"
      fill="#4C545C"
      fill-rule="nonzero"
    /></svg
></a>
```

```css
footer .social .icon:hover {
  fill: var(--strong-cyan);
}
```

### Useful resources

- [Set svg hover state to swap colors](https://css-tricks.com/the-many-ways-to-change-an-svg-fill-on-hover-and-when-to-use-them/)

## Author

- Frontend Mentor - [@alvinsalgado](https://www.frontendmentor.io/profile/alvinsalgado)
