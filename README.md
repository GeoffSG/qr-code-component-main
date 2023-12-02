# Frontend Mentor - QR code component solution
## Table of contents
- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned (Reflection)](#what-i-learned)
    - [The Colors](#the-colors)
- [Conclusion](#conclusion)

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

This was a fun, small and simple challenge to get myself started. It was good practice.

#### The Colors
Something I will share is how I got the colors. I used the [Tailwind CSS
Color Generator](https://uicolors.app/create) to create the colours. I did put this into a color map, but I removed this as I felt it was too much for this small project. So instead I just selected the "50" and "950" shades of the blue I chose as black and white. Then a shade for the background for the QR container.

This was so I can practice in designing a page within a custom scheme I've came up with. I think the colours work well together, even the dark grey though finding a way to have that to match more would be great.

## Conclusion
This challenge was fun. I look forward to taking on others and learning more. At the time of completing this (02/12/2023) I'm focusing on HTML and CSS with SASS/SCSS. I find CSS hard at times, therefore I need practice and it seems [Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) is a good place for that.

Thanks if you've made it this far. :)
