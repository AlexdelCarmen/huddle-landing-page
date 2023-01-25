# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Huddle Landing Page Solution](https://github.com/AlexdelCarmen/huddle-landing-page)
- Live Site URL: [Huddle Landing Page Site](https://alexdelcarmen.github.io/huddle-landing-page/)

## My process

Started off by building the mobile version of the site first, then I coded the desktop layout, and finished by properly sizing the social media icons on both layouts.   

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Improved my background image sizing: 


```css
#component {
  background-image: url("./images/bg-mobile.svg");
  background-size: 100%;
  background-repeat: no-repeat;
  background-position: center top;
  background-color: var(--primary-color1);
  max-width: var(--mobile-width);
  padding: 2rem;
  display: flex;
  flex-direction: column;
}

```

### Continued development

Need to keep practicing background image layout and proper sizing.

### Useful resources

- [W3Schools article on multiple backgrounds on an HTML element](https://www.w3schools.com/css/) - General CSS reference.


## Author

- Website - [Github Profile](https://github.com/AlexdelCarmen)
- Frontend Mentor - [@AlexdelCarmen](https://www.frontendmentor.io/profile/AlexdelCarmen)
- Mastodon - [cyborg_werewolf](https://mstdn.party/@cyborg_werewolf)

## Acknowledgments

To mom, I'll get you out one day.