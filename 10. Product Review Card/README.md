# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Desktop-view.png)
- Desktop View
![](./images/mobile-view.png)
-Mobile View

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Google Fonts

### What I learned

My biggest learning from this project is to make project responsive to the screen size.

Here is the code sinppet of that:

```css
@media screen and (min-width: 550px) {
    .card{
        /* border: 5px solid red; */
        display: flex;
        flex-direction: row;
        max-width: 480px;
        margin:20vh auto;
    }
    .mobile-img{
        display: none;
    }
    .desktop-img{
        display: flex;
        border-top-left-radius: 15px;
        border-bottom-left-radius: 15px;
        max-width: 50%;
        max-height: 100vh;
    }
    h1{
        padding-right: 20px;
    }
    
}
```






### Useful resources

- [Resource](https://freecodecamp.org) - There is no dearth of resources available on freecodecamp. We just need to utilize it.


## Author

- Website - [Raghu Anand](https://raghuaanand.github.io/)
- Frontend Mentor - [@raghuaanand](https://www.frontendmentor.io/profile/raghuaanand)
- Twitter - [@raghuaanand](https://www.twitter.com/raghuaanand)

