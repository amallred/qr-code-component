# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./design/finalLargeScreen.PNG)
![](./design/finalMobileScreen.PNG)

### Links

- Solution URL: [https://github.com/amallred/qr-code-component/tree/main](https://github.com/amallred/qr-code-component/tree/main)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

I had never used imported fonts before, so that presented a challenge. The solution I found was linking it directly in the html file like this:

```    
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
<style>
  html {
    background-color: hsl(212, 45%, 89%);
    font-family: 'Outfit', sans-serif;
  }
</style>
```
I also converted the hsl colors to rgba to apply the box shadow. To accomplish this, I used a built-in extension.


This was a fairly straightforward challenge, though I enjoyed my first foray into Frontend Mentor!

### Continued development

I want to challenge myself to start incorporating grid and flexbox more confidently in my designs. (I did not include those here because the layout was very straightforward.)

I'd also like to continue practicing with semantic HTML. For instance, I was unsure how to use the `<figure>` tag as it changed some of the default styling. 

### Useful resources

- [Box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - This helped me incorporate the blurred box-shadow and know what variables to tinker with until I got what I was looking for.

## Author

- Website - [Amanda Allred](https://github.com/amallred/)
- Frontend Mentor - [@amallred](https://www.frontendmentor.io/profile/amallred)
- [LinedIn](https://www.linkedin.com/in/amallred/)

## Acknowledgments

I tackled this one on my own, but I want to thank Kevin Powell for introducing me to this awesome resource full of frontend challenges!