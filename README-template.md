# Frontend Mentor - Browser Extensions Manager UI solution

This is a solution to the [Browser extensions manager UI challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/browser-extension-manager-ui-yNZnOfsMAp). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Toggle extensions between active and inactive states
- Filter active and inactive extensions
- Remove extensions from the list
- Select their color theme
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![Browser Extensions Manager UI](./preview.jpg)

### Links

- Solution URL: [Frontend Mentor Solution](#)
- Live Site URL: [Live Demo](#)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Vanilla JavaScript
- Custom theme switcher
- Responsive design principles

### What I learned

- Implementing a robust theme switching system with persistent storage
- Creating responsive card layouts that maintain consistency across screen sizes
- Building an effective filtering system for managing extension states
- Handling dynamic content updates without a framework
- Implementing smooth transitions and hover states
- Working with custom toggle switches and interactive elements

Key code highlights:

```css
/* Dynamic background gradient implementation */
body {
  background: linear-gradient(to bottom, hsl(227, 75%, 14%), hsl(226, 25%, 17%), hsl(225, 23%, 24%));
  background-attachment: fixed;
}

/* Responsive card layout */
.extensions-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
}
```

### Continued development

Future improvements and areas of focus:

- Adding animation transitions for theme switching
- Implementing drag-and-drop functionality for extension reordering
- Adding search functionality for extensions
- Enhancing accessibility features
- Implementing extension grouping capabilities
- Adding more interactive states and micro-animations

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
