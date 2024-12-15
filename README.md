# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learnt a lot about flexbox, hover properties and responsive mobile designs with @media.


```html
<p>Published <time datetime="2024-12-14" pubdate>December 14, 2024</time></p>
```
```css
.card-component{
  padding: 1rem;
  border-radius: 20px;
  background-color: hsl(0, 0%, 100%);
  width: min-content;
  border: 1px solid black;
  box-shadow: 5px 10px 1px 2px black;

  transition-property: box-shadow, transform;
  transition-duration: 350ms;
  transition-timing-function: ease;
}

.card-component:hover h2{
  color: hsl(47, 88%, 63%);
}
```



### Continued development

I want to work on mobile first workflows in future projects and also work on my flexbox and grid layouts more


### Useful resources

- The Mozilla Developer Network and Web.dev were the most important resources I used by far. I use Claude.ai for editing one or two code snippets that I couldn't work out where the problem was.

## Author

- Frontend Mentor - [@Akintayo74](https://www.frontendmentor.io/profile/Akintayo74)
- Github - https://github.com/Akintayo74

