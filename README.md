# Frontend Mentor - Social links profile

![Design preview for the Social links profile coding challenge](./preview.jpg)

# Frontend Mentor - Social links profile solution

This is my solution to the [Social links profile challenge](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).  
The challenge was to build a responsive social profile card with links and proper hover states.

## Table of contents
- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

---

## Overview

### The challenge
Users should be able to:
- See hover and focus states for all interactive elements
- View the layout properly on different screen sizes

### Screenshot
![](./screenshot.jpg)

### Links
- Solution URL: [Add here](https://your-solution-url.com)  
- Live Site URL: [Add here](https://your-live-site-url.com)  

---

## My process

### Built with
- Semantic **HTML5**
- **CSS custom properties**
- **Flexbox**
- **Mobile-first workflow**

### What I learned
I practiced:
- Using **CSS variables** for colors  
- Creating a **neumorphism-inspired card shadow**  
- Building a responsive **centered card layout with flexbox**  
- Styling hover states to make buttons interactive  

## Snippet I liked:
```css
.buttons a {
  background-color: var(--Grey-700);
  width: 15rem;
  border-radius: 0.5rem;
  padding: 12px;
  margin: 10px 0;
  text-align: center;
  font-weight: bold;
  color: white;
  transition: 0.3s ease-in-out;
}

.buttons a:hover {
  background-color: var(--Green);
  color: black;
}
```
## Continued development

In the future, I want to:

Replace <a><button></button></a> with semantic <a> buttons

Add animations for smoother hover states

Improve accessibility with ARIA labels

## Author

Frontend Mentor – @Mr-Prince2
