# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). It's useful resource to test your frontend skills.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the component depending on their device's screen size
-   See hover states for all interactive elements on the page
-   Hide/Show the answer to a question when the question is clicked

### Links

-   Solution URL: [https://github.com/andy-devs/faq-accordion-card](https://github.com/andy-devs/faq-accordion-card)
-   Live Site URL: [https://andy-devs.github.io/faq-accordion-card/](https://andy-devs.github.io/faq-accordion-card/)

## My process

### Built with

-   HTML5
-   CSS
-   Flexbox
-   Plain JavaScript for accordion

### What I learned

I learned how to make an accordion with JavaScript. Well, I just copied an example from [here](https://www.w3schools.com/howto/howto_js_accordion.asp) and customized it for my needs, but I think that counts.

```javascript
for (i = 0; i < acc.length; i++) {
	acc[i].addEventListener('click', function () {
		this.classList.toggle('active');
		var panel = this.nextElementSibling;
		if (panel.style.maxHeight) {
			panel.style.maxHeight = null;
		} else {
			panel.style.maxHeight = panel.scrollHeight + 'px';
		}
	});
}
```

### Continued development

I will continue to learn frontend development and I hope that I will get a chance to practice this pattern in bigger projects.

### Useful resources

-   [Simple example of accordion](https://www.w3schools.com/howto/howto_js_accordion.asp) - Helped me understand an accordion pattern. Recommend this one
