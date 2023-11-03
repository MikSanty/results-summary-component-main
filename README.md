# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help us improve your coding skills by building realistic projects.

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](/design/desktop-design.png)
![](/design/active-state.png)
![](/design/mobile-design.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The data-_ attribute is used to store custom data private to the page or application. The data-_ attribute gives us the ability to embed custom data attributes on all HTML elements.

```html
<div class="result-great result-gap" data-spacing="small"></div>
```

```css
.result-gap {
  gap: 1.5rem;
}
.result-gap[data-spacing="small"] {
  gap: 1rem;
}
```

### Continued development

These are concepts I am still not completely comfortable with or techniques I found useful that I want to refine and perfect.

- Using data-attributes
  - We can store custom data that is relevant to our specific element, such as an ID, a name, a value, or any other information that we need.
  - We can use the data to create dynamic and interactive user experiences, such as changing the style or behavior of an element based on the data value.
  - We can use the data to enhance the semantics and accessibility of our HTML elements, by providing additional information that is not visible to the users but can be read by assistive technologies or search engines.

### Useful resources

- [A (more) Modern CSS Reset](https://andy-bell.co.uk/a-more-modern-css-reset/) - This is where I got my reset css.
- [From Design to Code // HTML & CSS from scratch // Frontend Mentor](https://www.youtube.com/watch?v=KqFAs5d3Yl8&t=1063s) - This is a video which helped me understand the concept and usage of data-attributes quite clearly.

## Author

- Frontend Mentor - [@MikSanty](https://www.frontendmentor.io/profile/MikSanty)

## Acknowledgments

- Special thanks to Kevin Powell and Andy Bell
