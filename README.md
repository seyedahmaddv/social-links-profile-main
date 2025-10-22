# Social links profile solution


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
- [Author](#author)

## Overview

### The challenge

Users should be able to:
- See hover and focus states for all interactive elements on the page
- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![Project Screenshot Desktop](/design/destkop-design.jpg)

![Project Screenshot Mobile](/design/mobile-design.jpg)

![Project Screenshot Active States](/design/active-states.jpg)


### Links

- Live Site URL: [Live Site](https://social-links-profile-main2.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- CSS Variables
- Custom Font Implementation

### What I learned

During this project, I focused on creating a clean, responsive design using CSS variables for consistent theming. I implemented hover states for interactive elements and worked with custom fonts to achieve the desired visual style.

```html
<div class="profile-card">
  <img src="/assets/images/seyed-ahmad-gholami.webp" alt="Seyed Ahmad Gholami" class="profile-img" />
  <h1 class="profile-name">Seyed Ahmad Gholami</h1>
  <p class="profile-location">London, United Kingdom</p>
  <p class="profile-bio">"Front-end developer and avid reader."</p>
  <!-- Social links -->
</div>
```

```css
:root {
  --green: hsl(75, 94%, 57%);
  --white: hsl(0, 0%, 100%);
  --grey-700: hsl(0, 0%, 20%);
  --grey-800: hsl(0, 0%, 12%);
  --grey-900: hsl(0, 0%, 8%);
}

.social-link:hover {
  background-color: var(--green);
  color: var(--grey-900);
}
```

### Continued development

In future projects, I plan to:
- Enhance my CSS animations and transitions
- Explore more advanced responsive design techniques
- Implement accessibility best practices
- Work with CSS Grid for more complex layouts

### Useful resources

- [CSS Variables Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - This helped me implement a consistent color scheme using CSS variables.
- [Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - An excellent resource for understanding Flexbox layout.
- [Web Font Implementation](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face) - This article helped me implement custom fonts properly.

## Author

- Website - [Seyed Ahmad Gholami](https://seyedahmadgholami.ir)
- GitHub - [seyedahmaddv](https://github.com/seyedahmaddv/)
- LinkedIn - [seyedahmaddv](https://linkedin.com/in/seyedahmaddv)
- Dev.to - [seyedahmaddv](https://dev.to/seyedahmaddv)
