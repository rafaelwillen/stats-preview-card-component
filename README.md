# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
  - [Author](#author)

## Overview

The challenge is to build this card component and get it looking as close to the design as possible.

The tools tha I used are HTML and Sass pre-processor for CSS.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screenshot.png)

### Links

- Live Site URL: [Stats Preview Card Component](https://rafaelwillen.github.io/stats-preview-card-component/)

## My process

First I started with the markup, then setting up the scss compiler.

After that I created a basic workflow of the scss, by making two partials files that contain the global styling and variables. The rest of the styling, including the media queries, are in the main file of the scss.

This is my first approach of mobile first design and I believe it was good, but I think I could made the media queries with less line.

There are were two places that I struggled:

* The image sizing
* The image color overlay

For the image color overlay, I used the `mix-blend-mode` property to get as close to the color of the design, and for me it was good enough. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SCSS Pre-processor

## Author

- Twitter - [@RafaelWillen](https://www.twitter.com/RafaelWillen)
