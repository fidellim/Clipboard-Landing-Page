# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/Solution%20PC.png)
![](./images/Solution%20Mobile.png)

### Links

- Solution URL: [Solution](https://github.com/fidellim/Clipboard-Landing-Page)
- Live Site URL: [Live Site](https://hungry-chandrasekhar-e8da03.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

To set all items equally in size as its container's display is in flex. Also, in order for max-width to work for button, you must set width first.

```css
nav {
	width: 100%;
	max-width: 500px;
}

img {
	flex: 1 1 0;
}
```

### Continued development

To practice more CSS Grid.

### Useful resources

- [Max-width in Button](https://stackoverflow.com/questions/14938428/why-would-max-width-not-work-on-this) - This helped me set a max-width for a button.
- [Equal Size of Items](https://stackoverflow.com/questions/29503227/how-to-make-flexbox-items-the-same-size) - This made me set each item to be equal in size when container of items are in flex.
- [Change Color of SVG from Img Tag](https://stackoverflow.com/questions/24933430/img-src-svg-changing-the-styles-with-css) - This helped me change the color of svg from an img tag.

## Author

- Website - [Fidel Lim](https://fidellim-portfolio.netlify.app/)
- Frontend Mentor - [@fidellim](https://www.frontendmentor.io/profile/fidellim)
- Github - [@fidellim](https://github.com/fidellim)
