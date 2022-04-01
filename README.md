# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Order summary card solution](#frontend-mentor---order-summary-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

### Screenshot

![Screenshot](images/screenshot-order-summary.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://order-summary-component-green.vercel.app](https://order-summary-component-green.vercel.app)

## My process

### Built with

- HTML
- SASS, SCSS
- Flexbox

### What I learned

Funnily, where I struggled the most is when I tried to insert the curves SVG file on top of the background: either I could see the image on a white background, either the background color would be the only one to be displayed. It took me a while to understand that I just had to invert the 2 properties: 

```sass
body {
  font-family: $font-family;
  background: url(../images/pattern-background-desktop.svg) top center no-repeat ;
  background-size: 100%;
  background-color: $color-primary-light;
}
```

Also, in order to have the image overriding the padding of the main container and stretching on the entire width, I put it in a wrapper. It's the wrapper that stretches thanks to negative margins, instead of the image.  

## Author

- Frontend Mentor - [@Candyfair](https://www.frontendmentor.io/profile/Candyfair)
- Twitter - [@candy_fair](https://www.twitter.com/candy_fair)
