# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/screencapture-gregarious-gelato-ce6538-netlify-app-2022-07-04-22_08_26.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/montyaction/profile-card-component/blob/main/README-template.md)
- Live Site URL: [Add live site URL here](https://gregarious-gelato-ce6538.netlify.app/)

## My process

### Built with

- HTML
- [Sass](https://sass-lang.com/) - Css preprocesor
- Flexbox

### What I learned

I learned to use the after and before in set background two image.

```scss
    .card::before,
    ::after {
        content: "";
        position: absolute;
        z-index: -1;
        width: 980px;
        height: 980px;
        background-repeat: no-repeat;
        background-size: 100%;
    }

    .card::before {
        bottom: 100%;
        right: 100%;
        transform: translate(20%, 20%);
        background-image: url(./images/bg-pattern-top.svg);
    }

    .card::after {
        top: 100%;
        left: 100%;
        transform: translate(-20%, -20%);
        background-image: url(./images/bg-pattern-bottom.svg);
    }
```
### Continued development
For future projects I need to focus on using more advanced CSS to create effects.

### Useful resources

- [W3 School](https://www.w3schools.com/default.asp) - This helped me for my basic knowledge. I really liked this pattern and will use it going forward.
- [How To Create an Overlay Image Icon](https://www.w3schools.com/howto/howto_css_image_overlay_icon.asp) - This helped me to add an overlay to the image on hover.
- [Using only CSS, show div on hover over another element](https://stackoverflow.com/questions/5210033/using-only-css-show-div-on-hover-over-another-element) - This Stack Overflow question helped me to figure out how to show the view icon on hover.


## Author

- Portfolio - [montyaction](https://blissful-banach-06fb18.netlify.app/
)
- Frontend Mentor - [@montyaction](https://www.frontendmentor.io/profile/montyaction)
- Twitter - [@MontyKanwar19](https://twitter.com/MontyKanwar19)
- Instagram - [frontend_action](https://www.instagram.com/frontend_action/)

