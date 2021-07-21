# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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
- See hover states for interactive elements


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I ran into a little problem when I noticed that the width of the grid items wasn't uniform which was mainly because they grow according to the amount of contents with them. I did some trials and errors by trying to manipulate their max and min width, margin, padding (literally anything that could help) which all proved abortive. I googled about grid to see if there was a property I was missing and I came across grid-auto-columns. That pretty much solved the problem, but there was another problem; after setting the grid-auto-columns to 33%, the grid items had spaces in between them (which was not suppose to be so). well, I fixed it with this 
```css 
#container {
    grid-auto-columns: 33.33333333%;
    } /* that is 100% divided by 3 columns */
```
overall it was a pretty exciting challenge and I'm looking forward to completing more challenges.


### Continued development

I am gonna keep working on perfecting my CSS grid skills, also with flexbox but I definitely prefer grids

### Useful resources

- [w3schools grid auto columns](https://www.w3schools.com/cssref/pr_grid-auto-columns.asp) - This really helped me understand grid-auto-columns. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@kushyzee](https://www.frontendmentor.io/profile/kushyzee)
