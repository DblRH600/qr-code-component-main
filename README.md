# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

![](./qr_code_femc.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<section class="card-content">
      <img class="card-qr-code" src="images/image-qr-code.png" alt="qr-code for Frontend Mentor."/>
    <div class="card-qr-comments">
      <p class="card-main-comment">
        Improve your front-end skills by building projects
      </p>
      <p class="card-secondary-comment">
        Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
      </p>
    </div>
  </section>
```
```css
.card-main-comment {
  font-weight: 700;
  font-size: 22px;
  line-height: 120%;
  letter-spacing: 0px;
  text-align: center;
  color: #1f314f;
}
.card-secondary-comment {
  font-weight: 400;
  font-size: 15px;
  line-height: 140%;
  letter-spacing: 0.2px;
  text-align: center;
  color: #68778d;
}
.card-secondary-comment:hover {
  background-color: #68778d;
  color: hsl(0, 0%, 100%);
  backdrop-filter: blur;
}
```

### Continued development

I learned how to utilize figma to develop wireframes and utilize the developer tools to understand and structure the html and css code.
I need to do continued research to understand how/when to use flex elements vs grid elements; and how to implement media queries to adapt to screen sizes.

### Useful resources

- [Video: Figma Tutorial: Device Frames and Scrolling](https://www.youtube.com/watch?v=ST6DOO11zuA) - While in an indirect relation to the challenge, this tutrial helped me to gain a deeper understanding of Frames, Components, and Prototyping in figma.

