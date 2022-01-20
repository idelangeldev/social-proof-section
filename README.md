# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshots

![](/screenshots/screenshot-desktop.png)
![](/screenshots/screenshot-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Sass

### What I learned

I relearned using SVG files as background images. I used percentages to determine the size of the images. I'm sure someone else came up with a different solution. However, mine is the one that worked best for me.

```css
body {
  background-image: url(../images/bg-pattern-top-desktop.svg),
    url(../images/bg-pattern-bottom-desktop.svg);
  background-repeat: no-repeat no-repeat;
  background-position: left 0 top 0, right 0 bottom 0;
  background-size: 39.7%, 76.9%;
}
```

## Author

- Frontend Mentor - [@mexwebdev21](https://www.frontendmentor.io/profile/mexwebdev21)
- Twitter - [@mexwebdev2121](https://www.twitter.com/mexwebdev2121)

## Acknowledgments

A big shoutout to Kevin Powell [@KevinJPowell](https://twitter.com/KevinJPowell). His video tuturial on taking control of backgroud images helped a lot. In fact, the use of percentage in the "background-size property", came from said tutorial.
