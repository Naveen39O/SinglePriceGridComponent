# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![SinglePriceGridComponent](https://github.com/Naveen39O/SinglePriceGridComponent/blob/main/Screenshot_Single_Price_Grid_Component.png)


### Links

- Solution URL: [SinglePriceGridComponent](https://github.com/Naveen39O/SinglePriceGridComponent)
- Live Site URL: [SinglePriceGridComponent/](https://naveen39o.github.io/SinglePriceGridComponent/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I have learnt to use CSS Grid and Flexbox for the first time.

To see how you can add code snippets, see below:

```html
  <div class="grid-container">
```
```html
<div class="cost-div">
  <span class="cost">&dollar;29</span>
  <span class="cost-month"> per month</span>
</div>
```
```css
.grid-container{
  display: grid;
  grid-template-columns: 50% 50%;
}
```
```css
.cost-div{
  display: flex;
  align-items: center;
  gap: 0.5rem;
}
```

### Continued development

I haven't started using CSS preprocessors yet.
I would like to learn them and make the CSS code DRY.


## Author

- Website - [Naveen39O](https://github.com/Naveen39O)
- Frontend Mentor - [Naveen39O](https://www.frontendmentor.io/profile/Naveen39O)

## Acknowledgments
- [w3schools](https://www.w3schools.com/)
