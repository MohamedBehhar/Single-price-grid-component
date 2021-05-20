# Frontend Mentor - Single price grid component solution
 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

For this challenge I tried to make my code as dry as possible.
i used the CSS grid to creat the card layout, the i position each box using grid area.
I used autofit and minmax properties to make my design responsive.


```css
.card{
    display: grid;
    grid-template-columns: repeat( auto-fit , minmax(200px, 1fr));
}
```


### Continued development

I'll continue to make more designs using grids until I'll be more confortable using this property.

### Useful resources

- [Example resource 1](https://css-tricks.com/auto-sizing-columns-css-grid-auto-fill-vs-auto-fit/) - this help to understand the difference between the autofill and the autofit property and how I can use it to make the grid responsive. 

## Author

- Frontend Mentor - [@Mohamed BEHHAR](https://www.frontendmentor.io/profile/yourusername)
- Linkedin - [@Mohamed BEHHAR](https://www.linkedin.com/in/mohamed-behhar-332025155/)


## Acknowledgments

I just wanna thank  Frontend Mentor for this challenge.


