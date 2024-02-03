# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 



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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

<img src="./assets/design/desktop-preview.jpg" alt="Desktop design"/>


### Links

- Solution URL: [https://github.com/NataMellado/blog-card-challenge](https://github.com/NataMellado/blog-card-challenge)
- Live Site URL: [https://natamellado.github.io/recipe-page-challenge/](https://natamellado.github.io/recipe-page-challenge/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Grid and flexfox

### What I learned

#### 1. Hoover and focus states
```css
.card-title:hover,
.card-title:focus {
    color: var(--color-primary);
}
```
#### 2. The tabindex attribute makes the element focusable.
```html
<h2 tabindex="0" class="card-title">HTML & CSS foundations</h2>
```
#### 3. Responsive Grid Layout

```css
.card-section {
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    padding: 2rem;
}
```

#### 4. Body Height Set to 100% of Viewport Height
```css
body{
    height: 100vh;
}
```
