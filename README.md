# Frontend Mentor - Typemaster pre-launch landing page solution

This is a solution to the [Typemaster pre-launch landing page challenge on Frontend Mentor](). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Integrate the design files for Desktop/tablet/mobile views.

### Screenshot

![](./preview.jpg)

### Links

- Solution URL: [Solution Page](https://www.frontendmentor.io/solutions/typemaster-page-htmlsass-O0Q-xpjxB)
- Live Site URL: [Live site](https://rayanebengaoui.github.io/FM_challenge18_Typemaster_LandingPage/)

## My process

This site was made with a mobile first approach.

### Built with

- Semantic HTML5 markup
- SASS
- Parcel

### What I learned

During this challenge I have learned a few things such as :

Using the picture tag to generate images based on the screen size.

```html
<picture>
  <source
    srcset="./assets/desktop/image-keyboard.jpg"
    media="(min-width: 1000px)"
  />
  <source
    srcset="./assets/tablet/image-keyboard.jpg"
    media="(min-width: 700px)"
  />
  <img src="./assets/mobile/image-keyboard.jpg" alt="keyboard" />
</picture>
```

New features of SASS with @use instead of the deprecated @import.

```scss
@forward "variables";
@forward "mixins";
```

The mix-blend-mode CSS property to modify the color of a child container with its parent.

```css
img {
  mix-blend-mode: multiply;
}
```

Lastly, I have used Parcel to bundle my app and watch my app so I could use the latest dart SASS features.

## Author

- Website - [Rayane Bengaoui](https://rayanebengaoui.com/)
- Frontend Mentor - [@RayaneBengaoui](https://www.frontendmentor.io/profile/RayaneBengaoui)
