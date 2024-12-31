# Frontend Mentor - QR code component

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component](#frontend-mentor---qr-code-component)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshots](#screenshots)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### Screenshots

**Desktop**
![desktop version](/images/screenshot-1.png)

**Mobile**
![mobile version](/images/screenshot-2.png)

### Links

- [Solution URL](https://github.com/aigle-levant/qr-code-display)
- [Live Site URL](https://qr-code-display-beta.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- SASS
- Flexbox
- Responsive web design
- Mobile-first workflow

### What I learned

Centering a div and its content is HARD! I tried with the following snippets :

```scss
body
{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    //misc styles
}
.card-wrapper
{
    padding: 1rem 0;
    max-width: 90vw;
    max-height: none;
    //misc styles
}
```

My website is built mobile-first to avoid issues with size of content and containers. To size it for larger screens, I used the following snippet :

```scss
@media (min-width: 1000px)
{
    .card-wrapper
    {
        padding: 20px;
        max-width: 36vw;
    }
}
```

### Continued development

I'll add a button to toggle dark mode and resize it properly for desktops. I'll also add a link to the image so that if you click or tap it, it will take you to the frontendmentor challenge.

### Useful resources

- [Centering a div](https://www.joshwcomeau.com/css/center-a-div/) - This helped me when I was struggling to center the card.

## Author

- GitHub - [aigle-levant](https://github.com/aigle-levant)
- Frontend Mentor - [@aigle-levant](https://www.frontendmentor.io/profile/aigle-levant)

## Acknowledgments

Although I did this project entirely by myself, I thank @itsdarkstar and @gracesnow from the frontendmentor discord for helping me out with responsive web design.
