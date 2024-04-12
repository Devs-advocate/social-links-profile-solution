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
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This is a recreation of the Social links HTML page

### The challenge

Users should be able to:

- See hover states for all interactive elements on the page.

### Screenshot

![Desktop](./assets/images/FEM%20Social%20links%20desktop%20screenshot.png)
![Mobile](./assets/images/FEM%20Social%20links%20mobile%20screenshot.png)

### Links

- Live Site URL: [GitHub Pages](https://your-live-site-url.com)

## My process

I started by using @font-face for the downloaded Inter font and it's typography. From there I made custom properties for colors and font size as per the style guide.
The HTML was then completed, using semantic tags where possible, and descriptive CSS class selectors.
Before styling the HTML, I used a reset to zero unwanted margins and padding.
The styling started from the outside-in, hardcoding container and elements sizes. Followed by layout and centering using flexbox. Then individual elements were styled with matching colors, typography and states.
The mobile styling was completed next, with only sizing properties affected.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Custom properties
- @font-face

### What I learned

I learned how to change the type of quotes used for the q tag.

```css
q::before {
  content: '"';
}

q::after {
  content: '"';
}
```

### Continued development

I feel quite comfortable with this type of design. There aren't any particular difficult components, but I'll strive to find out how to do it better anyway.

## Author

- Frontend Mentor - [@Devs-advocate](https://www.frontendmentor.io/profile/Devs-advocate)
