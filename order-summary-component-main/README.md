# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](##overview)

  - [The challenge](###The-challenge)

  - [Screenshot](###Screenshot)

  - [Links](###links)

- [My process](##My-process)

  - [Built with](###built-with)

  - [What I learned](###what-i-learned)

  - [Useful resources](###useful-resources)

- [Author](##author)

## Overview

### The-challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![[]](D:\frontend-challenges\order-summary-component-main\screenShots\screen1.png)

![[]](D:\frontend-challenges\order-summary-component-main\screenShots\screen2.gif)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My-process

### Built-with

- HTML divs

- CSS custom properties

- flex

- Mobile-first workflow

**No framework or library used in this project**

### What-I-learned

I learned from this project how to center a div LOL.
I learned how to use div's classes to modify a part of the webpage, and learned how to import external fonts from the web in CSS, also how to animate few things like rotating the music icon, or the text's underline using only CSS.

##### The rotate animation i used in my CSS:

```css
.rotate {
  -webkit-transition-duration: 0.8s;
  -moz-transition-duration: 0.8s;
  -o-transition-duration: 0.8s;
  transition-duration: 0.8s;
  -webkit-transition-property: -webkit-transform;
  -moz-transition-property: -moz-transform;
  -o-transition-property: -o-transform;
  transition-property: transform;
  overflow: hidden;
}

.rotate:hover {
  -webkit-transform: rotate(360deg);
  -moz-transform: rotate(360deg);
  -o-transform: rotate(360deg);
  transform: rotate(360deg);
}
```

<br>

##### The Gradient Underline under the text:

```css
.fancy-line {
  color: var(--neutral-Desaturated);
  background-image: linear-gradient(90deg, red, blue);
  background-size: 0% 3px;
  background-repeat: no-repeat;
  background-position: left bottom;
  text-decoration: none;
  transition: background-size 300ms ease;
}

.fancy-line:hover {
  background-size: 100% 3px;
}
```

##### Custom variables i made to use in my CSS:

```css
:root {
  /* Font Size: 16px */
  /* Font family: Red Hat Display */
  /* Weight: 500, 700, 900 */
  --primary-pale: hsl(225, 100%, 94%);
  --primary-bright: hsl(245, 75%, 52%);
  --neutral-pale: hsl(225, 100%, 98%);
  --neutral-Desaturated: hsl(224, 23%, 55%);
  --neutral-dark: hsl(223, 47%, 23%);
}
```

<br>

### Useful-resources

- [How to add pressed effect on a button](https://www.geeksforgeeks.org/how-to-add-a-pressed-effect-on-button-click-in-css/) - This helped me for adding a pressed effect to the buttons i have. I really liked this pattern and will use it going forward.

![[]](D:\frontend-challenges\order-summary-component-main\screenShots\screen3.gif)

- [How to spin a Logo / Icon in css](https://stackoverflow.com/questions/27874302/how-to-spin-the-logo-360-degrees-using-css#27874531) - This is an amazing article which helped me creating a spinning icon when i hover over it. I'd recommend it to anyone still learning this concept.

![[]](D:\frontend-challenges\order-summary-component-main\screenShots\screen4.gif)

## Author

- LinkedIn - [Nibras Shami](https://www.linkedin.com/in/nibras-shami-4bb544209/)

- Frontend Mentor - [@vreoo](https://www.frontendmentor.io/profile/vreoo)

- Twitter - [@NibrassShami](https://twitter.com/NibrassShami)
