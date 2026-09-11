# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ)

## Table of contents

- [Frontend Mentor - Social links profile solution](#frontend-mentor---social-links-profile-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [github.com/rizanne-f/social-links-profile](https://github.com/rizanne-f/social-links-profile)
- Live Site URL: [rizanne-f.github.io/social-links-profile/](https://rizanne-f.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I reinforced my learnings from the previous project by relying more on relative units to improve the accessibility of the web page. I am also seeing more and more the importance of adjusting the spacing for desktop vs mobile designs in order to maximize the available space for content.
```css
@media screen and (min-width: 376px) {
    #social-links-profile { padding: 2.5rem; }
    #links > * { min-width: 300px; }
}
```
Initially, I made the the links using `<button>`, but I decided to turn them all into `<a>` as they are after all linking to external webpages then I used CSS styles to make them look like clickable buttons.
```html
<div id="links">
    <a href="https://github.com/rizanne-f">GitHub</a>
    ...
    <a href="https://www.instagram.com/rizanne.21/">Instagram</a>
</div>
```
This was also the first time that I included `focus` state along with `hover` to improve styles for tabbing navigation.
```css
#links > *:hover,
#links > *:focus {
    background-color: var(--Aqua);
    color: var(--Grey-900);
}
```
This time, I did not rely on the Figma file, I mainly guessed the  styling based on the reference images. I'm becoming more focused on what feels right while coding the styles instead of hyperfocusing on  pixel count.

### Continued development

Since the layout for the challenges I currently have are simple, I relied more on using flexbox. I think I am comfortable with flex now, but I am looking forward to using CSS grid to style more complex layouts in the near future.

## Author

- LinkedIn - [Rizanne Fernandez](https://ph.linkedin.com/in/rizanne-fernandez)
- Frontend Mentor - [@rizanne-f](https://www.frontendmentor.io/profile/rizanne-f)
- Twitter - [@rizanne621](https://www.twitter.com/rizanne621)