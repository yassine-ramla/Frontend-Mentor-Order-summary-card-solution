# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Order summary card solution](#frontend-mentor---order-summary-card-solution)
  - [Table of contents](#table-of-contents)
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

- See hover states for interactive elements

### Screenshot

![](screenshot-active.png)
![](screenshot-mobile.png)
![](screenshot.png)

### Links

- Solution URL: [solution URL](https://www.frontendmentor.io/solutions/a-responsive-component-using-css-grid-and-flex-box-GfNM6BzP4O)
- Live Site URL: [live site URL](https://yassine-ramla.github.io/Frontend-Mentor-Order-summary-card-solution/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

if you have a section that contains just a background-image and it's height isn't fixed, you can set the display of its parent to grid and set the right fractions to make its height according to the rest chidrens, for exmple:

```html
<main>
  <header></header>
  <section>
    <h1>Lorem ipsum dolor sit amet.</h1>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Autem amet, illo
      odio atque cupiditate quam adipisci minus neque impedit ipsum!
    </p>
    <button>Lorem, ipsum dolor.</button>
  </section>
</main>
```

in this case, the `header` element doesn't have a specific height, but you can give it a height accourding to the height of the `section` element height:

```css
main {
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 1fr 2fr;
}
```

like this, the height of the header will be auomatically half the height of the section element;

## Author

- Frontend Mentor - [@yassine-ramla](https://www.frontendmentor.io/profile/yassine-ramla)
- Twitter - [@yassine_ramla](https://www.twitter.com/yassine_ramla)
