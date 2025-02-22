# Product Preview Card Component Solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout depending on their device's screen size.
- See hover and focus states for interactive elements.

### Screenshot

![](images/product_review_final_output_capture.png)

### Links

- **Solution URL:** [https://github.com/jayco01/Product-preview-card.git](https://github.com/jayco01/Product-preview-card.git)
- **Live Site URL:** [https://jayco01.github.io/Product-preview-card/](https://jayco01.github.io/Product-preview-card/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned

Working on this project challenged me to design a responsive website that looks great on various devices. In particular, I learned how to use CSS techniques such as:

- `clamp()` for creating scalable and responsive typography and spacing.
- Using the `<picture>` element with `<source>` to swap images based on screen size.
- Crafting media queries to adjust layouts for mobile and desktop screens.

I encountered difficulties with achieving a consistent look across different devices—my laptop and a larger external monitor displayed the design differently. This experience taught me the importance of considering multiple breakpoints (and perhaps adding an additional media query) to handle various screen resolutions effectively.

```css
/* Example: Using clamp() for responsive font size */
.prod__title {
  font-size: clamp(1.8rem, 2vw, 2.5rem);
} 
```


Continued Development
Going forward, I want to deepen my understanding of responsive design, especially:
- Creating tailored media queries for various screen resolutions.
- Mastering the use of clamp() and other dynamic CSS functions to build truly fluid layouts.