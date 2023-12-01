# Frontend Mentor - QR code component solution
## Table of contents
- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned (Reflection)](#what-i-learned)

## Overview
This is my attempt at the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) - a place with a ton of web development & design challenges. In fact, this is my first challenge.

### Links
- Link: [View webpage here]([https://your-live-site-url.com](https://geoffsg.github.io/qr-code-component-main/))

## My process
### Built with
- HTML5
- CSS; SASS/SCSS
- Flexbox

### What I learned (Reflection)
Nothing really new to me. I thought I'd go for something simple to practice, and to get started with the platform. For this, I wanted to practice creating a simple container component that I could potentially use in future projects.

I also wanted to experiment with the Flexbox, by creating a "wrapper" container to centre the showcase (the QR container). Then I added the header and footer bars to snap to the top and bottom edges. Snapping the footer the way I did isn't something I'd typically do, especially for the longer pages. For this challenge, however, I thought its a nice way to stage the QR Container.

```html
<div class="wrapper">
  <header>
      ...
  </header>
  <div class="container qr">
    ...
  </div>
  <footer>
    ...
  </footer>
</div>
```
```css
.wrapper {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100vh;
}
```

By setting `.warpper` to flex with `justify-content: space-between` centres the container, while snapping the header & footer. Another important piece is the `height: 100vh` which sets the size of the `.wrapper` to the `viewport height`. Finally, `flex-direction: column` otherwise the header and footer would be sidebars instead.

This was fun. I even played around with maps using SASS/SCSS. Again, mostly as practice, though perhaps an over-engineer for such a small challenge like this.

