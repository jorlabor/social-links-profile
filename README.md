# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Design preview for the Social links profile coding challenge](./preview.jpg)

### Links

- Solution URL: <https://github.com/jorlabor/social-links-profile>
- Live Site URL: [social-links-profile-labor.netlify.app](https://social-links-profile-labor.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- `@font-face` for custom font hosting
- BEM (Block Element Modifier) naming convention
- Mobile-first approach

### What I learned

Working through this project helped me practice several key frontend concepts. Here are some highlights:

Using CSS custom properties to create a consistent design system:

```css
:root {
  --font-family: "Inter", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  --grey-900: hsl(0, 0%, 8%);
  --grey-800: hsl(0, 0%, 12%);
  --grey-700: hsl(0, 0%, 20%);
  --green: hsl(75, 94%, 57%);
  --white: hsl(0, 0%, 100%);
}
```

Centering content vertically and horizontally using CSS Grid:

```css
body {
  min-height: 100svh;
  display: grid;
  grid-template-rows: 1fr auto;
  justify-items: center;
  align-items: center;
}
```

Hosting custom fonts locally with `@font-face`:

```css
@font-face {
  font-family: "Inter";
  src: url("./assets/fonts/static/Inter-Regular.ttf") format("truetype");
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
```

Using BEM naming for clean, maintainable class names like `card__avatar`, `card__button`, and `attribution__link`.

### Continued development

Areas I want to continue focusing on in future projects:

- Responsive design: Making the card layout adapt more fluidly across different screen sizes instead of a fixed width
- Focus states: Adding more visible `:focus-visible` styles for better keyboard accessibility
- CSS transitions: Adding smooth animations when transitioning between hover states
- ARIA attributes: Learning more about accessibility attributes to make interactive elements even more usable with screen readers

### Useful resources

- [MDN Web Docs - @font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face) - This helped me understand how to properly host custom fonts locally.
- [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - A great visual reference for understanding Flexbox properties.
- [CSS-Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me use CSS Grid for centering content on the page.
- [BEM Methodology](https://getbem.com/introduction/) - A good introduction to the BEM naming convention for CSS classes.

### AI Collaboration

This project was built with guidance from an AI mentor who provided hints and explanations rather than writing code directly, to support the learning process.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@jorlabor](https://www.frontendmentor.io/profile/jorlabor)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

Thanks to Frontend Mentor for providing this challenge with clear designs and a helpful starter template. It's a great project for practicing HTML structure and CSS layout fundamentals.
