# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
I got stuck for a long time with svg styling. I haven't learned about svg yet. I had a problem with setting the SVG to the text in the button. SVG and text also had to be responsive to screen size. At the current level of knowledge, I used the display: inline-block property to align the SVG with the text. To do this, I enclosed the text with a span tag. I was able to position the SVG on the left side away from the text. Using the vertical-aligne property, I positioned the text in the center of the SCG.This was the most difficult for me in this exercise.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

In this challenge, I recorded the positioning of the object using flexbox.

```css
body {
    width: 100%;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: hsl(30, 38%, 92%);
    font-family: 'Montserrat', sans-serif;
    color: hsl(228, 12%, 48%);
}

```
### Continued development

In the course of further study, I need to learn how to handle SVG files.

### Useful resources

- [W3schools](https://www.w3schools.com/cssref/css3_pr_border-radius.asp) - This helped me understand how to make only two rounded corners using CSS border-radius Property.

## Author

- Website - [explorem](https://github.com/explorem)
- Frontend Mentor - [@explorem](https://www.frontendmentor.io/profile/explorem)
- Twitter - [@dkedzierska91](https://www.twitter.com/dkedzierska91)
