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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](images/screenshot_1.png)


### Links

- Live Site URL: [live Site](https://jacbfrancis.github.io/3-column-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

- I learnt how to use media queries to modify specific characteristics depending on the device's viewport. An example is shown below 

first design for desktop:

  ```css
  .sedans{
    background-color:hsl(31, 77%, 52%);
    flex-basis:260px;
    height:400px; 
    border-radius:10px 0px 0px 10px ;   
  }
```

applying media query for mobile:

```css
    @media(max-width:435px){
    .sedans{
        border-radius: 10px 10px 0px 0px;
    }
}
```
- i learnt how to use the :hover selector to target an element that the cursor or mouse pointer is hovering over. An example is shown below:
  
  ```css
        .btn-luxury:hover{
        background-color:hsl(179, 100%, 13%);
        color: hsl(0, 0%, 95%);
    }
  ```

- I also learnt how to use flexbox to to lay a collection of items out in one direction or another as well control spacing between items.

  ```css
         main{
    width: 80%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    margin: 100px auto 30px;
  }
  ```

### Continued development

- Build complex webpages using CSS flexbox and media queries.

### Useful resources

- [Responsive web design with media queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This is an amazing article which helped me understand Responsive Web design and Media queries. I'd recommend it to anyone still learning this concept.

- [Google fonts](https://fonts.google.com/) - This helped me to implement fonts on the website, so no trouble with font embedding.


## Author

- Twitter - [@jacobxavier_](https://twitter.com/jacobxavier_?t=YdJHQngdQYJVbC7mWspqDg&s=08)

