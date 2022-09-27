# Frontend Mentor - Single-page design portfolio solution

This is a solution to the [Single-page design portfolio challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Navigate the slider using either their mouse/trackpad or keyboard

### Screenshot

![Screenshot of desktop version](./Screenshot-desktop.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/ghintema/FrontendMentor_Sunnyside-agency-landingpage.git)
- Live Site URL: [Add live site URL here](https://ghintema.github.io/FrontendMentor_Sunnyside-agency-landingpage/)

## My process
- Design analysis: extracting font-styles and colors from figma-file.
- defining CSS variables
- defining CSS utility classes
- writing markup, including styles via utility classes
- writing layout for mobile design
- writing layout for desktop


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Custom CSS Utility classes for fonts and style for max mantainability 
- Flexbox
- Mobile-first workflow
- No frameworks used.


### What I learned

- working with pseudo-elements to make underlining 
- kombining :after with :hover
- liquid responsiveness 
- changing the order of elements in a flex-box

#card-4 .learn-more:after        {background-color:#ffdbd4;}
#card-2 .learn-more:hover::after,
#card-2 .learn-more:active::after  {background-color:#fad400}
#card-4 .learn-more:hover:after,
#card-4 .learn-more:active::after  {background-color:#fe7766}


### Continued development


## Author

Harm Intemann, Bolivia, July 2022

## Acknowledgment

System of utility classes according to Kevin Powell.

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```





