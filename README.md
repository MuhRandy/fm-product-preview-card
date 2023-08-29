# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learn much about basic CSS and HTML. I learn about semantic like article tag is usually used on product card so I am using it here. I learn about Centering component using flexbox, about text spacing, and how to make responsive web that not broken when using different width platform. I like the code when you hovering just the background component that change not entirely. This is how I am doing it :

```html
<button>
  <div>
    <img src="images/icon-cart.svg" alt="icon-cart" />
    Add to Cart
  </div>
</button>
```

```css
button {
  background-color: var(--dark-cyan);
  border-radius: 5px;
  border-style: none;
  color: var(--white);
  font-weight: bold;
  padding: 0;
}

button div {
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  border-radius: 5px;
}

button img {
  width: 14px;
}

button div:hover {
  backdrop-filter: brightness(50%);
}
```

Sorry for lack of english, I am still learning :>.

### Continued development

I dont think so, but maybe I change my mind later so I will keep this at the moment.

### Useful resources

- [W3school](https://www.w3schools.com/) - This helped me for knowing basic CSS and HTML. I really liked how simple, straightforward and easy to understand on this website.
- [Stack Overflow](https://stackoverflow.com/) - This is an amazing platform which helped me to make a bit complex component or fixing some problem. I'd recommend it to anyone that struggling when meet some complicated problem.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
