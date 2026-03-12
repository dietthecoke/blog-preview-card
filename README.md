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

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop screenshot](<screenshots/Desktop view.png>)
![Mobile screenshot](<screenshots/Mobile view.png>)

### Links

- [Solution URL](https://github.com/dietthecoke/blog-preview-card)
- [Live site URL](https://dietthecoke.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Custom fonts using @font-face
- Mobile-first workflow

### What I learned

While building this project, I practiced structuring a reusable card component and applying consistent styling using CSS variables.

I also learned how to include local fonts using @font-face and manage different font weights from the same font family.

Example of defining custom CSS variables:
```css
:root {
  --yellow: hsl(47, 88%, 63%);
  --white: hsl(0, 0%, 100%);
  --gray-500: hsl(0, 0%, 42%);
  --gray-950: hsl(0, 0%, 7%);
}
```
I also practiced creating hover states for links:
```css
h1 a:hover {
  color: var(--yellow);
}
```

Using Flexbox made it easier to align elements such as the author avatar and name:
```css
.card-author {
  display: flex;
  align-items: center;
  gap: 12px;
}
```

## Author

- Frontend Mentor - [@dietthecoke](https://www.frontendmentor.io/profile/dietthecoke)

