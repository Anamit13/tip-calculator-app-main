# Frontend Mentor - Tip calculator app solution

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

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Calculate the correct tip and total cost of the bill per person

### Screenshot

![](./screenshot.jpg)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
1. After getting the task first I checked the design part that what I need to develop.
2. Then I started the HTML part because according to me if the structure is ready than our 50% work is done. So, I completd the structure part.
3. Then I started with applying CSS to the code with the help of style - guide which is given. For font I has used the link of googlefonts.
4. For CSS I had also took some refrences from internet.
5. After that I took the functionality part using javascript. 

### Built with

- HTML5
- CSS3
- Mobile-first workflow
- JavaScript

### What I learned

In this project I had learned many things in HTML, CSS and JavaScript like some properties of CSS for correct positioning of any element and functions of JavaScript.



```html
<p>Total <br/> <span>/ person</span></p>
```
```css
.inputbill > input {}

.inputbill > input:focus {
    outline: none;
}

.amount > p > span {
    opacity: 0.5;
}
```
```js
button.forEach(btn => {
            btn.addEventListener('click',handleClick)
        });
button.forEach(btn => {
                btn.classList.remove('active')}
if(input.value.includes(',')){
                input.value.replace(',','.')
            }
```

### Continued development

In this project I came to know various different techniques in CSS by which we can easily place the element where we want so I want to get perfection in these techniques because it is very important that the web app should look appealing so right now I leanred a little part of it.


### Useful resources

- [Codepen](https://codepen.io/cphemm/pen/reNwWd) - This helped me to get the functionality of a tip calculator
- [W3Schools](https://www.w3schools.com/cssref/css3_pr_all.asp) - This helped me to check the different properties of CSS in HTML
- [W3Schools](https://www.w3schools.com/js/) - This helped me to check the different functions of JavaScript

## Author

- Website - [Anannya Mital](https://www.linkedin.com/in/anannya-mittal-520a721a0/)

## Acknowledgments

First of all thank you Muniversity team to give me this project from which I learnt a lot of things in HTML, CSS and JavaSript. Initially I was very nervous that how I am going to do that then I saw some existing projects on it and start getting some insights and started the project. The project is not similar to what was required but yes I had given my best in these 2 days to make it possible.