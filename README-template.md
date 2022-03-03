# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![this is screen shot](https://kun982.github.io/nft-preview-card-component/final.png)

### Links

- Solution URL: [my solution here](https://github.com/Kun982/nft-preview-card-component)
- Live Site URL: [live demo](https://kun982.github.io/nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

-use BEM

I try to use BEM to organize my html structure,and i found it is useful but need to practice.

### My question for this project

-How my css could adjust to better?
I try to mobile-first workflow, but i found a question when i try to fix the laptop view is my css is start to confusing to using BEM,for example:

this is mobile:

```css
.mt-1 {
  margin-top: 24px;
}

.mt-2 {
  margin-top: 16px;
}

.mb-2 {
  margin-bottom: 16px;
}
```

this is laptop:

```css
.mt-1 {
  margin-top: 22px;
}
.mt-2 {
  margin-top: 24px;
}
.mb-2 {
  margin-bottom: 25px;
}
```
