# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview


### 📸 Screenshots
<div align="center">
  
| Desktop View | Mobile View |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/97a726b4-94a5-4f56-ac9e-80d513ad0252" width="600"> | <img src="https://github.com/user-attachments/assets/6cc3276c-f02c-4e8a-b0b5-8b89458fa6c9" width="200"> |
  
</div>

### Links

- Solution URL: [Solution FrontEnd](https://your-solution-url.com)
- Live Site URL: [Live Server](https://eduarddo-sm.github.io/recipe-page-main/)

## My process

To ensure a smooth workflow, I develop the project section by section. I start at the top with the image and finish with the Nutrition table, committing each styled component via the terminal.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

To style certain things, like the marker color, I had to learn new properties. I also had to learn how to break words and the nth-child properties from tables. The properties listed below are ones I've never used before.

Propertiers:
- overflow-wrap: break-word;
- li::marker;
- list-style-position: inside;
- tr:nth-child < For the first child of a table
- td:nth-child(2) < For the second child of a data table

```css
h1, h2, h3 {
    overflow-wrap: break-word;
}
```

```css
.preparation-time li::marker {
    color: hsl(332, 51%, 32%);
}
```

```css
.preparation-time ul {
    list-style-position: inside;
    line-height: 2.0;
}
```

```css
table tr:nth-child(1){
    border: none;
}
```

## Author

- Frontend Mentor - [@Eduarddo-sm]([https://www.frontendmentor.io/profile/yourusername](https://www.frontendmentor.io/profile/Eduarddo-sm))
