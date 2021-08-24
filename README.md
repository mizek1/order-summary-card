# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

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

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Screenshot](./images/screenshot.png)

### Links

- Solution URL: [Here!](https://github.com/mizek1/order-summary-card/blob/master/index.html)
- Live Site URL: [Here!](https://mizek1.github.io/order-summary-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

There is still some work to do, but, until now, I learned to start a new layout from zero and I've been able to improve my eye to see minor details along the design and to translate them to code.
I'm still learning how to make mobile-first workflow, so, there's still work to do here.

Some snippets:

> I've never worked with `CSS variables` and it's pretty easy!

```css
:root {
  --pale-blue: hsl(225, 100%, 94%);
  --very-pale-blue: hsl(225, 100%, 98%);
  --bright-blue: hsl(245, 75%, 52%);
  --desaturated-blue: hsl(224, 23%, 55%);
  --dark-blue: hsl(223, 47%, 23%);
}
```

> I tried to make things easier for me when using `flexbox`:

```css
.flex-row {
  display: flex;
  flex-direction: row;
}

.flex-column {
  display: flex;
  flex-direction: column;
}

.align-center {
  align-items: center;
}

.justify-center {
  justify-content: center;
}

.space-around {
  justify-content: space-around;
}
```

### Continued development

I need to improve viewports and responsive layouts.

## Author

- Website - [Danilo Alves](https://github.com/mizek1)
- Frontend Mentor - [@mizek1](https://www.frontendmentor.io/profile/mizek1)
