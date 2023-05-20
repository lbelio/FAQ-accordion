# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam).

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![Desktop screenshot](FAQ%20card%20desktop.png)
![Mobile screenshot](FAQ%20card%20mobile.png)

### Links

- Solution URL: [Solution!](https://github.com/lbelio/faq-accordion-card-main.git)
- Live Site URL: [Site!](https://lbelio.github.io/faq-accordion-card-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I selected this challenge as my first challenge which includes Javascript. Little did I know that the real struggle was going to be the CSS! At first I tackled the project as I normally would, laying out the HTML foundations, then moving on to CSS. Of course, I did not expect this project to be easy breezing seeing as this is only my 3rd attempt at a FrontEndMentor challenge, however, it was quite the surprise to discover that something as simple as a FAQ card could be so finicky!

I finally understood why there are so many memes related to positioning things with CSS. The SVG elements in this challenge turned out to be a real nemesis. While I did attempt at positioning the orange box over exactly where it needed to go, and I tried to find the correct way to
add the shadow behind the main SVG element, I realised that I'll learn a lot more if I give myself a chance to learn from someone a lot more experienced.

So I found a CoderCoder video on this particular project and I chose to code-along with her. I am well aware that many people recommend NOT to rely on code-alongs and I agree, which is why I chose to make notes while coding along. I learned an immense amount from CoderCoder.

Firstly, I love the fact that one of the first things she says is that she has no idea how to make an accordion, so she reverse engineers a bootstrap example and applies it to this project. (definitely keeping this tip for future use).

It also helps seeing someone's approach to a new projects and their workflow. I seem to struggle to visualise how to approach a project so following along gives me a better idea on how to do so.

Major things i learned:

- Understand the purpose of ::after, ::before.
- Better understanding of siblings and parents.
- The usage of class specificity and its proper syntax.
- a way to approach a project and general workflow.
- troubleshooting! this was major for me. It really helps seeing how professionals go about working out an issue. CoderCoder spends a long time working out the accordion expanding and collapsing using Javascript. I will have to look back to this part to make sure i fully understand.

### Continued development

I will continue to work with CSS, specifically positioning and using properties like: position and display. Need to gain better understanding of their proper usage. Transform: translate is another property I'd like to get to grips with more as well.

The Javascript of this project was rather confusing with the seemingly overly complicated way to open up each segment of the accordion. I will definitely play around with that.

I should also revisit :focus and focus-visible properties.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [CoderCoder Youtube Channel](https://www.youtube.com/watch?v=sr94O6Y5NEA&ab_channel=CoderCoder) - This is the CoderCoder video i followed.
