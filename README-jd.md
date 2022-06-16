# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

images/screenshot.png


### Links

- Solution URL: https://github.com/jdisenso/qr-code-component/blob/main/README-jd.md
- Live Site URL: https://jdisenso.github.io/qr-code-component/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

At first, this looked like a pretty easy problem to solve. I estimated an hour, but likely thirty minutes. 

Since this was not part of an entire website, I wanted to keep the code lean. I first worked through the html and laid out the needed structure. Then I began to write the css to style the webpage. 

Since I am working on a free account, I don't have access to the Figma and Sketch files. I opened up Photoshop and examined the elements to determine the intended sizes. After finding widths and border-radius, I was ready to get started with the other details laid out in the style guide.

The second problem I needed to solve was the vertical alignment for all devices. I worked through a few Google and StackOverflow entries, but in the end I went to Devdocs.io to learn Flexbox. After understanding the layout parameters, I was able to engineer a solution with the addition of a height: 100vh on the .wrap div.

Finally, I wanted to make sure the design looked good on mobile devices, so I added some padding to ensure the design would stay intact on devices smaller than 320 pixels. This caused me to measure the final project, which I found was wider than the original design. I solved this by subtracting the padding from the max-width.

### Useful resources

- [Devdocs.io - Flexbox](https://devdocs.io/css/css_flexible_box_layout/aligning_items_in_a_flex_container) - This really helped me understand how to solve the vertical alignment issue. 


## Author

- Website - [Jason DiSenso](https://puremediagraphics.com)
- Frontend Mentor - [@jdisenso](https://www.frontendmentor.io/profile/jdisenso)
- Twitter - [@jadisenso](https://www.twitter.com/jadisenso)

## Acknowledgments

Thankful for the help of those on StackOverflow that offered help 7-8 years ago. Although they didn't directly help, they did put me on the right track to Flexbox.
