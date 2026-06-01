# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

The project required building a clean, responsive four-card feature section based on a provided design. It focuses on executing an advanced multi-layout switch between mobile, tablet, and desktop views using CSS Grid template areas, handling semantic HTML structures for better accessibility, and balancing typographic weight variations within the primary headings.

### Screenshots

Desktop version
![](.//images/desk.png)
Tablet version
![](.//images/tablet.png)
Mobile version
![](.//images/mob.png)

### Links

- Live URL: [Add solution URL here](https://bartekluczak.github.io/four-card-feature/)
- Solution Site URL: [Add live site URL here](https://github.com/bartekluczak/four-card-feature)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project was a great way to practice responsive layouts and clean code structure. I learned how to build a flexible system that looks good on any screen size without overcomplicating the code.

Here are my main takeaways:

1. **Better Layout Control with CSS Grid:** I learned how to use `grid-template-areas` to literally draw the website layout in my CSS. Designing the tablet version taught me how to change the grid columns so that the cards stay close together without creating massive, ugly gaps in the middle of the screen.

2. **Proper Use of HTML5 Semantics:** I focused on making the markup meaningful instead of just using generic `<div>` tags everywhere. I learned to wrap the entire feature block in a `<section>` tag to define it as a distinct part of the page, and I used the `<article>` tag for each individual card to treat them as self-contained, independent pieces of content.

3. **Organized CSS with BEM Architecture:** I used the BEM naming system to keep my CSS classes organized. This made it very easy to split the main header into two distinct parts, allowing me to style one line with a very light font weight and the other with a bold font weight while making sure they stack correctly on mobile.

4. **Cleaner Code by Moving SVGs:** Instead of pasting hundreds of lines of messy SVG code directly into my HTML, I moved the icons into separate files and loaded them through image tags. This kept my main HTML file clean, short, and very easy to maintain.

## Author

- Github - [Bartek Łuczak](https://github.com/bartekluczak)
- Frontend Mentor - [@bartekluczak](https://www.frontendmentor.io/profile/bartekluczak)
