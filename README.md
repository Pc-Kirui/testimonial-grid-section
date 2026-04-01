# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

![Design preview for the Testimonials grid section coding challenge](./preview.jpg)

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

The Testimonial grid section is a challenge from Frontend Mentor. Using the provided starter files, I implemented a solution that closely matches the original design specifications.

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

The following screenshots demonstrate the responsive layouts of Testimonial Grid Section. They were captured at 375px (mobile) and 1440px (desktop) viewports.

|                             Mobile (375px)                             |                             Desktop (1440px)                             |
| :--------------------------------------------------------------------: | :----------------------------------------------------------------------: |
| <img src="./design/mobile-design.jpg" width="250" alt="Mobile Layout"> | <img src="./design/desktop-design.jpg" width="500" alt="Desktop Layout"> |

### Links

- Solution URL: [Solution](https://github.com/Pc-Kirui/testimonial-grid-section)
- Live Site URL: [Live Preview](https://pc-kirui.github.io/testimonial-grid-section/)

## My process

### Built with

This application was built using HTML5 and CSS3, using Grid and Flexbox for markup and responsive styling.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Accessibility](https://img.shields.io/badge/accessibility-compliant-brightgreen?style=for-the-badge)

### What I learned

To complete this project, I transitioned from using purely Flexbox to mastering **CSS Grid** for complex layouts. I also prioritized **Web Accessibility (A11y)** by ensuring the project meets WCAG requirements.

Key takeaways:

- **CSS Grid Areas:** Implemented `grid-template-areas` for a readable and responsive desktop layout.
- **Accessible Color Contrast:** Maintained faded aesthetics using **HSL values** and opacity.
- **Screen Reader Support:** Used a visually hidden `<h1>` to provide proper heading hierarchy without affecting the visual design. This is demontrated by the code snippets below;

```
<h1 class="sr-only">Student Testimonials and Success Stories</h1>
```

```css
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border-width: 0;
}
```

### Continued development

- **Web Accessibility**: While I have learned the basics of web accessibility, I plan to explore more on the subject to ensure all projects I implement consistently meet the WCAG requirements.
- **CSS Architecture**: Intending to move beyond basic CSS and implement SASS, Less, Stylus or CSS modules to better manage large scale projects.

### AI Collaboration

This challenge helped me learn how to use AI tools for brainstorming solutions, debugging and code completions.
Some of the tools I used include:

- **GitHub Copilot**: Improved my efficiency by offering intelligent code completion.
- **Google Gemini**: Provided guidance on professional documentation standards.

## Author

- Patrick Cheruiyot Kirui- [Portfolio Website](https://pc-kirui.github.io/)
- Frontend Mentor - [@Pc-Kirui](https://www.frontendmentor.io/profile/Pc-Kirui)
- X (Twitter) - [@PcKirui](https://x.com/PcKirui)
