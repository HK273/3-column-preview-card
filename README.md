# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview
3-column preview card component challenge. Page should look as close to the design as possible\
and should be responsive to users screen sizes


### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/three-column-preview-card-css-grid-yXF6KqigS)
- Live Site URL: [Live Site](https://hk273.github.io/3-column-preview-card/)

### Built with

- HTML5 markup
- CSS Grid
- Google Fonts


### What I learned

Creating a three column equal grid, which collapses to rows at breakpoint

```css
grid-template-columns: repeat(3, minmax(0, 1fr));
```
```css
@media screen and (max-width: 1188px) {
    .wrapper {
        display: grid;
        /* collapse to rows */
        grid-template-columns: none;
    }
```

### Useful resources

- [CSS Grid](https://yoksel.github.io/grid-cheatsheet/) - Gave me a great overview on grid
- [CSS Grid](https://css-tricks.com/equal-width-columns-in-css-grid-are-kinda-weird/) - Helped me understanding how to produce equal columns when using grid
- [Markdown Preview](https://markdownlivepreview.com)

## Author

- Frontend Mentor - [@HK237](https://www.frontendmentor.io/profile/HK-Data-Monkey)

