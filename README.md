# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

This is an NFT Preview component card, even though it might seem easy, it was a
little tricky because I tried to implement more css tricks to make some effects
work properly.

### Screenshot

![](./images/Screenshot-desktop.png)

### Links

- Solution URL: [GitHub](https://github.com/newbpydev/02-nft-preview-card-component-main)
- Live Site URL: [Live Site](https://mystifying-yalow-ba4510.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Grid

### What I learned

I have learned on this project that I should not be afraid of web design. When
you can start to see the connection between the end goal and what you have been
given you can see some connection and adapt. I used the paragraph size to help
me get a general picture of the size that I needed to use for the rest of the document.

```css
.card-img-top-overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);

  background-color: hsl(178, 100%, 50%);
  padding: 15rem;
  opacity: 0;
  cursor: pointer;
  transition: all 0.3s;
}

.card-img-top:hover .card-img-top-overlay {
  opacity: 0.5;
}
```

### Continued development

For future development, I will continue to train using the flexbox and combine
it with the grid.

### Useful resources

- [Google Fonts](https://fonts.google.com/specimen/Outfit?query=outfit) - This was the font used in the project.
- [CSSTricks](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) - This is an amazing article which helped me finally understanding the @media
  for mobile and the importance of creating a more responsive site.

## Author

- Website - [Juan Gomez](https://www.newbpydev.com)
- Frontend Mentor - [@newbpydev](https://www.frontendmentor.io/profile/newbpydev)
- Twitter - [@Newb_PyDev](https://twitter.com/Newb_PyDev)

## Acknowledgments

The project may not be perfect compared to my sensei @jonasschmedtman but I need
to thank him because he has shown me the ropes and now I am a confident web
designer.

