# Frontend Mentor - Clipboard landing page solution

We’re a group called Arsenal and we started learning HTML/CSS about five weeks ago. This challenge from [Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9)

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Make a page where:

- layout adjusts for mobile and desktop
- buttons and links show hover states

### Links

- Live Site URL: [coming soon](https://afrxcan.github.io/Clipboard-Landing-Page/)

## Our process

### Built with

- Semantic HTML5
- CSS for layout and colors
- flexbox to line up items
- media queries for responsiveness
- mobile‑first workflow

### What we learned

We figured out how flexbox works, especially using `justify-content` and `align-items`. It also helped us to write more semantic tags like `<header>` and `<footer>`.

```html
<nav>
  <ul class="nav-links">
    <li><a href="#">Features</a></li>
    <li><a href="#">Pricing</a></li>
  </ul>
</nav>
```

```css
.nav-links {
  display: flex;
  gap: 1rem;
}
@media (max-width: 600px) {
  .nav-links {
    flex-direction: column;
  }
}
```

### Continued development

We want to practise CSS grid next and try adding some JavaScript to make a hamburger menu. Also need to get better at choosing breakpoints.

### Useful resources

- [MDN Flexbox guide](https://developer.mozilla.org/docs/Web/CSS/CSS_Flexible_Box_Layout) – helped me remember what each property does.
- [W3Schools media queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) – gave me easy examples when I was confused.

### AI Collaboration

We used GitHub Copilot and Google Gemini for small hints and asked ChatGPT about a couple of things like media query syntax. The suggestions were fine but we still had to figure out most of it ourselves.

## Author

This project was completed as a group named **Arsenal**. Each section of the HTML file includes comments with the contributor's name.

Group members:

- [Ernest Gitonga]
- [ELijah Mumo]
- [Billton Yusuf]
- [Ahmed Amin]

## Acknowledgments

Big thanks to the Frontend Mentor community for the challenge and to everyone in our group for working together. Seeing other solutions helped us brainstorm ideas.

