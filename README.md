# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### Screenshot

<img src="https://github.com/luizarilo/qrcode-component/blob/master/images/screenshot.png" alt="My cool logo"/>




### Links

- Solution URL: https://www.frontendmentor.io/solutions/responsive-qrcode-card-using-css-flexbox-ooBKTEOONg
- Live Site URL: https://qrcodecard-challenge.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

In this project I was able to practice and learn how to use CSS Flexbox to align itens and container in the internet page.



```css
  .card-content{
    display: flex;
    min-height: 100vh;
    align-items: center;
    justify-content: center;
    background-color: hsl(212, 45%, 89%);

}

```
I also practiced how to make a responsive page using media query

```css
@media (max-width: 375px){
    .qrcode-container{
        flex-basis: 250px;
        height: 400px;
        display: flex;
        justify-content: center;

    }

```


### Continued development

In future projects I intend to continue practicing HTML, CSS and I want to add JavaScript.




## Author

- Frontend Mentor - [@luizarilo](https://www.frontendmentor.io/profile/luizarilo)
- LinkedIn - (https://www.linkedin.com/in/luiz-arilo)
