# FEM-QRCode
Frontend Mentor QR Code Challenge

# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
- [Screenshot](#screenshot)
- [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Screenshot

[https://i.imgur.com/16QAjsy.png]

### Links

- Solution URL: [https://github.com/Qi-lang959/FEM-QRCode]

## My process

I initially decided to encase each element in a div and reference it in css with the parent first. 
But later I found out that wasn't always necessary, as I could just reference the tag I used directly without having to involve the parent 
(e.g.: p {} instead of  .my-container p {}). 

However, I'm not exactly sure why that is yet. 

After I finished building most of the structure in HTML and CSS, I moved on to fixing the repsonsiveness, 
as resizing the window (even when using width, min-width, and max-width) continually caused overflow issues and squishing in my containers. 

Luckily, I found out about flex-shrink, and it solved all of my remaining problems. 

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

I learned about the use of flex-shrink. Originally, no matter how many different configurations I tried 
and places to put it, width, min-width, and max-width refused to work. 

Why? Honestly, I don't know. 

It goes to show how much more I have yet to learn. :)

### Continued development

At the moment, I really just want to continue refining the basics of HTML/CSS. I don't have a robust understanding of inheritance yet. 
Nor do I know completely how to structure the body of an HTML document using semantic tags.

## Author

- Frontend Mentor - [@Qi-lang959](https://www.frontendmentor.io/profile/Qi-lang959)

## Acknowledgments

Shoutout to this guy (https://stackoverflow.com/a/44137356) who presented 
an alternate solution to someone else's problem, because it helped me with mine.
