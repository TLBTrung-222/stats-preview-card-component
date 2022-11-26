# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)

## Overview

### Screenshot

![](./screenshot.png)

### Links

-   Solution URL: [Mr Coder](https://www.youtube.com/watch?v=dhBR6-Jjql4)
-   Live Site URL: [Github Pages](https://tlbtrung-222.github.io/stats-preview-card-component/)

## My process

### Built with

-   CSS custom properties
-   Grid

### What I learned

-   If you want the layout split into multi column with the same width (items have padding), do not use flex. Instead, use grid. [Read here](https://css-tricks.com/equal-columns-with-flexbox-its-more-complicated-than-you-might-think/)

-   How to uppercase the text :

```css
p {
    text-transform: uppercase;
}
```

-   Create a layer on the image

```html
<div class="img-container">
    <img src="./images/image-header-desktop.jpg" alt="header image" />
    <div class="purple-layer"></div>
</div>
```

```css
.img-container {
    position: relative;
}

.purple-layer {
    background-color: hsl(277, 64%, 61%, 40%);
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
}
```

### Continued development

-   Semantic HTML5 markup
-   Know when to use flex or grid

### Useful resources
-   CSS Tricks : [Here](https://css-tricks.com/equal-columns-with-flexbox-its-more-complicated-than-you-might-think/)