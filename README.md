# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Toggle the mobile menu (requires some JavaScript)

### Screenshot

Desktop

![](/images/fm_news_hompage_desktop.png)

Mobile

![](/images/fm_news_hompage_mobile.png)

Mobile Menu

![](/images/fm_news_hompage_mobile_menu.png)

## My process

### Built with

- Mobile-first workflow
- Flexbox
- CSS Grid
- SASS

### What I learned

I have learned a new HTML tag which is `<picture>`, where I can specify the image I will use for the mobile based on the screen size.

```html
<picture>
  <source media="(max-width: 650px)" srcset="images/image-web-3-mobile.jpg" />
  <img src="images//image-web-3-desktop.jpg" alt="image" />
</picture>
```

## Author

- Frontend Mentor - [@aalmuqahwi](https://www.frontendmentor.io/profile/aalmuqahwi)
