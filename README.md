# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
 The challenge is to create a blog preview card that's mobile-first and responsive. 

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://blog-preview-card-main-two-gamma.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to work with CSS variable and its importance in organizing and simplifying my workflow. I also learned more about the flex property and how to use it effectively. Furthermore, I ensured that my design was responsive my working with media queries. Lastly, I practiced working with CSS psuedo-class. I worked with :hover, :focus, :active state. 

```css
:root {
    --BG-COLOR: #F4D04E;
    --BOX-SHADOW: #111111;
    --SHADOW: #6B6B6B;
    --MAIN-COLOR: #FFFFFF;
    --FONT-SIZE-14: 14px;
    --FONT-SIZE-24: 24px;
    --FONT-SIZE-20: 20px;
    --FONT-SIZE-16: 16px;
    --FONT-WEIGHT-BOLD: 800;
    --FONT-WEIGHT-MEDIUM: 600;
}

h1:hover, h1:active, h1:focus {
    color: var(--BG-COLOR);
    cursor: pointer;
}

@media screen and (max-width: 375px){ 
.img-container {
    width: 250px;
}

h1 {
    font-size: var(--FONT-SIZE-20);
}
}

## Author

- Website - [Joy](https://www.your-site.com)
- Frontend Mentor - [@joyafrikaana](https://www.frontendmentor.io/profile/yourusername)
