# Frontend Mentor – Advice Generator App Solution

This is a solution to the [Advice Generator App challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/advice-generator-app-QdUG-13db).
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## 📋 Table of contents

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

## 📖 Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements
- Generate a new piece of advice by clicking the dice button
- Fetch random advice from an external API

---

### Screenshot

![Screenshot of the Advice Generator App](./preview.jpg)

---

### Links

- Live Site URL: (https://juanfeoru.github.io/advice-generator-app/)

---

## 🛠️ My process

### Built with

- Semantic HTML5
- Tailwind CSS
- Mobile-first workflow
- Vanilla JavaScript
- Fetch API
- Advice Slip API

---

### What I learned

In this project, I reinforced several important frontend concepts:

- Handling asynchronous operations using `async/await`
- Fetching data from an external API and handling errors properly
- Managing UI states such as loading and disabled buttons
- Improving user experience with visual feedback during API requests
- Building responsive layouts using Tailwind CSS utility classes
- Using the `<picture>` element to serve responsive images efficiently

Example of the API handling logic:

```js
const response = await fetch('https://api.adviceslip.com/advice', {
  cache: 'no-store',
});

const { id, advice } = (await response.json()).slip;
```

### Continued development

In future projects, I want to:

- Improve accessibility (ARIA attributes and keyboard interactions)
- Explore animations and micro-interactions for better UX
- Practice more projects using external APIs
- Continue improving code structure and maintainability

## Author

- Frontend Mentor - [@juanfeoru](https://www.frontendmentor.io/profile/juanfeoru)
- Twitter - [@purpuraaaaaaa](https://www.twitter.com/purpuraaaaaaa)
