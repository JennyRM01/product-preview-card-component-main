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
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Mobile Solution](./images/Screenshot%20-mobile.png)
![Desktop Solution](./images/Screenshot-dekstop.png.jpg)

*(Add your own screenshot here before pushing — take one on both mobile and desktop width, save it in your project folder as `screenshot.jpg`.)*

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
- `<picture>` element for responsive, art-directed images

### What I learned

I needed to create a responsive card that works well on both mobile and desktop, with a hover state on the button and two prices shown (the current price and the original, crossed-out price). The project was mostly focused on building a site that's genuinely responsive for both mobile and desktop, which I did using media queries.

Most of what I actually learned came from debugging, not from the parts that just worked right away. This challenge taught me when to use `<picture>` and `<source>` for swapping images at different screen sizes.

The biggest issue I ran into was the desktop version of the image — it kept refusing to take up its full size. The way I fixed it was realizing my mobile image rule was using `max-height`, and that was still applying on desktop even after I set a new value there. I had to explicitly set `max-height: none` in my desktop media query so it would override the mobile rule and let the image actually reach its full height.

### Continued development

I just want to keep practicing overall — little by little I'm noticing I'm getting better and faster at coding, and I want to keep building on that. A few specific things I want to get better at:

- Get faster at predicting how flex and grid will size things, instead of having to debug it after it's already wrong
- Get quicker at spotting `height` vs `max-height` type mistakes, since this one cost me a lot of time
- Practice reading CSS more carefully for small typos (like a missing `.` on a class name), since that was the cause of a bug I didn't catch right away

### AI Collaboration

I used Claude mostly for debugging, not to write the code for me. I specifically asked it not to just give me the answer when I got stuck. I ran into a few real bugs — my desktop image not taking its full height, a media query getting silently overridden because of where it sat in the file, and some spacing that didn't match the design. Instead of handing me the fix, it walked me through questions until I found the cause myself, like realizing `max-height` doesn't force a size the way `height` does.

What worked well was having to reason through the bug instead of just getting the answer — I actually understood *why* it broke, not just what fixed it. Next time I'd like to get faster at catching my own typos before asking for help.

## Author

- Frontend Mentor - [@JennyRM01](https://www.frontendmentor.io/profile/JennyRM01)
- GitHub - [@JennyRM01](https://github.com/JennyRM01)



- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)
