# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
- Desktop 1440px
  ![FireShot Capture 036 - 3 column preview card - 1040px](https://github.com/kudos2Shef/3-column-preview-card-component/assets/16985060/e50207f3-21c2-4f19-b292-ac5eb914f838)

- Mobile 375px

  ![FireShot Capture 038 - 3 column preview card - 375new](https://github.com/kudos2Shef/3-column-preview-card-component/assets/16985060/4d07f717-df4b-4ae4-a585-84cd1c08bc3e)

### Links

- Solution URL: [solution URL ](https://github.com/kudos2Shef/3-column-preview-card-component)
- Live Site URL: [live site URL](https://kudos2shef.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Media Query



### What I learned

Used media query to make it responsive in different widths of website. Implemented Flexbox for alignments and CSS grid for column in card component, applicable in different sizes of wwbbsite making it responsive.CSS variables for color and background color component.  


```css
.column-card {
  grid-template-columns:repeat(3,1fr);
}
.info:nth-of-type(1){
	background-color: var(--Bright_orange);
	border-top-left-radius: 10px;
	border-bottom-left-radius: 10px;

}
.info:nth-of-type(2){
	background-color: var(--Dark_cyan);

}
.info:nth-of-type(3){
	background-color: var(--Very_dark_cyan);
	border-top-right-radius: 10px;
	border-bottom-right-radius: 10px;

}
@media (max-width:600px){
.column-card{
grid-template-columns:repeat(1,1fr);
}
```



## Author

- Website - [@kudos2shef](https://github.com/kudos2Shef)
- Frontend Mentor - [@kudos2shef](https://www.frontendmentor.io/profile/kudos2Shef)

