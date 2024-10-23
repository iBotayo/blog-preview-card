# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/screenshot.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/iBotayo/blog-preview-card)
- Live Site URL: [Preview Card](https://ibotayo.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

While working on this project, I learnt how to structure and position contents in the center using flexbox. With this, I was able to increase my knowledge on flexbox. Also, I used the mobile-first approach in designing.

See code snippet below:

```css
@media (min-width: 900px) {
  .card {
    justify-items: center;
    align-items: center;
    width: 200px;
    padding: 10px 10px;
  }

  .banner {
    width: 200px;
  }

  .button,
  .published,
  .description,
  .name {
    font-size: 10px;
  }

  h4 {
    font-size: 15px;
  }

  .avatar {
    width: 30px;
  }
}
```

### Continued development

I would continue to expand my knowledge in flexbox, CSS Grid, mobile-first design approach and also learn to add JavaScript for responsiveness.

## Author

- Frontend Mentor - [@iBotayo](https://www.frontendmentor.io/profile/iBotayo)
- Twitter - [@O_ibot](https://www.twitter.com/O_ibot)
- GitHub - [iBotayo](https://www.github.com/ibotayo)
