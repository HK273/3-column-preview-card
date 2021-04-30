# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Issues & Critiques](#Issues-&-Critiques)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview
3-column preview card component challenge. Page should look as close to the design as possible\
and should be responsive to users screen sizes


### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/three-column-preview-card-css-grid-yXF6KqigS)
- Live Site URL: [Live Site](https://hk273.github.io/3-column-preview-card/)

## My process

This was my first time completing a challenge on front end mentor and I really enjoyed the experience. \
I've been messing around with web development for a while, mostly just watching tutorials but haven't really \
taken the time to focus on a specific design, so this was a great learning experience for me. \
\
I started by writing out my HTML first to get the structure of the content sorted. I then added styles periodically \
until each section matched the design as close as possible.

### Issues / Critiques

Although I was quite happy with the end result and was pleasantly surprised with how quickly this came together (given my lack of experience)

I'm pretty sure that a lot of my CSS could've been condensed or written more appropriately.\
\
For example, the way I have positioned the images, headings and paragraphs using margin makes the content shift around unevenly at certain screen sizes. 
Is there a better way to manage the position of elements without having content shift around like this?\
\
I guess I could've used more breakpoints to change the size of elements to prevent this but this seemed a pretty convoluted approach.

I did a fair amount of experimenting with the position property but couldn't come up with a solution. More revision definitely needed on my part.I also ended up putting the breakpoint at 1188px because of this content shifting issue.

Alongside this, I also created three separate classes to style the button hover states - I'm sure there is a much neater approach to take!


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

I've also never used Git / Github before so that was a bit of a learning curve. But it's definitely great
to get stuck in and learn new technologies! 

### Continued development

Will definitely be looking to pick up another challenge, as feel I learned so much more actually attempting to create something
rather than just watching tutorials.

I need to be spend a bit more time understanding the box model, positioning elements and media queries.

### Useful resources

- [CSS Grid](https://yoksel.github.io/grid-cheatsheet/) - Gave me a great overview on grid
- [CSS Grid](https://css-tricks.com/equal-width-columns-in-css-grid-are-kinda-weird/) - Helped me understanding how to produce equal columns when using grid
- [Markdown Preview](https://markdownlivepreview.com)

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

