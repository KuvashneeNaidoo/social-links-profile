# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [SCSS Setup](#scss-setup)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

Users should be able to interact with the page and see hover and focus states for all clickable or interactive elements.

### Screenshot

![social-links-profile-kuvashnee-naidoo](https://github.com/user-attachments/assets/8e50929e-169c-410b-8322-8031fbbd672f)

### Links

- [Solution URL](https://github.com/KuvashneeNaidoo/social-links-profile)
- [Live Site URL](https://social-links-profile-kuvashnee.netlify.app/)

## My process

### Built with

- HTML5
- SCSS
- Flexbox
- Media queries

### SCSS Setup

In order to use SCSS, you need to ensure you have a SASS compiler installed. Here are a few steps to set it up and generate the CSS:

1. Install SASS via npm in the terminal:
```
npm install -g sass
```

2. Run SASS to generate the CSS:
```
sass scss/style.scss css/style.css
```

### What I learned

While working on this project, I learned how to use SCSS to nest selectors, making the styles more structured and readable. "&" can also be used inside nested selectors for pseudo-classes like :hover and :active.

```scss
.avatar {
  height: 94px;
  width: 94px;
  border-radius: 50%;
  border: 2px solid var(--Primary-color);
  transition: transform 0.3s ease;
  object-fit: cover;

  &:hover {
    transform: scale(1.1); 
  }
}

```

SCSS also helped to support variables to store reusable values like colors and fonts.

```scss
@font-face {
  font-family: Inter-Regular;
  src: url(../assets/fonts/static/Inter-Regular.ttf);
}

:root {
  --Primary-color: hsl(260, 60%, 50%);
  --Secondary-color: hsl(180, 70%, 40%);
  --Neutral-White: hsl(0, 0%, 95%);
  --Neutral-Grey: hsl(220, 10%, 50%);
  --Neutral-darkGrey: hsl(220, 10%, 25%);
  --Accent-color: hsl(220, 25%, 15%);
  --Background-color: hsl(220, 25%, 15%);
}
```

### Continued development

I will continue to focus on improving my SCSS skills by diving deeper into mixins to define styles that can be re-used throughout the stylesheet.
This could be a valuable resource worth following in the future: [SASS Documentation](https://sass-lang.com/documentation/at-rules/mixin/) 

### Useful resources

- [SASS Documentation](https://sass-lang.com/) - This resource helped me install and set up SASS and learn the basics of SCSS to improve the organisation and readability of the styles in the stylesheet.

## Author

- [Website](https://kuvashnee-naidoo-portfolio.netlify.app/)
- [Frontend Mentor](https://www.frontendmentor.io/profile/KuvashneeNaidoo)
- [Twitter](https://x.com/kuvashnee)
