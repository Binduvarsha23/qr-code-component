# Frontend Mentor - QR code component solution

![Design preview for the QR code component coding challenge](./design/desktop-preview.jpg)

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [GitHub Repository](https://github.com/Binduvarsha23/qr-code-component)
- Live Site URL: [Live Demo](https://Binduvarsha23.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

During this project, I practiced using:

- Flexbox for centering content vertically and horizontally
- CSS custom properties for managing colors and other repetitive values
- Applying box shadows to create a subtle depth effect

Here is a sample of the code I'm particularly proud of:

```html
<div class="card">
    <img src="image-qr-code.png" alt="QR Code">
    <div class="text">
        <h1>Improve your front-end skills by building projects</h1>
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
</div>
```

```css
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: hsl(212, 45%, 89%);
    font-family: 'Outfit', sans-serif;
}

.card {
    background: hsl(0, 0%, 100%);
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 90%;
    text-align: center;
    max-width: 320px;
    padding: 20px;
    box-sizing: border-box;
}

.text {
    padding: 20px;
}

.card img {
    width: 100%;
    border-radius: 10px;
}

.card h1 {
    font-size: 22px;
    color: hsl(218, 44%, 22%);
    margin: 20px 0;
}

.card p {
    color: hsl(220, 15%, 55%);
    font-size: 15px;
    margin: 0;
    padding-bottom: 10px;
}
```

### Continued development

For future projects, I want to focus on:

- Improving my workflow with design tools like Figma or Sketch
- Enhancing my CSS skills, particularly with animations and transitions
- Learning more about responsive design principles

## Author

- Frontend Mentor - [@Binduvarsha23](https://www.frontendmentor.io/profile/Binduvarsha23)
