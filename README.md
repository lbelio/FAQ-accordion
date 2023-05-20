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

- Solution URL: [Solution!](https://github.com/lbelio/FAQ-accordion/blob/main/index.html)
- Live Site URL: [Site!](https://lbelio.github.io/FAQ-accordion/)

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

To overcome this, I decided to follow along with a CoderCoder video tutorial. Although it's generally advised not to rely too heavily on code-alongs, I took notes while following along to ensure I gained a deeper understanding. I learned a great deal from CoderCoder's approach.

Firstly, I love the fact that one of the first things she says is that she has no idea how to make an accordion, so she reverse engineers a bootstrap example and applies it to this project. (definitely keeping this tip for future use).

Here are some major takeaways:

Understanding the purpose of ::after and ::before pseudo-elements.
Improved understanding of sibling and parent relationships in CSS.
Proper usage and understanding of class specificity.
Approaching a project and establishing a workflow.
Troubleshooting techniques. CoderCoder spent considerable time working through the expansion and collapse functionality of the accordion using JavaScript, which I plan to revisit for better comprehension.

### Continued development

Moving forward, I will focus on further developing my CSS skills, particularly regarding positioning and the usage of properties like position and display. I also intend to gain a better understanding of transform: translate and experiment with it more.

The JavaScript implementation in this project was initially confusing, particularly the seemingly complex way of expanding and collapsing each accordion section. I will dedicate time to exploring and experimenting with this aspect.

Additionally, I plan to revisit properties like :focus and focus-visible to deepen my understanding and leverage their functionality in future projects.

### Useful resources

- [CoderCoder Youtube Channel](https://www.youtube.com/watch?v=sr94O6Y5NEA&ab_channel=CoderCoder) - This is the CoderCoder video i followed.
