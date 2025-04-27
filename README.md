# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: 
- Live Site URL: https://bigboyemma20.github.io/social-links-profile-main/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned

While building this project, I learned how to:

- Correctly set up a responsive card layout using Flexbox.

- Work with CSS custom properties to maintain consistent colors throughout the project.

- Improve button interactivity with :hover and :active states.

- Structure a simple, clean, mobile-first design.

Here’s an example of using CSS custom properties and button styles:


```css
:root{
    --Green: hsl(75, 94%, 57%);
    --White: hsl(0, 0%, 100%);
    --Grey-700: hsl(0, 0%, 20%);
    --Grey-800: hsl(0, 0%, 12%);
    --Grey-900: hsl(0, 0%, 8%);
}

button:active{
    background-color: var(--Green);
    color: var(--Grey-900);
    font-weight: 700;
    cursor: pointer;
}

button:hover {
    background-color: var(--Green);
    color: var(--Grey-900);
    cursor: pointer;
  }
```


### Continued development

In future projects, I want to:

- Practice adding smooth transitions to hover states for even better UX.

- Experiment with adding animations to page elements.

- Learn more about accessibility best practices, like improving focus states and using ARIA labels.

### Useful resources

- CSS tricks- Flexbox guide (https://css-tricks.com/snippets/css/a-guide-to-flexbox/) 



## Author

- My Github - [Emmanuel Quarm](https://github.com/bigboyemma20)
- Frontend Mentor - [@bigboyemma20](https://www.frontendmentor.io/profile/bigboyemma20)
- Twitter - [@freshmanuel11](https://www.twitter.com/freshmanuel11)


