# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [my solution](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-/hub/responsive-card-component-4UbMS8UkA)
- Live Site URL: [live site here](https://loving-mahavira-a81c12.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [bootstrap](hhttps://getbootstrap.com/docs/5.1/getting-started/download/) - For styles

### What I learned

image resizing:

```css
.image-container img {
    width: 15%;
    height: auto;
    margin: 1rem;
}
```
flexbox:

centering 
```
main {
    display: flex;
    justify-content: center;
    align-items: center;
    height:100vh;
}
```
Media Query:

moblile responsive solution

```
@media only screen and (max-width:768px) {
    main {
        flex-direction: column;
        margin: 20rem;
    }
    
}
```

### Useful resources

- [resource 1](https://stackoverflow.com/questions/15685666/changing-image-sizes-proportionally-using-css) - This helped me with how to resize am image.


## Author

- Website - [Melinda Zhang](https://www.melinda-zhang.com)
- Frontend Mentor - [@Melinda Zhang](https://www.frontendmentor.io/profile/MelindaZhang2020)
- Twitter - [@melindazhang4](https://www.twitter.com/melindazhang4)
