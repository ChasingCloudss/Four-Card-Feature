# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![Desktop-design](./design/og-desktop-design.jpeg)
![Tablet-design](./design/og-tablet-design.jpeg)
![Mobile-design](./design/og-mobile-design.jpeg)

### Links

<!-- Remember to add the netlify link and github link here -->

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

I struggled creating the colored accents on the cards. However, I figured it out by parsing a value to the `border-top` property of the `li` tag.

See the code snippet below:

```css
li {
  overflow: hidden;
  border-radius: 0.5rem;
  border-top: 0.4rem solid var(--orange);
  background-color: var(--white);
}
```

## Author

- Github - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
