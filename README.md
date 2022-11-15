# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Preview](https://github.com/D0vl4/Profile-card-component/blob/ade700a6478cdbaedee5bd81245d6733cdf625c0/Design/Screenshot.png)

### Links

- Solution URL: https://www.frontendmentor.io/solutions/profile-card-component-SQHP71cdFk
- Live Site URL: https://pr0file-card-component.netlify.app

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I removed this circle because it was going down and to the right of the page, so the page was scrollable.

```css
.background::after {
  content: "";
  background-image: url("./images/bg-pattern-bottom.svg");
  width: 100%;
  height: 100%;
  position: absolute;
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
  right: -25%;
  bottom: -40%;
  clip-path: inset(0 25% 38% 0);
}
```

## Author

- Website - [Vlado](https://dovla.me)
- Frontend Mentor - [@D0vl4](https://www.frontendmentor.io/profile/D0vl4)
