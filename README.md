# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Build out the project to the designs provided

### Screenshot

![](./design/Desktop%20design.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I learnt how to work with svg backgrounds and how to add color to the hr tag used for horizontal lines.



```css
hr{
    margin: .5rem auto 1.5rem;
    border: 1px solid hsla(0, 0%, 59%, 0.205);
}
body::after {
    z-index: -1;
    background: url("images/bg-pattern-bottom.svg") no-repeat top left;
    top: 100%;
    left: 100%;
}
body::before {
    z-index: -1;
    background: url(images/bg-pattern-top.svg) no-repeat bottom right;
    top: 0;
    left: 0;
}
```

### Continued development

I'm going to continue learning how to work with svg backgrounds properly.


## Author

- Website - [tbahd](https://olukolejames.netlify.app)
- Frontend Mentor - [@tbahd](https://www.frontendmentor.io/profile/tbahd)
- Twitter - [@tbahd](https://www.twitter.com/tbahd2)
